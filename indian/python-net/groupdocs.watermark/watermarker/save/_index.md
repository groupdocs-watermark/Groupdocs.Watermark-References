---
title: "save मेथड"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "दस्तावेज़ डेटा को अंतर्निहित स्ट्रीम में सहेजता है।"
type: docs
url: /hi/python-net/groupdocs.watermark/watermarker/save/
is_root: false
weight: 1130
---


## save

दस्तावेज़ डेटा को अंतर्निहित स्ट्रीम में सहेजता है।

दस्तावेज़ों को सहेजने के बारे में अधिक जानें: https://docs.groupdocs.com/display/watermarknet/Saving+documents.

```python
def save(self):
    ...
```

### उदाहरण

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

with Watermarker(r"D:\\test.msg") as watermarker:
    criteria = TextSearchCriteria("test", False)
    watermarks = watermarker.search(criteria)
    watermarker.remove(watermarks)
    watermarker.save()
```

## save {#file_path}

दस्तावेज़ को निर्दिष्ट फ़ाइल स्थान पर सहेजता है।

दस्तावेज़ों को सहेजने के बारे में अधिक जानें: https://docs.groupdocs.com/display/watermarknet/Saving+documents.

```python
def save(self, file_path):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| file_path | `str` | फ़ाइल पथ जहाँ दस्तावेज़ डेटा सहेजा जाएगा। |

### उदाहरण

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font

def add_and_save():
    with Watermarker("input.pdf") as watermarker:
        watermark = TextWatermark("top secret", Font("Arial", 36))
        watermarker.add(watermark)
        watermarker.save("output.pdf")
```

## save {#document}

दस्तावेज़ को निर्दिष्ट स्ट्रीम में सहेजता है।

https://docs.groupdocs.com/display/watermarknet/Saving+documents. पर दस्तावेज़ों को सहेजने के बारे में अधिक जानें।

```python
def save(self, document):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| document | `io.RawIOBase` | दस्तावेज़ डेटा सहेजने के लिए स्ट्रीम। |

### उदाहरण

```python
from io import BytesIO
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark
from groupdocs.watermark.watermarks import Font

with Watermarker("input.pdf") as watermarker:
    watermark = TextWatermark("top secret", Font("Arial", 36))
    watermarker.add(watermark)
    stream = BytesIO()
    watermarker.save(stream)
    # `stream` अब सहेजे गए PDF बाइट्स को शामिल करता है
```

## save {#options}

सहेजने के विकल्पों का उपयोग करके दस्तावेज़ डेटा को अंतर्निहित स्ट्रीम में सहेजता है।

दस्तावेज़ों को सहेजने के बारे में अधिक जानें।

```python
def save(self, options):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| options | `SaveOptions` | दस्तावेज़ सहेजते समय उपयोग करने के लिए अतिरिक्त विकल्प। |

### उदाहरण

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options import SaveOptions
from groupdocs.watermark.watermarks import TextWatermark
from groupdocs.watermark.watermarks import Font

with Watermarker("input.pdf") as watermarker:
    watermark = TextWatermark("top secret", Font("Arial", 36))
    watermarker.add(watermark)
    watermarker.save(SaveOptions())
```

## save {#file_path-options}

सहेजने के विकल्पों का उपयोग करके दस्तावेज़ को निर्दिष्ट फ़ाइल स्थान पर सहेजता है।

दस्तावेज़ों को सहेजने के बारे में अधिक जानें: https://docs.groupdocs.com/display/watermarknet/Saving+documents.

```python
def save(self, file_path, options):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| file_path | `str` | फ़ाइल पथ जहाँ दस्तावेज़ डेटा सहेजा जाएगा। |
| options | `SaveOptions` | दस्तावेज़ सहेजते समय उपयोग करने के लिए अतिरिक्त विकल्प। |

### उदाहरण

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark
from groupdocs.watermark.watermarks import Font
from groupdocs.watermark.options import SaveOptions

with Watermarker("input.pdf") as watermarker:
    watermark = TextWatermark("top secret", Font("Arial", 36))
    watermarker.add(watermark)
    watermarker.save("output.pdf", SaveOptions())
```

## save {#document-options}

सहेजने के विकल्पों का उपयोग करके दस्तावेज़ को निर्दिष्ट स्ट्रीम में सहेजता है।

GroupDocs दस्तावेज़ीकरण में दस्तावेज़ों को सहेजने के बारे में अधिक जानें।

```python
def save(self, document, options):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| document | `io.RawIOBase` | दस्तावेज़ डेटा सहेजने के लिए स्ट्रीम। |
| options | `SaveOptions` | दस्तावेज़ सहेजते समय उपयोग करने के लिए अतिरिक्त विकल्प। |

### उदाहरण

```python
from io import BytesIO
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options import SaveOptions
from groupdocs.watermark.watermarks import TextWatermark
from groupdocs.watermark.watermarks import Font

def add_watermark_and_save():
    with Watermarker("input.pdf") as watermarker:
        watermark = TextWatermark("top secret", Font("Arial", 36))
        watermarker.add(watermark)

        stream = BytesIO()
        watermarker.save(stream, SaveOptions())
        # स्ट्रीम अब सहेजे गए PDF डेटा को शामिल करता है
        # उदाहरण के लिए, फ़ाइल में लिखें
        with open("output.pdf", "wb") as f:
            f.write(stream.getvalue())

if __name__ == "__main__":
    add_watermark_and_save()
```

### संबंधित देखें
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
