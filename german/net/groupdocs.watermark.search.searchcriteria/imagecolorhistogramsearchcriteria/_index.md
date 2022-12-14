---
title: ImageColorHistogramSearchCriteria
second_title: GroupDocs.Watermark für .NET-API-Referenz
description: Repräsentiert Suchkriterien zum Auffinden von Bildern in einem Inhalt.
type: docs
weight: 2580
url: /de/net/groupdocs.watermark.search.searchcriteria/imagecolorhistogramsearchcriteria/
---
## ImageColorHistogramSearchCriteria class

Repräsentiert Suchkriterien zum Auffinden von Bildern in einem Inhalt.

```csharp
public class ImageColorHistogramSearchCriteria : ImageSearchCriteria
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [ImageColorHistogramSearchCriteria](imagecolorhistogramsearchcriteria#constructor)(Stream) | Initialisiert eine neue Instanz von[`ImageColorHistogramSearchCriteria`](../imagecolorhistogramsearchcriteria) Klasse mit einem bestimmten Stream. |
| [ImageColorHistogramSearchCriteria](imagecolorhistogramsearchcriteria#constructor_1)(string) | Initialisiert eine neue Instanz von[`ImageColorHistogramSearchCriteria`](../imagecolorhistogramsearchcriteria) Klasse mit einem angegebenen Dateipfad. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BinsCount](../../groupdocs.watermark.search.searchcriteria/imagecolorhistogramsearchcriteria/binscount) { get; set; } | Ruft eine Anzahl von Bins ab oder legt sie fest, die zum Erstellen von Farbhistogrammen verwendet werden. |
| [MaxDifference](../../groupdocs.watermark.search.searchcriteria/imagesearchcriteria/maxdifference) { get; set; } | Ruft die maximal zulässige Differenz zwischen Bildern ab oder legt sie fest. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [And](../../groupdocs.watermark.search.searchcriteria/searchcriteria/and)(SearchCriteria) | Kombiniert dies[`SearchCriteria`](../searchcriteria) mit anderen Kriterien unter Verwendung des logischen UND-Operators. |
| [Not](../../groupdocs.watermark.search.searchcriteria/searchcriteria/not)() | Negiert dies[`SearchCriteria`](../searchcriteria) . |
| [Or](../../groupdocs.watermark.search.searchcriteria/searchcriteria/or)(SearchCriteria) | Kombiniert dies[`SearchCriteria`](../searchcriteria) mit anderen Kriterien mit logischem OR-Operator. |

### Bemerkungen

Dieses Suchkriterium verwendet Bildfarbhistogramme zur Berechnung der Bildähnlichkeit.

### Siehe auch

* class [ImageSearchCriteria](../imagesearchcriteria)
* namensraum [GroupDocs.Watermark.Search.SearchCriteria](../../groupdocs.watermark.search.searchcriteria)
* Montage [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
