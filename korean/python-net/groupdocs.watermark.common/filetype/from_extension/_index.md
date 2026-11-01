---
title: "from_extension 메서드"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "파일 확장자를 파일 유형에 매핑합니다."
type: docs
url: /ko/python-net/groupdocs.watermark.common/filetype/from_extension/
is_root: false
weight: 1040
---


## from_extension {#extension}

파일 확장자를 파일 유형에 매핑합니다.

```python
def from_extension(cls, extension):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| extension | `str` | 파일 확장자(마침표 "." 포함). |

**Returns:** FileType: When the file type is supported returns it, otherwise returns the default `FileType.unknown` file type.

| 예외 | 설명 |
| :- | :- |
| `ValueError` | `extension`이 null이거나 빈 문자열일 때 발생합니다. |

### 또 보기
* class [`FileType`](/watermark/python-net/groupdocs.watermark.common/filetype/)
