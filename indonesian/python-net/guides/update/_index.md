---
title: "Perbarui watermark"
linkTitle: "Update watermarks"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Cari watermark teks atau gambar yang ada dan perbarui mereka menggunakan GroupDocs.Watermark untuk Python melalui .NET."
type: docs
url: /id/python-net/guides/update/
is_root: false
weight: 90
---


Anda dapat mencari watermark yang ada dalam dokumen dan memodifikasinya secara langsung — misalnya, mengganti teks watermark teks atau menukar gambar watermark gambar.

## Update text watermarks

Cari watermark berdasarkan konten teksnya, lalu tetapkan nilai baru untuk setiap kecocokan. Contoh di bawah membuka dokumen yang sudah berisi watermark \"CONFIDENTIAL\" dan menggantinya dengan \"APPROVED\".

{{< tabs "code-example-update">}}
{{< tab "update_watermark.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

def update_watermark():
    with Watermarker("./watermarked-document.pdf") as watermarker:
        # Temukan watermark yang teksnya cocok dengan kriteria
        possible = watermarker.search(TextSearchCriteria("CONFIDENTIAL"))
        print("Found", len(possible), "possible watermark(s).")
        for watermark in possible:
            try:
                watermark.text = "APPROVED"
            except Exception:
                # Beberapa entitas yang ditemukan tidak mendukung penyuntingan teks — lewati mereka
                pass
        watermarker.save("./output.pdf")

if __name__ == "__main__":
    update_watermark()
```
{{< /tab >}}
{{< tab "watermarked-document.pdf" >}}

`watermarked-document.pdf` adalah file contoh yang digunakan dalam contoh ini. Klik [di sini](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/update/watermarked-document.pdf) untuk mengunduhnya.

{{< /tab >}}
{{< tab "output.pdf" >}}
```text
Binary file (PDF, 444 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/update/update_watermark/output.pdf)
{{< /tab >}}
{{< /tabs >}}

## Update image watermarks

Watermark gambar dapat ditemukan dengan hashing perseptual ([`ImageDctHashSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagedcthashsearchcriteria/)) dan diperbarui dengan menetapkan byte baru ke `image_data`. Contoh di bawah menemukan watermark logo dan menggantinya dengan stempel \"APPROVED\":

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
                # Beberapa entitas yang ditemukan tidak mendukung penyuntingan gambar — lewati mereka
                pass
        watermarker.save("./output.docx")

if __name__ == "__main__":
    update_image_watermark()
```
{{< /tab >}}
{{< tab "watermarked-document.docx" >}}

`watermarked-document.docx`, `logo.png`, dan `stamp.png` adalah file contoh yang digunakan dalam contoh ini. Unduh [watermarked-document.docx](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/update/watermarked-document.docx), [logo.png](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/update/logo.png), dan [stamp.png](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/update/stamp.png).

{{< /tab >}}
{{< tab "output.docx" >}}
```text
Binary file (DOCX, 19 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/update/update_image_watermark/output.docx)
{{< /tab >}}
{{< /tabs >}}
