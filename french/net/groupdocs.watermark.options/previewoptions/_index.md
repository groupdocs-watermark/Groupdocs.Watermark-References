---
title: "PreviewOptions"
second_title: "GroupDocs.Watermark pour .NET Référence de l'API"
description: "Fournit des options pour définir les exigences et les délégués de flux pour la génération d'aperçu."
type: docs
weight: 2140
url: /fr/net/groupdocs.watermark.options/previewoptions/
---
## PreviewOptions class

Fournit des options pour définir les exigences et les délégués de flux pour la génération d'aperçu.

```csharp
public class PreviewOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [PreviewOptions](previewoptions#constructor)(CreatePageStream) | Initialise une nouvelle instance de la classe [`PreviewOptions`](../previewoptions) entraînant la fermeture du flux de sortie. |
| [PreviewOptions](previewoptions#constructor_1)(CreatePageStream, ReleasePageStream) | Initialise une nouvelle instance de la classe [`PreviewOptions`](../previewoptions) entraînant le retour du flux de sortie au client pour une utilisation ultérieure. |

## Propriétés

| Nom | Description |
| --- | --- |
| [CreatePageStream](../../groupdocs.watermark.options/previewoptions/createpagestream) { get; set; } | Obtient ou définit une instance du délégué de création du flux de page. |
| [Height](../../groupdocs.watermark.options/previewoptions/height) { get; set; } | Obtient ou définit la hauteur de l'aperçu de la page. |
| [PageNumbers](../../groupdocs.watermark.options/previewoptions/pagenumbers) { get; set; } | Obtient ou définit un tableau de numéros de page pour générer des aperçus. |
| [PreviewFormat](../../groupdocs.watermark.options/previewoptions/previewformat) { get; set; } | Obtient ou définit le format de l'image d'aperçu. |
| [ReleasePageStream](../../groupdocs.watermark.options/previewoptions/releasepagestream) { get; set; } | Obtient ou définit une instance du délégué de fin de prévisualisation de page. |
| [Width](../../groupdocs.watermark.options/previewoptions/width) { get; set; } | Obtient ou définit la largeur de l'aperçu de page. |

### Voir aussi

* namespace [GroupDocs.Watermark.Options](../../groupdocs.watermark.options)
* assembly [GroupDocs.Watermark](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.watermark.dll -->
