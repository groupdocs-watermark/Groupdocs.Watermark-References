---
title: "فئة PresentationContent"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "يمثل مستند PowerPoint يمكن وضع علامة مائية فيه."
type: docs
url: /ar/python-net/groupdocs.watermark.contents.presentation/presentationcontent/
is_root: false
weight: 60
---


## PresentationContent class

يمثل مستند PowerPoint يمكن وضع علامة مائية فيه.

اعرف المزيد:
- Add watermarks to presentation documents: https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+presentation+documents
- Working with slide backgrounds: https://docs.groupdocs.com/display/watermarknet/Working+with+slide+backgrounds

نوع PresentationContent يعرض الأعضاء التالية:

### الطرق
| طريقة | الوصف |
| :- | :- |
| [decrypt](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/decrypt/) | يفك تشفير المستند. |
| [encrypt](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/encrypt/#password) | يشفر المستند. |
| [encrypt_file](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/encrypt_file/) |  |
| [encrypt_string](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/encrypt_string/) |  |
| [dispose](/watermark/python-net/groupdocs.watermark.contents/content/dispose/) | يتخلص من المثيل الحالي. (موروث من [`Content`](/watermark/python-net/groupdocs.watermark.contents/content/)) |
| [find_images](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images/) | يبحث عن الصور وفقًا لمعايير البحث المحددة. يتم البحث في الكائنات المحددة في [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). (موروث من [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [find_images_image_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images_image_search_criteria/) | (موروث من [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [search](/watermark/python-net/groupdocs.watermark.contents/contentpart/search/) | يبحث عن العلامات المائية المحتملة وفقًا لمعايير البحث المحددة. يتم البحث على الكائنات المدرجة في [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). (موروث من [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [search_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/search_search_criteria/) | (موروث من [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [layout_slides](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/layout_slides/) | مجموعة جميع شرائح التخطيط لهذه [`PresentationContent`](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/). |
| [master_handout_slide](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/master_handout_slide/) | شريحة المخطوطة الرئيسية لهذه [`PresentationContent`](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/). |
| [master_notes_slide](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/master_notes_slide/) | الشريحة الرئيسية لجميع شرائح الملاحظات لهذه [`PresentationContent`](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/). |
| [master_slides](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/master_slides/) | مجموعة جميع الشرائح الرئيسية لهذه PresentationContent. |
| [notes_slide_height](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/notes_slide_height/) | ارتفاع شريحة الملاحظات بالنقاط. |
| [notes_slide_width](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/notes_slide_width/) | عرض شريحة الملاحظات بالنقاط. |
| [slide_height](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/slide_height/) | ارتفاع الشريحة بالنقاط. |
| [slide_width](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/slide_width/) | عرض الشريحة بالنقاط. |
| [slides](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/slides/) | مجموعة جميع الشرائح لهذا [`PresentationContent`](/watermark/python-net/groupdocs.watermark.contents.presentation/presentationcontent/). |

### مثال

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.presentation import PresentationLoadOptions

load_options = PresentationLoadOptions()
with Watermarker(r"D:\input.ppt", load_options) as watermarker:
    # استخدم طريقة add لإضافة علامة مائية إلى شريحة معينة أو جميع الشرائح.
    watermarker.save(r"D:\output.ppt")
```

### انظر أيضًا
* module [`groupdocs.watermark.contents.presentation`](/watermark/python-net/groupdocs.watermark.contents.presentation/)
