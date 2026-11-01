---
title: "__init__ konstruktor"
second_title: "GroupDocs.Watermark för Python via .NET API-referenser"
description: "Initierar en ny instans av klassen PresentationLoadOptions."
type: docs
url: /sv/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initierar en ny instans av [`PresentationLoadOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/) klassen.

```python
def __init__(self):
    ...
```

### Exempel

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

Initierar en ny instans av PresentationLoadOptions‑klassen med ett angivet lösenord.

```python
def __init__(self, password):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| password | `str` | Lösenordet för att öppna krypterat innehåll. |

### Exempel

```python
    import groupdocs.watermark as gw
    from groupdocs.watermark.options.presentation import PresentationLoadOptions

    load_options = PresentationLoadOptions()
    ```

### Se även
* class [`PresentationLoadOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/)
