---
title: "PresentationBaseSlide"
second_title: "GroupDocs.Watermark für .NET API-Referenz"
description: "Stellt die abstrakte Basisklasse für Folien aller Typen in einem PowerPoint-Dokument bereit."
type: docs
weight: 870
url: /de/net/groupdocs.watermark.contents.presentation/presentationbaseslide/
---
## PresentationBaseSlide class

Stellt die abstrakte Basisklasse für Folien aller Typen in einem PowerPoint-Dokument bereit.

```csharp
public abstract class PresentationBaseSlide : ContentPart
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Charts](../../groupdocs.watermark.contents.presentation/presentationbaseslide/charts) { get; } | Ermittelt die Sammlung aller Diagramme in der Präsentation. |
| [ImageFillFormat](../../groupdocs.watermark.contents.presentation/presentationbaseslide/imagefillformat) { get; } | Ermittelt die Einstellungen des Bildfüllformats der Präsentation. |
| [Shapes](../../groupdocs.watermark.contents.presentation/presentationbaseslide/shapes) { get; } | Ermittelt die Sammlung aller Formen der Präsentation. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | Findet alle Bilder im Inhalt. Die Suche wird in den in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) angegebenen Objekten durchgeführt. |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | Findet Bilder gemäß den angegebenen Suchkriterien. Die Suche wird in den in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) angegebenen Objekten durchgeführt. |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | Findet alle möglichen Wasserzeichen im Inhalt. Die Suche wird in den in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) angegebenen Objekten durchgeführt. |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | Findet mögliche Wasserzeichen gemäß den angegebenen Suchkriterien. Die Suche wird in den in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) angegebenen Objekten durchgeführt. |

### Siehe auch

* class [ContentPart](../../groupdocs.watermark.contents/contentpart)
* namespace [GroupDocs.Watermark.Contents.Presentation](../../groupdocs.watermark.contents.presentation)
* assembly [GroupDocs.Watermark](../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.watermark.dll -->
