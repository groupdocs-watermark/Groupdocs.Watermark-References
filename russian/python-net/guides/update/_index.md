---
title: "Обновить водяные знаки"
linkTitle: "Update watermarks"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Ищите существующие текстовые или графические водяные знаки и обновляйте их с помощью GroupDocs.Watermark для Python через .NET."
type: docs
url: /ru/python-net/guides/update/
is_root: false
weight: 90
---


Вы можете искать в документе существующие водяные знаки и изменять их на месте — например, заменить текст текстового водяного знака или заменить изображение графического водяного знака.

## Update text watermarks

Найдите водяной знак по его текстовому содержимому, затем присвойте новое значение каждому совпадению. Пример ниже открывает документ, уже содержащий водяной знак "CONFIDENTIAL", и заменяет его на "APPROVED".

{{< tabs "code-example-update">}}
{{< tab "update_watermark.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

def update_watermark():
    with Watermarker("./watermarked-document.pdf") as watermarker:
        # Найдите водяные знаки, чей текст соответствует критерию
        possible = watermarker.search(TextSearchCriteria("CONFIDENTIAL"))
        print("Found", len(possible), "possible watermark(s).")
        for watermark in possible:
            try:
                watermark.text = "APPROVED"
            except Exception:
                # Некоторые найденные объекты не поддерживают редактирование текста — пропустите их
                pass
        watermarker.save("./output.pdf")

if __name__ == "__main__":
    update_watermark()
```
{{< /tab >}}
{{< tab "watermarked-document.pdf" >}}

`watermarked-document.pdf` — это пример файла, используемый в данном примере. Нажмите [здесь](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/update/watermarked-document.pdf), чтобы скачать его.

{{< /tab >}}
{{< tab "output.pdf" >}}
```text
Binary file (PDF, 444 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/update/update_watermark/output.pdf)
{{< /tab >}}
{{< /tabs >}}

## Update image watermarks

Графические водяные знаки можно находить с помощью перцептивного хеширования ([`ImageDctHashSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagedcthashsearchcriteria/)) и обновлять, присваивая новые байты полю `image_data`. Пример ниже находит логотип‑водяной знак и заменяет его на штамп "APPROVED":

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
                # Некоторые найденные сущности не поддерживают редактирование изображений — пропустите их
                pass
        watermarker.save("./output.docx")

if __name__ == "__main__":
    update_image_watermark()
```
{{< /tab >}}
{{< tab "watermarked-document.docx" >}}

`watermarked-document.docx`, `logo.png` и `stamp.png` — это образцы файлов, используемые в этом примере. Скачайте [watermarked-document.docx](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/update/watermarked-document.docx), [logo.png](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/update/logo.png) и [stamp.png](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/update/stamp.png).

{{< /tab >}}
{{< tab "output.docx" >}}
```text
Binary file (DOCX, 19 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/update/update_image_watermark/output.docx)
{{< /tab >}}
{{< /tabs >}}
