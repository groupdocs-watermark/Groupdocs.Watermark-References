---
title: "WordProcessingContent sınıfı"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "Filigranın yerleştirilebileceği bir Word belgesini (doc, docx vb.) temsil eder."
type: docs
url: /tr/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/
is_root: false
weight: 10
---


## WordProcessingContent class

Filigranın yerleştirilebileceği bir Word belgesini (doc, docx vb.) temsil eder.

Daha fazla bilgi edinin:
- Add watermarks to word processing documents: https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+word+processing+documents
- Existing objects in word processing document: https://docs.groupdocs.com/display/watermarknet/Existing+objects+in+word+processing+document
- Locking watermark in word processing document: https://docs.groupdocs.com/display/watermarknet/Locking+watermark+in+word+processing+document
- Protecting word processing documents: https://docs.groupdocs.com/display/watermarknet/Protecting+word+processing+documents
- Watermarks in word processing document: https://docs.groupdocs.com/display/watermarknet/Watermarks+in+word+processing+document

WordProcessingContent türü aşağıdaki üyeleri sunar:

### Yöntemler
| Yöntem | Açıklama |
| :- | :- |
| [decrypt](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/decrypt/) | Belgeyi şifre çözer. |
| [encrypt](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/encrypt/#password) | Belgeyi şifreler. |
| [encrypt_file](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/encrypt_file/) |  |
| [encrypt_string](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/encrypt_string/) |  |
| [protect](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/protect/#protection_type-password) | Belgeyi değişikliklere karşı korur ve bir koruma şifresi belirler. |
| [protect_file](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/protect_file/) |  |
| [protect_string](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/protect_string/) |  |
| [protect_word_processing_protection_type](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/protect_word_processing_protection_type/) |  |
| [unprotect](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/unprotect/) | Şifreye bakılmaksızın belgedeki korumayı kaldırır. |
| [dispose](/watermark/python-net/groupdocs.watermark.contents/content/dispose/) | Mevcut örneği yok eder. ([`Content`](/watermark/python-net/groupdocs.watermark.contents/content/) sınıfından miras alınmıştır) |
| [find_images](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images/) | Belirtilen arama kriterlerine göre görüntüleri bulur. Arama, [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/) içinde belirtilen nesnelerde gerçekleştirilir. ([`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/) üzerinden miras alınmıştır.) |
| [find_images_image_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images_image_search_criteria/) | ([`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/) üzerinden miras alınmıştır) |
| [search](/watermark/python-net/groupdocs.watermark.contents/contentpart/search/) | Belirtilen arama kriterlerine göre olası filigranları bulur. Arama, [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/) içinde listelenen nesnelerde gerçekleştirilir. ([`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/) üzerinden miras alınmıştır.) |
| [search_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/search_search_criteria/) | ([`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/) üzerinden miras alınmıştır) |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [page_count](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/page_count/) | Belgedeki sayfa sayısı. |
| [sections](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/sections/) | Bu [`WordProcessingContent`](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/) öğesinin tüm bölümlerinin koleksiyonu. |

### Örnek

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.word_processing import WordProcessingLoadOptions

load_options = WordProcessingLoadOptions()
with Watermarker("input.docx", load_options) as watermarker:
    # Gerekirse burada belirli bir bölüme ya da tüm bölümlere filigran ekleyin.
    watermarker.save("output.docx")
```

### Ayrıca Bakınız
* module [`groupdocs.watermark.contents.word_processing`](/watermark/python-net/groupdocs.watermark.contents.word_processing/)
