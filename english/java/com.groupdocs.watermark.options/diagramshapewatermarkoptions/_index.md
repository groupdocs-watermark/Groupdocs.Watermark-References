---
title: DiagramShapeWatermarkOptions
second_title: GroupDocs.Watermark for Java API Reference
description: Represents watermark adding options when adding shape watermark to a Visio document.
type: docs
weight: 14
url: /java/com.groupdocs.watermark.options/diagramshapewatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.DiagramWatermarkOptions](../../com.groupdocs.watermark.options/diagramwatermarkoptions)
```
public final class DiagramShapeWatermarkOptions extends DiagramWatermarkOptions
```

Represents watermark adding options when adding shape watermark to a Visio document.

**Learn more:**

 *  [Add watermarks to diagram documents][]

The following example demonstrates how to add a protected watermark to all pages of the Visio document.

> ```
> ```
> 
>    DiagramLoadOptions loadOptions = new DiagramLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.vsdx", loadOptions);
> 
>    TextWatermark watermark = new TextWatermark("watermark test", new Font("Arial", 42));
> 
>    DiagramShapeWatermarkOptions options = new DiagramShapeWatermarkOptions();
>    options.setLocked(true);
>    options.setPlacementType(DiagramWatermarkPlacementType.AllPages);
> 
>    watermarker.add(watermark, options);
>    watermarker.save("D:\\watermarked_test.vsdx");
>    watermarker.close();
>  
> ```
> ```


[Add watermarks to diagram documents]: https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+diagram+documents
## Constructors

| Constructor | Description |
| --- | --- |
| [DiagramShapeWatermarkOptions()](#DiagramShapeWatermarkOptions--) | Initializes a new instance of the `[DiagramShapeWatermarkOptions](../../com.groupdocs.watermark.options/diagramshapewatermarkoptions)` class. |
## Methods

| Method | Description |
| --- | --- |
| [getPlacementType()](#getPlacementType--) | Gets a value specifying to what pages a watermark should be added. |
| [setPlacementType(int value)](#setPlacementType-int-) | Gets or sets a value specifying to what pages a watermark should be added. |
### DiagramShapeWatermarkOptions() {#DiagramShapeWatermarkOptions--}
```
public DiagramShapeWatermarkOptions()
```


Initializes a new instance of the `[DiagramShapeWatermarkOptions](../../com.groupdocs.watermark.options/diagramshapewatermarkoptions)` class.

### getPlacementType() {#getPlacementType--}
```
public final int getPlacementType()
```


Gets a value specifying to what pages a watermark should be added.

**Returns:**
int - The `[DiagramWatermarkPlacementType](../../com.groupdocs.watermark.contents/diagramwatermarkplacementtype)`, that specifies to what pages a watermark should be added.
### setPlacementType(int value) {#setPlacementType-int-}
```
public final void setPlacementType(int value)
```


Gets or sets a value specifying to what pages a watermark should be added.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The `[DiagramWatermarkPlacementType](../../com.groupdocs.watermark.contents/diagramwatermarkplacementtype)`, that specifies to what pages a watermark should be added. |

