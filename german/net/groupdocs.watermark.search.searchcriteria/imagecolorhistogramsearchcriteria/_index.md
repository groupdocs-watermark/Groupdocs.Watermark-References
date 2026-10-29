---
title: "ImageColorHistogramSearchCriteria"
second_title: "GroupDocs.Watermark für .NET API-Referenz"
description: "Stellt Suchkriterien zum Finden von Bildern in einem Inhalt dar."
type: docs
weight: 2620
url: /de/net/groupdocs.watermark.search.searchcriteria/imagecolorhistogramsearchcriteria/
---
## ImageColorHistogramSearchCriteria class

Stellt Suchkriterien zum Finden von Bildern in einem Inhalt dar.

```csharp
public class ImageColorHistogramSearchCriteria : ImageSearchCriteria
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [ImageColorHistogramSearchCriteria](imagecolorhistogramsearchcriteria#constructor)(Stream) | Initialisiert eine neue Instanz der [`ImageColorHistogramSearchCriteria`](../imagecolorhistogramsearchcriteria) Klasse mit einem angegebenen Stream. |
| [ImageColorHistogramSearchCriteria](imagecolorhistogramsearchcriteria#constructor_1)(string) | Initialisiert eine neue Instanz der [`ImageColorHistogramSearchCriteria`](../imagecolorhistogramsearchcriteria) Klasse mit einem angegebenen Dateipfad. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BinsCount](../../groupdocs.watermark.search.searchcriteria/imagecolorhistogramsearchcriteria/binscount) { get; set; } | Liest oder setzt die Anzahl der Behälter, die zum Erstellen von Farbhistogrammen verwendet werden. |
| [MaxDifference](../../groupdocs.watermark.search.searchcriteria/imagesearchcriteria/maxdifference) { get; set; } | Liest oder setzt die maximal zulässige Differenz zwischen Bildern. |
| [Pages](../../groupdocs.watermark.search.searchcriteria/pagesearchcriteria/pages) { get; set; } | Liefert oder setzt die Liste spezifischer Seitenzahlen |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [And](../../groupdocs.watermark.search.searchcriteria/searchcriteria/and)(SearchCriteria) | Kombiniert dieses [`SearchCriteria`](../searchcriteria) mit anderen Kriterien mittels logischem UND-Operator. |
| [Not](../../groupdocs.watermark.search.searchcriteria/searchcriteria/not)() | Negiert dieses [`SearchCriteria`](../searchcriteria). |
| [Or](../../groupdocs.watermark.search.searchcriteria/searchcriteria/or)(SearchCriteria) | Kombiniert dieses [`SearchCriteria`](../searchcriteria) mit anderen Kriterien mittels logischem ODER-Operator. |

### Hinweise

Dieses Suchkriterium verwendet Farbhistogramme von Bildern zur Berechnung der Bildähnlichkeit.

### Siehe auch

* class [ImageSearchCriteria](../imagesearchcriteria)
* namespace [GroupDocs.Watermark.Search.SearchCriteria](../../groupdocs.watermark.search.searchcriteria)
* assembly [GroupDocs.Watermark](../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.watermark.dll -->
