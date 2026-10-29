---
title: "Attachment"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "Bir belgeye eklenmiş dosyayı temsil eder."
type: docs
weight: 10
url: /tr/java/com.groupdocs.watermark.common/attachment/
---
**Inheritance:**
java.lang.Object
```
public abstract class Attachment
```

Bir belgeye eklenmiş dosyayı temsil eder.

**Learn more**

* [Email attachments](../https://docs.groupdocs.com/display/watermarkjava/Email+attachments)
* [Attachments in PDF document](../https://docs.groupdocs.com/display/watermarkjava/Attachments+in+PDF+document)
* [Working with spreadsheet document attachments](../https://docs.groupdocs.com/display/watermarkjava/Working+with+spreadsheet+document+attachments)

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getDocumentInfo()](#getDocumentInfo--) | Ekli dosyada depolanan bir belge hakkında bilgi alır. |
|
|  | [getContent()](#getContent--) | Ekli dosya içeriğini alır. |
|
|  | [setContent(byte[] value)](#setContent-byte---) | Ekli dosya içeriğini ayarlar. |
|
|  | [createWatermarker()](#createWatermarker--) | Ekli dosyadan bir içerik yükler. |
|
|  | [createWatermarker(LoadOptions loadOptions)](#createWatermarker-com.groupdocs.watermark.options.LoadOptions-) | Ekli dosyadan, belirtilen yükleme seçenekleriyle bir içerik yükler. |
|
|  | [createWatermarker(LoadOptions loadOptions, WatermarkerSettings watermarkerSettings)](#createWatermarker-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-) | Ekli dosyadan, belirtilen yükleme seçenekleri ve ayarlarla bir içerik yükler. |
|
|  | [getContentStream()](#getContentStream--) | Ekli dosyadan bir akış alır. |
|
|  | [setContentStream(System.IO.Stream stream)](#setContentStream-com.aspose.ms.System.IO.Stream-) | Bir akıştan ekli dosyayı günceller. |
|
|  | [updateContent(Watermarker updatedVersion)](#updateContent-com.groupdocs.watermark.Watermarker-) | Ekli içeriği günceller. |
|
### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


Ekli dosyada depolanan bir belge hakkında bilgi alır.


**Returns:**
[IDocumentInfo](../../com.groupdocs.watermark.common/idocumentinfo) - The `[IDocumentInfo](../../com.groupdocs.watermark.common/idocumentinfo)` instance that contains detected information.

### getContent() {#getContent--}
```
public abstract byte[] getContent()
```


Ekli dosya içeriğini alır.


**Returns:**
byte[] - Ekli dosya içeriği.

### setContent(byte[] value) {#setContent-byte---}
```
public abstract void setContent(byte[] value)
```


Ekli dosya içeriğini ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | byte[] | Ekli dosya içeriği. |
|

### createWatermarker() {#createWatermarker--}
```
public final Watermarker createWatermarker()
```


Ekli dosyadan bir içerik yükler.


**Returns:**
[Watermarker](../../com.groupdocs.watermark/watermarker) - The instance of appropriate descendant of `[Content](../../com.groupdocs.watermark.contents/content)` class.

### createWatermarker(LoadOptions loadOptions) {#createWatermarker-com.groupdocs.watermark.options.LoadOptions-}
```
public final Watermarker createWatermarker(LoadOptions loadOptions)
```


Ekli dosyadan, belirtilen yükleme seçenekleriyle bir içerik yükler.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | loadOptions | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) | Ek bir içerik yüklerken kullanılacak ek seçenekler. |
|

**Returns:**
[Watermarker](../../com.groupdocs.watermark/watermarker) - The instance of appropriate descendant of `[Content](../../com.groupdocs.watermark.contents/content)` class.

### createWatermarker(LoadOptions loadOptions, WatermarkerSettings watermarkerSettings) {#createWatermarker-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-}
```
public final Watermarker createWatermarker(LoadOptions loadOptions, WatermarkerSettings watermarkerSettings)
```


Ekli dosyadan, belirtilen yükleme seçenekleri ve ayarlarla bir içerik yükler.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | loadOptions | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) | Ek bir içerik yüklerken kullanılacak ek seçenekler. |
|
|  | watermarkerSettings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) | Yüklenen belgeyle çalışırken kullanılacak ek ayarlar. |
|

**Returns:**
[Watermarker](../../com.groupdocs.watermark/watermarker) - The instance of appropriate descendant of `[Content](../../com.groupdocs.watermark.contents/content)` class.

### getContentStream() {#getContentStream--}
```
public System.IO.Stream getContentStream()
```


Ekli dosyadan bir akış alır.


**Returns:**
com.aspose.ms.System.IO.Stream - Dosya içeriğini okumak için kullanılan akış.

### setContentStream(System.IO.Stream stream) {#setContentStream-com.aspose.ms.System.IO.Stream-}
```
public void setContentStream(System.IO.Stream stream)
```


Bir akıştan ekli dosyayı günceller.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | stream | com.aspose.ms.System.IO.Stream | Ekli dosyayı güncellemek için akış. |
|

### updateContent(Watermarker updatedVersion) {#updateContent-com.groupdocs.watermark.Watermarker-}
```
public final void updateContent(Watermarker updatedVersion)
```


Ekli içeriği günceller.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | updatedVersion | [Watermarker](../../com.groupdocs.watermark/watermarker) | İçeriğin güncellenmiş sürümü. |
|

