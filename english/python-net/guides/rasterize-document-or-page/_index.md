---
title: Rasterize document or page
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/guides/rasterize-document-or-page/
is_root: false
weight: 240
---


## How to remove a watermark from a PDF
Watermarks in PDFs can be removed by third-party tools. If you need watermarks that are very hard to remove, rasterize the document: convert pages to images so content becomes non-editable.

## Rasterize PDF document
This sample converts all PDF pages to images (after adding a watermark) to lock down content and make subsequent removal extremely difficult.

```python
import groupdocs.watermark as gw
import groupdocs.watermark.contents.pdf as gwc_pdf
import groupdocs.watermark.watermarks as gww
import groupdocs.watermark.common as gwc

load_options = gw.PdfLoadOptions()
with gw.Watermarker("document.pdf", load_options) as watermarker:
    watermark = gww.TextWatermark("Do not copy", gww.Font("Arial", 8.0))
    watermark.horizontal_alignment = gwc.HorizontalAlignment.CENTER
    watermark.vertical_alignment = gwc.VerticalAlignment.CENTER
    watermark.rotate_angle = 45
    watermark.sizing_type = gww.SizingType.SCALE_TO_PARENT_DIMENSIONS
    watermark.scale_factor = 1.0
    watermark.opacity = 0.5

    watermarker.add(watermark)
    pdf_content = watermarker.get_content(gwc_pdf.PdfContent)
    pdf_content.rasterize(100, 100, gwc_pdf.PdfImageConversionFormat.PNG)
    watermarker.save("document.pdf")
```

You can't restore document content after saving the document. Rasterization significantly increases the size of the resultant PDF file.

## Rasterize particular page of the PDF document
This sample rasterizes only a specified page of the PDF (with an applied watermark), leaving the rest of the document editable.

```python
import groupdocs.watermark as gw
import groupdocs.watermark.contents.pdf as gwc_pdf
import groupdocs.watermark.watermarks as gww
import groupdocs.watermark.common as gwc
import groupdocs.watermark.options.pdf as gwo_pdf

load_options = gw.PdfLoadOptions()
with gw.Watermarker("document.pdf", load_options) as watermarker:
    watermark = gww.TextWatermark("Do not copy", gww.Font("Arial", 8.0))
    watermark.horizontal_alignment = gwc.HorizontalAlignment.CENTER
    watermark.vertical_alignment = gwc.VerticalAlignment.CENTER
    watermark.rotate_angle = 45
    watermark.sizing_type = gww.SizingType.SCALE_TO_PARENT_DIMENSIONS
    watermark.scale_factor = 1.0
    watermark.opacity = 0.5

    options = gwo_pdf.PdfArtifactWatermarkOptions()
    options.page_index = 0
    watermarker.add(watermark, options)

    pdf_content = watermarker.get_content(gwc_pdf.PdfContent)
    pdf_content.pages[0].rasterize(100, 100, gwc_pdf.PdfImageConversionFormat.PNG)
    watermarker.save("document.pdf")
```
