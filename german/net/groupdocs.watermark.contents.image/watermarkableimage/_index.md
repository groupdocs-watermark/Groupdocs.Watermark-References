---
title: "WatermarkableImage"
second_title: "GroupDocs.Watermark für .NET API-Referenz"
description: "Stellt ein Bild in einem Dokument dar."
type: docs
weight: 470
url: /de/net/groupdocs.watermark.contents.image/watermarkableimage/
---
## WatermarkableImage class

Stellt ein Bild in einem Dokument dar.

```csharp
public abstract class WatermarkableImage : ContentPart
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Height](../../groupdocs.watermark.contents.image/watermarkableimage/height) { get; } | Ermittelt die Höhe dieses [`WatermarkableImage`](../watermarkableimage) in Pixeln. |
| [Width](../../groupdocs.watermark.contents.image/watermarkableimage/width) { get; } | Ermittelt die Breite dieses [`WatermarkableImage`](../watermarkableimage) in Pixeln. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Add](../../groupdocs.watermark.contents.image/watermarkableimage/add)(Watermark) | Fügt diesem [`WatermarkableImage`](../watermarkableimage) ein Wasserzeichen hinzu. Diese Methode geht davon aus, dass Wasserzeichenversatz und -größe in Pixeln gemessen werden (falls sie zugewiesen wurden). |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | Findet alle Bilder im Inhalt. Die Suche wird in den in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) angegebenen Objekten durchgeführt. |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | Findet Bilder gemäß den angegebenen Suchkriterien. Die Suche wird in den in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) angegebenen Objekten durchgeführt. |
| [GetBytes](../../groupdocs.watermark.contents.image/watermarkableimage/getbytes)() | Liefert das Bild als Byte-Array. |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | Findet alle möglichen Wasserzeichen im Inhalt. Die Suche wird in den in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) angegebenen Objekten durchgeführt. |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | Findet mögliche Wasserzeichen gemäß den angegebenen Suchkriterien. Die Suche wird in den in [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) angegebenen Objekten durchgeführt. |

### Hinweise

**Learn more:**

* [Adding watermark to images inside a document](https://docs.groupdocs.com/display/watermarknet/Adding+watermark+to+images+inside+a+document)

### Beispiele

Füge ein Wasserzeichen zu allen Bildern innerhalb eines Dokuments eines beliebigen unterstützten Typs hinzu.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\input.doc"))
{
    // Initialisiere Text- oder Bildwasserzeichen.
    TextWatermark watermark = new TextWatermark("DRAFT", new Font("Arial", 19));

    // Finde alle Bilder im Inhalt.
    WatermarkableImageCollection images = watermarker.GetImages();

    // Wasserzeichen hinzufügen.
    foreach (WatermarkableImage watermarkableImage in images)
    {
        watermarkableImage.Add(watermark);
    }

    // Änderungen speichern.
    watermarker.Save(@"D:\output.doc");
}
```

### Siehe auch

* class [ContentPart](../../groupdocs.watermark.contents/contentpart)
* namespace [GroupDocs.Watermark.Contents.Image](../../groupdocs.watermark.contents.image)
* assembly [GroupDocs.Watermark](../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.watermark.dll -->
