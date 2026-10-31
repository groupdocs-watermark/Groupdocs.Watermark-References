---
title: "منشئ __init__"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "ينشئ مثيلًا جديدًا من PreviewOptions يغلق تدفق الإخراج بعد الاستخدام."
type: docs
url: /ar/python-net/groupdocs.watermark.options/previewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_page_stream}

ينشئ مثيلًا جديدًا من PreviewOptions يغلق تدفق الإخراج بعد الاستخدام.

```python
def __init__(self, create_page_stream):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Callable[[int], io.RawIOBase] – ينشئ تدفقًا لمعاينة صفحة محددة. |

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

## __init__ {#create_page_stream-release_page_stream}

ينشئ مثيلًا جديدًا من PreviewOptions يُعيد تدفق الإخراج إلى العميل للاستخدام لاحقًا.

```python
def __init__(self, create_page_stream, release_page_stream):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Callable الذي ينشئ تدفقًا لمعاينة صفحة محددة. يستقبل رقم الصفحة (`int`) ويجب أن يُعيد تدفقًا قابلًا للكتابة (`io.RawIOBase`). |
| release_page_stream | `ReleasePageStream` | Callable الذي يُستدعى عند اكتمال توليد معاينة الصفحة ويُوفر تدفق الإخراج. |

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

### انظر أيضًا
* class [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/)
