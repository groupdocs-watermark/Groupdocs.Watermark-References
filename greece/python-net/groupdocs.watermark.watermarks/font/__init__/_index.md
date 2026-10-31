---
title: "__init__ κατασκευαστής"
second_title: "GroupDocs.Watermark για Python μέσω .NET Αναφορές API"
description: "Δημιουργεί ένα νέο αντικείμενο Font με το καθορισμένο όνομα οικογένειας γραμματοσειράς και μέγεθος."
type: docs
url: /el/python-net/groupdocs.watermark.watermarks/font/__init__/
is_root: false
weight: 10
---


## __init__ {#font_family_name-size}

Δημιουργεί ένα νέο αντικείμενο Font με το καθορισμένο όνομα οικογένειας γραμματοσειράς και μέγεθος.

```python
def __init__(self, font_family_name, size):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| font_family_name | `str` | Το όνομα οικογένειας γραμματοσειράς. |
| size | `float` | Το μέγεθος της νέας γραμματοσειράς. |

### Παράδειγμα

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

Δημιουργεί ένα νέο αντικείμενο Font με το καθορισμένο όνομα οικογένειας γραμματοσειράς, μέγεθος και στυλ.

```python
def __init__(self, font_family_name, size, style):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| font_family_name | `str` | Το όνομα οικογένειας γραμματοσειράς. |
| size | `float` | Το μέγεθος της νέας γραμματοσειράς. |
| style | `FontStyle` | Το στυλ της νέας γραμματοσειράς. |

### Παράδειγμα

```python
from groupdocs.watermark.watermarks import Font, FontStyle, TextWatermark

font = Font("Arial", 48.0, FontStyle.Regular)
watermark = TextWatermark("CONFIDENTIAL", font)
```

## __init__ {#font_family_name-folder_path-size}

Δημιουργεί ένα νέο αντικείμενο Font με προσαρμοσμένο όνομα οικογένειας γραμματοσειράς, φάκελο που περιέχει γραμματοσειρές TrueType, μέγεθος και στυλ.

```python
def __init__(self, font_family_name, folder_path, size):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| font_family_name | `str` | Το όνομα οικογένειας γραμματοσειράς. |
| folder_path | `str` | Διαδρομή φακέλου που περιέχει αρχεία γραμματοσειρών TrueType. |
| size | `float` | Το μέγεθος της νέας γραμματοσειράς. |

### Παράδειγμα

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

Δημιουργεί ένα νέο αντικείμενο Font με προσαρμοσμένο όνομα οικογένειας γραμματοσειράς, το φάκελο που περιέχει τα αρχεία γραμματοσειρών TrueType, και μέγεθος.

```python
def __init__(self, font_family_name, folder_path, size, style):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| font_family_name | `str` | Το όνομα οικογένειας γραμματοσειράς. |
| folder_path | `str` | Διαδρομή φακέλου που περιέχει αρχεία γραμματοσειρών TrueType. |
| size | `float` | Το μέγεθος της νέας γραμματοσειράς. |
| style | `FontStyle` |  |

### Παράδειγμα

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

### Δείτε επίσης
* class [`Font`](/watermark/python-net/groupdocs.watermark.watermarks/font/)
