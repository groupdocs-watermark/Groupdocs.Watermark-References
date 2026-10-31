---
title: "__init__ कंस्ट्रक्टर"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "निर्दिष्ट फ़ाइल पथ के साथ एक नया ImageDctHashSearchCriteria इंस्टेंस प्रारंभ करता है।"
type: docs
url: /hi/python-net/groupdocs.watermark.search.search_criteria/imagedcthashsearchcriteria/__init__/
is_root: false
weight: 10
---


## __init__ {#file_path}

निर्दिष्ट फ़ाइल पथ के साथ एक नया ImageDctHashSearchCriteria इंस्टेंस प्रारंभ करता है।

```python
def __init__(self, file_path):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| file_path | `str` | फ़ाइल पथ जिससे छवि लोड की जाएगी। |

### उदाहरण

```python
    from groupdocs.watermark.search.search_criteria import ImageDctHashSearchCriteria

    criteria = ImageDctHashSearchCriteria("./logo.png")
    ```

## __init__ {#stream}

प्रदान किए गए इमेज स्ट्रीम के साथ एक नया ImageDctHashSearchCriteria इंस्टेंस प्रारंभ करता है।

```python
def __init__(self, stream):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| stream | `io.RawIOBase` | स्ट्रीम जिससे छवि लोड की जाएगी। |

### संबंधित देखें
* class [`ImageDctHashSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagedcthashsearchcriteria/)
