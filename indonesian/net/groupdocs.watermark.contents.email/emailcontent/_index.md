---
title: "EmailContent"
second_title: "GroupDocs.Watermark untuk Referensi API .NET"
description: "Mewakili pesan email."
type: docs
weight: 360
url: /id/net/groupdocs.watermark.contents.email/emailcontent/
---
## EmailContent class

Mewakili pesan email.

```csharp
public sealed class EmailContent : Content
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Attachments](../../groupdocs.watermark.contents.email/emailcontent/attachments) { get; } | Mendapatkan koleksi semua lampiran dari pesan email. |
| [Bcc](../../groupdocs.watermark.contents.email/emailcontent/bcc) { get; } | Mendapatkan koleksi penerima BCC (blind carbon copy) dari pesan email. |
| [Body](../../groupdocs.watermark.contents.email/emailcontent/body) { get; set; } | Mendapatkan atau mengatur representasi teks biasa dari isi pesan. |
| [BodyType](../../groupdocs.watermark.contents.email/emailcontent/bodytype) { get; } | Mendapatkan tipe isi pesan email. |
| [Cc](../../groupdocs.watermark.contents.email/emailcontent/cc) { get; } | Mendapatkan koleksi penerima CC (carbon copy) dari pesan email. |
| [EmbeddedObjects](../../groupdocs.watermark.contents.email/emailcontent/embeddedobjects) { get; } | Mendapatkan koleksi semua objek tersemat dari pesan email. |
| [From](../../groupdocs.watermark.contents.email/emailcontent/from) { get; } | Mendapatkan alamat pengirim dari pesan email. |
| [HtmlBody](../../groupdocs.watermark.contents.email/emailcontent/htmlbody) { get; set; } | Mendapatkan atau mengatur representasi HTML dari isi pesan. |
| [Subject](../../groupdocs.watermark.contents.email/emailcontent/subject) { get; set; } | Mendapatkan atau mengatur subjek pesan email. |
| [To](../../groupdocs.watermark.contents.email/emailcontent/to) { get; } | Mendapatkan koleksi penerima pesan email. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Dispose](../../groupdocs.watermark.contents/content/dispose)() | Membuang instance saat ini. |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | Menemukan semua gambar dalam konten. Pencarian dilakukan pada objek-objek yang ditentukan dalam [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | Menemukan gambar sesuai dengan kriteria pencarian yang ditentukan. Pencarian dilakukan pada objek-objek yang ditentukan dalam [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | Menemukan semua watermark yang mungkin dalam konten. Pencarian dilakukan pada objek-objek yang ditentukan dalam [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | Menemukan watermark yang mungkin sesuai dengan kriteria pencarian yang ditentukan. Pencarian dilakukan pada objek yang ditentukan dalam [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |

### Catatan

**Learn more:**

* [Add watermarks to email attachments](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+email+attachments)
* [Email attachments](https://docs.groupdocs.com/display/watermarknet/Email+attachments)
* [Email messages](https://docs.groupdocs.com/display/watermarknet/Email+messages)

### Lihat Juga

* class [Content](../../groupdocs.watermark.contents/content)
* namespace [GroupDocs.Watermark.Contents.Email](../../groupdocs.watermark.contents.email)
* assembly [GroupDocs.Watermark](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.watermark.dll -->
