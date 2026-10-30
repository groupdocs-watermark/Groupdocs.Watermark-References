---
title: "ImageInpaintingPossibleWatermark"
second_title: "GroupDocs.Watermark per .NET Riferimento API"
description: "Rappresenta una regione immagine specificata manualmente che dovrebbe essere riempita mediante inpainting usando i pixel circostanti."
type: docs
weight: 2900
url: /it/net/groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/
---
## ImageInpaintingPossibleWatermark class

Rappresenta una regione immagine specificata manualmente che deve essere ritoccata (riempita usando i pixel circostanti).

```csharp
public class ImageInpaintingPossibleWatermark : PossibleWatermark
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [ImageInpaintingPossibleWatermark](imageinpaintingpossiblewatermark)() | Inizializza una nuova istanza della classe [`ImageInpaintingPossibleWatermark`](../imageinpaintingpossiblewatermark). |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| virtual [FormattedTextFragments](../../groupdocs.watermark.search/possiblewatermark/formattedtextfragments) { get; } | Ottiene la collezione di frammenti di testo formattati di questo [`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark). |
| virtual [Height](../../groupdocs.watermark.search/possiblewatermark/height) { get; } | Ottiene l'altezza di questo [`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark). |
| [ImageData](../../groupdocs.watermark.search/possiblewatermark/imagedata) { get; set; } | Ottiene o imposta l'immagine di questo [`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark). |
| [Method](../../groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/method) { get; set; } | Ottiene o imposta l'algoritmo di inpainting. Il valore predefinito è PatchBased. |
| virtual [PageNumber](../../groupdocs.watermark.search/possiblewatermark/pagenumber) { get; } | Ottiene la pagina su cui è posizionato il watermark. |
| override [Parent](../../groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/parent) { get; } | Restituisce il genitore di questo [`ImageInpaintingPossibleWatermark`](../imageinpaintingpossiblewatermark). Restituisce sempre `null` perché la regione è specificata manualmente. |
| [PatchSize](../../groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/patchsize) { get; set; } | Ottiene o imposta la dimensione del patch utilizzata dall'algoritmo (dispari, 5-11). Il valore predefinito è 7. Per Telea questo è usato come HalfPatchSize. |
| [Polygons](../../groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/polygons) { get; set; } | Ottiene o imposta le regioni poligonali da inpaintare, in pixel immagine. Ogni poligono è un array di vertici. È necessario specificare o [`Rectangles`](./rectangles) o [`Polygons`](./polygons), ma non entrambi. |
| [Rectangles](../../groupdocs.watermark.search.watermarks/imageinpaintingpossiblewatermark/rectangles) { get; set; } | Ottiene o imposta le aree rettangolari da inpaintare, in pixel immagine. È necessario specificare o [`Rectangles`](./rectangles) o [`Polygons`](./polygons), ma non entrambi. |
| virtual [RotateAngle](../../groupdocs.watermark.search/possiblewatermark/rotateangle) { get; } | Ottiene l'angolo di rotazione di questo [`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark) in gradi. |
| virtual [Text](../../groupdocs.watermark.search/possiblewatermark/text) { get; set; } | Ottiene o imposta il testo di questo [`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark). |
| virtual [UnitOfMeasurement](../../groupdocs.watermark.search/possiblewatermark/unitofmeasurement) { get; } | Ottiene l'unità di misura di questo [`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark). |
| virtual [Width](../../groupdocs.watermark.search/possiblewatermark/width) { get; } | Ottiene la larghezza di questo [`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark). |
| virtual [X](../../groupdocs.watermark.search/possiblewatermark/x) { get; } | Ottiene la coordinata x di questo [`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark). |
| virtual [Y](../../groupdocs.watermark.search/possiblewatermark/y) { get; } | Ottiene la coordinata y di questo [`PossibleWatermark`](../../groupdocs.watermark.search/possiblewatermark). |

### Vedi anche

* class [PossibleWatermark](../../groupdocs.watermark.search/possiblewatermark)
* namespace [GroupDocs.Watermark.Search.Watermarks](../../groupdocs.watermark.search.watermarks)
* assembly [GroupDocs.Watermark](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.watermark.dll -->
