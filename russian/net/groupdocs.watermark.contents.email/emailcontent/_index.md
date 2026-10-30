---
title: "EmailContent"
second_title: "GroupDocs.Watermark для .NET API Справка"
description: "Представляет электронное сообщение."
type: docs
weight: 360
url: /ru/net/groupdocs.watermark.contents.email/emailcontent/
---
## EmailContent class

Представляет электронное сообщение.

```csharp
public sealed class EmailContent : Content
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Attachments](../../groupdocs.watermark.contents.email/emailcontent/attachments) { get; } | Получает коллекцию всех вложений электронного сообщения. |
| [Bcc](../../groupdocs.watermark.contents.email/emailcontent/bcc) { get; } | Получает коллекцию получателей BCC (слепая копия) электронного сообщения. |
| [Body](../../groupdocs.watermark.contents.email/emailcontent/body) { get; set; } | Получает или задаёт текстовое представление тела сообщения. |
| [BodyType](../../groupdocs.watermark.contents.email/emailcontent/bodytype) { get; } | Получает тип тела электронного сообщения. |
| [Cc](../../groupdocs.watermark.contents.email/emailcontent/cc) { get; } | Получает коллекцию получателей CC (копия) электронного сообщения. |
| [EmbeddedObjects](../../groupdocs.watermark.contents.email/emailcontent/embeddedobjects) { get; } | Получает коллекцию всех встроенных объектов электронного сообщения. |
| [From](../../groupdocs.watermark.contents.email/emailcontent/from) { get; } | Получает адрес отправителя электронного сообщения. |
| [HtmlBody](../../groupdocs.watermark.contents.email/emailcontent/htmlbody) { get; set; } | Получает или задаёт HTML‑представление тела сообщения. |
| [Subject](../../groupdocs.watermark.contents.email/emailcontent/subject) { get; set; } | Получает или задаёт тему электронного сообщения. |
| [To](../../groupdocs.watermark.contents.email/emailcontent/to) { get; } | Получает коллекцию получателей электронного сообщения. |

## Методы

| Имя | Описание |
| --- | --- |
| [Dispose](../../groupdocs.watermark.contents/content/dispose)() | Освобождает текущий экземпляр. |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | Находит все изображения в контенте. Поиск выполняется в объектах, указанных в [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | Находит изображения согласно указанным критериям поиска. Поиск выполняется в объектах, указанных в [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | Находит все возможные водяные знаки в контенте. Поиск выполняется в объектах, указанных в [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | Находит возможные водяные знаки в соответствии с указанными критериями поиска. Поиск выполняется в объектах, указанных в [`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects). |

### Примечания

**Learn more:**

* [Add watermarks to email attachments](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+email+attachments)
* [Email attachments](https://docs.groupdocs.com/display/watermarknet/Email+attachments)
* [Email messages](https://docs.groupdocs.com/display/watermarknet/Email+messages)

### См. также

* class [Content](../../groupdocs.watermark.contents/content)
* namespace [GroupDocs.Watermark.Contents.Email](../../groupdocs.watermark.contents.email)
* assembly [GroupDocs.Watermark](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.watermark.dll -->
