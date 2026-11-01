---
title: "to_argb 메서드"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "이 Color 구조체의 32비트 ARGB 값을 반환합니다."
type: docs
url: /ko/python-net/groupdocs.watermark.watermarks/color/to_argb/
is_root: false
weight: 1100
---


## to_argb

이 [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color/) 구조체의 32비트 ARGB 값을 반환합니다.

```python
def to_argb(self):
    ...
```

**Returns:** int: The 32-bit ARGB value.

### 예시

```python
from groupdocs.watermark import Watermarker
with Watermarker("diagram.vsdx") as watermarker:
    content = watermarker.get_content()
    argb = content.header_footer.text_color.to_argb()
    print(argb)
```

### 또 보기
* class [`Color`](/watermark/python-net/groupdocs.watermark.watermarks/color/)
