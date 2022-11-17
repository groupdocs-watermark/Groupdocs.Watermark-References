---
title: Watermarker
second_title: .NET API Başvurusu için GroupDocs.Watermark
description: Bir belgede filigran yönetimi için bir sınıfı temsil eder.
type: docs
weight: 3060
url: /tr/net/groupdocs.watermark/watermarker/
---
## Watermarker class

Bir belgede filigran yönetimi için bir sınıfı temsil eder.

```csharp
public class Watermarker : IDisposable
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [Watermarker](watermarker#constructor)(Stream) | Yeni bir örneğini başlatır.[`Watermarker`](../watermarker) belirtilen akışa sahip sınıf. |
| [Watermarker](watermarker#constructor_4)(string) | Yeni bir örneğini başlatır.[`Watermarker`](../watermarker) belirtilen belge yoluna sahip sınıf. |
| [Watermarker](watermarker#constructor_1)(Stream, LoadOptions) | Yeni bir örneğini başlatır.[`Watermarker`](../watermarker) belirtilen stream ve yükleme seçeneklerine sahip sınıf. |
| [Watermarker](watermarker#constructor_3)(Stream, WatermarkerSettings) | Yeni bir örneğini başlatır.[`Watermarker`](../watermarker) belirtilen stream ve settings. ile sınıf |
| [Watermarker](watermarker#constructor_5)(string, LoadOptions) | Yeni bir örneğini başlatır.[`Watermarker`](../watermarker)belirtilen belge yolu ve yükleme seçenekleriyle sınıf. |
| [Watermarker](watermarker#constructor_7)(string, WatermarkerSettings) | Yeni bir örneğini başlatır.[`Watermarker`](../watermarker) belirtilen belge yolu ve ayarları ile sınıf. |
| [Watermarker](watermarker#constructor_2)(Stream, LoadOptions, WatermarkerSettings) | Yeni bir örneğini başlatır.[`Watermarker`](../watermarker) belirtilen akışa sahip sınıf, yükleme seçenekleri ve ayarları. |
| [Watermarker](watermarker#constructor_6)(string, LoadOptions, WatermarkerSettings) | Yeni bir örneğini başlatır.[`Watermarker`](../watermarker) belirtilen belge yolu, yükleme seçenekleri ve ayarları ile sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [SearchableObjects](../../groupdocs.watermark/watermarker/searchableobjects) { get; set; } | Bir filigran aramasına dahil edilecek içerik nesnelerini alır veya ayarlar. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [Add](../../groupdocs.watermark/watermarker/add#add)(Watermark) | Yüklenen belgeye bir filigran ekler. |
| [Add](../../groupdocs.watermark/watermarker/add#add_1)(Watermark, WatermarkOptions) | Filigran seçeneklerini kullanarak yüklenen belgeye bir filigran ekler. |
| [Dispose](../../groupdocs.watermark/watermarker/dispose)() | Geçerli örneği ortadan kaldırır. |
| [GeneratePreview](../../groupdocs.watermark/watermarker/generatepreview)(PreviewOptions) | Belge için önizleme görüntüleri oluşturur. |
| [GetContent&lt;T&gt;](../../groupdocs.watermark/watermarker/getcontent)() | şunu döndürür:[`Content`](../../groupdocs.watermark.contents/content) yüklenen belge için nesne. |
| [GetDocumentInfo](../../groupdocs.watermark/watermarker/getdocumentinfo)() | Yüklenen belgenin formatı hakkında bilgi alır. |
| [GetImages](../../groupdocs.watermark/watermarker/getimages#getimages)() | Belgedeki tüm görüntüleri bulur. |
| [GetImages](../../groupdocs.watermark/watermarker/getimages#getimages_1)(ImageSearchCriteria) | Belirtilen arama kriterlerine göre resimleri bulur. |
| [Remove](../../groupdocs.watermark/watermarker/remove#remove)(PossibleWatermark) | Filigranı belgeden kaldırır. |
| [Remove](../../groupdocs.watermark/watermarker/remove#remove_1)(PossibleWatermarkCollection) | Koleksiyondaki tüm filigranları belgeden kaldırır. |
| [Save](../../groupdocs.watermark/watermarker/save#save)() | Belge verilerini alttaki akışa kaydeder. |
| [Save](../../groupdocs.watermark/watermarker/save#save_1)(SaveOptions) | Belge verilerini, kaydetme seçeneklerini kullanarak alttaki akışa kaydeder. |
| [Save](../../groupdocs.watermark/watermarker/save#save_2)(Stream) | Belgeyi belirtilen akışa kaydeder. |
| [Save](../../groupdocs.watermark/watermarker/save#save_4)(string) | Belgeyi belirtilen dosya konumuna kaydeder. |
| [Save](../../groupdocs.watermark/watermarker/save#save_3)(Stream, SaveOptions) | Kaydetme seçeneklerini kullanarak belgeyi belirtilen akışa kaydeder. |
| [Save](../../groupdocs.watermark/watermarker/save#save_5)(string, SaveOptions) | Kaydetme seçeneklerini kullanarak belgeyi belirtilen dosya konumuna kaydeder. |
| [Search](../../groupdocs.watermark/watermarker/search#search)() | Belgedeki tüm olası filigranları arar. |
| [Search](../../groupdocs.watermark/watermarker/search#search_1)(SearchCriteria) | Belirtilen arama kriterlerine göre olası filigranları arar. |

### Örnekler

Desteklenen herhangi bir biçimdeki içeriği yükleyin ve kaydedin.

```csharp
// Bir dosyadan içerik yükleyin.
using (Watermarker watermarker = new Watermarker("D:\\input.pdf"))
{
    // Filigran eklemek, aramak veya kaldırmak için Watermarker sınıfının yöntemlerini kullanın.

    // Değişiklikleri Kaydet.
    watermarker.Save("D:\\output.pdf");
}
```

### Ayrıca bakınız

* ad alanı [GroupDocs.Watermark](../../groupdocs.watermark)
* toplantı [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
