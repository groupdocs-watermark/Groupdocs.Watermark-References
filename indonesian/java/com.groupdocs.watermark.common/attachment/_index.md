---
title: "Attachment"
second_title: "Referensi API GroupDocs.Watermark untuk Java"
description: "Mewakili file yang dilampirkan pada dokumen."
type: docs
weight: 10
url: /id/java/com.groupdocs.watermark.common/attachment/
---
**Inheritance:**
java.lang.Object
```
public abstract class Attachment
```

Mewakili file yang dilampirkan pada dokumen.

**Learn more**

* [Email attachments](../https://docs.groupdocs.com/display/watermarkjava/Email+attachments)
* [Attachments in PDF document](../https://docs.groupdocs.com/display/watermarkjava/Attachments+in+PDF+document)
* [Working with spreadsheet document attachments](../https://docs.groupdocs.com/display/watermarkjava/Working+with+spreadsheet+document+attachments)

## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getDocumentInfo()](#getDocumentInfo--) | Mendapatkan informasi tentang dokumen yang disimpan dalam file terlampir. |
|
|  | [getContent()](#getContent--) | Mendapatkan konten file terlampir. |
|
|  | [setContent(byte[] value)](#setContent-byte---) | Mengatur konten file terlampir. |
|
|  | [createWatermarker()](#createWatermarker--) | Memuat konten dari file terlampir. |
|
|  | [createWatermarker(LoadOptions loadOptions)](#createWatermarker-com.groupdocs.watermark.options.LoadOptions-) | Memuat konten dari file terlampir dengan opsi pemuatan yang ditentukan. |
|
|  | [createWatermarker(LoadOptions loadOptions, WatermarkerSettings watermarkerSettings)](#createWatermarker-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-) | Memuat konten dari file terlampir dengan opsi pemuatan dan pengaturan yang ditentukan. |
|
|  | [getContentStream()](#getContentStream--) | Mendapatkan aliran dari file terlampir. |
|
|  | [setContentStream(System.IO.Stream stream)](#setContentStream-com.aspose.ms.System.IO.Stream-) | Memperbarui file terlampir dari aliran. |
|
|  | [updateContent(Watermarker updatedVersion)](#updateContent-com.groupdocs.watermark.Watermarker-) | Memperbarui konten terlampir. |
|
### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


Mendapatkan informasi tentang dokumen yang disimpan dalam file terlampir.


**Returns:**
[IDocumentInfo](../../com.groupdocs.watermark.common/idocumentinfo) - The `[IDocumentInfo](../../com.groupdocs.watermark.common/idocumentinfo)` instance that contains detected information.

### getContent() {#getContent--}
```
public abstract byte[] getContent()
```


Mendapatkan konten file terlampir.


**Returns:**
byte[] - Konten file terlampir.

### setContent(byte[] value) {#setContent-byte---}
```
public abstract void setContent(byte[] value)
```


Mengatur konten file terlampir.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | byte[] | Konten file terlampir. |
|

### createWatermarker() {#createWatermarker--}
```
public final Watermarker createWatermarker()
```


Memuat konten dari file terlampir.


**Returns:**
[Watermarker](../../com.groupdocs.watermark/watermarker) - The instance of appropriate descendant of `[Content](../../com.groupdocs.watermark.contents/content)` class.

### createWatermarker(LoadOptions loadOptions) {#createWatermarker-com.groupdocs.watermark.options.LoadOptions-}
```
public final Watermarker createWatermarker(LoadOptions loadOptions)
```


Memuat konten dari file terlampir dengan opsi pemuatan yang ditentukan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | loadOptions | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) | Opsi tambahan untuk digunakan saat memuat konten lampiran. |
|

**Returns:**
[Watermarker](../../com.groupdocs.watermark/watermarker) - The instance of appropriate descendant of `[Content](../../com.groupdocs.watermark.contents/content)` class.

### createWatermarker(LoadOptions loadOptions, WatermarkerSettings watermarkerSettings) {#createWatermarker-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-}
```
public final Watermarker createWatermarker(LoadOptions loadOptions, WatermarkerSettings watermarkerSettings)
```


Memuat konten dari file terlampir dengan opsi pemuatan dan pengaturan yang ditentukan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | loadOptions | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) | Opsi tambahan untuk digunakan saat memuat konten lampiran. |
|
|  | watermarkerSettings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) | Pengaturan tambahan yang digunakan saat bekerja dengan dokumen yang dimuat. |
|

**Returns:**
[Watermarker](../../com.groupdocs.watermark/watermarker) - The instance of appropriate descendant of `[Content](../../com.groupdocs.watermark.contents/content)` class.

### getContentStream() {#getContentStream--}
```
public System.IO.Stream getContentStream()
```


Mendapatkan aliran dari file terlampir.


**Returns:**
com.aspose.ms.System.IO.Stream - Aliran untuk membaca konten file.

### setContentStream(System.IO.Stream stream) {#setContentStream-com.aspose.ms.System.IO.Stream-}
```
public void setContentStream(System.IO.Stream stream)
```


Memperbarui file terlampir dari aliran.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | stream | com.aspose.ms.System.IO.Stream | Aliran untuk memperbarui file terlampir. |
|

### updateContent(Watermarker updatedVersion) {#updateContent-com.groupdocs.watermark.Watermarker-}
```
public final void updateContent(Watermarker updatedVersion)
```


Memperbarui konten terlampir.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | updatedVersion | [Watermarker](../../com.groupdocs.watermark/watermarker) | Versi konten yang diperbarui. |
|

