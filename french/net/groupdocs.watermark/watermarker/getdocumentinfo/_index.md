---
title: GetDocumentInfo
second_title: Référence de l'API GroupDocs.Watermark pour .NET
description: Obtient les informations sur le format du document chargé.
type: docs
weight: 70
url: /fr/net/groupdocs.watermark/watermarker/getdocumentinfo/
---
## Watermarker.GetDocumentInfo method

Obtient les informations sur le format du document chargé.

```csharp
public IDocumentInfo GetDocumentInfo()
```

### Return_Value

Le[`IDocumentInfo`](../../../groupdocs.watermark.common/idocumentinfo) instance qui contient des informations détectées.

### Remarques

En savoir plus sur l'obtention des informations sur le document [Obtenir des informations sur les documents](https://docs.groupdocs.com/display/watermarknet/Get+document+info) .

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

### Voir également

* interface [IDocumentInfo](../../../groupdocs.watermark.common/idocumentinfo)
* class [Watermarker](../../watermarker)
* espace de noms [GroupDocs.Watermark](../../watermarker)
* Assemblée [GroupDocs.Watermark](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->