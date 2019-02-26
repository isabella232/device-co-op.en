---
description: Descriptions and answers to common questions about the Identity Services Cooperative and the Identity Graph.
seo-description: Descriptions and answers to common questions about the Identity Services Cooperative and the Identity Graph.
seo-title: FAQ
title: FAQ
uuid: 490566e1-4d35-468c-8389-678f9ff02cc8
index: y
internal: n
snippet: y
---

# FAQ{#faq}

Descriptions and answers to common questions about the Identity Services Cooperative and the Identity Graph.

**What is the [!DNL Device Co-op]?**

The Device Co-op is a digital cooperative for participating Adobe Experience Cloud customers to work together to better identify their consumers across devices.

**What technologies are used in the Device Co-op?**

The Device Co-op consists of two technologies:

* **Experience Cloud ID Service:** This core service of the Adobe Experience Cloud provides a common ID for identifying consumers consistently across solutions, channels, experiences, and devices. 
* **Adobe Experience Cloud Device Co-op:** This technology links different devices used by a consumer or household.

**How does the [!DNL Device Co-op] work?**

As brands pitch in their piece of the of the cross-device puzzle through anonymized logins and site visits, Adobe processes this data to form device clusters which represent a group of devices used by an unknown person. These device clusters are given to Device Co-op members, and used to provide their consumers with a better, more consistent cross-device experience.

**How does the [!DNL Device Co-op] link devices?**

See [Deterministic and Probabilistic Links](mcdc-processes/mcdc-links.md#concept-58bb7ab25f904f5f98d645e35205c931).

**What data do participants provide [!DNL Adobe]?**

See [Consumer Opt-Out Tool, Privacy, and the Device Graph](mcdc-privacy.md#concept-fa1346e6b95a484eaeafc9bebe3cd6be).

**What data is shared between [!DNL Device Co-op] members?**

See [Link Sharing in the Device Graph](mcdc-processes/mcdc-link-sharing.md#concept-7168053105a94649a3f092d375d79eaf).

<!--
Removed at Asa's request.
<p><b>What does <span class="keyword"> Adobe </span> see via the <span class="wintitle"> Device Graph </span>?</b> </p>
<p>Adobe can see which devices are most likely being used by the same person, using probabilistic and deterministic device graph algorithms. This match between a group of devices and a person is really two numbers that are linked to each other. One number represents a group of devices believed to belong to the same person while the other number represents a person. Adobe makes this linked device information available to consumers as well, so they can correct misinformation and/or opt-out one or all devices from the Device Co-op. </p>
-->

**Can a [!DNL Device Co-op] member see links to devices they have never seen before?**

No. Device Co-op members can only gain data based on devices that have visited one of their brand’s web properties. See [Known Devices](mcdc-processes/mcdc-known-device.md#concept-8e87c276819a48bfac5cef10b45216d1) and [Unknown Devices](mcdc-processes/mcdc-unknown-device.md#concept-95090d341cdc4c22ba4319d79d8f6e40).

**Will I need to share any of my company's marketing information?**

No. Brands only supply anonymous device data to Adobe.

**Does [!DNL Adobe] use personally identifiable information (PII) in the [!DNL Device Co-op]?**

No. All personally identifiable information is hashed before it’s brought into any Adobe system, so your customer’s information is never transferred to Adobe systems.

**Do smaller brands who contribute less device data to the Device Co-op get more value than what they put in, compared to their larger counterparts?**

No. All members of the Cooperative get back value relative to what they put in. For instance, if a brand contributes 10,000 devices they will be able to receive additional linked device information associated with those 10,000. Looking at the big picture, this contribution may seem minimal; but as more and more brands of all sizes join, the aggregated contribution is significant, and will provide the missing link for many devices that many other, perhaps larger, brands are looking for. See [Fairness and the Known Device](mcdc-processes/mcdc-known-device.md#section-0543188729d845d6b95db70b8b25e9f8).

**How will [!DNL Adobe] manage IP addresses if some countries consider an IP address as personal information?**

The Device Co-op is first being released in the United States and Canada where IP address is not considered to be personal information. When the Cooperative is released in countries where IP address is considered to be personal information, the IP address will not be used. 
