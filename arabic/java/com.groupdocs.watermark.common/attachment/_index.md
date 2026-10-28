---
title: "Attachment"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يمثل ملفًا مرفقًا بمستند."
type: docs
weight: 10
url: /ar/java/com.groupdocs.watermark.common/attachment/
---
**Inheritance:**
java.lang.Object
```
public abstract class Attachment
```

يمثل ملفًا مرفقًا بمستند.

**Learn more**

* [Email attachments](../https://docs.groupdocs.com/display/watermarkjava/Email+attachments)
* [Attachments in PDF document](../https://docs.groupdocs.com/display/watermarkjava/Attachments+in+PDF+document)
* [Working with spreadsheet document attachments](../https://docs.groupdocs.com/display/watermarkjava/Working+with+spreadsheet+document+attachments)

## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getDocumentInfo()](#getDocumentInfo--) | يحصل على المعلومات حول المستند المخزن في الملف المرفق. |
|
|  | [getContent()](#getContent--) | يحصل على محتوى الملف المرفق. |
|
|  | [setContent(byte[] value)](#setContent-byte---) | يضبط محتوى الملف المرفق. |
|
|  | [createWatermarker()](#createWatermarker--) | يقوم بتحميل محتوى من الملف المرفق. |
|
|  | [createWatermarker(LoadOptions loadOptions)](#createWatermarker-com.groupdocs.watermark.options.LoadOptions-) | يقوم بتحميل محتوى من الملف المرفق باستخدام خيارات التحميل المحددة. |
|
|  | [createWatermarker(LoadOptions loadOptions, WatermarkerSettings watermarkerSettings)](#createWatermarker-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-) | يقوم بتحميل محتوى من الملف المرفق باستخدام خيارات التحميل والإعدادات المحددة. |
|
|  | [getContentStream()](#getContentStream--) | يحصل على تدفق من الملف المرفق. |
|
|  | [setContentStream(System.IO.Stream stream)](#setContentStream-com.aspose.ms.System.IO.Stream-) | يقوم بتحديث الملف المرفق من تدفق. |
|
|  | [updateContent(Watermarker updatedVersion)](#updateContent-com.groupdocs.watermark.Watermarker-) | يقوم بتحديث المحتوى المرفق. |
|
### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


يحصل على المعلومات حول المستند المخزن في الملف المرفق.


**Returns:**
[IDocumentInfo](../../com.groupdocs.watermark.common/idocumentinfo) - The `[IDocumentInfo](../../com.groupdocs.watermark.common/idocumentinfo)` instance that contains detected information.

### getContent() {#getContent--}
```
public abstract byte[] getContent()
```


يحصل على محتوى الملف المرفق.


**Returns:**
byte[] - محتوى الملف المرفق.

### setContent(byte[] value) {#setContent-byte---}
```
public abstract void setContent(byte[] value)
```


يضبط محتوى الملف المرفق.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | byte[] | محتوى الملف المرفق. |
|

### createWatermarker() {#createWatermarker--}
```
public final Watermarker createWatermarker()
```


يقوم بتحميل محتوى من الملف المرفق.


**Returns:**
[Watermarker](../../com.groupdocs.watermark/watermarker) - The instance of appropriate descendant of `[Content](../../com.groupdocs.watermark.contents/content)` class.

### createWatermarker(LoadOptions loadOptions) {#createWatermarker-com.groupdocs.watermark.options.LoadOptions-}
```
public final Watermarker createWatermarker(LoadOptions loadOptions)
```


يقوم بتحميل محتوى من الملف المرفق باستخدام خيارات التحميل المحددة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | loadOptions | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) | خيارات إضافية للاستخدام عند تحميل محتوى المرفق. |
|

**Returns:**
[Watermarker](../../com.groupdocs.watermark/watermarker) - The instance of appropriate descendant of `[Content](../../com.groupdocs.watermark.contents/content)` class.

### createWatermarker(LoadOptions loadOptions, WatermarkerSettings watermarkerSettings) {#createWatermarker-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-}
```
public final Watermarker createWatermarker(LoadOptions loadOptions, WatermarkerSettings watermarkerSettings)
```


يقوم بتحميل محتوى من الملف المرفق باستخدام خيارات التحميل والإعدادات المحددة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | loadOptions | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) | خيارات إضافية للاستخدام عند تحميل محتوى المرفق. |
|
|  | watermarkerSettings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) | إعدادات إضافية لاستخدامها عند العمل مع المستند المحمَّل. |
|

**Returns:**
[Watermarker](../../com.groupdocs.watermark/watermarker) - The instance of appropriate descendant of `[Content](../../com.groupdocs.watermark.contents/content)` class.

### getContentStream() {#getContentStream--}
```
public System.IO.Stream getContentStream()
```


يحصل على تدفق من الملف المرفق.


**Returns:**
com.aspose.ms.System.IO.Stream - التدفق لقراءة محتوى الملف منه.

### setContentStream(System.IO.Stream stream) {#setContentStream-com.aspose.ms.System.IO.Stream-}
```
public void setContentStream(System.IO.Stream stream)
```


يقوم بتحديث الملف المرفق من تدفق.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | stream | com.aspose.ms.System.IO.Stream | التدفق لتحديث الملف المرفق منه. |
|

### updateContent(Watermarker updatedVersion) {#updateContent-com.groupdocs.watermark.Watermarker-}
```
public final void updateContent(Watermarker updatedVersion)
```


يقوم بتحديث المحتوى المرفق.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | updatedVersion | [Watermarker](../../com.groupdocs.watermark/watermarker) | الإصدار المحدث للمحتوى. |
|

