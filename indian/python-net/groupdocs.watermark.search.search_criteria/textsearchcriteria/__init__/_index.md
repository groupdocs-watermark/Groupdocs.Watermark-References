---
title: "__init__ कंस्ट्रक्टर"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "निर्दिष्ट नियमित अभिव्यक्ति के साथ नया TextSearchCriteria प्रारंभ करता है।"
type: docs
url: /hi/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/__init__/
is_root: false
weight: 10
---


## __init__ {#pattern}

निर्दिष्ट नियमित अभिव्यक्ति के साथ नया TextSearchCriteria प्रारंभ करता है।

```python
def __init__(self, pattern):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| pattern | `System.Text.RegularExpressions.Regex` | मैच करने के लिए रेगुलर एक्सप्रेशन। |

### उदाहरण

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

with Watermarker("./document.pdf") as watermarker:
    criteria = TextSearchCriteria("CONFIDENTIAL")
    results = watermarker.search(criteria)
    print("Found", len(results), "possible watermark(s)")
```

## __init__ {#search_string-is_match_case}

खोज स्ट्रिंग और केस‑सेंसिटिव तुलना के लिए फ़्लैग के साथ [`TextSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/) वर्ग का एक नया इंस्टेंस प्रारंभ करता है।

```python
def __init__(self, search_string, is_match_case):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| search_string | `str` | खोजने के लिए सटीक स्ट्रिंग। |
| is_match_case | `bool` | तुलना के दौरान केस को अनदेखा करने के लिए False; अन्यथा True। |

### उदाहरण

```python
    from groupdocs.watermark import Watermarker
    from groupdocs.watermark.search.search_criteria import TextSearchCriteria

    with Watermarker("./document.pdf") as watermarker:
        criteria = TextSearchCriteria("CONFIDENTIAL", False)
        results = watermarker.search(criteria)
        print("Found", len(results), "possible watermark(s)")
    ```

## __init__ {#search_string}

खोज स्ट्रिंग के साथ [`TextSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/) वर्ग का एक नया इंस्टेंस प्रारंभ करता है।

```python
def __init__(self, search_string):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| search_string | `str` | खोजने के लिए सटीक स्ट्रिंग। |

### उदाहरण

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

def search_by_text():
    with Watermarker("./document.pdf") as watermarker:
        possible = watermarker.search(TextSearchCriteria("CONFIDENTIAL"))
        print("Found", len(possible), "possible watermark(s)")

if __name__ == "__main__":
    search_by_text()
```

### संबंधित देखें
* class [`TextSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/)
