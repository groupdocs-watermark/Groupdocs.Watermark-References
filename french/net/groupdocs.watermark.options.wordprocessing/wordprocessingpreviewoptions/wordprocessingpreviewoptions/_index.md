---
title: "WordProcessingPreviewOptions"
second_title: "GroupDocs.Watermark pour .NET Référence de l'API"
description: "Initialise une nouvelle instance de la classe WordProcessingPreviewOptionsgroupdocs.watermark.options.wordprocessing/wordprocessingpreviewoptions, provoquant la fermeture du flux de sortie."
type: docs
weight: 10
url: /fr/net/groupdocs.watermark.options.wordprocessing/wordprocessingpreviewoptions/wordprocessingpreviewoptions/
---
## WordProcessingPreviewOptions(CreatePageStream) {#constructor}

Initialise une nouvelle instance de la classe [`WordProcessingPreviewOptions`](../../wordprocessingpreviewoptions) provoquant la fermeture du flux de sortie.

```csharp
public WordProcessingPreviewOptions(CreatePageStream createPageStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| createPageStream | CreatePageStream | Crée un flux pour un aperçu de page spécifique. |

### Voir aussi

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* class [WordProcessingPreviewOptions](../../wordprocessingpreviewoptions)
* namespace [GroupDocs.Watermark.Options.WordProcessing](../../../groupdocs.watermark.options.wordprocessing)
* assembly [GroupDocs.Watermark](../../../)

---

## WordProcessingPreviewOptions(CreatePageStream, ReleasePageStream) {#constructor_1}

Initialise une nouvelle instance de la classe [`WordProcessingPreviewOptions`](../../wordprocessingpreviewoptions) provoquant le renvoi du flux de sortie au client pour une utilisation ultérieure.

```csharp
public WordProcessingPreviewOptions(CreatePageStream createPageStream, 
    ReleasePageStream releasePageStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| createPageStream | CreatePageStream | Crée un flux pour un aperçu de page spécifique. |
| releasePageStream | ReleasePageStream | Notifie que la génération de l'aperçu de page est terminée et récupère le flux de sortie. |

### Voir aussi

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.watermark.options/releasepagestream)
* class [WordProcessingPreviewOptions](../../wordprocessingpreviewoptions)
* namespace [GroupDocs.Watermark.Options.WordProcessing](../../../groupdocs.watermark.options.wordprocessing)
* assembly [GroupDocs.Watermark](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.watermark.dll -->
