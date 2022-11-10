---
title: DiagramWatermarkOptions
second_title: GroupDocs.Watermark for Java API Reference
description: Base class for watermark adding options to a Visio document.
type: docs
weight: 15
url: /java/com.groupdocs.watermark.options/diagramwatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions)
```
public abstract class DiagramWatermarkOptions extends WatermarkOptions
```

Base class for watermark adding options to a Visio document.
## Methods

| Method | Description |
| --- | --- |
| [isLocked()](#isLocked--) | Gets a value indicating whether an editing of the shape in Visio is forbidden. |
| [setLocked(boolean value)](#setLocked-boolean-) | Sets a value indicating whether an editing of the shape in Visio is forbidden. |
### isLocked() {#isLocked--}
```
public final boolean isLocked()
```


Gets a value indicating whether an editing of the shape in Visio is forbidden.

**Returns:**
boolean - If the value is true, shape editing will be forbidden.

--------------------

By default, the value is false, the shape can be edited in Visio.
### setLocked(boolean value) {#setLocked-boolean-}
```
public final void setLocked(boolean value)
```


Sets a value indicating whether an editing of the shape in Visio is forbidden.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | If the value is true, shape editing will be forbidden.

--------------------

By default, the value is false, the shape can be edited in Visio. |

