---
title: "Attachment 클래스"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "문서에 첨부된 파일을 나타냅니다."
type: docs
url: /ko/python-net/groupdocs.watermark.common/attachment/
is_root: false
weight: 10
---


## Attachment class

문서에 첨부된 파일을 나타냅니다.

자세히 알아보기

- https://docs.groupdocs.com/display/watermarknet/Email+attachments
- https://docs.groupdocs.com/display/watermarknet/Attachments+in+PDF+document
- https://docs.groupdocs.com/display/watermarknet/Working+with+spreadsheet+document+attachments

Attachment 유형은 다음 멤버를 노출합니다:

### 메서드
| 메서드 | 설명 |
| :- | :- |
| [create_watermarker](/watermark/python-net/groupdocs.watermark.common/attachment/create_watermarker/) | 첨부된 파일에서 콘텐츠를 로드합니다. |
| [create_watermarker](/watermark/python-net/groupdocs.watermark.common/attachment/create_watermarker/#load_options) | 지정된 로드 옵션으로 첨부된 파일에서 콘텐츠를 로드합니다. |
| [create_watermarker](/watermark/python-net/groupdocs.watermark.common/attachment/create_watermarker/#load_options-watermarker_settings) | 지정된 로드 옵션 및 설정으로 첨부된 파일에서 콘텐츠를 로드합니다. |
| [create_watermarker_load_options](/watermark/python-net/groupdocs.watermark.common/attachment/create_watermarker_load_options/) |  |
| [get_document_info](/watermark/python-net/groupdocs.watermark.common/attachment/get_document_info/) | 첨부된 파일에 저장된 문서에 대한 정보를 검색합니다. |

### 속성
| 속성 | 설명 |
| :- | :- |
| [content](/watermark/python-net/groupdocs.watermark.common/attachment/content/) | 첨부된 파일 콘텐츠. |

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

### 또 보기
* module [`groupdocs.watermark.common`](/watermark/python-net/groupdocs.watermark.common/)
