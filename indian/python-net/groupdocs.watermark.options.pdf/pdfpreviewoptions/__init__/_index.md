---
title: "__init__ कंस्ट्रक्टर"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "PdfPreviewOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है जिससे आउटपुट स्ट्रीम बंद हो जाती है।"
type: docs
url: /hi/python-net/groupdocs.watermark.options.pdf/pdfpreviewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_page_stream}

एक नया उदाहरण बनाता है [`PdfPreviewOptions`](/watermark/python-net/groupdocs.watermark.options.pdf/pdfpreviewoptions/) क्लास का, जिससे आउटपुट स्ट्रीम बंद हो जाता है।

```python
def __init__(self, create_page_stream):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | एक विशिष्ट पेज प्रीव्यू के लिए स्ट्रीम बनाता है। |

## __init__ {#create_page_stream-release_page_stream}

एक नया PdfPreviewOptions उदाहरण बनाता है जो आउटपुट स्ट्रीम को आगे के उपयोग के लिए क्लाइंट को वापस करता है।

```python
def __init__(self, create_page_stream, release_page_stream):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | एक विशिष्ट पेज प्रीव्यू के लिए स्ट्रीम बनाता है। |
| release_page_stream | `ReleasePageStream` | सूचित करता है कि पेज प्रीव्यू जेनरेशन पूरा हो गया है और आउटपुट स्ट्रीम प्राप्त करता है। |

### संबंधित देखें
* class [`PdfPreviewOptions`](/watermark/python-net/groupdocs.watermark.options.pdf/pdfpreviewoptions/)
