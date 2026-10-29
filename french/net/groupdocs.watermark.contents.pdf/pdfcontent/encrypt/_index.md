---
title: "Crypter"
second_title: "GroupDocs.Watermark pour .NET Référence de l'API"
description: "Crypte le document en utilisant le même mot de passe que le mot de passe utilisateur et le mot de passe propriétaire."
type: docs
weight: 50
url: /fr/net/groupdocs.watermark.contents.pdf/pdfcontent/encrypt/
---
## Encrypt(string) {#encrypt}

Crypte le document en utilisant le même mot de passe que le mot de passe utilisateur et le mot de passe propriétaire.

```csharp
public void Encrypt(string password)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| mot de passe | String | Mot de passe de l'utilisateur et du propriétaire. |

### Voir aussi

* class [PdfContent](../../pdfcontent)
* namespace [GroupDocs.Watermark.Contents.Pdf](../../../groupdocs.watermark.contents.pdf)
* assembly [GroupDocs.Watermark](../../../)

---

## Encrypt(string, string, PdfPermissions, PdfCryptoAlgorithm) {#encrypt_1}

Crypte le contenu.

```csharp
public void Encrypt(string userPassword, string ownerPassword, PdfPermissions permissions, 
    PdfCryptoAlgorithm cryptoAlgorithm)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| userPassword | String | Mot de passe de l'utilisateur. |
| ownerPassword | String | Mot de passe du propriétaire. |
| permissions | PdfPermissions | Autorisations de contenu. |
| cryptoAlgorithm | PdfCryptoAlgorithm | Algorithme cryptographique. |

### Voir aussi

* enum [PdfPermissions](../../pdfpermissions)
* enum [PdfCryptoAlgorithm](../../pdfcryptoalgorithm)
* class [PdfContent](../../pdfcontent)
* namespace [GroupDocs.Watermark.Contents.Pdf](../../../groupdocs.watermark.contents.pdf)
* assembly [GroupDocs.Watermark](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.watermark.dll -->
