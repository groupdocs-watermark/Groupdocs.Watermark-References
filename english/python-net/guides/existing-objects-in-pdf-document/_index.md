---
title: Existing objects in PDF document
linkTitle: "Existing objects in"
second_title: GroupDocs.Watermark for Python via .NET API References
description: "Inspect, modify, and remove existing PDF page objects — XObjects, artifacts, and annotations — using GroupDocs.Watermark for Python via .NET."
type: docs
url: /python-net/guides/existing-objects-in-pdf-document/
is_root: false
weight: 170
---


`Watermarker.get_content()` returns a [`PdfContent`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/) whose `pages` expose three collections of existing objects: `xobjects`, `artifacts`, and `annotations`. You can iterate them to read their properties, modify them, or remove them.

## Extract information about page objects

The example below reports the objects on the first page of a watermarked PDF.

  
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.pdf import PdfLoadOptions

def extract_objects():
    with Watermarker("./document.pdf", PdfLoadOptions()) as watermarker:
        content = watermarker.get_content()
        page = content.pages[0]
        print(f"Page 1: xobjects={len(page.xobjects)} "
              f"artifacts={len(page.artifacts)} annotations={len(page.annotations)}")
        for artifact in page.artifacts:
            text = (artifact.text or "").strip()
            print(f"  artifact text={text!r} size={round(artifact.width)}x{round(artifact.height)}")
        for annotation in page.annotations:
            text = (annotation.text or "").strip()
            print(f"  annotation text={text!r} size={round(annotation.width)}x{round(annotation.height)}")

if __name__ == "__main__":
    extract_objects()
```

  

`document.pdf` is the sample file used in this example. Click [here](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/adding-watermarks/existing-objects-in-pdf-document/document.pdf) to download it.

  
```text
Page 1: xobjects=2 artifacts=2 annotations=0
  artifact text='CONFIDENTIAL' size=268x36
  artifact text='' size=135x40
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/advanced-usage/adding-watermarks/add-watermarks-to-pdf-documents/existing-objects-in-pdf-document/extract_objects/extract-objects.txt)

Each object exposes `text`, `image`, `x`, `y`, `width`, `height`, and `rotate_angle` (artifacts also expose `opacity`, `artifact_type`, and `artifact_subtype`).

## Remove and modify objects

Each collection supports `remove_at(index)` and `remove(object)`. Iterate in reverse when removing by index:

  
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.pdf import PdfLoadOptions

def remove_and_modify_objects():
    with Watermarker("./document.pdf", PdfLoadOptions()) as watermarker:
        content = watermarker.get_content()
        for page in content.pages:
            for i in range(len(page.artifacts) - 1, -1, -1):
                if page.artifacts[i].text and "watermark" in page.artifacts[i].text.lower():
                    page.artifacts.remove_at(i)
        watermarker.save("./output.pdf")

if __name__ == "__main__":
    remove_and_modify_objects()
```

  

`document.pdf` is the sample file used in this example. Click [here](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/adding-watermarks/existing-objects-in-pdf-document/document.pdf) to download it.

  
```text
Binary file (PDF, 394 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/advanced-usage/adding-watermarks/add-watermarks-to-pdf-documents/existing-objects-in-pdf-document/remove_and_modify_objects/output.pdf)

You can replace an object's text by assigning to `obj.text`, replace its image by assigning bytes to `obj.image_data`, and add a watermark to an image object via `image.add(watermark)` after locating it with `page.find_images()`.
