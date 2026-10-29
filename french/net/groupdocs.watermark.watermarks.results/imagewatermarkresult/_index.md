---
title: "ImageWatermarkResult"
second_title: "GroupDocs.Watermark pour .NET Référence de l'API"
description: "Contient les propriétés du filigrane d'image."
type: docs
weight: 3260
url: /fr/net/groupdocs.watermark.watermarks.results/imagewatermarkresult/
---
## ImageWatermarkResult class

Contient les propriétés du filigrane d'image.

```csharp
public class ImageWatermarkResult : BaseWatermarkResult
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [ImageWatermarkResult](imagewatermarkresult)(string) | Initialise l'objet ImageWatermarkResult avec l'identifiant du filigrane obtenu après le processus de recherche. Cet identifiant unique est utilisé pour trouver des propriétés supplémentaires pour ce filigrane à partir de la couche d'informations de filigrane du document. |

## Propriétés

| Nom | Description |
| --- | --- |
| [CreatedOn](../../groupdocs.watermark.watermarks.results/basewatermarkresult/createdon) { get; set; } | Obtient ou définit la date de création du filigrane. |
| [Height](../../groupdocs.watermark.watermarks.results/basewatermarkresult/height) { get; set; } | Spécifie la hauteur du filigrane. |
| [Left](../../groupdocs.watermark.watermarks.results/basewatermarkresult/left) { get; set; } | Spécifie la position gauche du filigrane. |
| [ModifiedOn](../../groupdocs.watermark.watermarks.results/basewatermarkresult/modifiedon) { get; set; } | Obtient ou définit la date de modification du filigrane. |
| [PageNumber](../../groupdocs.watermark.watermarks.results/basewatermarkresult/pagenumber) { get; } | Spécifie la page sur laquelle le filigrane a été placé. |
| [Size](../../groupdocs.watermark.watermarks.results/imagewatermarkresult/size) { get; } | Spécifie la taille en octets de l'image du filigrane. |
| [Top](../../groupdocs.watermark.watermarks.results/basewatermarkresult/top) { get; set; } | Spécifie la position supérieure du filigrane. |
| [WatermarkId](../../groupdocs.watermark.watermarks.results/basewatermarkresult/watermarkid) { get; } | Identifiant unique du filigrane pour modifier le filigrane dans le document via les méthodes Update ou Delete. Cette propriété sera définie automatiquement après l'appel de la méthode Add. Si cette propriété a été enregistrée auparavant, elle peut être définie manuellement pour manipuler le filigrane. |
| [WatermarkPosition](../../groupdocs.watermark.watermarks.results/basewatermarkresult/watermarkposition) { get; } | Spécifie la position du filigrane |
| [WatermarkType](../../groupdocs.watermark.watermarks.results/basewatermarkresult/watermarktype) { get; } | Spécifie le type de filigrane. |
| [Width](../../groupdocs.watermark.watermarks.results/basewatermarkresult/width) { get; set; } | Spécifie la largeur du filigrane. |

### Voir aussi

* class [BaseWatermarkResult](../basewatermarkresult)
* namespace [GroupDocs.Watermark.Watermarks.Results](../../groupdocs.watermark.watermarks.results)
* assembly [GroupDocs.Watermark](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.watermark.dll -->
