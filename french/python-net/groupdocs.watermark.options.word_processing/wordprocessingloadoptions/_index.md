---
title: "Classe WordProcessingLoadOptions"
second_title: "Références d'API GroupDocs.Watermark pour Python via .NET"
description: "Représente les options de chargement du document pour un document Word."
type: docs
url: /fr/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/
is_root: false
weight: 40
---


## WordProcessingLoadOptions class

Représente les options de chargement du document pour un document Word.

Le type WordProcessingLoadOptions expose les membres suivants :

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/__init__/) | Initialise une nouvelle instance de la classe [`WordProcessingLoadOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/). |
| [__init__](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/__init__/#password) | Initialise une nouvelle instance de la classe WordProcessingLoadOptions avec un mot de passe spécifié. |

### Propriétés
| Propriété | Description |
| :- | :- |
| [file_type](/watermark/python-net/groupdocs.watermark.options/loadoptions/file_type/) | Le type du fichier, indiquant son format (p. ex., docx, pdf, xlsx, etc.). (hérité de [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [format_family](/watermark/python-net/groupdocs.watermark.options/loadoptions/format_family/) | La famille de format du document, indiquant son type (p. ex., Image, Pdf, Spreadsheet, etc.). (hérité de [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [password](/watermark/python-net/groupdocs.watermark.options/loadoptions/password/) | Le mot de passe pour ouvrir un document chiffré. (hérité de [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |

### Champs
| Champ | Description |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/default/) | Obtient la valeur par défaut pour la classe. |

### Exemple

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.word_processing import WordProcessingLoadOptions

def process_document():
    with Watermarker("./document.docx", WordProcessingLoadOptions()) as watermarker:
        content = watermarker.get_content()
        # effectuer des opérations sur le contenu, p. ex., protéger, déprotéger, ajouter des filigranes
        watermarker.save("./output.docx")

if __name__ == "__main__":
    process_document()
```

### Voir aussi
* module [`groupdocs.watermark.options.word_processing`](/watermark/python-net/groupdocs.watermark.options.word_processing/)
