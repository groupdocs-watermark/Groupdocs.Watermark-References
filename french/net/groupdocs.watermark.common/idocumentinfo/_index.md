---
title: "IDocumentInfo"
second_title: "GroupDocs.Watermark pour .NET Référence de l'API"
description: "Définit les méthodes requises pour obtenir les informations de base du document."
type: docs
weight: 70
url: /fr/net/groupdocs.watermark.common/idocumentinfo/
---
## IDocumentInfo interface

Définit les méthodes requises pour obtenir les informations de base du document.

```csharp
public interface IDocumentInfo
```

## Propriétés

| Nom | Description |
| --- | --- |
| [FileType](../../groupdocs.watermark.common/idocumentinfo/filetype) { get; } | Obtient la description du format de fichier. |
| [IsEncrypted](../../groupdocs.watermark.common/idocumentinfo/isencrypted) { get; } | Obtient une valeur indiquant si le document est chiffré et nécessite un mot de passe pour l'ouvrir. |
| [PageCount](../../groupdocs.watermark.common/idocumentinfo/pagecount) { get; } | Obtient le nombre total de pages. |
| [Pages](../../groupdocs.watermark.common/idocumentinfo/pages) { get; } | Obtient la collection des descriptions des pages du document. |
| [Size](../../groupdocs.watermark.common/idocumentinfo/size) { get; } | Obtient la taille du document en octets. |

### Remarques

**Learn more**

* [Get document info](https://docs.groupdocs.com/display/watermarknet/Get+document+info)

### Exemples

L'exemple suivant montre comment récupérer les informations générales du document en utilisant [`IDocumentInfo`](../idocumentinfo).

```csharp
using (Watermarker watermarker = new Watermarker("D:\\input.pdf"))
{
    IDocumentInfo docInfo = watermarker.GetDocumentInfo();
    Console.WriteLine("Document size: {0}", docInfo.Size);
    Console.WriteLine("Document format: {0}", docInfo.FileType.FileFormat);
    Console.WriteLine("Document contains {0} pages", docInfo.PageCount);
}
```

### Voir aussi

* namespace [GroupDocs.Watermark.Common](../../groupdocs.watermark.common)
* assembly [GroupDocs.Watermark](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.watermark.dll -->
