---
title: "طريقة generate_preview"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "ينشئ صورًا معاينة للمستند."
type: docs
url: /ar/python-net/groupdocs.watermark/watermarker/generate_preview/
is_root: false
weight: 1040
---


## generate_preview {#preview_options}

ينشئ صورًا معاينة للمستند.

```python
def generate_preview(self, preview_options):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| preview_options | `PreviewOptions` | خيارات إضافية لاستخدامها عند إنشاء صور المعاينة. |

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
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
