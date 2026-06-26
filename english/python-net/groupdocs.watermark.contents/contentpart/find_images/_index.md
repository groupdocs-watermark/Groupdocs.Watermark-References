---
title: find_images method
second_title: GroupDocs.Watermark for Python via .NET API References
description: "Finds images according to the specified search criteria."
type: docs
url: /python-net/groupdocs.watermark.contents/contentpart/find_images/
is_root: false
weight: 1010
---


## find_images {#search_criteria}

Finds images according to the specified search criteria.

The search is conducted in the objects specified in [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/).

```python
def find_images(self, search_criteria):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| search_criteria | `ImageSearchCriteria` | The search criteria to use. |

**Returns:** An iterable collection of the found images.

### Example

```python
import groupdocs.watermark as gw
import groupdocs.watermark.watermarks as gww
import groupdocs.watermark.common as gwc
import groupdocs.watermark.contents.pdf as gwc_pdf

load_options = gw.PdfLoadOptions()
with gw.Watermarker("document.pdf", load_options) as watermarker:
    watermark = gww.TextWatermark("Protected image", gww.Font("Arial", 8.0))
    watermark.horizontal_alignment = gwc.HorizontalAlignment.CENTER
    watermark.vertical_alignment = gwc.VerticalAlignment.CENTER
    watermark.rotate_angle = 45
    watermark.sizing_type = gww.SizingType.SCALE_TO_PARENT_DIMENSIONS
    watermark.scale_factor = 1.0

    pdf_content = watermarker.get_content(gwc_pdf.PdfContent)
    images = pdf_content.pages[0].find_images()
    for image in images:
        image.add(watermark)

    watermarker.save("document.pdf")
```

## find_images

Finds all images in the content.

The search is performed on the objects specified in [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/).

```python
def find_images(self):
    ...
```

**Returns:** Collection of the found images.

### Example

```python
import groupdocs.watermark as gw
import groupdocs.watermark.watermarks as gww
import groupdocs.watermark.common as gwc
import groupdocs.watermark.contents.pdf as gwc_pdf

load_options = gw.PdfLoadOptions()
with gw.Watermarker("document.pdf", load_options) as watermarker:
    watermark = gww.TextWatermark("Protected image", gww.Font("Arial", 8.0))
    watermark.horizontal_alignment = gwc.HorizontalAlignment.CENTER
    watermark.vertical_alignment = gwc.VerticalAlignment.CENTER
    watermark.rotate_angle = 45
    watermark.sizing_type = gww.SizingType.SCALE_TO_PARENT_DIMENSIONS
    watermark.scale_factor = 1.0

    pdf_content = watermarker.get_content(gwc_pdf.PdfContent)
    images = pdf_content.pages[0].find_images()
    for image in images:
        image.add(watermark)

    watermarker.save("document.pdf")
```

### See Also
* class [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)
