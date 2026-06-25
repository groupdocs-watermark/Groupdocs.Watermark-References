---
title: WordProcessingImageEffects class
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.watermark.options.word_processing/wordprocessingimageeffects/
is_root: false
weight: 30
---


## WordProcessingImageEffects class

Represents effects that can be applied to an image watermark for a Word document.

The WordProcessingImageEffects type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingimageeffects/__init__/) | Initializes a new instance of the WordProcessingImageEffects class. |

### Properties
| Property | Description |
| :- | :- |
| [border_line_format](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/border_line_format/) | The line format settings for the image border. (inherited from [`OfficeImageEffects`](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/)) |
| [brightness](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/brightness/) | The brightness of the picture, a float between 0.0 (dimmest) and 1.0 (brightest); defaults to 0.5. (inherited from [`OfficeImageEffects`](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/)) |
| [chroma_key](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/chroma_key/) | The color value of the image that will be treated as transparent. The default value is a fully transparent color. (inherited from [`OfficeImageEffects`](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/)) |
| [contrast](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/contrast/) | The contrast for the specified picture, ranging from 0.0 (least contrast) to 1.0 (greatest contrast). The default value is 0.5. (inherited from [`OfficeImageEffects`](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/)) |
| [gray_scale](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/gray_scale/) | The property indicates whether a picture will be displayed in grayscale mode. (inherited from [`OfficeImageEffects`](/watermark/python-net/groupdocs.watermark.contents/officeimageeffects/)) |

### Example

```python
import groupdocs.watermark as gw
import groupdocs.watermark.watermarks as gww
import groupdocs.watermark.options.wordprocessing as gwo_wp

load_options = gw.WordProcessingLoadOptions()
with gw.Watermarker("document.docx", load_options) as watermarker:
    with gww.ImageWatermark("logo.png") as watermark:
        effects = gwo_wp.WordProcessingImageEffects()
        effects.brightness = 0.7
        effects.contrast = 0.6
        effects.chroma_key = gww.Color.red
        effects.border_line_format.enabled = True
        effects.border_line_format.weight = 1

        options = gwo_wp.WordProcessingWatermarkSectionOptions()
        options.effects = effects

        watermarker.add(watermark, options)

    watermarker.save("document.docx")
```

### See Also
* module [`groupdocs.watermark.options.word_processing`](/watermark/python-net/groupdocs.watermark.options.word_processing/)
