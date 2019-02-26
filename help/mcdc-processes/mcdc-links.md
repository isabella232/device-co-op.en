---
description: How the Device Graph analyzes deterministic and probabilistic data to build a map that links devices together.
seo-description: How the Device Graph analyzes deterministic and probabilistic data to build a map that links devices together.
seo-title: Deterministic and probabilistic links
title: Deterministic and probabilistic links
uuid: 00693a0a-f73d-460d-84a4-b7c745b9fe0a
index: y
internal: n
snippet: y
---

# Deterministic and probabilistic links{#deterministic-and-probabilistic-links}

How the Device Graph analyzes deterministic and probabilistic data to build a map that links devices together.

In the [!DNL Device Graph], internal processes build an identity hierarchy that maps devices and connects them to individual, anonymized people. The output of the graph includes cross-device links you can use for targeting along with data exposed in select Experience Cloud solutions. The Adobe solutions that work with [!DNL Device Graph] data include Analytics, Audience Manager, Media Optimizer, and Target.

The [!DNL Device Graph] analyzes deterministic and probabilistic data to build a map that links devices together. Deterministic data links devices together based upon hashed logon information. Probabilistic data links devices together based on information such as IP addresses and other metadata. The [!DNL Device Graph] associates the linked device clusters to an anonymous individual person These connections let digital marketers reach people instead of devices. In the [!DNL Device Graph], the owner of a device is the anonymous representation of a real-life person. Both deterministic and probabilistic links help build a structure of user identity.

>[!NOTE]
>
>In the Adobe Experience Cloud Device Co-op, terms such as *device*, *person*, and *identity* have specific meanings. For example, *device* can refer to physical hardware such as a phone or tablet and the applications that run on that hardware. See the [glossary](../mcdc-glossary.md#glossgroup-0f47d7fbd76c4759801f565f341a386c) for definitions.

## What are links? {#section-2df4c6f01eba49369993146df0661f13}

When we talk about links, it's important to keep in mind what these really are in the context of the [!DNL Experience Cloud] Device Graph. In this context, links are not physical connections between devices. Instead, a link is how the Device Graph associates different devices to the same, unknown person. For example, say we have a mobile phone and a desktop browser. The phone and the browser can be considered "linked" once the Device Graph determines both these devices are used by the same, unknown person. As you'll read below, the Device Graph builds identities with deterministic and probabilistic links. And, in the Device Graph, the owner of a device is the anonymous representation of a real-life person.

## Deterministic links {#section-33d41e828a674b398e36fe63da20ac09}

Deterministic links associate a device to a person based on an authentication event (e.g., a log in action to a site from a device). This action creates an anonymized identifier known as a consumer ID. Let's take a look at how deterministic linking works. In this example, Person A logs in to a news site through an app on their mobile device. Later that day, Person A again logs on, but this time through a browser on their laptop.

![](assets/link1.png)

Based on the logon information, the Device Graph:

* Knows that Person A authenticated to the news site with a mobile phone/app and laptop/browser device combination. 
* Links these devices to Person A. 
* Builds an identity based on linked devices associated with an anonymous person.

![](assets/link2.png)

>[!NOTE]
>
>Neither the [!DNL Adobe Experience Cloud Device Co-op] or the [!DNL Device Graph] receives actual authentication information or personally identifiable information (PII) in this data. Members of the [!DNL Experience Cloud Device Co-op], pass in cryptographically hashed, unique consumer IDs to the Device Graph. The consumer ID represents an authenticated user in the graph and protects consumer privacy.

## Probabilistic links {#section-5f5aa755da984f9d851f7cb380262998}

Probabilistic links connect a device to a person algorithmically, based on characteristics and metadata such as:

* Browsing behavior 
* IP addresses 
* Operating systems 
* IDFA and GAID identifiers

Let's take a look at how probabilistic linking works. In this example, Person A browses to a news site on their tablet and then later from a desktop computer. While browsing, Person A does not log on to the news site. During each separate visit, the tablet and desktop share the same IP address.

![](assets/link3.png)

Based on this information, the [!DNL Device Graph] evaluates IP address sharing patterns between both devices and links these devices together if the results suggest they belong to Person A. The end result is hierarchy of identity derived from algorithmic probability calculations.

![](assets/link4.png)

In this example, the Device Graph linked both devices after they were used to access the same news site. But, devices do not have to be seen on the same site to be linked. To illustrate this point, let's say each device in this example visits completely different websites. The [!DNL Device Graph] algorithm can still make a probabilistic link based on their shared IP address and from an analysis of other data. This process is what helps make probabilistic linking so powerful for members of the [!DNL Experience Cloud] Device Co-op.

## Both types of data provide value {#section-43d22d8c10634edcb261e7bda6fdf323}

Deterministic and probabilistic data compliment each other. By contrast, a device graph that only includes deterministic data gives you a limited view of a person's identity. Without authentication, a device graph cannot tell you about other devices and people who browse your site. Probabilistic data can make these connections and help you reach unauthenticated devices, people, and households.

However, deterministic data is important too. It can, for example, improve probabilistic decision making by removing false links generated in places where probabilistic signals are plentiful and overlapping (e.g., coffee shops, libraries, airports, etc.).

With both types of data, the Device Graph gives you a more comprehensive picture of a person's identity than with either type alone.

![](assets/link5.png)

