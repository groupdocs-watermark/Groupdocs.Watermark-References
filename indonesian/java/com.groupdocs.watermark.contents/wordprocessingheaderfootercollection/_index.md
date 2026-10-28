---
title: "WordProcessingHeaderFooterCollection"
second_title: "Referensi API GroupDocs.Watermark untuk Java"
description: "Mewakili kumpulan header dan footer dalam dokumen Word."
type: docs
weight: 132
url: /id/java/com.groupdocs.watermark.contents/wordprocessingheaderfootercollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase
```
public class WordProcessingHeaderFooterCollection extends ReadOnlyListBase<WordProcessingHeaderFooter>
```

Mewakili kumpulan header dan footer dalam dokumen Word.

Koleksi ini berisi item dengan tipe `[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter)`.

## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getByOfficeHeaderFooterType(int headerFooterType)](#getByOfficeHeaderFooterType-int-) | Mendapatkan header atau footer dari tipe yang ditentukan. |
|
|  | [linkToPrevious(boolean isLinkToPrevious)](#linkToPrevious-boolean-) | Menautkan atau memutuskan semua header dan footer ke yang sesuai |
header dan footer di bagian sebelumnya.
|
### getByOfficeHeaderFooterType(int headerFooterType) {#getByOfficeHeaderFooterType-int-}
```
public final WordProcessingHeaderFooter getByOfficeHeaderFooterType(int headerFooterType)
```


Mendapatkan header atau footer dari tipe yang ditentukan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | headerFooterType | int | Sebuah nilai `[OfficeHeaderFooterType](../../com.groupdocs.watermark.contents/officeheaderfootertype)` yang menentukan tipe header/footer yang akan diambil. |
|

**Returns:**
[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter) - The `[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter)` of specified type.

### linkToPrevious(boolean isLinkToPrevious) {#linkToPrevious-boolean-}
```
public final void linkToPrevious(boolean isLinkToPrevious)
```


Menautkan atau memutuskan semua header dan footer ke yang sesuai
header dan footer di bagian sebelumnya.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | isLinkToPrevious | boolean | True untuk menautkan header dan footer ke bagian sebelumnya; false untuk memutuskan tautannya. |
|

