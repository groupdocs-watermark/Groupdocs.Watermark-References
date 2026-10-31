---
title: "Hapus watermark"
linkTitle: "Clear watermarks"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Cari dan hapus watermark teks atau gambar yang ada menggunakan GroupDocs.Watermark untuk Python melalui .NET."
type: docs
url: /id/python-net/guides/clear/
is_root: false
weight: 100
---


Anda dapat mencari watermark yang ada dalam dokumen dan menghapusnya. Contoh di bawah menemukan watermark teks \"CONFIDENTIAL\" dan menghapusnya, menghasilkan dokumen bersih.

## Remove text watermarks

Iterasi hasil pencarian secara terbalik sehingga menghapus sebuah item tidak menggeser indeks yang masih akan dikunjungi, dan panggil `remove()` untuk setiap kecocokan.

{{< tabs "code-example-clear">}}
{{< tab "clear_watermark.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

def clear_watermark():
    with Watermarker("./watermarked-document.pdf") as watermarker:
        possible = watermarker.search(TextSearchCriteria("CONFIDENTIAL"))
        # Hapus secara terbalik sehingga indeks tetap valid saat item dihapus
        for i in range(len(possible) - 1, -1, -1):
            watermarker.remove(possible[i])
        watermarker.save("./output.pdf")

if __name__ == "__main__":
    clear_watermark()
```
{{< /tab >}}
{{< tab "watermarked-document.pdf" >}}

`watermarked-document.pdf` adalah file contoh yang digunakan dalam contoh ini. Klik [di sini](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/clear/watermarked-document.pdf) untuk mengunduhnya.

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

Watermark gambar dapat ditemukan dengan hashing perseptual dan dihapus dengan cara yang sama:

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
        # Hapus secara terbalik sehingga indeks tetap valid saat item dihapus
        for i in range(len(possible) - 1, -1, -1):
            watermarker.remove(possible[i])
        watermarker.save("./output.docx")

if __name__ == "__main__":
    clear_image_watermark()
```
{{< /tab >}}
{{< tab "watermarked-document.docx" >}}

`watermarked-document.docx` dan `logo.png` adalah file contoh yang digunakan dalam contoh ini. Unduh [watermarked-document.docx](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/clear/watermarked-document.docx) dan [logo.png](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/clear/logo.png).

{{< /tab >}}
{{< tab "output.docx" >}}
```text
Binary file (DOCX, 13 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/clear/clear_image_watermark/output.docx)
{{< /tab >}}
{{< /tabs >}}
