---
title: "Пароль"
second_title: "GroupDocs.Watermark для .NET API Справка"
description: "Получает или задает пароль для открытия зашифрованного документа."
type: docs
weight: 50
url: /ru/net/groupdocs.watermark.options/loadoptions/password/
---
## LoadOptions.Password property

Получает или задает пароль для открытия зашифрованного документа.

```csharp
public string Password { get; set; }
```

### Property Value

Пароль для открытия зашифрованного документа.

### Примечания

Пароль может быть null или пустой строкой. Значение по умолчанию — null. Если содержимое не зашифровано, установите null или пустую строку.

### Примеры

Загружает содержимое, защищённое паролем.

```csharp
LoadOptions loadOptions = new LoadOptions
{
    Password = "pwd123"
};
using (Watermarker watermarker = new Watermarker(@"D:\doc.vsdx", loadOptions))
{
    // ...
}
```

### См. также

* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Watermark.Options](../../../groupdocs.watermark.options)
* assembly [GroupDocs.Watermark](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.watermark.dll -->
