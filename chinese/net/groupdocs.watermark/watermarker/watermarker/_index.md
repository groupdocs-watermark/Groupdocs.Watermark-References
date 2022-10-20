---
title: Watermarker
second_title: .NET API 参考的 GroupDocs.Watermark
description: 初始化Watermarkergroupdocs.watermark/watermarker具有指定文档路径的类
type: docs
weight: 10
url: /zh/net/groupdocs.watermark/watermarker/watermarker/
---
## Watermarker(string) {#constructor_4}

初始化[`Watermarker`](../../watermarker)具有指定文档路径的类。

```csharp
public Watermarker(string filePath)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 从中加载文档的文件路径。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | 不支持提供的文档类型。 |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | 提供的密码不正确。 |

### 评论

了解有关加载文档的更多信息： [加载文档](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### 例子

加载和保存任何支持格式的内容。

```csharp
// 从文件中加载内容。
using (Watermarker watermarker = new Watermarker("D:\\input.pdf"))
{
    // 使用 Watermarker 类的方法添加、搜索或删除水印。

    // 保存文档。
    watermarker.Save("D:\\output.pdf");
}
```

### 也可以看看

* class [Watermarker](../../watermarker)
* 命名空间 [GroupDocs.Watermark](../../watermarker)
* 部件 [GroupDocs.Watermark](../../../)

---

## Watermarker(string, LoadOptions) {#constructor_5}

初始化[`Watermarker`](../../watermarker)具有指定 文档路径和加载选项的类。

```csharp
public Watermarker(string filePath, LoadOptions options)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 从中加载文档的文件路径。 |
| options | LoadOptions | 加载文档时使用的其他选项。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | 不支持提供的文档类型。 |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | 提供的密码不正确。 |

### 评论

了解有关加载文档的更多信息： [加载文档](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### 例子

使用密码加载加密的 PDF 文档。

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
loadOptions.Password = "123";
using (Watermarker watermarker = new Watermarker(@"C:\Documents\test.pdf", loadOptions))
{
    // ...
}
```

### 也可以看看

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [Watermarker](../../watermarker)
* 命名空间 [GroupDocs.Watermark](../../watermarker)
* 部件 [GroupDocs.Watermark](../../../)

---

## Watermarker(string, WatermarkerSettings) {#constructor_7}

初始化[`Watermarker`](../../watermarker)具有指定 文档路径和设置的类。

```csharp
public Watermarker(string filePath, WatermarkerSettings settings)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 从中加载文档的文件路径。 |
| settings | WatermarkerSettings | 处理加载的文档时要使用的其他设置。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | 不支持提供的文档类型。 |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | 提供的密码不正确。 |

### 评论

了解有关加载文档的更多信息： [加载文档](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### 例子

全局设置可搜索对象（之后将加载的所有文档）。

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

        // 处理找到的水印的代码在这里。
    }
}
```

### 也可以看看

* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* 命名空间 [GroupDocs.Watermark](../../watermarker)
* 部件 [GroupDocs.Watermark](../../../)

---

## Watermarker(string, LoadOptions, WatermarkerSettings) {#constructor_6}

初始化[`Watermarker`](../../watermarker)具有指定 文档路径、加载选项和设置的类。

```csharp
public Watermarker(string filePath, LoadOptions options, WatermarkerSettings settings)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 从中加载文档的文件路径。 |
| options | LoadOptions | 加载文档时使用的其他选项。 |
| settings | WatermarkerSettings | 处理加载的文档时要使用的其他设置。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | 不支持提供的文档类型。 |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | 提供的密码不正确。 |

### 评论

了解有关加载文档的更多信息： [加载文档](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### 例子

在电子邮件正文/主题中查找特定的文本片段。

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
    // 注意，只有将 TextSearchCriteria 实例传递给 Search 方法时才会执行搜索
    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    // 删除找到的文本片段
    watermarks.Clear();
    // 保存更改
    watermarker.Save();
}
```

### 也可以看看

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* 命名空间 [GroupDocs.Watermark](../../watermarker)
* 部件 [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream) {#constructor}

初始化[`Watermarker`](../../watermarker)具有指定流的类。

```csharp
public Watermarker(Stream document)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | Stream | 要从中加载文档的流。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | 不支持提供的文档类型。 |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | 提供的密码不正确。 |

### 评论

了解有关加载文档的更多信息 [加载文档](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### 例子

加载并保存任何支持格式的文档。

```csharp
// 从流中加载内容。
using (FileStream inputStream = File.Open("D:\\input.pdf", FileMode.Open))
using (FileStream outputStream = File.Open("D:\\output.pdf", FileMode.Create))
using (Watermarker watermarker = new Watermarker(inputStream))
{
    // 使用 Watermarker 类的方法添加、搜索或删除水印。

    // 保存更改。
    watermarker.Save(outputStream);
}
```

### 也可以看看

* class [Watermarker](../../watermarker)
* 命名空间 [GroupDocs.Watermark](../../watermarker)
* 部件 [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, LoadOptions) {#constructor_1}

初始化[`Watermarker`](../../watermarker)具有指定 stream 和加载选项的类。

```csharp
public Watermarker(Stream document, LoadOptions options)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | Stream | 要从中加载文档的流。 |
| options | LoadOptions | 加载文档时使用的其他选项。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | 不支持提供的文档类型。 |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | 提供的密码不正确。 |

### 评论

了解有关加载文档的更多信息 [加载文档](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### 例子

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

### 也可以看看

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [Watermarker](../../watermarker)
* 命名空间 [GroupDocs.Watermark](../../watermarker)
* 部件 [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, WatermarkerSettings) {#constructor_3}

初始化[`Watermarker`](../../watermarker)具有指定 stream 和 settings. 的类

```csharp
public Watermarker(Stream document, WatermarkerSettings settings)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | Stream | 要从中加载文档的流。 |
| settings | WatermarkerSettings | 处理加载的文档时要使用的其他设置。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | 不支持提供的文档类型。 |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | 提供的密码不正确。 |

### 评论

了解有关加载文档的更多信息 [加载文档](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### 例子

全局设置可搜索对象（之后将加载的所有文档）。

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

        // 处理找到的水印的代码在这里。
    }
}
```

### 也可以看看

* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* 命名空间 [GroupDocs.Watermark](../../watermarker)
* 部件 [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, LoadOptions, WatermarkerSettings) {#constructor_2}

初始化[`Watermarker`](../../watermarker)具有指定流的类， 加载选项和设置。

```csharp
public Watermarker(Stream document, LoadOptions options, WatermarkerSettings settings)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | Stream | 要从中加载文档的流。 |
| options | LoadOptions | 加载文档时使用的其他选项。 |
| settings | WatermarkerSettings | 处理加载的文档时要使用的其他设置。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | 不支持提供的文档类型。 |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | 提供的密码不正确。 |

### 评论

了解有关加载文档的更多信息 [加载文档](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### 例子

在电子邮件正文/主题中查找特定的文本片段。

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
    // 注意，只有将 TextSearchCriteria 实例传递给 Search 方法时才会执行搜索
    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    // 删除找到的文本片段
    watermarks.Clear();
    // 保存更改
    watermarker.Save();
}
```

### 也可以看看

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* 命名空间 [GroupDocs.Watermark](../../watermarker)
* 部件 [GroupDocs.Watermark](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
