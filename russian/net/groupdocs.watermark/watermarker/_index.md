---
title: Watermarker
second_title: Справочник по API GroupDocs.Watermark для .NET
description: Представляет класс для управления водяными знаками в документе.
type: docs
weight: 3060
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
| [Watermarker](watermarker#constructor)(Stream) | Инициализирует новый экземпляр[`Watermarker`](../watermarker) класс с указанным потоком. |
| [Watermarker](watermarker#constructor_4)(string) | Инициализирует новый экземпляр[`Watermarker`](../watermarker) класс с указанным путем к документу. |
| [Watermarker](watermarker#constructor_1)(Stream, LoadOptions) | Инициализирует новый экземпляр[`Watermarker`](../watermarker) класс с указанным stream и параметрами загрузки. |
| [Watermarker](watermarker#constructor_3)(Stream, WatermarkerSettings) | Инициализирует новый экземпляр[`Watermarker`](../watermarker) class с указанным stream и settings. |
| [Watermarker](watermarker#constructor_5)(string, LoadOptions) | Инициализирует новый экземпляр[`Watermarker`](../watermarker)класс с указанным путем к документу и параметрами загрузки. |
| [Watermarker](watermarker#constructor_7)(string, WatermarkerSettings) | Инициализирует новый экземпляр[`Watermarker`](../watermarker) класс с указанным путем к документу и настройками. |
| [Watermarker](watermarker#constructor_2)(Stream, LoadOptions, WatermarkerSettings) | Инициализирует новый экземпляр[`Watermarker`](../watermarker) класс с указанным потоком, параметры загрузки и настройки. |
| [Watermarker](watermarker#constructor_6)(string, LoadOptions, WatermarkerSettings) | Инициализирует новый экземпляр[`Watermarker`](../watermarker) класс с указанным путем к документу, параметрами загрузки и настройками. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [SearchableObjects](../../groupdocs.watermark/watermarker/searchableobjects) { get; set; } | Получает или задает объекты содержимого, которые должны быть включены в поиск водяных знаков. |

## Методы

| Имя | Описание |
| --- | --- |
| [Add](../../groupdocs.watermark/watermarker/add#add)(Watermark) | Добавляет водяной знак к загруженному документу. |
| [Add](../../groupdocs.watermark/watermarker/add#add_1)(Watermark, WatermarkOptions) | Добавляет водяной знак в загруженный документ с помощью параметров водяного знака. |
| [Dispose](../../groupdocs.watermark/watermarker/dispose)() | Удаляет текущий экземпляр. |
| [GeneratePreview](../../groupdocs.watermark/watermarker/generatepreview)(PreviewOptions) | Генерирует изображения предварительного просмотра для документа. |
| [GetContent&lt;T&gt;](../../groupdocs.watermark/watermarker/getcontent)() | Возвращает[`Content`](../../groupdocs.watermark.contents/content) объект для загруженного документа. |
| [GetDocumentInfo](../../groupdocs.watermark/watermarker/getdocumentinfo)() | Получает информацию о формате загруженного документа. |
| [GetImages](../../groupdocs.watermark/watermarker/getimages#getimages)() | Находит все изображения в документе. |
| [GetImages](../../groupdocs.watermark/watermarker/getimages#getimages_1)(ImageSearchCriteria) | Находит изображения по заданным критериям поиска. |
| [Remove](../../groupdocs.watermark/watermarker/remove#remove)(PossibleWatermark) | Удаляет водяной знак из документа. |
| [Remove](../../groupdocs.watermark/watermarker/remove#remove_1)(PossibleWatermarkCollection) | Удаляет все водяные знаки коллекции из документа. |
| [Save](../../groupdocs.watermark/watermarker/save#save)() | Сохраняет данные документа в базовый поток. |
| [Save](../../groupdocs.watermark/watermarker/save#save_1)(SaveOptions) | Сохраняет данные документа в базовый поток, используя параметры сохранения. |
| [Save](../../groupdocs.watermark/watermarker/save#save_2)(Stream) | Сохраняет документ в указанный поток. |
| [Save](../../groupdocs.watermark/watermarker/save#save_4)(string) | Сохраняет документ в указанном месте файла. |
| [Save](../../groupdocs.watermark/watermarker/save#save_3)(Stream, SaveOptions) | Сохраняет документ в указанный поток, используя параметры сохранения. |
| [Save](../../groupdocs.watermark/watermarker/save#save_5)(string, SaveOptions) | Сохраняет документ в указанное место файла с помощью параметров сохранения. |
| [Search](../../groupdocs.watermark/watermarker/search#search)() | Поиск всех возможных водяных знаков в документе. |
| [Search](../../groupdocs.watermark/watermarker/search#search_1)(SearchCriteria) | Ищет возможные водяные знаки в соответствии с указанными критериями поиска. |

### Примеры

Загружать и сохранять содержимое любого поддерживаемого формата.

```csharp
// Загрузить содержимое из файла.
using (Watermarker watermarker = new Watermarker("D:\\input.pdf"))
{
    // Используйте методы класса Watermarker для добавления, поиска или удаления водяных знаков.

    // Сохранить изменения.
    watermarker.Save("D:\\output.pdf");
}
```

### Смотрите также

* пространство имен [GroupDocs.Watermark](../../groupdocs.watermark)
* сборка [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
