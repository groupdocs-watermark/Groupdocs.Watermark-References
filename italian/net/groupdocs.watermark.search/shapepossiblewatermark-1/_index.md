---
title: "ShapePossibleWatermarkT"
second_title: "GroupDocs.Watermark per .NET Riferimento API"
description: "Rappresenta una filigrana di forma in un contenuto di qualsiasi formato supportato."
type: docs
weight: 2770
url: /it/net/groupdocs.watermark.search/shapepossiblewatermark-1/
---
## ShapePossibleWatermark&lt;T&gt; class

Rappresenta una filigrana di forma in un contenuto di qualsiasi formato supportato.

```csharp
public abstract class ShapePossibleWatermark<T> : TwoDObjectPossibleWatermark
    where T : ShapeSearchAdapter, ITwoDObject
```

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo della forma. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| override [FormattedTextFragments](../../groupdocs.watermark.search/shapepossiblewatermark-1/formattedtextfragments) { get; } | Ottiene la collezione di frammenti di testo formattati della forma. |
| override [Height](../../groupdocs.watermark.search/twodobjectpossiblewatermark/height) { get; } | Ottiene l'altezza dell'oggetto 2D. |
| [ImageData](../../groupdocs.watermark.search/possiblewatermark/imagedata) { get; set; } | Ottiene o imposta l'immagine di questo [`PossibleWatermark`](../possiblewatermark). |
| override [PageNumber](../../groupdocs.watermark.search/shapepossiblewatermark-1/pagenumber) { get; } | Ottiene la pagina su cui è posizionato il watermark. |
| abstract [Parent](../../groupdocs.watermark.search/possiblewatermark/parent) { get; } | Ottiene il genitore di questo [`PossibleWatermark`](../possiblewatermark). |
| override [RotateAngle](../../groupdocs.watermark.search/shapepossiblewatermark-1/rotateangle) { get; } | Ottiene l'angolo di rotazione della forma in gradi. |
| override [Text](../../groupdocs.watermark.search/shapepossiblewatermark-1/text) { get; set; } | Ottiene o imposta il testo della forma. |
| override [UnitOfMeasurement](../../groupdocs.watermark.search/twodobjectpossiblewatermark/unitofmeasurement) { get; } | Ottiene l'unità di misura dell'oggetto 2D. |
| override [Width](../../groupdocs.watermark.search/twodobjectpossiblewatermark/width) { get; } | Ottiene la larghezza dell'oggetto 2D. |
| override [X](../../groupdocs.watermark.search/twodobjectpossiblewatermark/x) { get; } | Ottiene la coordinata x dell'oggetto 2D. |
| override [Y](../../groupdocs.watermark.search/twodobjectpossiblewatermark/y) { get; } | Ottiene la coordinata y dell'oggetto 2D. |

### Vedi anche

* class [TwoDObjectPossibleWatermark](../twodobjectpossiblewatermark)
* class [ShapeSearchAdapter](../shapesearchadapter)
* interface [ITwoDObject](../itwodobject)
* namespace [GroupDocs.Watermark.Search](../../groupdocs.watermark.search)
* assembly [GroupDocs.Watermark](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.watermark.dll -->
