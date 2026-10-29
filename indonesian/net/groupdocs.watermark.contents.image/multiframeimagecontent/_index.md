---
title: "MultiframeImageContent"
second_title: "GroupDocs.Watermark untuk Referensi API .NET"
description: "Mewakili gambar multibingkai di mana watermark dapat ditempatkan."
type: docs
weight: 430
url: /id/net/groupdocs.watermark.contents.image/multiframeimagecontent/
---
## MultiframeImageContent class

Mewakili gambar multibingkai di mana watermark dapat ditempatkan.

```csharp
public abstract class MultiframeImageContent : ImageContent
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Frames](../../groupdocs.watermark.contents.image/multiframeimagecontent/frames) { get; } | Mendapatkan koleksi semua frame gambar. |
| virtual [Height](../../groupdocs.watermark.contents.image/imagecontent/height) { get; } | Mendapatkan tinggi dari [`ImageContent`](../imagecontent) ini dalam piksel. |
| virtual [Width](../../groupdocs.watermark.contents.image/imagecontent/width) { get; } | Mendapatkan lebar dari [`ImageContent`](../imagecontent) ini dalam piksel. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Dispose](../../groupdocs.watermark.contents/content/dispose)() | Membuang instance saat ini. |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | Menemukan semua gambar dalam konten. Pencarian dilakukan pada objek-objek yang ditentukan dalam [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | Menemukan gambar sesuai dengan kriteria pencarian yang ditentukan. Pencarian dilakukan pada objek-objek yang ditentukan dalam [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | Menemukan semua watermark yang mungkin dalam konten. Pencarian dilakukan pada objek-objek yang ditentukan dalam [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | Menemukan watermark yang mungkin sesuai dengan kriteria pencarian yang ditentukan. Pencarian dilakukan pada objek yang ditentukan dalam [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |

### Lihat Juga

* class [ImageContent](../imagecontent)
* namespace [GroupDocs.Watermark.Contents.Image](../../groupdocs.watermark.contents.image)
* assembly [GroupDocs.Watermark](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.watermark.dll -->
