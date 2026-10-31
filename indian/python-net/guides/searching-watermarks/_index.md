---
title: "वॉटरमार्क खोज"
linkTitle: "Searching watermarks"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "शक्तिशाली मानदंडों — टेक्स्ट, रेगेक्स, छवि समानता, फ़ॉर्मेटिंग, और संयुक्त मानदंड — के साथ संभावित टेक्स्ट और इमेज वॉटरमार्क खोजें — GroupDocs.Watermark for Python via .NET का उपयोग करके।"
type: docs
url: /hi/python-net/guides/searching-watermarks/
is_root: false
weight: 80
---


`Watermarker.search()` का उपयोग करके दस्तावेज़ को उन वस्तुओं के लिए स्कैन करें जिन्हें वॉटरमार्क माना जा सकता है — जिसमें तृतीय-पक्ष टूल्स द्वारा जोड़े गए वॉटरमार्क भी शामिल हैं। बिना मानदंड के, `search()` पृष्ठभूमि और फ्लोटिंग ऑब्जेक्ट्स जैसी उपसमुच्चय लौटाता है; परिणामों को संकीर्ण करने के लिए एक मानदंड ऑब्जेक्ट पास करें।

## Search for possible watermarks

नीचे दिया गया उदाहरण एक वॉटरमार्केड PDF को खोजता है और प्रत्येक संभावित वॉटरमार्क का टेक्स्ट, पृष्ठ और आकार प्रिंट करता है।

{{< tabs \"code-example-searching-watermarks\">}}
{{< tab \"search_watermarks.py\" >}}
```python
from groupdocs.watermark import Watermarker

def search_watermarks():
    with Watermarker("./document.pdf") as watermarker:
        possible = watermarker.search()
        print(f"Found {len(possible)} possible watermark(s).")
        for wm in possible:
            text = (wm.text or "").strip()
            print(f"- page={wm.page_number} text={text!r} size={round(wm.width)}x{round(wm.height)}")

if __name__ == "__main__":
    search_watermarks()
```
{{< /tab >}}
{{< tab \"document.pdf\" >}}

`document.pdf` इस उदाहरण में उपयोग की गई नमूना फ़ाइल है। इसे डाउनलोड करने के लिए [here](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/document.pdf) पर क्लिक करें।

{{< /tab >}}
{{< tab \"search-watermarks.txt\" >}}
```text
Found 14 possible watermark(s).
- page=1 text='CONFIDENTIAL' size=268x36
- page=1 text='' size=135x40
- page=1 text='' size=230x69
- page=1 text='' size=460x287
- page=2 text='CONFIDENTIAL' size=268x36
- page=2 text='' size=135x40
- page=3 text='CONFIDENTIAL' size=268x36
- page=3 text='' size=135x40
- page=4 text='CONFIDENTIAL' size=268x36
[TRUNCATED]
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/search_watermarks/search-watermarks.txt)
{{< /tab >}}
{{< /tabs >}}

प्रत्येक संभावित वॉटरमार्क `text`, `image_data`, `x`, `y`, `width`, `height`, `rotate_angle`, और `page_number` को उजागर करता है।

## Search criteria

बड़े दस्तावेज़ों में कई उम्मीदवार हो सकते हैं। जो आपको चाहिए वह ठीक-ठीक खोजने के लिए समर्पित मानदंडों का उपयोग करें।

### Text search criteria

सटीक टेक्स्ट द्वारा वॉटरमार्क खोजें।

{{< tabs \"code-example-search-by-text\">}}
{{< tab \"search_by_text.py\" >}}
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
{{< /tab >}}
{{< tab \"document.pdf\" >}}

`document.pdf` इस उदाहरण में उपयोग की गई नमूना फ़ाइल है। इसे डाउनलोड करने के लिए [here](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/document.pdf) पर क्लिक करें।

{{< /tab >}}
{{< tab \"search-by-text.txt\" >}}
```text
Found 8 possible watermark(s)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/search_by_text/search-by-text.txt)
{{< /tab >}}
{{< /tabs >}}

### Regular expression search criteria

एक संकलित रेगुलर एक्सप्रेशन को [`TextSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/) में पास करें।

{{< tabs \"code-example-search-by-regex\">}}
{{< tab \"search_by_regex.py\" >}}
```python
import re
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

def search_by_regex():
    with Watermarker("./document.pdf") as watermarker:
        possible = watermarker.search(TextSearchCriteria(re.compile(r"^CONFIDENTIAL$")))
        print("Found", len(possible), "possible watermark(s)")

if __name__ == "__main__":
    search_by_regex()
```
{{< /tab >}}
{{< tab \"document.pdf\" >}}

`document.pdf` इस उदाहरण में उपयोग की गई नमूना फ़ाइल है। इसे डाउनलोड करने के लिए [here](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/document.pdf) पर क्लिक करें।

{{< /tab >}}
{{< tab \"search-by-regex.txt\" >}}
```text
Found 8 possible watermark(s)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/search_by_regex/search-by-regex.txt)
{{< /tab >}}
{{< /tabs >}}

जब एक [`TextSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/textsearchcriteria/) प्रदान किया जाता है, तो API मुख्य दस्तावेज़ के टेक्स्ट को शैप्स, XObjects, एनोटेशन्स और अन्य वस्तुओं के साथ भी स्कैन करती है।

### Image search criteria

परसेप्चुअल हैशिंग (DCT हैश) का उपयोग करके एक नमूना छवि के समान दृश्यात्मक इमेज वॉटरमार्क खोजें। संवेदनशीलता को `max_difference` (0–1) के साथ नियंत्रित करें।

{{< tabs \"code-example-search-by-image\">}}
{{< tab \"search_by_image.py\" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import ImageDctHashSearchCriteria

def search_by_image():
    with Watermarker("./document.pdf") as watermarker:
        criteria = ImageDctHashSearchCriteria("./logo.png")
        criteria.max_difference = 0.9
        possible = watermarker.search(criteria)
        print("Found", len(possible), "possible watermark(s)")

if __name__ == "__main__":
    search_by_image()
```
{{< /tab >}}
{{< tab \"document.pdf\" >}}

`document.pdf` और `logo.png` इस उदाहरण में उपयोग की गई नमूना फ़ाइलें हैं। डाउनलोड करें [document.pdf](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/document.pdf) और [logo.png](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/logo.png)।

{{< /tab >}}
{{< tab \"search-by-image.txt\" >}}
```text
Found 6 possible watermark(s)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/search_by_image/search-by-image.txt)
{{< /tab >}}
{{< /tabs >}}

अन्य छवि मानदंड:

- [`ImageColorHistogramSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagecolorhistogramsearchcriteria/) — robust to rotation, scaling, and translation.
- [`ImageThumbnailSearchCriteria`](/watermark/python-net/groupdocs.watermark.search.search_criteria/imagethumbnailsearchcriteria/) — robust to rotation, scaling, and minor color changes.

### Combined search criteria

मानदंड को `and_()`, `or_()`, और `not_()` के साथ संयोजित करें।

{{< tabs \"code-example-search-combined\">}}
{{< tab \"search_combined.py\" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import (
    ImageDctHashSearchCriteria, TextSearchCriteria, RotateAngleSearchCriteria,
)

def search_combined():
    with Watermarker("./document.pdf") as watermarker:
        image_criteria = ImageDctHashSearchCriteria("./logo.png")
        image_criteria.max_difference = 0.9
        text_criteria = TextSearchCriteria("CONFIDENTIAL")
        angle_criteria = RotateAngleSearchCriteria(30, 60)

        combined = image_criteria.or_(text_criteria).and_(angle_criteria)
        possible = watermarker.search(combined)
        print("Found", len(possible), "possible watermark(s)")

if __name__ == "__main__":
    search_combined()
```
{{< /tab >}}
{{< tab \"document.pdf\" >}}

`document.pdf` और `logo.png` इस उदाहरण में उपयोग की गई नमूना फ़ाइलें हैं। डाउनलोड करें [document.pdf](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/document.pdf) और [logo.png](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/logo.png)।

{{< /tab >}}
{{< tab \"search-combined.txt\" >}}
```text
Found 4 possible watermark(s)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/search_combined/search-combined.txt)
{{< /tab >}}
{{< /tabs >}}

### Text formatting search criteria

फ़ॉन्ट, आकार, और रंग रेंज जैसी टेक्स्ट फ़ॉर्मेटिंग द्वारा वॉटरमार्क खोजें।

{{< tabs \"code-example-search-by-formatting\">}}
{{< tab \"search_by_formatting.py\" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextFormattingSearchCriteria, ColorRange

def search_by_formatting():
    with Watermarker("./document.pdf") as watermarker:
        criteria = TextFormattingSearchCriteria()
        criteria.foreground_color_range = ColorRange()
        criteria.foreground_color_range.min_hue = -15
        criteria.foreground_color_range.max_hue = 15
        criteria.foreground_color_range.min_brightness = 0.01
        criteria.foreground_color_range.max_brightness = 0.99
        criteria.min_font_size = 19
        criteria.max_font_size = 42

        possible = watermarker.search(criteria)
        print("Found", len(possible), "possible watermark(s)")

if __name__ == "__main__":
    search_by_formatting()
```
{{< /tab >}}
{{< tab \"document.pdf\" >}}

`document.pdf` इस उदाहरण में उपयोग की गई नमूना फ़ाइल है। इसे डाउनलोड करने के लिए [here](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/document.pdf) पर क्लिक करें।

{{< /tab >}}
{{< tab \"search-by-formatting.txt\" >}}
```text
Found 4 possible watermark(s)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/search_by_formatting/search-by-formatting.txt)
{{< /tab >}}
{{< /tabs >}}

**color and size** द्वारा खोज करना टेक्स्ट वॉटरमार्क से मेल कराने का सबसे मजबूत तरीका है। आप कर सकते हैं
साथ ही `font_name` और `font_bold` को सीमित करें, लेकिन बोल्ड फ़ॉन्ट अक्सर एक संयुक्त
सबसेट नाम (उदाहरण के लिए `ArialBold`) के रूप में होते हैं, न कि अलग बोल्ड फ़्लैग वाले `Arial` के, इसलिए एक
`font_name = \"Arial\"` फ़िल्टर इन्हें चूक सकता है।

## Search watermarks in particular objects

प्रदर्शन सुधारने के लिए खोज को विशिष्ट ऑब्जेक्ट प्रकारों तक सीमित करें — या तो वैश्विक रूप से `WatermarkerSettings.searchable_objects` के माध्यम से, या प्रति इंस्टेंस `Watermarker.searchable_objects` के माध्यम से। फ़्लैग `groupdocs.watermark.search.objects` में स्थित हैं।

{{< tabs \"code-example-search-in-objects\">}}
{{< tab \"search_in_objects.py\" >}}
```python
from groupdocs.watermark import Watermarker, WatermarkerSettings
from groupdocs.watermark.search.objects import (
    SearchableObjects, WordProcessingSearchableObjects, PdfSearchableObjects,
)

def search_in_objects():
    settings = WatermarkerSettings()
    settings.searchable_objects = SearchableObjects(
        word_processing_searchable_objects=WordProcessingSearchableObjects.HYPERLINKS | WordProcessingSearchableObjects.TEXT,
        pdf_searchable_objects=PdfSearchableObjects.ALL,
    )

    with Watermarker("./document.pdf", settings) as watermarker:
        possible = watermarker.search()
        print("Found", len(possible), "possible watermark(s)")

if __name__ == "__main__":
    search_in_objects()
```
{{< /tab >}}
{{< tab \"document.pdf\" >}}

`document.pdf` इस उदाहरण में उपयोग की गई नमूना फ़ाइल है। इसे डाउनलोड करने के लिए [here](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/document.pdf) पर क्लिक करें।

{{< /tab >}}
{{< tab \"search-in-objects.txt\" >}}
```text
Found 14 possible watermark(s)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/search_in_objects/search-in-objects.txt)
{{< /tab >}}
{{< /tabs >}}

### Search for hyperlink watermarks

एकल [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/) इंस्टेंस के लिए खोज को हाइपरलिंक तक सीमित करें:

{{< tabs \"code-example-search-hyperlinks\">}}
{{< tab \"search_hyperlinks.py\" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.objects import PdfSearchableObjects

def search_hyperlinks():
    with Watermarker("./document.pdf") as watermarker:
        watermarker.searchable_objects.pdf_searchable_objects = PdfSearchableObjects.HYPERLINKS
        possible = watermarker.search()
        print("Found", len(possible), "hyperlink watermark(s)")

if __name__ == "__main__":
    search_hyperlinks()
```
{{< /tab >}}
{{< tab \"document.pdf\" >}}

`document.pdf` इस उदाहरण में उपयोग की गई नमूना फ़ाइल है। इसे डाउनलोड करने के लिए [here](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/document.pdf) पर क्लिक करें।

{{< /tab >}}
{{< tab \"search-hyperlinks.txt\" >}}
```text
Found 4 hyperlink watermark(s)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/search_hyperlinks/search-hyperlinks.txt)
{{< /tab >}}
{{< /tabs >}}

## Search text while skipping unreadable characters

जब टेक्स्ट में अक्षरों के बीच अपठनीय अक्षर होते हैं तो सहनशील मिलान सक्षम करें।

{{< tabs "code-example-search-skip-unreadable">}}
{{< tab "search_skip_unreadable.py" >}}
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

def search_skip_unreadable():
    with Watermarker("./document.pdf") as watermarker:
        criterion = TextSearchCriteria("CONFIDENTIAL")
        criterion.skip_unreadable_characters = True
        possible = watermarker.search(criterion)
        print("Found", len(possible), "possible watermark(s)")

if __name__ == "__main__":
    search_skip_unreadable()
```
{{< /tab >}}
{{< tab \"document.pdf\" >}}

`document.pdf` इस उदाहरण में उपयोग की गई नमूना फ़ाइल है। इसे डाउनलोड करने के लिए [here](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/document.pdf) पर क्लिक करें।

{{< /tab >}}
{{< tab "search-skip-unreadable.txt" >}}
```text
Found 8 possible watermark(s)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/advanced-usage/searching-and-modifying-watermarks/searching-watermarks/search_skip_unreadable/search-skip-unreadable.txt)
{{< /tab >}}
{{< /tabs >}}
