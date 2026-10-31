---
title: "classe ImageInpaintingPossibleWatermark"
second_title: "Riferimenti API di GroupDocs.Watermark per Python via .NET"
description: "Rappresenta una regione immagine specificata manualmente che dovrebbe essere ricostruita (riempita usando i pixel circostanti)."
type: docs
url: /it/python-net/groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/
is_root: false
weight: 110
---


## ImageInpaintingPossibleWatermark class

Rappresenta una regione immagine specificata manualmente che dovrebbe essere ricostruita (riempita usando i pixel circostanti).

Il tipo ImageInpaintingPossibleWatermark espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/watermark/python-net/groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/__init__/) | Inizializza una nuova istanza di ImageInpaintingPossibleWatermark. |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [method](/watermark/python-net/groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/method/) | L'algoritmo di inpainting usato per il rilevamento di possibili filigrane. Il valore predefinito è `InpaintingMethod.patch_based`. |
| [parent](/watermark/python-net/groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/parent/) | Il genitore di questo ImageInpaintingPossibleWatermark. Restituisce sempre None perché la regione è specificata manualmente. |
| [patch_size](/watermark/python-net/groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/patch_size/) | La dimensione del patch usata dall'algoritmo (dispari, 5-11). |
| [polygons](/watermark/python-net/groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/polygons/) | Le regioni poligonali da inpaintare, espresse come una lista di poligoni dove ogni poligono è una lista di vertici in pixel dell'immagine. |
| [rectangles](/watermark/python-net/groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/rectangles/) | Le aree rettangolari da inpaintare, in pixel dell'immagine. |
| [formatted_text_fragments](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/formatted_text_fragments/) | La raccolta di frammenti di testo formattato di questo [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/). (ereditato da [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/)) |
| [height](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/height/) | L'altezza di questo [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/). (ereditato da [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/)) |
| [image_data](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/image_data/) | L'immagine di questo [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/) o None se la filigrana non ha immagine. (ereditato da [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/)) |
| [page_number](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/page_number/) | Il numero di pagina in cui la filigrana è posizionata. (ereditato da [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/)) |
| [rotate_angle](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/rotate_angle/) | L'angolo di rotazione di questo [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/) in gradi. (eredita da [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/)) |
| [text](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/text/) | Il testo di questo [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/). (eredita da [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/)) |
| [unit_of_measurement](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/unit_of_measurement/) | L'unità di misura di questo [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/). (eredita da [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/)) |
| [width](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/width/) | La larghezza di questo [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/). (eredita da [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/)) |
| [x](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/x/) | La coordinata x di questo [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/). (eredita da [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/)) |
| [y](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/y/) | La coordinata y di questo [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/). (eredita da [`PossibleWatermark`](/watermark/python-net/groupdocs.watermark.search/possiblewatermark/)) |

### Vedi anche
* module [`groupdocs.watermark.search.watermarks`](/watermark/python-net/groupdocs.watermark.search.watermarks/)
