---
title: "فئة DiagramContent"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "يمثل مستند Visio."
type: docs
url: /ar/python-net/groupdocs.watermark.contents.diagram/diagramcontent/
is_root: false
weight: 10
---


## DiagramContent class

يمثل مستند Visio.

اعرف المزيد:
- Add watermarks to diagram documents https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+diagram+documents
- Existing objects in diagram document https://docs.groupdocs.com/display/watermarknet/Existing+objects+in+diagram+document

نوع DiagramContent يعرض الأعضاء التالية:

### الطرق
| طريقة | الوصف |
| :- | :- |
| [dispose](/watermark/python-net/groupdocs.watermark.contents/content/dispose/) | يتخلص من المثيل الحالي. (موروث من [`Content`](/watermark/python-net/groupdocs.watermark.contents/content/)) |
| [find_images](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images/) | يبحث عن الصور وفقًا لمعايير البحث المحددة. يتم البحث في الكائنات المحددة في [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). (موروث من [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [find_images_image_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images_image_search_criteria/) | (موروث من [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [search](/watermark/python-net/groupdocs.watermark.contents/contentpart/search/) | يبحث عن العلامات المائية المحتملة وفقًا لمعايير البحث المحددة. يتم البحث على الكائنات المدرجة في [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). (موروث من [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [search_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/search_search_criteria/) | (موروث من [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [header_footer](/watermark/python-net/groupdocs.watermark.contents.diagram/diagramcontent/header_footer/) | الترويسة والتذييل لهذه DiagramContent. |
| [pages](/watermark/python-net/groupdocs.watermark.contents.diagram/diagramcontent/pages/) | مجموعة جميع صفحات هذا [`DiagramContent`](/watermark/python-net/groupdocs.watermark.contents.diagram/diagramcontent/). |

### مثال

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

### انظر أيضًا
* module [`groupdocs.watermark.contents.diagram`](/watermark/python-net/groupdocs.watermark.contents.diagram/)
