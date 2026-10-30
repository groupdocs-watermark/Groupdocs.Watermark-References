---
title: "Watermarker"
second_title: "GroupDocs.Watermark для .NET API Справка"
description: "Представляет класс для управления водяными знаками в документе."
type: docs
weight: 3140
url: /ru/net/groupdocs.watermark/watermarker/
---
## Watermarker class

Представляет класс для управления водяными знаками в документе.

```csharp
public class Watermarker : IDisposable
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Watermarker](watermarker#constructor)(Stream) | Инициализирует новый экземпляр класса [`Watermarker`](../watermarker) с указанным потоком. |
| [Watermarker](watermarker#constructor_4)(string) | Инициализирует новый экземпляр класса [`Watermarker`](../watermarker) с указанным путем к документу. |
| [Watermarker](watermarker#constructor_1)(Stream, LoadOptions) | Инициализирует новый экземпляр класса [`Watermarker`](../watermarker) с указанным потоком и параметрами загрузки. |
| [Watermarker](watermarker#constructor_3)(Stream, WatermarkerSettings) | Инициализирует новый экземпляр класса [`Watermarker`](../watermarker) с указанным потоком и настройками. |
| [Watermarker](watermarker#constructor_5)(string, LoadOptions) | Инициализирует новый экземпляр класса [`Watermarker`](../watermarker) с указанным путем к документу и параметрами загрузки. |
| [Watermarker](watermarker#constructor_7)(string, WatermarkerSettings) | Инициализирует новый экземпляр класса [`Watermarker`](../watermarker) с указанным путем к документу и настройками. |
| [Watermarker](watermarker#constructor_2)(Stream, LoadOptions, WatermarkerSettings) | Инициализирует новый экземпляр класса [`Watermarker`](../watermarker) с указанным потоком, параметрами загрузки и настройками. |
| [Watermarker](watermarker#constructor_6)(string, LoadOptions, WatermarkerSettings) | Инициализирует новый экземпляр класса [`Watermarker`](../watermarker) с указанным путем к документу, параметрами загрузки и настройками. |

## Свойства

| Имя | Описание |
| --- | --- |
| [SearchableObjects](../../groupdocs.watermark/watermarker/searchableobjects) { get; set; } | Получает или задает объекты контента, которые должны быть включены в поиск водяных знаков. |

## Методы

| Имя | Описание |
| --- | --- |
| [Add](../../groupdocs.watermark/watermarker/add#add)(Watermark) | Добавляет водяной знак в загруженный документ. |
| [Add](../../groupdocs.watermark/watermarker/add#add_1)(Watermark, WatermarkOptions) | Добавляет водяной знак в загруженный документ, используя параметры водяного знака. |
| [Dispose](../../groupdocs.watermark/watermarker/dispose)() | Освобождает текущий экземпляр. |
| [GeneratePreview](../../groupdocs.watermark/watermarker/generatepreview)(PreviewOptions) | Создаёт предварительные изображения для документа. |
| [GetContent&lt;T&gt;](../../groupdocs.watermark/watermarker/getcontent)() | Возвращает объект [`Content`](../../groupdocs.watermark.contents/content) для загруженного документа. |
| [GetDocumentInfo](../../groupdocs.watermark/watermarker/getdocumentinfo)() | Получает информацию о формате загруженного документа. |
| [GetImages](../../groupdocs.watermark/watermarker/getimages#getimages)() | Находит все изображения в документе. |
| [GetImages](../../groupdocs.watermark/watermarker/getimages#getimages_1)(ImageSearchCriteria) | Находит изображения согласно указанным критериям поиска. |
| [Remove](../../groupdocs.watermark/watermarker/remove#remove)(PossibleWatermark) | Удаляет водяной знак из документа. |
| [Remove](../../groupdocs.watermark/watermarker/remove#remove_1)(PossibleWatermarkCollection) | Удаляет все водяные знаки из коллекции в документе. |
| [Save](../../groupdocs.watermark/watermarker/save#save)() | Сохраняет данные документа во внутренний поток. |
| [Save](../../groupdocs.watermark/watermarker/save#save_1)(SaveOptions) | Сохраняет данные документа во внутренний поток, используя параметры сохранения. |
| [Save](../../groupdocs.watermark/watermarker/save#save_2)(Stream) | Сохраняет документ в указанный поток. |
| [Save](../../groupdocs.watermark/watermarker/save#save_4)(string) | Сохраняет документ в указанное файловое расположение. |
| [Save](../../groupdocs.watermark/watermarker/save#save_3)(Stream, SaveOptions) | Сохраняет документ в указанный поток, используя параметры сохранения. |
| [Save](../../groupdocs.watermark/watermarker/save#save_5)(string, SaveOptions) | Сохраняет документ в указанное файловое расположение, используя параметры сохранения. |
| [Search](../../groupdocs.watermark/watermarker/search#search)() | Ищет все возможные водяные знаки в документе. |
| [Search](../../groupdocs.watermark/watermarker/search#search_1)(SearchCriteria) | Ищет возможные водяные знаки согласно указанным критериям поиска. |

### Примеры

Загружает и сохраняет содержимое в любом поддерживаемом формате.

```csharp
// Загружает содержимое из файла.
using (Watermarker watermarker = new Watermarker("D:\\input.pdf"))
{
    // Используйте методы класса Watermarker для добавления, поиска или удаления водяных знаков.

    // Сохраняет изменения.
    watermarker.Save("D:\\output.pdf");
}
```

### См. также

* namespace [GroupDocs.Watermark](../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.watermark.dll -->
