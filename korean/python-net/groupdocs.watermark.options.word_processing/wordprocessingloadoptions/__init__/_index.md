---
title: "__init__ 생성자"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "WordProcessingLoadOptions 클래스의 새 인스턴스를 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/__init__/
is_root: false
weight: 10
---


## __init__

새 [`WordProcessingLoadOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/) 클래스 인스턴스를 초기화합니다.

```python
def __init__(self):
    ...
```

## __init__ {#password}

지정된 비밀번호로 WordProcessingLoadOptions 클래스의 새 인스턴스를 초기화합니다.

```python
def __init__(self, password):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| password | `str` | 암호화된 콘텐츠를 열기 위한 비밀번호. |

### 예시

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.word_processing import WordProcessingLoadOptions

with Watermarker("./document.docx", WordProcessingLoadOptions()) as watermarker:
    # 워터마크 작업을 수행합니다
    pass
```

### 또 보기
* class [`WordProcessingLoadOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/)
