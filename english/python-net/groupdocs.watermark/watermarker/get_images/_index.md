---
title: get_images method
second_title: GroupDocs.Watermark for Python via .NET API References
description: "Finds images according to the specified search criteria."
type: docs
url: /python-net/groupdocs.watermark/watermarker/get_images/
is_root: false
weight: 1080
---


## get_images {#search_criteria}

Finds images according to the specified search criteria.

The search is conducted in objects specified in [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/).

Learn more about searching watermarks https://docs.groupdocs.com/display/watermarknet/Searching+watermarks.

```python
def get_images(self, search_criteria):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| search_criteria | `ImageSearchCriteria` | The search criteria to use. |

**Returns:** The collection of found images.

### Example

```python
import groupdocs.watermark as gw
import groupdocs.watermark.search as gws

with gw.Watermarker(r"D:\\input.doc") as watermarker:
    criteria = gws.ImageThumbnailSearchCriteria("reference.png")
    images = watermarker.get_images(criteria)
    images.clear()
    watermarker.save(r"D:\\output.doc")
```

## get_images

Finds all images in the document.

The search is conducted in objects specified in [`Watermarker.searchable_objects`](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/).

Learn more about searching watermarks https://docs.groupdocs.com/display/watermarknet/Searching+watermarks.

```python
def get_images(self):
    ...
```

**Returns:** WatermarkableImageCollection: The collection of found images.

### Example

```python
    import groupdocs.watermark as gw
    import groupdocs.watermark.common as gwc

    load_options = gw.PdfLoadOptions()
    with gw.Watermarker("document.pdf", load_options) as watermarker:
        watermarker.searchable_objects.pdf_searchable_objects = gwc.PdfSearchableObjects.ATTACHED_IMAGES
        images = watermarker.get_images()
        print("Found", images.count, "image(s).")
    ```

### See Also
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
