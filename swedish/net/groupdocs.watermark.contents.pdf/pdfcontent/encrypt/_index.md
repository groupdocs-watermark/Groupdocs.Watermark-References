---
title: "Kryptera"
second_title: "GroupDocs.Watermark för .NET API-referens"
description: "Krypterar dokumentet med samma lösenord som användarlösenordet och ägarlösenordet."
type: docs
weight: 50
url: /sv/net/groupdocs.watermark.contents.pdf/pdfcontent/encrypt/
---
## Encrypt(string) {#encrypt}

Krypterar dokumentet med samma lösenord som användarlösenordet och ägarlösenordet.

```csharp
public void Encrypt(string password)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lösenord | Sträng | Användar- och ägarlösenord. |

### Se även

* class [PdfContent](../../pdfcontent)
* namespace [GroupDocs.Watermark.Contents.Pdf](../../../groupdocs.watermark.contents.pdf)
* assembly [GroupDocs.Watermark](../../../)

---

## Encrypt(string, string, PdfPermissions, PdfCryptoAlgorithm) {#encrypt_1}

Krypterar innehållet.

```csharp
public void Encrypt(string userPassword, string ownerPassword, PdfPermissions permissions, 
    PdfCryptoAlgorithm cryptoAlgorithm)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| userPassword | Sträng | Användarlösenord. |
| ownerPassword | Sträng | Ägarlösenord. |
| permissions | PdfPermissions | Innehållsbehörigheter. |
| cryptoAlgorithm | PdfCryptoAlgorithm | Kryptografisk algoritm. |

### Se även

* enum [PdfPermissions](../../pdfpermissions)
* enum [PdfCryptoAlgorithm](../../pdfcryptoalgorithm)
* class [PdfContent](../../pdfcontent)
* namespace [GroupDocs.Watermark.Contents.Pdf](../../../groupdocs.watermark.contents.pdf)
* assembly [GroupDocs.Watermark](../../../)

<!-- FÅR INTE REDIGERAS: genererad av xmldocmd för GroupDocs.watermark.dll -->
