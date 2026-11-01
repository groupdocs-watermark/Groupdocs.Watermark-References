---
title: "PreviewOptions sınıfı"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "Önizleme oluşturma için gereksinimleri ve akış delegelerini ayarlama seçenekleri sağlar."
type: docs
url: /tr/python-net/groupdocs.watermark.options/previewoptions/
is_root: false
weight: 60
---


## PreviewOptions class

Önizleme oluşturma için gereksinimleri ve akış delegelerini ayarlama seçenekleri sağlar.

PreviewOptions türü aşağıdaki üyeleri gösterir:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options/previewoptions/__init__/#create_page_stream) | Kullanımdan sonra çıktı akışını kapatan yeni bir PreviewOptions örneği başlatır. |
| [__init__](/watermark/python-net/groupdocs.watermark.options/previewoptions/__init__/#create_page_stream-release_page_stream) | Çıktı akışını istemciye daha sonraki kullanım için döndüren yeni bir PreviewOptions örneği başlatır. |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [create_page_stream](/watermark/python-net/groupdocs.watermark.options/previewoptions/create_page_stream/) | Her işlenen sayfa için yazılabilir bir akış elde etmek amacıyla kullanılan sayfa akışı oluşturma temsilcisi. |
| [height](/watermark/python-net/groupdocs.watermark.options/previewoptions/height/) | Sayfa önizleme yüksekliği. |
| [page_numbers](/watermark/python-net/groupdocs.watermark.options/previewoptions/page_numbers/) | Önizlemeler oluşturulacak sayfa numaralarının dizisi. |
| [preview_format](/watermark/python-net/groupdocs.watermark.options/previewoptions/preview_format/) | Önizleme görüntü biçimi. |
| [release_page_stream](/watermark/python-net/groupdocs.watermark.options/previewoptions/release_page_stream/) | Sayfa önizleme tamamlanma temsilcisi. |
| [width](/watermark/python-net/groupdocs.watermark.options/previewoptions/width/) | Sayfa önizleme genişliği. |

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

### Guides
`PreviewOptions` kullanan görev kılavuzları:

* [Document preview](/watermark/python-net/guides/preview/)

### Ayrıca Bakınız
* module [`groupdocs.watermark.options`](/watermark/python-net/groupdocs.watermark.options/)
