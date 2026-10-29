---
title: "加密"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "使用与用户密码和所有者密码相同的密码加密文档。"
type: docs
weight: 50
url: /zh/net/groupdocs.watermark.contents.pdf/pdfcontent/encrypt/
---
## Encrypt(string) {#encrypt}

使用与用户密码和所有者密码相同的密码加密文档。

```csharp
public void Encrypt(string password)
```

| 参数 | Type | 描述 |
| --- | --- | --- |
| 密码 | String | 用户和所有者密码。 |

### 另请参阅

* class [PdfContent](../../pdfcontent)
* namespace [GroupDocs.Watermark.Contents.Pdf](../../../groupdocs.watermark.contents.pdf)
* assembly [GroupDocs.Watermark](../../../)

---

## Encrypt(string, string, PdfPermissions, PdfCryptoAlgorithm) {#encrypt_1}

加密内容。

```csharp
public void Encrypt(string userPassword, string ownerPassword, PdfPermissions permissions, 
    PdfCryptoAlgorithm cryptoAlgorithm)
```

| 参数 | Type | 描述 |
| --- | --- | --- |
| userPassword | String | 用户密码。 |
| ownerPassword | String | 所有者密码。 |
| 权限 | PdfPermissions | 内容权限。 |
| cryptoAlgorithm | PdfCryptoAlgorithm | 加密算法。 |

### 另请参阅

* enum [PdfPermissions](../../pdfpermissions)
* enum [PdfCryptoAlgorithm](../../pdfcryptoalgorithm)
* class [PdfContent](../../pdfcontent)
* namespace [GroupDocs.Watermark.Contents.Pdf](../../../groupdocs.watermark.contents.pdf)
* assembly [GroupDocs.Watermark](../../../)

<!-- 请勿编辑：由 xmldoccmd 为 GroupDocs.watermark.dll 生成 -->
