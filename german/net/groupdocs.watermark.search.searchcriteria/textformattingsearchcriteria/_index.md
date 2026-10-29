---
title: "TextFormattingSearchCriteria"
second_title: "GroupDocs.Watermark für .NET API-Referenz"
description: "Stellt Kriterien dar, die das Filtern nach Textformatierung ermöglichen."
type: docs
weight: 2740
url: /de/net/groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/
---
## TextFormattingSearchCriteria class

Stellt Kriterien dar, die das Filtern nach Textformatierung ermöglichen.

```csharp
public class TextFormattingSearchCriteria : SearchCriteria
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [TextFormattingSearchCriteria](textformattingsearchcriteria)() | Initialisiert eine neue Instanz der [`TextFormattingSearchCriteria`](../textformattingsearchcriteria) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BackgroundColorRange](../../groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/backgroundcolorrange) { get; set; } | Liest oder setzt den Farbbereich, der zum Filtern von Wasserzeichen nach Text-Hintergrundfarbe verwendet wird. |
| [FontBold](../../groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/fontbold) { get; set; } | Liest oder setzt einen Wert, der angibt, ob die im Wasserzeichen-Textformat verwendete Schrift fett ist. |
| [FontItalic](../../groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/fontitalic) { get; set; } | Liest oder setzt einen Wert, der angibt, ob die im Wasserzeichen-Textformat verwendete Schrift kursiv ist. |
| [FontName](../../groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/fontname) { get; set; } | Liest oder setzt den Namen der Schrift, die in möglichen Wasserzeichen-Textformaten verwendet wird. |
| [FontStrikeout](../../groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/fontstrikeout) { get; set; } | Liest oder setzt einen Wert, der angibt, ob die im Wasserzeichen-Textformat verwendete Schrift durchgestrichen ist. |
| [FontUnderline](../../groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/fontunderline) { get; set; } | Liest oder setzt einen Wert, der angibt, ob die im Wasserzeichen-Textformat verwendete Schrift unterstrichen ist. |
| [ForegroundColorRange](../../groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/foregroundcolorrange) { get; set; } | Liest oder setzt den Farbbereich, der zum Filtern von Wasserzeichen nach Text-Vordergrundfarbe verwendet wird. |
| [MaxFontSize](../../groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/maxfontsize) { get; set; } | Liest oder setzt den Endwert der Schriftgröße. |
| [MinFontSize](../../groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/minfontsize) { get; set; } | Liest oder setzt den Startwert der Schriftgröße |

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

Entfernt mögliche Wasserzeichen mit einer bestimmten Textformatierung (unabhängig vom Dokumenttyp).

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\test.doc"))
{
    TextFormattingSearchCriteria criteria = new TextFormattingSearchCriteria();
    criteria.ForegroundColorRange = new ColorRange();
    criteria.ForegroundColorRange.MinHue = -5;
    criteria.ForegroundColorRange.MaxHue = 10;
    criteria.ForegroundColorRange.MinBrightness = 0.01f;
    criteria.ForegroundColorRange.MaxBrightness = 0.99f;
    criteria.BackgroundColorRange = new ColorRange();
    criteria.BackgroundColorRange.IsEmpty = true;
    criteria.FontName = "Arial";
    criteria.MinFontSize = 19;
    criteria.MaxFontSize = 42;
    criteria.FontBold = true;

    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    watermarks.Clear();
    watermarker.Save();
}
```

### Siehe auch

* class [SearchCriteria](../searchcriteria)
* namespace [GroupDocs.Watermark.Search.SearchCriteria](../../groupdocs.watermark.search.searchcriteria)
* assembly [GroupDocs.Watermark](../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.watermark.dll -->
