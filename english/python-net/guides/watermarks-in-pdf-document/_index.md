---
title: Watermarks in PDF document
second_title: GroupDocs.Watermark for Python via .NET API References
description: 
type: docs
url: /python-net/guides/watermarks-in-pdf-document/
is_root: false
weight: 300
---


Learn the ways GroupDocs.Watermark adds watermarks in PDF documents.

## XObjects

When `add` on [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/) is called, a simple XObject is added to the PDF.

Image XObject and Form XObject are used to add [`ImageWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/imagewatermark/) and [`TextWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/) respectively. XObjects are page real content and are not removed by Adobe Acrobat sanitization.

## Artifacts

Watermarks can be represented by artifacts. Add an artifact watermark using [`PdfArtifactWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.pdf/pdfartifactwatermarkoptions/).

```python
import groupdocs.watermark as gw
import groupdocs.watermark.watermarks as gww
import groupdocs.watermark.contents.pdf as gwc_pdf
import groupdocs.watermark.options.pdf as gwo_pdf
import groupdocs.watermark.common as gwc

load_options = gw.PdfLoadOptions()
with gw.Watermarker("document.pdf", load_options) as watermarker:
    options = gwo_pdf.PdfArtifactWatermarkOptions()

    text_watermark = gww.TextWatermark("This is an artifact watermark", gww.Font("Arial", 8.0))
    text_watermark.horizontal_alignment = gwc.HorizontalAlignment.RIGHT
    watermarker.add(text_watermark, options)

    with gww.ImageWatermark("logo.bmp") as image_watermark:
        watermarker.add(image_watermark, options)

    watermarker.save("document.pdf")
```

## Annotations

Add annotation watermarks using [`PdfAnnotationWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.pdf/pdfannotationwatermarkoptions/).

```python
import groupdocs.watermark as gw
import groupdocs.watermark.watermarks as gww
import groupdocs.watermark.contents.pdf as gwc_pdf
import groupdocs.watermark.options.pdf as gwo_pdf
import groupdocs.watermark.common as gwc

load_options = gw.PdfLoadOptions()
with gw.Watermarker("document.pdf", load_options) as watermarker:
    options = gwo_pdf.PdfAnnotationWatermarkOptions()

    text_watermark = gww.TextWatermark("This is a annotation watermark", gww.Font("Arial", 8.0))
    text_watermark.horizontal_alignment = gwc.HorizontalAlignment.LEFT
    text_watermark.vertical_alignment = gwc.VerticalAlignment.TOP
    watermarker.add(text_watermark, options)

    with gww.ImageWatermark("protect.jpg") as image_watermark:
        image_watermark.horizontal_alignment = gwc.HorizontalAlignment.RIGHT
        image_watermark.vertical_alignment = gwc.VerticalAlignment.TOP
        watermarker.add(image_watermark, options)

    watermarker.save("document.pdf")
```

## Print-only annotations

Make an annotation print-only using `print_only`.

```python
import groupdocs.watermark as gw
import groupdocs.watermark.watermarks as gww
import groupdocs.watermark.options.pdf as gwo_pdf

load_options = gw.PdfLoadOptions()
with gw.Watermarker("document.pdf", load_options) as watermarker:
    text_watermark = gww.TextWatermark(
        "This is a print only test watermark. It won't appear in view mode.",
        gww.Font("Arial", 8.0),
    )

    options = gwo_pdf.PdfAnnotationWatermarkOptions()
    options.page_index = 0
    options.print_only = True

    watermarker.add(text_watermark, options)
    watermarker.save("document.pdf")
```
