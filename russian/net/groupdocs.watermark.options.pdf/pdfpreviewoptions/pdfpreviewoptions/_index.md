---
title: "PdfPreviewOptions"
second_title: "GroupDocs.Watermark для .NET API Справка"
description: "Инициализирует новый экземпляр класса PdfPreviewOptionsgroupdocs.watermark.options.pdf/pdfpreviewoptions, закрывая выходной поток."
type: docs
weight: 10
url: /ru/net/groupdocs.watermark.options.pdf/pdfpreviewoptions/pdfpreviewoptions/
---
## PdfPreviewOptions(CreatePageStream) {#constructor}

Инициализирует новый экземпляр класса [`PdfPreviewOptions`](../../pdfpreviewoptions), закрывая выходной поток.

```csharp
public PdfPreviewOptions(CreatePageStream createPageStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| createPageStream | CreatePageStream | Создаёт поток для предварительного просмотра конкретной страницы. |

### См. также

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* class [PdfPreviewOptions](../../pdfpreviewoptions)
* namespace [GroupDocs.Watermark.Options.Pdf](../../../groupdocs.watermark.options.pdf)
* assembly [GroupDocs.Watermark](../../../)

---

## PdfPreviewOptions(CreatePageStream, ReleasePageStream) {#constructor_1}

Инициализирует новый экземпляр класса [`PdfPreviewOptions`](../../pdfpreviewoptions), возвращая выходной поток клиенту для дальнейшего использования.

```csharp
public PdfPreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| createPageStream | CreatePageStream | Создаёт поток для предварительного просмотра конкретной страницы. |
| releasePageStream | ReleasePageStream | Уведомляет о завершении генерации предварительного просмотра страницы и получает выходной поток. |

### См. также

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.watermark.options/releasepagestream)
* class [PdfPreviewOptions](../../pdfpreviewoptions)
* namespace [GroupDocs.Watermark.Options.Pdf](../../../groupdocs.watermark.options.pdf)
* assembly [GroupDocs.Watermark](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.watermark.dll -->
