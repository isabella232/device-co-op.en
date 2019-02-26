---
description: Learn how to use Device Co-op data in Adobe Target activities.
seo-description: Learn how to use Device Co-op data in Adobe Target activities.
seo-title: Target - A/B tests, multivariate tests, and experience targeting
title: Target - A/B tests, multivariate tests, and experience targeting
uuid: c1b478a4-812e-41ee-913f-29666c5c7ec4
index: y
internal: n
snippet: y
---

# Target - A/B tests, multivariate tests, and experience targeting{#target-a-b-tests-multivariate-tests-and-experience-targeting}

Learn how to use Device Co-op data in Adobe Target activities.

You can use Device Co-op data in A/B tests, multivariate (MVT) tests, and experience targeting activities. The Device Co-op option is available during activity creation on the [!DNL Goals & Settings] page in the [!DNL Target] three-step guided workflow.

You cannot use Device Co-op data in Automated Personalization activities, Recommendation activities, or activities using [!DNL Adobe Analytics] as the reporting source (the [!DNL Target] and [!DNL Analytics] integration, known as A4T).

>[!NOTE]
>
>Ensure that you have the required version of `mbox.js`. You can use any version of `at.js`. For more information, see [Membership Requirements](../mcdc-about/mcdc-requirements.md#concept-31d3d165d22546afbedf023d32ad3a43).

## Deliver relevant content regardless of the device {#section-bba8d41e96914c82a6d267a54f776354}

Marketers want to deliver the most relevant experience to each visitor, regardless of the device the visitor is currently using to interact with their company or brand.

Users interact with the same company or brand from many different devices: work laptops, home computers, iPads, iPhones, various browsers, and so forth. If you can’t recognize that each specific device or browser is being used by the same person who has previously interacted with your brand on another device or browser, you can’t deliver a consistent and targeted experience to that person.

With the Device Co-op, a user’s various devices can be identified as being used by the same user. When that user sees a page with [!DNL Target] activities—either activities or targeted content— [!DNL Target] can ensure that the user sees the same experience seen on another device.

## Analyze Target activities by people instead of by visitors {#section-c25cf4f8483942d7836d60756235e62c}

Marketers want to analyze [!DNL Target] activities by “people” instead of “visitors.”

Each person is likely interacting with the same company or brand across devices and browsers, but without the Device Co-op, each individual device or browser is considered a separate “visitor” in [!DNL Target] reports.

Viewing reports by individual devices and browsers inflates the “visitor” count to a higher number than the number of different people interacting with the company or brand. These people typically convert only once across these various devices and browsers, so the conversion rate will be lower than in reality because more “visitors” will be counted for a single conversion.

With the Device Co-op, content delivery and reporting is done at the “people” level, so the reports accurately show how many different people saw the activity and how many of the people converted.

Without Device Co-op data, you might determine that a particular activity is the winner; however, because reporting is more accurate with the Device Co-op, another activity might actually have a higher conversion rate, and, therefore, be the winner.

For more information on this concept, see [Analytics: People Metric](../mcdc-other-solutions/mcdc-people.md#concept-8c57cd3904974e078d7fbf84ac9c2d63).

## Use Device Co-op data per activity {#section-fb46fae482654023abb1a1e26564db9a}

Marketers can choose to use the Device Co-op data per activity. Certain [!DNL Target] activities might not be appropriate for Device Co-op data, such as:

* Specific content appropriate for users on an iPad.

  Users who first view an experience on an iPad, will continue to see that experience on their home computers. 

* An interest rate offer available only for a strict segment of visitors. 
* Products allowed to be advertised only in a specific state (for example, an insurance policy with license restrictions).

When marketers create audiences in [!DNL Target], they are alerted if the audience is not appropriate for Device Co-op data-enabled activities. Appropriate audiences include all visitors, new visitors, and returning visitors. 
