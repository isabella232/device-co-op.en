---
description: When a person has devices that are not used to interact with your brand, those devices are called unknown devices.
seo-description: When a person has devices that are not used to interact with your brand, those devices are called unknown devices.
seo-title: Unknown devices
title: Unknown devices
uuid: 18e69dad-bdb3-4ac1-a690-374aba1aa0a6
---

# Unknown devices{#unknown-devices}

When a person has devices that are not used to interact with your brand, those devices are called unknown devices.

## Unknown device categories {#section-014b83fd0f2e4d50aa19dd9fbb46f6ab}

There are several ways or categories by which a device may be considered "unknown" to you. These include:

* **First-party visits to other Device Co-op members:** Visits to other [!DNL Device Co-op] member sites or advertising to a device does not, by itself, make a device known to your brand. 

* **Not tracked ad inventory:** Advertising inventory that is available, but not yet served or ingested does not make a device known to your brand. 
* **Consumer opt-out:** To respect consumer desire, devices that have been opted-out are not considered known devices.

Unlike known devices, unknown devices are not linked to other devices or associated with individual people.

## Rules for setting known/unknown status {#section-fa5c85e59e2d4f88bb79f27f17f02344}

The [!DNL Device Graph] tries to be inclusive as possible when classifying devices as known compared to unknown. The rules that help determine known/unknown status work in priority order (1 is highest) as shown below:

* **Rule 1:** Is the device opted-out? If yes, then the device is unknown. 
* **Rule 2:** Is the device known by *any* method? If yes, then the device is known. 

* **Rule 3: ** If the previous do not apply, the device is unknown.

>[!MORELIKETHIS]
>
>* [Known Devices](../processes/known-device.md#concept-8e87c276819a48bfac5cef10b45216d1)
