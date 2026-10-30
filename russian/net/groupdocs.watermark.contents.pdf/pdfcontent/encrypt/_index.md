---
title: "Зашифровать"
second_title: "GroupDocs.Watermark для .NET API Справка"
description: "Шифрует документ, используя тот же пароль, что и пароль пользователя и пароль владельца."
type: docs
weight: 50
url: /ru/net/groupdocs.watermark.contents.pdf/pdfcontent/encrypt/
---
## Encrypt(string) {#encrypt}

Шифрует документ, используя тот же пароль, что и пароль пользователя и пароль владельца.

```csharp
public void Encrypt(string password)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| пароль | String | Пароль пользователя и владельца. |

### См. также

* class [PdfContent](../../pdfcontent)
* namespace [GroupDocs.Watermark.Contents.Pdf](../../../groupdocs.watermark.contents.pdf)
* assembly [GroupDocs.Watermark](../../../)

---

## Encrypt(string, string, PdfPermissions, PdfCryptoAlgorithm) {#encrypt_1}

Шифрует содержимое.

```csharp
public void Encrypt(string userPassword, string ownerPassword, PdfPermissions permissions, 
    PdfCryptoAlgorithm cryptoAlgorithm)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| userPassword | String | Пароль пользователя. |
| ownerPassword | String | Пароль владельца. |
| permissions | PdfPermissions | Разрешения на содержание. |
| cryptoAlgorithm | PdfCryptoAlgorithm | Криптографический алгоритм. |

### См. также

* enum [PdfPermissions](../../pdfpermissions)
* enum [PdfCryptoAlgorithm](../../pdfcryptoalgorithm)
* class [PdfContent](../../pdfcontent)
* namespace [GroupDocs.Watermark.Contents.Pdf](../../../groupdocs.watermark.contents.pdf)
* assembly [GroupDocs.Watermark](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.watermark.dll -->
