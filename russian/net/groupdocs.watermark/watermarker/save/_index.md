---
title: Save
second_title: Справочник по API GroupDocs.Watermark для .NET
description: Сохраняет данные документа в базовый поток.
type: docs
weight: 100
url: /ru/net/groupdocs.watermark/watermarker/save/
---
## Save() {#save}

Сохраняет данные документа в базовый поток.

```csharp
public void Save()
```

### Примечания

Подробнее о сохранении документов [Сохранение документов](https://docs.groupdocs.com/display/watermarknet/Saving+documents) .

### Примеры

Удалите определенные текстовые фрагменты из тела/темы сообщения электронной почты и сохраните сообщение электронной почты.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\test.msg"))
{
    SearchCriteria criteria = new TextSearchCriteria("test", false);
    // Обратите внимание, поиск выполняется только в том случае, если вы передаете экземпляр TextSearchCriteria в метод Search
    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    // Удаляем найденные фрагменты текста
    watermarker.Remove(watermarks);
    // Сохранить изменения
    watermarker.Save();
}
```

### Смотрите также

* class [Watermarker](../../watermarker)
* пространство имен [GroupDocs.Watermark](../../watermarker)
* сборка [GroupDocs.Watermark](../../../)

---

## Save(string) {#save_4}

Сохраняет документ в указанном месте файла.

```csharp
public void Save(string filePath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | String | Путь к файлу для сохранения данных документа. |

### Примечания

Подробнее о сохранении документов [Сохранение документов](https://docs.groupdocs.com/display/watermarknet/Saving+documents) .

### Примеры

Добавьте водяной знак и сохраните документ в другой файл.

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{                                                                                   
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);                                            
    watermarker.Save("ouput.pdf");                                   
}                                                                                   
```

### Смотрите также

* class [Watermarker](../../watermarker)
* пространство имен [GroupDocs.Watermark](../../watermarker)
* сборка [GroupDocs.Watermark](../../../)

---

## Save(Stream) {#save_2}

Сохраняет документ в указанный поток.

```csharp
public void Save(Stream document)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | Stream | Поток для сохранения данных документа. |

### Примечания

Подробнее о сохранении документов [Сохранение документов](https://docs.groupdocs.com/display/watermarknet/Saving+documents) .

### Примеры

Добавьте водяной знак и сохраните документ в потоке памяти.

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);
    using (MemoryStream stream = new MemoryStream())
    {
        watermarker.Save(stream);
        // ...
    }
}
```

### Смотрите также

* class [Watermarker](../../watermarker)
* пространство имен [GroupDocs.Watermark](../../watermarker)
* сборка [GroupDocs.Watermark](../../../)

---

## Save(SaveOptions) {#save_1}

Сохраняет данные документа в базовый поток, используя параметры сохранения.

```csharp
public void Save(SaveOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| options | SaveOptions | Дополнительные параметры для использования при сохранении документа. |

### Примечания

Подробнее о сохранении документов [Сохранение документов](https://docs.groupdocs.com/display/watermarknet/Saving+documents) .

### Примеры

Добавить водяной знак и сохранить документ по умолчанию[`SaveOptions`](../../../groupdocs.watermark.options/saveoptions) .

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);
    watermarker.Save(new SaveOptions());
}
```

### Смотрите также

* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* пространство имен [GroupDocs.Watermark](../../watermarker)
* сборка [GroupDocs.Watermark](../../../)

---

## Save(string, SaveOptions) {#save_5}

Сохраняет документ в указанное место файла с помощью параметров сохранения.

```csharp
public void Save(string filePath, SaveOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | String | Путь к файлу для сохранения данных документа. |
| options | SaveOptions | Дополнительные параметры для использования при сохранении документа. |

### Примечания

Подробнее о сохранении документов [Сохранение документов](https://docs.groupdocs.com/display/watermarknet/Saving+documents) .

### Примеры

Добавьте водяной знак и сохраните документ в другой файл по умолчанию[`SaveOptions`](../../../groupdocs.watermark.options/saveoptions) .

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{                                                                                   
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);                                            
    watermarker.Save("ouput.pdf", new SaveOptions());
}                                                                                   
```

### Смотрите также

* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* пространство имен [GroupDocs.Watermark](../../watermarker)
* сборка [GroupDocs.Watermark](../../../)

---

## Save(Stream, SaveOptions) {#save_3}

Сохраняет документ в указанный поток, используя параметры сохранения.

```csharp
public void Save(Stream document, SaveOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | Stream | Поток для сохранения данных документа. |
| options | SaveOptions | Дополнительные параметры для использования при сохранении документа. |

### Примечания

Подробнее о сохранении документов [Сохранение документов](https://docs.groupdocs.com/display/watermarknet/Saving+documents) .

### Примеры

Добавить водяной знак и сохранить документ в потоке памяти по умолчанию[`SaveOptions`](../../../groupdocs.watermark.options/saveoptions) .

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);
    using (MemoryStream stream = new MemoryStream())
    {
        watermarker.Save(stream, new SaveOptions());
        // ...
    }
}
```

### Смотрите также

* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* пространство имен [GroupDocs.Watermark](../../watermarker)
* сборка [GroupDocs.Watermark](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
