---
title: __init__ constructor
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.watermark.options.email/emailpreviewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_page_stream}

Initializes a new EmailPreviewOptions instance that closes the output stream.

```python
def __init__(self, create_page_stream):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Creates a stream for a specific page preview. |

## __init__ {#create_page_stream-release_page_stream}

Initializes a new EmailPreviewOptions instance that returns the output stream to the client for further use.

```python
def __init__(self, create_page_stream, release_page_stream):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Creates a stream for a specific page preview. |
| release_page_stream | `ReleasePageStream` | Notifies that the page preview generation is done and gets the output stream. |

### See Also
* class [`EmailPreviewOptions`](/watermark/python-net/groupdocs.watermark.options.email/emailpreviewoptions/)
