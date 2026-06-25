---
title: __init__ constructor
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.watermark.options.spreadsheet/spreadsheetpreviewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_page_stream}

Initializes a new instance of the SpreadsheetPreviewOptions class causing the output stream to be closed.

```python
def __init__(self, create_page_stream):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Creates a stream for a specific page preview. |

## __init__ {#create_page_stream-release_page_stream}

Initializes a new instance of [`SpreadsheetPreviewOptions`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetpreviewoptions/) that returns the output stream to the client for further use.

```python
def __init__(self, create_page_stream, release_page_stream):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Creates a stream for a specific page preview. |
| release_page_stream | `ReleasePageStream` | Notifies that the page preview generation is done and gets the output stream. |

### See Also
* class [`SpreadsheetPreviewOptions`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetpreviewoptions/)
