---
title: "EmailEmbeddedObject"
second_title: "GroupDocs.Watermark для .NET API Справка"
description: "Представляет объект, встроенный в тело электронного письма."
type: docs
weight: 370
url: /ru/net/groupdocs.watermark.contents.email/emailembeddedobject/
---
## EmailEmbeddedObject class

Представляет объект, встроенный в тело электронного письма.

```csharp
public class EmailEmbeddedObject : EmailAttachmentBase
```

## Свойства

| Имя | Описание |
| --- | --- |
| override [Content](../../groupdocs.watermark.contents.email/emailattachmentbase/content) { get; set; } | Получает или задает содержимое вложенного файла. |
| [ContentId](../../groupdocs.watermark.contents.email/emailattachmentbase/contentid) { get; } | Получает идентификатор содержимого этого [`EmailAttachmentBase`](../emailattachmentbase). |
| [MediaType](../../groupdocs.watermark.contents.email/emailattachmentbase/mediatype) { get; } | Получает тип медиа этого [`EmailAttachmentBase`](../emailattachmentbase). |

## Методы

| Имя | Описание |
| --- | --- |
| [CreateWatermarker](../../groupdocs.watermark.common/attachment/createwatermarker)() | Загружает содержимое из вложенного файла. |
| [CreateWatermarker](../../groupdocs.watermark.common/attachment/createwatermarker)(LoadOptions) | Загружает содержимое из вложенного файла с указанными параметрами загрузки. |
| [CreateWatermarker](../../groupdocs.watermark.common/attachment/createwatermarker)(LoadOptions, WatermarkerSettings) | Загружает содержимое из вложенного файла с указанными параметрами загрузки и настройками. |
| [GetDocumentInfo](../../groupdocs.watermark.common/attachment/getdocumentinfo)() | Получает информацию о документе, хранящемся во вложенном файле. |

### См. также

* class [EmailAttachmentBase](../emailattachmentbase)
* namespace [GroupDocs.Watermark.Contents.Email](../../groupdocs.watermark.contents.email)
* assembly [GroupDocs.Watermark](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.watermark.dll -->
