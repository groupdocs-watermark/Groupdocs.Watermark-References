---
title: PdfAnnotationWatermarkOptions
second_title: GroupDocs.Watermark for Java API Reference
description: Represents watermark adding options when adding annotation watermark to a pdf document.
type: docs
weight: 28
url: /java/com.groupdocs.watermark.options/pdfannotationwatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.PdfWatermarkOptions](../../com.groupdocs.watermark.options/pdfwatermarkoptions)
```
public final class PdfAnnotationWatermarkOptions extends PdfWatermarkOptions
```

Represents watermark adding options when adding annotation watermark to a pdf document.

**Learn more:**

 *  [Add watermarks to PDF documents][]

The following example demonstrates how to add an image annotation watermark to a PDF document.

> ```
> ```
> 
>    PdfLoadOptions loadOptions = new PdfLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.pdf", loadOptions);
> 
>    ImageWatermark watermark = new ImageWatermark("D:\\icon.png");
> 
>    PdfAnnotationWatermarkOptions options = new PdfAnnotationWatermarkOptions();
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
| [PdfAnnotationWatermarkOptions()](#PdfAnnotationWatermarkOptions--) | Initializes a new instance of the `[PdfAnnotationWatermarkOptions](../../com.groupdocs.watermark.options/pdfannotationwatermarkoptions)` class. |
## Methods

| Method | Description |
| --- | --- |
| [getPageIndex()](#getPageIndex--) | Gets the page index to add watermark to. |
| [setPageIndex(int value)](#setPageIndex-int-) | Sets the page index to add watermark to. |
| [getPrintOnly()](#getPrintOnly--) | Get the value indicating whether annotation will be printed, but not displayed in pdf viewing application. |
| [setPrintOnly(boolean value)](#setPrintOnly-boolean-) | Sets the value indicating whether annotation will be printed, but not displayed in pdf viewing application. |
### PdfAnnotationWatermarkOptions() {#PdfAnnotationWatermarkOptions--}
```
public PdfAnnotationWatermarkOptions()
```


Initializes a new instance of the `[PdfAnnotationWatermarkOptions](../../com.groupdocs.watermark.options/pdfannotationwatermarkoptions)` class.

### getPageIndex() {#getPageIndex--}
```
public final int getPageIndex()
```


Gets the page index to add watermark to.

**Returns:**
int - The page index to add watermark to.

--------------------

\-1 means all pages.
### setPageIndex(int value) {#setPageIndex-int-}
```
public final void setPageIndex(int value)
```


Sets the page index to add watermark to.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The page index to add watermark to.

--------------------

\-1 means all pages. |

### getPrintOnly() {#getPrintOnly--}
```
public final boolean getPrintOnly()
```


Get the value indicating whether annotation will be printed, but not displayed in pdf viewing application.

**Returns:**
boolean - The value indicating whether annotation will be printed, but not displayed in pdf viewing application.
### setPrintOnly(boolean value) {#setPrintOnly-boolean-}
```
public final void setPrintOnly(boolean value)
```


Sets the value indicating whether annotation will be printed, but not displayed in pdf viewing application.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | The value indicating whether annotation will be printed, but not displayed in pdf viewing application. |

