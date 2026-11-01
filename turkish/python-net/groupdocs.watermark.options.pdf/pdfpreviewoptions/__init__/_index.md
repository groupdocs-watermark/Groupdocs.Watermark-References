---
title: "__init__ yapıcı"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "PdfPreviewOptions sınıfının yeni bir örneğini başlatır ve çıktı akışının kapatılmasına neden olur."
type: docs
url: /tr/python-net/groupdocs.watermark.options.pdf/pdfpreviewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_page_stream}

Yeni bir [`PdfPreviewOptions`](/watermark/python-net/groupdocs.watermark.options.pdf/pdfpreviewoptions/) sınıfı örneği başlatır ve çıktı akışının kapatılmasına neden olur.

```python
def __init__(self, create_page_stream):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Belirli bir sayfa önizlemesi için bir akış oluşturur. |

## __init__ {#create_page_stream-release_page_stream}

Yeni bir PdfPreviewOptions örneği başlatır ve çıktı akışını daha sonraki kullanım için istemciye döndürür.

```python
def __init__(self, create_page_stream, release_page_stream):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Belirli bir sayfa önizlemesi için bir akış oluşturur. |
| release_page_stream | `ReleasePageStream` | Sayfa önizlemesi oluşturmanın tamamlandığını bildirir ve çıktı akışını alır. |

### Ayrıca Bakınız
* class [`PdfPreviewOptions`](/watermark/python-net/groupdocs.watermark.options.pdf/pdfpreviewoptions/)
