---
title: "getState (Client API reference) in model-driven apps| MicrosoftDocs"
description: Includes description and supported parameters for the getState method.
ms.author: jdaly
author: adrianorth
manager: kvivek
ms.date: 03/12/2022
ms.reviewer: jdaly
ms.topic: "reference"
applies_to: "Dynamics 365 (online)"
search.audienceType: 
  - developer
search.app: 
  - PowerApps
  - D365CE
contributors:
  - JimDaly
---
# getState (Client API reference)

Returns the state of the timer control.

This method is only supported for [Unified Interface](/dynamics365/get-started/whats-new/customer-engagement/new-in-july-2017-update#unified-interface-framework-for-new-apps). 

## Control types supported

Timer

## Syntax

`formContext.getControl(arg).getState();`

## Return Value

**Type**: Number

**Description**: Returns one of the following values:

|Value | State |
|--|--|
|1 | Not Set|
|2 | In progress|
|3 | Warning|
|4 | Violated|
|5 | Success|
|6 | Expired|
|7 | Canceled|
|8 | Paused|

### Related topics

[Controls](../controls.md)


[!INCLUDE[footer-include](../../../../../includes/footer-banner.md)]