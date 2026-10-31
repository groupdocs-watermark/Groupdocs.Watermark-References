---
title: "إضافة علامات مائية صورة"
linkTitle: "Add image watermarks"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "توضح هذه المقالة كيفية إضافة علامة مائية صورة إلى مستند وحفظ النتيجة باستخدام GroupDocs.Watermark للبايثون عبر .NET."
type: docs
url: /ar/python-net/guides/add-image/
is_root: false
weight: 50
---


إحدى الميزات الرئيسية في GroupDocs.Watermark هي إضافة علامات مائية صورة إلى المستندات. يمكنك إضافة علامات مائية إلى المستندات أو الصور من مسار محلي، وكذلك من تدفق. للحصول على قائمة كاملة بالتنسيقات المدعومة، راجع [Supported document formats](https://docs.groupdocs.com/watermark/python-net/supported-document-formats/).

## Add an image watermark

لإضافة علامة مائية صورة، اتبع الخطوات التالية:

1. افتح المستند بتمرير مساره (أو تدفق) إلى الفئة [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/).
2. أنشئ كائنًا من [`ImageWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/imagewatermark/) باستخدام ملف صورة العلامة المائية (أو تدفق).
3. ضع العلامة المائية — على سبيل المثال، اضبط `horizontal_alignment` و `vertical_alignment` و `opacity`.
4. استدعِ `add()` لتطبيق العلامة المائية و `save()` لكتابة النتيجة.

{{< tabs "code-example-add-image">}}
{{< tab "add_image_watermark.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import ImageWatermark
from groupdocs.watermark.common import HorizontalAlignment, VerticalAlignment

def add_image_watermark():
    with Watermarker("./sample.docx") as watermarker:
        # إنشاء علامة مائية صورة من ملف شعار وتوسيطها
        watermark = ImageWatermark("./logo.png")
        watermark.horizontal_alignment = HorizontalAlignment.CENTER
        watermark.vertical_alignment = VerticalAlignment.CENTER
        watermark.opacity = 0.7

        watermarker.add(watermark)
        watermarker.save("./output.docx")

if __name__ == "__main__":
    add_image_watermark()
```
{{< /tab >}}
{{< tab "sample.docx" >}}

`sample.docx` و `logo.png` هما ملفات العينة المستخدمة في هذا المثال. حمّل [sample.docx](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/add-image/sample.docx) و [logo.png](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/add-image/logo.png).

{{< /tab >}}
{{< tab "output.docx" >}}
```text
Binary file (DOCX, 127 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/add-image/add_image_watermark/output.docx)
{{< /tab >}}
{{< /tabs >}}

## What's next

يقدم GroupDocs.Watermark مزيدًا من القدرات للعلامات المائية الصورة — التحميل من التدفقات، التحجيم، التكرار، والتموضع المطلق أو النسبي. راجع [Adding image watermarks](https://docs.groupdocs.com/watermark/python-net/adding-image-watermarks/) في الدليل المتقدم.
