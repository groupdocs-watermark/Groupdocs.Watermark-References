---
title: "Watermarker"
second_title: "GroupDocs.Watermark 的 .NET API 参考"
description: "使用指定的文档路径初始化 Watermarkergroupdocs.watermark/watermarker 类的新实例。"
type: docs
weight: 10
url: /zh/net/groupdocs.watermark/watermarker/watermarker/
---
## Watermarker(string) {#constructor_4}

使用指定的文档路径初始化 [`Watermarker`](../../watermarker) 类的新实例。

```csharp
public Watermarker(string filePath)
```

| 参数 | Type | 描述 |
| --- | --- | --- |
| filePath | String | 加载文档的文件路径。 |

### Exceptions

| exception | 条件 |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | 提供的文档类型不受支持。 |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | 提供的密码不正确。 |

### 备注

了解更多关于加载文档的信息: [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents)。

### 示例

加载并保存任何受支持格式的内容。

```csharp
// 从文件加载内容。
using (Watermarker watermarker = new Watermarker("D:\\input.pdf"))
{
    // 使用 Watermarker 类的方法来添加、搜索或移除水印。

    // 保存文档。
    watermarker.Save("D:\\output.pdf");
}
```

### 另请参阅

* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(string, LoadOptions) {#constructor_5}

使用指定的文档路径和加载选项初始化 [`Watermarker`](../../watermarker) 类的新实例。

```csharp
public Watermarker(string filePath, LoadOptions options)
```

| 参数 | Type | 描述 |
| --- | --- | --- |
| filePath | String | 加载文档的文件路径。 |
| 选项 | LoadOptions | 加载文档时使用的其他选项。 |

### Exceptions

| exception | 条件 |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | 提供的文档类型不受支持。 |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | 提供的密码不正确。 |

### 备注

了解更多关于加载文档的信息: [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents)。

### 示例

使用密码加载加密的 PDF 文档。

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
loadOptions.Password = "123";
using (Watermarker watermarker = new Watermarker(@"C:\Documents\test.pdf", loadOptions))
{
    // ...
}
```

### 另请参阅

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(string, WatermarkerSettings) {#constructor_7}

使用指定的文档路径和设置初始化 [`Watermarker`](../../watermarker) 类的新实例。

```csharp
public Watermarker(string filePath, WatermarkerSettings settings)
```

| 参数 | Type | 描述 |
| --- | --- | --- |
| filePath | String | 加载文档的文件路径。 |
| 设置 | WatermarkerSettings | 处理已加载文档时使用的附加设置。 |

### Exceptions

| exception | 条件 |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | 提供的文档类型不受支持。 |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | 提供的密码不正确。 |

### 备注

了解更多关于加载文档的信息: [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents)。

### 示例

全局设置可搜索对象（适用于之后加载的所有文档）。

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

        // 处理已找到水印的代码放在此处。
    }
}
```

### 另请参阅

* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(string, LoadOptions, WatermarkerSettings) {#constructor_6}

使用指定的文档路径、加载选项和设置初始化 [`Watermarker`](../../watermarker) 类的新实例。

```csharp
public Watermarker(string filePath, LoadOptions options, WatermarkerSettings settings)
```

| 参数 | Type | 描述 |
| --- | --- | --- |
| filePath | String | 加载文档的文件路径。 |
| 选项 | LoadOptions | 加载文档时使用的其他选项。 |
| 设置 | WatermarkerSettings | 处理已加载文档时使用的附加设置。 |

### Exceptions

| exception | 条件 |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | 提供的文档类型不受支持。 |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | 提供的密码不正确。 |

### 备注

了解更多关于加载文档的信息: [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents)。

### 示例

在电子邮件正文/主题中查找特定文本片段。

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
    // 注意，只有在将 TextSearchCriteria 实例传递给 Search 方法时才会执行搜索
    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    // 删除已找到的文本片段
    watermarks.Clear();
    // 保存更改
    watermarker.Save();
}
```

### 另请参阅

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream) {#constructor}

使用指定的流初始化 [`Watermarker`](../../watermarker) 类的新实例。

```csharp
public Watermarker(Stream document)
```

| 参数 | Type | 描述 |
| --- | --- | --- |
| 文档 | Stream | 用于加载文档的流。 |

### Exceptions

| exception | 条件 |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | 提供的文档类型不受支持。 |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | 提供的密码不正确。 |

### 备注

了解有关加载文档的更多信息 [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents)。

### 示例

加载并保存任何受支持格式的文档。

```csharp
// 从流加载内容。
using (FileStream inputStream = File.Open("D:\\input.pdf", FileMode.Open))
using (FileStream outputStream = File.Open("D:\\output.pdf", FileMode.Create))
using (Watermarker watermarker = new Watermarker(inputStream))
{
    // 使用 Watermarker 类的方法来添加、搜索或移除水印。

    // 保存更改。
    watermarker.Save(outputStream);
}
```

### 另请参阅

* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, LoadOptions) {#constructor_1}

使用指定的流和加载选项初始化 [`Watermarker`](../../watermarker) 类的新实例。

```csharp
public Watermarker(Stream document, LoadOptions options)
```

| 参数 | Type | 描述 |
| --- | --- | --- |
| 文档 | Stream | 用于加载文档的流。 |
| 选项 | LoadOptions | 加载文档时使用的其他选项。 |

### Exceptions

| exception | 条件 |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | 提供的文档类型不受支持。 |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | 提供的密码不正确。 |

### 备注

了解有关加载文档的更多信息 [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents)。

### 示例

使用密码加载加密的 PDF 文档

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
loadOptions.Password = "123";
using (FileStream fileStream = File.Open(@"C:\Documents\test.pdf", FileMode.Open))
using (Watermarker watermarker = new Watermarker(fileStream, loadOptions))
{
    // ...
}
```

### 另请参阅

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, WatermarkerSettings) {#constructor_3}

使用指定的流和设置初始化 [`Watermarker`](../../watermarker) 类的新实例。

```csharp
public Watermarker(Stream document, WatermarkerSettings settings)
```

| 参数 | Type | 描述 |
| --- | --- | --- |
| 文档 | Stream | 用于加载文档的流。 |
| 设置 | WatermarkerSettings | 处理已加载文档时使用的附加设置。 |

### Exceptions

| exception | 条件 |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | 提供的文档类型不受支持。 |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | 提供的密码不正确。 |

### 备注

了解有关加载文档的更多信息 [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents)。

### 示例

全局设置可搜索对象（适用于之后加载的所有文档）。

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

        // 处理已找到水印的代码放在此处。
    }
}
```

### 另请参阅

* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, LoadOptions, WatermarkerSettings) {#constructor_2}

使用指定的流、加载选项和设置初始化 [`Watermarker`](../../watermarker) 类的新实例。

```csharp
public Watermarker(Stream document, LoadOptions options, WatermarkerSettings settings)
```

| 参数 | Type | 描述 |
| --- | --- | --- |
| 文档 | Stream | 用于加载文档的流。 |
| 选项 | LoadOptions | 加载文档时使用的其他选项。 |
| 设置 | WatermarkerSettings | 处理已加载文档时使用的附加设置。 |

### Exceptions

| exception | 条件 |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | 提供的文档类型不受支持。 |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | 提供的密码不正确。 |

### 备注

了解有关加载文档的更多信息 [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents)。

### 示例

在电子邮件正文/主题中查找特定文本片段。

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
    // 注意，只有在将 TextSearchCriteria 实例传递给 Search 方法时才会执行搜索
    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    // 删除已找到的文本片段
    watermarks.Clear();
    // 保存更改
    watermarker.Save();
}
```

### 另请参阅

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- 请勿编辑：由 xmldoccmd 为 GroupDocs.watermark.dll 生成 -->
