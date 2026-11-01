---
title: "create_watermarker 메서드"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "첨부된 파일에서 콘텐츠를 로드합니다."
type: docs
url: /ko/python-net/groupdocs.watermark.common/attachment/create_watermarker/
is_root: false
weight: 1010
---


## create_watermarker

첨부된 파일에서 콘텐츠를 로드합니다.

```python
def create_watermarker(self):
    ...
```

**Returns:** The instance of appropriate descendant of `Content` class.

### 예시

```python
    import groupdocs.watermark as gw
    import groupdocs.watermark.contents.pdf as gwc_pdf
    import groupdocs.watermark.watermarks as gww

    watermark = gww.TextWatermark("This is WaterMark on Attachment", gww.Font("Arial", 19.0))

    with gw.Watermarker("document.pdf") as watermarker:
        pdf_content = watermarker.get_content()
        for attachment in pdf_content.attachments:
            with attachment.create_watermarker() as attached:
                attached.add(watermark)
                attached.save()
    ```

## create_watermarker {#load_options}

지정된 로드 옵션으로 첨부된 파일에서 콘텐츠를 로드합니다.

```python
def create_watermarker(self, load_options):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| load_options | `LoadOptions` | 첨부 파일 내용을 로드할 때 사용할 추가 옵션. |

**Returns:** Content: The instance of appropriate descendant of `Content` class.

### 예시

```python
import groupdocs.watermark as gw
from groupdocs.watermark.options.pdf import PdfLoadOptions
import groupdocs.watermark.contents.pdf as gwc_pdf
import groupdocs.watermark.watermarks as gww
from groupdocs.watermark.common import FileType

watermark = gww.TextWatermark("This is WaterMark on Attachment", gww.Font("Arial", 19.0))

load_options = PdfLoadOptions()
with gw.Watermarker("document.pdf", load_options) as watermarker:
    pdf_content = watermarker.get_content()
    for attachment in pdf_content.attachments:
        info = attachment.get_document_info()
        if info.file_type != FileType.UNKNOWN and not info.is_encrypted:
            with attachment.create_watermarker() as attached:
                attached.add(watermark)
                attached.save()
    watermarker.save("output.pdf")
```

## create_watermarker {#load_options-watermarker_settings}

지정된 로드 옵션 및 설정으로 첨부된 파일에서 콘텐츠를 로드합니다.

```python
def create_watermarker(self, load_options, watermarker_settings):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| load_options | `LoadOptions` | 첨부 파일 내용을 로드할 때 사용할 추가 옵션. |
| watermarker_settings | `WatermarkerSettings` | 로드된 문서를 작업할 때 사용할 추가 설정. |

**Returns:** The instance of appropriate descendant of `Content` class.

### 예시

```python
import groupdocs.watermark as gw
import groupdocs.watermark.contents.pdf as gwc_pdf
import groupdocs.watermark.watermarks as gww

watermark = gww.TextWatermark("Sample watermark", gww.Font("Arial", 19.0))

with gw.Watermarker("document.pdf") as watermarker:
    pdf_content = watermarker.get_content()
    for attachment in pdf_content.attachments:
        with attachment.create_watermarker() as attached:
            attached.add(watermark)
            attached.save()
    watermarker.save("output.pdf")
```

### 또 보기
* class [`Attachment`](/watermark/python-net/groupdocs.watermark.common/attachment/)
