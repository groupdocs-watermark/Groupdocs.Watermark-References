---
title: "ImageWatermarkResult"
second_title: "GroupDocs.Watermark для .NET API Справка"
description: "Содержит свойства изображений водяного знака."
type: docs
weight: 3260
url: /ru/net/groupdocs.watermark.watermarks.results/imagewatermarkresult/
---
## ImageWatermarkResult class

Содержит свойства изображений водяного знака.

```csharp
public class ImageWatermarkResult : BaseWatermarkResult
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ImageWatermarkResult](imagewatermarkresult)(string) | Инициализирует объект ImageWatermarkResult с идентификатором водяного знака, полученным после процесса поиска. Этот уникальный идентификатор используется для получения дополнительных свойств этого водяного знака из слоя информации о водяных знаках документа. |

## Свойства

| Имя | Описание |
| --- | --- |
| [CreatedOn](../../groupdocs.watermark.watermarks.results/basewatermarkresult/createdon) { get; set; } | Получить или задать дату создания водяного знака. |
| [Height](../../groupdocs.watermark.watermarks.results/basewatermarkresult/height) { get; set; } | Указывает высоту водяного знака. |
| [Left](../../groupdocs.watermark.watermarks.results/basewatermarkresult/left) { get; set; } | Указывает левое положение водяного знака. |
| [ModifiedOn](../../groupdocs.watermark.watermarks.results/basewatermarkresult/modifiedon) { get; set; } | Получить или задать дату изменения водяного знака. |
| [PageNumber](../../groupdocs.watermark.watermarks.results/basewatermarkresult/pagenumber) { get; } | Указывает страницу, на которой размещён водяной знак. |
| [Size](../../groupdocs.watermark.watermarks.results/imagewatermarkresult/size) { get; } | Указывает размер изображения водяного знака в байтах. |
| [Top](../../groupdocs.watermark.watermarks.results/basewatermarkresult/top) { get; set; } | Указывает верхнее положение водяного знака. |
| [WatermarkId](../../groupdocs.watermark.watermarks.results/basewatermarkresult/watermarkid) { get; } | Уникальный идентификатор водяного знака для изменения водяного знака в документе с помощью методов Update или Delete. Это свойство будет установлено автоматически после вызова метода Add. Если это свойство было сохранено ранее, его можно установить вручную для манипуляции водяным знаком. |
| [WatermarkPosition](../../groupdocs.watermark.watermarks.results/basewatermarkresult/watermarkposition) { get; } | Указывает позицию водяного знака |
| [WatermarkType](../../groupdocs.watermark.watermarks.results/basewatermarkresult/watermarktype) { get; } | Указывает тип водяного знака. |
| [Width](../../groupdocs.watermark.watermarks.results/basewatermarkresult/width) { get; set; } | Указывает ширину водяного знака. |

### См. также

* class [BaseWatermarkResult](../basewatermarkresult)
* namespace [GroupDocs.Watermark.Watermarks.Results](../../groupdocs.watermark.watermarks.results)
* assembly [GroupDocs.Watermark](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.watermark.dll -->
