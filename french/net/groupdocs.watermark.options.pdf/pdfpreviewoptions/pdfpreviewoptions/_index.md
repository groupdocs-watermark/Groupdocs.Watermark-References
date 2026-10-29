---
title: "PdfPreviewOptions"
second_title: "GroupDocs.Watermark pour .NET Référence de l'API"
description: "Initialise une nouvelle instance de la classe PdfPreviewOptionsgroupdocs.watermark.options.pdf/pdfpreviewoptions provoquant la fermeture du flux de sortie."
type: docs
weight: 10
url: /fr/net/groupdocs.watermark.options.pdf/pdfpreviewoptions/pdfpreviewoptions/
---
## PdfPreviewOptions(CreatePageStream) {#constructor}

Initialise une nouvelle instance de la classe [`PdfPreviewOptions`](../../pdfpreviewoptions) provoquant la fermeture du flux de sortie.

```csharp
public PdfPreviewOptions(CreatePageStream createPageStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| createPageStream | CreatePageStream | Crée un flux pour un aperçu de page spécifique. |

### Voir aussi

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* class [PdfPreviewOptions](../../pdfpreviewoptions)
* namespace [GroupDocs.Watermark.Options.Pdf](../../../groupdocs.watermark.options.pdf)
* assembly [GroupDocs.Watermark](../../../)

---

## PdfPreviewOptions(CreatePageStream, ReleasePageStream) {#constructor_1}

Initialise une nouvelle instance de la classe [`PdfPreviewOptions`](../../pdfpreviewoptions) provoquant le retour du flux de sortie au client pour une utilisation ultérieure.

```csharp
public PdfPreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| createPageStream | CreatePageStream | Crée un flux pour un aperçu de page spécifique. |
| releasePageStream | ReleasePageStream | Notifie que la génération de l'aperçu de page est terminée et récupère le flux de sortie. |

### Voir aussi

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.watermark.options/releasepagestream)
* class [PdfPreviewOptions](../../pdfpreviewoptions)
* namespace [GroupDocs.Watermark.Options.Pdf](../../../groupdocs.watermark.options.pdf)
* assembly [GroupDocs.Watermark](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.watermark.dll -->
