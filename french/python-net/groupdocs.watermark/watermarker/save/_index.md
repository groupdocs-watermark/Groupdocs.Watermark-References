---
title: "méthode save"
second_title: "Références d'API GroupDocs.Watermark pour Python via .NET"
description: "Enregistre les données du document dans le flux sous-jacent."
type: docs
url: /fr/python-net/groupdocs.watermark/watermarker/save/
is_root: false
weight: 1130
---


## save

Enregistre les données du document dans le flux sous-jacent.

En savoir plus sur l’enregistrement des documents : https://docs.groupdocs.com/display/watermarknet/Saving+documents.

```python
def save(self):
    ...
```

### Exemple

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.search.search_criteria import TextSearchCriteria

with Watermarker(r"D:\\test.msg") as watermarker:
    criteria = TextSearchCriteria("test", False)
    watermarks = watermarker.search(criteria)
    watermarker.remove(watermarks)
    watermarker.save()
```

## save {#file_path}

Enregistre le document à l'emplacement de fichier spécifié.

En savoir plus sur l’enregistrement des documents : https://docs.groupdocs.com/display/watermarknet/Saving+documents.

```python
def save(self, file_path):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | `str` | Le chemin du fichier où enregistrer les données du document. |

### Exemple

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark, Font

def add_and_save():
    with Watermarker("input.pdf") as watermarker:
        watermark = TextWatermark("top secret", Font("Arial", 36))
        watermarker.add(watermark)
        watermarker.save("output.pdf")
```

## save {#document}

Enregistre le document dans le flux spécifié.

En savoir plus sur l’enregistrement des documents sur https://docs.groupdocs.com/display/watermarknet/Saving+documents.

```python
def save(self, document):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| document | `io.RawIOBase` | Le flux où enregistrer les données du document. |

### Exemple

```python
from io import BytesIO
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark
from groupdocs.watermark.watermarks import Font

with Watermarker("input.pdf") as watermarker:
    watermark = TextWatermark("top secret", Font("Arial", 36))
    watermarker.add(watermark)
    stream = BytesIO()
    watermarker.save(stream)
    # `stream` contient maintenant les octets PDF enregistrés
```

## save {#options}

Enregistre les données du document dans le flux sous-jacent en utilisant les options d'enregistrement.

En savoir plus sur l’enregistrement des documents.

```python
def save(self, options):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| options | `SaveOptions` | Options supplémentaires à utiliser lors de l’enregistrement d’un document. |

### Exemple

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options import SaveOptions
from groupdocs.watermark.watermarks import TextWatermark
from groupdocs.watermark.watermarks import Font

with Watermarker("input.pdf") as watermarker:
    watermark = TextWatermark("top secret", Font("Arial", 36))
    watermarker.add(watermark)
    watermarker.save(SaveOptions())
```

## save {#file_path-options}

Enregistre le document à l'emplacement de fichier spécifié en utilisant les options d'enregistrement.

En savoir plus sur l’enregistrement des documents : https://docs.groupdocs.com/display/watermarknet/Saving+documents.

```python
def save(self, file_path, options):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | `str` | Le chemin du fichier où enregistrer les données du document. |
| options | `SaveOptions` | Options supplémentaires à utiliser lors de l’enregistrement d’un document. |

### Exemple

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.watermarks import TextWatermark
from groupdocs.watermark.watermarks import Font
from groupdocs.watermark.options import SaveOptions

with Watermarker("input.pdf") as watermarker:
    watermark = TextWatermark("top secret", Font("Arial", 36))
    watermarker.add(watermark)
    watermarker.save("output.pdf", SaveOptions())
```

## save {#document-options}

Enregistre le document dans le flux spécifié en utilisant les options d'enregistrement.

En savoir plus sur l’enregistrement des documents dans la documentation GroupDocs.

```python
def save(self, document, options):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| document | `io.RawIOBase` | Le flux où enregistrer les données du document. |
| options | `SaveOptions` | Options supplémentaires à utiliser lors de l’enregistrement d’un document. |

### Exemple

```python
from io import BytesIO
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options import SaveOptions
from groupdocs.watermark.watermarks import TextWatermark
from groupdocs.watermark.watermarks import Font

def add_watermark_and_save():
    with Watermarker("input.pdf") as watermarker:
        watermark = TextWatermark("top secret", Font("Arial", 36))
        watermarker.add(watermark)

        stream = BytesIO()
        watermarker.save(stream, SaveOptions())
        # Le flux contient maintenant les données PDF enregistrées
        # par ex., écrire dans un fichier
        with open("output.pdf", "wb") as f:
            f.write(stream.getvalue())

if __name__ == "__main__":
    add_watermark_and_save()
```

### Voir aussi
* class [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/)
