---
title: "فئة PreviewOptions"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "يوفر خيارات لتعيين المتطلبات ومندوبين التدفق لإنشاء المعاينة."
type: docs
url: /ar/python-net/groupdocs.watermark.options/previewoptions/
is_root: false
weight: 60
---


## PreviewOptions class

يوفر خيارات لتعيين المتطلبات ومندوبين التدفق لإنشاء المعاينة.

يعرض نوع PreviewOptions الأعضاء التالية:

### المنشئات
| منشئ | الوصف |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options/previewoptions/__init__/#create_page_stream) | ينشئ مثيلًا جديدًا من PreviewOptions يغلق تدفق الإخراج بعد الاستخدام. |
| [__init__](/watermark/python-net/groupdocs.watermark.options/previewoptions/__init__/#create_page_stream-release_page_stream) | ينشئ مثيلًا جديدًا من PreviewOptions يُعيد تدفق الإخراج إلى العميل للاستخدام لاحقًا. |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [create_page_stream](/watermark/python-net/groupdocs.watermark.options/previewoptions/create_page_stream/) | المندوب المسؤول عن إنشاء تدفق الصفحة المستخدم للحصول على تدفق قابل للكتابة لكل صفحة مُعالجة. |
| [height](/watermark/python-net/groupdocs.watermark.options/previewoptions/height/) | ارتفاع معاينة الصفحة. |
| [page_numbers](/watermark/python-net/groupdocs.watermark.options/previewoptions/page_numbers/) | المصفوفة التي تحتوي على أرقام الصفحات لتوليد المعاينات. |
| [preview_format](/watermark/python-net/groupdocs.watermark.options/previewoptions/preview_format/) | تنسيق صورة المعاينة. |
| [release_page_stream](/watermark/python-net/groupdocs.watermark.options/previewoptions/release_page_stream/) | المندوب المسؤول عن إكمال معاينة الصفحة. |
| [width](/watermark/python-net/groupdocs.watermark.options/previewoptions/width/) | عرض معاينة الصفحة. |

### مثال

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options import PreviewOptions, PreviewFormats

def generate_preview():
    # قدّم تدفق ملف قابل للكتابة لكل صفحة لتتم عملية العرض
    def create_page_stream(page_number):
        return open(f"./output-page-{page_number}.png", "wb")

    with Watermarker("./sample.pdf") as watermarker:
        options = PreviewOptions(create_page_stream)
        options.preview_format = PreviewFormats.PNG
        options.page_numbers = [1, 2]
        watermarker.generate_preview(options)

if __name__ == "__main__":
    generate_preview()
```

### Guides
أدلة المهام التي تستخدم `PreviewOptions`:

* [Document preview](/watermark/python-net/guides/preview/)

### انظر أيضًا
* module [`groupdocs.watermark.options`](/watermark/python-net/groupdocs.watermark.options/)
