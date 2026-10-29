---
title: "Enkripsi"
second_title: "GroupDocs.Watermark untuk Referensi API .NET"
description: "Mengenkripsi dokumen menggunakan kata sandi yang sama sebagai kata sandi pengguna dan kata sandi pemilik."
type: docs
weight: 50
url: /id/net/groupdocs.watermark.contents.pdf/pdfcontent/encrypt/
---
## Encrypt(string) {#encrypt}

Mengenkripsi dokumen menggunakan kata sandi yang sama sebagai kata sandi pengguna dan kata sandi pemilik.

```csharp
public void Encrypt(string password)
```

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| kata sandi | String | Kata sandi pengguna dan pemilik. |

### Lihat Juga

* class [PdfContent](../../pdfcontent)
* namespace [GroupDocs.Watermark.Contents.Pdf](../../../groupdocs.watermark.contents.pdf)
* assembly [GroupDocs.Watermark](../../../)

---

## Encrypt(string, string, PdfPermissions, PdfCryptoAlgorithm) {#encrypt_1}

Mengenkripsi konten.

```csharp
public void Encrypt(string userPassword, string ownerPassword, PdfPermissions permissions, 
    PdfCryptoAlgorithm cryptoAlgorithm)
```

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| userPassword | String | Kata sandi pengguna. |
| ownerPassword | String | Kata sandi pemilik. |
| izin | PdfPermissions | Izin konten. |
| cryptoAlgorithm | PdfCryptoAlgorithm | Algoritma kriptografi. |

### Lihat Juga

* enum [PdfPermissions](../../pdfpermissions)
* enum [PdfCryptoAlgorithm](../../pdfcryptoalgorithm)
* class [PdfContent](../../pdfcontent)
* namespace [GroupDocs.Watermark.Contents.Pdf](../../../groupdocs.watermark.contents.pdf)
* assembly [GroupDocs.Watermark](../../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.watermark.dll -->
