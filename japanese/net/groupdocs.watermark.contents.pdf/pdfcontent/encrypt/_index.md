---
title: "暗号化"
second_title: "GroupDocs.Watermark の .NET API リファレンス"
description: "ユーザーパスワードとオーナーパスワードと同じパスワードを使用してドキュメントを暗号化します。"
type: docs
weight: 50
url: /ja/net/groupdocs.watermark.contents.pdf/pdfcontent/encrypt/
---
## Encrypt(string) {#encrypt}

ユーザーパスワードとオーナーパスワードと同じパスワードを使用してドキュメントを暗号化します。

```csharp
public void Encrypt(string password)
```

| パラメーター | Type | 説明 |
| --- | --- | --- |
| パスワード | String | ユーザーおよび所有者パスワード。 |

### 関連項目

* class [PdfContent](../../pdfcontent)
* namespace [GroupDocs.Watermark.Contents.Pdf](../../../groupdocs.watermark.contents.pdf)
* assembly [GroupDocs.Watermark](../../../)

---

## Encrypt(string, string, PdfPermissions, PdfCryptoAlgorithm) {#encrypt_1}

コンテンツを暗号化します。

```csharp
public void Encrypt(string userPassword, string ownerPassword, PdfPermissions permissions, 
    PdfCryptoAlgorithm cryptoAlgorithm)
```

| パラメーター | Type | 説明 |
| --- | --- | --- |
| userPassword | String | ユーザーパスワード。 |
| ownerPassword | String | 所有者パスワード。 |
| permissions | PdfPermissions | コンテンツの権限。 |
| cryptoAlgorithm | PdfCryptoAlgorithm | 暗号アルゴリズム。 |

### 関連項目

* enum [PdfPermissions](../../pdfpermissions)
* enum [PdfCryptoAlgorithm](../../pdfcryptoalgorithm)
* class [PdfContent](../../pdfcontent)
* namespace [GroupDocs.Watermark.Contents.Pdf](../../../groupdocs.watermark.contents.pdf)
* assembly [GroupDocs.Watermark](../../../)

<!-- 編集しないでください: GroupDocs.watermark.dll 用に xmldocmd によって生成されました -->
