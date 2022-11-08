---
title: WordProcessingWatermarkPagesOptions
second_title: GroupDocs.Watermark for Java API Reference
description: Represents options when adding watermark to Word document pages.
type: docs
weight: 76
url: /java/com.groupdocs.watermark.options/wordprocessingwatermarkpagesoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkBaseOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkbaseoptions)
```
public final class WordProcessingWatermarkPagesOptions extends WordProcessingWatermarkBaseOptions
```

Represents options when adding watermark to Word document pages.

**Learn more:**

 *  [Add watermarks to word processing documents][]

The following example demonstrates how to add a watermark to a particular page of a Word document.

> ```
> ```
> 
>    WordProcessingLoadOptions loadOptions = new WordProcessingLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.doc", loadOptions);
> 
>    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 14));
> 
>    WordProcessingWatermarkPagesOptions options = new WordProcessingWatermarkPagesOptions();
>    options.setPageNumbers(new int[] { 1 });
>    
>    watermarker.save("D:\\watermarked_test.doc");
>    watermarker.close();
>  
> ```
> ```


[Add watermarks to word processing documents]: https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+word+processing+documents
## Constructors

| Constructor | Description |
| --- | --- |
| [WordProcessingWatermarkPagesOptions()](#WordProcessingWatermarkPagesOptions--) | Initializes a new instance of the `[WordProcessingWatermarkPagesOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkpagesoptions)` class. |
## Methods

| Method | Description |
| --- | --- |
| [getPageNumbers()](#getPageNumbers--) | Gets the page numbers to add the watermark. |
| [setPageNumbers(int[] value)](#setPageNumbers-int---) | Sets the page numbers to add the watermark. |
### WordProcessingWatermarkPagesOptions() {#WordProcessingWatermarkPagesOptions--}
```
public WordProcessingWatermarkPagesOptions()
```


Initializes a new instance of the `[WordProcessingWatermarkPagesOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkpagesoptions)` class.

### getPageNumbers() {#getPageNumbers--}
```
public final int[] getPageNumbers()
```


Gets the page numbers to add the watermark.

**Returns:**
int[] - The page numbers to add the watermark.

--------------------

All numbers must be greater than or equal to 1. This property is only used when adding the watermark to a document. If this value is  null  or empty, the watermark is added to all pages.
### setPageNumbers(int[] value) {#setPageNumbers-int---}
```
public final void setPageNumbers(int[] value)
```


Sets the page numbers to add the watermark.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int[] | The page numbers to add the watermark.

--------------------

All numbers must be greater than or equal to 1. This property is only used when adding the watermark to a document. If this value is  null  or empty, the watermark is added to all pages. |

