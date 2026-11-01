---
title: "SpreadsheetContent sınıfı"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "Filigranın yerleştirilebileceği bir Excel belgesini temsil eder."
type: docs
url: /tr/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetcontent/
is_root: false
weight: 80
---


## SpreadsheetContent class

Filigranın yerleştirilebileceği bir Excel belgesini temsil eder.

Daha fazla bilgi edinin:
- https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+spreadsheet+documents
- https://docs.groupdocs.com/display/watermarknet/Shapes+in+spreadsheet+document
- https://docs.groupdocs.com/display/watermarknet/Working+with+spreadsheet+document+attachments
- https://docs.groupdocs.com/display/watermarknet/Working+with+worksheet+backgrounds
- https://docs.groupdocs.com/display/watermarknet/Working+with+worksheet+headers+and+footers

SpreadsheetContent türü aşağıdaki üyeleri ortaya çıkarır:

### Yöntemler
| Yöntem | Açıklama |
| :- | :- |
| [decrypt](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetcontent/decrypt/) | Belgeyi şifre çözer. |
| [encrypt](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetcontent/encrypt/#password) | İçeriği şifreler. |
| [encrypt_file](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetcontent/encrypt_file/) |  |
| [encrypt_string](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetcontent/encrypt_string/) |  |
| [dispose](/watermark/python-net/groupdocs.watermark.contents/content/dispose/) | Mevcut örneği yok eder. ([`Content`](/watermark/python-net/groupdocs.watermark.contents/content/) sınıfından miras alınmıştır) |
| [find_images](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images/) | Belirtilen arama kriterlerine göre görüntüleri bulur. Arama, [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/) içinde belirtilen nesnelerde gerçekleştirilir. ([`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/) üzerinden miras alınmıştır.) |
| [find_images_image_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images_image_search_criteria/) | ([`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/) üzerinden miras alınmıştır) |
| [search](/watermark/python-net/groupdocs.watermark.contents/contentpart/search/) | Belirtilen arama kriterlerine göre olası filigranları bulur. Arama, [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/) içinde listelenen nesnelerde gerçekleştirilir. ([`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/) üzerinden miras alınmıştır.) |
| [search_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/search_search_criteria/) | ([`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/) üzerinden miras alınmıştır) |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [worksheets](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetcontent/worksheets/) | Bu [`SpreadsheetContent`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetcontent/) nesnesinin tüm çalışma sayfalarının koleksiyonu. |

### Örnek

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.spreadsheet import SpreadsheetLoadOptions

load_options = SpreadsheetLoadOptions()
with Watermarker(r"D:\input.xls", load_options) as watermarker:
    # Belirli bir veya tüm çalışma sayfalarına filigran eklemek için add yöntemini kullanın.
    watermarker.save(r"D:\output.xls")
```

### Ayrıca Bakınız
* module [`groupdocs.watermark.contents.spreadsheet`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/)
