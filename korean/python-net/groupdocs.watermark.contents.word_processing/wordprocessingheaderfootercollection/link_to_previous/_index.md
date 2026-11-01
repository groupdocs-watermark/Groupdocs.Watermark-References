---
title: "link_to_previous 메서드"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "이전 섹션의 해당 머리글 및 바닥글에 모든 머리글과 바닥글을 연결하거나 연결을 해제합니다."
type: docs
url: /ko/python-net/groupdocs.watermark.contents.word_processing/wordprocessingheaderfootercollection/link_to_previous/
is_root: false
weight: 1030
---


## link_to_previous {#is_link_to_previous}

이전 섹션의 해당 머리글 및 바닥글에 모든 머리글과 바닥글을 연결하거나 연결을 해제합니다.

```python
def link_to_previous(self, is_link_to_previous):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| is_link_to_previous | `bool` | True는 헤더와 푸터를 이전 섹션에 연결하고; False는 연결을 해제합니다. |

### 예시

```python
import groupdocs.watermark as gw
from groupdocs.watermark.options.word_processing import WordProcessingLoadOptions
import groupdocs.watermark.contents.word_processing as wp

load_options = WordProcessingLoadOptions()
with gw.Watermarker("document.docx", load_options) as watermarker:
    content = watermarker.get_content()
    for i in range(1, content.sections.count):
        content.sections[i].headers_footers.link_to_previous(True)
    watermarker.save("output.docx")
```

### 또 보기
* class [`WordProcessingHeaderFooterCollection`](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingheaderfootercollection/)
