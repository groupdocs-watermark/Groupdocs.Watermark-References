---
title: Working with spreadsheet document attachments
linkTitle: "Working with"
second_title: GroupDocs.Watermark for Python via .NET API References
description: "Extract, add, remove, and watermark the OLE attachments embedded in Excel worksheets using GroupDocs.Watermark for Python via .NET."
type: docs
url: /python-net/guides/working-with-spreadsheet-document-attachments/
is_root: false
weight: 210
---


Excel worksheets can embed file attachments (OLE objects). They are available through `SpreadsheetContent.worksheets[i].attachments`. Each attachment exposes `alternative_text`, `is_link`, `source_full_name`, `content`, and `get_document_info()`, and the document it contains can be opened in its own [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/).

## Extract attachments

  
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.spreadsheet import SpreadsheetLoadOptions

def extract_attachments():
    with Watermarker("./spreadsheet.xlsx", SpreadsheetLoadOptions()) as watermarker:
        content = watermarker.get_content()
        for i, worksheet in enumerate(content.worksheets):
            for attachment in worksheet.attachments:
                info = attachment.get_document_info()
                print(f"Worksheet {i}: {attachment.alternative_text!r} type={info.file_type}")
                with open(f"./{attachment.alternative_text}", "wb") as f:
                    f.write(attachment.content)

if __name__ == "__main__":
    extract_attachments()
```

  

`spreadsheet.xlsx` is the sample file used in this example. Click [here](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/adding-watermarks/add-watermarks-to-spreadsheet-documents/working-with-spreadsheet-document-attachments/spreadsheet.xlsx) to download it.

## Remove an attachment

The `attachments` collection supports `remove_at(index)` and `remove(attachment)`. Iterate in reverse when removing by index:

  
```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.spreadsheet import SpreadsheetLoadOptions

def remove_attachment():
    with Watermarker("./spreadsheet.xlsx", SpreadsheetLoadOptions()) as watermarker:
        content = watermarker.get_content()
        for worksheet in content.worksheets:
            for i in range(len(worksheet.attachments) - 1, -1, -1):
                if worksheet.attachments[i].is_link:
                    worksheet.attachments.remove_at(i)
        watermarker.save("./output.xlsx")

if __name__ == "__main__":
    remove_attachment()
```

  

`spreadsheet.xlsx` is the sample file used in this example. Click [here](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/adding-watermarks/add-watermarks-to-spreadsheet-documents/working-with-spreadsheet-document-attachments/spreadsheet.xlsx) to download it.

  
```text
Binary file (XLSX, 9 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/advanced-usage/adding-watermarks/add-watermarks-to-spreadsheet-documents/working-with-spreadsheet-document-attachments/remove_attachment/output.xlsx)

## Watermark the attached documents

Open each attachment's bytes in its own [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/), add a watermark, and write the result back:

  
```python
import io
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color
from groupdocs.watermark.options.spreadsheet import SpreadsheetLoadOptions

def watermark_attached_documents():
    with Watermarker("./spreadsheet.xlsx", SpreadsheetLoadOptions()) as watermarker:
        content = watermarker.get_content()
        for worksheet in content.worksheets:
            for attachment in worksheet.attachments:
                with Watermarker(io.BytesIO(attachment.content)) as inner:
                    wm = TextWatermark("CONFIDENTIAL", Font("Arial", 19.0))
                    wm.foreground_color = Color.red
                    inner.add(wm)
                    buffer = io.BytesIO()
                    inner.save(buffer)
                # write the watermarked attachment bytes back as needed
        watermarker.save("./output.xlsx")

if __name__ == "__main__":
    watermark_attached_documents()
```

  

`spreadsheet.xlsx` is the sample file used in this example. Click [here](https://docs.groupdocs.com/watermark/python-net/_sample_files/developer-guide/advanced-usage/adding-watermarks/add-watermarks-to-spreadsheet-documents/working-with-spreadsheet-document-attachments/spreadsheet.xlsx) to download it.

  
```text
Binary file (XLSX, 9 KB)
```
[Download full output](https://docs.groupdocs.com/watermark/python-net/_output_files/developer-guide/advanced-usage/adding-watermarks/add-watermarks-to-spreadsheet-documents/working-with-spreadsheet-document-attachments/watermark_attached_documents/output.xlsx)
