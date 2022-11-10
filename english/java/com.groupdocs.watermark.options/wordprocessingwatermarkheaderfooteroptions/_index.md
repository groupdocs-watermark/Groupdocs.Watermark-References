---
title: WordProcessingWatermarkHeaderFooterOptions
second_title: GroupDocs.Watermark for Java API Reference
description: Represents options when adding the watermark to a Word section header/footer.
type: docs
weight: 74
url: /java/com.groupdocs.watermark.options/wordprocessingwatermarkheaderfooteroptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkBaseOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkbaseoptions)
```
public final class WordProcessingWatermarkHeaderFooterOptions extends WordProcessingWatermarkBaseOptions
```

Represents options when adding the watermark to a Word section header/footer.
## Constructors

| Constructor | Description |
| --- | --- |
| [WordProcessingWatermarkHeaderFooterOptions()](#WordProcessingWatermarkHeaderFooterOptions--) | Initializes a new instance of the `[WordProcessingWatermarkHeaderFooterOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkheaderfooteroptions)` class. |
## Methods

| Method | Description |
| --- | --- |
| [getSectionIndex()](#getSectionIndex--) | Gets the index of a section to add the watermark to. |
| [setSectionIndex(int value)](#setSectionIndex-int-) | Sets the index of a section to add the watermark to. |
| [getHeaderFooterType()](#getHeaderFooterType--) | Gets the value that identifies the type of header or footer to add the watermark to. |
| [setHeaderFooterType(int value)](#setHeaderFooterType-int-) | Sets the value that identifies the type of header or footer to add the watermark to. |
### WordProcessingWatermarkHeaderFooterOptions() {#WordProcessingWatermarkHeaderFooterOptions--}
```
public WordProcessingWatermarkHeaderFooterOptions()
```


Initializes a new instance of the `[WordProcessingWatermarkHeaderFooterOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkheaderfooteroptions)` class.

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

### getHeaderFooterType() {#getHeaderFooterType--}
```
public final int getHeaderFooterType()
```


Gets the value that identifies the type of header or footer to add the watermark to.

**Returns:**
int - The value of type `[OfficeHeaderFooterType](../../com.groupdocs.watermark.contents/officeheaderfootertype)` that identifies the type of header or footer to add the watermark to.
### setHeaderFooterType(int value) {#setHeaderFooterType-int-}
```
public final void setHeaderFooterType(int value)
```


Sets the value that identifies the type of header or footer to add the watermark to.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The value of type `[OfficeHeaderFooterType](../../com.groupdocs.watermark.contents/officeheaderfootertype)` that identifies the type of header or footer to add the watermark to. |

