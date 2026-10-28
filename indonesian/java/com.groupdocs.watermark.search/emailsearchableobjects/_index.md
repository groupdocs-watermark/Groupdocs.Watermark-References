---
title: "EmailSearchableObjects"
second_title: "Referensi API GroupDocs.Watermark untuk Java"
description: "Menentukan flag yang mewakili objek pesan email yang akan disertakan dalam pencarian watermark."
type: docs
weight: 22
url: /id/java/com.groupdocs.watermark.search/emailsearchableobjects/
---
**Inheritance:**
java.lang.Object
```
public final class EmailSearchableObjects
```

Menentukan flag yang mewakili objek pesan email yang akan disertakan dalam pencarian watermark.

## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [None](#None) | Menentukan tidak ada objek pencarian. |
|
|  | [Subject](#Subject) | Cari di subjek pesan. |
|
|  | [PlainTextBody](#PlainTextBody) | Cari di isi pesan teks biasa. |
|
|  | [HtmlBody](#HtmlBody) | Cari di isi pesan html. |
|
|  | [AttachedImages](#AttachedImages) | Cari di gambar terlampir. |
|
|  | [EmbeddedImages](#EmbeddedImages) | Cari di gambar tersemat. |
|
|  | [All](#All) | Cari di semua objek email. |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getValues()](#getValues--) | Mendapatkan array semua nilai dari enumerasi `[EmailSearchableObjects](../../com.groupdocs.watermark.search/emailsearchableobjects)`. |
|
### None {#None}
```
public static final int None
```


Menentukan tidak ada objek pencarian.


### Subject {#Subject}
```
public static final int Subject
```


Cari di subjek pesan.


### PlainTextBody {#PlainTextBody}
```
public static final int PlainTextBody
```


Cari di isi pesan teks biasa.


### HtmlBody {#HtmlBody}
```
public static final int HtmlBody
```


Cari di isi pesan html.


### AttachedImages {#AttachedImages}
```
public static final int AttachedImages
```


Cari di gambar terlampir.


### EmbeddedImages {#EmbeddedImages}
```
public static final int EmbeddedImages
```


Cari di gambar tersemat.


### All {#All}
```
public static final int All
```


Cari di semua objek email.


### getValues() {#getValues--}
```
public static final int[] getValues()
```


Mendapatkan array semua nilai dari enumerasi `[EmailSearchableObjects](../../com.groupdocs.watermark.search/emailsearchableobjects)`.


**Returns:**
int[] - Array semua nilai dari enumerasi `[EmailSearchableObjects](../../com.groupdocs.watermark.search/emailsearchableobjects)`.

