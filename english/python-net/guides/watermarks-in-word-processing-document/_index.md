---
title: Watermarks in word processing document
linkTitle: "Watermarks in word"
second_title: GroupDocs.Watermark for Python via .NET API References
description: "Add shape-based watermarks to Word documents with a name, alternative text, and text/image effects using GroupDocs.Watermark for Python via .NET."
type: docs
url: /python-net/guides/watermarks-in-word-processing-document/
is_root: false
weight: 330
---


When you add a watermark to a Microsoft Word document, a shape with the appropriate content is placed in the section headers. [`WordProcessingWatermarkSectionOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarksectionoptions/) (and [`WordProcessingWatermarkPagesOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkpagesoptions/)) let you set the shape's `name` and `alternative_text`, and apply text or image effects through the `effects` property.

## Add an image watermark with effects

The example applies brightness, contrast, and a chroma-key to an image watermark using [`WordProcessingImageEffects`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingimageeffects/).

  
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import ImageWatermark, Color
from groupdocs.watermark.options.word_processing import (
    WordProcessingLoadOptions, WordProcessingWatermarkSectionOptions, WordProcessingImageEffects,
)

def add_watermark_with_effects():
    with Watermarker("./document.docx", WordProcessingLoadOptions()) as watermarker:
        with ImageWatermark("./logo.png") as watermark:
            effects = WordProcessingImageEffects()
            effects.brightness = 0.7
            effects.contrast = 0.6
            effects.chroma_key = Color.red

            options = WordProcessingWatermarkSectionOptions()
            options.name = "Shape 1"
            options.alternative_text = "Company logo watermark"
            options.effects = effects
            watermarker.add(watermark, options)

        watermarker.save("./output.docx")

if __name__ == "__main__":
    add_watermark_with_effects()
```

  

`document.docx` and `logo.png` are the sample files used in this example. Download [document.docx](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/adding-watermarks/add-watermarks-to-word-processing-documents/document.docx) and [logo.png](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/adding-watermarks/add-watermarks-to-word-processing-documents/logo.png).

  
```text
Binary file (DOCX, 120 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/advanced-usage/adding-watermarks/add-watermarks-to-word-processing-documents/watermarks-in-word-processing-document/add_watermark_with_effects/output.docx)

For a text watermark, use [`WordProcessingTextEffects`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingtexteffects/) instead — set its `line_format` (enabled, color, dash style, line style, and weight) and assign it to `options.effects`. [`WordProcessingImageEffects`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingimageeffects/) also exposes `gray_scale` and `border_line_format`.

To work with shapes already present in a document, see [Existing objects in word processing document]().
