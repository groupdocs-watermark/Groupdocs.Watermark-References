---
title: "GetDocumentInfo"
second_title: "GroupDocs.Watermark für .NET API-Referenz"
description: "Liest die Informationen über das Format des geladenen Dokuments."
type: docs
weight: 70
url: /de/net/groupdocs.watermark/watermarker/getdocumentinfo/
---
## Watermarker.GetDocumentInfo method

Liest die Informationen über das Format des geladenen Dokuments.

```csharp
public IDocumentInfo GetDocumentInfo()
```

### Rückgabewert

Die [`IDocumentInfo`](../../../groupdocs.watermark.common/idocumentinfo)-Instanz, die erkannte Informationen enthält.

### Hinweise

Erfahren Sie mehr über das Abrufen von Dokumentinformationen [Dokumentinformationen abrufen](https://docs.groupdocs.com/display/watermarknet/Get+document+info).

### Beispiele

Rufen Sie Informationen zu einem Dokument eines beliebigen unterstützten Typs ab.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\test.ppt"))
{
    IDocumentInfo docInfo = watermarker.GetDocumentInfo();
    Console.WriteLine("Document size: {0}", docInfo.Size);
    Console.WriteLine("Document format: {0}", docInfo.FileType.FileFormat);
    Console.WriteLine("Document contains {0} pages", docInfo.PageCount);
}
```

### Siehe auch

* interface [IDocumentInfo](../../../groupdocs.watermark.common/idocumentinfo)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.watermark.dll -->
