---
title: SpreadsheetShapeSettings
second_title: GroupDocs.Watermark for Java API Reference
description: Represents settings that can be applied to a shape watermark for an Excel document.
type: docs
weight: 54
url: /java/com.groupdocs.watermark.options/spreadsheetshapesettings/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.OfficeShapeSettings](../../com.groupdocs.watermark.contents/officeshapesettings)
```
public final class SpreadsheetShapeSettings extends OfficeShapeSettings
```

Represents settings that can be applied to a shape watermark for an Excel document.
## Constructors

| Constructor | Description |
| --- | --- |
| [SpreadsheetShapeSettings()](#SpreadsheetShapeSettings--) | Initializes a new instance of the `[SpreadsheetShapeSettings](../../com.groupdocs.watermark.options/spreadsheetshapesettings)` class. |
## Methods

| Method | Description |
| --- | --- |
| [isLocked()](#isLocked--) | Gets a value indicating whether an editing of the shape in Excel is forbidden. |
| [setLocked(boolean value)](#setLocked-boolean-) | Sets a value indicating whether an editing of the shape in Excel is forbidden. |
### SpreadsheetShapeSettings() {#SpreadsheetShapeSettings--}
```
public SpreadsheetShapeSettings()
```


Initializes a new instance of the `[SpreadsheetShapeSettings](../../com.groupdocs.watermark.options/spreadsheetshapesettings)` class.

### isLocked() {#isLocked--}
```
public final boolean isLocked()
```


Gets a value indicating whether an editing of the shape in Excel is forbidden.

**Returns:**
boolean - If the value is true, shape editing will be forbidden. By default, the value is false, the shape can be edited in Excel.
### setLocked(boolean value) {#setLocked-boolean-}
```
public final void setLocked(boolean value)
```


Sets a value indicating whether an editing of the shape in Excel is forbidden.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | If the value is true, shape editing will be forbidden. By default, the value is false, the shape can be edited in Excel. |

