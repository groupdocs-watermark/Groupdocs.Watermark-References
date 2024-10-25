---
title: Attachment
second_title: GroupDocs.Watermark for Java API Reference
description: Represents a file attached to a document.
type: docs
weight: 10
url: /java/com.groupdocs.watermark.common/attachment/
---
**Inheritance:**
java.lang.Object
```
public abstract class Attachment
```

Represents a file attached to a document.

**Learn more**

 *  [Email attachments][]
 *  [Attachments in PDF document][]
 *  [Working with spreadsheet document attachments][]


[Email attachments]: https://docs.groupdocs.com/display/watermarkjava/Email+attachments
[Attachments in PDF document]: https://docs.groupdocs.com/display/watermarkjava/Attachments+in+PDF+document
[Working with spreadsheet document attachments]: https://docs.groupdocs.com/display/watermarkjava/Working+with+spreadsheet+document+attachments
## Methods

| Method | Description |
| --- | --- |
| [getDocumentInfo()](#getDocumentInfo--) | Gets the information about a document stored in the attached file. |
| [getContent()](#getContent--) | Gets the attached file content. |
| [setContent(byte[] value)](#setContent-byte---) | Sets the attached file content. |
| [createWatermarker()](#createWatermarker--) | Loads a content from the attached file. |
| [createWatermarker(LoadOptions loadOptions)](#createWatermarker-com.groupdocs.watermark.options.LoadOptions-) | Loads a content from the attached file with the specified load options. |
| [createWatermarker(LoadOptions loadOptions, WatermarkerSettings watermarkerSettings)](#createWatermarker-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-) | Loads a content from the attached file with the specified load options and settings. |
| [getContentStream()](#getContentStream--) | Gets a stream from the attached file. |
| [setContentStream(System.IO.Stream stream)](#setContentStream-com.aspose.ms.System.IO.Stream-) | Updates attached file from a stream. |
| [updateContent(Watermarker updatedVersion)](#updateContent-com.groupdocs.watermark.Watermarker-) | Updates the attached content. |
### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


Gets the information about a document stored in the attached file.

**Returns:**
[IDocumentInfo](../../com.groupdocs.watermark.common/idocumentinfo) - The `[IDocumentInfo](../../com.groupdocs.watermark.common/idocumentinfo)` instance that contains detected information.
### getContent() {#getContent--}
```
public abstract byte[] getContent()
```


Gets the attached file content.

**Returns:**
byte[] - The attached file content.
### setContent(byte[] value) {#setContent-byte---}
```
public abstract void setContent(byte[] value)
```


Sets the attached file content.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] | The attached file content. |

### createWatermarker() {#createWatermarker--}
```
public final Watermarker createWatermarker()
```


Loads a content from the attached file.

**Returns:**
[Watermarker](../../com.groupdocs.watermark/watermarker) - The instance of appropriate descendant of `[Content](../../com.groupdocs.watermark.contents/content)` class.
### createWatermarker(LoadOptions loadOptions) {#createWatermarker-com.groupdocs.watermark.options.LoadOptions-}
```
public final Watermarker createWatermarker(LoadOptions loadOptions)
```


Loads a content from the attached file with the specified load options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| loadOptions | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) | Additional options to use when loading an attachment content. |

**Returns:**
[Watermarker](../../com.groupdocs.watermark/watermarker) - The instance of appropriate descendant of `[Content](../../com.groupdocs.watermark.contents/content)` class.
### createWatermarker(LoadOptions loadOptions, WatermarkerSettings watermarkerSettings) {#createWatermarker-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-}
```
public final Watermarker createWatermarker(LoadOptions loadOptions, WatermarkerSettings watermarkerSettings)
```


Loads a content from the attached file with the specified load options and settings.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| loadOptions | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) | Additional options to use when loading an attachment content. |
| watermarkerSettings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) | Additional settings to use when working with loaded document. |

**Returns:**
[Watermarker](../../com.groupdocs.watermark/watermarker) - The instance of appropriate descendant of `[Content](../../com.groupdocs.watermark.contents/content)` class.
### getContentStream() {#getContentStream--}
```
public System.IO.Stream getContentStream()
```


Gets a stream from the attached file.

**Returns:**
com.aspose.ms.System.IO.Stream - The stream to read the file content from.
### setContentStream(System.IO.Stream stream) {#setContentStream-com.aspose.ms.System.IO.Stream-}
```
public void setContentStream(System.IO.Stream stream)
```


Updates attached file from a stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | The stream to update attached file from. |

### updateContent(Watermarker updatedVersion) {#updateContent-com.groupdocs.watermark.Watermarker-}
```
public final void updateContent(Watermarker updatedVersion)
```


Updates the attached content.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| updatedVersion | [Watermarker](../../com.groupdocs.watermark/watermarker) | The updated version of the content. |

