---
title: "Удалить водяные знаки"
linkTitle: "Clear watermarks"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Ищите и удаляйте существующие текстовые или графические водяные знаки с помощью GroupDocs.Watermark для Python через .NET."
type: docs
url: /ru/python-net/guides/clear/
is_root: false
weight: 100
---


Вы можете искать в документе существующие водяные знаки и удалять их. Пример ниже находит текстовый водяной знак "CONFIDENTIAL" и удаляет его, получая чистый документ.

## Remove text watermarks

Итерируйте результаты поиска в обратном порядке, чтобы удаление элемента не сдвигало индексы, которые ещё нужно посетить, и вызывайте `remove()` для каждого совпадения.

{{< tabs "code-example-clear">}}
{{< tab "clear_watermark.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

def clear_watermark():
    with Watermarker("./watermarked-document.pdf") as watermarker:
        possible = watermarker.search(TextSearchCriteria("CONFIDENTIAL"))
        # Удаляйте в обратном порядке, чтобы индексы оставались корректными при удалении элементов
        for i in range(len(possible) - 1, -1, -1):
            watermarker.remove(possible[i])
        watermarker.save("./output.pdf")

if __name__ == "__main__":
    clear_watermark()
```
{{< /tab >}}
{{< tab "watermarked-document.pdf" >}}

`watermarked-document.pdf` — это пример файла, используемый в данном примере. Нажмите [здесь](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/clear/watermarked-document.pdf), чтобы скачать его.

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

Графические водяные знаки можно находить с помощью перцептивного хеширования и удалять тем же способом:

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
        # Удаляйте в обратном порядке, чтобы индексы оставались корректными при удалении элементов
        for i in range(len(possible) - 1, -1, -1):
            watermarker.remove(possible[i])
        watermarker.save("./output.docx")

if __name__ == "__main__":
    clear_image_watermark()
```
{{< /tab >}}
{{< tab "watermarked-document.docx" >}}

`watermarked-document.docx` и `logo.png` — это примерные файлы, используемые в данном примере. Скачайте [watermarked-document.docx](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/clear/watermarked-document.docx) и [logo.png](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/clear/logo.png).

{{< /tab >}}
{{< tab "output.docx" >}}
```text
Binary file (DOCX, 13 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/clear/clear_image_watermark/output.docx)
{{< /tab >}}
{{< /tabs >}}
