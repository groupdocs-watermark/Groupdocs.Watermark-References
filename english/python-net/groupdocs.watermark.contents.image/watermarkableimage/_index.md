---
title: WatermarkableImage class
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.watermark.contents.image/watermarkableimage/
is_root: false
weight: 90
---


## WatermarkableImage class

Represents an image inside a document.

Learn more:
- Adding watermark to images inside a document (https://docs.groupdocs.com/display/watermarknet/Adding+watermark+to+images+inside+a+document)

The WatermarkableImage type exposes the following members:

### Methods
| Method | Description |
| :- | :- |
| [add](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/add/#watermark) | Adds a watermark to this [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/). Assumes that watermark offset and size are measured in pixels (if they are assigned). |
| [add_watermark](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/add_watermark/) |  |
| [get_bytes](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/get_bytes/) | Gets the image as a byte array. |
| [find_images](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images/) | Finds images according to the specified search criteria. The search is conducted in the objects specified in [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/). (inherited from [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [find_images_image_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images_image_search_criteria/) |  (inherited from [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [search](/watermark/python-net/groupdocs.watermark.contents/contentpart/search/) | Finds possible watermarks according to the specified search criteria. (inherited from [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [search_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/search_search_criteria/) |  (inherited from [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |

### Properties
| Property | Description |
| :- | :- |
| [height](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/height/) | The height of this WatermarkableImage in pixels. |
| [width](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/width/) | The width of this WatermarkableImage in pixels. |

### Example

```python
from groupdocs.watermark import Watermarker, TextWatermark, Font

with Watermarker(r"D:\input.doc") as watermarker:
    watermark = TextWatermark("DRAFT", Font("Arial", 19))
    images = watermarker.get_images()
    for img in images:
        img.add(watermark)
    watermarker.save(r"D:\output.doc")
```

### See Also
* module [`groupdocs.watermark.contents.image`](/watermark/python-net/groupdocs.watermark.contents.image/)
