---
title: "IDocumentInfo"
second_title: "GroupDocs.Watermark для .NET API Справка"
description: "Определяет методы, необходимые для получения основной информации о документе."
type: docs
weight: 70
url: /ru/net/groupdocs.watermark.common/idocumentinfo/
---
## IDocumentInfo interface

Определяет методы, необходимые для получения основной информации о документе.

```csharp
public interface IDocumentInfo
```

## Свойства

| Имя | Описание |
| --- | --- |
| [FileType](../../groupdocs.watermark.common/idocumentinfo/filetype) { get; } | Получает описание формата файла. |
| [IsEncrypted](../../groupdocs.watermark.common/idocumentinfo/isencrypted) { get; } | Возвращает значение, указывающее, зашифрован ли документ и требуется ли пароль для его открытия. |
| [PageCount](../../groupdocs.watermark.common/idocumentinfo/pagecount) { get; } | Получает общее количество страниц. |
| [Pages](../../groupdocs.watermark.common/idocumentinfo/pages) { get; } | Получает коллекцию описаний страниц документа. |
| [Size](../../groupdocs.watermark.common/idocumentinfo/size) { get; } | Получает размер документа в байтах. |

### Примечания

**Learn more**

* [Get document info](https://docs.groupdocs.com/display/watermarknet/Get+document+info)

### Примеры

Следующий пример демонстрирует, как получить общую информацию о документе, используя [`IDocumentInfo`](../idocumentinfo).

```csharp
using (Watermarker watermarker = new Watermarker("D:\\input.pdf"))
{
    IDocumentInfo docInfo = watermarker.GetDocumentInfo();
    Console.WriteLine("Document size: {0}", docInfo.Size);
    Console.WriteLine("Document format: {0}", docInfo.FileType.FileFormat);
    Console.WriteLine("Document contains {0} pages", docInfo.PageCount);
}
```

### См. также

* namespace [GroupDocs.Watermark.Common](../../groupdocs.watermark.common)
* assembly [GroupDocs.Watermark](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.watermark.dll -->
