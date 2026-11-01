---
title: "SpreadsheetContent‑klasse"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Stelt een Excel-document voor waarin een watermerk kan worden geplaatst."
type: docs
url: /nl/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetcontent/
is_root: false
weight: 80
---


## SpreadsheetContent class

Stelt een Excel-document voor waarin een watermerk kan worden geplaatst.

Meer informatie:
- https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+spreadsheet+documents
- https://docs.groupdocs.com/display/watermarknet/Shapes+in+spreadsheet+document
- https://docs.groupdocs.com/display/watermarknet/Working+with+spreadsheet+document+attachments
- https://docs.groupdocs.com/display/watermarknet/Working+with+worksheet+backgrounds
- https://docs.groupdocs.com/display/watermarknet/Working+with+worksheet+headers+and+footers

Het type SpreadsheetContent exposeert de volgende leden:

### Methoden
| Methode | Beschrijving |
| :- | :- |
| [decrypt](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetcontent/decrypt/) | Ontsleutelt het document. |
| [encrypt](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetcontent/encrypt/#password) | Versleutelt de inhoud. |
| [encrypt_file](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetcontent/encrypt_file/) |  |
| [encrypt_string](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetcontent/encrypt_string/) |  |
| [dispose](/watermark/python-net/groupdocs.watermark.contents/content/dispose/) | Verwijdert de huidige instantie. (geërfd van [`Content`](/watermark/python-net/groupdocs.watermark.contents/content/)) |
| [find_images](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images/) | Zoekt afbeeldingen volgens de opgegeven zoekcriteria. De zoekopdracht wordt uitgevoerd in de objecten die zijn gespecificeerd in [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). (geërfd van [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [find_images_image_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images_image_search_criteria/) | (geërfd van [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [search](/watermark/python-net/groupdocs.watermark.contents/contentpart/search/) | Zoekt mogelijke watermerken volgens de opgegeven zoekcriteria. De zoekopdracht wordt uitgevoerd op de objecten die zijn vermeld in [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). (geërfd van [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [search_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/search_search_criteria/) | (geërfd van [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [worksheets](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetcontent/worksheets/) | De collectie van alle werkbladen van deze [`SpreadsheetContent`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/spreadsheetcontent/). |

### Voorbeeld

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.spreadsheet import SpreadsheetLoadOptions

load_options = SpreadsheetLoadOptions()
with Watermarker(r"D:\input.xls", load_options) as watermarker:
    # Gebruik de add‑methode om een watermerk toe te voegen aan een specifiek of alle werkbladen.
    watermarker.save(r"D:\output.xls")
```

### Zie ook
* module [`groupdocs.watermark.contents.spreadsheet`](/watermark/python-net/groupdocs.watermark.contents.spreadsheet/)
