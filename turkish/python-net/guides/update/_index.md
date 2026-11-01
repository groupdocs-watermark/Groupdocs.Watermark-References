---
title: "Filigranları güncelle"
linkTitle: "Update watermarks"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "GroupDocs.Watermark for Python via .NET kullanarak mevcut metin veya resim filigranlarını arayın ve güncelleyin."
type: docs
url: /tr/python-net/guides/update/
is_root: false
weight: 90
---


Bir belgede mevcut filigranları arayabilir ve yerinde değiştirebilirsiniz — örneğin, bir metin filigranının metnini değiştirebilir veya bir resim filigranının görselini değiştirebilirsiniz.

## Update text watermarks

Filigranı metin içeriğine göre arayın, ardından her eşleşmeye yeni bir değer atayın. Aşağıdaki örnek, zaten "CONFIDENTIAL" filigranı içeren bir belgeyi açar ve onu "APPROVED" ile değiştirir.

{{< tabs "code-example-update">}}
{{< tab "update_watermark.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

def update_watermark():
    with Watermarker("./watermarked-document.pdf") as watermarker:
        # Kriterle eşleşen metinlere sahip filigranları bulun
        possible = watermarker.search(TextSearchCriteria("CONFIDENTIAL"))
        print("Found", len(possible), "possible watermark(s).")
        for watermark in possible:
            try:
                watermark.text = "APPROVED"
            except Exception:
                # Bulunan bazı varlıklar metin düzenlemeyi desteklemez — atlayın
                pass
        watermarker.save("./output.pdf")

if __name__ == "__main__":
    update_watermark()
```
{{< /tab >}}
{{< tab "watermarked-document.pdf" >}}

`watermarked-document.pdf` bu örnekte kullanılan örnek dosyadır. İndirmek için [buraya](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/update/watermarked-document.pdf) tıklayın.

{{< /tab >}}
{{< tab \"output.pdf\" >}}
```text
Binary file (PDF, 444 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/update/update_watermark/output.pdf)
{{< /tab >}}
{{< /tabs >}}

## Update image watermarks

Görsel filigranlar algısal karma (perceptual hashing) ile bulunabilir ([`ImageDctHashSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagedcthashsearchcriteria/)) ve `image_data`'ya yeni baytlar atanarak güncellenebilir. Aşağıdaki örnek, logo filigranını bulur ve onu "APPROVED" damgası ile değiştirir:

{{< tabs \"code-example-update-image\">}}
{{< tab \"update_image_watermark.py\" >}}
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
                # Bulunan bazı varlıklar görüntü düzenlemeyi desteklemiyor — atlayın.
                pass
        watermarker.save("./output.docx")

if __name__ == "__main__":
    update_image_watermark()
```
{{< /tab >}}
{{< tab "watermarked-document.docx" >}}

`watermarked-document.docx`, `logo.png` ve `stamp.png` bu örnekte kullanılan örnek dosyalardır. [watermarked-document.docx](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/update/watermarked-document.docx), [logo.png](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/update/logo.png) ve [stamp.png](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/update/stamp.png) dosyalarını indirin.

{{< /tab >}}
{{< tab "output.docx" >}}
```text
Binary file (DOCX, 19 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/update/update_image_watermark/output.docx)
{{< /tab >}}
{{< /tabs >}}
