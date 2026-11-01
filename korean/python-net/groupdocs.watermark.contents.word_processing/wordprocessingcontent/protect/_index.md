---
title: "protect 메서드"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "문서를 변경으로부터 보호하고 보호 암호를 설정합니다."
type: docs
url: /ko/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/protect/
is_root: false
weight: 1050
---


## protect {#protection_type-password}

문서를 변경으로부터 보호하고 보호 암호를 설정합니다.

문서의 내용을 편집 가능하게 하려면, `WordProcessingLockType.allow_only_form_fields` 또는 `WordProcessingLockType.read_only_with_editable_content` 매개변수를 사용하여 워터마크를 추가하는 적절한 메서드를 사용하십시오.

```python
def protect(self, protection_type, password):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| protection_type | `WordProcessingProtectionType` | 문서에 대한 보호 유형을 지정합니다. |
| password | `str` | 문서를 보호하기 위한 비밀번호입니다. |

### 예시

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.word_processing import WordProcessingLoadOptions
from groupdocs.watermark.contents.word_processing import WordProcessingProtectionType

def protect_document():
    with Watermarker("./document.docx", WordProcessingLoadOptions()) as watermarker:
        content = watermarker.get_content()
        content.protect(WordProcessingProtectionType.READ_ONLY, "p@ssw0rd")
        watermarker.save("./output.docx")
```

### 또 보기
* class [`WordProcessingContent`](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/)
