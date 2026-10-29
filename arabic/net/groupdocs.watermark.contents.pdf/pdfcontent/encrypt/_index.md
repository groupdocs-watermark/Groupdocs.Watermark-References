---
title: "تشفير"
second_title: "GroupDocs.Watermark لـ .NET مرجع API"
description: "يشفّر المستند باستخدام نفس كلمة المرور ككلمة مرور المستخدم وكلمة مرور المالك."
type: docs
weight: 50
url: /ar/net/groupdocs.watermark.contents.pdf/pdfcontent/encrypt/
---
## Encrypt(string) {#encrypt}

يشفّر المستند باستخدام نفس كلمة المرور ككلمة مرور المستخدم وكلمة مرور المالك.

```csharp
public void Encrypt(string password)
```

| معامل | Type | الوصف |
| --- | --- | --- |
| كلمة المرور | String | كلمة مرور المستخدم والمالك. |

### انظر أيضاً

* class [PdfContent](../../pdfcontent)
* namespace [GroupDocs.Watermark.Contents.Pdf](../../../groupdocs.watermark.contents.pdf)
* assembly [GroupDocs.Watermark](../../../)

---

## Encrypt(string, string, PdfPermissions, PdfCryptoAlgorithm) {#encrypt_1}

يشفّر المحتوى.

```csharp
public void Encrypt(string userPassword, string ownerPassword, PdfPermissions permissions, 
    PdfCryptoAlgorithm cryptoAlgorithm)
```

| معامل | Type | الوصف |
| --- | --- | --- |
| userPassword | String | كلمة مرور المستخدم. |
| ownerPassword | String | كلمة مرور المالك. |
| الأذونات | PdfPermissions | أذونات المحتوى. |
| cryptoAlgorithm | PdfCryptoAlgorithm | الخوارزمية التشفيرية. |

### انظر أيضاً

* enum [PdfPermissions](../../pdfpermissions)
* enum [PdfCryptoAlgorithm](../../pdfcryptoalgorithm)
* class [PdfContent](../../pdfcontent)
* namespace [GroupDocs.Watermark.Contents.Pdf](../../../groupdocs.watermark.contents.pdf)
* assembly [GroupDocs.Watermark](../../../)

<!-- لا تقم بالتعديل: تم الإنشاء بواسطة xmldocmd لـ GroupDocs.watermark.dll -->
