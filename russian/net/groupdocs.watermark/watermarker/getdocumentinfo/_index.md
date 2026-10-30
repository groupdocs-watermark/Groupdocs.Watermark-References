---
title: "GetDocumentInfo"
second_title: "GroupDocs.Watermark для .NET API Справка"
description: "Получает информацию о формате загруженного документа."
type: docs
weight: 70
url: /ru/net/groupdocs.watermark/watermarker/getdocumentinfo/
---
## Watermarker.GetDocumentInfo method

Получает информацию о формате загруженного документа.

```csharp
public IDocumentInfo GetDocumentInfo()
```

### Возвращаемое значение

Экземпляр [`IDocumentInfo`](../../../groupdocs.watermark.common/idocumentinfo), содержащий обнаруженную информацию.

### Примечания

Узнайте больше о получении информации о документе [Получить информацию о документе](https://docs.groupdocs.com/display/watermarknet/Get+document+info).

### Примеры

Получить информацию о документе любого поддерживаемого типа.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\test.ppt"))
{
    IDocumentInfo docInfo = watermarker.GetDocumentInfo();
    Console.WriteLine("Document size: {0}", docInfo.Size);
    Console.WriteLine("Document format: {0}", docInfo.FileType.FileFormat);
    Console.WriteLine("Document contains {0} pages", docInfo.PageCount);
}
```

### См. также

* interface [IDocumentInfo](../../../groupdocs.watermark.common/idocumentinfo)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.watermark.dll -->
