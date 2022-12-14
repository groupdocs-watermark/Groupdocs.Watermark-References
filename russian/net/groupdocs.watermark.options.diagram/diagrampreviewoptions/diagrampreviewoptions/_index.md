---
title: DiagramPreviewOptions
second_title: Справочник по API GroupDocs.Watermark для .NET
description: Инициализирует новый экземплярDiagramPreviewOptionsgroupdocs.watermark.options.diagram/diagrampreviewoptions класс вызывающий закрытие выходного потока.
type: docs
weight: 10
url: /ru/net/groupdocs.watermark.options.diagram/diagrampreviewoptions/diagrampreviewoptions/
---
## DiagramPreviewOptions(CreatePageStream) {#constructor}

Инициализирует новый экземпляр[`DiagramPreviewOptions`](../../diagrampreviewoptions) класс, вызывающий закрытие выходного потока.

```csharp
public DiagramPreviewOptions(CreatePageStream createPageStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| createPageStream | CreatePageStream | Создает поток для предварительного просмотра определенной страницы. |

### Смотрите также

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* class [DiagramPreviewOptions](../../diagrampreviewoptions)
* пространство имен [GroupDocs.Watermark.Options.Diagram](../../diagrampreviewoptions)
* сборка [GroupDocs.Watermark](../../../)

---

## DiagramPreviewOptions(CreatePageStream, ReleasePageStream) {#constructor_1}

Инициализирует новый экземпляр[`DiagramPreviewOptions`](../../diagrampreviewoptions) класс, вызывающий возврат выходного потока клиенту для дальнейшего использования.

```csharp
public DiagramPreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| createPageStream | CreatePageStream | Создает поток для предварительного просмотра определенной страницы. |
| releasePageStream | ReleasePageStream | Уведомляет о том, что создание предварительного просмотра страницы выполнено, и получает выходной поток. |

### Смотрите также

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.watermark.options/releasepagestream)
* class [DiagramPreviewOptions](../../diagrampreviewoptions)
* пространство имен [GroupDocs.Watermark.Options.Diagram](../../diagrampreviewoptions)
* сборка [GroupDocs.Watermark](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
