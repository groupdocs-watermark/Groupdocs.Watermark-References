---
title: "PdfSearchableObjects"
second_title: "GroupDocs.Watermark для .NET API Справка"
description: "Указывает флаги, представляющие объекты содержимого PDF, которые должны быть включены в поиск водяного знака."
type: docs
weight: 2530
url: /ru/net/groupdocs.watermark.search.objects/pdfsearchableobjects/
---
## PdfSearchableObjects enumeration

Указывает флаги, представляющие объекты содержимого PDF, которые должны быть включены в поиск водяного знака.

```csharp
[Flags]
public enum PdfSearchableObjects
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| None | `0` | Указывает отсутствие объектов поиска. |
| XObjects | `1` | Поиск в XObjects. |
| Artifacts | `2` | Поиск в артефактах. |
| Annotations | `4` | Поиск в аннотациях. |
| Text | `8` | Поиск в тексте содержимого. |
| Hyperlinks | `10` | Поиск в гиперссылках. |
| AttachedImages | `20` | Поиск во вложенных изображениях. |
| Vector | `40` | Поиск в операторах. |
| All | `7F` | Поиск во всех объектах содержимого. |

### См. также

* namespace [GroupDocs.Watermark.Search.Objects](../../groupdocs.watermark.search.objects)
* assembly [GroupDocs.Watermark](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.watermark.dll -->
