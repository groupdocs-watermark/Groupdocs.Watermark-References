---
title: "EmailSearchableObjects"
second_title: "GroupDocs.Watermark для .NET API Справка"
description: "Указывает флаги, представляющие объекты электронных сообщений, которые должны быть включены в поиск водяного знака."
type: docs
weight: 2520
url: /ru/net/groupdocs.watermark.search.objects/emailsearchableobjects/
---
## EmailSearchableObjects enumeration

Указывает флаги, представляющие объекты электронных сообщений, которые должны быть включены в поиск водяного знака.

```csharp
[Flags]
public enum EmailSearchableObjects
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| None | `0` | Указывает отсутствие объектов поиска. |
| Subject | `1` | Поиск в теме сообщения. |
| PlainTextBody | `2` | Поиск в простом текстовом теле сообщения. |
| HtmlBody | `4` | Поиск в html‑теле сообщения. |
| AttachedImages | `8` | Поиск во вложенных изображениях. |
| EmbeddedImages | `10` | Поиск во встроенных изображениях. |
| All | `1F` | Поиск во всех объектах электронной почты. |

### См. также

* namespace [GroupDocs.Watermark.Search.Objects](../../groupdocs.watermark.search.objects)
* assembly [GroupDocs.Watermark](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.watermark.dll -->
