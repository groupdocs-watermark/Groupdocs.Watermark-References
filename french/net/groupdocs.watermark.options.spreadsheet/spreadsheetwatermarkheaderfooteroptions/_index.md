---
title: SpreadsheetWatermarkHeaderFooterOptions
second_title: Référence de l'API GroupDocs.Watermark pour .NET
description: Représente les options lors de lajout du filigrane à un entête/pied de page de feuille de calcul.
type: docs
weight: 2200
url: /fr/net/groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkheaderfooteroptions/
---
## SpreadsheetWatermarkHeaderFooterOptions class

Représente les options lors de l'ajout du filigrane à un en-tête/pied de page de feuille de calcul.

```csharp
public sealed class SpreadsheetWatermarkHeaderFooterOptions : SpreadsheetWatermarkOptions
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [SpreadsheetWatermarkHeaderFooterOptions](spreadsheetwatermarkheaderfooteroptions)() | Initialise une nouvelle instance du[`SpreadsheetWatermarkHeaderFooterOptions`](../spreadsheetwatermarkheaderfooteroptions) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [WorksheetIndex](../../groupdocs.watermark.options.spreadsheet/spreadsheetwatermarkheaderfooteroptions/worksheetindex) { get; set; } | Obtient ou définit l'index de la feuille de calcul à laquelle ajouter le filigrane. |

### Remarques

**Apprendre encore plus:**

* [Ajouter des filigranes aux feuilles de calcul](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+spreadsheet+documents)

### Exemples

Ajouter un filigrane de texte dans l'en-tête de la feuille de calcul Excel.

```csharp
SpreadsheetLoadOptions loadOptions = new SpreadsheetLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\test.xls", loadOptions))
{
    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 14));

    SpreadsheetWatermarkHeaderFooterOptions options = new SpreadsheetWatermarkHeaderFooterOptions();
    options.WorksheetIndex = 0;

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### Voir également

* class [SpreadsheetWatermarkOptions](../spreadsheetwatermarkoptions)
* espace de noms [GroupDocs.Watermark.Options.Spreadsheet](../../groupdocs.watermark.options.spreadsheet)
* Assemblée [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->