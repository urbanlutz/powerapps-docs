---
title: "getPrecision (Client API reference)| MicrosoftDocs"
description: Includes description and supported parameters for the getPrecision method.
ms.author: jdaly
author: adrianorth
manager: kvivek
ms.date: 03/12/2022
ms.reviewer: jdaly
ms.topic: "reference"
applies_to: "Dynamics 365 (online)"
ms.subservice: mda-developer
search.audienceType: 
  - developer
search.app: 
  - PowerApps
  - D365CE
contributors:
  - JimDaly
---
# getPrecision (Client API reference)



Returns the number of digits allowed to the right of the decimal point. 

## Column types supported

Money, decimal, double, and integer

## Syntax

`formContext.getAttribute(arg).getPrecision()`

## Return Value

**Type**: Number. 

**Description**: The number of digits allowed to the right of the decimal point.

### Related topics

[setPrecision](setPrecision.md)



[!INCLUDE[footer-include](../../../../../includes/footer-banner.md)]