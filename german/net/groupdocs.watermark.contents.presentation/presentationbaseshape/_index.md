---
title: "PresentationBaseShape"
second_title: "GroupDocs.Watermark für .NET API-Referenz"
description: "Stellt die abstrakte Basisklasse für Formen aller Typen in einem PowerPoint-Dokument bereit."
type: docs
weight: 860
url: /de/net/groupdocs.watermark.contents.presentation/presentationbaseshape/
---
## PresentationBaseShape class

Stellt die abstrakte Basisklasse für Formen aller Typen in einem PowerPoint-Dokument bereit.

```csharp
public abstract class PresentationBaseShape : ShapeSearchAdapter, IPresentationHyperlinkContainer, 
    ITwoDObject
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AlternativeText](../../groupdocs.watermark.contents.presentation/presentationbaseshape/alternativetext) { get; set; } | Ermittelt oder legt den beschreibenden (alternativen) Text fest, der mit diesem [`PresentationBaseShape`](../presentationbaseshape) verknüpft ist. |
| [Height](../../groupdocs.watermark.contents.presentation/presentationbaseshape/height) { get; set; } | Ermittelt oder legt die Höhe dieses [`PresentationBaseShape`](../presentationbaseshape) in Punkten fest. |
| [Id](../../groupdocs.watermark.contents.presentation/presentationbaseshape/id) { get; } | Ermittelt den Bezeichner dieses [`PresentationBaseShape`](../presentationbaseshape). |
| [ImageFillFormat](../../groupdocs.watermark.contents.presentation/presentationbaseshape/imagefillformat) { get; } | Ermittelt die Einstellungen des Bildfüllformats dieses [`PresentationBaseShape`](../presentationbaseshape). |
| [Name](../../groupdocs.watermark.contents.presentation/presentationbaseshape/name) { get; } | Ermittelt den Namen dieses [`PresentationBaseShape`](../presentationbaseshape). |
| [Presentation](../../groupdocs.watermark.contents.presentation/presentationbaseshape/presentation) { get; } | Ermittelt die übergeordnete Präsentation dieses [`PresentationBaseShape`](../presentationbaseshape). |
| [Width](../../groupdocs.watermark.contents.presentation/presentationbaseshape/width) { get; set; } | Liest oder legt die Breite dieses [`PresentationBaseShape`](../presentationbaseshape) in Punkten fest. |
| [X](../../groupdocs.watermark.contents.presentation/presentationbaseshape/x) { get; set; } | Liest oder legt den horizontalen Versatz dieses [`PresentationBaseShape`](../presentationbaseshape) von der linken Präsentationskante in Punkten fest. |
| [Y](../../groupdocs.watermark.contents.presentation/presentationbaseshape/y) { get; set; } | Liest oder legt den vertikalen Versatz dieses [`PresentationBaseShape`](../presentationbaseshape) von der oberen Präsentationskante in Punkten fest. |
| [ZOrderPosition](../../groupdocs.watermark.contents.presentation/presentationbaseshape/zorderposition) { get; } | Liest die Position dieses [`PresentationBaseShape`](../presentationbaseshape) in der Z-Reihenfolge. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [GetHyperlink](../../groupdocs.watermark.contents.presentation/presentationbaseshape/gethyperlink)(PresentationHyperlinkActionType) | Liest den Hyperlink, der mit diesem [`PresentationBaseShape`](../presentationbaseshape) verknüpft ist. |
| [SetHyperlink](../../groupdocs.watermark.contents.presentation/presentationbaseshape/sethyperlink)(PresentationHyperlinkActionType, string) | Setzt den Hyperlink, der mit diesem [`PresentationBaseShape`](../presentationbaseshape) verknüpft ist. |

### Siehe auch

* class [ShapeSearchAdapter](../../groupdocs.watermark.search/shapesearchadapter)
* interface [IPresentationHyperlinkContainer](../ipresentationhyperlinkcontainer)
* interface [ITwoDObject](../../groupdocs.watermark.search/itwodobject)
* namespace [GroupDocs.Watermark.Contents.Presentation](../../groupdocs.watermark.contents.presentation)
* assembly [GroupDocs.Watermark](../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.watermark.dll -->
