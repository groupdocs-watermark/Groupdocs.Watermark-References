---
title: SpreadsheetWatermarkBaseOptions
second_title: GroupDocs.Watermark for Java API Reference
description: Base class for watermark adding options to a Spreadsheet document.
type: docs
weight: 56
url: /java/com.groupdocs.watermark.options/spreadsheetwatermarkbaseoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.SpreadsheetWatermarkOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkoptions)
```
public abstract class SpreadsheetWatermarkBaseOptions extends SpreadsheetWatermarkOptions
```

Base class for watermark adding options to a Spreadsheet document.
## Methods

| Method | Description |
| --- | --- |
| [isLocked()](#isLocked--) | Gets a value indicating whether an editing of the shape in Excel is forbidden. |
| [setLocked(boolean value)](#setLocked-boolean-) | Sets a value indicating whether an editing of the shape in Excel is forbidden. |
| [getName()](#getName--) | Gets the name a shape. |
| [setName(String value)](#setName-java.lang.String-) | Sets the name a shape. |
| [getAlternativeText()](#getAlternativeText--) | Gets the descriptive (alternative) text that will be associated with a shape. |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Sets the descriptive (alternative) text that will be associated with a shape. |
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

### getName() {#getName--}
```
public final String getName()
```


Gets the name a shape.

**Returns:**
java.lang.String - The shape name.
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Sets the name a shape.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The shape name. |

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


Gets the descriptive (alternative) text that will be associated with a shape.

**Returns:**
java.lang.String - The descriptive (alternative) text that will be associated with a shape.
### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


Sets the descriptive (alternative) text that will be associated with a shape.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The descriptive (alternative) text that will be associated with a shape. |

