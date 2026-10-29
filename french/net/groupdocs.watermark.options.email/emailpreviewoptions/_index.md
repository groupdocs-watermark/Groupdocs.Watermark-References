---
title: "EmailPreviewOptions"
second_title: "GroupDocs.Watermark pour .NET Référence de l'API"
description: "Fournit des options pour définir les exigences et les délégués de flux pour la génération d'aperçu du document Email."
type: docs
weight: 1780
url: /fr/net/groupdocs.watermark.options.email/emailpreviewoptions/
---
## EmailPreviewOptions class

Fournit des options pour définir les exigences et les délégués de flux pour la génération d'aperçu du document Email.

```csharp
public class EmailPreviewOptions : PreviewOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [EmailPreviewOptions](emailpreviewoptions#constructor)(CreatePageStream) | Initialise une nouvelle instance de la classe [`EmailPreviewOptions`](../emailpreviewoptions) provoquant la fermeture du flux de sortie. |
| [EmailPreviewOptions](emailpreviewoptions#constructor_1)(CreatePageStream, ReleasePageStream) | Initialise une nouvelle instance de la classe [`EmailPreviewOptions`](../emailpreviewoptions) provoquant le renvoi du flux de sortie au client pour une utilisation ultérieure. |

## Propriétés

| Nom | Description |
| --- | --- |
| [CreatePageStream](../../groupdocs.watermark.options/previewoptions/createpagestream) { get; set; } | Obtient ou définit une instance du délégué de création du flux de page. |
| [Height](../../groupdocs.watermark.options/previewoptions/height) { get; set; } | Obtient ou définit la hauteur de l'aperçu de la page. |
| [PageNumbers](../../groupdocs.watermark.options/previewoptions/pagenumbers) { get; set; } | Obtient ou définit un tableau de numéros de page pour générer des aperçus. |
| [PreviewFormat](../../groupdocs.watermark.options/previewoptions/previewformat) { get; set; } | Obtient ou définit le format de l'image d'aperçu. |
| [ReleasePageStream](../../groupdocs.watermark.options/previewoptions/releasepagestream) { get; set; } | Obtient ou définit une instance du délégué de fin de prévisualisation de page. |
| [Resolution](../../groupdocs.watermark.options.email/emailpreviewoptions/resolution) { get; set; } | Obtient ou définit la résolution des images générées, en points par pouce. |
| [Width](../../groupdocs.watermark.options/previewoptions/width) { get; set; } | Obtient ou définit la largeur de l'aperçu de page. |

## Champs

| Nom | Description |
| --- | --- |
| const [DefaultResolution](../../groupdocs.watermark.options.email/emailpreviewoptions/defaultresolution) | Résolution par défaut en points par pouce. |

### Voir aussi

* class [PreviewOptions](../../groupdocs.watermark.options/previewoptions)
* namespace [GroupDocs.Watermark.Options.Email](../../groupdocs.watermark.options.email)
* assembly [GroupDocs.Watermark](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.watermark.dll -->
