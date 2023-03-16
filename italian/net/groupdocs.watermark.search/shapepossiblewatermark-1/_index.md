---
title: ShapePossibleWatermarkT
second_title: Riferimento API GroupDocs.Watermark per .NET
description: Rappresenta la filigrana di forma in un contenuto di qualsiasi formato supportato.
type: docs
weight: 2710
url: /it/net/groupdocs.watermark.search/shapepossiblewatermark-1/
---
## ShapePossibleWatermark&lt;T&gt; class

Rappresenta la filigrana di forma in un contenuto di qualsiasi formato supportato.

```csharp
public abstract class ShapePossibleWatermark<T> : TwoDObjectPossibleWatermark
    where T : ShapeSearchAdapter, ITwoDObject
```

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo di forma. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| override [FormattedTextFragments](../../groupdocs.watermark.search/shapepossiblewatermark-1/formattedtextfragments) { get; } | Ottiene la raccolta di frammenti di testo formattato della forma. |
| override [Height](../../groupdocs.watermark.search/twodobjectpossiblewatermark/height) { get; } | Ottiene l'altezza dell'oggetto 2D. |
| [ImageData](../../groupdocs.watermark.search/possiblewatermark/imagedata) { get; set; } | Ottiene o imposta l'immagine di this[`PossibleWatermark`](../possiblewatermark) . |
| abstract [Parent](../../groupdocs.watermark.search/possiblewatermark/parent) { get; } | Ottiene il genitore di this[`PossibleWatermark`](../possiblewatermark) . |
| override [RotateAngle](../../groupdocs.watermark.search/shapepossiblewatermark-1/rotateangle) { get; } | Ottiene l'angolo di rotazione della forma in gradi. |
| override [Text](../../groupdocs.watermark.search/shapepossiblewatermark-1/text) { get; set; } | Ottiene o imposta il testo della forma. |
| override [UnitOfMeasurement](../../groupdocs.watermark.search/twodobjectpossiblewatermark/unitofmeasurement) { get; } | Ottiene l'unità di misura dell'oggetto 2D. |
| override [Width](../../groupdocs.watermark.search/twodobjectpossiblewatermark/width) { get; } | Ottiene la larghezza dell'oggetto 2D. |
| override [X](../../groupdocs.watermark.search/twodobjectpossiblewatermark/x) { get; } | Ottiene la coordinata x dell'oggetto 2D. |
| override [Y](../../groupdocs.watermark.search/twodobjectpossiblewatermark/y) { get; } | Ottiene la coordinata y dell'oggetto 2D. |

### Guarda anche

* class [TwoDObjectPossibleWatermark](../twodobjectpossiblewatermark)
* class [ShapeSearchAdapter](../shapesearchadapter)
* interface [ITwoDObject](../itwodobject)
* spazio dei nomi [GroupDocs.Watermark.Search](../../groupdocs.watermark.search)
* assemblea [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->