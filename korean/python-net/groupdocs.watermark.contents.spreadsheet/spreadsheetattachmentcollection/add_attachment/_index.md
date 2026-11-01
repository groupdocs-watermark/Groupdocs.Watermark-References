---
title: "add_attachment 메서드"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "SpreadsheetWorksheet에 첨부 파일을 추가합니다."
type: docs
url: /ko/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/add_attachment/
is_root: false
weight: 1010
---


## add_attachment {#file_content-source_full_name-preview_image_content-x-y-width-height}

SpreadsheetWorksheet에 첨부 파일을 추가합니다.

```python
def add_attachment(self, file_content, source_full_name, preview_image_content, x, y, width, height):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| file_content | `list[int]` | 첨부될 파일의 내용을 포함하는 바이트. |
| source_full_name | `str` | 첨부된 파일의 전체 이름을 나타내는 str (확장자는 파일을 열 적절한 애플리케이션을 결정하는 데 사용됩니다). |
| preview_image_content | `list[int]` | 첨부된 파일의 미리보기 이미지를 바이트 배열 형태로 나타내는 bytes. |
| x | `float` | 첨부 프레임의 x 좌표 (포인트 단위)인 int. |
| y | `float` | 첨부 프레임의 y 좌표 (포인트 단위)인 int. |
| width | `float` | 첨부 프레임의 너비 (포인트 단위)인 int. |
| height | `float` | 첨부 프레임의 높이 (포인트 단위)인 int. |

**Returns:** None.

### 예시

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.spreadsheet import SpreadsheetLoadOptions

def add_attachment():
    with Watermarker("./sample.xlsx", SpreadsheetLoadOptions()) as watermarker:
        content = watermarker.get_content()
        with open("./sample.docx", "rb") as f:
            data = f.read()
        with open("./preview.png", "rb") as f:
            preview = f.read()
        # 파일을 첫 번째 워크시트에 삽입하고, 미리보기 이미지로 표시합니다.
        # x=50, y=20 위치에 100 x 120 프레임으로
        content.worksheets[0].attachments.add_attachment(data, "sample.docx", preview, 50, 20, 100, 120)
        watermarker.save("./output.xlsx")

if __name__ == "__main__":
    add_attachment()
```

### 또 보기
* class [`SpreadsheetAttachmentCollection`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetattachmentcollection/)
