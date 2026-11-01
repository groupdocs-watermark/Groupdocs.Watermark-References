---
title: "__init__ 생성자"
second_title: "Python용 .NET을 통한 GroupDocs.Watermark API 참조"
description: "지정된 글꼴 패밀리 이름과 크기로 새로운 Font 인스턴스를 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.watermark.watermarks/font/__init__/
is_root: false
weight: 10
---


## __init__ {#font_family_name-size}

지정된 글꼴 패밀리 이름과 크기로 새로운 Font 인스턴스를 초기화합니다.

```python
def __init__(self, font_family_name, size):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| font_family_name | `str` | 글꼴 패밀리 이름입니다. |
| size | `float` | 새 글꼴의 크기입니다. |

### 예시

```python
    from groupdocs.watermark import Watermarker
    from groupdocs.watermark.watermarks import TextWatermark, Font, Color

    with Watermarker("document.pdf") as watermarker:
        watermark = TextWatermark("CONFIDENTIAL", Font("Arial", 48))
        watermark.foreground_color = Color.red
        watermark.opacity = 0.5
        watermarker.add(watermark)
        watermarker.save("watermarked.pdf")
    ```

## __init__ {#font_family_name-size-style}

지정된 글꼴 패밀리 이름, 크기 및 스타일로 새로운 Font 인스턴스를 초기화합니다.

```python
def __init__(self, font_family_name, size, style):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| font_family_name | `str` | 글꼴 패밀리 이름입니다. |
| size | `float` | 새 글꼴의 크기입니다. |
| style | `FontStyle` | 새 글꼴의 스타일입니다. |

### 예시

```python
from groupdocs.watermark.watermarks import Font, FontStyle, TextWatermark

font = Font("Arial", 48.0, FontStyle.Regular)
watermark = TextWatermark("CONFIDENTIAL", font)
```

## __init__ {#font_family_name-folder_path-size}

맞춤 글꼴 패밀리 이름, TrueType 글꼴이 포함된 폴더, 크기 및 스타일로 새로운 Font 인스턴스를 초기화합니다.

```python
def __init__(self, font_family_name, folder_path, size):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| font_family_name | `str` | 글꼴 패밀리 이름입니다. |
| folder_path | `str` | TrueType 글꼴 파일이 포함된 폴더 경로입니다. |
| size | `float` | 새 글꼴의 크기입니다. |

### 예시

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color

fonts_folder = r"c:\CustomFonts"
with Watermarker("./sample.pdf") as watermarker:
    watermark = TextWatermark(
        "Test watermark",
        Font("CustomFontName", fonts_folder, 36.0)
    )
    watermark.foreground_color = Color.blue
    watermark.opacity = 0.5
    watermarker.add(watermark)
    watermarker.save("./output.pdf")
```

## __init__ {#font_family_name-folder_path-size-style}

맞춤 글꼴 패밀리 이름, TrueType 글꼴 파일이 포함된 폴더, 그리고 크기로 새로운 Font 인스턴스를 초기화합니다.

```python
def __init__(self, font_family_name, folder_path, size, style):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| font_family_name | `str` | 글꼴 패밀리 이름입니다. |
| folder_path | `str` | TrueType 글꼴 파일이 포함된 폴더 경로입니다. |
| size | `float` | 새 글꼴의 크기입니다. |
| style | `FontStyle` |  |

### 예시

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font, Color

with Watermarker("./sample.pdf") as watermarker:
    watermark = TextWatermark(
        "Test watermark",
        Font("CustomFontName", r"c:\CustomFonts", 36.0)
    )
    watermark.foreground_color = Color.blue
    watermark.opacity = 0.5
    watermarker.add(watermark)
    watermarker.save("./output.pdf")
```

### 또 보기
* class [`Font`](/watermark/python-net/groupdocs.watermark.watermarks/font/)
