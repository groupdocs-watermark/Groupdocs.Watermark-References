---
title: "__init__ Konstruktor"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "Initialisiert eine neue Instanz der Klasse PresentationLoadOptions."
type: docs
url: /de/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initialisiert eine neue Instanz der [`PresentationLoadOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/) Klasse.

```python
def __init__(self):
    ...
```

### Beispiel

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

Initialisiert eine neue Instanz der PresentationLoadOptions Klasse mit einem angegebenen Passwort.

```python
def __init__(self, password):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| password | `str` | Das Passwort zum Öffnen eines verschlüsselten Inhalts. |

### Beispiel

```python
    import groupdocs.watermark as gw
    from groupdocs.watermark.options.presentation import PresentationLoadOptions

    load_options = PresentationLoadOptions()
    ```

### Siehe auch
* class [`PresentationLoadOptions`](/watermark/python-net/groupdocs.watermark.options.presentation/presentationloadoptions/)
