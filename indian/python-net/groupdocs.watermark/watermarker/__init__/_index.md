---
title: "__init__ कंस्ट्रक्टर"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "निर्दिष्ट दस्तावेज़ पथ के साथ एक नया Watermarker उदाहरण प्रारंभ करता है।"
type: docs
url: /hi/python-net/groupdocs.watermark/watermarker/__init__/
is_root: false
weight: 10
---


## __init__ {#file_path}

निर्दिष्ट दस्तावेज़ पथ के साथ एक नया Watermarker उदाहरण प्रारंभ करता है।

दस्तावेज़ लोड करने के बारे में अधिक जानें: https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, file_path):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| file_path | `str` | दस्तावेज़ लोड करने के लिए फ़ाइल पथ। |

| उठाता है | विवरण |
| :- | :- |
| `UnsupportedFileTypeException` | प्रदान किया गया दस्तावेज़ प्रकार समर्थित नहीं है। |
| `InvalidPasswordException` | प्रदान किया गया पासवर्ड गलत है। |

### उदाहरण

```python
from groupdocs.watermark import Watermarker

# एक दस्तावेज़ लोड करें।
watermarker = Watermarker("./document.pdf")
# वॉटरमार्क जोड़ने, खोजने या हटाने के लिए Watermarker मेथड्स का उपयोग करें।

# दस्तावेज़ सहेजें।
watermarker.save("./output.pdf")
```

## __init__ {#file_path-options}

निर्दिष्ट दस्तावेज़ पथ और लोड विकल्पों के साथ एक नया Watermarker उदाहरण प्रारंभ करता है।

दस्तावेज़ लोड करने के बारे में अधिक जानें: https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, file_path, options):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| file_path | `str` | दस्तावेज़ लोड करने के लिए फ़ाइल पथ। |
| options | `LoadOptions` | दस्तावेज़ लोड करते समय उपयोग करने के लिए अतिरिक्त विकल्प। |

| उठाता है | विवरण |
| :- | :- |
| `UnsupportedFileTypeException` | प्रदान किया गया दस्तावेज़ प्रकार समर्थित नहीं है। |
| `InvalidPasswordException` | प्रदान किया गया पासवर्ड गलत है। |

### उदाहरण

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.pdf import PdfLoadOptions

load_options = PdfLoadOptions()
load_options.password = "123"

with Watermarker(r"C:\Documents\test.pdf", load_options) as watermarker:
    # एन्क्रिप्टेड PDF पर संचालन करें
    pass
```

## __init__ {#file_path-settings}

निर्दिष्ट दस्तावेज़ पथ और सेटिंग्स के साथ एक Watermarker प्रारंभ करता है।

दस्तावेज़ लोड करने के बारे में अधिक जानें: https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, file_path, settings):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| file_path | `str` | दस्तावेज़ लोड करने के लिए फ़ाइल पथ। |
| settings | `WatermarkerSettings` | लोड किए गए दस्तावेज़ के साथ काम करते समय उपयोग करने के लिए अतिरिक्त सेटिंग्स। |

| उठाता है | विवरण |
| :- | :- |
| `UnsupportedFileTypeException` | प्रदान किया गया दस्तावेज़ प्रकार समर्थित नहीं है। |
| `InvalidPasswordException` | प्रदान किया गया पासवर्ड गलत है। |

### उदाहरण

```python
from groupdocs.watermark import Watermarker, WatermarkerSettings
from groupdocs.watermark.search.objects import SearchableObjects
from groupdocs.watermark.search.objects import WordProcessingSearchableObjects, SpreadsheetSearchableObjects, PresentationSearchableObjects, DiagramSearchableObjects, PdfSearchableObjects

settings = WatermarkerSettings()
settings.searchable_objects = SearchableObjects(
    word_processing_searchable_objects=WordProcessingSearchableObjects.HYPERLINKS
                     | WordProcessingSearchableObjects.TEXT,
    spreadsheet_searchable_objects=SpreadsheetSearchableObjects.HEADERS_FOOTERS,
    presentation_searchable_objects=PresentationSearchableObjects.SLIDES_BACKGROUNDS
                  | PresentationSearchableObjects.SHAPES,
    diagram_searchable_objects=DiagramSearchableObjects.NONE,
    pdf_searchable_objects=PdfSearchableObjects.ALL,
)

with Watermarker("./document.pdf", settings) as watermarker:
    # watermarker के साथ काम करें, उदाहरण के लिए, वॉटरमार्क खोजें या हटाएँ
    pass
```

## __init__ {#file_path-options-settings}

निर्दिष्ट दस्तावेज़ पथ, लोड विकल्पों और सेटिंग्स के साथ एक नया Watermarker उदाहरण प्रारंभ करता है।

दस्तावेज़ लोड करने के बारे में अधिक जानें: https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, file_path, options, settings):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| file_path | `str` | दस्तावेज़ लोड करने के लिए फ़ाइल पथ। |
| options | `LoadOptions` | दस्तावेज़ लोड करते समय उपयोग करने के लिए अतिरिक्त विकल्प। |
| settings | `WatermarkerSettings` | लोड किए गए दस्तावेज़ के साथ काम करते समय उपयोग करने के अतिरिक्त सेटिंग्स। |

| उठाता है | विवरण |
| :- | :- |
| `UnsupportedFileTypeException` | प्रदान किया गया दस्तावेज़ प्रकार समर्थित नहीं है। |
| `InvalidPasswordException` | प्रदान किया गया पासवर्ड गलत है। |

### उदाहरण

```python
from groupdocs.watermark import Watermarker, WatermarkerSettings
from groupdocs.watermark.options.email import EmailLoadOptions
from groupdocs.watermark.search.search_criteria import TextSearchCriteria
from groupdocs.watermark.search.objects import SearchableObjects, EmailSearchableObjects

def search_email():
    settings = WatermarkerSettings()
    settings.searchable_objects = SearchableObjects(
        email_searchable_objects=(
            EmailSearchableObjects.Subject
            | EmailSearchableObjects.HtmlBody
            | EmailSearchableObjects.PlainTextBody
        )
    )
    load_options = EmailLoadOptions()
    with Watermarker("./test.msg", load_options, settings) as watermarker:
        criteria = TextSearchCriteria("test", False)
        watermarks = watermarker.search(criteria)
        watermarks.clear()
        watermarker.save()
```

## __init__ {#document}

निर्दिष्ट स्ट्रीम के साथ Watermarker क्लास का एक नया उदाहरण प्रारंभ करता है।

दस्तावेज़ लोड करने के बारे में अधिक जानें: https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, document):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| document | `io.RawIOBase` | दस्तावेज़ लोड करने के लिए स्ट्रीम। |

| उठाता है | विवरण |
| :- | :- |
| `UnsupportedFileTypeException` | प्रदान किया गया दस्तावेज़ प्रकार समर्थित नहीं है। |
| `InvalidPasswordException` | प्रदान किया गया पासवर्ड गलत है। |

### उदाहरण

```python
from groupdocs.watermark import Watermarker

def load_from_stream():
    with open("input.pdf", "rb") as input_stream, open("output.pdf", "wb") as output_stream:
        with Watermarker(input_stream) as watermarker:
            # वॉटरमार्क जोड़ने, खोजने या हटाने के लिए Watermarker के मेथड्स का उपयोग करें।
            watermarker.save(output_stream)
```

## __init__ {#document-options}

निर्दिष्ट स्ट्रीम और लोड विकल्पों के साथ एक नया Watermarker उदाहरण प्रारंभ करता है।

दस्तावेज़ लोड करने के बारे में अधिक जानें।

```python
def __init__(self, document, options):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| document | `io.RawIOBase` | दस्तावेज़ लोड करने के लिए स्ट्रीम। |
| options | `LoadOptions` | दस्तावेज़ लोड करते समय उपयोग करने के लिए अतिरिक्त विकल्प। |

| उठाता है | विवरण |
| :- | :- |
| `UnsupportedFileTypeException` | प्रदान किया गया दस्तावेज़ प्रकार समर्थित नहीं है। |
| `InvalidPasswordException` | प्रदान किया गया पासवर्ड गलत है। |

### उदाहरण

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.pdf import PdfLoadOptions

with open(r"C:\Documents\test.pdf", "rb") as file_stream:
    load_options = PdfLoadOptions()
    load_options.password = "123"
    with Watermarker(file_stream, load_options) as watermarker:
        # watermarker के साथ संचालन करें
        pass
```

## __init__ {#document-settings}

निर्दिष्ट स्ट्रीम और सेटिंग्स के साथ एक नया Watermarker उदाहरण प्रारंभ करता है।

दस्तावेज़ लोड करने के बारे में अधिक जानें।

```python
def __init__(self, document, settings):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| document | `io.RawIOBase` | दस्तावेज़ लोड करने के लिए स्ट्रीम। |
| settings | `WatermarkerSettings` | लोड किए गए दस्तावेज़ के साथ काम करते समय उपयोग करने के अतिरिक्त सेटिंग्स। |

| उठाता है | विवरण |
| :- | :- |
| `UnsupportedFileTypeException` | प्रदान किया गया दस्तावेज़ प्रकार समर्थित नहीं है। |
| `InvalidPasswordException` | प्रदान किया गया पासवर्ड गलत है। |

### उदाहरण

```python
from groupdocs.watermark import Watermarker, WatermarkerSettings
from groupdocs.watermark.search.objects import SearchableObjects
from groupdocs.watermark.search.objects import WordProcessingSearchableObjects, SpreadsheetSearchableObjects, PresentationSearchableObjects, DiagramSearchableObjects, PdfSearchableObjects

settings = WatermarkerSettings()
settings.searchable_objects = SearchableObjects(
    word_processing_searchable_objects=WordProcessingSearchableObjects.HYPERLINKS | WordProcessingSearchableObjects.TEXT,
    spreadsheet_searchable_objects=SpreadsheetSearchableObjects.HEADERS_FOOTERS,
    presentation_searchable_objects=PresentationSearchableObjects.SLIDES_BACKGROUNDS | PresentationSearchableObjects.SHAPES,
    diagram_searchable_objects=DiagramSearchableObjects.NONE,
    pdf_searchable_objects=PdfSearchableObjects.ALL,
)

for file_path in ["./document1.pdf", "./document2.docx"]:
    with open(file_path, "rb") as stream:
        with Watermarker(stream, settings) as watermarker:
            watermarks = watermarker.search()
            # पाए गए वॉटरमार्क के साथ काम करें
```

## __init__ {#document-options-settings}

निर्दिष्ट स्ट्रीम, लोड विकल्प और सेटिंग्स के साथ [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/) क्लास का एक नया उदाहरण प्रारंभ करता है।

दस्तावेज़ लोड करने के बारे में अधिक जानें पर https://docs.groupdocs.com/display/watermarknet/Loading+documents.

```python
def __init__(self, document, options, settings):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| document | `io.RawIOBase` | दस्तावेज़ लोड करने के लिए स्ट्रीम। |
| options | `LoadOptions` | दस्तावेज़ लोड करते समय उपयोग करने के लिए अतिरिक्त विकल्प। |
| settings | `WatermarkerSettings` | लोड किए गए दस्तावेज़ के साथ काम करते समय उपयोग करने के लिए अतिरिक्त सेटिंग्स। |

| उठाता है | विवरण |
| :- | :- |
| `UnsupportedFileTypeException` | प्रदान किया गया दस्तावेज़ प्रकार समर्थित नहीं है। |
| `InvalidPasswordException` | प्रदान किया गया पासवर्ड गलत है। |

### उदाहरण

```python
from groupdocs.watermark import Watermarker, WatermarkerSettings
from groupdocs.watermark.options.email import EmailLoadOptions
from groupdocs.watermark.search.objects import SearchableObjects, EmailSearchableObjects
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

settings = WatermarkerSettings()
settings.searchable_objects = SearchableObjects(
    email_searchable_objects=(
        EmailSearchableObjects.Subject
        | EmailSearchableObjects.HtmlBody
        | EmailSearchableObjects.PlainTextBody
    )
)

load_options = EmailLoadOptions()
with open("./test.msg", "rb") as stream:
    with Watermarker(stream, load_options, settings) as watermarker:
        criteria = TextSearchCriteria("test", False)
        watermarks = watermarker.search(criteria)
        watermarks.clear()
        watermarker.save("./output.msg")
```

### संबंधित देखें
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
