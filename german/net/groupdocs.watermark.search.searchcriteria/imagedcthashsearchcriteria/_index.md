---
title: "ImageDctHashSearchCriteria"
second_title: "GroupDocs.Watermark für .NET API-Referenz"
description: "Stellt ein Suchkriterium zum Finden von Bildern in einem Dokument dar."
type: docs
weight: 2630
url: /de/net/groupdocs.watermark.search.searchcriteria/imagedcthashsearchcriteria/
---
## ImageDctHashSearchCriteria class

Stellt ein Suchkriterium zum Finden von Bildern in einem Dokument dar.

```csharp
public class ImageDctHashSearchCriteria : ImageSearchCriteria
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [ImageDctHashSearchCriteria](imagedcthashsearchcriteria#constructor)(Stream) | Initialisiert eine neue Instanz der [`ImageDctHashSearchCriteria`](../imagedcthashsearchcriteria)-Klasse mit einem angegebenen Stream. |
| [ImageDctHashSearchCriteria](imagedcthashsearchcriteria#constructor_1)(string) | Initialisiert eine neue Instanz der [`ImageDctHashSearchCriteria`](../imagedcthashsearchcriteria)-Klasse mit einem angegebenen Dateipfad. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [MaxDifference](../../groupdocs.watermark.search.searchcriteria/imagesearchcriteria/maxdifference) { get; set; } | Liest oder setzt die maximal zulässige Differenz zwischen Bildern. |
| [Pages](../../groupdocs.watermark.search.searchcriteria/pagesearchcriteria/pages) { get; set; } | Liefert oder setzt die Liste spezifischer Seitenzahlen |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [And](../../groupdocs.watermark.search.searchcriteria/searchcriteria/and)(SearchCriteria) | Kombiniert dieses [`SearchCriteria`](../searchcriteria) mit anderen Kriterien mittels logischem UND-Operator. |
| [Not](../../groupdocs.watermark.search.searchcriteria/searchcriteria/not)() | Negiert dieses [`SearchCriteria`](../searchcriteria). |
| [Or](../../groupdocs.watermark.search.searchcriteria/searchcriteria/or)(SearchCriteria) | Kombiniert dieses [`SearchCriteria`](../searchcriteria) mit anderen Kriterien mittels logischem ODER-Operator. |

### Hinweise

Dieses Suchkriterium verwendet DCT-basierte perzeptuelle Bild-Hashes zur Berechnung der Bildähnlichkeit. **Mehr erfahren:**

* [Searching watermarks](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks)

### Beispiele

Suche nach Bildern in den angehängten Dateien (PDF).

```csharp
WatermarkerSettings settings = new WatermarkerSettings();
settings.SearchableObjects = new SearchableObjects
{
    PdfSearchableObjects = PdfSearchableObjects.All
};
PdfLoadOptions loadOptions = new PdfLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\test.pdf", loadOptions, settings))
{
    // Geben Sie ein Beispielbild an, um Dokumentenbilder damit zu vergleichen
    ImageSearchCriteria criteria = new ImageDctHashSearchCriteria(@"D:\sample.png");
    // Suche nach ähnlichen Bildern
    PossibleWatermarkCollection possibleWatermarks = watermarker.Search(criteria);
    // Entfernen oder ändern gefundene Bildwasserzeichen
    // ...
}
```

### Siehe auch

* class [ImageSearchCriteria](../imagesearchcriteria)
* namespace [GroupDocs.Watermark.Search.SearchCriteria](../../groupdocs.watermark.search.searchcriteria)
* assembly [GroupDocs.Watermark](../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.watermark.dll -->
