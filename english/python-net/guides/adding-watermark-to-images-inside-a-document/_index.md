---
title: Adding watermark to images inside a document
linkTitle: "Adding watermark to"
second_title: GroupDocs.Watermark for Python via .NET API References
description: "Add a watermark to the images embedded inside a document using GroupDocs.Watermark for Python via .NET."
type: docs
url: /python-net/guides/adding-watermark-to-images-inside-a-document/
is_root: false
weight: 30
---


Beyond watermarking a document's pages, you can watermark the **images embedded inside** it. `Watermarker.get_images()` returns a collection of every raster image in the document, regardless of format, and each image accepts its own watermark via `add()`.

## Watermark every embedded image

The example finds all embedded images, watermarks the larger ones (over 100×100), and saves the result.

  
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color, SizingType
from groupdocs.watermark.options.pdf import PdfLoadOptions

def watermark_images_inside():
    with Watermarker("./document.pdf", PdfLoadOptions()) as watermarker:
        watermark = TextWatermark("PROTECTED", Font("Arial", 8.0))
        watermark.foreground_color = Color.red
        watermark.sizing_type = SizingType.SCALE_TO_PARENT_DIMENSIONS
        watermark.scale_factor = 1.0

        # Every raster image embedded in the document
        for image in watermarker.get_images():
            # Skip tiny images such as icons or bullets
            if image.width > 100 and image.height > 100:
                image.add(watermark)

        watermarker.save("./output.pdf")

if __name__ == "__main__":
    watermark_images_inside()
```

  

`document.pdf` is the sample file used in this example. Click [here](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/adding-watermarks/adding-watermark-to-images-inside-a-document/document.pdf) to download it.

  
```text
Binary file (PDF, 1596 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/advanced-usage/adding-watermarks/adding-watermark-to-images-inside-a-document/watermark_images_inside/output.pdf)

For the example document (10 embedded images), 8 images larger than 100×100 are watermarked. `get_images()` works the same way for Word, Excel, PowerPoint, and other formats — open the document and iterate the returned collection. You can also pass an [`ImageWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/imagewatermark/) to `image.add(...)` to stamp a logo onto each embedded image.
