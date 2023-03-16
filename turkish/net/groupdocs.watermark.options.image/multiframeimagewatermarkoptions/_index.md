---
title: MultiframeImageWatermarkOptions
second_title: .NET API Başvurusu için GroupDocs.Watermark
description: Çok çerçeveli bir görüntüye filigran eklerken filigran ekleme seçeneklerini temsil eder.
type: docs
weight: 1800
url: /tr/net/groupdocs.watermark.options.image/multiframeimagewatermarkoptions/
---
## MultiframeImageWatermarkOptions class

Çok çerçeveli bir görüntüye filigran eklerken filigran ekleme seçeneklerini temsil eder.

```csharp
public class MultiframeImageWatermarkOptions : WatermarkOptions
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [MultiframeImageWatermarkOptions](multiframeimagewatermarkoptions#constructor)() | Yeni bir örneğini başlatır.[`MultiframeImageWatermarkOptions`](../multiframeimagewatermarkoptions) sınıf. |
| [MultiframeImageWatermarkOptions](multiframeimagewatermarkoptions#constructor_1)(int) | Yeni bir örneğini başlatır.[`MultiframeImageWatermarkOptions`](../multiframeimagewatermarkoptions) frame. belirtilen bir dizine sahip class |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [FrameIndex](../../groupdocs.watermark.options.image/multiframeimagewatermarkoptions/frameindex) { get; set; } | Filigran eklemek için çerçeve dizinini alır veya ayarlar. |

### Notlar

**Daha fazla bilgi edin:**

* [Resimlere filigran ekleyin](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+images)

### Örnekler

Çok çerçeveli görüntünün belirli bir çerçevesine filigran ekleyin.

```csharp
ImageLoadOptions loadOptions = new ImageLoadOptions();
using (Watermarker watermarker = new Watermarker(@"C:\test.gif", loadOptions))
{
    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 12));

    MultiframeImageWatermarkOptions options = new MultiframeImageWatermarkOptions();
    options.FrameIndex = 0;

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### Ayrıca bakınız

* class [WatermarkOptions](../../groupdocs.watermark.options/watermarkoptions)
* ad alanı [GroupDocs.Watermark.Options.Image](../../groupdocs.watermark.options.image)
* toplantı [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->