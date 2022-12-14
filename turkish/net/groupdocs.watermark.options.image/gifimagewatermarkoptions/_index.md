---
title: GifImageWatermarkOptions
second_title: .NET API Başvurusu için GroupDocs.Watermark
description: Bir GIF görüntüsüne filigran eklerken filigran ekleme seçeneklerini temsil eder.
type: docs
weight: 1760
url: /tr/net/groupdocs.watermark.options.image/gifimagewatermarkoptions/
---
## GifImageWatermarkOptions class

Bir GIF görüntüsüne filigran eklerken filigran ekleme seçeneklerini temsil eder.

```csharp
public sealed class GifImageWatermarkOptions : MultiframeImageWatermarkOptions
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [GifImageWatermarkOptions](gifimagewatermarkoptions#constructor)() | Yeni bir örneğini başlatır.[`GifImageWatermarkOptions`](../gifimagewatermarkoptions) sınıf. |
| [GifImageWatermarkOptions](gifimagewatermarkoptions#constructor_1)(int) | Yeni bir örneğini başlatır.[`GifImageWatermarkOptions`](../gifimagewatermarkoptions) belirtilen bir çerçeve dizini olan sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [FrameIndex](../../groupdocs.watermark.options.image/multiframeimagewatermarkoptions/frameindex) { get; set; } | Filigran eklemek için çerçeve dizinini alır veya ayarlar. |

### Notlar

**Daha fazla bilgi edin:**

* [Resimlere filigran ekleyin](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+images)

### Örnekler

GIF görüntüsünün belirli bir çerçevesine filigran ekleyin.

```csharp
GifImageLoadOptions loadOptions = new GifImageLoadOptions();
using (Watermarker watermarker = new Watermarker(@"C:\test.gif", loadOptions))
{
    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 12));

    GifImageWatermarkOptions options = new GifImageWatermarkOptions();
    options.FrameIndex = 0;

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### Ayrıca bakınız

* class [MultiframeImageWatermarkOptions](../multiframeimagewatermarkoptions)
* ad alanı [GroupDocs.Watermark.Options.Image](../../groupdocs.watermark.options.image)
* toplantı [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
