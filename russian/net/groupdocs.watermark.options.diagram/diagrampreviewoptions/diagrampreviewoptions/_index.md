---
title: "DiagramPreviewOptions"
second_title: "GroupDocs.Watermark для .NET API Справка"
description: "Инициализирует новый экземпляр класса DiagramPreviewOptionsgroupdocs.watermark.options.diagram/diagrampreviewoptions, закрывая поток вывода."
type: docs
weight: 10
url: /ru/net/groupdocs.watermark.options.diagram/diagrampreviewoptions/diagrampreviewoptions/
---
## DiagramPreviewOptions(CreatePageStream) {#constructor}

Инициализирует новый экземпляр класса [`DiagramPreviewOptions`](../../diagrampreviewoptions), закрывая поток вывода.

```csharp
public DiagramPreviewOptions(CreatePageStream createPageStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| createPageStream | CreatePageStream | Создаёт поток для предварительного просмотра конкретной страницы. |

### См. также

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* class [DiagramPreviewOptions](../../diagrampreviewoptions)
* namespace [GroupDocs.Watermark.Options.Diagram](../../../groupdocs.watermark.options.diagram)
* assembly [GroupDocs.Watermark](../../../)

---

## DiagramPreviewOptions(CreatePageStream, ReleasePageStream) {#constructor_1}

Инициализирует новый экземпляр класса [`DiagramPreviewOptions`](../../diagrampreviewoptions), возвращая поток вывода клиенту для дальнейшего использования.

```csharp
public DiagramPreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| createPageStream | CreatePageStream | Создаёт поток для предварительного просмотра конкретной страницы. |
| releasePageStream | ReleasePageStream | Уведомляет о завершении генерации предварительного просмотра страницы и получает выходной поток. |

### См. также

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.watermark.options/releasepagestream)
* class [DiagramPreviewOptions](../../diagrampreviewoptions)
* namespace [GroupDocs.Watermark.Options.Diagram](../../../groupdocs.watermark.options.diagram)
* assembly [GroupDocs.Watermark](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.watermark.dll -->
