---
title: "PresentationBaseShape"
second_title: "GroupDocs.Watermark för .NET API-referens"
description: "Tillhandahåller den abstrakta basklassen för former av alla typer i ett PowerPoint-dokument."
type: docs
weight: 860
url: /sv/net/groupdocs.watermark.contents.presentation/presentationbaseshape/
---
## PresentationBaseShape class

Tillhandahåller den abstrakta basklassen för former av alla typer i ett PowerPoint-dokument.

```csharp
public abstract class PresentationBaseShape : ShapeSearchAdapter, IPresentationHyperlinkContainer, 
    ITwoDObject
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AlternativeText](../../groupdocs.watermark.contents.presentation/presentationbaseshape/alternativetext) { get; set; } | Hämtar eller anger den beskrivande (alternativa) texten som är associerad med detta [`PresentationBaseShape`](../presentationbaseshape). |
| [Height](../../groupdocs.watermark.contents.presentation/presentationbaseshape/height) { get; set; } | Hämtar eller anger höjden på detta [`PresentationBaseShape`](../presentationbaseshape) i punkter. |
| [Id](../../groupdocs.watermark.contents.presentation/presentationbaseshape/id) { get; } | Hämtar identifieraren för detta [`PresentationBaseShape`](../presentationbaseshape). |
| [ImageFillFormat](../../groupdocs.watermark.contents.presentation/presentationbaseshape/imagefillformat) { get; } | Hämtar bildfyllnadsformatinställningarna för detta [`PresentationBaseShape`](../presentationbaseshape). |
| [Name](../../groupdocs.watermark.contents.presentation/presentationbaseshape/name) { get; } | Hämtar namnet på detta [`PresentationBaseShape`](../presentationbaseshape). |
| [Presentation](../../groupdocs.watermark.contents.presentation/presentationbaseshape/presentation) { get; } | Hämtar den överordnade presentationen för detta [`PresentationBaseShape`](../presentationbaseshape). |
| [Width](../../groupdocs.watermark.contents.presentation/presentationbaseshape/width) { get; set; } | Hämtar eller anger bredden på detta [`PresentationBaseShape`](../presentationbaseshape) i punkter. |
| [X](../../groupdocs.watermark.contents.presentation/presentationbaseshape/x) { get; set; } | Hämtar eller anger det horisontella offsetet för detta [`PresentationBaseShape`](../presentationbaseshape) från presentationens vänstra kant i punkter. |
| [Y](../../groupdocs.watermark.contents.presentation/presentationbaseshape/y) { get; set; } | Hämtar eller anger det vertikala offsetet för detta [`PresentationBaseShape`](../presentationbaseshape) från presentationens övre kant i punkter. |
| [ZOrderPosition](../../groupdocs.watermark.contents.presentation/presentationbaseshape/zorderposition) { get; } | Hämtar positionen för detta [`PresentationBaseShape`](../presentationbaseshape) i z-ordningen. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [GetHyperlink](../../groupdocs.watermark.contents.presentation/presentationbaseshape/gethyperlink)(PresentationHyperlinkActionType) | Hämtar hyperlänken som är associerad med detta [`PresentationBaseShape`](../presentationbaseshape). |
| [SetHyperlink](../../groupdocs.watermark.contents.presentation/presentationbaseshape/sethyperlink)(PresentationHyperlinkActionType, string) | Ställer in hyperlänken som är associerad med detta [`PresentationBaseShape`](../presentationbaseshape). |

### Se även

* class [ShapeSearchAdapter](../../groupdocs.watermark.search/shapesearchadapter)
* interface [IPresentationHyperlinkContainer](../ipresentationhyperlinkcontainer)
* interface [ITwoDObject](../../groupdocs.watermark.search/itwodobject)
* namespace [GroupDocs.Watermark.Contents.Presentation](../../groupdocs.watermark.contents.presentation)
* assembly [GroupDocs.Watermark](../../)

<!-- FÅR INTE REDIGERAS: genererad av xmldocmd för GroupDocs.watermark.dll -->
