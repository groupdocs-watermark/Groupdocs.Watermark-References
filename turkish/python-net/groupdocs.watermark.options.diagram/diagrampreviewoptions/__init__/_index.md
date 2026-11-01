---
title: "__init__ yapıcı"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "DiagramPreviewOptions sınıfının yeni bir örneğini başlatır ve çıktı akışını kapatır."
type: docs
url: /tr/python-net/groupdocs.watermark.options.diagram/diagrampreviewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_page_stream}

Çıktı akışının kapatılmasına neden olacak şekilde yeni bir [`DiagramPreviewOptions`](/watermark/python-net/groupdocs.watermark.options.diagram/diagrampreviewoptions/) sınıfının örneğini başlatır.

```python
def __init__(self, create_page_stream):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Belirli bir sayfa önizlemesi için bir akış oluşturur. |

## __init__ {#create_page_stream-release_page_stream}

Çıktı akışının istemciye daha fazla kullanım için geri döndürülmesine neden olacak şekilde yeni bir [`DiagramPreviewOptions`](/watermark/python-net/groupdocs.watermark.options.diagram/diagrampreviewoptions/) sınıfının örneğini başlatır.

```python
def __init__(self, create_page_stream, release_page_stream):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Belirli bir sayfa önizlemesi için bir akış oluşturur. |
| release_page_stream | `ReleasePageStream` | Sayfa önizlemesi oluşturmanın tamamlandığını bildirir ve çıktı akışını alır. |

### Ayrıca Bakınız
* class [`DiagramPreviewOptions`](/watermark/python-net/groupdocs.watermark.options.diagram/diagrampreviewoptions/)
