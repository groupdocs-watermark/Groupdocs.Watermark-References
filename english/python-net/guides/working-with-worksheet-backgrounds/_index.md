---
title: Working with worksheet backgrounds
linkTitle: "Working with"
second_title: GroupDocs.Watermark for Python via .NET API References
description: "Extract, remove, and watermark Excel worksheet background images using GroupDocs.Watermark for Python via .NET."
type: docs
url: /python-net/guides/working-with-worksheet-backgrounds/
is_root: false
weight: 280
---


Each worksheet can have a background image, available through `SpreadsheetContent.worksheets[i].background_image`. It is `None` when the worksheet has no background.

## Extract information about worksheet backgrounds

  
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.spreadsheet import SpreadsheetLoadOptions

def extract_worksheet_backgrounds():
    with Watermarker("./spreadsheet.xlsx", SpreadsheetLoadOptions()) as watermarker:
        content = watermarker.get_content()
        for i, worksheet in enumerate(content.worksheets):
            background = worksheet.background_image
            if background is not None:
                print(f"Worksheet {i}: background {background.width}x{background.height}")
            else:
                print(f"Worksheet {i}: no background")

if __name__ == "__main__":
    extract_worksheet_backgrounds()
```

  

`spreadsheet.xlsx` is the sample file used in this example. Click [here](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/adding-watermarks/add-watermarks-to-spreadsheet-documents/working-with-worksheet-backgrounds/spreadsheet.xlsx) to download it.

  
```text
Worksheet 0: no background
Worksheet 1: no background
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/advanced-usage/adding-watermarks/add-watermarks-to-spreadsheet-documents/working-with-worksheet-backgrounds/extract_worksheet_backgrounds/extract-worksheet-backgrounds.txt)

## Remove a background

Set `background_image` to `None`:

  
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.spreadsheet import SpreadsheetLoadOptions

def remove_worksheet_background():
    with Watermarker("./spreadsheet.xlsx", SpreadsheetLoadOptions()) as watermarker:
        content = watermarker.get_content()
        content.worksheets[0].background_image = None
        watermarker.save("./output.xlsx")

if __name__ == "__main__":
    remove_worksheet_background()
```

  

`spreadsheet.xlsx` is the sample file used in this example. Click [here](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/adding-watermarks/add-watermarks-to-spreadsheet-documents/working-with-worksheet-backgrounds/spreadsheet.xlsx) to download it.

  
```text
Binary file (XLSX, 9 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/advanced-usage/adding-watermarks/add-watermarks-to-spreadsheet-documents/working-with-worksheet-backgrounds/remove_worksheet_background/output.xlsx)

## Watermark existing backgrounds

Add a watermark to every worksheet that has a background image:

  
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color
from groupdocs.watermark.options.spreadsheet import SpreadsheetLoadOptions

def watermark_worksheet_backgrounds():
    with Watermarker("./spreadsheet.xlsx", SpreadsheetLoadOptions()) as watermarker:
        watermark = TextWatermark("CONFIDENTIAL", Font("Arial", 19.0))
        watermark.foreground_color = Color.red
        content = watermarker.get_content()
        for worksheet in content.worksheets:
            if worksheet.background_image is not None:
                worksheet.background_image.add(watermark)
        watermarker.save("./output.xlsx")

if __name__ == "__main__":
    watermark_worksheet_backgrounds()
```

  

`spreadsheet.xlsx` is the sample file used in this example. Click [here](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/adding-watermarks/add-watermarks-to-spreadsheet-documents/working-with-worksheet-backgrounds/spreadsheet.xlsx) to download it.

  
```text
Binary file (XLSX, 9 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/advanced-usage/adding-watermarks/add-watermarks-to-spreadsheet-documents/working-with-worksheet-backgrounds/watermark_worksheet_backgrounds/output.xlsx)

To add a fresh worksheet background watermark, use [`SpreadsheetBackgroundWatermarkOptions`](/watermark/python-net/groupdocs.watermark.options.spreadsheet/spreadsheetbackgroundwatermarkoptions/) when calling `add()`.
