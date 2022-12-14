---
title: Encrypt
second_title: Referencia de API de GroupDocs.Watermark para .NET
description: Cifra el documento utilizando la misma contraseña que la contraseña de usuario y la contraseña de propietario.
type: docs
weight: 50
url: /es/net/groupdocs.watermark.contents.pdf/pdfcontent/encrypt/
---
## Encrypt(string) {#encrypt}

Cifra el documento utilizando la misma contraseña que la contraseña de usuario y la contraseña de propietario.

```csharp
public void Encrypt(string password)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| password | String | Contraseña de usuario y propietario. |

### Ver también

* class [PdfContent](../../pdfcontent)
* espacio de nombres [GroupDocs.Watermark.Contents.Pdf](../../pdfcontent)
* asamblea [GroupDocs.Watermark](../../../)

---

## Encrypt(string, string, PdfPermissions, PdfCryptoAlgorithm) {#encrypt_1}

Cifra el contenido.

```csharp
public void Encrypt(string userPassword, string ownerPassword, PdfPermissions permissions, 
    PdfCryptoAlgorithm cryptoAlgorithm)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| userPassword | String | Contraseña de usuario. |
| ownerPassword | String | Contraseña de propietario. |
| permissions | PdfPermissions | Permisos de contenido. |
| cryptoAlgorithm | PdfCryptoAlgorithm | Algoritmo criptográfico. |

### Ver también

* enum [PdfPermissions](../../pdfpermissions)
* enum [PdfCryptoAlgorithm](../../pdfcryptoalgorithm)
* class [PdfContent](../../pdfcontent)
* espacio de nombres [GroupDocs.Watermark.Contents.Pdf](../../pdfcontent)
* asamblea [GroupDocs.Watermark](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
