---
title: "مسح العلامات المائية"
linkTitle: "Clear watermarks"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "ابحث عن العلامات المائية النصية أو الصورية الموجودة واحذفها باستخدام GroupDocs.Watermark للبايثون عبر .NET."
type: docs
url: /ar/python-net/guides/clear/
is_root: false
weight: 100
---


يمكنك البحث في مستند عن العلامات المائية الموجودة وإزالتها. المثال أدناه يجد علامة مائية نصية "CONFIDENTIAL" ويزيلها، مما ينتج مستندًا نظيفًا.

## Remove text watermarks

قم بتكرار نتائج البحث بترتيب عكسي حتى لا يؤدي حذف عنصر إلى تغيير الفهارس المتبقية للزيارة، واستدعِ `remove()` لكل تطابق.

{{< tabs "code-example-clear">}}
{{< tab "clear_watermark.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

def clear_watermark():
    with Watermarker("./watermarked-document.pdf") as watermarker:
        possible = watermarker.search(TextSearchCriteria("CONFIDENTIAL"))
        # احذف بترتيب عكسي حتى تظل الفهارس صالحة أثناء حذف العناصر
        for i in range(len(possible) - 1, -1, -1):
            watermarker.remove(possible[i])
        watermarker.save("./output.pdf")

if __name__ == "__main__":
    clear_watermark()
```
{{< /tab >}}
{{< tab "watermarked-document.pdf" >}}

`watermarked-document.pdf` هو ملف العينة المستخدم في هذا المثال. انقر [هنا](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/clear/watermarked-document.pdf) لتنزيله.

{{< /tab >}}
{{< tab "output.pdf" >}}
```text
Binary file (PDF, 360 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/clear/clear_watermark/output.pdf)
{{< /tab >}}
{{< /tabs >}}

**Use case:** Remove outdated labels such as "Draft" or "Internal Use Only" before sharing a document externally.

## Remove image watermarks

يمكن العثور على العلامات المائية الصورية باستخدام التجزئة الإدراكية وإزالتها بنفس الطريقة:

{{< tabs "code-example-clear-image">}}
{{< tab "clear_image_watermark.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import ImageDctHashSearchCriteria

def clear_image_watermark():
    with Watermarker("./watermarked-document.docx") as watermarker:
        criteria = ImageDctHashSearchCriteria("./logo.png")
        criteria.max_difference = 0.9
        possible = watermarker.search(criteria)
        # احذف بترتيب عكسي حتى تظل الفهارس صالحة أثناء حذف العناصر
        for i in range(len(possible) - 1, -1, -1):
            watermarker.remove(possible[i])
        watermarker.save("./output.docx")

if __name__ == "__main__":
    clear_image_watermark()
```
{{< /tab >}}
{{< tab "watermarked-document.docx" >}}

`watermarked-document.docx` و `logo.png` هما ملفات العينة المستخدمة في هذا المثال. قم بتنزيل [watermarked-document.docx](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/clear/watermarked-document.docx) و [logo.png](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/clear/logo.png).

{{< /tab >}}
{{< tab "output.docx" >}}
```text
Binary file (DOCX, 13 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/clear/clear_image_watermark/output.docx)
{{< /tab >}}
{{< /tabs >}}
