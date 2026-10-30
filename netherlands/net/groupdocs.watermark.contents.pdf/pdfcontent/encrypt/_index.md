---
title: "Versleutelen"
second_title: "GroupDocs.Watermark voor .NET API-referentie"
description: "Versleutelt het document met hetzelfde wachtwoord als gebruikerswachtwoord en eigenaarwachtwoord."
type: docs
weight: 50
url: /nl/net/groupdocs.watermark.contents.pdf/pdfcontent/encrypt/
---
## Encrypt(string) {#encrypt}

Versleutelt het document met hetzelfde wachtwoord als gebruikerswachtwoord en eigenaarwachtwoord.

```csharp
public void Encrypt(string password)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| wachtwoord | String | Gebruikers- en eigenaarwachtwoord. |

### Zie ook

* class [PdfContent](../../pdfcontent)
* namespace [GroupDocs.Watermark.Contents.Pdf](../../../groupdocs.watermark.contents.pdf)
* assembly [GroupDocs.Watermark](../../../)

---

## Encrypt(string, string, PdfPermissions, PdfCryptoAlgorithm) {#encrypt_1}

Versleutelt de inhoud.

```csharp
public void Encrypt(string userPassword, string ownerPassword, PdfPermissions permissions, 
    PdfCryptoAlgorithm cryptoAlgorithm)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| userPassword | String | Gebruikerswachtwoord. |
| ownerPassword | String | Eigenaarwachtwoord. |
| machtigingen | PdfPermissions | Inhoudsmachtigingen. |
| cryptoAlgorithm | PdfCryptoAlgorithm | Cryptografisch algoritme. |

### Zie ook

* enum [PdfPermissions](../../pdfpermissions)
* enum [PdfCryptoAlgorithm](../../pdfcryptoalgorithm)
* class [PdfContent](../../pdfcontent)
* namespace [GroupDocs.Watermark.Contents.Pdf](../../../groupdocs.watermark.contents.pdf)
* assembly [GroupDocs.Watermark](../../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.watermark.dll -->
