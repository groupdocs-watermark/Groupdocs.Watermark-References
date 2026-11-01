---
title: "__init__ yapıcı"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "Kullanımdan sonra çıktı akışını kapatan yeni bir PreviewOptions örneği başlatır."
type: docs
url: /tr/python-net/groupdocs.watermark.options/previewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_page_stream}

Kullanımdan sonra çıktı akışını kapatan yeni bir PreviewOptions örneği başlatır.

```python
def __init__(self, create_page_stream):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Callable[[int], io.RawIOBase] – Belirli bir sayfa önizlemesi için bir akış oluşturur. |

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

## __init__ {#create_page_stream-release_page_stream}

Çıktı akışını istemciye daha sonraki kullanım için döndüren yeni bir PreviewOptions örneği başlatır.

```python
def __init__(self, create_page_stream, release_page_stream):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Belirli bir sayfa önizlemesi için bir akış oluşturan Callable. Sayfa numarasını (`int`) alır ve yazılabilir bir akış (`io.RawIOBase`) döndürmelidir. |
| release_page_stream | `ReleasePageStream` | Sayfa önizlemesi oluşturulması tamamlandığında çağrılan ve çıktı akışını sağlayan Callable. |

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
* class [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/)
