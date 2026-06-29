---
title: Document preview
linkTitle: "Document preview"
second_title: GroupDocs.Watermark for Python via .NET API References
description: "Generate preview images (PNG/JPG/BMP) for document pages using GroupDocs.Watermark for Python via .NET."
type: docs
url: /python-net/guides/preview/
is_root: false
weight: 110
---


GroupDocs.Watermark can render document pages as images so you can show page thumbnails without fully opening a document in a viewer. You drive the render with a `create_page_stream` callback that supplies a writable file stream for each page — the library writes the page image to it and closes it for you.

## Generate a document preview

Set [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/) with a `create_page_stream` callback, choose the `preview_format`, and list the `page_numbers` to render.

  
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options import PreviewOptions, PreviewFormats

def generate_preview():
    # Supply a writable file stream for each page to render
    def create_page_stream(page_number):
        return open(f"./output-page-{page_number}.png", "wb")

    with Watermarker("./sample.pdf") as watermarker:
        options = PreviewOptions(create_page_stream)
        options.preview_format = PreviewFormats.PNG
        options.page_numbers = [1, 2]
        watermarker.generate_preview(options)

if __name__ == "__main__":
    generate_preview()
```

  

`sample.pdf` is the two-page sample file used in this example. Click [here](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/basic-usage/preview/sample.pdf) to download it.

  
```text
output-page-1.png (597 KB)
output-page-2.png (129 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/basic-usage/preview/generate_preview/generate-preview-outputs.zip)

The page images are written to the current directory — one PNG per requested page. Use `PreviewFormats.JPEG` or `PreviewFormats.BMP` for other formats, and set `options.width` / `options.height` to control the rendered size.

The library owns the lifecycle of the stream returned by `create_page_stream` and closes it after writing the page. A two-argument form, `PreviewOptions(create_page_stream, release_page_stream)`, is also available, but the release callback receives `stream=None` because the bridge has already closed the stream — capture the stream in the `create_page_stream` closure if you need to act on it.

**Use case:** Generate page previews to display in a web app, dashboard, or document-management system without requiring users to download the full file.
