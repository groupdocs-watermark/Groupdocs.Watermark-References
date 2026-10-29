---
title: "SpreadsheetBackgroundWatermarkOptions"
second_title: "GroupDocs.Watermark pour .NET Référence de l'API"
description: "Représente les options lors de l'ajout du filigrane comme arrière-plan à une feuille de calcul Spreadsheet."
type: docs
weight: 2190
url: /fr/net/groupdocs.watermark.options.spreadsheet/spreadsheetbackgroundwatermarkoptions/
---
## SpreadsheetBackgroundWatermarkOptions class

Représente les options lors de l'ajout du filigrane comme arrière-plan à une feuille de calcul Spreadsheet.

```csharp
public sealed class SpreadsheetBackgroundWatermarkOptions : WatermarkOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [SpreadsheetBackgroundWatermarkOptions](spreadsheetbackgroundwatermarkoptions)() | Initialise une nouvelle instance de la classe [`SpreadsheetBackgroundWatermarkOptions`](../spreadsheetbackgroundwatermarkoptions). |

## Propriétés

| Nom | Description |
| --- | --- |
| [BackgroundHeight](../../groupdocs.watermark.options.spreadsheet/spreadsheetbackgroundwatermarkoptions/backgroundheight) { get; set; } | Obtient ou définit la hauteur souhaitée de l'image d'arrière-plan en pixels. |
| [BackgroundWidth](../../groupdocs.watermark.options.spreadsheet/spreadsheetbackgroundwatermarkoptions/backgroundwidth) { get; set; } | Obtient ou définit la largeur souhaitée de l'image d'arrière-plan en pixels. |
| [WorksheetIndex](../../groupdocs.watermark.options.spreadsheet/spreadsheetbackgroundwatermarkoptions/worksheetindex) { get; set; } | Obtient ou définit l'index de la feuille de calcul où ajouter le filigrane. |

### Remarques

**Learn more:**

* [Add watermarks to spreadsheet documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+spreadsheet+documents)

### Exemples

Ajoutez un filigrane texte à une feuille de calcul d'un document Excel en tant qu'arrière-plan.

```csharp
SpreadsheetLoadOptions loadOptions = new SpreadsheetLoadOptions();
using (Watermarker watermarker = new Watermarker(@"C:\Documents\test.xlsx", loadOptions))
{
    TextWatermark watermark = new TextWatermark("Test watermark", new Font("Arial", 36));

    SpreadsheetBackgroundWatermarkOptions options = new SpreadsheetBackgroundWatermarkOptions();
    options.WorksheetIndex = -1; // default
    options.BackgroundWidth = 800;
    options.BackgroundHeight = 600;

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### Voir aussi

* class [WatermarkOptions](../../groupdocs.watermark.options/watermarkoptions)
* namespace [GroupDocs.Watermark.Options.Spreadsheet](../../groupdocs.watermark.options.spreadsheet)
* assembly [GroupDocs.Watermark](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.watermark.dll -->
