---
title: "DiagramPreviewOptions"
second_title: "GroupDocs.Watermark pour .NET Référence de l'API"
description: "Initialise une nouvelle instance de la classe DiagramPreviewOptionsgroupdocs.watermark.options.diagram/diagrampreviewoptions entraînant la fermeture du flux de sortie."
type: docs
weight: 10
url: /fr/net/groupdocs.watermark.options.diagram/diagrampreviewoptions/diagrampreviewoptions/
---
## DiagramPreviewOptions(CreatePageStream) {#constructor}

Initialise une nouvelle instance de la classe [`DiagramPreviewOptions`](../../diagrampreviewoptions) entraînant la fermeture du flux de sortie.

```csharp
public DiagramPreviewOptions(CreatePageStream createPageStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| createPageStream | CreatePageStream | Crée un flux pour un aperçu de page spécifique. |

### Voir aussi

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* class [DiagramPreviewOptions](../../diagrampreviewoptions)
* namespace [GroupDocs.Watermark.Options.Diagram](../../../groupdocs.watermark.options.diagram)
* assembly [GroupDocs.Watermark](../../../)

---

## DiagramPreviewOptions(CreatePageStream, ReleasePageStream) {#constructor_1}

Initialise une nouvelle instance de la classe [`DiagramPreviewOptions`](../../diagrampreviewoptions) entraînant le retour du flux de sortie au client pour une utilisation ultérieure.

```csharp
public DiagramPreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| createPageStream | CreatePageStream | Crée un flux pour un aperçu de page spécifique. |
| releasePageStream | ReleasePageStream | Notifie que la génération de l'aperçu de page est terminée et récupère le flux de sortie. |

### Voir aussi

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.watermark.options/releasepagestream)
* class [DiagramPreviewOptions](../../diagrampreviewoptions)
* namespace [GroupDocs.Watermark.Options.Diagram](../../../groupdocs.watermark.options.diagram)
* assembly [GroupDocs.Watermark](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.watermark.dll -->
