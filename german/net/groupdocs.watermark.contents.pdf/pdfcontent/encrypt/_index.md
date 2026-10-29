---
title: "Verschlüsseln"
second_title: "GroupDocs.Watermark für .NET API-Referenz"
description: "Verschlüsselt das Dokument mit demselben Passwort wie Benutzer- und Eigentümerpasswort."
type: docs
weight: 50
url: /de/net/groupdocs.watermark.contents.pdf/pdfcontent/encrypt/
---
## Encrypt(string) {#encrypt}

Verschlüsselt das Dokument mit demselben Passwort wie Benutzer- und Eigentümerpasswort.

```csharp
public void Encrypt(string password)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Passwort | String | Benutzer‑ und Eigentümerpasswort. |

### Siehe auch

* class [PdfContent](../../pdfcontent)
* namespace [GroupDocs.Watermark.Contents.Pdf](../../../groupdocs.watermark.contents.pdf)
* assembly [GroupDocs.Watermark](../../../)

---

## Encrypt(string, string, PdfPermissions, PdfCryptoAlgorithm) {#encrypt_1}

Verschlüsselt den Inhalt.

```csharp
public void Encrypt(string userPassword, string ownerPassword, PdfPermissions permissions, 
    PdfCryptoAlgorithm cryptoAlgorithm)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| userPassword | String | Benutzerpasswort. |
| ownerPassword | String | Eigentümerpasswort. |
| Berechtigungen | PdfPermissions | Inhaltsberechtigungen. |
| cryptoAlgorithm | PdfCryptoAlgorithm | Kryptografischer Algorithmus. |

### Siehe auch

* enum [PdfPermissions](../../pdfpermissions)
* enum [PdfCryptoAlgorithm](../../pdfcryptoalgorithm)
* class [PdfContent](../../pdfcontent)
* namespace [GroupDocs.Watermark.Contents.Pdf](../../../groupdocs.watermark.contents.pdf)
* assembly [GroupDocs.Watermark](../../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.watermark.dll -->
