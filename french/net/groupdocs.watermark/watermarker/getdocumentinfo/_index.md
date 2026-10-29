---
title: "GetDocumentInfo"
second_title: "GroupDocs.Watermark pour .NET Référence de l'API"
description: "Obtient les informations sur le format du document chargé."
type: docs
weight: 70
url: /fr/net/groupdocs.watermark/watermarker/getdocumentinfo/
---
## Watermarker.GetDocumentInfo method

Obtient les informations sur le format du document chargé.

```csharp
public IDocumentInfo GetDocumentInfo()
```

### Valeur de retour

L'instance [`IDocumentInfo`](../../../groupdocs.watermark.common/idocumentinfo) qui contient les informations détectées.

### Remarques

En savoir plus sur l'obtention des informations du document [Obtenir les informations du document](https://docs.groupdocs.com/display/watermarknet/Get+document+info).

### Exemples

Obtenir des informations sur un document de tout type pris en charge.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\test.ppt"))
{
    IDocumentInfo docInfo = watermarker.GetDocumentInfo();
    Console.WriteLine("Document size: {0}", docInfo.Size);
    Console.WriteLine("Document format: {0}", docInfo.FileType.FileFormat);
    Console.WriteLine("Document contains {0} pages", docInfo.PageCount);
}
```

### Voir aussi

* interface [IDocumentInfo](../../../groupdocs.watermark.common/idocumentinfo)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.watermark.dll -->
