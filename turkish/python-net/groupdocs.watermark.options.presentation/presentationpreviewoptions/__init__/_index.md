---
title: "__init__ yapıcı"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "Çıktı akışının kapanmasına neden olarak yeni bir PresentationPreviewOptions sınıfı örneği başlatır."
type: docs
url: /tr/python-net/groupdocs.watermark.options.presentation/presentationpreviewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_page_stream}

Çıktı akışının kapanmasına neden olarak yeni bir PresentationPreviewOptions sınıfı örneği başlatır.

```python
def __init__(self, create_page_stream):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Belirli bir sayfa önizlemesi için bir akış oluşturur. |

## __init__ {#create_page_stream-release_page_stream}

Çıktı akışının istemciye daha fazla kullanım için geri gönderilmesine neden olarak yeni bir [`PresentationPreviewOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationpreviewoptions/) örneği başlatır.

```python
def __init__(self, create_page_stream, release_page_stream):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Belirli bir sayfa önizlemesi için bir akış oluşturur. |
| release_page_stream | `ReleasePageStream` | Sayfa önizlemesi oluşturmanın tamamlandığını bildirir ve çıktı akışını alır. |

### Ayrıca Bakınız
* class [`PresentationPreviewOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationpreviewoptions/)
