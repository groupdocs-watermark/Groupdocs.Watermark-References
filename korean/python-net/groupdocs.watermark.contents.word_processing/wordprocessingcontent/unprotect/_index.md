---
title: "unprotect 메서드"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "암호와 관계없이 문서의 보호를 해제합니다."
type: docs
url: /ko/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/unprotect/
is_root: false
weight: 1090
---


## unprotect

암호와 관계없이 문서의 보호를 해제합니다.

```python
def unprotect(self):
    ...
```

### 예시

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.word_processing import WordProcessingLoadOptions

def unprotect_document():
    with Watermarker("./document.docx", WordProcessingLoadOptions()) as watermarker:
        content = watermarker.get_content()
        content.unprotect()
        watermarker.save("./output.docx")

if __name__ == "__main__":
    unprotect_document()
```

### 또 보기
* class [`WordProcessingContent`](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/)
