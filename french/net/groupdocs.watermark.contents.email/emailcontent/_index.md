---
title: EmailContent
second_title: Référence de l'API GroupDocs.Watermark pour .NET
description: Représente un email.
type: docs
weight: 330
url: /fr/net/groupdocs.watermark.contents.email/emailcontent/
---
## EmailContent class

Représente un e-mail.

```csharp
public sealed class EmailContent : Content
```

## Propriétés

| Nom | La description |
| --- | --- |
| [Attachments](../../groupdocs.watermark.contents.email/emailcontent/attachments) { get; } | Obtient la collection de toutes les pièces jointes du message électronique. |
| [Bcc](../../groupdocs.watermark.contents.email/emailcontent/bcc) { get; } | Obtient la collection de destinataires BCC (copie carbone invisible) du message électronique. |
| [Body](../../groupdocs.watermark.contents.email/emailcontent/body) { get; set; } | Obtient ou définit la représentation en texte brut du corps du message. |
| [BodyType](../../groupdocs.watermark.contents.email/emailcontent/bodytype) { get; } | Obtient le type du corps du message électronique. |
| [Cc](../../groupdocs.watermark.contents.email/emailcontent/cc) { get; } | Obtient la collection de destinataires CC (copie carbone) du message électronique. |
| [EmbeddedObjects](../../groupdocs.watermark.contents.email/emailcontent/embeddedobjects) { get; } | Obtient la collection de tous les objets incorporés du message électronique. |
| [From](../../groupdocs.watermark.contents.email/emailcontent/from) { get; } | Obtient l'adresse de l'e-mail. |
| [HtmlBody](../../groupdocs.watermark.contents.email/emailcontent/htmlbody) { get; set; } | Obtient ou définit la représentation HTML du corps du message. |
| [Subject](../../groupdocs.watermark.contents.email/emailcontent/subject) { get; set; } | Obtient ou définit l'objet du message électronique. |
| [To](../../groupdocs.watermark.contents.email/emailcontent/to) { get; } | Obtient la collection de destinataires du message électronique. |

## Méthodes

| Nom | La description |
| --- | --- |
| [Dispose](../../groupdocs.watermark.contents/content/dispose)() | Supprime l'instance actuelle. |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | Recherche toutes les images dans le contenu. La recherche est effectuée dans les objets spécifiés dans[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) . |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | Trouve des images selon les critères de recherche spécifiés. La recherche est effectuée dans les objets spécifiés dans[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) . |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | Recherche tous les filigranes possibles dans le contenu. La recherche est effectuée dans les objets spécifiés dans[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) . |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | Trouve les filigranes possibles selon les critères de recherche spécifiés. La recherche est effectuée dans les objets spécifiés dans[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) . |

### Remarques

**Apprendre encore plus:**

* [Ajouter des filigranes aux pièces jointes des e-mails](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+email+attachments)
* [Pièces jointes aux e-mails](https://docs.groupdocs.com/display/watermarknet/Email+attachments)
* [E-mails](https://docs.groupdocs.com/display/watermarknet/Email+messages)

### Voir également

* class [Content](../../groupdocs.watermark.contents/content)
* espace de noms [GroupDocs.Watermark.Contents.Email](../../groupdocs.watermark.contents.email)
* Assemblée [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
