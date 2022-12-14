---
title: PresentationPreviewOptions
second_title: Справочник по API GroupDocs.Watermark для .NET
description: Инициализирует новый экземплярPresentationPreviewOptionsgroupdocs.watermark.options.presentation/presentationpreviewoptions класс вызывающий закрытие выходного потока.
type: docs
weight: 10
url: /ru/net/groupdocs.watermark.options.presentation/presentationpreviewoptions/presentationpreviewoptions/
---
## PresentationPreviewOptions(CreatePageStream) {#constructor}

Инициализирует новый экземпляр[`PresentationPreviewOptions`](../../presentationpreviewoptions) класс, вызывающий закрытие выходного потока.

```csharp
public PresentationPreviewOptions(CreatePageStream createPageStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| createPageStream | CreatePageStream | Создает поток для предварительного просмотра определенной страницы. |

### Смотрите также

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* class [PresentationPreviewOptions](../../presentationpreviewoptions)
* пространство имен [GroupDocs.Watermark.Options.Presentation](../../presentationpreviewoptions)
* сборка [GroupDocs.Watermark](../../../)

---

## PresentationPreviewOptions(CreatePageStream, ReleasePageStream) {#constructor_1}

Инициализирует новый экземпляр[`PresentationPreviewOptions`](../../presentationpreviewoptions) класс, вызывающий возврат выходного потока клиенту для дальнейшего использования.

```csharp
public PresentationPreviewOptions(CreatePageStream createPageStream, 
    ReleasePageStream releasePageStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| createPageStream | CreatePageStream | Создает поток для предварительного просмотра определенной страницы. |
| releasePageStream | ReleasePageStream | Уведомляет о том, что создание предварительного просмотра страницы выполнено, и получает выходной поток. |

### Смотрите также

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.watermark.options/releasepagestream)
* class [PresentationPreviewOptions](../../presentationpreviewoptions)
* пространство имен [GroupDocs.Watermark.Options.Presentation](../../presentationpreviewoptions)
* сборка [GroupDocs.Watermark](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
