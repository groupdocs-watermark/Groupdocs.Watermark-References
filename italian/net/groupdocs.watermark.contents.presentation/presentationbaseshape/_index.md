---
title: "PresentationBaseShape"
second_title: "GroupDocs.Watermark per .NET Riferimento API"
description: "Fornisce la classe base astratta per le forme di tutti i tipi in un documento PowerPoint."
type: docs
weight: 860
url: /it/net/groupdocs.watermark.contents.presentation/presentationbaseshape/
---
## PresentationBaseShape class

Fornisce la classe base astratta per le forme di tutti i tipi in un documento PowerPoint.

```csharp
public abstract class PresentationBaseShape : ShapeSearchAdapter, IPresentationHyperlinkContainer, 
    ITwoDObject
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AlternativeText](../../groupdocs.watermark.contents.presentation/presentationbaseshape/alternativetext) { get; set; } | Ottiene o imposta il testo descrittivo (alternativo) associato a questo [`PresentationBaseShape`](../presentationbaseshape). |
| [Height](../../groupdocs.watermark.contents.presentation/presentationbaseshape/height) { get; set; } | Ottiene o imposta l'altezza di questo [`PresentationBaseShape`](../presentationbaseshape) in punti. |
| [Id](../../groupdocs.watermark.contents.presentation/presentationbaseshape/id) { get; } | Ottiene l'identificatore di questo [`PresentationBaseShape`](../presentationbaseshape). |
| [ImageFillFormat](../../groupdocs.watermark.contents.presentation/presentationbaseshape/imagefillformat) { get; } | Ottiene le impostazioni del formato di riempimento immagine di questo [`PresentationBaseShape`](../presentationbaseshape). |
| [Name](../../groupdocs.watermark.contents.presentation/presentationbaseshape/name) { get; } | Ottiene il nome di questo [`PresentationBaseShape`](../presentationbaseshape). |
| [Presentation](../../groupdocs.watermark.contents.presentation/presentationbaseshape/presentation) { get; } | Ottiene la presentazione genitore di questo [`PresentationBaseShape`](../presentationbaseshape). |
| [Width](../../groupdocs.watermark.contents.presentation/presentationbaseshape/width) { get; set; } | Ottiene o imposta la larghezza di questo [`PresentationBaseShape`](../presentationbaseshape) in punti. |
| [X](../../groupdocs.watermark.contents.presentation/presentationbaseshape/x) { get; set; } | Ottiene o imposta lo spostamento orizzontale di questo [`PresentationBaseShape`](../presentationbaseshape) dal bordo sinistro della presentazione in punti. |
| [Y](../../groupdocs.watermark.contents.presentation/presentationbaseshape/y) { get; set; } | Ottiene o imposta lo spostamento verticale di questo [`PresentationBaseShape`](../presentationbaseshape) dal bordo superiore della presentazione in punti. |
| [ZOrderPosition](../../groupdocs.watermark.contents.presentation/presentationbaseshape/zorderposition) { get; } | Ottiene la posizione di questo [`PresentationBaseShape`](../presentationbaseshape) nell'ordine z. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [GetHyperlink](../../groupdocs.watermark.contents.presentation/presentationbaseshape/gethyperlink)(PresentationHyperlinkActionType) | Ottiene il collegamento ipertestuale associato a questo [`PresentationBaseShape`](../presentationbaseshape). |
| [SetHyperlink](../../groupdocs.watermark.contents.presentation/presentationbaseshape/sethyperlink)(PresentationHyperlinkActionType, string) | Imposta il collegamento ipertestuale associato a questo [`PresentationBaseShape`](../presentationbaseshape). |

### Vedi anche

* class [ShapeSearchAdapter](../../groupdocs.watermark.search/shapesearchadapter)
* interface [IPresentationHyperlinkContainer](../ipresentationhyperlinkcontainer)
* interface [ITwoDObject](../../groupdocs.watermark.search/itwodobject)
* namespace [GroupDocs.Watermark.Contents.Presentation](../../groupdocs.watermark.contents.presentation)
* assembly [GroupDocs.Watermark](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.watermark.dll -->
