---
title: "__init__ कंस्ट्रक्टर"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "SpreadsheetPreviewOptions वर्ग का एक नया उदाहरण प्रारंभ करता है, जिससे आउटपुट स्ट्रीम बंद हो जाता है।"
type: docs
url: /hi/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetpreviewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_page_stream}

SpreadsheetPreviewOptions वर्ग का एक नया उदाहरण प्रारंभ करता है, जिससे आउटपुट स्ट्रीम बंद हो जाता है।

```python
def __init__(self, create_page_stream):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | एक विशिष्ट पेज प्रीव्यू के लिए स्ट्रीम बनाता है। |

## __init__ {#create_page_stream-release_page_stream}

SpreadsheetPreviewOptions वर्ग का एक नया उदाहरण प्रारंभ करता है, जिससे आउटपुट स्ट्रीम क्लाइंट को आगे उपयोग के लिए वापस किया जाता है।

```python
def __init__(self, create_page_stream, release_page_stream):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | एक विशिष्ट पेज प्रीव्यू के लिए स्ट्रीम बनाता है। |
| release_page_stream | `ReleasePageStream` | सूचित करता है कि पेज प्रीव्यू जेनरेशन पूरा हो गया है और आउटपुट स्ट्रीम प्राप्त करता है। |

### संबंधित देखें
* class [`SpreadsheetPreviewOptions`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetpreviewoptions/)
