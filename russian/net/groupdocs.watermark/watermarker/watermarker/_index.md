---
title: "Watermarker"
second_title: "GroupDocs.Watermark для .NET API Справка"
description: "Инициализирует новый экземпляр класса Watermarkergroupdocs.watermark/watermarker с указанным путём к документу."
type: docs
weight: 10
url: /ru/net/groupdocs.watermark/watermarker/watermarker/
---
## Watermarker(string) {#constructor_4}

Инициализирует новый экземпляр класса [`Watermarker`](../../watermarker) с указанным путём к документу.

```csharp
public Watermarker(string filePath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | String | Путь к файлу для загрузки документа. |

### Исключения

| исключение | условие |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Указанный тип документа не поддерживается. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Указанный пароль неверен. |

### Примечания

Узнайте больше о загрузке документов: [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### Примеры

Загружает и сохраняет содержимое в любом поддерживаемом формате.

```csharp
// Загружает содержимое из файла.
using (Watermarker watermarker = new Watermarker("D:\\input.pdf"))
{
    // Используйте методы класса Watermarker для добавления, поиска или удаления водяных знаков.

    // Сохраните документ.
    watermarker.Save("D:\\output.pdf");
}
```

### См. также

* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(string, LoadOptions) {#constructor_5}

Инициализирует новый экземпляр класса [`Watermarker`](../../watermarker) с указанным путём к документу и параметрами загрузки.

```csharp
public Watermarker(string filePath, LoadOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | String | Путь к файлу для загрузки документа. |
| options | LoadOptions | Дополнительные параметры, используемые при загрузке документа. |

### Исключения

| исключение | условие |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Указанный тип документа не поддерживается. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Указанный пароль неверен. |

### Примечания

Узнайте больше о загрузке документов: [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### Примеры

Загрузить зашифрованный PDF‑документ, используя пароль.

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
loadOptions.Password = "123";
using (Watermarker watermarker = new Watermarker(@"C:\Documents\test.pdf", loadOptions))
{
    // ...
}
```

### См. также

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(string, WatermarkerSettings) {#constructor_7}

Инициализирует новый экземпляр класса [`Watermarker`](../../watermarker) с указанным путём к документу и настройками.

```csharp
public Watermarker(string filePath, WatermarkerSettings settings)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | String | Путь к файлу для загрузки документа. |
| настройки | WatermarkerSettings | Дополнительные настройки, используемые при работе с загруженным документом. |

### Исключения

| исключение | условие |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Указанный тип документа не поддерживается. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Указанный пароль неверен. |

### Примечания

Узнайте больше о загрузке документов: [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### Примеры

Установите поисковые объекты глобально (для всех документов, которые будут загружены после этого).

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

        // Код для работы с найденными водяными знаками размещён здесь.
    }
}
```

### См. также

* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(string, LoadOptions, WatermarkerSettings) {#constructor_6}

Инициализирует новый экземпляр класса [`Watermarker`](../../watermarker) с указанным путём к документу, параметрами загрузки и настройками.

```csharp
public Watermarker(string filePath, LoadOptions options, WatermarkerSettings settings)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | String | Путь к файлу для загрузки документа. |
| options | LoadOptions | Дополнительные параметры, используемые при загрузке документа. |
| настройки | WatermarkerSettings | Дополнительные настройки, используемые при работе с загруженным документом. |

### Исключения

| исключение | условие |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Указанный тип документа не поддерживается. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Указанный пароль неверен. |

### Примечания

Узнайте больше о загрузке документов: [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### Примеры

Найдите определённые фрагменты текста в теле/теме электронного письма.

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
    // Примечание, поиск выполняется только если передать экземпляр TextSearchCriteria в метод Search
    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    // Удалить найденные фрагменты текста
    watermarks.Clear();
    // Сохранить изменения
    watermarker.Save();
}
```

### См. также

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream) {#constructor}

Инициализирует новый экземпляр класса [`Watermarker`](../../watermarker) с указанным потоком.

```csharp
public Watermarker(Stream document)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| документ | Поток | Поток, из которого загружается документ. |

### Исключения

| исключение | условие |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Указанный тип документа не поддерживается. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Указанный пароль неверен. |

### Примечания

Узнайте больше о загрузке документов [Загрузка документов](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### Примеры

Загрузить и сохранить документ в любом поддерживаемом формате.

```csharp
// Загрузить содержимое из потока.
using (FileStream inputStream = File.Open("D:\\input.pdf", FileMode.Open))
using (FileStream outputStream = File.Open("D:\\output.pdf", FileMode.Create))
using (Watermarker watermarker = new Watermarker(inputStream))
{
    // Используйте методы класса Watermarker для добавления, поиска или удаления водяных знаков.

    // Сохраняет изменения.
    watermarker.Save(outputStream);
}
```

### См. также

* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, LoadOptions) {#constructor_1}

Инициализирует новый экземпляр класса [`Watermarker`](../../watermarker) с указанным потоком и параметрами загрузки.

```csharp
public Watermarker(Stream document, LoadOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| документ | Поток | Поток, из которого загружается документ. |
| options | LoadOptions | Дополнительные параметры, используемые при загрузке документа. |

### Исключения

| исключение | условие |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Указанный тип документа не поддерживается. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Указанный пароль неверен. |

### Примечания

Узнайте больше о загрузке документов [Загрузка документов](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### Примеры

Загрузить зашифрованный PDF-документ с использованием пароля

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
loadOptions.Password = "123";
using (FileStream fileStream = File.Open(@"C:\Documents\test.pdf", FileMode.Open))
using (Watermarker watermarker = new Watermarker(fileStream, loadOptions))
{
    // ...
}
```

### См. также

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, WatermarkerSettings) {#constructor_3}

Инициализирует новый экземпляр класса [`Watermarker`](../../watermarker) с указанным потоком и настройками.

```csharp
public Watermarker(Stream document, WatermarkerSettings settings)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| документ | Поток | Поток, из которого загружается документ. |
| настройки | WatermarkerSettings | Дополнительные настройки, используемые при работе с загруженным документом. |

### Исключения

| исключение | условие |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Указанный тип документа не поддерживается. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Указанный пароль неверен. |

### Примечания

Узнайте больше о загрузке документов [Загрузка документов](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### Примеры

Установите поисковые объекты глобально (для всех документов, которые будут загружены после этого).

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

        // Код для работы с найденными водяными знаками размещён здесь.
    }
}
```

### См. также

* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, LoadOptions, WatermarkerSettings) {#constructor_2}

Инициализирует новый экземпляр класса [`Watermarker`](../../watermarker) с указанным потоком, параметрами загрузки и настройками.

```csharp
public Watermarker(Stream document, LoadOptions options, WatermarkerSettings settings)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| документ | Поток | Поток, из которого загружается документ. |
| options | LoadOptions | Дополнительные параметры, используемые при загрузке документа. |
| настройки | WatermarkerSettings | Дополнительные настройки, используемые при работе с загруженным документом. |

### Исключения

| исключение | условие |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Указанный тип документа не поддерживается. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Указанный пароль неверен. |

### Примечания

Узнайте больше о загрузке документов [Загрузка документов](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### Примеры

Найдите определённые фрагменты текста в теле/теме электронного письма.

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
    // Примечание, поиск выполняется только если передать экземпляр TextSearchCriteria в метод Search
    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    // Удалить найденные фрагменты текста
    watermarks.Clear();
    // Сохранить изменения
    watermarker.Save();
}
```

### См. также

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.watermark.dll -->
