---
title: "generate_preview metodu"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "Belge için önizleme görselleri oluşturur."
type: docs
url: /tr/python-net/groupdocs.watermark/watermarker/generate_preview/
is_root: false
weight: 1040
---


## generate_preview {#preview_options}

Belge için önizleme görselleri oluşturur.

```python
def generate_preview(self, preview_options):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| preview_options | `PreviewOptions` | Önizleme görüntüleri oluştururken kullanılacak ek seçenekler. |

### Örnek

```python
    from groupdocs.watermark import Watermarker
    from groupdocs.watermark.options import PreviewOptions, PreviewFormats

    def generate_preview():
        # Her sayfayı renderlemek için yazılabilir bir dosya akışı sağlayın
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

### Ayrıca Bakınız
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
