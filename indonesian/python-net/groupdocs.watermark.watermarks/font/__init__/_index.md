---
title: "__init__ konstruktor"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "Menginisialisasi instance Font baru dengan nama keluarga font dan ukuran yang ditentukan."
type: docs
url: /id/python-net/groupdocs.watermark.watermarks/font/__init__/
is_root: false
weight: 10
---


## __init__ {#font_family_name-size}

Menginisialisasi instance Font baru dengan nama keluarga font dan ukuran yang ditentukan.

```python
def __init__(self, font_family_name, size):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| font_family_name | `str` | Nama keluarga font. |
| size | `float` | Ukuran font baru. |

### Contoh

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

Menginisialisasi instance Font baru dengan nama keluarga font, ukuran, dan gaya yang ditentukan.

```python
def __init__(self, font_family_name, size, style):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| font_family_name | `str` | Nama keluarga font. |
| size | `float` | Ukuran font baru. |
| style | `FontStyle` | Gaya font baru. |

### Contoh

```python
from groupdocs.watermark.watermarks import Font, FontStyle, TextWatermark

font = Font("Arial", 48.0, FontStyle.Regular)
watermark = TextWatermark("CONFIDENTIAL", font)
```

## __init__ {#font_family_name-folder_path-size}

Menginisialisasi instance Font baru dengan nama keluarga font khusus, folder yang berisi font TrueType, ukuran, dan gaya.

```python
def __init__(self, font_family_name, folder_path, size):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| font_family_name | `str` | Nama keluarga font. |
| folder_path | `str` | Path folder yang berisi file font TrueType. |
| size | `float` | Ukuran font baru. |

### Contoh

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

Menginisialisasi instance Font baru dengan nama keluarga font khusus, folder yang berisi file font TrueType, dan ukuran.

```python
def __init__(self, font_family_name, folder_path, size, style):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| font_family_name | `str` | Nama keluarga font. |
| folder_path | `str` | Path folder yang berisi file font TrueType. |
| size | `float` | Ukuran font baru. |
| style | `FontStyle` |  |

### Contoh

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

### Lihat Juga
* class [`Font`](/watermark/python-net/groupdocs.watermark.watermarks/font/)
