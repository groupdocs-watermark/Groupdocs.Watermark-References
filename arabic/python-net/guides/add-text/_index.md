---
title: "إضافة علامات مائية نصية"
linkTitle: "Add text watermarks"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "توضح هذه المقالة كيفية إضافة علامة مائية نصية إلى مستند وحفظ النتيجة باستخدام GroupDocs.Watermark للـ Python عبر .NET."
type: docs
url: /ar/python-net/guides/add-text/
is_root: false
weight: 40
---


إحدى الميزات الرئيسية في GroupDocs.Watermark هي إضافة علامات مائية نصية إلى المستندات. يمكنك إضافة علامات مائية إلى المستندات أو الصور من مسار محلي، وكذلك من تدفق. للحصول على القائمة الكاملة للتنسيقات المدعومة، راجع [Supported document formats](https://docs.groupdocs.com/watermark/python-net/supported-document-formats/).

## Add a text watermark

لإضافة علامة مائية نصية، اتبع الخطوات التالية:

1. افتح المستند بتمرير مساره (أو تدفقه) إلى الفئة [Watermarker](https://reference.groupdocs.com/watermark/python-net/)، باستخدام كتلة `with` بحيث يتم تحرير المستند تلقائيًا.
2. أنشئ [`TextWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/) بالنص المطلوب و[`Font`](/watermark/python-net/groupdocs.watermark.watermarks/font/).
3. صمّم العلامة المائية — على سبيل المثال، اضبط `foreground_color` والمحاذاة.
4. استدعِ `add()` لتطبيق العلامة المائية و `save()` لكتابة النتيجة.

{{< tabs \"code-example-add-text\">}}
{{< tab \"add_text_watermark.py\" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color
from groupdocs.watermark.common import HorizontalAlignment, VerticalAlignment

def add_text_watermark():
    with Watermarker("./sample.pdf") as watermarker:
        # بناء العلامة المائية النصية وتنسيقها
        watermark = TextWatermark("Top Secret", Font("Arial", 36.0))
        watermark.foreground_color = Color.red
        watermark.horizontal_alignment = HorizontalAlignment.CENTER
        watermark.vertical_alignment = VerticalAlignment.CENTER
        watermark.rotate_angle = 45.0
        watermark.opacity = 0.4

        watermarker.add(watermark)
        watermarker.save("./output.pdf")

if __name__ == "__main__":
    add_text_watermark()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` هو ملف العينة المستخدم في هذا المثال. انقر [هنا](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/add-text/sample.pdf) لتنزيله.

{{< /tab >}}
{{< tab "output.pdf" >}}
```text
Binary file (PDF, 313 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/add-text/add_text_watermark/output.pdf)
{{< /tab >}}
{{< /tabs >}}

شغّل البرنامج. يظهر مستند مائيّ جديد في المسار المحدد.

## What's next

GroupDocs.Watermark يقدم العديد من القدرات الإضافية للعلامات المائية النصية — ألوان الخلفية والواجهة، خطوط مخصصة، شفافية، تدوير، تكرار، وتحديد الموقع بشكل مطلق أو نسبي. راجع [Adding text watermarks](https://docs.groupdocs.com/watermark/python-net/adding-text-watermarks/) في الدليل المتقدم.
