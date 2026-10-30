---
title: "WatermarkResult"
second_title: "GroupDocs.Watermark для .NET API Справка"
description: "Представляет результат операции водяного знака, включая такие детали, как размеры документов, время обработки и количество применённых водяных знаков."
type: docs
weight: 1670
url: /ru/net/groupdocs.watermark.internal/watermarkresult/
---
## WatermarkResult class

Представляет результат операции наложения водяного знака, включая такие детали, как размеры документа, время обработки и количество применённых водяных знаков.

```csharp
public class WatermarkResult
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [WatermarkResult](watermarkresult#constructor)() | Инициализирует новый экземпляр класса [`WatermarkResult`](../watermarkresult). |
| [WatermarkResult](watermarkresult#constructor_1)(long, TimeSpan, long, int) | Инициализирует новый экземпляр класса [`WatermarkResult`](../watermarkresult) с конкретными значениями. |

## Свойства

| Имя | Описание |
| --- | --- |
| [FinalDocumentSize](../../groupdocs.watermark.internal/watermarkresult/finaldocumentsize) { get; } | Получает или задаёт размер окончательного обработанного документа в байтах. |
| [NumberWatermarksApplied](../../groupdocs.watermark.internal/watermarkresult/numberwatermarksapplied) { get; } | Получает или задаёт общее количество водяных знаков, применённых к документу. |
| [ProcessingTime](../../groupdocs.watermark.internal/watermarkresult/processingtime) { get; } | Получает или задаёт время обработки операции наложения водяного знака. |
| [SourceDocumentSize](../../groupdocs.watermark.internal/watermarkresult/sourcedocumentsize) { get; } | Получает или задаёт размер исходного документа в байтах. |

### См. также

* namespace [GroupDocs.Watermark.Internal](../../groupdocs.watermark.internal)
* assembly [GroupDocs.Watermark](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.watermark.dll -->
