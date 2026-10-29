---
title: "SpreadsheetPreviewOptions"
second_title: "GroupDocs.Watermark pour .NET Référence de l'API"
description: "Initialise une nouvelle instance de la classe SpreadsheetPreviewOptionsgroupdocs.watermark.options.spreadsheet/spreadsheetpreviewoptions entraînant la fermeture du flux de sortie."
type: docs
weight: 10
url: /fr/net/groupdocs.watermark.options.spreadsheet/spreadsheetpreviewoptions/spreadsheetpreviewoptions/
---
## SpreadsheetPreviewOptions(CreatePageStream) {#constructor}

Initialise une nouvelle instance de la classe [`SpreadsheetPreviewOptions`](../../spreadsheetpreviewoptions) entraînant la fermeture du flux de sortie.

```csharp
public SpreadsheetPreviewOptions(CreatePageStream createPageStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| createPageStream | CreatePageStream | Crée un flux pour un aperçu de page spécifique. |

### Voir aussi

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* class [SpreadsheetPreviewOptions](../../spreadsheetpreviewoptions)
* namespace [GroupDocs.Watermark.Options.Spreadsheet](../../../groupdocs.watermark.options.spreadsheet)
* assembly [GroupDocs.Watermark](../../../)

---

## SpreadsheetPreviewOptions(CreatePageStream, ReleasePageStream) {#constructor_1}

Initialise une nouvelle instance de la classe [`SpreadsheetPreviewOptions`](../../spreadsheetpreviewoptions) entraînant le retour du flux de sortie au client pour une utilisation ultérieure.

```csharp
public SpreadsheetPreviewOptions(CreatePageStream createPageStream, 
    ReleasePageStream releasePageStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| createPageStream | CreatePageStream | Crée un flux pour un aperçu de page spécifique. |
| releasePageStream | ReleasePageStream | Notifie que la génération de l'aperçu de page est terminée et récupère le flux de sortie. |

### Voir aussi

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.watermark.options/releasepagestream)
* class [SpreadsheetPreviewOptions](../../spreadsheetpreviewoptions)
* namespace [GroupDocs.Watermark.Options.Spreadsheet](../../../groupdocs.watermark.options.spreadsheet)
* assembly [GroupDocs.Watermark](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.watermark.dll -->
