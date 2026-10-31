---
title: "فئة PresentationWatermarkableImage"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "يمثل صورة داخل مستند PowerPoint."
type: docs
url: /ar/python-net/groupdocs.watermark.contents.presentation/presentationwatermarkableimage/
is_root: false
weight: 250
---


## PresentationWatermarkableImage class

يمثل صورة داخل مستند PowerPoint.

نوع PresentationWatermarkableImage يعرض الأعضاء التالية:

### المنشئات
| منشئ | الوصف |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationwatermarkableimage/__init__/#image_data) | ينشئ مثلاً جديداً من فئة [`PresentationWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationwatermarkableimage/) باستخدام بيانات الصورة المحددة. |

### الطرق
| طريقة | الوصف |
| :- | :- |
| [add](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/add/) | يضيف علامة مائية إلى هذا [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/). تفترض هذه الطريقة أن إزاحة العلامة المائية وحجمها يُقاسان بالبكسل (إذا تم تعيينهما). (موروث من [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/)) |
| [add_watermark](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/add_watermark/) | (موروث من [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/)) |
| [find_images](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images/) | يبحث عن الصور وفقًا لمعايير البحث المحددة. يتم البحث في الكائنات المحددة في [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). (موروث من [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [find_images_image_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images_image_search_criteria/) | (موروث من [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [get_bytes](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/get_bytes/) | يحصل على الصورة كمصفوفة بايت. (موروث من [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/)) |
| [search](/watermark/python-net/groupdocs.watermark.contents/contentpart/search/) | يبحث عن العلامات المائية المحتملة وفقًا لمعايير البحث المحددة. يتم البحث على الكائنات المدرجة في [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). (موروث من [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [search_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/search_search_criteria/) | (موروث من [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [height](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/height/) | ارتفاع هذا [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/) بالبكسل. (موروث من [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/)) |
| [width](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/width/) | عرض هذا WatermarkableImage بالبكسل. (موروث من [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/)) |

### مثال

```python
import groupdocs.watermark as gw
import groupdocs.watermark.contents.presentation as gwc_ppt

with open("image.png", "rb") as f:
    img = gwc_ppt.PresentationWatermarkableImage(f.read())
```

### انظر أيضًا
* module [`groupdocs.watermark.contents.presentation`](/watermark/python-net/groupdocs.watermark.contents.presentation/)
