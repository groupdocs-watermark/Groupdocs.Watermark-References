---
title: "معاينة المستند"
linkTitle: "Document preview"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "إنشاء صور معاينة (PNG/JPG/BMP) لصفحات المستند باستخدام GroupDocs.Watermark للبايثون عبر .NET."
type: docs
url: /ar/python-net/guides/preview/
is_root: false
weight: 110
---


GroupDocs.Watermark يمكنه عرض صفحات المستند كصور بحيث يمكنك إظهار صور مصغرة للصفحات دون فتح المستند بالكامل في عارض. تقوم بتحكم العرض عبر استدعاء `create_page_stream` الذي يوفر تدفق ملف قابل للكتابة لكل صفحة — المكتبة تكتب صورة الصفحة فيه وتغلقه لك.

## Generate a document preview

قم بتعيين [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/) مع استدعاء `create_page_stream`، اختر `preview_format`، وقم بإدراج `page_numbers` للعرض.

{{< tabs \"code-example-preview\">}}
{{< tab \"generate_preview.py\" >}}
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
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` هو ملف العينة ذو الصفحتين المستخدم في هذا المثال. انقر [هنا](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/preview/sample.pdf) لتنزيله.

{{< /tab >}}
{{< tab \"generate-preview-outputs.zip\" >}}
```text
output-page-1.png (600 KB)
output-page-2.png (94 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/preview/generate_preview/generate-preview-outputs.zip)
{{< /tab >}}
{{< /tabs >}}

يتم كتابة صور الصفحات إلى الدليل الحالي — صورة PNG واحدة لكل صفحة مطلوبة. استخدم `PreviewFormats.JPEG` أو `PreviewFormats.BMP` لتنسيقات أخرى، واضبط `options.width` / `options.height` للتحكم في حجم العرض.

المكتبة تغلق كل ملف يُرجع من `create_page_stream` بمجرد كتابة الصفحة. للتعامل مع الصفحة بمجرد جاهزتها، مرر استدعاءً ثانيًا: `PreviewOptions(create_page_stream, release_page_stream)` يستدعي `release_page_stream(page_number, stream)` مع الكائن الذي أرجعه `create_page_stream` لتلك الصفحة، بعد أن تكون الصورة كاملة فيه. استدعاء `release_page_stream(page_number)` ذو وسيط واحد يعمل أيضًا. يمكن أن يُرجع `create_page_stream` أيضًا `io.BytesIO`: يبقى مفتوحًا، ويحفظ صورة الصفحة حتى يحصل عليها `release_page_stream`.

**Use case:** Generate page previews to display in a web app, dashboard, or document-management system without requiring users to download the full file.
