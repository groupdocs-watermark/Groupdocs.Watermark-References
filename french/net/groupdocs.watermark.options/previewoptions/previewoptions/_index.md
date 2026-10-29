---
title: "PreviewOptions"
second_title: "GroupDocs.Watermark pour .NET Référence de l'API"
description: "Initialise une nouvelle instance de la classe PreviewOptionsgroupdocs.watermark.options/previewoptions entraînant la fermeture du flux de sortie."
type: docs
weight: 10
url: /fr/net/groupdocs.watermark.options/previewoptions/previewoptions/
---
## PreviewOptions(CreatePageStream) {#constructor}

Initialise une nouvelle instance de la classe [`PreviewOptions`](../../previewoptions) entraînant la fermeture du flux de sortie.

```csharp
public PreviewOptions(CreatePageStream createPageStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| createPageStream | CreatePageStream | Crée un flux pour un aperçu de page spécifique. |

### Voir aussi

* delegate [CreatePageStream](../../createpagestream)
* class [PreviewOptions](../../previewoptions)
* namespace [GroupDocs.Watermark.Options](../../../groupdocs.watermark.options)
* assembly [GroupDocs.Watermark](../../../)

---

## PreviewOptions(CreatePageStream, ReleasePageStream) {#constructor_1}

Initialise une nouvelle instance de la classe [`PreviewOptions`](../../previewoptions) entraînant le retour du flux de sortie au client pour une utilisation ultérieure.

```csharp
public PreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| createPageStream | CreatePageStream | Crée un flux pour un aperçu de page spécifique. |
| releasePageStream | ReleasePageStream | Notifie que la génération de l'aperçu de page est terminée et récupère le flux de sortie. |

### Voir aussi

* delegate [CreatePageStream](../../createpagestream)
* delegate [ReleasePageStream](../../releasepagestream)
* class [PreviewOptions](../../previewoptions)
* namespace [GroupDocs.Watermark.Options](../../../groupdocs.watermark.options)
* assembly [GroupDocs.Watermark](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.watermark.dll -->
