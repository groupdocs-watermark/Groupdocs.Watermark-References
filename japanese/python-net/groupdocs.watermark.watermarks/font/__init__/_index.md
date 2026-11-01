---
title: "__init__ コンストラクタ"
second_title: "GroupDocs.Watermark for Python via .NET API リファレンス"
description: "指定されたフォントファミリ名とサイズで新しい Font インスタンスを初期化します。"
type: docs
url: /ja/python-net/groupdocs.watermark.watermarks/font/__init__/
is_root: false
weight: 10
---


## __init__ {#font_family_name-size}

指定されたフォントファミリ名とサイズで新しい Font インスタンスを初期化します。

```python
def __init__(self, font_family_name, size):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| font_family_name | `str` | フォント ファミリ名です。 |
| size | `float` | 新しいフォントのサイズ。 |

### 例

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

指定されたフォントファミリ名、サイズ、スタイルで新しい Font インスタンスを初期化します。

```python
def __init__(self, font_family_name, size, style):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| font_family_name | `str` | フォント ファミリ名です。 |
| size | `float` | 新しいフォントのサイズ。 |
| style | `FontStyle` | 新しいフォントのスタイル。 |

### 例

```python
from groupdocs.watermark.watermarks import Font, FontStyle, TextWatermark

font = Font("Arial", 48.0, FontStyle.Regular)
watermark = TextWatermark("CONFIDENTIAL", font)
```

## __init__ {#font_family_name-folder_path-size}

カスタムフォントファミリ名、TrueType フォントを含むフォルダー、サイズ、スタイルで新しい Font インスタンスを初期化します。

```python
def __init__(self, font_family_name, folder_path, size):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| font_family_name | `str` | フォント ファミリ名です。 |
| folder_path | `str` | TrueType フォントファイルが含まれるフォルダー パス。 |
| size | `float` | 新しいフォントのサイズ。 |

### 例

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

カスタムフォントファミリ名、TrueType フォントファイルを含むフォルダー、サイズで新しい Font インスタンスを初期化します。

```python
def __init__(self, font_family_name, folder_path, size, style):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| font_family_name | `str` | フォント ファミリ名です。 |
| folder_path | `str` | TrueType フォントファイルが含まれるフォルダー パス。 |
| size | `float` | 新しいフォントのサイズ。 |
| style | `FontStyle` |  |

### 例

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

### 関連項目
* class [`Font`](/watermark/python-net/groupdocs.watermark.watermarks/font/)
