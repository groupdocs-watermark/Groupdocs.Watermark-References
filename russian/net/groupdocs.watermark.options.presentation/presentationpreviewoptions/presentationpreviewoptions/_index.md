---
title: "PresentationPreviewOptions"
second_title: "GroupDocs.Watermark для .NET API Справка"
description: "Инициализирует новый экземпляр класса PresentationPreviewOptionsgroupdocs.watermark.options.presentation/presentationpreviewoptions, закрывая выходной поток."
type: docs
weight: 10
url: /ru/net/groupdocs.watermark.options.presentation/presentationpreviewoptions/presentationpreviewoptions/
---
## PresentationPreviewOptions(CreatePageStream) {#constructor}

Инициализирует новый экземпляр класса [`PresentationPreviewOptions`](../../presentationpreviewoptions), закрывая выходной поток.

```csharp
public PresentationPreviewOptions(CreatePageStream createPageStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| createPageStream | CreatePageStream | Создаёт поток для предварительного просмотра конкретной страницы. |

### См. также

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* class [PresentationPreviewOptions](../../presentationpreviewoptions)
* namespace [GroupDocs.Watermark.Options.Presentation](../../../groupdocs.watermark.options.presentation)
* assembly [GroupDocs.Watermark](../../../)

---

## PresentationPreviewOptions(CreatePageStream, ReleasePageStream) {#constructor_1}

Инициализирует новый экземпляр класса [`PresentationPreviewOptions`](../../presentationpreviewoptions), возвращая выходной поток клиенту для дальнейшего использования.

```csharp
public PresentationPreviewOptions(CreatePageStream createPageStream, 
    ReleasePageStream releasePageStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| createPageStream | CreatePageStream | Создаёт поток для предварительного просмотра конкретной страницы. |
| releasePageStream | ReleasePageStream | Уведомляет о завершении генерации предварительного просмотра страницы и получает выходной поток. |

### См. также

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.watermark.options/releasepagestream)
* class [PresentationPreviewOptions](../../presentationpreviewoptions)
* namespace [GroupDocs.Watermark.Options.Presentation](../../../groupdocs.watermark.options.presentation)
* assembly [GroupDocs.Watermark](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.watermark.dll -->
