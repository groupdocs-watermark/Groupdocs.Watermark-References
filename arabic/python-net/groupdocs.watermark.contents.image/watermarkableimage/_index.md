---
title: "فئة WatermarkableImage"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "يمثل صورة داخل مستند."
type: docs
url: /ar/python-net/groupdocs.watermark.contents.image/watermarkableimage/
is_root: false
weight: 90
---


## WatermarkableImage class

يمثل صورة داخل مستند.

اعرف المزيد:
- https://docs.groupdocs.com/display/watermarknet/Adding+watermark+to+images+inside+a+document

يعرض نوع WatermarkableImage الأعضاء التالية:

### الطرق
| طريقة | الوصف |
| :- | :- |
| [add](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/add/#watermark) | يضيف علامة مائية إلى هذا [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/). تفترض هذه الطريقة أن إزاحة وحجم العلامة المائية مقاسين بالبكسل (إذا تم تعيينهما). |
| [add_watermark](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/add_watermark/) |  |
| [get_bytes](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/get_bytes/) | يحصل على الصورة كمصفوفة بايت. |
| [find_images](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images/) | يبحث عن الصور وفقًا لمعايير البحث المحددة. يتم البحث في الكائنات المحددة في [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). (موروث من [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [find_images_image_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images_image_search_criteria/) | (موروث من [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [search](/watermark/python-net/groupdocs.watermark.contents/contentpart/search/) | يبحث عن العلامات المائية المحتملة وفقًا لمعايير البحث المحددة. يتم البحث على الكائنات المدرجة في [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). (موروث من [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [search_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/search_search_criteria/) | (موروث من [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [height](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/height/) | ارتفاع هذا [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/) بالبكسل. |
| [width](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/width/) | عرض هذا WatermarkableImage بالبكسل. |

### مثال

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font

with Watermarker(r"D:\input.doc") as watermarker:
    # تهيئة علامة مائية نصية.
    watermark = TextWatermark("DRAFT", Font("Arial", 19))

    # ابحث عن جميع الصور في المستند.
    images = watermarker.get_images()

    # أضف علامة مائية إلى كل صورة.
    for img in images:
        img.add(watermark)

    # احفظ التغييرات.
    watermarker.save(r"D:\output.doc")
```

### انظر أيضًا
* module [`groupdocs.watermark.contents.image`](/watermark/python-net/groupdocs.watermark.contents.image/)
