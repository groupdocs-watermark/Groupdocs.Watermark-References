---
title: "metode generate_preview"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Menghasilkan gambar pratinjau untuk dokumen."
type: docs
url: /id/python-net/groupdocs.watermark/watermarker/generate_preview/
is_root: false
weight: 1040
---


## generate_preview {#preview_options}

Menghasilkan gambar pratinjau untuk dokumen.

```python
def generate_preview(self, preview_options):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| preview_options | `PreviewOptions` | Opsi tambahan yang dapat digunakan saat menghasilkan gambar pratinjau. |

### Contoh

```python
    from groupdocs.watermark import Watermarker
    from groupdocs.watermark.options import PreviewOptions, PreviewFormats

    def generate_preview():
        # Sediakan aliran file yang dapat ditulis untuk setiap halaman yang akan dirender
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

### Lihat Juga
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
