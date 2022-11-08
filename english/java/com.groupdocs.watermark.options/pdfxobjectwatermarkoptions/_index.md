---
title: PdfXObjectWatermarkOptions
second_title: GroupDocs.Watermark for Java API Reference
description: Represents watermark adding options when adding XObject watermark to a pdf document.
type: docs
weight: 34
url: /java/com.groupdocs.watermark.options/pdfxobjectwatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.PdfWatermarkOptions](../../com.groupdocs.watermark.options/pdfwatermarkoptions)
```
public final class PdfXObjectWatermarkOptions extends PdfWatermarkOptions
```

Represents watermark adding options when adding XObject watermark to a pdf document.

**Learn more:**

 *  [Add watermarks to PDF documents][]

The following example demonstrates how to add a watermark to a particular page of a pdf document.

> ```
> ```
> 
>    PdfLoadOptions loadOptions = new PdfLoadOptions();
>    Watermarker watermarker = new Watermarker("C:\\doc.pdf", loadOptions);
> 
>    ImageWatermark watermark = new ImageWatermark("C:\\watermark.png");
> 
>    PdfXObjectWatermarkOptions options = new PdfXObjectWatermarkOptions();
>    options.setPageIndex(0);
> 
>    watermarker.add(watermark, options);
>    watermarker.save("C:\\watermarked_doc.pdf");
>    watermark.close();
>    watermarker.close();
>  
> ```
> ```


[Add watermarks to PDF documents]: https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+PDF+documents
## Constructors

| Constructor | Description |
| --- | --- |
| [PdfXObjectWatermarkOptions()](#PdfXObjectWatermarkOptions--) | Initializes a new instance of the `[PdfXObjectWatermarkOptions](../../com.groupdocs.watermark.options/pdfxobjectwatermarkoptions)` class. |
## Methods

| Method | Description |
| --- | --- |
| [getPageIndex()](#getPageIndex--) | Gets the page index to add watermark to. |
| [setPageIndex(int value)](#setPageIndex-int-) | Sets the page index to add watermark to. |
### PdfXObjectWatermarkOptions() {#PdfXObjectWatermarkOptions--}
```
public PdfXObjectWatermarkOptions()
```


Initializes a new instance of the `[PdfXObjectWatermarkOptions](../../com.groupdocs.watermark.options/pdfxobjectwatermarkoptions)` class.

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

