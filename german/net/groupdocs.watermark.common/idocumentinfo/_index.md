---
title: "IDocumentInfo"
second_title: "GroupDocs.Watermark für .NET API-Referenz"
description: "Definiert die Methoden, die zum Abrufen der grundlegenden Dokumentinformationen erforderlich sind."
type: docs
weight: 70
url: /de/net/groupdocs.watermark.common/idocumentinfo/
---
## IDocumentInfo interface

Definiert die Methoden, die zum Abrufen der grundlegenden Dokumentinformationen erforderlich sind.

```csharp
public interface IDocumentInfo
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [FileType](../../groupdocs.watermark.common/idocumentinfo/filetype) { get; } | Liefert die Dateiformatbeschreibung. |
| [IsEncrypted](../../groupdocs.watermark.common/idocumentinfo/isencrypted) { get; } | Liefert einen Wert, der angibt, ob das Dokument verschlüsselt ist und ein Passwort zum Öffnen benötigt. |
| [PageCount](../../groupdocs.watermark.common/idocumentinfo/pagecount) { get; } | Liefert die Gesamtseitenzahl. |
| [Pages](../../groupdocs.watermark.common/idocumentinfo/pages) { get; } | Liefert die Sammlung der Seitenbeschreibungen des Dokuments. |
| [Size](../../groupdocs.watermark.common/idocumentinfo/size) { get; } | Liefert die Dokumentgröße in Bytes. |

### Hinweise

**Learn more**

* [Get document info](https://docs.groupdocs.com/display/watermarknet/Get+document+info)

### Beispiele

Das folgende Beispiel zeigt, wie man die allgemeinen Dokumentinformationen mit [`IDocumentInfo`](../idocumentinfo) abruft.

```csharp
using (Watermarker watermarker = new Watermarker("D:\\input.pdf"))
{
    IDocumentInfo docInfo = watermarker.GetDocumentInfo();
    Console.WriteLine("Document size: {0}", docInfo.Size);
    Console.WriteLine("Document format: {0}", docInfo.FileType.FileFormat);
    Console.WriteLine("Document contains {0} pages", docInfo.PageCount);
}
```

### Siehe auch

* namespace [GroupDocs.Watermark.Common](../../groupdocs.watermark.common)
* assembly [GroupDocs.Watermark](../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.watermark.dll -->
