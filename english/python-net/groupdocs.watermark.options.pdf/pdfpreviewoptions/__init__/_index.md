---
title: __init__ constructor
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.watermark.options.pdf/pdfpreviewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_page_stream}

Initializes a new PdfPreviewOptions instance that causes the output stream to be closed.

```python
def __init__(self, create_page_stream):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Creates a stream for a specific page preview. |

## __init__ {#create_page_stream-release_page_stream}

Initializes a new instance of [`PdfPreviewOptions`](/watermark/python-net/groupdocs.watermark.options.pdf/pdfpreviewoptions/) class causing the output stream to be returned to the client for further use.

```python
def __init__(self, create_page_stream, release_page_stream):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Creates a stream for a specific page preview. |
| release_page_stream | `ReleasePageStream` | Notifies that the page preview generation is done and gets the output stream. |

### See Also
* class [`PdfPreviewOptions`](/watermark/python-net/groupdocs.watermark.options.pdf/pdfpreviewoptions/)
