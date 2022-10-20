---
title: Watermarker
second_title: Справочник по API GroupDocs.Watermark для .NET
description: Инициализирует новый экземплярWatermarkergroupdocs.watermark/watermarker класс с указанным путем к документу.
type: docs
weight: 10
url: /ru/net/groupdocs.watermark/watermarker/watermarker/
---
## Watermarker(string) {#constructor_4}

Инициализирует новый экземпляр[`Watermarker`](../../watermarker) класс с указанным путем к документу.

```csharp
public Watermarker(string filePath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | String | Путь к файлу, из которого нужно загрузить документ. |

### Исключения

| исключение | условие |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Предоставленный тип документа не поддерживается. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Предоставленный пароль неверен. |

### Примечания

Подробнее о загрузке документов: [Загрузка документов](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### Примеры

Загружать и сохранять содержимое любого поддерживаемого формата.

```csharp
// Загрузить содержимое из файла.
using (Watermarker watermarker = new Watermarker("D:\\input.pdf"))
{
    // Используйте методы класса Watermarker для добавления, поиска или удаления водяных знаков.

    // Сохраняем документ.
    watermarker.Save("D:\\output.pdf");
}
```

### Смотрите также

* class [Watermarker](../../watermarker)
* пространство имен [GroupDocs.Watermark](../../watermarker)
* сборка [GroupDocs.Watermark](../../../)

---

## Watermarker(string, LoadOptions) {#constructor_5}

Инициализирует новый экземпляр[`Watermarker`](../../watermarker)класс с указанным путем к документу и параметрами загрузки.

```csharp
public Watermarker(string filePath, LoadOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | String | Путь к файлу, из которого нужно загрузить документ. |
| options | LoadOptions | Дополнительные параметры для использования при загрузке документа. |

### Исключения

| исключение | условие |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Предоставленный тип документа не поддерживается. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Предоставленный пароль неверен. |

### Примечания

Подробнее о загрузке документов: [Загрузка документов](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### Примеры

Загрузить зашифрованный PDF-документ с использованием пароля.

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
loadOptions.Password = "123";
using (Watermarker watermarker = new Watermarker(@"C:\Documents\test.pdf", loadOptions))
{
    // ...
}
```

### Смотрите также

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [Watermarker](../../watermarker)
* пространство имен [GroupDocs.Watermark](../../watermarker)
* сборка [GroupDocs.Watermark](../../../)

---

## Watermarker(string, WatermarkerSettings) {#constructor_7}

Инициализирует новый экземпляр[`Watermarker`](../../watermarker) класс с указанным путем к документу и настройками.

```csharp
public Watermarker(string filePath, WatermarkerSettings settings)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | String | Путь к файлу, из которого нужно загрузить документ. |
| settings | WatermarkerSettings | Дополнительные настройки для использования при работе с загруженным документом. |

### Исключения

| исключение | условие |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Предоставленный тип документа не поддерживается. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Предоставленный пароль неверен. |

### Примечания

Подробнее о загрузке документов: [Загрузка документов](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### Примеры

Установить доступные для поиска объекты глобально (для всех документов, которые будут загружены после этого).

```csharp
WatermarkerSettings settings = new WatermarkerSettings();
settings.SearchableObjects = new SearchableObjects
{
    WordProcessingSearchableObjects = WordProcessingSearchableObjects.Hyperlinks
                                    | WordProcessingSearchableObjects.Text,
    SpreadsheetSearchableObjects = SpreadsheetSearchableObjects.HeadersFooters,
    PresentationSearchableObjects = PresentationSearchableObjects.SlidesBackgrounds
                                  | PresentationSearchableObjects.Shapes,
    DiagramSearchableObjects = DiagramSearchableObjects.None,
    PdfSearchableObjects = PdfSearchableObjects.All
};

foreach (string file in Directory.GetFiles(@"D:\files"))
{
    using (Watermarker watermarker = new Watermarker(file, settings))
    {
        PossibleWatermarkCollection watermarks = watermarker.Search();

        // Здесь находится код для работы с найденными водяными знаками.
    }
}
```

### Смотрите также

* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* пространство имен [GroupDocs.Watermark](../../watermarker)
* сборка [GroupDocs.Watermark](../../../)

---

## Watermarker(string, LoadOptions, WatermarkerSettings) {#constructor_6}

Инициализирует новый экземпляр[`Watermarker`](../../watermarker) класс с указанным путем к документу, параметрами загрузки и настройками.

```csharp
public Watermarker(string filePath, LoadOptions options, WatermarkerSettings settings)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | String | Путь к файлу, из которого нужно загрузить документ. |
| options | LoadOptions | Дополнительные параметры для использования при загрузке документа. |
| settings | WatermarkerSettings | Дополнительные настройки для использования при работе с загруженным документом. |

### Исключения

| исключение | условие |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Предоставленный тип документа не поддерживается. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Предоставленный пароль неверен. |

### Примечания

Подробнее о загрузке документов: [Загрузка документов](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### Примеры

Найти определенные текстовые фрагменты в теле/теме сообщения электронной почты.

```csharp
WatermarkerSettings settings = new WatermarkerSettings();
settings.SearchableObjects = new SearchableObjects
{
    EmailSearchableObjects = EmailSearchableObjects.Subject
                           | EmailSearchableObjects.HtmlBody
                           | EmailSearchableObjects.PlainTextBody
};
EmailLoadOptions loadOptions = new EmailLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\test.msg", loadOptions, settings))
{
    SearchCriteria criteria = new TextSearchCriteria("test", false);
    // Обратите внимание, поиск выполняется только в том случае, если вы передаете экземпляр TextSearchCriteria в метод Search
    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    // Удаляем найденные фрагменты текста
    watermarks.Clear();
    // Сохранить изменения
    watermarker.Save();
}
```

### Смотрите также

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* пространство имен [GroupDocs.Watermark](../../watermarker)
* сборка [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream) {#constructor}

Инициализирует новый экземпляр[`Watermarker`](../../watermarker) класс с указанным потоком.

```csharp
public Watermarker(Stream document)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | Stream | Поток, из которого загружается документ. |

### Исключения

| исключение | условие |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Предоставленный тип документа не поддерживается. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Предоставленный пароль неверен. |

### Примечания

Подробнее о загрузке документов [Загрузка документов](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### Примеры

Загрузить и сохранить документ любого поддерживаемого формата.

```csharp
// Загружаем содержимое из потока.
using (FileStream inputStream = File.Open("D:\\input.pdf", FileMode.Open))
using (FileStream outputStream = File.Open("D:\\output.pdf", FileMode.Create))
using (Watermarker watermarker = new Watermarker(inputStream))
{
    // Используйте методы класса Watermarker для добавления, поиска или удаления водяных знаков.

    // Сохранить изменения.
    watermarker.Save(outputStream);
}
```

### Смотрите также

* class [Watermarker](../../watermarker)
* пространство имен [GroupDocs.Watermark](../../watermarker)
* сборка [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, LoadOptions) {#constructor_1}

Инициализирует новый экземпляр[`Watermarker`](../../watermarker) класс с указанным stream и параметрами загрузки.

```csharp
public Watermarker(Stream document, LoadOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | Stream | Поток, из которого загружается документ. |
| options | LoadOptions | Дополнительные параметры для использования при загрузке документа. |

### Исключения

| исключение | условие |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Предоставленный тип документа не поддерживается. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Предоставленный пароль неверен. |

### Примечания

Подробнее о загрузке документов [Загрузка документов](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### Примеры

Загрузить зашифрованный PDF-документ, используя пароль

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
loadOptions.Password = "123";
using (FileStream fileStream = File.Open(@"C:\Documents\test.pdf", FileMode.Open))
using (Watermarker watermarker = new Watermarker(fileStream, loadOptions))
{
    // ...
}
```

### Смотрите также

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [Watermarker](../../watermarker)
* пространство имен [GroupDocs.Watermark](../../watermarker)
* сборка [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, WatermarkerSettings) {#constructor_3}

Инициализирует новый экземпляр[`Watermarker`](../../watermarker) class с указанным stream и settings.

```csharp
public Watermarker(Stream document, WatermarkerSettings settings)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | Stream | Поток, из которого загружается документ. |
| settings | WatermarkerSettings | Дополнительные настройки для использования при работе с загруженным документом. |

### Исключения

| исключение | условие |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Предоставленный тип документа не поддерживается. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Предоставленный пароль неверен. |

### Примечания

Подробнее о загрузке документов [Загрузка документов](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### Примеры

Установить доступные для поиска объекты глобально (для всех документов, которые будут загружены после этого).

```csharp
WatermarkerSettings settings = new WatermarkerSettings();
settings.SearchableObjects = new SearchableObjects
{
    WordProcessingSearchableObjects = WordProcessingSearchableObjects.Hyperlinks
                                    | WordProcessingSearchableObjects.Text,
    SpreadsheetSearchableObjects = SpreadsheetSearchableObjects.HeadersFooters,
    PresentationSearchableObjects = PresentationSearchableObjects.SlidesBackgrounds
                                  | PresentationSearchableObjects.Shapes,
    DiagramSearchableObjects = DiagramSearchableObjects.None,
    PdfSearchableObjects = PdfSearchableObjects.All
};

foreach (string file in Directory.GetFiles(@"D:\files"))
{
    using (FileStream fileStream = File.Open(file, FileMode.Open))
    using (Watermarker watermarker = new Watermarker(fileStream, settings))
    {
        PossibleWatermarkCollection watermarks = watermarker.Search();

        // Здесь находится код для работы с найденными водяными знаками.
    }
}
```

### Смотрите также

* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* пространство имен [GroupDocs.Watermark](../../watermarker)
* сборка [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, LoadOptions, WatermarkerSettings) {#constructor_2}

Инициализирует новый экземпляр[`Watermarker`](../../watermarker) класс с указанным потоком, параметры загрузки и настройки.

```csharp
public Watermarker(Stream document, LoadOptions options, WatermarkerSettings settings)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | Stream | Поток, из которого загружается документ. |
| options | LoadOptions | Дополнительные параметры для использования при загрузке документа. |
| settings | WatermarkerSettings | Дополнительные настройки для использования при работе с загруженным документом. |

### Исключения

| исключение | условие |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Предоставленный тип документа не поддерживается. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Предоставленный пароль неверен. |

### Примечания

Подробнее о загрузке документов [Загрузка документов](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### Примеры

Найти определенные текстовые фрагменты в теле/теме сообщения электронной почты.

```csharp
WatermarkerSettings settings = new WatermarkerSettings();
settings.SearchableObjects = new SearchableObjects
{
    EmailSearchableObjects = EmailSearchableObjects.Subject
                           | EmailSearchableObjects.HtmlBody
                           | EmailSearchableObjects.PlainTextBody
};
EmailLoadOptions loadOptions = new EmailLoadOptions();
using (FileStream fileStream = File.Open(@"D:\test.msg", FileMode.Open))
using (Watermarker watermarker = new Watermarker(fileStream, loadOptions, settings))
{
    SearchCriteria criteria = new TextSearchCriteria("test", false);
    // Обратите внимание, поиск выполняется только в том случае, если вы передаете экземпляр TextSearchCriteria в метод Search
    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    // Удаляем найденные фрагменты текста
    watermarks.Clear();
    // Сохранить изменения
    watermarker.Save();
}
```

### Смотрите также

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* пространство имен [GroupDocs.Watermark](../../watermarker)
* сборка [GroupDocs.Watermark](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
