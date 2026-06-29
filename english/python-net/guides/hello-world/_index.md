---
title: Hello, World!
linkTitle: "Hello, World!"
second_title: GroupDocs.Watermark for Python via .NET API References
description: "Quickly get started with GroupDocs.Watermark for Python via .NET by creating and running a simple example."
type: docs
url: /python-net/guides/hello-world/
is_root: false
weight: 20
---


## Introduction
A "Hello, World!" example is often the first step when exploring GroupDocs.Watermark for Python via .NET. It serves as a simple test to confirm that your development environment is correctly set up and that the library is functioning as expected.

## Overview
GroupDocs.Watermark for Python via .NET lets you add, search, and remove watermarks in various document formats. A wide range of [supported formats](https://docs.groupdocs.com/watermark/python-net/getting-started/supported-document-formats/) makes it versatile for different use cases.

## How to add a watermark
The following steps demonstrate how to add a text watermark to a document using GroupDocs.Watermark for Python via .NET:

1. Import the `groupdocs.watermark` classes you need.
2. Open a [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/) with the path to the sample document.
3. Create a [`TextWatermark`](/watermark/python-net/groupdocs.watermark.watermarks/textwatermark/) with the desired text and font, and style it.
4. Apply the watermark with `add()`.
5. Save the result.

## Complete example
The example below adds a semi-transparent, diagonal "Hello, Watermark!" text watermark and saves the result:

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color

def hello_world():
    # Open the document, add a single text watermark, and save the result
    with Watermarker("./sample.pdf") as watermarker:
        watermark = TextWatermark("Hello, Watermark!", Font("Arial", 36.0))
        watermark.foreground_color = Color.red
        watermark.opacity = 0.5
        watermark.rotate_angle = 45.0
        watermarker.add(watermark)
        watermarker.save("./output.pdf")

    print("Watermark added successfully. Output saved to ./output.pdf.")

if __name__ == "__main__":
    hello_world()
```

`sample.pdf` is the sample file used in this example. Click [here](https://docs.groupdocs.com/watermark/python-net/_sample_files/getting-started/hello-world/sample.pdf) to download it.

  
```text
Binary file (PDF, 354 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/getting-started/hello-world/hello_world/output.pdf)

The watermark is saved back to the same PDF format as `output.pdf`. To stamp a different document, change the input path and the output extension — GroupDocs.Watermark saves in the input document's format.

## Additional resources
This demo references the GroupDocs.Watermark for Python via .NET [code samples](https://github.com/groupdocs-watermark/GroupDocs.Watermark-for-Python-via-.NET/).
