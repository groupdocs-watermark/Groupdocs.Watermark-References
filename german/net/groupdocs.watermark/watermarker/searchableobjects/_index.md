---
title: "SearchableObjects"
second_title: "GroupDocs.Watermark für .NET API-Referenz"
description: "Liest oder setzt die Inhaltsobjekte, die in einer Wasserzeichen-Suche einbezogen werden sollen."
type: docs
weight: 20
url: /de/net/groupdocs.watermark/watermarker/searchableobjects/
---
## Watermarker.SearchableObjects property

Liest oder setzt die Inhaltsobjekte, die in einer Wasserzeichen-Suche einbezogen werden sollen.

```csharp
public SearchableObjects SearchableObjects { get; set; }
```

### Property Value

Die Objekte, die in eine Wasserzeichen‑Suche einbezogen werden sollen.

### Hinweise

Diese Eigenschaft gibt außerdem Inhaltsobjekte an, die bei der Bildsuche verwendet werden. Weitere Informationen finden Sie in den Methoden [`Search`](../search) und [`GetImages`](../getimages).

Erfahren Sie mehr über das Suchen von Wasserzeichen: [Suchen von Wasserzeichen](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks).

### Beispiele

Entferne alle XObjects und Artefakte aus einem PDF-Dokument.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\test.pdf"))
{
    // Gib an, dass nur nach XObjects und Artefakten gesucht werden soll.
    watermarker.SearchableObjects.PdfSearchableObjects
        = PdfSearchableObjects.XObjects | PdfSearchableObjects.Artifacts; 

    PossibleWatermarkCollection watermarks = watermarker.Search();

    // Entferne alle gefundenen Objekte.
    watermarks.Clear();

    // Änderungen speichern.
    watermarker.Save();
}
```

### Siehe auch

* class [SearchableObjects](../../../groupdocs.watermark.search.objects/searchableobjects)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.watermark.dll -->
