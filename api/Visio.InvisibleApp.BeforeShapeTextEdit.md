---
title: InvisibleApp.BeforeShapeTextEdit event (Visio)
ms.prod: visio
api_name:
- Visio.InvisibleApp.BeforeShapeTextEdit
ms.assetid: 6d07daf2-bb95-802e-57a8-5436236dd4d6
ms.date: 06/25/2019
ms.localizationpriority: medium
---


# InvisibleApp.BeforeShapeTextEdit event (Visio)

Occurs before a shape is opened for text editing in the user interface.


## Syntax

_expression_.**BeforeShapeTextEdit** (_Shape_)

_expression_ A variable that represents an **[InvisibleApp](Visio.InvisibleApp.md)** object.


## Parameters

|Name|Required/Optional|Data type|Description|
|:-----|:-----|:-----|:-----|
| _Shape_|Required| **[IVSHAPE]**|The shape that is going to be opened for text editing.|

## Remarks

If you are using Microsoft Visual Basic or Visual Basic for Applications (VBA), the syntax in this topic describes a common, efficient way to handle events.

If you want to create your own **Event** objects, use the **[Add](visio.eventlist.add.md)** or **[AddAdvise](visio.eventlist.addadvise.md)** method. 

To create an **Event** object that runs an add-on, use the **Add** method as it applies to the **EventList** collection. 

To create an **Event** object that receives notification, use the **AddAdvise** method. 

To find an event code for the event that you want to create, see [Event codes](../visio/Concepts/event-codesvisio.md).

[!include[Support and feedback](~/includes/feedback-boilerplate.md)]