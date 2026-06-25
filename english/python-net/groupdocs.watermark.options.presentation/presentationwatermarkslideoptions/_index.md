---
title: PresentationWatermarkSlideOptions class
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.watermark.options.presentation/presentationwatermarkslideoptions/
is_root: false
weight: 140
---


## PresentationWatermarkSlideOptions class

Represents options when adding a watermark to a Presentation document slide.

Learn more:
- https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+presentation+documents

The PresentationWatermarkSlideOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkslideoptions/__init__/) | Initializes a new instance of the [`PresentationWatermarkSlideOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkslideoptions/) class. |

### Properties
| Property | Description |
| :- | :- |
| [slide_index](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkslideoptions/slide_index/) | The index of the slide to add the watermark to. |
| [alternative_text](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/alternative_text/) | The descriptive (alternative) text that will be associated with a shape. (inherited from [`PresentationWatermarkBaseSlideOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/)) |
| [effects](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/effects/) | The effects applied to the watermark, specified as a [`PresentationImageEffects`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationimageeffects/) or [`PresentationTextEffects`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationtexteffects/) instance. (inherited from [`PresentationWatermarkBaseSlideOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/)) |
| [is_locked](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/is_locked/) | The shape editing lock state for a PowerPoint slide. (inherited from [`PresentationWatermarkBaseSlideOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/)) |
| [name](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/name/) | The shape name. (inherited from [`PresentationWatermarkBaseSlideOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/)) |
| [protect_with_unreadable_characters](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/protect_with_unreadable_characters/) | The property indicates whether the text watermark characters are mixed with unreadable characters. (inherited from [`PresentationWatermarkBaseSlideOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationwatermarkbaseslideoptions/)) |

### Fields
| Field | Description |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | Gets the default value for the class. (inherited from [`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/)) |

### Example

```python
import groupdocs.watermark as gw
import groupdocs.watermark.watermarks as gww
import groupdocs.watermark.options.presentation as gwo_ppt

load_options = gw.PresentationLoadOptions()
with gw.Watermarker("presentation.pptx", load_options) as watermarker:
    # Add a text watermark to the first slide
    text_wm = gww.TextWatermark("Test watermark", gww.Font("Arial", 36.0))
    text_opts = gwo_ppt.PresentationWatermarkSlideOptions()
    text_opts.slide_index = 0
    text_opts.is_locked = False
    text_opts.protect_with_unreadable_characters = False
    watermarker.add(text_wm, text_opts)

    # Add an image watermark to the second slide and lock it
    with gww.ImageWatermark("logo.jpg") as img_wm:
        img_opts = gwo_ppt.PresentationWatermarkSlideOptions()
        img_opts.slide_index = 1
        img_opts.is_locked = True
        img_opts.protect_with_unreadable_characters = True
        watermarker.add(img_wm, img_opts)

    watermarker.save("presentation.pptx")
```

### See Also
* module [`groupdocs.watermark.options.presentation`](/watermark/python-net/groupdocs.watermark.options.presentation/)
