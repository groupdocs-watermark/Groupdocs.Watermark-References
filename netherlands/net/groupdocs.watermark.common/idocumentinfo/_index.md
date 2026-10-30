---
title: "IDocumentInfo"
second_title: "GroupDocs.Watermark voor .NET API-referentie"
description: "Definieert de methoden die vereist zijn om de basisdocumentinformatie op te halen."
type: docs
weight: 70
url: /nl/net/groupdocs.watermark.common/idocumentinfo/
---
## IDocumentInfo interface

Definieert de methoden die vereist zijn om de basisdocumentinformatie op te halen.

```csharp
public interface IDocumentInfo
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [FileType](../../groupdocs.watermark.common/idocumentinfo/filetype) { get; } | Haalt de bestandsformaatbeschrijving op. |
| [IsEncrypted](../../groupdocs.watermark.common/idocumentinfo/isencrypted) { get; } | Haalt een waarde op die aangeeft of het document versleuteld is en een wachtwoord vereist om te openen. |
| [PageCount](../../groupdocs.watermark.common/idocumentinfo/pagecount) { get; } | Haalt het totale aantal pagina's op. |
| [Pages](../../groupdocs.watermark.common/idocumentinfo/pages) { get; } | Haalt de collectie van paginabeschrijvingen van het document op. |
| [Size](../../groupdocs.watermark.common/idocumentinfo/size) { get; } | Haalt de documentgrootte in bytes op. |

### Opmerkingen

**Learn more**

* [Get document info](https://docs.groupdocs.com/display/watermarknet/Get+document+info)

### Voorbeelden

Het volgende voorbeeld laat zien hoe de algemene documentinformatie opgehaald kan worden met behulp van [`IDocumentInfo`](../idocumentinfo).

```csharp
using (Watermarker watermarker = new Watermarker("D:\\input.pdf"))
{
    IDocumentInfo docInfo = watermarker.GetDocumentInfo();
    Console.WriteLine("Document size: {0}", docInfo.Size);
    Console.WriteLine("Document format: {0}", docInfo.FileType.FileFormat);
    Console.WriteLine("Document contains {0} pages", docInfo.PageCount);
}
```

### Zie ook

* namespace [GroupDocs.Watermark.Common](../../groupdocs.watermark.common)
* assembly [GroupDocs.Watermark](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.watermark.dll -->
