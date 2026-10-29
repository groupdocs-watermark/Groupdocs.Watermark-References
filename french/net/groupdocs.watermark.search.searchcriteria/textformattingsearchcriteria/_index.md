---
title: "TextFormattingSearchCriteria"
second_title: "GroupDocs.Watermark pour .NET Référence de l'API"
description: "Représente des critères permettant de filtrer par formatage du texte."
type: docs
weight: 2740
url: /fr/net/groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/
---
## TextFormattingSearchCriteria class

Représente des critères permettant de filtrer par formatage du texte.

```csharp
public class TextFormattingSearchCriteria : SearchCriteria
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [TextFormattingSearchCriteria](textformattingsearchcriteria)() | Initialise une nouvelle instance de la classe [`TextFormattingSearchCriteria`](../textformattingsearchcriteria). |

## Propriétés

| Nom | Description |
| --- | --- |
| [BackgroundColorRange](../../groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/backgroundcolorrange) { get; set; } | Obtient ou définit la plage de couleurs utilisée pour filtrer les filigranes par couleur d'arrière-plan du texte. |
| [FontBold](../../groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/fontbold) { get; set; } | Obtient ou définit une valeur indiquant si la police utilisée dans le formatage du texte du filigrane est en gras. |
| [FontItalic](../../groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/fontitalic) { get; set; } | Obtient ou définit une valeur indiquant si la police utilisée dans le formatage du texte du filigrane est en italique. |
| [FontName](../../groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/fontname) { get; set; } | Obtient ou définit le nom de la police utilisée dans le formatage possible du texte du filigrane. |
| [FontStrikeout](../../groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/fontstrikeout) { get; set; } | Obtient ou définit une valeur indiquant si la police utilisée dans le formatage du texte du filigrane est barrée. |
| [FontUnderline](../../groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/fontunderline) { get; set; } | Obtient ou définit une valeur indiquant si la police utilisée dans le formatage du texte du filigrane est soulignée. |
| [ForegroundColorRange](../../groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/foregroundcolorrange) { get; set; } | Obtient ou définit la plage de couleurs utilisée pour filtrer les filigranes par couleur de premier plan du texte. |
| [MaxFontSize](../../groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/maxfontsize) { get; set; } | Obtient ou définit la valeur de fin de la taille de police. |
| [MinFontSize](../../groupdocs.watermark.search.searchcriteria/textformattingsearchcriteria/minfontsize) { get; set; } | Obtient ou définit la valeur de départ de la taille de police. |

## Méthodes

| Nom | Description |
| --- | --- |
| [And](../../groupdocs.watermark.search.searchcriteria/searchcriteria/and)(SearchCriteria) | Combine ce [`SearchCriteria`](../searchcriteria) avec d'autres critères en utilisant l'opérateur logique AND. |
| [Not](../../groupdocs.watermark.search.searchcriteria/searchcriteria/not)() | Inverse ce [`SearchCriteria`](../searchcriteria). |
| [Or](../../groupdocs.watermark.search.searchcriteria/searchcriteria/or)(SearchCriteria) | Combine ce [`SearchCriteria`](../searchcriteria) avec d'autres critères en utilisant l'opérateur logique OR. |

### Remarques

**Learn more:**

* [Searching watermarks](https://docs.groupdocs.com/display/watermarknet/Searching+watermarks)

### Exemples

Supprime les filigranes possibles avec un formatage de texte particulier (indépendamment du type de document).

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

### Voir aussi

* class [SearchCriteria](../searchcriteria)
* namespace [GroupDocs.Watermark.Search.SearchCriteria](../../groupdocs.watermark.search.searchcriteria)
* assembly [GroupDocs.Watermark](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.watermark.dll -->
