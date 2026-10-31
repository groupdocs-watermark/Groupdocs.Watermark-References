---
title: "__init__ कंस्ट्रक्टर"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "एक नया PreviewOptions इंस्टेंस प्रारंभ करता है जो उपयोग के बाद आउटपुट स्ट्रीम को बंद कर देता है।"
type: docs
url: /hi/python-net/groupdocs.watermark.options/previewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_page_stream}

एक नया PreviewOptions इंस्टेंस प्रारंभ करता है जो उपयोग के बाद आउटपुट स्ट्रीम को बंद कर देता है।

```python
def __init__(self, create_page_stream):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Callable[[int], io.RawIOBase] – एक विशिष्ट पृष्ठ पूर्वावलोकन के लिए स्ट्रीम बनाता है। |

### उदाहरण

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options import PreviewOptions, PreviewFormats

def generate_preview():
    # प्रत्येक पृष्ठ को रेंडर करने के लिए एक लिखने योग्य फ़ाइल स्ट्रीम प्रदान करें
    def create_page_stream(page_number):
        return open(f"./output-page-{page_number}.png", "wb")

    with Watermarker("./sample.pdf") as watermarker:
        options = PreviewOptions(create_page_stream)
        options.preview_format = PreviewFormats.PNG
        options.page_numbers = [1, 2]
        watermarker.generate_preview(options)

if __name__ == "__main__":
    generate_preview()
```

## __init__ {#create_page_stream-release_page_stream}

एक नया PreviewOptions इंस्टेंस प्रारंभ करता है जो क्लाइंट को आगे उपयोग के लिए आउटपुट स्ट्रीम लौटाता है।

```python
def __init__(self, create_page_stream, release_page_stream):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | एक Callable जो एक विशिष्ट पृष्ठ पूर्वावलोकन के लिए स्ट्रीम बनाता है। पृष्ठ संख्या (`int`) प्राप्त करता है और एक लिखने योग्य स्ट्रीम (`io.RawIOBase`) लौटाना चाहिए। |
| release_page_stream | `ReleasePageStream` | एक Callable जो पृष्ठ पूर्वावलोकन निर्माण पूर्ण होने पर बुलाया जाता है और आउटपुट स्ट्रीम प्रदान करता है। |

### उदाहरण

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options import PreviewOptions, PreviewFormats

def generate_preview():
    # प्रत्येक पृष्ठ को रेंडर करने के लिए एक लिखने योग्य फ़ाइल स्ट्रीम प्रदान करें
    def create_page_stream(page_number):
        return open(f"./output-page-{page_number}.png", "wb")

    with Watermarker("./sample.pdf") as watermarker:
        options = PreviewOptions(create_page_stream)
        options.preview_format = PreviewFormats.PNG
        options.page_numbers = [1, 2]
        watermarker.generate_preview(options)

if __name__ == "__main__":
    generate_preview()
```

### संबंधित देखें
* class [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/)
