---
title: "SpreadsheetWatermarkShapeOptions"
second_title: "GroupDocs.Watermark pour .NET Référence de l'API"
description: "Représente les options lors de l'ajout d'un filigrane de forme à une feuille de calcul Spreadsheet."
type: docs
weight: 2290
url: /fr/net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkshapeoptions/
---
## SpreadsheetWatermarkShapeOptions class

Représente les options lors de l'ajout d'un filigrane de forme à une feuille de calcul Spreadsheet.

```csharp
public sealed class SpreadsheetWatermarkShapeOptions : SpreadsheetWatermarkBaseOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [SpreadsheetWatermarkShapeOptions](spreadsheetwatermarkshapeoptions)() | Initialise une nouvelle instance de la classe [`SpreadsheetWatermarkShapeOptions`](../spreadsheetwatermarkshapeoptions). |

## Propriétés

| Nom | Description |
| --- | --- |
| [AlternativeText](../../groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkbaseoptions/alternativetext) { get; set; } | Obtient ou définit le texte descriptif (alternatif) qui sera associé à une forme. |
| [Effects](../../groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkshapeoptions/effects) { get; set; } | Obtient ou définit une valeur de [`SpreadsheetImageEffects`](../spreadsheetimageeffects) ou [`SpreadsheetTextEffects`](../spreadsheettexteffects) pour les effets qui doivent être appliqués au filigrane. |
| [IsLocked](../../groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkbaseoptions/islocked) { get; set; } | Obtient ou définit une valeur indiquant si la modification de la forme dans Excel est interdite. |
| [Name](../../groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkbaseoptions/name) { get; set; } | Obtient ou définit le nom d'une forme. |
| [WorksheetIndex](../../groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkshapeoptions/worksheetindex) { get; set; } | Obtient ou définit l'index de la feuille de calcul où ajouter le filigrane. |

### Remarques

**Learn more:**

* [Add watermarks to spreadsheet documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+spreadsheet+documents)

### Exemples

Ajoutez un filigrane à une feuille de calcul particulière d'un document Excel.

```csharp
SpreadsheetLoadOptions loadOptions = new SpreadsheetLoadOptions();
using (Watermarker watermarker = new Watermarker(@"C:\Documents\test.xls", loadOptions))
{
    TextWatermark watermark = new TextWatermark("Test watermark", new Font("Arial", 36, FontStyle.Bold | FontStyle.Italic));
    watermark.HorizontalAlignment = HorizontalAlignment.Center;
    watermark.VerticalAlignment = VerticalAlignment.Center;

    SpreadsheetWatermarkShapeOptions options = new SpreadsheetWatermarkShapeOptions();
    options.WorksheetIndex = 0;

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### Voir aussi

* class [SpreadsheetWatermarkBaseOptions](../spreadsheetwatermarkbaseoptions)
* namespace [GroupDocs.Watermark.Options.Spreadsheet](../../groupdocs.watermark.options.spreadsheet)
* assembly [GroupDocs.Watermark](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.watermark.dll -->
