---
title: "TextFormattingSearchCriteria sınıfı"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "Metin biçimlendirmesine göre filtrelemeye izin veren kriterleri temsil eder."
type: docs
url: /tr/python-net/groupdocs.watermark.search.search_criteria/textformattingsearchcriteria/
is_root: false
weight: 150
---


## TextFormattingSearchCriteria class

Metin biçimlendirmesine göre filtrelemeye izin veren kriterleri temsil eder.

Daha fazla bilgi edinin:
- Searching watermarks (https://docs.groupdocs.com/display/watermarknet/Searching+watermarks)

TextFormattingSearchCriteria türü aşağıdaki üyeleri gösterir:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/textformattingsearchcriteria/__init__/) | Yeni bir [`TextFormattingSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/textformattingsearchcriteria/) örneği başlatır. |

### Yöntemler
| Yöntem | Açıklama |
| :- | :- |
| [and_](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/and_/) | Bu SearchCriteria'yi mantıksal VE operatörü kullanarak diğer kriterlerle birleştirir. ([`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/) sınıfından kalıtılmıştır) |
| [and_search_criteria](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/and_search_criteria/) | ([`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/) sınıfından kalıtılmıştır) |
| [not_](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/not_/) | Bu SearchCriteria'yi olumsuzlar. ([`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/) sınıfından kalıtılmıştır) |
| [or_](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/or_/) | Bu SearchCriteria'yi mantıksal VEYA operatörü kullanarak diğer kriterlerle birleştirir. ([`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/) sınıfından kalıtılmıştır) |
| [or_search_criteria](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/or_search_criteria/) | ([`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/) sınıfından kalıtılmıştır) |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [background_color_range](/watermark/python-net/groupdocs.watermark.search.search_criteria/textformattingsearchcriteria/background_color_range/) | Metin arka plan rengine göre filigranları filtrelemek için kullanılan renk aralığı. |
| [font_bold](/watermark/python-net/groupdocs.watermark.search.search_criteria/textformattingsearchcriteria/font_bold/) | Filigran metin biçimlendirmesinde kullanılan yazı tipi kalındır. |
| [font_italic](/watermark/python-net/groupdocs.watermark.search.search_criteria/textformattingsearchcriteria/font_italic/) | font_italic özelliği, filigran metin yazı tipinin italik olup olmadığını gösterir. |
| [font_name](/watermark/python-net/groupdocs.watermark.search.search_criteria/textformattingsearchcriteria/font_name/) | Olası filigran metin biçimlendirmesinde kullanılan yazı tipinin adı. |
| [font_strikeout](/watermark/python-net/groupdocs.watermark.search.search_criteria/textformattingsearchcriteria/font_strikeout/) | Filigran metin biçimlendirmesi için yazı tipi üstü çizili bayrağı. |
| [font_underline](/watermark/python-net/groupdocs.watermark.search.search_criteria/textformattingsearchcriteria/font_underline/) | Filigran metnin alt çizgi kullanıp kullanmadığını gösteren yazı tipi alt çizgi bayrağı. |
| [foreground_color_range](/watermark/python-net/groupdocs.watermark.search.search_criteria/textformattingsearchcriteria/foreground_color_range/) | Metin ön plan rengine göre filigranları filtrelemek için kullanılan renk aralığı. |
| [max_font_size](/watermark/python-net/groupdocs.watermark.search.search_criteria/textformattingsearchcriteria/max_font_size/) | Yazı tipi boyutunun bitiş değeri. |
| [min_font_size](/watermark/python-net/groupdocs.watermark.search.search_criteria/textformattingsearchcriteria/min_font_size/) | Yazı tipi boyutunun başlangıç değeri. |

### Örnek

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextFormattingSearchCriteria, ColorRange

def search_by_formatting():
    with Watermarker("./document.pdf") as watermarker:
        criteria = TextFormattingSearchCriteria()
        criteria.foreground_color_range = ColorRange()
        criteria.foreground_color_range.min_hue = -15
        criteria.foreground_color_range.max_hue = 15
        criteria.foreground_color_range.min_brightness = 0.01
        criteria.foreground_color_range.max_brightness = 0.99
        criteria.min_font_size = 19
        criteria.max_font_size = 42

        possible = watermarker.search(criteria)
        print("Found", len(possible), "possible watermark(s)")

if __name__ == "__main__":
    search_by_formatting()
```

### Guides
`TextFormattingSearchCriteria` kullanan görev kılavuzları:

* [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)

### Ayrıca Bakınız
* module [`groupdocs.watermark.search.search_criteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/)
