---
title: "Cifra"
second_title: "GroupDocs.Watermark per .NET Riferimento API"
description: "Cifra il documento usando la stessa password per la password utente e la password proprietario."
type: docs
weight: 50
url: /it/net/groupdocs.watermark.contents.pdf/pdfcontent/encrypt/
---
## Encrypt(string) {#encrypt}

Cifra il documento usando la stessa password per la password utente e la password proprietario.

```csharp
public void Encrypt(string password)
```

| Parametro | Type | Descrizione |
| --- | --- | --- |
| password | String | Password utente e proprietario. |

### Vedi anche

* class [PdfContent](../../pdfcontent)
* namespace [GroupDocs.Watermark.Contents.Pdf](../../../groupdocs.watermark.contents.pdf)
* assembly [GroupDocs.Watermark](../../../)

---

## Encrypt(string, string, PdfPermissions, PdfCryptoAlgorithm) {#encrypt_1}

Cifra il contenuto.

```csharp
public void Encrypt(string userPassword, string ownerPassword, PdfPermissions permissions, 
    PdfCryptoAlgorithm cryptoAlgorithm)
```

| Parametro | Type | Descrizione |
| --- | --- | --- |
| userPassword | String | Password utente. |
| ownerPassword | String | Password proprietario. |
| permessi | PdfPermissions | Permessi del contenuto. |
| cryptoAlgorithm | PdfCryptoAlgorithm | Algoritmo crittografico. |

### Vedi anche

* enum [PdfPermissions](../../pdfpermissions)
* enum [PdfCryptoAlgorithm](../../pdfcryptoalgorithm)
* class [PdfContent](../../pdfcontent)
* namespace [GroupDocs.Watermark.Contents.Pdf](../../../groupdocs.watermark.contents.pdf)
* assembly [GroupDocs.Watermark](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.watermark.dll -->
