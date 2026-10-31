---
title: "Classe PdfContent"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Rappresenta un documento PDF in cui è possibile posizionare una filigrana."
type: docs
url: /it/python-net/groupdocs.watermark.contents.pdf/pdfcontent/
is_root: false
weight: 100
---


## PdfContent class

Rappresenta un documento PDF in cui è possibile posizionare una filigrana.

Per saperne di più:
- [Add watermarks to PDF documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+PDF+documents)
- [Existing objects in PDF document](https://docs.groupdocs.com/display/watermarknet/Existing+objects+in+PDF+document)
- [Rasterize document or page](https://docs.groupdocs.com/display/watermarknet/Rasterize+document+or+page)
- [Watermarks in PDF document](https://docs.groupdocs.com/display/watermarknet/Watermarks+in+PDF+document)

Il tipo PdfContent espone i seguenti membri:

### Metodi
| Metodo | Descrizione |
| :- | :- |
| [decrypt](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/decrypt/) | Decripta il contenuto. |
| [encrypt](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/encrypt/#password) | Cifra il documento usando la stessa password dell'utente e del proprietario. |
| [encrypt](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/encrypt/#user_password-owner_password-permissions-crypto_algorithm) | Cifra il contenuto. |
| [encrypt_file](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/encrypt_file/) |  |
| [encrypt_string](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/encrypt_string/) |  |
| [rasterize](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/rasterize/#horizontal_resolution-vertical_resolution-image_format) | Converte tutte le pagine del contenuto in immagini. |
| [rasterize_int32](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/rasterize_int32/) |  |
| [dispose](/watermark/python-net/groupdocs.watermark.contents/content/dispose/) | Elimina l'istanza corrente. (eredita da [`Content`](/watermark/python-net/groupdocs.watermark.contents/content/)) |
| [find_images](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images/) | Trova le immagini in base ai criteri di ricerca specificati. La ricerca viene eseguita negli oggetti specificati in [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). (eredita da [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [find_images_image_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images_image_search_criteria/) | (eredita da [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [search](/watermark/python-net/groupdocs.watermark.contents/contentpart/search/) | Trova i possibili watermark in base ai criteri di ricerca specificati. La ricerca viene eseguita sugli oggetti elencati in [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). (eredita da [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [search_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/search_search_criteria/) | (eredita da [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [attachments](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/attachments/) | La raccolta di tutti gli allegati di questo [`PdfContent`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/). |
| [page_margin_type](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/page_margin_type/) | I margini della pagina PDF da utilizzare durante l'aggiunta della filigrana. |
| [pages](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/pages/) | La raccolta di tutte le pagine di questo [`PdfContent`](/watermark/python-net/groupdocs.watermark.contents.pdf/pdfcontent/). |

### Esempio

```python
from groupdocs.watermark import Watermarker

# Carica un file PDF
watermarker = Watermarker("sample.pdf")

# Recupera l'albero del contenuto PDF
pdf_content = watermarker.get_content()

# Itera sulle pagine e stampa le loro dimensioni
for page in pdf_content.pages:
    print(page.width, page.height)
```

### Vedi anche
* module [`groupdocs.watermark.contents.pdf`](/watermark/python-net/groupdocs.watermark.contents.pdf/)
