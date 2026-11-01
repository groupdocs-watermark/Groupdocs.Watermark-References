---
title: "__init__ yapıcı"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "EmailPreviewOptions sınıfının yeni bir örneğini başlatır ve çıktı akışını kapatır."
type: docs
url: /tr/python-net/groupdocs.watermark.options.email/emailpreviewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_page_stream}

Yeni bir [`EmailPreviewOptions`](/watermark/python-net/groupdocs.watermark.options.email/emailpreviewoptions/) sınıfı örneği başlatır ve çıktı akışının kapatılmasına neden olur.

```python
def __init__(self, create_page_stream):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Belirli bir sayfa önizlemesi için bir akış oluşturur. |

## __init__ {#create_page_stream-release_page_stream}

Yeni bir EmailPreviewOptions sınıfı örneği başlatır ve çıktı akışının daha sonraki kullanım için istemciye geri döndürülmesine neden olur.

```python
def __init__(self, create_page_stream, release_page_stream):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Belirli bir sayfa önizlemesi için bir akış oluşturur. |
| release_page_stream | `ReleasePageStream` | Sayfa önizlemesi oluşturmanın tamamlandığını bildirir ve çıktı akışını alır. |

### Ayrıca Bakınız
* class [`EmailPreviewOptions`](/watermark/python-net/groupdocs.watermark.options.email/emailpreviewoptions/)
