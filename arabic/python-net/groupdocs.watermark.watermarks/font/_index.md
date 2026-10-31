---
title: "فئة Font"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "يمثل خطًا."
type: docs
url: /ar/python-net/groupdocs.watermark.watermarks/font/
is_root: false
weight: 20
---


## Font class

يمثل خطًا.

تُظهر فئة Font الأعضاء التالية:

### المنشئات
| منشئ | الوصف |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/font/__init__/#font_family_name-size) | يُنشئ مثلاً جديدًا من الفئة Font بالاسم العائلي للخط والحجم المحددين. |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/font/__init__/#font_family_name-size-style) | يُنشئ مثلاً جديدًا من الفئة Font بالاسم العائلي للخط، والحجم، والنمط المحددين. |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/font/__init__/#font_family_name-folder_path-size) | يُنشئ مثلاً جديدًا من الفئة Font باسم عائلة خط مخصص، ومجلد يحتوي على خطوط TrueType، وحجم، ونمط. |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/font/__init__/#font_family_name-folder_path-size-style) | يُنشئ مثلاً جديدًا من الفئة Font باسم عائلة خط مخصص، والمجلد الذي يحتوي على ملفات خطوط TrueType، وحجم. |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [bold](/watermark/python-net/groupdocs.watermark.watermarks/font/bold/) | الخط غامق. |
| [family_name](/watermark/python-net/groupdocs.watermark.watermarks/font/family_name/) | اسم العائلة لهذا الخط. |
| [folder_path](/watermark/python-net/groupdocs.watermark.watermarks/font/folder_path/) | المجلد الذي يحتوي على ملفات خطوط TrueType. |
| [italic](/watermark/python-net/groupdocs.watermark.watermarks/font/italic/) | الخط مائل. |
| [size](/watermark/python-net/groupdocs.watermark.watermarks/font/size/) | حجم هذا Font. |
| [strikeout](/watermark/python-net/groupdocs.watermark.watermarks/font/strikeout/) | الخط يحدد خطًا أفقيًا عبر النص. |
| [style](/watermark/python-net/groupdocs.watermark.watermarks/font/style/) | معلومات النمط لهذا Font. |
| [underline](/watermark/python-net/groupdocs.watermark.watermarks/font/underline/) | الخط مسطر. |

### مثال

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color

with Watermarker("document.pdf") as watermarker:
    watermark = TextWatermark("CONFIDENTIAL", Font("Arial", 48))
    watermark.foreground_color = Color.red
    watermarker.add(watermark)
    watermarker.save("watermarked.pdf")
```

### Guides
دليل المهام التي تستخدم `Font`:

* [Hello, World!](/watermark/python-net/guides/hello-world/)
* [Add text watermarks](/watermark/python-net/guides/add-text/)
* [Customize watermarks](/watermark/python-net/guides/customize/)
* [Adding repeated watermarks](/watermark/python-net/guides/adding-repeated-watermarks/)

### انظر أيضًا
* module [`groupdocs.watermark.watermarks`](/watermark/python-net/groupdocs.watermark.watermarks/)
