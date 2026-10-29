---
title: "ImageThumbnailSearchCriteria"
second_title: "GroupDocs.Watermark für .NET API-Referenz"
description: "Stellt Suchkriterien zum Finden von Bildern in einem Inhalt dar."
type: docs
weight: 2650
url: /de/net/groupdocs.watermark.search.searchcriteria/imagethumbnailsearchcriteria/
---
## ImageThumbnailSearchCriteria class

Stellt Suchkriterien zum Finden von Bildern in einem Inhalt dar.

```csharp
public class ImageThumbnailSearchCriteria : ImageSearchCriteria
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [ImageThumbnailSearchCriteria](imagethumbnailsearchcriteria#constructor)(Stream) | Initialisiert eine neue Instanz der [`ImageThumbnailSearchCriteria`](../imagethumbnailsearchcriteria)-Klasse mit einem angegebenen Stream. |
| [ImageThumbnailSearchCriteria](imagethumbnailsearchcriteria#constructor_1)(string) | Initialisiert eine neue Instanz der [`ImageThumbnailSearchCriteria`](../imagethumbnailsearchcriteria)-Klasse mit einem angegebenen Dateipfad. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [MaxDifference](../../groupdocs.watermark.search.searchcriteria/imagesearchcriteria/maxdifference) { get; set; } | Liest oder setzt die maximal zulässige Differenz zwischen Bildern. |
| [Pages](../../groupdocs.watermark.search.searchcriteria/pagesearchcriteria/pages) { get; set; } | Liefert oder setzt die Liste spezifischer Seitenzahlen |
| [ThumbnailSize](../../groupdocs.watermark.search.searchcriteria/imagethumbnailsearchcriteria/thumbnailsize) { get; set; } | Liest oder setzt die Thumbnail-Größe. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [And](../../groupdocs.watermark.search.searchcriteria/searchcriteria/and)(SearchCriteria) | Kombiniert dieses [`SearchCriteria`](../searchcriteria) mit anderen Kriterien mittels logischem UND-Operator. |
| [Not](../../groupdocs.watermark.search.searchcriteria/searchcriteria/not)() | Negiert dieses [`SearchCriteria`](../searchcriteria). |
| [Or](../../groupdocs.watermark.search.searchcriteria/searchcriteria/or)(SearchCriteria) | Kombiniert dieses [`SearchCriteria`](../searchcriteria) mit anderen Kriterien mittels logischem ODER-Operator. |

### Hinweise

Dieses Suchkriterium verwendet ein binarisiertes Bild-Thumbnail zur Berechnung der Bildähnlichkeit.

### Siehe auch

* class [ImageSearchCriteria](../imagesearchcriteria)
* namespace [GroupDocs.Watermark.Search.SearchCriteria](../../groupdocs.watermark.search.searchcriteria)
* assembly [GroupDocs.Watermark](../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.watermark.dll -->
