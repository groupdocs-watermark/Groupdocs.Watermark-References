---
title: "__init__ конструктор"
second_title: "GroupDocs.Watermark для Python через .NET справочник API"
description: "Инициализирует новый экземпляр Font с указанным названием семейства шрифтов и размером."
type: docs
url: /ru/python-net/groupdocs.watermark.watermarks/font/__init__/
is_root: false
weight: 10
---


## __init__ {#font_family_name-size}

Инициализирует новый экземпляр Font с указанным названием семейства шрифтов и размером.

```python
def __init__(self, font_family_name, size):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| font_family_name | `str` | Название семейства шрифта. |
| size | `float` | Размер нового шрифта. |

### Пример

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

Инициализирует новый экземпляр Font с указанным названием семейства шрифтов, размером и стилем.

```python
def __init__(self, font_family_name, size, style):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| font_family_name | `str` | Название семейства шрифта. |
| size | `float` | Размер нового шрифта. |
| style | `FontStyle` | Стиль нового шрифта. |

### Пример

```python
from groupdocs.watermark.watermarks import Font, FontStyle, TextWatermark

font = Font("Arial", 48.0, FontStyle.Regular)
watermark = TextWatermark("CONFIDENTIAL", font)
```

## __init__ {#font_family_name-folder_path-size}

Инициализирует новый экземпляр Font с пользовательским названием семейства шрифтов, папкой, содержащей TrueType шрифты, размером и стилем.

```python
def __init__(self, font_family_name, folder_path, size):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| font_family_name | `str` | Название семейства шрифта. |
| folder_path | `str` | Путь к папке, содержащей файлы шрифтов TrueType. |
| size | `float` | Размер нового шрифта. |

### Пример

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

Инициализирует новый экземпляр Font с пользовательским названием семейства шрифтов, папкой, содержащей файлы TrueType шрифтов, и размером.

```python
def __init__(self, font_family_name, folder_path, size, style):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| font_family_name | `str` | Название семейства шрифта. |
| folder_path | `str` | Путь к папке, содержащей файлы шрифтов TrueType. |
| size | `float` | Размер нового шрифта. |
| style | `FontStyle` |  |

### Пример

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

### См. также
* class [`Font`](/watermark/python-net/groupdocs.watermark.watermarks/font/)
