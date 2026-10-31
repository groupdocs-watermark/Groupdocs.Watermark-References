---
title: "WordProcessingWatermarkableImage classe"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Rappresenta un'immagine all'interno di un documento Word."
type: docs
url: /it/python-net/groupdocs.watermark.contents.word_processing/wordprocessingwatermarkableimage/
is_root: false
weight: 190
---


## WordProcessingWatermarkableImage class

Rappresenta un'immagine all'interno di un documento Word.

Il tipo WordProcessingWatermarkableImage espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingwatermarkableimage/__init__/#image_data) | Inizializza una nuova istanza della classe [`WordProcessingWatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.word_processing/wordprocessingwatermarkableimage/) utilizzando i dati immagine specificati. |

### Metodi
| Metodo | Descrizione |
| :- | :- |
| [add](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/add/) | Aggiunge una filigrana a questo [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/). Questo metodo presume che l'offset e le dimensioni della filigrana siano misurati in pixel (se sono assegnati). (eredita da [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/)) |
| [add_watermark](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/add_watermark/) | (eredita da [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/)) |
| [find_images](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images/) | Trova le immagini in base ai criteri di ricerca specificati. La ricerca viene eseguita negli oggetti specificati in [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). (eredita da [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [find_images_image_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/find_images_image_search_criteria/) | (eredita da [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [get_bytes](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/get_bytes/) | Ottiene l'immagine come array di byte. (eredita da [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/)) |
| [search](/watermark/python-net/groupdocs.watermark.contents/contentpart/search/) | Trova i possibili watermark in base ai criteri di ricerca specificati. La ricerca viene eseguita sugli oggetti elencati in [`Watermarker.SearchableObjects`](/watermark/python-net/groupdocs.watermark.search.objects/searchableobjects/). (eredita da [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |
| [search_search_criteria](/watermark/python-net/groupdocs.watermark.contents/contentpart/search_search_criteria/) | (eredita da [`ContentPart`](/watermark/python-net/groupdocs.watermark.contents/contentpart/)) |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [height](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/height/) | L'altezza di questo [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/) in pixel. (eredita da [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/)) |
| [width](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/width/) | La larghezza di questo WatermarkableImage in pixel. (eredita da [`WatermarkableImage`](/watermark/python-net/groupdocs.watermark.contents.image/watermarkableimage/)) |

### Esempio

```python
import groupdocs.watermark as gw
import groupdocs.watermark.contents.word_processing as gwc_wp

with open("test.png", "rb") as f:
    img_bytes = f.read()
image = gwc_wp.WordProcessingWatermarkableImage(img_bytes)
```

### Vedi anche
* module [`groupdocs.watermark.contents.word_processing`](/watermark/python-net/groupdocs.watermark.contents.word_processing/)
