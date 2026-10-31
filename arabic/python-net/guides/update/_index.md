---
title: "تحديث العلامات المائية"
linkTitle: "Update watermarks"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "ابحث عن العلامات المائية النصية أو الصورية الموجودة وقم بتحديثها باستخدام GroupDocs.Watermark للبايثون عبر .NET."
type: docs
url: /ar/python-net/guides/update/
is_root: false
weight: 90
---


يمكنك البحث في مستند عن العلامات المائية الموجودة وتعديلها في مكانها — على سبيل المثال، استبدال نص علامة مائية نصية أو تبديل صورة علامة مائية صورية.

## Update text watermarks

ابحث عن علامة مائية بناءً على محتوى نصها، ثم عيّن قيمة جديدة لكل تطابق. المثال أدناه يفتح مستندًا يحتوي بالفعل على علامة مائية "CONFIDENTIAL" ويستبدلها بـ "APPROVED".

{{< tabs "code-example-update">}}
{{< tab "update_watermark.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

def update_watermark():
    with Watermarker("./watermarked-document.pdf") as watermarker:
        # اعثر على العلامات المائية التي يتطابق نصها مع المعايير
        possible = watermarker.search(TextSearchCriteria("CONFIDENTIAL"))
        print("Found", len(possible), "possible watermark(s).")
        for watermark in possible:
            try:
                watermark.text = "APPROVED"
            except Exception:
                # بعض الكيانات التي تم العثور عليها لا تدعم تحرير النص — تخطها
                pass
        watermarker.save("./output.pdf")

if __name__ == "__main__":
    update_watermark()
```
{{< /tab >}}
{{< tab "watermarked-document.pdf" >}}

`watermarked-document.pdf` هو ملف العينة المستخدم في هذا المثال. انقر [هنا](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/update/watermarked-document.pdf) لتنزيله.

{{< /tab >}}
{{< tab "output.pdf" >}}
```text
Binary file (PDF, 444 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/update/update_watermark/output.pdf)
{{< /tab >}}
{{< /tabs >}}

## Update image watermarks

يمكن العثور على العلامات المائية الصورية باستخدام التجزئة الإدراكية ([`ImageDctHashSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagedcthashsearchcriteria/)) وتحديثها عن طريق تعيين بايتات جديدة إلى `image_data`. المثال أدناه يجد علامة مائية الشعار ويستبدلها بطابع "APPROVED".

{{< tabs "code-example-update-image">}}
{{< tab "update_image_watermark.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import ImageDctHashSearchCriteria

def update_image_watermark():
    with Watermarker("./watermarked-document.docx") as watermarker:
        criteria = ImageDctHashSearchCriteria("./logo.png")
        criteria.max_difference = 0.9
        possible = watermarker.search(criteria)
        with open("./stamp.png", "rb") as f:
            image_data = f.read()
        for watermark in possible:
            try:
                watermark.image_data = image_data
            except Exception:
                # بعض الكيانات المكتشفة لا تدعم تحرير الصور — تخطها
                pass
        watermarker.save("./output.docx")

if __name__ == "__main__":
    update_image_watermark()
```
{{< /tab >}}
{{< tab "watermarked-document.docx" >}}

`watermarked-document.docx`، `logo.png`، و `stamp.png` هي الملفات النموذجية المستخدمة في هذا المثال. قم بتنزيل [watermarked-document.docx](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/update/watermarked-document.docx), [logo.png](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/update/logo.png), و [stamp.png](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/update/stamp.png).

{{< /tab >}}
{{< tab "output.docx" >}}
```text
Binary file (DOCX, 19 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/update/update_image_watermark/output.docx)
{{< /tab >}}
{{< /tabs >}}
