---
title: WordProcessingWatermarkPagesOptions class
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkpagesoptions/
is_root: false
weight: 110
---


## WordProcessingWatermarkPagesOptions class

Represents options when adding a watermark to Word document pages.

Learn more:
- https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+word+processing+documents

The WordProcessingWatermarkPagesOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkpagesoptions/__init__/) | Initializes a new instance of the [`WordProcessingWatermarkPagesOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkpagesoptions/) class. |

### Properties
| Property | Description |
| :- | :- |
| [page_numbers](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkpagesoptions/page_numbers/) | The page numbers to add the watermark. |
| [alternative_text](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/alternative_text/) | The descriptive (alternative) text that will be associated with a shape. (inherited from [`WordProcessingWatermarkBaseOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/)) |
| [effects](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/effects/) | The image or text effects applied to the watermark. (inherited from [`WordProcessingWatermarkBaseOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/)) |
| [is_locked](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/is_locked/) | The property indicates whether editing of the shape in Word is forbidden. (inherited from [`WordProcessingWatermarkBaseOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/)) |
| [lock_type](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/lock_type/) | The watermark lock type. (inherited from [`WordProcessingWatermarkBaseOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/)) |
| [name](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/name/) | The shape name. (inherited from [`WordProcessingWatermarkBaseOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/)) |
| [password](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/password/) | The password used to lock the watermark. (inherited from [`WordProcessingWatermarkBaseOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/)) |

### Fields
| Field | Description |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | Gets the default value for the class. (inherited from [`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/)) |

### Example

```python
import groupdocs.watermark as gw
import groupdocs.watermark.watermarks as gww
import groupdocs.watermark.options.wordprocessing as gwo_wp
import groupdocs.watermark.contents.wordprocessing as gwc_wp

load_options = gw.WordProcessingLoadOptions()
with gw.Watermarker("document.docx", load_options) as watermarker:
    text_watermark = gww.TextWatermark("DRAFT", gww.Font("Arial", 42.0))

    content = watermarker.get_content(gwc_wp.WordProcessingContent)
    options = gwo_wp.WordProcessingWatermarkPagesOptions()
    options.page_numbers = [content.page_count]

    watermarker.add(text_watermark, options)
    watermarker.save("document.docx")
```

### See Also
* module [`groupdocs.watermark.options.word_processing`](/watermark/python-net/groupdocs.watermark.options.word_processing/)
