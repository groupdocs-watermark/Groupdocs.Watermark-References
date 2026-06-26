---
title: WordProcessingTextEffects class
second_title: GroupDocs.Watermark for Python via .NET API References
description: "Represents effects that can be applied to a text watermark for a Word document."
type: docs
url: /python-net/groupdocs.watermark.options.word_processing/wordprocessingtexteffects/
is_root: false
weight: 80
---


## WordProcessingTextEffects class

Represents effects that can be applied to a text watermark for a Word document.

The WordProcessingTextEffects type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingtexteffects/__init__/) | Initializes a new instance of the WordProcessingTextEffects class. |

### Properties
| Property | Description |
| :- | :- |
| [flip_orientation](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingtexteffects/flip_orientation/) | The orientation of a shape. |
| [line_format](/watermark/python-net/groupdocs.watermark.contents/officetexteffects/line_format/) | The line format settings, represented by a [`OfficeLineFormat`](/watermark/python-net/groupdocs.watermark.contents/officelineformat/) instance. (inherited from [`OfficeTextEffects`](/watermark/python-net/groupdocs.watermark.contents/officetexteffects/)) |

### Fields
| Field | Description |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingtexteffects/default/) | Gets the default value for the class. |

### Example

```python
import groupdocs.watermark as gw
import groupdocs.watermark.watermarks as gww
import groupdocs.watermark.options.wordprocessing as gwo_wp
import groupdocs.watermark.common as gwc

load_options = gw.WordProcessingLoadOptions()
with gw.Watermarker("document.docx", load_options) as watermarker:
    watermark = gww.TextWatermark("Test watermark", gww.Font("Arial", 19.0))

    effects = gwo_wp.WordProcessingTextEffects()
    effects.line_format.enabled = True
    effects.line_format.color = gww.Color.red
    effects.line_format.dash_style = gwc.OfficeDashStyle.DASH_DOT_DOT
    effects.line_format.line_style = gwc.OfficeLineStyle.TRIPLE
    effects.line_format.weight = 1

    options = gwo_wp.WordProcessingWatermarkSectionOptions()
    options.effects = effects

    watermarker.add(watermark, options)
    watermarker.save("document.docx")
```

### See Also
* module [`groupdocs.watermark.options.word_processing`](/watermark/python-net/groupdocs.watermark.options.word_processing/)
