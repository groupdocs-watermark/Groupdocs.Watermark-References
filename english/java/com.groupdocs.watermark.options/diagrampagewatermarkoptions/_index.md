---
title: DiagramPageWatermarkOptions
second_title: GroupDocs.Watermark for Java API Reference
description: Represents watermark adding options when adding shape watermark to a particular page of a Visio document.
type: docs
weight: 11
url: /java/com.groupdocs.watermark.options/diagrampagewatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.DiagramWatermarkOptions](../../com.groupdocs.watermark.options/diagramwatermarkoptions)
```
public final class DiagramPageWatermarkOptions extends DiagramWatermarkOptions
```

Represents watermark adding options when adding shape watermark to a particular page of a Visio document.

**Learn more:**

 *  [Add watermarks to diagram documents][]

The following example demonstrates how to add a protected watermark to the first page of a Visio document.

> ```
> ```
> 
>    DiagramLoadOptions loadOptions = new DiagramLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.vsdx", loadOptions);
> 
>    TextWatermark watermark = new TextWatermark("watermark test", new Font("Arial", 42));
> 
>    DiagramPageWatermarkOptions options = new DiagramPageWatermarkOptions();
>    options.setLocked(true);
>    options.setPageIndex(0);
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
| [DiagramPageWatermarkOptions()](#DiagramPageWatermarkOptions--) | Initializes a new instance of the `[DiagramPageWatermarkOptions](../../com.groupdocs.watermark.options/diagrampagewatermarkoptions)` class. |
## Methods

| Method | Description |
| --- | --- |
| [getPageIndex()](#getPageIndex--) | Gets the page index to add watermark to. |
| [setPageIndex(int value)](#setPageIndex-int-) | Sets the page index to add watermark to. |
### DiagramPageWatermarkOptions() {#DiagramPageWatermarkOptions--}
```
public DiagramPageWatermarkOptions()
```


Initializes a new instance of the `[DiagramPageWatermarkOptions](../../com.groupdocs.watermark.options/diagrampagewatermarkoptions)` class.

### getPageIndex() {#getPageIndex--}
```
public final int getPageIndex()
```


Gets the page index to add watermark to.

**Returns:**
int - The page index to add watermark to.
### setPageIndex(int value) {#setPageIndex-int-}
```
public final void setPageIndex(int value)
```


Sets the page index to add watermark to.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The page index to add watermark to. |

