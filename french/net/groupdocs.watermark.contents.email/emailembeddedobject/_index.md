---
title: EmailEmbeddedObject
second_title: Référence de l'API GroupDocs.Watermark pour .NET
description: Représente un objet intégré au corps dun message électronique.
type: docs
weight: 340
url: /fr/net/groupdocs.watermark.contents.email/emailembeddedobject/
---
## EmailEmbeddedObject class

Représente un objet intégré au corps d'un message électronique.

```csharp
public class EmailEmbeddedObject : EmailAttachmentBase
```

## Propriétés

| Nom | La description |
| --- | --- |
| override [Content](../../groupdocs.watermark.contents.email/emailattachmentbase/content) { get; set; } | Obtient ou définit le contenu du fichier joint. |
| [ContentId](../../groupdocs.watermark.contents.email/emailattachmentbase/contentid) { get; } | Obtient l'identifiant de contenu de ceci[`EmailAttachmentBase`](../emailattachmentbase) . |
| [MediaType](../../groupdocs.watermark.contents.email/emailattachmentbase/mediatype) { get; } | Obtient le type de média de ce[`EmailAttachmentBase`](../emailattachmentbase) . |

## Méthodes

| Nom | La description |
| --- | --- |
| [CreateWatermarker](../../groupdocs.watermark.common/attachment/createwatermarker)() | Charge un contenu à partir du fichier joint. |
| [CreateWatermarker](../../groupdocs.watermark.common/attachment/createwatermarker)(LoadOptions) | Charge un contenu à partir du fichier joint avec les options de chargement spécifiées. |
| [CreateWatermarker](../../groupdocs.watermark.common/attachment/createwatermarker)(LoadOptions, WatermarkerSettings) | Charge un contenu à partir du fichier joint avec les options de chargement et les paramètres spécifiés. |
| [GetDocumentInfo](../../groupdocs.watermark.common/attachment/getdocumentinfo)() | Obtient les informations sur un document stocké dans le fichier joint. |

### Voir également

* class [EmailAttachmentBase](../emailattachmentbase)
* espace de noms [GroupDocs.Watermark.Contents.Email](../../groupdocs.watermark.contents.email)
* Assemblée [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->