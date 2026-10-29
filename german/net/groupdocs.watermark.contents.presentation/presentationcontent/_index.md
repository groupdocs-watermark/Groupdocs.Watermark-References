---
title: "PresentationContent"
second_title: "GroupDocs.Watermark für .NET API-Referenz"
description: "Stellt ein PowerPoint-Dokument dar, in dem ein Wasserzeichen platziert werden kann."
type: docs
weight: 900
url: /de/net/groupdocs.watermark.contents.presentation/presentationcontent/
---
## PresentationContent class

Stellt ein PowerPoint-Dokument dar, in dem ein Wasserzeichen platziert werden kann.

```csharp
public class PresentationContent : Content
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [LayoutSlides](../../groupdocs.watermark.contents.presentation/presentationcontent/layoutslides) { get; } | Liest die Sammlung aller Layout‑Folien dieses [`PresentationContent`](../presentationcontent). |
| [MasterHandoutSlide](../../groupdocs.watermark.contents.presentation/presentationcontent/masterhandoutslide) { get; } | Liest die Master‑Handout‑Folien dieses [`PresentationContent`](../presentationcontent). |
| [MasterNotesSlide](../../groupdocs.watermark.contents.presentation/presentationcontent/masternotesslide) { get; } | Liefert die Master‑Folien für alle Notizfolien dieses [`PresentationContent`](../presentationcontent). |
| [MasterSlides](../../groupdocs.watermark.contents.presentation/presentationcontent/masterslides) { get; } | Liefert die Sammlung aller Master‑Folien dieses [`PresentationContent`](../presentationcontent). |
| [NotesSlideHeight](../../groupdocs.watermark.contents.presentation/presentationcontent/notesslideheight) { get; } | Liefert die Höhe einer Notizfolie in Punkten. |
| [NotesSlideWidth](../../groupdocs.watermark.contents.presentation/presentationcontent/notesslidewidth) { get; } | Liefert die Breite einer Notizfolie in Punkten. |
| [SlideHeight](../../groupdocs.watermark.contents.presentation/presentationcontent/slideheight) { get; } | Liefert die Höhe einer Folie in Punkten. |
| [Slides](../../groupdocs.watermark.contents.presentation/presentationcontent/slides) { get; } | Liefert die Sammlung aller Folien dieses [`PresentationContent`](../presentationcontent). |
| [SlideWidth](../../groupdocs.watermark.contents.presentation/presentationcontent/slidewidth) { get; } | Liefert die Breite einer Folie in Punkten. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Decrypt](../../groupdocs.watermark.contents.presentation/presentationcontent/decrypt)() | Entschlüsselt das Dokument. |
| [Dispose](../../groupdocs.watermark.contents/content/dispose)() | Gibt die aktuelle Instanz frei. |
| [Encrypt](../../groupdocs.watermark.contents.presentation/presentationcontent/encrypt)(string) | Verschlüsselt das Dokument. |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | Findet alle Bilder im Inhalt. Die Suche wird in den in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) angegebenen Objekten durchgeführt. |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | Findet Bilder gemäß den angegebenen Suchkriterien. Die Suche wird in den in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) angegebenen Objekten durchgeführt. |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | Findet alle möglichen Wasserzeichen im Inhalt. Die Suche wird in den in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) angegebenen Objekten durchgeführt. |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | Findet mögliche Wasserzeichen gemäß den angegebenen Suchkriterien. Die Suche wird in den in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) angegebenen Objekten durchgeführt. |

### Hinweise

**Learn more:**

* [Add watermarks to presentation documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+presentation+documents)
* [Working with slide backgrounds](https://docs.groupdocs.com/display/watermarknet/Working+with+slide+backgrounds)

### Beispiele

Lädt und speichert PowerPoint‑Dokumente jedes unterstützten Typs.

```csharp
PresentationLoadOptions loadOptions = new PresentationLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\input.ppt", loadOptions))
{
    // Verwenden Sie die Add‑Methode, um ein Wasserzeichen zu einer bestimmten Folie oder zu allen Folien hinzuzufügen.

    // Änderungen speichern.
    watermarker.Save(@"D:\output.ppt");
}
```

### Siehe auch

* class [Content](../../groupdocs.watermark.contents/content)
* namespace [GroupDocs.Watermark.Contents.Presentation](../../groupdocs.watermark.contents.presentation)
* assembly [GroupDocs.Watermark](../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.watermark.dll -->
