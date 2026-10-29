---
title: "RotateAngleSearchCriteria"
second_title: "GroupDocs.Watermark für .NET API-Referenz"
description: "Stellt Kriterien dar, die das Filtern nach dem Rotationswinkel des Wasserzeichens ermöglichen."
type: docs
weight: 2710
url: /de/net/groupdocs.watermark.search.searchcriteria/rotateanglesearchcriteria/
---
## RotateAngleSearchCriteria class

Stellt Kriterien dar, die das Filtern nach dem Rotationswinkel des Wasserzeichens ermöglichen.

```csharp
public class RotateAngleSearchCriteria : SearchCriteria
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [RotateAngleSearchCriteria](rotateanglesearchcriteria)(double, double) | Initialisiert eine neue Instanz der [`RotateAngleSearchCriteria`](../rotateanglesearchcriteria)-Klasse mit einem Startwinkel und einem Endwinkel. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [MaximumAngle](../../groupdocs.watermark.search.searchcriteria/rotateanglesearchcriteria/maximumangle) { get; } | Liest den Endwinkel in Grad. |
| [MinimumAngle](../../groupdocs.watermark.search.searchcriteria/rotateanglesearchcriteria/minimumangle) { get; } | Liest den Startwinkel in Grad. |

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

Finde und entferne Wasserzeichen mithilfe von Suchkriterien.

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
