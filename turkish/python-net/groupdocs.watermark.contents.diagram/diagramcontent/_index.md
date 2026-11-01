---
title: "DiagramContent sınıfı"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "Bir Visio belgesini temsil eder."
type: docs
url: /tr/python-net/groupdocs.watermark.contents.diagram/diagramcontent/
is_root: false
weight: 10
---


## DiagramContent class

Bir Visio belgesini temsil eder.

Daha fazla bilgi edinin:
- Add watermarks to diagram documents https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+diagram+documents
- Existing objects in diagram document https://docs.groupdocs.com/display/watermarknet/Existing+objects+in+diagram+document

DiagramContent türü aşağıdaki üyeleri sunar:

### Yöntemler
| Yöntem | Açıklama |
| :- | :- |
| [dispose](/watermark/python-net/groupdocs.watermark.contents/content/dispose/) | Mevcut örneği yok eder. ([`Content`](/watermark/python-net/groupdocs.watermark.contents/content/) sınıfından miras alınmıştır) |
| [find_images](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images/) | Belirtilen arama kriterlerine göre görüntüleri bulur. Arama, [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/) içinde belirtilen nesnelerde gerçekleştirilir. ([`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/) üzerinden miras alınmıştır.) |
| [find_images_image_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images_image_search_criteria/) | ([`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/) üzerinden miras alınmıştır) |
| [search](/watermark/python-net/groupdocs.watermark.contents/contentpart/search/) | Belirtilen arama kriterlerine göre olası filigranları bulur. Arama, [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/) içinde listelenen nesnelerde gerçekleştirilir. ([`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/) üzerinden miras alınmıştır.) |
| [search_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/search_search_criteria/) | ([`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/) üzerinden miras alınmıştır) |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [header_footer](/watermark/python-net/groupdocs.watermark.contents.diagram/diagramcontent/header_footer/) | Bu DiagramContent'in üstbilgi ve altbilgisi. |
| [pages](/watermark/python-net/groupdocs.watermark.contents.diagram/diagramcontent/pages/) | Bu [`DiagramContent`](/watermark/python-net/groupdocs.watermark.contents.diagram/diagramcontent/) öğesinin tüm sayfalarının koleksiyonu. |

### Örnek

```python
import groupdocs.watermark as gw
from groupdocs.watermark.options.diagram import DiagramLoadOptions
import groupdocs.watermark.contents.diagram as gwc_vsdx

load_options = DiagramLoadOptions()
with gw.Watermarker("diagram.vsdx", load_options) as watermarker:
    content = watermarker.get_content()
    for shape in content.pages[0].shapes:
        if shape.text and "© Aspose 2016" in shape.text:
            shape.text = "© GroupDocs 2017"
    watermarker.save("output.vsdx")
```

### Ayrıca Bakınız
* module [`groupdocs.watermark.contents.diagram`](/watermark/python-net/groupdocs.watermark.contents.diagram/)
