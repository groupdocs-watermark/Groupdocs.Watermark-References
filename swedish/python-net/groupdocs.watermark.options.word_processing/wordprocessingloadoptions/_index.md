---
title: "WordProcessingLoadOptions-klass"
second_title: "GroupDocs.Watermark för Python via .NET API-referenser"
description: "Representerar dokumentläsningsalternativ för ett Word-dokument."
type: docs
url: /sv/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/
is_root: false
weight: 40
---


## WordProcessingLoadOptions class

Representerar dokumentläsningsalternativ för ett Word-dokument.

WordProcessingLoadOptions-typen visar följande medlemmar:

### Konstruktörer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/__init__/) | Initierar en ny instans av [`WordProcessingLoadOptions`](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/) klassen. |
| [__init__](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/__init__/#password) | Initierar en ny instans av WordProcessingLoadOptions-klassen med ett angivet lösenord. |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [file_type](/watermark/python-net/groupdocs.watermark.options/loadoptions/file_type/) | Filens typ, som anger dess format (t.ex. docx, pdf, xlsx, osv.). (ärvd från [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [format_family](/watermark/python-net/groupdocs.watermark.options/loadoptions/format_family/) | Formatfamiljen för dokumentet, som anger dess typ (t.ex. Image, Pdf, Spreadsheet, osv.). (ärvd från [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |
| [password](/watermark/python-net/groupdocs.watermark.options/loadoptions/password/) | Lösenordet för att öppna ett krypterat dokument. (ärvd från [`LoadOptions`](/watermark/python-net/groupdocs.watermark.options/loadoptions/)) |

### Fält
| Fält | Beskrivning |
| :- | :- |
| [DEFAULT](/watermark/python-net/groupdocs.watermark.options.word_processing/wordprocessingloadoptions/default/) | Hämtar standardvärdet för klassen. |

### Exempel

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.word_processing import WordProcessingLoadOptions

def process_document():
    with Watermarker("./document.docx", WordProcessingLoadOptions()) as watermarker:
        content = watermarker.get_content()
        # utför operationer på innehållet, t.ex. skydda, avskydda, lägga till vattenmärken
        watermarker.save("./output.docx")

if __name__ == "__main__":
    process_document()
```

### Se även
* module [`groupdocs.watermark.options.word_processing`](/watermark/python-net/groupdocs.watermark.options.word_processing/)
