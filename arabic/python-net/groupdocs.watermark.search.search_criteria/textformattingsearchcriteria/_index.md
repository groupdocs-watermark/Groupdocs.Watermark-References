---
title: "TextFormattingSearchCriteria فئة"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "يمثل معايير تسمح بالتصفية حسب تنسيق النص."
type: docs
url: /ar/python-net/groupdocs.watermark.search.search_criteria/textformattingsearchcriteria/
is_root: false
weight: 150
---


## TextFormattingSearchCriteria class

يمثل معايير تسمح بالتصفية حسب تنسيق النص.

اعرف المزيد:
- Searching watermarks (https://docs.groupdocs.com/display/watermarknet/Searching+watermarks)

نوع TextFormattingSearchCriteria يعرض الأعضاء التالية:

### المنشئات
| منشئ | الوصف |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.search_criteria/textformattingsearchcriteria/__init__/) | ينشئ مثيلاً جديداً من [`TextFormattingSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/textformattingsearchcriteria/). |

### الطرق
| طريقة | الوصف |
| :- | :- |
| [and_](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/and_/) | يجمع هذا SearchCriteria مع معايير أخرى باستخدام عامل AND المنطقي. (موروث من [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)) |
| [and_search_criteria](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/and_search_criteria/) | (موروث من [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)) |
| [not_](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/not_/) | ينفي هذا SearchCriteria. (موروث من [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)) |
| [or_](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/or_/) | يجمع هذا SearchCriteria مع معايير أخرى باستخدام عامل OR المنطقي. (موروث من [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)) |
| [or_search_criteria](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/or_search_criteria/) | (موروث من [`SearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/searchcriteria/)) |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [background_color_range](/watermark/python-net/groupdocs.watermark.search.search_criteria/textformattingsearchcriteria/background_color_range/) | نطاق الألوان المستخدمة لتصفية العلامات المائية حسب لون خلفية النص. |
| [font_bold](/watermark/python-net/groupdocs.watermark.search.search_criteria/textformattingsearchcriteria/font_bold/) | الخط المستخدم في تنسيق نص العلامة المائية هو عريض. |
| [font_italic](/watermark/python-net/groupdocs.watermark.search.search_criteria/textformattingsearchcriteria/font_italic/) | خاصية font_italic تشير إلى ما إذا كان خط نص العلامة المائية مائلًا. |
| [font_name](/watermark/python-net/groupdocs.watermark.search.search_criteria/textformattingsearchcriteria/font_name/) | اسم الخط المستخدم في تنسيق نص العلامة المائية المحتمل. |
| [font_strikeout](/watermark/python-net/groupdocs.watermark.search.search_criteria/textformattingsearchcriteria/font_strikeout/) | علامة الشطب للخط في تنسيق نص العلامة المائية. |
| [font_underline](/watermark/python-net/groupdocs.watermark.search.search_criteria/textformattingsearchcriteria/font_underline/) | علامة التسطير للخط التي تشير إلى ما إذا كان نص العلامة المائية يستخدم تسطيرًا. |
| [foreground_color_range](/watermark/python-net/groupdocs.watermark.search.search_criteria/textformattingsearchcriteria/foreground_color_range/) | نطاق الألوان المستخدم لتصفية العلامات المائية حسب لون المقدمة للنص. |
| [max_font_size](/watermark/python-net/groupdocs.watermark.search.search_criteria/textformattingsearchcriteria/max_font_size/) | القيمة النهائية لحجم الخط. |
| [min_font_size](/watermark/python-net/groupdocs.watermark.search.search_criteria/textformattingsearchcriteria/min_font_size/) | القيمة الابتدائية لحجم الخط. |

### مثال

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
أدلة المهام التي تستخدم `TextFormattingSearchCriteria`:

* [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)

### انظر أيضًا
* module [`groupdocs.watermark.search.search_criteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/)
