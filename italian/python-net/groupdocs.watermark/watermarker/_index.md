---
title: "Classe Watermarker"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Rappresenta una classe per la gestione delle filigrane in un documento."
type: docs
url: /it/python-net/groupdocs.watermark/watermarker/
is_root: false
weight: 60
---


## Watermarker class

Rappresenta una classe per la gestione delle filigrane in un documento.

Carica e salva il contenuto di qualsiasi formato supportato.

Il tipo Watermarker espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark/watermarker/__init__/#file_path) | Inizializza una nuova istanza di Watermarker con il percorso del documento specificato. |
| [__init__](/watermark/python-net/groupdocs.watermark/watermarker/__init__/#file_path-options) | Inizializza una nuova istanza di Watermarker con il percorso del documento specificato e le opzioni di caricamento. |
| [__init__](/watermark/python-net/groupdocs.watermark/watermarker/__init__/#file_path-settings) | Inizializza un Watermarker con il percorso del documento specificato e le impostazioni. |
| [__init__](/watermark/python-net/groupdocs.watermark/watermarker/__init__/#file_path-options-settings) | Inizializza una nuova istanza di Watermarker con il percorso del documento specificato, le opzioni di caricamento e le impostazioni. |
| [__init__](/watermark/python-net/groupdocs.watermark/watermarker/__init__/#document) | Inizializza una nuova istanza della classe Watermarker con lo stream specificato. |
| [__init__](/watermark/python-net/groupdocs.watermark/watermarker/__init__/#document-options) | Inizializza una nuova istanza di Watermarker con lo stream specificato e le opzioni di caricamento. |
| [__init__](/watermark/python-net/groupdocs.watermark/watermarker/__init__/#document-settings) | Inizializza una nuova istanza di Watermarker con lo stream specificato e le impostazioni. |
| [__init__](/watermark/python-net/groupdocs.watermark/watermarker/__init__/#document-options-settings) | Inizializza una nuova istanza della classe [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/) con lo stream specificato, le opzioni di caricamento e le impostazioni. |

### Metodi
| Metodo | Descrizione |
| :- | :- |
| [add](/watermark/python-net/groupdocs.watermark/watermarker/add/#watermark) | Aggiunge una filigrana al documento caricato. |
| [add](/watermark/python-net/groupdocs.watermark/watermarker/add/#watermark-options) | Aggiunge una filigrana al documento caricato utilizzando le opzioni di filigrana. |
| [add_watermark](/watermark/python-net/groupdocs.watermark/watermarker/add_watermark/) |  |
| [dispose](/watermark/python-net/groupdocs.watermark/watermarker/dispose/) | Elimina l'istanza corrente. |
| [generate_preview](/watermark/python-net/groupdocs.watermark/watermarker/generate_preview/#preview_options) | Genera immagini di anteprima per il documento. |
| [generate_preview_preview_options](/watermark/python-net/groupdocs.watermark/watermarker/generate_preview_preview_options/) |  |
| [get_content](/watermark/python-net/groupdocs.watermark/watermarker/get_content/) |  |
| [get_document_info](/watermark/python-net/groupdocs.watermark/watermarker/get_document_info/) | Ottiene le informazioni sul formato del documento caricato. |
| [get_images](/watermark/python-net/groupdocs.watermark/watermarker/get_images/#search_criteria) | Trova le immagini secondo i criteri di ricerca specificati. |
| [get_images](/watermark/python-net/groupdocs.watermark/watermarker/get_images/) | Trova tutte le immagini nel documento. |
| [get_images_image_search_criteria](/watermark/python-net/groupdocs.watermark/watermarker/get_images_image_search_criteria/) |  |
| [remove](/watermark/python-net/groupdocs.watermark/watermarker/remove/#possible_watermark) | Rimuove una filigrana dal documento. |
| [remove](/watermark/python-net/groupdocs.watermark/watermarker/remove/#possible_watermarks) | Rimuove tutte le filigrane nella collezione dal documento. |
| [remove_possible_watermark](/watermark/python-net/groupdocs.watermark/watermarker/remove_possible_watermark/) |  |
| [remove_possible_watermark_collection](/watermark/python-net/groupdocs.watermark/watermarker/remove_possible_watermark_collection/) |  |
| [save](/watermark/python-net/groupdocs.watermark/watermarker/save/) | Salva i dati del documento nello stream sottostante. |
| [save](/watermark/python-net/groupdocs.watermark/watermarker/save/#file_path) | Salva il documento nella posizione file specificata. |
| [save](/watermark/python-net/groupdocs.watermark/watermarker/save/#document) | Salva il documento nello stream specificato. |
| [save](/watermark/python-net/groupdocs.watermark/watermarker/save/#options) | Salva i dati del documento nello stream sottostante usando le opzioni di salvataggio. |
| [save](/watermark/python-net/groupdocs.watermark/watermarker/save/#file_path-options) | Salva il documento nella posizione file specificata usando le opzioni di salvataggio. |
| [save](/watermark/python-net/groupdocs.watermark/watermarker/save/#document-options) | Salva il documento nello stream specificato usando le opzioni di salvataggio. |
| [save_file](/watermark/python-net/groupdocs.watermark/watermarker/save_file/) |  |
| [save_save_options](/watermark/python-net/groupdocs.watermark/watermarker/save_save_options/) |  |
| [save_stream](/watermark/python-net/groupdocs.watermark/watermarker/save_stream/) |  |
| [save_streams](/watermark/python-net/groupdocs.watermark/watermarker/save_streams/) |  |
| [save_string](/watermark/python-net/groupdocs.watermark/watermarker/save_string/) |  |
| [search](/watermark/python-net/groupdocs.watermark/watermarker/search/) | Cerca tutte le possibili filigrane nel documento. |
| [search](/watermark/python-net/groupdocs.watermark/watermarker/search/#search_criteria) | Cerca le possibili filigrane secondo i criteri di ricerca specificati. |
| [search_search_criteria](/watermark/python-net/groupdocs.watermark/watermarker/search_search_criteria/) |  |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [searchable_objects](/watermark/python-net/groupdocs.watermark/watermarker/searchable_objects/) | Gli oggetti da includere in una ricerca di filigrane. |

### Esempio

```python
from groupdocs.watermark import Watermarker

with Watermarker("D:\\input.pdf") as watermarker:
    # Usa i metodi di Watermarker per aggiungere, cercare o rimuovere le filigrane.
    watermarker.save("D:\\output.pdf")
```

### Guides
Guide operative che utilizzano `Watermarker`:

* [Hello, World!](/watermark/python-net/guides/hello-world/)
* [Add text watermarks](/watermark/python-net/guides/add-text/)
* [Add image watermarks](/watermark/python-net/guides/add-image/)
* [Customize watermarks](/watermark/python-net/guides/customize/)
* [Adding repeated watermarks](/watermark/python-net/guides/adding-repeated-watermarks/)
* [Searching watermarks](/watermark/python-net/guides/searching-watermarks/)
* [Update watermarks](/watermark/python-net/guides/update/)
* [Clear watermarks](/watermark/python-net/guides/clear/)
* [Document preview](/watermark/python-net/guides/preview/)
* [Get document info](/watermark/python-net/guides/get-document-info/)

### Vedi anche
* module [`groupdocs.watermark`](/watermark/python-net/groupdocs.watermark/)
