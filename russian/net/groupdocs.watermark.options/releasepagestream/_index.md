---
title: "ReleasePageStream"
second_title: "GroupDocs.Watermark для .NET API Справка"
description: "Представляет метод, который освобождает поток, созданный делегатом CreatePageStream./createpagestream."
type: docs
weight: 2160
url: /ru/net/groupdocs.watermark.options/releasepagestream/
---
## ReleasePageStream delegate

Представляет метод, который освобождает поток, созданный делегатом [`CreatePageStream`](../createpagestream).

```csharp
public delegate void ReleasePageStream(int pageNumber, Stream pageStream);
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pageNumber | Int32 | Номер страницы сгенерированного предварительного просмотра. |
| pageStream | Поток | Поток, содержащий сгенерированный предварительный просмотр страницы. |

### См. также

* namespace [GroupDocs.Watermark.Options](../../groupdocs.watermark.options)
* assembly [GroupDocs.Watermark](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.watermark.dll -->
