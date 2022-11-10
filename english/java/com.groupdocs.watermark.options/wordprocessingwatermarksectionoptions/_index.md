---
title: WordProcessingWatermarkSectionOptions
second_title: GroupDocs.Watermark for Java API Reference
description: Represents options when adding shape watermark to a Word document section.
type: docs
weight: 77
url: /java/com.groupdocs.watermark.options/wordprocessingwatermarksectionoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkBaseOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkbaseoptions)
```
public final class WordProcessingWatermarkSectionOptions extends WordProcessingWatermarkBaseOptions
```

Represents options when adding shape watermark to a Word document section.

**Learn more:**

 *  [Add watermarks to word processing documents][]

The following example demonstrates how to add a watermark to a particular section of a Word document.

> ```
> ```
> 
>    WordProcessingLoadOptions loadOptions = new WordProcessingLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.doc", loadOptions);
> 
>    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 14));
> 
>    WordProcessingWatermarkSectionOptions options = new WordProcessingWatermarkSectionOptions();
>    options.setSectionIndex(0);
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
| [WordProcessingWatermarkSectionOptions()](#WordProcessingWatermarkSectionOptions--) | Initializes a new instance of the `[WordProcessingWatermarkSectionOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarksectionoptions)` class. |
## Methods

| Method | Description |
| --- | --- |
| [getSectionIndex()](#getSectionIndex--) | Gets the index of a section to add the watermark to. |
| [setSectionIndex(int value)](#setSectionIndex-int-) | Sets the index of a section to add the watermark to. |
### WordProcessingWatermarkSectionOptions() {#WordProcessingWatermarkSectionOptions--}
```
public WordProcessingWatermarkSectionOptions()
```


Initializes a new instance of the `[WordProcessingWatermarkSectionOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarksectionoptions)` class.

### getSectionIndex() {#getSectionIndex--}
```
public final int getSectionIndex()
```


Gets the index of a section to add the watermark to.

**Returns:**
int - The index of a section to add the watermark to.

--------------------

\-1 means all sections.
### setSectionIndex(int value) {#setSectionIndex-int-}
```
public final void setSectionIndex(int value)
```


Sets the index of a section to add the watermark to.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The index of a section to add the watermark to.

--------------------

\-1 means all sections. |

