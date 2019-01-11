---
title: "keyValue resource type"
description: "Key Value definition."
author: "tfitzmac"
localization_priority: Normal
ms.prod: "intune"
---

# keyValue resource type

> **Important:** APIs under the / beta version in Microsoft Graph are in preview and are subject to change. Use of these APIs in production applications is not supported.

> **Note:** Using the Microsoft Graph APIs to configure Intune controls and policies still requires that the Intune service is [correctly licensed](https://go.microsoft.com/fwlink/?linkid=839381) by the customer.

Key Value definition.
## Properties
|Property|Type|Description|
|:---|:---|:---|
|key|String|Key.|
|value|String|Value.|

## Relationships
None
## JSON Representation
Here is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.keyValue"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.keyValue",
  "key": "String",
  "value": "String"
}
```




