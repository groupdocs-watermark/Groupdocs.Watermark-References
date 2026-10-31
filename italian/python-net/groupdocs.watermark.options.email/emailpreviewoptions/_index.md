---
title: "Classe EmailPreviewOptions"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Fornisce opzioni per impostare requisiti e delegati di stream per la generazione dell'anteprima di un documento email."
type: docs
url: /it/python-net/groupdocs.watermark.options.email/emailpreviewoptions/
is_root: false
weight: 20
---


## EmailPreviewOptions class

Fornisce opzioni per impostare requisiti e delegati di stream per la generazione dell'anteprima di un documento email.

Il tipo EmailPreviewOptions espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.options.email/emailpreviewoptions/__init__/#create_page_stream) | Inizializza una nuova istanza della classe [`EmailPreviewOptions`](/watermark/python-net/groupdocs.watermark.options.email/emailpreviewoptions/) facendo chiudere lo stream di output. |
| [__init__](/watermark/python-net/groupdocs.watermark.options.email/emailpreviewoptions/__init__/#create_page_stream-release_page_stream) | Inizializza una nuova istanza della classe EmailPreviewOptions facendo restituire lo stream di output al client per un uso successivo. |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [resolution](/watermark/python-net/groupdocs.watermark.options.email/emailpreviewoptions/resolution/) | La risoluzione per le immagini generate, in punti per pollice. |
| [create_page_stream](/watermark/python-net/groupdocs.watermark.options/previewoptions/create_page_stream/) | Il delegato di creazione dello stream di pagina utilizzato per ottenere uno stream scrivibile per ogni pagina renderizzata. (eredita da [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/)) |
| [height](/watermark/python-net/groupdocs.watermark.options/previewoptions/height/) | L'altezza dell'anteprima della pagina. (eredita da [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/)) |
| [page_numbers](/watermark/python-net/groupdocs.watermark.options/previewoptions/page_numbers/) | L'array di numeri di pagina per generare le anteprime. (eredita da [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/)) |
| [preview_format](/watermark/python-net/groupdocs.watermark.options/previewoptions/preview_format/) | Il formato dell'immagine di anteprima. (eredita da [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/)) |
| [release_page_stream](/watermark/python-net/groupdocs.watermark.options/previewoptions/release_page_stream/) | Il delegato di completamento dell'anteprima della pagina. (eredita da [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/)) |
| [width](/watermark/python-net/groupdocs.watermark.options/previewoptions/width/) | La larghezza dell'anteprima della pagina. (eredita da [`PreviewOptions`](/watermark/python-net/groupdocs.watermark.options/previewoptions/)) |

### Campi
| Campo | Descrizione |
| :- | :- |
| [DEFAULT_RESOLUTION](/watermark/python-net/groupdocs.watermark.options.email/emailpreviewoptions/default_resolution/) | Risoluzione predefinita in punti per pollice. |

### Vedi anche
* module [`groupdocs.watermark.options.email`](/watermark/python-net/groupdocs.watermark.options.email/)
