---
title: "Filigranları temizle"
linkTitle: "Clear watermarks"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "GroupDocs.Watermark for Python via .NET kullanarak mevcut metin veya resim filigranlarını arayın ve kaldırın."
type: docs
url: /tr/python-net/guides/clear/
is_root: false
weight: 100
---


Bir belgede mevcut filigranları arayabilir ve kaldırabilirsiniz. Aşağıdaki örnek, "CONFIDENTIAL" metin filigranını bulur ve kaldırır, temiz bir belge üretir.

## Remove text watermarks

Kaldırılan bir öğenin kalan indeksleri kaydırmaması için arama sonuçlarını ters yönde yineleyin ve her eşleşme için `remove()` metodunu çağırın.

{{< tabs "code-example-clear">}}
{{< tab "clear_watermark.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

def clear_watermark():
    with Watermarker("./watermarked-document.pdf") as watermarker:
        possible = watermarker.search(TextSearchCriteria("CONFIDENTIAL"))
        # Öğeler silinirken indekslerin geçerli kalması için ters yönde kaldırın
        for i in range(len(possible) - 1, -1, -1):
            watermarker.remove(possible[i])
        watermarker.save("./output.pdf")

if __name__ == "__main__":
    clear_watermark()
```
{{< /tab >}}
{{< tab "watermarked-document.pdf" >}}

`watermarked-document.pdf` bu örnekte kullanılan örnek dosyadır. İndirmek için [buraya](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/clear/watermarked-document.pdf) tıklayın.

{{< /tab >}}
{{< tab \"output.pdf\" >}}
```text
Binary file (PDF, 360 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/clear/clear_watermark/output.pdf)
{{< /tab >}}
{{< /tabs >}}

**Use case:** Remove outdated labels such as "Draft" or "Internal Use Only" before sharing a document externally.

## Remove image watermarks

Görsel filigranlar algısal karma (perceptual hashing) ile bulunabilir ve aynı şekilde kaldırılabilir:

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
        # Öğeler silinirken indekslerin geçerli kalması için ters yönde kaldırın
        for i in range(len(possible) - 1, -1, -1):
            watermarker.remove(possible[i])
        watermarker.save("./output.docx")

if __name__ == "__main__":
    clear_image_watermark()
```
{{< /tab >}}
{{< tab "watermarked-document.docx" >}}

`watermarked-document.docx` ve `logo.png` bu örnekte kullanılan örnek dosyalardır. [watermarked-document.docx](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/clear/watermarked-document.docx) ve [logo.png](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/clear/logo.png) dosyalarını indirin.

{{< /tab >}}
{{< tab "output.docx" >}}
```text
Binary file (DOCX, 13 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/clear/clear_image_watermark/output.docx)
{{< /tab >}}
{{< /tabs >}}
