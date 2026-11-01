---
title: "add_link 메서드"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "링크를 통해 첨부 파일을 추가합니다 (문서에 첨부 파일 내용이 포함되지 않습니다)."
type: docs
url: /ko/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/add_link/
is_root: false
weight: 1050
---


## add_link {#source_full_name-preview_image_content-x-y-width-height}

링크를 통해 첨부 파일을 추가합니다 (문서에 첨부 파일 내용이 포함되지 않습니다).

```python
def add_link(self, source_full_name, preview_image_content, x, y, width, height):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| source_full_name | `str` | 링크된 파일 경로. |
| preview_image_content | `list[int]` | 첨부된 파일 미리보기 이미지가 바이트 배열로 제공됩니다. |
| x | `float` | 첨부 프레임의 x 좌표(포인트 단위). |
| y | `float` | 첨부 프레임의 y 좌표(포인트 단위). |
| width | `float` | 첨부 프레임의 너비(포인트 단위)입니다. |
| height | `float` | 첨부 프레임의 높이(포인트 단위)입니다. |

### 예시

```python
import groupdocs.watermark as gw
from groupdocs.watermark.options.spreadsheet import SpreadsheetLoadOptions
import groupdocs.watermark.contents.spreadsheet as gwc_xls

load_options = SpreadsheetLoadOptions()
with gw.Watermarker("spreadsheet.xlsx", load_options) as watermarker:
    content = watermarker.get_content()
    worksheet = content.worksheets[0]
    with open("document_preview.png", "rb") as f_prev:
        worksheet.attachments.add_link(
            "document.docx",
            f_prev.read(),
            50,
            100,
            200,
            400,
        )
    watermarker.save("output.xlsx")
```

### 또 보기
* class [`SpreadsheetAttachmentCollection`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/)
