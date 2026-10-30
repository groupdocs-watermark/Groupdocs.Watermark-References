---
title: "TextWatermark"
second_title: "GroupDocs.Watermark for .NET API Referansı"
description: "Bir metin filigranını temsil eder."
type: docs
weight: 3320
url: /tr/net/groupdocs.watermark.watermarks/textwatermark/
---
## TextWatermark class

Bir metin filigranını temsil eder.

```csharp
public class TextWatermark : Watermark
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [TextWatermark](textwatermark)(string, Font) | Belirtilen bir metin ve bir yazı tipi ile [`TextWatermark`](../textwatermark) sınıfının yeni bir örneğini başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [BackgroundColor](../../groupdocs.watermark.watermarks/textwatermark/backgroundcolor) { get; set; } | Metnin arka plan rengini alır veya ayarlar. |
| [ConsiderParentMargins](../../groupdocs.watermark/watermark/considerparentmargins) { get; set; } | Filigran boyutu ve koordinatlarının ebeveyn kenar boşlukları dikkate alınarak hesaplanıp hesaplanmadığını gösteren bir değeri alır veya ayarlar. |
| [Font](../../groupdocs.watermark.watermarks/textwatermark/font) { get; set; } | Metnin yazı tipini alır veya ayarlar. |
| [ForegroundColor](../../groupdocs.watermark.watermarks/textwatermark/foregroundcolor) { get; set; } | Metnin ön plan rengini alır veya ayarlar. |
| [Height](../../groupdocs.watermark/watermark/height) { get; set; } | Bu [`Watermark`](../../groupdocs.watermark/watermark) öğesinin istenen yüksekliğini alır veya ayarlar. |
| [HorizontalAlignment](../../groupdocs.watermark/watermark/horizontalalignment) { get; set; } | Bu [`Watermark`](../../groupdocs.watermark/watermark) öğesinin yatay hizalamasını alır veya ayarlar. |
| [IsBackground](../../groupdocs.watermark/watermark/isbackground) { get; set; } | Filigranın arka plana yerleştirilecek olup olmadığını belirten bir değeri alır veya ayarlar. |
| [Margins](../../groupdocs.watermark/watermark/margins) { get; set; } | Bu [`Watermark`](../../groupdocs.watermark/watermark) öğesinin kenar boşluğu ayarlarını alır veya ayarlar. |
| [Opacity](../../groupdocs.watermark/watermark/opacity) { get; set; } | Bu [`Watermark`](../../groupdocs.watermark/watermark) öğesinin opaklığını alır veya ayarlar. |
| [Padding](../../groupdocs.watermark.watermarks/textwatermark/padding) { get; set; } | Bu [`TextWatermark`](../textwatermark) öğesinin dolgu ayarlarını alır veya ayarlar. Bu özellik yalnızca görüntü dosyalarına uygulanabilir. |
| [PagesSetup](../../groupdocs.watermark/watermark/pagessetup) { get; set; } | Bu [`Watermark`](../../groupdocs.watermark/watermark) öğesinin sayfa ayarlarını alır veya ayarlar. |
| [RotateAngle](../../groupdocs.watermark/watermark/rotateangle) { get; set; } | Bu [`Watermark`](../../groupdocs.watermark/watermark) öğesinin döndürme açısını derece cinsinden alır veya ayarlar. |
| [SaveResultInMetadata](../../groupdocs.watermark/watermark/saveresultinmetadata) { get; set; } | Eklenen filigranlarla ilgili bilgilerin belge meta verilerinde kaydedilip kaydedilmeyeceğini gösteren bir değeri alır veya ayarlar. |
| [ScaleFactor](../../groupdocs.watermark/watermark/scalefactor) { get; set; } | Filigran boyutunun ebeveyn boyutuna nasıl bağlı olduğunu tanımlayan bir değeri alır veya ayarlar. |
| [SizingType](../../groupdocs.watermark/watermark/sizingtype) { get; set; } | Filigranın nasıl boyutlandırılacağını belirten bir değeri alır veya ayarlar. |
| [Text](../../groupdocs.watermark.watermarks/textwatermark/text) { get; set; } | Filigran olarak kullanılacak metni alır veya ayarlar. |
| [TextAlignment](../../groupdocs.watermark.watermarks/textwatermark/textalignment) { get; set; } | Filigran metni hizalamasını alır veya ayarlar. |
| [TileOptions](../../groupdocs.watermark/watermark/tileoptions) { get; set; } | Tekrarlanan filigranı tanımlamak için seçenekleri alır veya ayarlar |
| [VerticalAlignment](../../groupdocs.watermark/watermark/verticalalignment) { get; set; } | Bu [`Watermark`](../../groupdocs.watermark/watermark) öğesinin dikey hizalamasını alır veya ayarlar. |
| [Width](../../groupdocs.watermark/watermark/width) { get; set; } | Bu [`Watermark`](../../groupdocs.watermark/watermark) öğesinin istenen genişliğini alır veya ayarlar. |
| [X](../../groupdocs.watermark/watermark/x) { get; set; } | Bu [`Watermark`](../../groupdocs.watermark/watermark) öğesinin x koordinatını alır veya ayarlar. |
| [Y](../../groupdocs.watermark/watermark/y) { get; set; } | Bu [`Watermark`](../../groupdocs.watermark/watermark) öğesinin y koordinatını alır veya ayarlar. |

### Açıklamalar

**Learn more:**

* [Adding text watermarks](https://docs.groupdocs.com/display/watermarknet/Adding+text+watermarks)

### Örnekler

Metin filigranını üst öğenin boyutuna göre ölçeklendir.

```csharp
foreach (string file in Directory.GetFiles("C:\\test"))
{
    using (Watermarker watermarker = new Watermarker(file))
    {
        TextWatermark watermark = new TextWatermark("test watermark", new Font("Arial", 36));
        watermark.HorizontalAlignment = HorizontalAlignment.Center;
        watermark.VerticalAlignment = VerticalAlignment.Center;
        watermark.SizingType = SizingType.ScaleToParentDimensions;
        watermark.RotateAngle = 45;
        watermark.ScaleFactor = 0.4;

        watermarker.Add(watermark);
        watermarker.Save();
    }
}
```

### Ayrıca Bakınız

* class [Watermark](../../groupdocs.watermark/watermark)
* namespace [GroupDocs.Watermark.Watermarks](../../groupdocs.watermark.watermarks)
* assembly [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.watermark.dll -->
