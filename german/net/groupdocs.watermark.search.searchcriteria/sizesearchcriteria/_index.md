---
title: "SizeSearchCriteria"
second_title: "GroupDocs.Watermark für .NET API-Referenz"
description: "Stellt Kriterien dar, die das Filtern nach Wasserzeichen‑Größe ermöglichen."
type: docs
weight: 2730
url: /de/net/groupdocs.watermark.search.searchcriteria/sizesearchcriteria/
---
## SizeSearchCriteria class

Stellt Kriterien dar, die das Filtern nach Wasserzeichen‑Größe ermöglichen.

```csharp
public class SizeSearchCriteria : SearchCriteria
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [SizeSearchCriteria](sizesearchcriteria)(Dimension, double, double) | Initialisiert eine neue Instanz der [`SizeSearchCriteria`](../sizesearchcriteria) Klasse mit einer angegebenen Dimension, einem Startwert und einem Endwert. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Dimension](../../groupdocs.watermark.search.searchcriteria/sizesearchcriteria/dimension) { get; } | Liest die Dimension des Wasserzeichens, nach der gesucht wird. |
| [Maximum](../../groupdocs.watermark.search.searchcriteria/sizesearchcriteria/maximum) { get; } | Liest den Endwert. |
| [Minimum](../../groupdocs.watermark.search.searchcriteria/sizesearchcriteria/minimum) { get; } | Liest den Startwert. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [And](../../groupdocs.watermark.search.searchcriteria/searchcriteria/and)(SearchCriteria) | Kombiniert dieses [`SearchCriteria`](../searchcriteria) mit anderen Kriterien mittels logischem UND-Operator. |
| [Not](../../groupdocs.watermark.search.searchcriteria/searchcriteria/not)() | Negiert dieses [`SearchCriteria`](../searchcriteria). |
| [Or](../../groupdocs.watermark.search.searchcriteria/searchcriteria/or)(SearchCriteria) | Kombiniert dieses [`SearchCriteria`](../searchcriteria) mit anderen Kriterien mittels logischem ODER-Operator. |

### Hinweise

**Learn more:**

* [Searching watermarks](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks)

### Beispiele

Findet und entfernt das Wasserzeichen mithilfe von Suchkriterien.

```csharp
using (Watermarker watermarker = new Watermarker(@"C:\test.some_ext"))
{
    SizeSearchCriteria widthRange = new SizeSearchCriteria(Dimension.Width, 50, 100);
    RotateAngleSearchCriteria rotateAngle = new RotateAngleSearchCriteria(0, 45);
    TextSearchCriteria textCriteria = new TextSearchCriteria(new Regex("^Test watermark$"));
    PossibleWatermarkCollection watermarks = watermarker.Search(textCriteria.And(widthRange.Or(rotateAngle)));
    watermarks.Clear();
    watermarker.Save();
}
```

### Siehe auch

* class [SearchCriteria](../searchcriteria)
* namespace [GroupDocs.Watermark.Search.SearchCriteria](../../groupdocs.watermark.search.searchcriteria)
* assembly [GroupDocs.Watermark](../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.watermark.dll -->
