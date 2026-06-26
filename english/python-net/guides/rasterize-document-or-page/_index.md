---
title: Rasterize document or page
linkTitle: "Rasterize document or"
second_title: GroupDocs.Watermark for Python via .NET API References
description: "Rasterize a PDF — convert pages to images — so that watermarks become hard to remove, using GroupDocs.Watermark for Python via .NET."
type: docs
url: /python-net/guides/rasterize-document-or-page/
is_root: false
weight: 240
---


Watermarks in PDFs can be removed by third-party tools. If you need watermarks that are very hard to remove, **rasterize** the document: convert its pages to images so the content — including the watermark — becomes non-editable. Access the PDF content tree with `Watermarker.get_content()` and call `rasterize()`.

Rasterization is irreversible: the original text and vector content cannot be restored afterwards, and the output file size usually increases.

## Rasterize the whole document

The example adds a watermark, rasterizes every page to a PNG image at 100 DPI, and saves the result.

  
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color
from groupdocs.watermark.options.pdf import PdfLoadOptions
from groupdocs.watermark.contents.pdf import PdfImageConversionFormat

def rasterize_document():
    with Watermarker("./document.pdf", PdfLoadOptions()) as watermarker:
        watermark = TextWatermark("CONFIDENTIAL", Font("Arial", 19.0))
        watermark.foreground_color = Color.red
        watermarker.add(watermark)

        # Rasterize every page at 100x100 DPI to PNG images
        content = watermarker.get_content()
        content.rasterize(100, 100, PdfImageConversionFormat.PNG)

        watermarker.save("./output.pdf")

if __name__ == "__main__":
    rasterize_document()
```

  

`document.pdf` is the sample file used in this example. Click [here](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/adding-watermarks/add-watermarks-to-pdf-documents/document.pdf) to download it.

  
```text
Binary file (PDF, 1.1 MB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/advanced-usage/adding-watermarks/add-watermarks-to-pdf-documents/rasterize-document-or-page/rasterize_document/output.pdf)

## Rasterize a particular page

To rasterize a single page, call `rasterize()` on that page instead of the whole content:

  
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.pdf import PdfLoadOptions
from groupdocs.watermark.contents.pdf import PdfImageConversionFormat

def rasterize_page():
    with Watermarker("./document.pdf", PdfLoadOptions()) as watermarker:
        content = watermarker.get_content()
        content.pages[0].rasterize(100, 100, PdfImageConversionFormat.PNG)
        watermarker.save("./output.pdf")

if __name__ == "__main__":
    rasterize_page()
```

  

`document.pdf` is the sample file used in this example. Click [here](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/adding-watermarks/add-watermarks-to-pdf-documents/document.pdf) to download it.

  
```text
Binary file (PDF, 570 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/advanced-usage/adding-watermarks/add-watermarks-to-pdf-documents/rasterize-document-or-page/rasterize_page/output.pdf)
