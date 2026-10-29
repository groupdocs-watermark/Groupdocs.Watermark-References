---
title: "SpreadsheetWatermarkModernWordArtOptions"
second_title: "GroupDocs.Watermark pour .NET Référence de l'API"
description: "Représente les options lors de l'ajout d'un filigrane word art moderne à une feuille de calcul Spreadsheet."
type: docs
weight: 2280
url: /fr/net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkmodernwordartoptions/
---
## SpreadsheetWatermarkModernWordArtOptions class

Représente les options lors de l'ajout d'un filigrane word art moderne à une feuille de calcul Spreadsheet.

```csharp
public sealed class SpreadsheetWatermarkModernWordArtOptions : SpreadsheetWatermarkBaseOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [SpreadsheetWatermarkModernWordArtOptions](spreadsheetwatermarkmodernwordartoptions)() | Initialise une nouvelle instance de la classe [`SpreadsheetWatermarkModernWordArtOptions`](../spreadsheetwatermarkmodernwordartoptions). |

## Propriétés

| Nom | Description |
| --- | --- |
| [AlternativeText](../../groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkbaseoptions/alternativetext) { get; set; } | Obtient ou définit le texte descriptif (alternatif) qui sera associé à une forme. |
| [IsLocked](../../groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkbaseoptions/islocked) { get; set; } | Obtient ou définit une valeur indiquant si la modification de la forme dans Excel est interdite. |
| [Name](../../groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkbaseoptions/name) { get; set; } | Obtient ou définit le nom d'une forme. |
| [WorksheetIndex](../../groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkmodernwordartoptions/worksheetindex) { get; set; } | Obtient ou définit l'index de la feuille de calcul où ajouter le filigrane. |

### Remarques

**Learn more:**

* [Add watermarks to spreadsheet documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+spreadsheet+documents)

### Exemples

Ajoutez un filigrane WordArt moderne à un document Excel.

```csharp
SpreadsheetLoadOptions loadOptions = new SpreadsheetLoadOptions();
using (Watermarker watermarker = new Watermarker(@"C:\Documents\test.xls", loadOptions))
{
    TextWatermark watermark = new TextWatermark("Test watermark", new Font("Arial", 36));

    SpreadsheetWatermarkModernWordArtOptions options = new SpreadsheetWatermarkModernWordArtOptions();
    options.WorksheetIndex = -1; // default
    options.IsLocked = false; // default

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### Voir aussi

* class [SpreadsheetWatermarkBaseOptions](../spreadsheetwatermarkbaseoptions)
* namespace [GroupDocs.Watermark.Options.Spreadsheet](../../groupdocs.watermark.options.spreadsheet)
* assembly [GroupDocs.Watermark](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.watermark.dll -->
