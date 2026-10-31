---
title: "فئة TextWatermark"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "يمثل علامة مائية نصية."
type: docs
url: /ar/python-net/groupdocs.watermark.watermarks/textwatermark/
is_root: false
weight: 110
---


## TextWatermark class

يمثل علامة مائية نصية.

اعرف المزيد:
- Adding text watermarks: https://docs.groupdocs.com/display/watermarknet/Adding+text+watermarks

يُظهر نوع TextWatermark الأعضاء التالية:

### المنشئات
| منشئ | الوصف |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/__init__/#text-font) | يقوم بتهيئة TextWatermark جديد بالنص والخط المحددين. |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [background_color](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/background_color/) | لون الخلفية للنص. |
| [font](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/font/) | خط النص. |
| [foreground_color](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/foreground_color/) | لون المقدمة للنص. |
| [padding](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/padding/) | إعدادات الحشو لهذا TextWatermark، تنطبق فقط على ملفات الصور. |
| [text](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/text/) | النص الذي سيُستخدم كعلامة مائية. |
| [text_alignment](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/text_alignment/) | محاذاة نص العلامة المائية. |
| [consider_parent_margins](/watermark/python-net/groupdocs.watermark/watermark/consider_parent_margins/) | الخاصية التي تشير إلى ما إذا كان حجم العلامة المائية وإحداثياتها يُحسب مع مراعاة هوامش العنصر الأصل. إذا تم تعيينها إلى True، تُؤخذ هوامش الأصل في الاعتبار؛ بشكل افتراضي تكون القيمة False وتُهمل هوامش الأصل. (موروث من [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [height](/watermark/python-net/groupdocs.watermark/watermark/height/) | الارتفاع المطلوب لهذا [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/). (موروث من [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [horizontal_alignment](/watermark/python-net/groupdocs.watermark/watermark/horizontal_alignment/) | المحاذاة الأفقية لهذا Watermark. (موروث من [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [is_background](/watermark/python-net/groupdocs.watermark/watermark/is_background/) | الخاصية التي تشير إلى ما إذا كان يجب وضع العلامة المائية في الخلفية. إذا كانت True، توضع العلامة المائية في الأسفل؛ وإلا توضع في الأعلى (الافتراضي هو False). (موروث من [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [margins](/watermark/python-net/groupdocs.watermark/watermark/margins/) | إعدادات الهوامش لهذا Watermark. (موروث من [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [opacity](/watermark/python-net/groupdocs.watermark/watermark/opacity/) | الشفافية لهذا [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/). (موروث من [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [pages_setup](/watermark/python-net/groupdocs.watermark/watermark/pages_setup/) | إعدادات إعداد الصفحات لهذا Watermark. (موروث من [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [rotate_angle](/watermark/python-net/groupdocs.watermark/watermark/rotate_angle/) | زاوية الدوران لهذا [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/) بالدرجات. (موروث من [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [save_result_in_metadata](/watermark/python-net/groupdocs.watermark/watermark/save_result_in_metadata/) | تشير الخاصية إلى ما إذا كان يجب حفظ المعلومات حول العلامات المائية المضافة في بيانات تعريف المستند. (موروث من [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [scale_factor](/watermark/python-net/groupdocs.watermark/watermark/scale_factor/) | عامل المقياس لهذا [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)، يحدد كيف يعتمد حجم العلامة المائية على حجم العنصر الأصلي. (موروث من [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [sizing_type](/watermark/python-net/groupdocs.watermark/watermark/sizing_type/) | نوع التحجيم للعلامة المائية. (موروث من [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [tile_options](/watermark/python-net/groupdocs.watermark/watermark/tile_options/) | الخيارات لتحديد علامة مائية مكررة. (موروث من [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [vertical_alignment](/watermark/python-net/groupdocs.watermark/watermark/vertical_alignment/) | محاذاة عمودية لهذا [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/). (موروث من [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [width](/watermark/python-net/groupdocs.watermark/watermark/width/) | العرض المطلوب لهذا [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/). (موروث من [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [x](/watermark/python-net/groupdocs.watermark/watermark/x/) | الإحداثي السيني لهذا [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/). (موروث من [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |
| [y](/watermark/python-net/groupdocs.watermark/watermark/y/) | الإحداثي الصادي لهذا [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/). (موروث من [`Watermark`](/watermark/python-net/groupdocs.watermark/watermark/)) |

### مثال

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color

with Watermarker("document.pdf") as watermarker:
    watermark = TextWatermark("CONFIDENTIAL", Font("Arial", 48))
    watermark.foreground_color = Color.red
    watermark.opacity = 0.5
    watermarker.add(watermark)
    watermarker.save("watermarked.pdf")
```

### Guides
دليل المهام الذي يستخدم `TextWatermark`:

* [Hello, World!](/watermark/python-net/guides/hello-world/)
* [Add text watermarks](/watermark/python-net/guides/add-text/)
* [Customize watermarks](/watermark/python-net/guides/customize/)
* [Adding repeated watermarks](/watermark/python-net/guides/adding-repeated-watermarks/)

### انظر أيضًا
* module [`groupdocs.watermark.watermarks`](/watermark/python-net/groupdocs.watermark.watermarks/)
