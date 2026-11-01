---
title: "__init__ yapıcı"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "SpreadsheetPreviewOptions sınıfının yeni bir örneğini başlatır, çıktı akışının kapanmasına neden olur."
type: docs
url: /tr/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetpreviewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_page_stream}

SpreadsheetPreviewOptions sınıfının yeni bir örneğini başlatır, çıktı akışının kapanmasına neden olur.

```python
def __init__(self, create_page_stream):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Belirli bir sayfa önizlemesi için bir akış oluşturur. |

## __init__ {#create_page_stream-release_page_stream}

SpreadsheetPreviewOptions sınıfının yeni bir örneğini başlatır, çıktı akışının daha sonraki kullanım için istemciye geri döndürülmesini sağlar.

```python
def __init__(self, create_page_stream, release_page_stream):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Belirli bir sayfa önizlemesi için bir akış oluşturur. |
| release_page_stream | `ReleasePageStream` | Sayfa önizlemesi oluşturmanın tamamlandığını bildirir ve çıktı akışını alır. |

### Ayrıca Bakınız
* class [`SpreadsheetPreviewOptions`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetpreviewoptions/)
