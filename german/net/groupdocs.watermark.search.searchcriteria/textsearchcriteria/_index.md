---
title: "TextSearchCriteria"
second_title: "GroupDocs.Watermark für .NET API-Referenz"
description: "Stellt Kriterien dar, die das Filtern nach Wasserzeichen‑Text ermöglichen."
type: docs
weight: 2750
url: /de/net/groupdocs.watermark.search.searchcriteria/textsearchcriteria/
---
## TextSearchCriteria class

Stellt Kriterien dar, die das Filtern nach Wasserzeichen‑Text ermöglichen.

```csharp
public class TextSearchCriteria : PageSearchCriteria
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [TextSearchCriteria](textsearchcriteria#constructor_2)(Regex) | Initialisiert eine neue Instanz der [`TextSearchCriteria`](../textsearchcriteria)-Klasse mit einem angegebenen regulären Ausdruck. |
| [TextSearchCriteria](textsearchcriteria#constructor)(string) | Initialisiert eine neue Instanz der [`TextSearchCriteria`](../textsearchcriteria)-Klasse mit einem Suchstring. |
| [TextSearchCriteria](textsearchcriteria#constructor_1)(string, bool) | Initialisiert eine neue Instanz der [`TextSearchCriteria`](../textsearchcriteria)-Klasse mit einem Suchstring und einem Vergleichs-Flag. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Pages](../../groupdocs.watermark.search.searchcriteria/pagesearchcriteria/pages) { get; set; } | Liefert oder setzt die Liste spezifischer Seitenzahlen |
| [Pattern](../../groupdocs.watermark.search.searchcriteria/textsearchcriteria/pattern) { get; } | Liefert das Suchmuster. |
| [SkipUnreadableCharacters](../../groupdocs.watermark.search.searchcriteria/textsearchcriteria/skipunreadablecharacters) { get; set; } | Liest oder setzt einen Wert, der angibt, dass nicht lesbare Zeichen beim Zeichenkettenvergleich übersprungen werden. |

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

* class [PageSearchCriteria](../pagesearchcriteria)
* namespace [GroupDocs.Watermark.Search.SearchCriteria](../../groupdocs.watermark.search.searchcriteria)
* assembly [GroupDocs.Watermark](../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.watermark.dll -->
