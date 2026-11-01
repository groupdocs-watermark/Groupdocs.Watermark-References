---
title: "PresentationWatermarkableImage sınıfı"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "PowerPoint belgesi içindeki bir resmi temsil eder."
type: docs
url: /tr/python-net/groupdocs.watermark.contents.presentation/presentationwatermarkableimage/
is_root: false
weight: 250
---


## PresentationWatermarkableImage class

PowerPoint belgesi içindeki bir resmi temsil eder.

PresentationWatermarkableImage türü aşağıdaki üyeleri gösterir:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationwatermarkableimage/__init__/#image_data) | Belirtilen resim verileri kullanılarak [`PresentationWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationwatermarkableimage/) sınıfının yeni bir örneğini başlatır. |

### Yöntemler
| Yöntem | Açıklama |
| :- | :- |
| [add](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/add/) | Bu [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/) üzerine bir filigran ekler. Bu yöntem, filigran ofseti ve boyutunun piksellerle ölçüldüğünü varsayar (atanmışsa). ([`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/) üzerinden devralınmıştır) |
| [add_watermark](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/add_watermark/) | ([`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/) üzerinden devralınmıştır) |
| [find_images](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images/) | Belirtilen arama kriterlerine göre görüntüleri bulur. Arama, [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/) içinde belirtilen nesnelerde gerçekleştirilir. ([`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/) üzerinden miras alınmıştır.) |
| [find_images_image_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images_image_search_criteria/) | ([`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/) üzerinden miras alınmıştır) |
| [get_bytes](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/get_bytes/) | Görüntüyü bayt dizisi olarak alır. ([`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/) üzerinden devralınmıştır) |
| [search](/watermark/python-net/groupdocs.watermark.contents/contentpart/search/) | Belirtilen arama kriterlerine göre olası filigranları bulur. Arama, [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/) içinde listelenen nesnelerde gerçekleştirilir. ([`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/) üzerinden miras alınmıştır.) |
| [search_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/search_search_criteria/) | ([`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/) üzerinden miras alınmıştır) |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [height](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/height/) | Bu [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/) yüksekliği piksellerde. ([`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/) üzerinden devralınmıştır) |
| [width](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/width/) | Bu WatermarkableImage genişliği piksellerde. ([`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/) üzerinden devralınmıştır) |

### Örnek

```python
import groupdocs.watermark as gw
import groupdocs.watermark.contents.presentation as gwc_ppt

with open("image.png", "rb") as f:
    img = gwc_ppt.PresentationWatermarkableImage(f.read())
```

### Ayrıca Bakınız
* module [`groupdocs.watermark.contents.presentation`](/watermark/python-net/groupdocs.watermark.contents.presentation/)
