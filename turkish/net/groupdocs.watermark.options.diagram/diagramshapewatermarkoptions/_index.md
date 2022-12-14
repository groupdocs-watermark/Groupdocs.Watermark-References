---
title: DiagramShapeWatermarkOptions
second_title: .NET API Başvurusu için GroupDocs.Watermark
description: Visio belgesine şekil filigranı eklerken filigran ekleme seçeneklerini temsil eder.
type: docs
weight: 1680
url: /tr/net/groupdocs.watermark.options.diagram/diagramshapewatermarkoptions/
---
## DiagramShapeWatermarkOptions class

Visio belgesine şekil filigranı eklerken filigran ekleme seçeneklerini temsil eder.

```csharp
public sealed class DiagramShapeWatermarkOptions : DiagramWatermarkOptions
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [DiagramShapeWatermarkOptions](diagramshapewatermarkoptions)() | Yeni bir örneğini başlatır.[`DiagramShapeWatermarkOptions`](../diagramshapewatermarkoptions) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [IsLocked](../../groupdocs.watermark.options.diagram/diagramwatermarkoptions/islocked) { get; set; } | Şeklin Visio'da düzenlenmesinin yasak olup olmadığını gösteren bir değer alır veya ayarlar. |
| [PlacementType](../../groupdocs.watermark.options.diagram/diagramshapewatermarkoptions/placementtype) { get; set; } | Bir filigranın hangi sayfalara eklenmesi gerektiğini belirten bir değer alır veya ayarlar. |

### Notlar

**Daha fazla bilgi edin:**

* [Diyagram belgelerine filigran ekleme](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+diagram+documents)

### Örnekler

Visio belgesinin tüm sayfalarına korumalı filigran ekleyin.

```csharp
DiagramLoadOptions loadOptions = new DiagramLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\test.vsdx", loadOptions))
{
    TextWatermark watermark = new TextWatermark("watermark test", new Font("Arial", 42));

    DiagramShapeWatermarkOptions options = new DiagramShapeWatermarkOptions();
    options.IsLocked = true;
    options.PlacementType = DiagramWatermarkPlacementType.AllPages; // varsayılan

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### Ayrıca bakınız

* class [DiagramWatermarkOptions](../diagramwatermarkoptions)
* ad alanı [GroupDocs.Watermark.Options.Diagram](../../groupdocs.watermark.options.diagram)
* toplantı [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
