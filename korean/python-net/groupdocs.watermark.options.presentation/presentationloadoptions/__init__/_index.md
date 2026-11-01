---
title: "__init__ 생성자"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "PresentationLoadOptions 클래스의 새 인스턴스를 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/__init__/
is_root: false
weight: 10
---


## __init__

새 [`PresentationLoadOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/) 클래스 인스턴스를 초기화합니다.

```python
def __init__(self):
    ...
```

### 예시

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.presentation import PresentationLoadOptions

def remove_slide_background():
    with Watermarker("./presentation.pptx", PresentationLoadOptions()) as watermarker:
        content = watermarker.get_content()
        content.slides[0].image_fill_format.background_image = None
        watermarker.save("./output.pptx")
```

## __init__ {#password}

지정된 비밀번호와 함께 PresentationLoadOptions 클래스의 새 인스턴스를 초기화합니다.

```python
def __init__(self, password):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| password | `str` | 암호화된 콘텐츠를 열기 위한 비밀번호. |

### 예시

```python
    import groupdocs.watermark as gw
    from groupdocs.watermark.options.presentation import PresentationLoadOptions

    load_options = PresentationLoadOptions()
    ```

### 또 보기
* class [`PresentationLoadOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/)
