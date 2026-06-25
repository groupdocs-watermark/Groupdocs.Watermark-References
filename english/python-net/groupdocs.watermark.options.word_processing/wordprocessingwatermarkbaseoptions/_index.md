---
title: WordProcessingWatermarkBaseOptions class
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/
is_root: false
weight: 90
---


## WordProcessingWatermarkBaseOptions class

Represents the base class for watermark adding options to a Word document.

Use `lock_type` to set the lock type for the watermark, restricting editing of the document. Available lock types include `AllowOnlyRevisions`, `AllowOnlyComments`, `AllowOnlyFormFields`, `ReadOnly`, and `ReadOnlyWithEditableContent`.

The WordProcessingWatermarkBaseOptions type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [alternative_text](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/alternative_text/) | The descriptive (alternative) text that will be associated with a shape. |
| [effects](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/effects/) | The image or text effects applied to the watermark. |
| [is_locked](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/is_locked/) | The property indicates whether editing of the shape in Word is forbidden. |
| [lock_type](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/lock_type/) | The watermark lock type. |
| [name](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/name/) | The shape name. |
| [password](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingwatermarkbaseoptions/password/) | The password used to lock the watermark. |

### Fields
| Field | Description |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/default/) | Gets the default value for the class. (inherited from [`WatermarkOptions`](/watermark/python-net/groupdocs.watermark.options/watermarkoptions/)) |

### Example

```python
from groupdocs.watermark import Watermark
from groupdocs.watermark.options import WordProcessingWatermarkBaseOptions
from groupdocs.watermark.enums import WatermarkLockType

options = WordProcessingWatermarkBaseOptions()
options.lock_type = WatermarkLockType.ReadOnly

Watermark.add(watermark_text="Confidential", options=options)
```

### See Also
* module [`groupdocs.watermark.options.word_processing`](/watermark/python-net/groupdocs.watermark.options.word_processing/)
