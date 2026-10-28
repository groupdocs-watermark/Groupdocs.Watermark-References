---
title: "Attachment"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "表示附加到文档的文件。"
type: docs
weight: 10
url: /zh/java/com.groupdocs.watermark.common/attachment/
---
**Inheritance:**
java.lang.Object
```
public abstract class Attachment
```

表示附加到文档的文件。

**Learn more**

* [Email attachments](../https://docs.groupdocs.com/display/watermarkjava/Email+attachments)
* [Attachments in PDF document](../https://docs.groupdocs.com/display/watermarkjava/Attachments+in+PDF+document)
* [Working with spreadsheet document attachments](../https://docs.groupdocs.com/display/watermarkjava/Working+with+spreadsheet+document+attachments)

## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getDocumentInfo()](#getDocumentInfo--) | 获取存储在附件文件中的文档信息。 |
|
|  | [getContent()](#getContent--) | 获取附件文件的内容。 |
|
|  | [setContent(byte[] value)](#setContent-byte---) | 设置附件文件的内容。 |
|
|  | [createWatermarker()](#createWatermarker--) | 从附件文件加载内容。 |
|
|  | [createWatermarker(LoadOptions loadOptions)](#createWatermarker-com.groupdocs.watermark.options.LoadOptions-) | 使用指定的加载选项从附件文件加载内容。 |
|
|  | [createWatermarker(LoadOptions loadOptions, WatermarkerSettings watermarkerSettings)](#createWatermarker-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-) | 使用指定的加载选项和设置从附件文件加载内容。 |
|
|  | [getContentStream()](#getContentStream--) | 获取附件文件的流。 |
|
|  | [setContentStream(System.IO.Stream stream)](#setContentStream-com.aspose.ms.System.IO.Stream-) | 从流更新附件文件。 |
|
|  | [updateContent(Watermarker updatedVersion)](#updateContent-com.groupdocs.watermark.Watermarker-) | 更新附件内容。 |
|
### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


获取存储在附件文件中的文档信息。


**Returns:**
[IDocumentInfo](../../com.groupdocs.watermark.common/idocumentinfo) - The `[IDocumentInfo](../../com.groupdocs.watermark.common/idocumentinfo)` instance that contains detected information.

### getContent() {#getContent--}
```
public abstract byte[] getContent()
```


获取附件文件的内容。


**Returns:**
byte[] - 附件文件的内容。

### setContent(byte[] value) {#setContent-byte---}
```
public abstract void setContent(byte[] value)
```


设置附件文件的内容。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | byte[] | 附件文件的内容。 |
|

### createWatermarker() {#createWatermarker--}
```
public final Watermarker createWatermarker()
```


从附件文件加载内容。


**Returns:**
[Watermarker](../../com.groupdocs.watermark/watermarker) - The instance of appropriate descendant of `[Content](../../com.groupdocs.watermark.contents/content)` class.

### createWatermarker(LoadOptions loadOptions) {#createWatermarker-com.groupdocs.watermark.options.LoadOptions-}
```
public final Watermarker createWatermarker(LoadOptions loadOptions)
```


使用指定的加载选项从附件文件加载内容。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | loadOptions | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) | 加载附件内容时使用的其他选项。 |
|

**Returns:**
[Watermarker](../../com.groupdocs.watermark/watermarker) - The instance of appropriate descendant of `[Content](../../com.groupdocs.watermark.contents/content)` class.

### createWatermarker(LoadOptions loadOptions, WatermarkerSettings watermarkerSettings) {#createWatermarker-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-}
```
public final Watermarker createWatermarker(LoadOptions loadOptions, WatermarkerSettings watermarkerSettings)
```


使用指定的加载选项和设置从附件文件加载内容。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | loadOptions | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) | 加载附件内容时使用的其他选项。 |
|
|  | watermarkerSettings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) | 处理已加载文档时使用的其他设置。 |
|

**Returns:**
[Watermarker](../../com.groupdocs.watermark/watermarker) - The instance of appropriate descendant of `[Content](../../com.groupdocs.watermark.contents/content)` class.

### getContentStream() {#getContentStream--}
```
public System.IO.Stream getContentStream()
```


获取附件文件的流。


**Returns:**
com.aspose.ms.System.IO.Stream - 用于读取文件内容的流。

### setContentStream(System.IO.Stream stream) {#setContentStream-com.aspose.ms.System.IO.Stream-}
```
public void setContentStream(System.IO.Stream stream)
```


从流更新附件文件。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | stream | com.aspose.ms.System.IO.Stream | 用于更新附件文件的流。 |
|

### updateContent(Watermarker updatedVersion) {#updateContent-com.groupdocs.watermark.Watermarker-}
```
public final void updateContent(Watermarker updatedVersion)
```


更新附件内容。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | updatedVersion | [Watermarker](../../com.groupdocs.watermark/watermarker) | 内容的更新版本。 |
|

