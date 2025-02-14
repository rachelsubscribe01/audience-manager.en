---
description: Frequently asked questions about the Audience Lab feature.
seo-description: Frequently asked questions about the Audience Lab feature.
seo-title: Audience Lab FAQ
solution: Audience Manager
title: Audience Lab FAQ
uuid: b1daf99d-af60-4f65-987d-794a6d45d566
feature: Audience Lab
exl-id: 25bdabb5-2ba8-45d2-81ca-05c0590d7d96
---
# Audience Lab FAQ{#audience-lab-faq}

Frequently asked questions about the Audience Lab feature.

<!-- 

audience-lab-faq.xml

 -->

<br>&nbsp;

**Do the test segments created in the test groups have different segment IDs? How do I map the IDs to different destinations?**

Yes, the test segments have different segment IDs. For destinations with [!UICONTROL Auto-fill Destination Mapping] or segments sent to [!DNL Google], [!UICONTROL Audience Lab] will handle the mapping values just like the destinations normally would.

<br>&nbsp;

**Can the same conversion trait be associated with multiple test groups?**

Yes, this is allowed. Think of a case of one test using a male segment associated to conversion X and one test using a female segment associated to conversion X. It doesn't matter that both tests are driving conversions since they are testing two different audiences.

<br>&nbsp;

**Let's say a test group is using an authenticated profile for the test segment split. The authenticated profile is linked to 4 [Audience Manager UUIDs](../reference/ids-in-aam.md). When the visitor exhibits a conversion trait from one of the four UUIDs, does [!UICONTROL Audience Lab] count this as one or four conversions?**

In this case, [!UICONTROL Audience Lab] only counts one conversion.

<br>&nbsp;

**What if the visitor from the case above first exhibits the conversion trait from one of the four UUIDs linked to their authenticated profile and then also exhibits the conversion trait from two other UUIDs linked to the authenticated profile? Does this case count as one or three conversions?**

In this case, [!UICONTROL Audience Lab] counts three conversions, one for each device that has exhibited the authentication trait.

<br>&nbsp;

**Can a user have [!UICONTROL Segment: Read-Only] access, yet also [!UICONTROL Audience Lab] test segment creation access?**

See [Create Segment Test Group](../features/audience-lab/audience-lab-manage-test-groups.md#create-test-groups) for information on how to use [!UICONTROL Audience Lab] with [!UICONTROL RBAC] privileges.

**Can I use [!UICONTROL Audience Lab] in conjunction with the [!UICONTROL Profile Link Device Graph] and External Device Graphs ([Adobe Experience Cloud Device Co-op](https://experienceleague.adobe.com/docs/device-co-op/using/home.html), Tapad Device Graph, Liveramp Device Graph)?**

For now, [!UICONTROL Audience Lab] can only split out segment populations by the devices connected to a qualifying device, when using the [!UICONTROL Profile Link Device Graph]. We are working on adding support in [!UICONTROL Audience Lab] for the other device graphs and will let you know when we do so.
