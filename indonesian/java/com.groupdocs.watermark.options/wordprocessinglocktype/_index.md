---
title: "WordProcessingLockType"
second_title: "Referensi API GroupDocs.Watermark untuk Java"
description: "Menentukan jenis kunci watermark dalam dokumen Word."
type: docs
weight: 68
url: /id/java/com.groupdocs.watermark.options/wordprocessinglocktype/
---
**Inheritance:**
java.lang.Object
```
public final class WordProcessingLockType
```

Menentukan jenis kunci watermark dalam dokumen Word.

## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [AllowOnlyRevisions](#AllowOnlyRevisions) | Pengguna hanya dapat menambahkan tanda revisi ke dokumen. |
|
|  | [AllowOnlyComments](#AllowOnlyComments) | Pengguna hanya dapat mengubah komentar dalam dokumen. |
|
|  | [AllowOnlyFormFields](#AllowOnlyFormFields) | Pengguna hanya dapat memasukkan data ke bidang formulir dalam dokumen. |
|
|  | [ReadOnly](#ReadOnly) | Seluruh dokumen bersifat read-only. |
|
|  | [ReadOnlyWithEditableContent](#ReadOnlyWithEditableContent) | Dokumen bersifat read-only, tetapi semua konten kecuali watermark ditandai dapat diedit. |
|
|  | [NoLock](#NoLock) | Nonaktifkan semua kunci pada watermark dan dokumen. |
|
### AllowOnlyRevisions {#AllowOnlyRevisions}
```
public static final int AllowOnlyRevisions
```


Pengguna hanya dapat menambahkan tanda revisi ke dokumen.


### AllowOnlyComments {#AllowOnlyComments}
```
public static final int AllowOnlyComments
```


Pengguna hanya dapat mengubah komentar dalam dokumen.


### AllowOnlyFormFields {#AllowOnlyFormFields}
```
public static final int AllowOnlyFormFields
```


Pengguna hanya dapat memasukkan data ke bidang formulir dalam dokumen.

<br />

*** ** * ** ***

Dokumen dibagi menjadi bagian satu halaman dan bagian terkunci dengan watermark ditambahkan di antara setiap dua bagian konten yang bersebelahan.

<br />



### ReadOnly {#ReadOnly}
```
public static final int ReadOnly
```


Seluruh dokumen bersifat read-only.


### ReadOnlyWithEditableContent {#ReadOnlyWithEditableContent}
```
public static final int ReadOnlyWithEditableContent
```


Dokumen bersifat read-only, tetapi semua konten kecuali watermark ditandai dapat diedit.


### NoLock {#NoLock}
```
public static final int NoLock
```


Nonaktifkan semua kunci pada watermark dan dokumen.


