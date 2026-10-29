---
title: "EmailContent"
second_title: "GroupDocs.Watermark pour .NET Référence de l'API"
description: "Représente un message électronique."
type: docs
weight: 360
url: /fr/net/groupdocs.watermark.contents.email/emailcontent/
---
## EmailContent class

Représente un message électronique.

```csharp
public sealed class EmailContent : Content
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Attachments](../../groupdocs.watermark.contents.email/emailcontent/attachments) { get; } | Obtient la collection de toutes les pièces jointes du message électronique. |
| [Bcc](../../groupdocs.watermark.contents.email/emailcontent/bcc) { get; } | Obtient la collection des destinataires CCI (copie carbone invisible) du message électronique. |
| [Body](../../groupdocs.watermark.contents.email/emailcontent/body) { get; set; } | Obtient ou définit la représentation en texte brut du corps du message. |
| [BodyType](../../groupdocs.watermark.contents.email/emailcontent/bodytype) { get; } | Obtient le type du corps du message électronique. |
| [Cc](../../groupdocs.watermark.contents.email/emailcontent/cc) { get; } | Obtient la collection des destinataires CC (copie carbone) du message électronique. |
| [EmbeddedObjects](../../groupdocs.watermark.contents.email/emailcontent/embeddedobjects) { get; } | Obtient la collection de tous les objets intégrés du message électronique. |
| [From](../../groupdocs.watermark.contents.email/emailcontent/from) { get; } | Obtient l'adresse d'expéditeur du message électronique. |
| [HtmlBody](../../groupdocs.watermark.contents.email/emailcontent/htmlbody) { get; set; } | Obtient ou définit la représentation HTML du corps du message. |
| [Subject](../../groupdocs.watermark.contents.email/emailcontent/subject) { get; set; } | Obtient ou définit l'objet du message électronique. |
| [To](../../groupdocs.watermark.contents.email/emailcontent/to) { get; } | Obtient la collection des destinataires du message électronique. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Dispose](../../groupdocs.watermark.contents/content/dispose)() | Libère l'instance actuelle. |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | Trouve toutes les images dans le contenu. La recherche est effectuée dans les objets spécifiés dans [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | Trouve les images selon les critères de recherche spécifiés. La recherche est effectuée dans les objets spécifiés dans [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | Trouve tous les filigranes possibles dans le contenu. La recherche est effectuée dans les objets spécifiés dans [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | Trouve les filigranes possibles selon les critères de recherche spécifiés. La recherche est effectuée dans les objets spécifiés dans [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |

### Remarques

**Learn more:**

* [Add watermarks to email attachments](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+email+attachments)
* [Email attachments](https://docs.groupdocs.com/display/watermarknet/Email+attachments)
* [Email messages](https://docs.groupdocs.com/display/watermarknet/Email+messages)

### Voir aussi

* class [Content](../../groupdocs.watermark.contents/content)
* namespace [GroupDocs.Watermark.Contents.Email](../../groupdocs.watermark.contents.email)
* assembly [GroupDocs.Watermark](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.watermark.dll -->
