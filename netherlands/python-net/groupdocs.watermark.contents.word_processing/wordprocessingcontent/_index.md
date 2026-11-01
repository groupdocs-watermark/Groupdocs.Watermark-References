---
title: "WordProcessingContent klasse"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Stelt een Word-document (doc, docx, enz.) voor waar een watermerk kan worden geplaatst."
type: docs
url: /nl/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/
is_root: false
weight: 10
---


## WordProcessingContent class

Stelt een Word-document (doc, docx, enz.) voor waar een watermerk kan worden geplaatst.

Meer informatie:
- Add watermarks to word processing documents: https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+word+processing+documents
- Existing objects in word processing document: https://docs.groupdocs.com/display/watermarknet/Existing+objects+in+word+processing+document
- Locking watermark in word processing document: https://docs.groupdocs.com/display/watermarknet/Locking+watermark+in+word+processing+document
- Protecting word processing documents: https://docs.groupdocs.com/display/watermarknet/Protecting+word+processing+documents
- Watermarks in word processing document: https://docs.groupdocs.com/display/watermarknet/Watermarks+in+word+processing+document

Het WordProcessingContent-type geeft de volgende leden weer:

### Methoden
| Methode | Beschrijving |
| :- | :- |
| [decrypt](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/decrypt/) | Ontsleutelt het document. |
| [encrypt](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/encrypt/#password) | Versleutelt het document. |
| [encrypt_file](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/encrypt_file/) |  |
| [encrypt_string](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/encrypt_string/) |  |
| [protect](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/protect/#protection_type-password) | Beschermt het document tegen wijzigingen en stelt een beschermingswachtwoord in. |
| [protect_file](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/protect_file/) |  |
| [protect_string](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/protect_string/) |  |
| [protect_word_processing_protection_type](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/protect_word_processing_protection_type/) |  |
| [unprotect](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/unprotect/) | Verwijdert de bescherming van het document, ongeacht het wachtwoord. |
| [dispose](/watermark/python-net/groupdocs.watermark.contents/content/dispose/) | Verwijdert de huidige instantie. (geërfd van [`Content`](/watermark/python-net/groupdocs.watermark.contents/content/)) |
| [find_images](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images/) | Zoekt afbeeldingen volgens de opgegeven zoekcriteria. De zoekopdracht wordt uitgevoerd in de objecten die zijn gespecificeerd in [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). (geërfd van [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [find_images_image_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images_image_search_criteria/) | (geërfd van [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [search](/watermark/python-net/groupdocs.watermark.contents/contentpart/search/) | Zoekt mogelijke watermerken volgens de opgegeven zoekcriteria. De zoekopdracht wordt uitgevoerd op de objecten die zijn vermeld in [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). (geërfd van [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [search_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/search_search_criteria/) | (geërfd van [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [page_count](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/page_count/) | Het aantal pagina's in het document. |
| [sections](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/sections/) | De verzameling van alle secties van deze [`WordProcessingContent`](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingcontent/). |

### Voorbeeld

```python
from groupdocs.watermark import Watermarker
from groupdocs.watermark.options.word_processing import WordProcessingLoadOptions

load_options = WordProcessingLoadOptions()
with Watermarker("input.docx", load_options) as watermarker:
    # Voeg hier een watermerk toe aan een specifieke of alle secties indien nodig.
    watermarker.save("output.docx")
```

### Zie ook
* module [`groupdocs.watermark.contents.word_processing`](/watermark/python-net/groupdocs.watermark.contents.word_processing/)
