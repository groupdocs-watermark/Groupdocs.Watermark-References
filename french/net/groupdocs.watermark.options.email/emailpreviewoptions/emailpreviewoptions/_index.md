---
title: "EmailPreviewOptions"
second_title: "GroupDocs.Watermark pour .NET Référence de l'API"
description: "Initialise une nouvelle instance de la classe EmailPreviewOptionsgroupdocs.watermark.options.email/emailpreviewoptions entraînant la fermeture du flux de sortie."
type: docs
weight: 10
url: /fr/net/groupdocs.watermark.options.email/emailpreviewoptions/emailpreviewoptions/
---
## EmailPreviewOptions(CreatePageStream) {#constructor}

Initialise une nouvelle instance de la classe [`EmailPreviewOptions`](../../emailpreviewoptions) entraînant la fermeture du flux de sortie.

```csharp
public EmailPreviewOptions(CreatePageStream createPageStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| createPageStream | CreatePageStream | Crée un flux pour un aperçu de page spécifique. |

### Voir aussi

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* class [EmailPreviewOptions](../../emailpreviewoptions)
* namespace [GroupDocs.Watermark.Options.Email](../../../groupdocs.watermark.options.email)
* assembly [GroupDocs.Watermark](../../../)

---

## EmailPreviewOptions(CreatePageStream, ReleasePageStream) {#constructor_1}

Initialise une nouvelle instance de la classe [`EmailPreviewOptions`](../../emailpreviewoptions) entraînant le renvoi du flux de sortie au client pour une utilisation ultérieure.

```csharp
public EmailPreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| createPageStream | CreatePageStream | Crée un flux pour un aperçu de page spécifique. |
| releasePageStream | ReleasePageStream | Notifie que la génération de l'aperçu de page est terminée et récupère le flux de sortie. |

### Voir aussi

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.watermark.options/releasepagestream)
* class [EmailPreviewOptions](../../emailpreviewoptions)
* namespace [GroupDocs.Watermark.Options.Email](../../../groupdocs.watermark.options.email)
* assembly [GroupDocs.Watermark](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.watermark.dll -->
