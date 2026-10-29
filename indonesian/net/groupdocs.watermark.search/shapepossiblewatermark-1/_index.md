---
title: "ShapePossibleWatermarkT"
second_title: "GroupDocs.Watermark untuk Referensi API .NET"
description: "Mewakili watermark bentuk dalam konten dengan format apa pun yang didukung."
type: docs
weight: 2770
url: /id/net/groupdocs.watermark.search/shapepossiblewatermark-1/
---
## ShapePossibleWatermark&lt;T&gt; class

Mewakili watermark bentuk dalam konten dengan format apa pun yang didukung.

```csharp
public abstract class ShapePossibleWatermark<T> : TwoDObjectPossibleWatermark
    where T : ShapeSearchAdapter, ITwoDObject
```

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe bentuk. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| override [FormattedTextFragments](../../groupdocs.watermark.search/shapepossiblewatermark-1/formattedtextfragments) { get; } | Mendapatkan koleksi fragmen teks terformat dari bentuk. |
| override [Height](../../groupdocs.watermark.search/twodobjectpossiblewatermark/height) { get; } | Mendapatkan tinggi dari objek 2D. |
| [ImageData](../../groupdocs.watermark.search/possiblewatermark/imagedata) { get; set; } | Mendapatkan atau mengatur gambar dari [`PossibleWatermark`](../possiblewatermark) ini. |
| override [PageNumber](../../groupdocs.watermark.search/shapepossiblewatermark-1/pagenumber) { get; } | Mendapatkan halaman tempat watermark ditempatkan. |
| abstract [Parent](../../groupdocs.watermark.search/possiblewatermark/parent) { get; } | Mendapatkan induk dari [`PossibleWatermark`](../possiblewatermark) ini. |
| override [RotateAngle](../../groupdocs.watermark.search/shapepossiblewatermark-1/rotateangle) { get; } | Mendapatkan sudut rotasi dari bentuk dalam derajat. |
| override [Text](../../groupdocs.watermark.search/shapepossiblewatermark-1/text) { get; set; } | Mendapatkan atau mengatur teks dari bentuk. |
| override [UnitOfMeasurement](../../groupdocs.watermark.search/twodobjectpossiblewatermark/unitofmeasurement) { get; } | Mendapatkan satuan ukuran dari objek 2D. |
| override [Width](../../groupdocs.watermark.search/twodobjectpossiblewatermark/width) { get; } | Mendapatkan lebar dari objek 2D. |
| override [X](../../groupdocs.watermark.search/twodobjectpossiblewatermark/x) { get; } | Mendapatkan koordinat x dari objek 2D. |
| override [Y](../../groupdocs.watermark.search/twodobjectpossiblewatermark/y) { get; } | Mendapatkan koordinat y dari objek 2D. |

### Lihat Juga

* class [TwoDObjectPossibleWatermark](../twodobjectpossiblewatermark)
* class [ShapeSearchAdapter](../shapesearchadapter)
* interface [ITwoDObject](../itwodobject)
* namespace [GroupDocs.Watermark.Search](../../groupdocs.watermark.search)
* assembly [GroupDocs.Watermark](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.watermark.dll -->
