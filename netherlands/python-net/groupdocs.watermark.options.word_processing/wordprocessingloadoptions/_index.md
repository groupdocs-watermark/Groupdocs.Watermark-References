---
title: "WordProcessingLoadOptions klasse"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Stelt documentlaadopties voor een Word-document voor."
type: docs
url: /nl/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/
is_root: false
weight: 40
---


## WordProcessingLoadOptions class

Stelt documentlaadopties voor een Word-document voor.

Het WordProcessingLoadOptions type bevat de volgende leden:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/__init__/) | Initialiseert een nieuw exemplaar van de [`WordProcessingLoadOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/) klasse. |
| [__init__](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/__init__/#password) | Initialiseert een nieuw exemplaar van de WordProcessingLoadOptions klasse met een opgegeven wachtwoord. |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [file_type](/watermark/python-net/groupdocs.watermark.options/loadoptions/file_type/) | Het type van het bestand, dat het formaat aangeeft (bijv. docx, pdf, xlsx, enz.). (geërfd van [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [format_family](/watermark/python-net/groupdocs.watermark.options/loadoptions/format_family/) | De formaatfamilie van het document, die het type aangeeft (bijv. Image, Pdf, Spreadsheet, enz.). (geërfd van [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [password](/watermark/python-net/groupdocs.watermark.options/loadoptions/password/) | Het wachtwoord voor het openen van een versleuteld document. (geërfd van [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |

### Velden
| Veld | Beschrijving |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/default/) | Haalt de standaardwaarde op voor de klasse. |

### Voorbeeld

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.word_processing import WordProcessingLoadOptions

def process_document():
    with Watermarker("./document.docx", WordProcessingLoadOptions()) as watermarker:
        content = watermarker.get_content()
        # voert bewerkingen uit op de inhoud, bijv., beschermen, ontbeschermen, watermerken toevoegen
        watermarker.save("./output.docx")

if __name__ == "__main__":
    process_document()
```

### Zie ook
* module [`groupdocs.watermark.options.word_processing`](/watermark/python-net/groupdocs.watermark.options.word_processing/)
