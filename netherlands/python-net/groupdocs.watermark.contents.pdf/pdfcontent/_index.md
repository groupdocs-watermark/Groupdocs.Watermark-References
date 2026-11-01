---
title: "PdfContent-klasse"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "Stelt een PDF-document voor waarin een watermerk kan worden geplaatst."
type: docs
url: /nl/python-net/groupdocs.watermark.contents.pdf/pdfcontent/
is_root: false
weight: 100
---


## PdfContent class

Stelt een PDF-document voor waarin een watermerk kan worden geplaatst.

Meer informatie:
- [Add watermarks to PDF documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+PDF+documents)
- [Existing objects in PDF document](https://docs.groupdocs.com/display/watermarknet/Existing+objects+in+PDF+document)
- [Rasterize document or page](https://docs.groupdocs.com/display/watermarknet/Rasterize+document+or+page)
- [Watermarks in PDF document](https://docs.groupdocs.com/display/watermarknet/Watermarks+in+PDF+document)

Het PdfContent-type geeft de volgende leden weer:

### Methoden
| Methode | Beschrijving |
| :- | :- |
| [decrypt](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/decrypt/) | Decodeert de inhoud. |
| [encrypt](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/encrypt/#password) | Versleutelt het document met hetzelfde wachtwoord als gebruikerswachtwoord en eigenaarwachtwoord. |
| [encrypt](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/encrypt/#user_password-owner_password-permissions-crypto_algorithm) | Versleutelt de inhoud. |
| [encrypt_file](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/encrypt_file/) |  |
| [encrypt_string](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/encrypt_string/) |  |
| [rasterize](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/rasterize/#horizontal_resolution-vertical_resolution-image_format) | Converteert alle inhoudspagina's naar afbeeldingen. |
| [rasterize_int32](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/rasterize_int32/) |  |
| [dispose](/watermark/python-net/groupdocs.watermark.contents/content/dispose/) | Verwijdert de huidige instantie. (geërfd van [`Content`](/watermark/python-net/groupdocs.watermark.contents/content/)) |
| [find_images](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images/) | Zoekt afbeeldingen volgens de opgegeven zoekcriteria. De zoekopdracht wordt uitgevoerd in de objecten die zijn gespecificeerd in [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). (geërfd van [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [find_images_image_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images_image_search_criteria/) | (geërfd van [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [search](/watermark/python-net/groupdocs.watermark.contents/contentpart/search/) | Zoekt mogelijke watermerken volgens de opgegeven zoekcriteria. De zoekopdracht wordt uitgevoerd op de objecten die zijn vermeld in [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). (geërfd van [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [search_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/search_search_criteria/) | (geërfd van [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [attachments](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/attachments/) | De verzameling van alle bijlagen van deze [`PdfContent`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/). |
| [page_margin_type](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/page_margin_type/) | De pdf-paginamarges die gebruikt worden tijdens het toevoegen van een watermerk. |
| [pages](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/pages/) | De verzameling van alle pagina's van deze [`PdfContent`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/). |

### Voorbeeld

```python
from groupdocs.watermark import Watermarker

# Laad een PDF-bestand
watermarker = Watermarker("sample.pdf")

# Haal de PDF-inhoudboom op
pdf_content = watermarker.get_content()

# Itereer over pagina's en druk hun afmetingen af
for page in pdf_content.pages:
    print(page.width, page.height)
```

### Zie ook
* module [`groupdocs.watermark.contents.pdf`](/watermark/python-net/groupdocs.watermark.contents.pdf/)
