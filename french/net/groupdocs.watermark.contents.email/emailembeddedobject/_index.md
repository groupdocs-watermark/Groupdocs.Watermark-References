---
title: "EmailEmbeddedObject"
second_title: "GroupDocs.Watermark pour .NET Référence de l'API"
description: "Représente un objet intégré au corps d'un message électronique."
type: docs
weight: 370
url: /fr/net/groupdocs.watermark.contents.email/emailembeddedobject/
---
## EmailEmbeddedObject class

Représente un objet intégré au corps d'un message électronique.

```csharp
public class EmailEmbeddedObject : EmailAttachmentBase
```

## Propriétés

| Nom | Description |
| --- | --- |
| override [Content](../../groupdocs.watermark.contents.email/emailattachmentbase/content) { get; set; } | Obtient ou définit le contenu du fichier joint. |
| [ContentId](../../groupdocs.watermark.contents.email/emailattachmentbase/contentid) { get; } | Obtient l'identifiant de contenu de cet [`EmailAttachmentBase`](../emailattachmentbase). |
| [MediaType](../../groupdocs.watermark.contents.email/emailattachmentbase/mediatype) { get; } | Obtient le type de média de cet [`EmailAttachmentBase`](../emailattachmentbase). |

## Méthodes

| Nom | Description |
| --- | --- |
| [CreateWatermarker](../../groupdocs.watermark.common/attachment/createwatermarker)() | Charge un contenu depuis le fichier joint. |
| [CreateWatermarker](../../groupdocs.watermark.common/attachment/createwatermarker)(LoadOptions) | Charge un contenu depuis le fichier joint avec les options de chargement spécifiées. |
| [CreateWatermarker](../../groupdocs.watermark.common/attachment/createwatermarker)(LoadOptions, WatermarkerSettings) | Charge un contenu depuis le fichier joint avec les options de chargement et les paramètres spécifiés. |
| [GetDocumentInfo](../../groupdocs.watermark.common/attachment/getdocumentinfo)() | Obtient les informations sur un document stocké dans le fichier joint. |

### Voir aussi

* class [EmailAttachmentBase](../emailattachmentbase)
* namespace [GroupDocs.Watermark.Contents.Email](../../groupdocs.watermark.contents.email)
* assembly [GroupDocs.Watermark](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.watermark.dll -->
