---
title: "WatermarkableImage sınıfı"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "Bir belgedeki resmi temsil eder."
type: docs
url: /tr/python-net/groupdocs.watermark.contents.image/watermarkableimage/
is_root: false
weight: 90
---


## WatermarkableImage class

Bir belgedeki resmi temsil eder.

Daha fazla bilgi edinin:
- https://docs.groupdocs.com/display/watermarknet/Adding+watermark+to+images+inside+a+document

WatermarkableImage türü aşağıdaki üyeleri sunar:

### Yöntemler
| Yöntem | Açıklama |
| :- | :- |
| [add](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/add/#watermark) | Bu [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/) üzerine bir filigran ekler. Bu yöntem, filigran ofseti ve boyutunun piksel cinsinden ölçüldüğünü varsayar (atanmışsa). |
| [add_watermark](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/add_watermark/) |  |
| [get_bytes](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/get_bytes/) | Görüntüyü bayt dizisi olarak alır. |
| [find_images](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images/) | Belirtilen arama kriterlerine göre görüntüleri bulur. Arama, [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/) içinde belirtilen nesnelerde gerçekleştirilir. ([`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/) üzerinden miras alınmıştır.) |
| [find_images_image_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images_image_search_criteria/) | ([`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/) üzerinden miras alınmıştır) |
| [search](/watermark/python-net/groupdocs.watermark.contents/contentpart/search/) | Belirtilen arama kriterlerine göre olası filigranları bulur. Arama, [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/) içinde listelenen nesnelerde gerçekleştirilir. ([`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/) üzerinden miras alınmıştır.) |
| [search_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/search_search_criteria/) | ([`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/) üzerinden miras alınmıştır) |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [height](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/height/) | Bu [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/) öğesinin piksel cinsinden yüksekliği. |
| [width](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/width/) | Bu WatermarkableImage'in piksel cinsinden genişliği. |

### Örnek

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font

with Watermarker(r"D:\input.doc") as watermarker:
    # Metin filigranını başlat.
    watermark = TextWatermark("DRAFT", Font("Arial", 19))

    # Belgedeki tüm görüntüleri bul.
    images = watermarker.get_images()

    # Her görüntüye filigran ekle.
    for img in images:
        img.add(watermark)

    # Değişiklikleri kaydet.
    watermarker.save(r"D:\output.doc")
```

### Ayrıca Bakınız
* module [`groupdocs.watermark.contents.image`](/watermark/python-net/groupdocs.watermark.contents.image/)
