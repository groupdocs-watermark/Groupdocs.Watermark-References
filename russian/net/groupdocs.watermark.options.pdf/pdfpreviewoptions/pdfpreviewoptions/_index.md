---
title: PdfPreviewOptions
second_title: Справочник по API GroupDocs.Watermark для .NET
description: Инициализирует новый экземплярPdfPreviewOptionsgroupdocs.watermark.options.pdf/pdfpreviewoptions класс вызывающий закрытие выходного потока.
type: docs
weight: 10
url: /ru/net/groupdocs.watermark.options.pdf/pdfpreviewoptions/pdfpreviewoptions/
---
## PdfPreviewOptions(CreatePageStream) {#constructor}

Инициализирует новый экземпляр[`PdfPreviewOptions`](../../pdfpreviewoptions) класс, вызывающий закрытие выходного потока.

```csharp
public PdfPreviewOptions(CreatePageStream createPageStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| createPageStream | CreatePageStream | Создает поток для предварительного просмотра определенной страницы. |

### Смотрите также

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* class [PdfPreviewOptions](../../pdfpreviewoptions)
* пространство имен [GroupDocs.Watermark.Options.Pdf](../../pdfpreviewoptions)
* сборка [GroupDocs.Watermark](../../../)

---

## PdfPreviewOptions(CreatePageStream, ReleasePageStream) {#constructor_1}

Инициализирует новый экземпляр[`PdfPreviewOptions`](../../pdfpreviewoptions) класс, вызывающий возврат выходного потока клиенту для дальнейшего использования.

```csharp
public PdfPreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| createPageStream | CreatePageStream | Создает поток для предварительного просмотра определенной страницы. |
| releasePageStream | ReleasePageStream | Уведомляет о том, что создание предварительного просмотра страницы выполнено, и получает выходной поток. |

### Смотрите также

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.watermark.options/releasepagestream)
* class [PdfPreviewOptions](../../pdfpreviewoptions)
* пространство имен [GroupDocs.Watermark.Options.Pdf](../../pdfpreviewoptions)
* сборка [GroupDocs.Watermark](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
