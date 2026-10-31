---
title: "مرحبًا، العالم!"
linkTitle: "Hello, World!"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "ابدأ بسرعة مع GroupDocs.Watermark للـ Python عبر .NET بإنشاء وتشغيل مثال بسيط."
type: docs
url: /ar/python-net/guides/hello-world/
is_root: false
weight: 20
---


## Introduction
عادةً ما يكون مثال "Hello, World!" هو الخطوة الأولى عند استكشاف GroupDocs.Watermark للـ Python عبر .NET. فهو يعمل كاختبار بسيط لتأكيد أن بيئة التطوير الخاصة بك مُعدة بشكل صحيح وأن المكتبة تعمل كما هو متوقع.

## Overview
GroupDocs.Watermark للـ Python عبر .NET يتيح لك إضافة، بحث، وإزالة العلامات المائية في صيغ مستندات مختلفة. مجموعة واسعة من [supported formats](https://docs.groupdocs.com/watermark/python-net/getting-started/supported-document-formats/) تجعلها متعددة الاستخدامات لحالات الاستخدام المختلفة.

## How to add a watermark
الخطوات التالية توضح كيفية إضافة علامة مائية نصية إلى مستند باستخدام GroupDocs.Watermark للبايثون عبر .NET:

1. استورد الفئات `groupdocs.watermark` التي تحتاجها.
2. افتح [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/) مع المسار إلى المستند النموذجي.
3. أنشئ [`TextWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/) بالنص والخط المطلوبين، وقم بتنسيقه.
4. طبّق العلامة المائية باستخدام `add()`.
5. احفظ النتيجة.

## Complete example
المثال أدناه يضيف علامة مائية نصية شبه شفافة ومائلة "Hello, Watermark!" ويحفظ النتيجة:

{{< tabs \"code-example-hello-world\" >}}
{{< tab \"hello_world.py\" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color

def hello_world():
    # افتح المستند، أضف علامة مائية نصية واحدة، واحفظ النتيجة
    with Watermarker("./sample.pdf") as watermarker:
        watermark = TextWatermark("Hello, Watermark!", Font("Arial", 36.0))
        watermark.foreground_color = Color.red
        watermark.opacity = 0.5
        watermark.rotate_angle = 45.0
        watermarker.add(watermark)
        watermarker.save("./output.pdf")

    print("Watermark added successfully. Output saved to ./output.pdf.")

if __name__ == "__main__":
    hello_world()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` هو الملف النموذجي المستخدم في هذا المثال. انقر [هنا](https://docs.groupdocs.com/watermark/python-net/_sample_files/getting-started/hello-world/sample.pdf) لتنزيله.

{{< /tab >}}
{{< tab "output.pdf" >}}
```text
Binary file (PDF, 315 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/getting-started/hello-world/hello_world/output.pdf)
{{< /tab >}}
{{< /tabs >}}

يتم حفظ العلامة المائية مرة أخرى بنفس تنسيق PDF كـ `output.pdf`. لطباعة مستند مختلف، غيّر مسار الإدخال وامتداد الإخراج — GroupDocs.Watermark يحفظ بتنسيق المستند الأصلي.

## Additional resources
هذا العرض يوضح أمثلة الكود لـ GroupDocs.Watermark للبايثون عبر .NET [code samples](https://github.com/groupdocs-watermark/GroupDocs.Watermark-for-Python-via-.NET/).
