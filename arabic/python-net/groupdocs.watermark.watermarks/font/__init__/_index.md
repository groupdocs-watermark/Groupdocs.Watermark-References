---
title: "منشئ __init__"
second_title: "مراجع API لـ GroupDocs.Watermark للبايثون عبر .NET"
description: "يُنشئ مثلاً جديدًا من الفئة Font بالاسم العائلي للخط والحجم المحددين."
type: docs
url: /ar/python-net/groupdocs.watermark.watermarks/font/__init__/
is_root: false
weight: 10
---


## __init__ {#font_family_name-size}

يُنشئ مثلاً جديدًا من الفئة Font بالاسم العائلي للخط والحجم المحددين.

```python
def __init__(self, font_family_name, size):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| font_family_name | `str` | اسم عائلة الخط. |
| size | `float` | حجم الخط الجديد. |

### مثال

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

يُنشئ مثلاً جديدًا من الفئة Font بالاسم العائلي للخط، والحجم، والنمط المحددين.

```python
def __init__(self, font_family_name, size, style):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| font_family_name | `str` | اسم عائلة الخط. |
| size | `float` | حجم الخط الجديد. |
| style | `FontStyle` | نمط الخط الجديد. |

### مثال

```python
from groupdocs.watermark.watermarks import Font, FontStyle, TextWatermark

font = Font("Arial", 48.0, FontStyle.Regular)
watermark = TextWatermark("CONFIDENTIAL", font)
```

## __init__ {#font_family_name-folder_path-size}

يُنشئ مثلاً جديدًا من الفئة Font باسم عائلة خط مخصص، ومجلد يحتوي على خطوط TrueType، وحجم، ونمط.

```python
def __init__(self, font_family_name, folder_path, size):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| font_family_name | `str` | اسم عائلة الخط. |
| folder_path | `str` | مسار المجلد الذي يحتوي على ملفات خطوط TrueType. |
| size | `float` | حجم الخط الجديد. |

### مثال

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

يُنشئ مثلاً جديدًا من الفئة Font باسم عائلة خط مخصص، والمجلد الذي يحتوي على ملفات خطوط TrueType، وحجم.

```python
def __init__(self, font_family_name, folder_path, size, style):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| font_family_name | `str` | اسم عائلة الخط. |
| folder_path | `str` | مسار المجلد الذي يحتوي على ملفات خطوط TrueType. |
| size | `float` | حجم الخط الجديد. |
| style | `FontStyle` |  |

### مثال

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

### انظر أيضًا
* class [`Font`](/watermark/python-net/groupdocs.watermark.watermarks/font/)
