---
title: "generate_preview मेथड"
second_title: "GroupDocs.Watermark Python के लिए .NET API संदर्भ"
description: "दस्तावेज़ के लिए प्रीव्यू इमेजेज़ उत्पन्न करता है।"
type: docs
url: /hi/python-net/groupdocs.watermark/watermarker/generate_preview/
is_root: false
weight: 1040
---


## generate_preview {#preview_options}

दस्तावेज़ के लिए प्रीव्यू इमेजेज़ उत्पन्न करता है।

```python
def generate_preview(self, preview_options):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| preview_options | `PreviewOptions` | पूर्वावलोकन छवियों को उत्पन्न करते समय उपयोग करने के लिए अतिरिक्त विकल्प। |

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
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
