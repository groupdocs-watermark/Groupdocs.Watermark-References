---
title: PdfArtifactWatermarkOptions
second_title: GroupDocs.Watermark for Java API Reference
description: Represents watermark adding options when adding artifact watermark to a pdf document.
type: docs
weight: 29
url: /java/com.groupdocs.watermark.options/pdfartifactwatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.PdfWatermarkOptions](../../com.groupdocs.watermark.options/pdfwatermarkoptions)
```
public final class PdfArtifactWatermarkOptions extends PdfWatermarkOptions
```

Represents watermark adding options when adding artifact watermark to a pdf document.

**Leran more:**

 *  [Add watermarks to PDF documents][]

The following example demonstrates how to add an image artifact watermark to a PDF document.

> ```
> ```
> 
>    PdfLoadOptions loadOptions = new PdfLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.pdf", loadOptions);
> 
>    ImageWatermark watermark = new ImageWatermark("D:\\icon.png");
> 
>    PdfArtifactWatermarkOptions options = new PdfArtifactWatermarkOptions();
>    options.setPageIndex(-1); // default - all pages
> 
>    watermarker.add(watermark, options);
>    watermarker.save("D:\\watermarked_test.pdf");
>    watermark.close();
>    watermarker.close();
>  
> ```
> ```


[Add watermarks to PDF documents]: https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+PDF+documents
## Constructors

| Constructor | Description |
| --- | --- |
| [PdfArtifactWatermarkOptions()](#PdfArtifactWatermarkOptions--) | Initializes a new instance of the `[PdfArtifactWatermarkOptions](../../com.groupdocs.watermark.options/pdfartifactwatermarkoptions)` class. |
## Methods

| Method | Description |
| --- | --- |
| [getPageIndex()](#getPageIndex--) | Gets the page index to add watermark to. |
| [setPageIndex(int value)](#setPageIndex-int-) | Sets the page index to add watermark to. |
### PdfArtifactWatermarkOptions() {#PdfArtifactWatermarkOptions--}
```
public PdfArtifactWatermarkOptions()
```


Initializes a new instance of the `[PdfArtifactWatermarkOptions](../../com.groupdocs.watermark.options/pdfartifactwatermarkoptions)` class.

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

