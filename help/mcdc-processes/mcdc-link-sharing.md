---
description: About link sharing in the Device Graph.
seo-description: About link sharing in the Device Graph.
seo-title: Link sharing in the Device Graph
title: Link sharing in the Device Graph
uuid: 6c7202f0-c6d9-48a4-82ad-ee57d7a518a0
index: y
internal: n
snippet: y
---

# Link sharing in the Device Graph{#link-sharing-in-the-device-graph}

About link sharing in the Device Graph.

The [!DNL Device Graph] shares deterministic and probabilistic links with different members of the Adobe Experience Cloud Device Co-op. Link sharing is what makes the [!DNL Device Co-op] so powerful. It extends what each member knows about the devices associated with an anonymous person, but only if you've seen at least one of the devices of that anonymous person before.

## Device Graph summary review {#section-7858e9f61b5644c981ffb53626fcc19d}

Before getting started, let's take a moment to review how the [!DNL Device Graph] works. Members of the [!DNL Device Co-op] send data to the [!DNL Device Graph]. The [!DNL Device Graph] uses this data to construct a person's identity from [deterministic and probabilistic links](../mcdc-processes/mcdc-links.md#concept-58bb7ab25f904f5f98d645e35205c931) between devices. As a [!DNL Device Co-op] participant, these links provide insight about the relationship between your authenticated users, other users, and their devices. Let's take a look at how this works in the section below.

## Link sharing example {#section-cb410d827cf14f76bc9b0bd4d31ed767}

The following example demonstrates the power of link sharing in the Device Co-op. In this example, we have 2 fictitious companies, the News Company and the Finance Company. Both companies are members of the [!DNL Device Co-op]. Person A is a consumer who either logs on or browses the websites of each company from multiple devices.

![](assets/share1.png)

Because Person A has authenticated to the news site with their mobile phone and tablet, the News Company identifies them with a consumer ID. It sends that ID to the [!DNL Device Graph] as a cryptographic hash. The Finance Company has seen these devices before, but Person A hasn't logged on to the site. Consequently, the Finance Company does not know if or how these devices relate to each other or how they are associated with Person A.

![](assets/share2.png)

Given the cryptographic hash of the consumer ID, the [!DNL Device Graph] recognizes that these devices are related to each other and a particular person. To companies that do not participate in the [!DNL Device Co-op] these site visits would appear to come from separate, random devices. In any case, once the [!DNL Device Graph] has the hashed ID it:

* Knows mobile phone and laptop are linked. 
* Recognizes that the Finance Company wants to know if the mobile phone and laptop are linked.

Given these conditions, the [!DNL Device Graph] now shares the link connecting these devices for the News Company with the Finance Company. During this process, the [!DNL Device Graph] duplicates and shares the link from one co-op member to another.

![](assets/share3.png)

At this point, the [!DNL Device Graph] performed its role successfully. Both the News Company and the Finance Company have a clear picture of an identity. They can reach Person A accurately across all their devices.

## Privacy and link sharing {#section-7b566018b3304420a4b3e4c079826110}

Maintaining consumer privacy and data integrity for [!DNL Device Co-op] members is crucial throughout the link sharing process. During this customer identification and link sharing process the [!DNL Device Graph] did not:

* Tell the Finance Company that the link came from the News Company. 
* Share the customer ID used by one [!DNL Device Co-op] member with another. 
* Provide any information other than that the mobile device and laptop share a link in common.

## Next steps {#section-ac6e61f1eb6e45b1bb4be8ece39147c7}

Reading the documentation on identity, linking, and link sharing should give you a good sense of how the [!DNL Device Graph] assembles data internally. As a next step, we recommend taking a look at our documentation that describes how the concept of a *`known device`* delivers cross-device links to Device Co-op members. See [Known Devices](../mcdc-processes/mcdc-known-device.md#concept-8e87c276819a48bfac5cef10b45216d1) and [Unknown Devices](../mcdc-processes/mcdc-unknown-device.md#concept-95090d341cdc4c22ba4319d79d8f6e40). 
