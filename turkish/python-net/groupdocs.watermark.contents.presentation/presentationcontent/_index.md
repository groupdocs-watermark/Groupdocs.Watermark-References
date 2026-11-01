---
title: "PresentationContent sınıfı"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "Filigran yerleştirilebilecek bir PowerPoint belgesini temsil eder."
type: docs
url: /tr/python-net/groupdocs.watermark.contents.presentation/presentationcontent/
is_root: false
weight: 60
---


## PresentationContent class

Filigran yerleştirilebilecek bir PowerPoint belgesini temsil eder.

Daha fazla bilgi edinin:
- Add watermarks to presentation documents: https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+presentation+documents
- Working with slide backgrounds: https://docs.groupdocs.com/display/watermarknet/Working+with+slide+backgrounds

PresentationContent türü aşağıdaki üyeleri gösterir:

### Yöntemler
| Yöntem | Açıklama |
| :- | :- |
| [decrypt](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/decrypt/) | Belgeyi şifre çözer. |
| [encrypt](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/encrypt/#password) | Belgeyi şifreler. |
| [encrypt_file](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/encrypt_file/) |  |
| [encrypt_string](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/encrypt_string/) |  |
| [dispose](/watermark/python-net/groupdocs.watermark.contents/content/dispose/) | Mevcut örneği yok eder. ([`Content`](/watermark/python-net/groupdocs.watermark.contents/content/) sınıfından miras alınmıştır) |
| [find_images](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images/) | Belirtilen arama kriterlerine göre görüntüleri bulur. Arama, [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/) içinde belirtilen nesnelerde gerçekleştirilir. ([`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/) üzerinden miras alınmıştır.) |
| [find_images_image_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images_image_search_criteria/) | ([`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/) üzerinden miras alınmıştır) |
| [search](/watermark/python-net/groupdocs.watermark.contents/contentpart/search/) | Belirtilen arama kriterlerine göre olası filigranları bulur. Arama, [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/) içinde listelenen nesnelerde gerçekleştirilir. ([`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/) üzerinden miras alınmıştır.) |
| [search_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/search_search_criteria/) | ([`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/) üzerinden miras alınmıştır) |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [layout_slides](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/layout_slides/) | Bu [`PresentationContent`](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/) içindeki tüm düzen slaytlarının koleksiyonu. |
| [master_handout_slide](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/master_handout_slide/) | Bu [`PresentationContent`](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/) içindeki ana el ilanı slaytı. |
| [master_notes_slide](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/master_notes_slide/) | Bu [`PresentationContent`](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/) içindeki tüm not slaytları için ana slayt. |
| [master_slides](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/master_slides/) | Bu PresentationContent içindeki tüm ana slaytların koleksiyonu. |
| [notes_slide_height](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/notes_slide_height/) | Bir not slaytının yüksekliği puan cinsinden. |
| [notes_slide_width](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/notes_slide_width/) | Not slaytının genişliği puan cinsinden. |
| [slide_height](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/slide_height/) | Slaytın yüksekliği puan cinsinden. |
| [slide_width](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/slide_width/) | Slaytın genişliği puan cinsinden. |
| [slides](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/slides/) | Bu [`PresentationContent`](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/) öğesinin tüm slaytlarının koleksiyonu. |

### Örnek

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.presentation import PresentationLoadOptions

load_options = PresentationLoadOptions()
with Watermarker(r"D:\input.ppt", load_options) as watermarker:
    # Belirli bir slayta veya tüm slaytlara bir filigran eklemek için add yöntemini kullanın.
    watermarker.save(r"D:\output.ppt")
```

### Ayrıca Bakınız
* module [`groupdocs.watermark.contents.presentation`](/watermark/python-net/groupdocs.watermark.contents.presentation/)
