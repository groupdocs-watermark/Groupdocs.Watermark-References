---
title: "__init__ yapıcı"
second_title: "GroupDocs.Watermark Python için .NET API Referansları"
description: "Belirtilen yazı tipi ailesi adı ve boyutuyla yeni bir Font örneği oluşturur."
type: docs
url: /tr/python-net/groupdocs.watermark.watermarks/font/__init__/
is_root: false
weight: 10
---


## __init__ {#font_family_name-size}

Belirtilen yazı tipi ailesi adı ve boyutuyla yeni bir Font örneği oluşturur.

```python
def __init__(self, font_family_name, size):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| font_family_name | `str` | Yazı tipi ailesi adı. |
| size | `float` | Yeni yazı tipinin boyutu. |

### Örnek

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

Belirtilen yazı tipi ailesi adı, boyut ve stil ile yeni bir Font örneği oluşturur.

```python
def __init__(self, font_family_name, size, style):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| font_family_name | `str` | Yazı tipi ailesi adı. |
| size | `float` | Yeni yazı tipinin boyutu. |
| style | `FontStyle` | Yeni yazı tipinin stili. |

### Örnek

```python
from groupdocs.watermark.watermarks import Font, FontStyle, TextWatermark

font = Font("Arial", 48.0, FontStyle.Regular)
watermark = TextWatermark("CONFIDENTIAL", font)
```

## __init__ {#font_family_name-folder_path-size}

Özel bir yazı tipi ailesi adı, TrueType yazı tiplerini içeren bir klasör, bir boyut ve bir stil ile yeni bir Font örneği oluşturur.

```python
def __init__(self, font_family_name, folder_path, size):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| font_family_name | `str` | Yazı tipi ailesi adı. |
| folder_path | `str` | TrueType yazı tipi dosyalarını içeren klasör yolu. |
| size | `float` | Yeni yazı tipinin boyutu. |

### Örnek

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

Özel bir yazı tipi ailesi adı, TrueType yazı tipi dosyalarını içeren klasör ve bir boyut ile yeni bir Font örneği oluşturur.

```python
def __init__(self, font_family_name, folder_path, size, style):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| font_family_name | `str` | Yazı tipi ailesi adı. |
| folder_path | `str` | TrueType yazı tipi dosyalarını içeren klasör yolu. |
| size | `float` | Yeni yazı tipinin boyutu. |
| style | `FontStyle` |  |

### Örnek

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

### Ayrıca Bakınız
* class [`Font`](/watermark/python-net/groupdocs.watermark.watermarks/font/)
