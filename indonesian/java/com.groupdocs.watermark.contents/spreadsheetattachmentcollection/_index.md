---
title: "SpreadsheetAttachmentCollection"
second_title: "Referensi API GroupDocs.Watermark untuk Java"
description: "Mewakili kumpulan lampiran dalam dokumen Excel."
type: docs
weight: 102
url: /id/java/com.groupdocs.watermark.contents/spreadsheetattachmentcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase
```
public class SpreadsheetAttachmentCollection extends RemoveOnlyListBase<SpreadsheetAttachment>
```

Mewakili kumpulan lampiran dalam dokumen Excel.

Koleksi ini berisi item dengan tipe `[SpreadsheetAttachment](../../com.groupdocs.watermark.contents/spreadsheetattachment)`.

## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [addAttachment(byte[] fileContent, String sourceFullName, byte[] previewImageContent, double x, double y, double width, double height)](#addAttachment-byte---java.lang.String-byte---double-double-double-double-) | Menambahkan lampiran ke `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)`. |
|
|  | [addLink(String sourceFullName, byte[] previewImageContent, double x, double y, double width, double height)](#addLink-java.lang.String-byte---double-double-double-double-) | Menambahkan lampiran melalui tautan (dokumen tidak akan berisi konten file yang dilampirkan). |
|
|  | [removeFromDocument(SpreadsheetAttachment item)](#removeFromDocument-com.groupdocs.watermark.contents.SpreadsheetAttachment-) | <br /> |

|
### addAttachment(byte[] fileContent, String sourceFullName, byte[] previewImageContent, double x, double y, double width, double height) {#addAttachment-byte---java.lang.String-byte---double-double-double-double-}
```
public final void addAttachment(byte[] fileContent, String sourceFullName, byte[] previewImageContent, double x, double y, double width, double height)
```


Menambahkan lampiran ke `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)`.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | fileContent | byte[] | Konten file yang akan dilampirkan. |
|
|  | sourceFullName | java.lang.String | Nama lengkap file yang dilampirkan (Ekstensi digunakan untuk menentukan aplikasi yang tepat untuk membuka file). |
|
|  | previewImageContent | byte[] | Gambar pratinjau file terlampir sebagai array byte. |
|
|  | x | double | Koordinat x dari bingkai lampiran (dalam poin). |
|
|  | y | double | Koordinat y dari bingkai lampiran (dalam poin). |
|
|  | lebar | double | Lebar bingkai lampiran dalam poin. |
|
|  | tinggi | double | Tinggi bingkai lampiran dalam poin. |
|

### addLink(String sourceFullName, byte[] previewImageContent, double x, double y, double width, double height) {#addLink-java.lang.String-byte---double-double-double-double-}
```
public final void addLink(String sourceFullName, byte[] previewImageContent, double x, double y, double width, double height)
```


Menambahkan lampiran melalui tautan (dokumen tidak akan berisi konten file yang dilampirkan).


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | sourceFullName | java.lang.String | Jalur file yang ditautkan. |
|
|  | previewImageContent | byte[] | Gambar pratinjau file terlampir sebagai array byte. |
|
|  | x | double | Koordinat x dari bingkai lampiran (dalam poin). |
|
|  | y | double | Koordinat y dari bingkai lampiran (dalam poin). |
|
|  | lebar | double | Lebar bingkai lampiran dalam poin. |
|
|  | tinggi | double | Tinggi bingkai lampiran dalam poin. |
|

### removeFromDocument(SpreadsheetAttachment item) {#removeFromDocument-com.groupdocs.watermark.contents.SpreadsheetAttachment-}
```
public void removeFromDocument(SpreadsheetAttachment item)
```


<br />



**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [SpreadsheetAttachment](../../com.groupdocs.watermark.contents/spreadsheetattachment) |  |

