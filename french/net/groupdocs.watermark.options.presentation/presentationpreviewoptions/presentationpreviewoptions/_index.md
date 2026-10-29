---
title: "PresentationPreviewOptions"
second_title: "GroupDocs.Watermark pour .NET Référence de l'API"
description: "Initialise une nouvelle instance de la classe PresentationPreviewOptionsgroupdocs.watermark.options.presentation/presentationpreviewoptions en fermant le flux de sortie."
type: docs
weight: 10
url: /fr/net/groupdocs.watermark.options.presentation/presentationpreviewoptions/presentationpreviewoptions/
---
## PresentationPreviewOptions(CreatePageStream) {#constructor}

Initialise une nouvelle instance de la classe [`PresentationPreviewOptions`](../../presentationpreviewoptions) en fermant le flux de sortie.

```csharp
public PresentationPreviewOptions(CreatePageStream createPageStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| createPageStream | CreatePageStream | Crée un flux pour un aperçu de page spécifique. |

### Voir aussi

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* class [PresentationPreviewOptions](../../presentationpreviewoptions)
* namespace [GroupDocs.Watermark.Options.Presentation](../../../groupdocs.watermark.options.presentation)
* assembly [GroupDocs.Watermark](../../../)

---

## PresentationPreviewOptions(CreatePageStream, ReleasePageStream) {#constructor_1}

Initialise une nouvelle instance de la classe [`PresentationPreviewOptions`](../../presentationpreviewoptions) en renvoyant le flux de sortie au client pour une utilisation ultérieure.

```csharp
public PresentationPreviewOptions(CreatePageStream createPageStream, 
    ReleasePageStream releasePageStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| createPageStream | CreatePageStream | Crée un flux pour un aperçu de page spécifique. |
| releasePageStream | ReleasePageStream | Notifie que la génération de l'aperçu de page est terminée et récupère le flux de sortie. |

### Voir aussi

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.watermark.options/releasepagestream)
* class [PresentationPreviewOptions](../../presentationpreviewoptions)
* namespace [GroupDocs.Watermark.Options.Presentation](../../../groupdocs.watermark.options.presentation)
* assembly [GroupDocs.Watermark](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.watermark.dll -->
