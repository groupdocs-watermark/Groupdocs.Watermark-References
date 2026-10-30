---
title: "Сохранить"
second_title: "GroupDocs.Watermark для .NET API Справка"
description: "Сохраняет данные документа во внутренний поток."
type: docs
weight: 100
url: /ru/net/groupdocs.watermark/watermarker/save/
---
## Save() {#save}

Сохраняет данные документа во внутренний поток.

```csharp
public WatermarkResult Save()
```

### Примечания

Узнайте больше о сохранении документов [Сохранение документов](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### Примеры

Удалить определённые фрагменты текста из тела/темы электронного сообщения и сохранить сообщение.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\test.msg"))
{
    SearchCriteria criteria = new TextSearchCriteria("test", false);
    // Примечание, поиск выполняется только если передать экземпляр TextSearchCriteria в метод Search
    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    // Удалить найденные фрагменты текста
    watermarker.Remove(watermarks);
    // Сохранить изменения
    watermarker.Save();
}
```

### См. также

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Save(string) {#save_4}

Сохраняет документ в указанное файловое расположение.

```csharp
public WatermarkResult Save(string filePath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | String | Путь к файлу, в который сохраняются данные документа. |

### Примечания

Узнайте больше о сохранении документов [Сохранение документов](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### Примеры

Добавить водяной знак и сохранить документ в другой файл.

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{                                                                                   
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);                                            
    watermarker.Save("ouput.pdf");                                   
}                                                                                   
```

### См. также

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Save(Stream) {#save_2}

Сохраняет документ в указанный поток.

```csharp
public WatermarkResult Save(Stream document)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| документ | Поток | Поток, в который сохраняются данные документа. |

### Примечания

Узнайте больше о сохранении документов [Сохранение документов](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### Примеры

Добавить водяной знак и сохранить документ в поток памяти.

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

### См. также

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Save(SaveOptions) {#save_1}

Сохраняет данные документа во внутренний поток, используя параметры сохранения.

```csharp
public WatermarkResult Save(SaveOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| options | SaveOptions | Дополнительные параметры, используемые при сохранении документа. |

### Примечания

Узнайте больше о сохранении документов [Сохранение документов](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### Примеры

Добавьте водяной знак и сохраните документ с параметрами по умолчанию [`SaveOptions`](../../../groupdocs.watermark.options/saveoptions).

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);
    watermarker.Save(new SaveOptions());
}
```

### См. также

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Save(string, SaveOptions) {#save_5}

Сохраняет документ в указанное файловое расположение, используя параметры сохранения.

```csharp
public WatermarkResult Save(string filePath, SaveOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | String | Путь к файлу, в который сохраняются данные документа. |
| options | SaveOptions | Дополнительные параметры, используемые при сохранении документа. |

### Примечания

Узнайте больше о сохранении документов [Сохранение документов](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### Примеры

Добавьте водяной знак и сохраните документ в другой файл с параметрами по умолчанию [`SaveOptions`](../../../groupdocs.watermark.options/saveoptions).

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{                                                                                   
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);                                            
    watermarker.Save("ouput.pdf", new SaveOptions());
}                                                                                   
```

### См. также

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Save(Stream, SaveOptions) {#save_3}

Сохраняет документ в указанный поток, используя параметры сохранения.

```csharp
public WatermarkResult Save(Stream document, SaveOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| документ | Поток | Поток, в который сохраняются данные документа. |
| options | SaveOptions | Дополнительные параметры, используемые при сохранении документа. |

### Примечания

Узнайте больше о сохранении документов [Сохранение документов](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### Примеры

Добавьте водяной знак и сохраните документ в поток памяти с параметрами по умолчанию [`SaveOptions`](../../../groupdocs.watermark.options/saveoptions).

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

### См. также

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.watermark.dll -->
