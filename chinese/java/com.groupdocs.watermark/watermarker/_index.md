---
title: "Watermarker"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "表示文档中用于水印管理的类。"
type: docs
weight: 14
url: /zh/java/com.groupdocs.watermark/watermarker/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class Watermarker implements Closeable
```

表示文档中用于水印管理的类。

以下示例演示了如何加载和保存任何受支持格式的内容。
>
> ````
> ```
>
>    // Load a content from a file.
>    Watermarker watermarker = new Watermarker("D:\\input.pdf");
>
>    // Use methods of Watermarker class to add, search or remove watermarks.
>
>    // Save changes.
>    watermarker.save("D:\\output.pdf");
>
>    // Free resources.
>    watermarker.close();
>  
> ```
> ````


## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [Watermarker(String filePath)](#Watermarker-java.lang.String-) | 使用指定的文档路径初始化 `[Watermarker](../../com.groupdocs.watermark/watermarker)` 类的新实例。 |
|
|  | [Watermarker(String filePath, LoadOptions options)](#Watermarker-java.lang.String-com.groupdocs.watermark.options.LoadOptions-) | 使用指定的文档路径和加载选项初始化 `[Watermarker](../../com.groupdocs.watermark/watermarker)` 类的新实例。 |
|
|  | [Watermarker(String filePath, WatermarkerSettings settings)](#Watermarker-java.lang.String-com.groupdocs.watermark.WatermarkerSettings-) | 使用指定的文档路径和设置初始化 `[Watermarker](../../com.groupdocs.watermark/watermarker)` 类的新实例。 |
|
|  | [Watermarker(String filePath, LoadOptions options, WatermarkerSettings settings)](#Watermarker-java.lang.String-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-) | 使用指定的文档路径、加载选项和设置初始化 `[Watermarker](../../com.groupdocs.watermark/watermarker)` 类的新实例。 |
|
|  | [Watermarker(InputStream document)](#Watermarker-java.io.InputStream-) | 使用指定的流初始化 `[Watermarker](../../com.groupdocs.watermark/watermarker)` 类的新实例。 |
|
|  | [Watermarker(InputStream document, LoadOptions options)](#Watermarker-java.io.InputStream-com.groupdocs.watermark.options.LoadOptions-) | 使用指定的流和加载选项初始化 `[Watermarker](../../com.groupdocs.watermark/watermarker)` 类的新实例。 |
|
|  | [Watermarker(InputStream document, WatermarkerSettings settings)](#Watermarker-java.io.InputStream-com.groupdocs.watermark.WatermarkerSettings-) | 使用指定的流和设置初始化 `[Watermarker](../../com.groupdocs.watermark/watermarker)` 类的新实例。 |
|
|  | [Watermarker(InputStream document, LoadOptions options, WatermarkerSettings settings)](#Watermarker-java.io.InputStream-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-) | 使用指定的流、加载选项和设置初始化该类的新实例。 |
|
| [Watermarker(System.IO.Stream document, LoadOptions options, WatermarkerSettings settings)](#Watermarker-com.aspose.ms.System.IO.Stream-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getSearchableObjects()](#getSearchableObjects--) | 获取将在水印搜索中包含的内容对象。 |
|
|  | [setSearchableObjects(SearchableObjects value)](#setSearchableObjects-com.groupdocs.watermark.search.SearchableObjects-) | 设置将在水印搜索中包含的内容对象。 |
|
| [dispose()](#dispose--) |  |
|  | [close()](#close--) | 释放当前实例。 |
|
|  | [getDocumentInfo()](#getDocumentInfo--) | 获取已加载文档格式的信息。 |
|
|  | [add(Watermark watermark)](#add-com.groupdocs.watermark.Watermark-) | 向已加载的文档添加水印。 |
|
|  | [add(Watermark watermark, WatermarkOptions options)](#add-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.WatermarkOptions-) | 使用水印选项向已加载的文档添加水印。 |
|
|  | [remove(PossibleWatermark possibleWatermark)](#remove-com.groupdocs.watermark.search.PossibleWatermark-) | 从文档中移除水印。 |
|
|  | [remove(PossibleWatermarkCollection possibleWatermarks)](#remove-com.groupdocs.watermark.search.PossibleWatermarkCollection-) | 从文档中移除集合中的所有水印。 |
|
|  | [save(String filePath)](#save-java.lang.String-) | 将文档保存到指定的文件位置。 |
|
|  | [save(OutputStream document)](#save-java.io.OutputStream-) | 将文档保存到指定的流中。 |
|
|  | [save(String filePath, SaveOptions options)](#save-java.lang.String-com.groupdocs.watermark.options.SaveOptions-) | 使用保存选项将文档保存到指定的文件位置。 |
|
|  | [save(OutputStream document, SaveOptions options)](#save-java.io.OutputStream-com.groupdocs.watermark.options.SaveOptions-) | 使用保存选项将文档保存到指定的流中。 |
|
|  | [generatePreview(PreviewOptions previewOptions)](#generatePreview-com.groupdocs.watermark.options.PreviewOptions-) | 为文档生成预览图像。 |
|
|  | [search()](#search--) | 搜索文档中所有可能的水印。 |
|
|  | [search(SearchCriteria searchCriteria)](#search-com.groupdocs.watermark.search.SearchCriteria-) | 根据指定的搜索条件搜索可能的水印。 |
|
|  | [getImages(ImageSearchCriteria searchCriteria)](#getImages-com.groupdocs.watermark.search.ImageSearchCriteria-) | 根据指定的搜索条件查找图像。 |
|
|  | [getImages()](#getImages--) | 查找文档中的所有图像。 |
|
|  | [<T>getContent(Class<T> contentType)](#-T-getContent-java.lang.Class-T--) | 返回已加载文档的 `[Content](../../com.groupdocs.watermark.contents/content)` 对象。 |
|
### Watermarker(String filePath) {#Watermarker-java.lang.String-}
```
public Watermarker(String filePath)
```


使用指定的文档路径初始化 `[Watermarker](../../com.groupdocs.watermark/watermarker)` 类的新实例。

了解有关加载文档的更多信息：
[Loading documents](../https://docs.groupdocs.com/display/watermarkjava/Loading+documents).

以下示例演示了如何加载和保存任何受支持格式的内容。
>
> ````
> ```
>
>    // Load a content from a file.
>    Watermarker watermarker = new Watermarker("D:\\input.pdf");
>
>    // Use methods of Watermarker class to add, search or remove watermarks.
>
>    // Save changes.
>    watermarker.save("D:\\output.pdf");
>
>    // Free resources.
>    watermarker.close();
>  
> ```
> ````



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | filePath | java.lang.String | 用于加载文档的文件路径。 |
|

### Watermarker(String filePath, LoadOptions options) {#Watermarker-java.lang.String-com.groupdocs.watermark.options.LoadOptions-}
```
public Watermarker(String filePath, LoadOptions options)
```


使用指定的文档路径和加载选项初始化 `[Watermarker](../../com.groupdocs.watermark/watermarker)` 类的新实例。

了解有关加载文档的更多信息：
[Loading documents](../https://docs.groupdocs.com/display/watermarkjava/Loading+documents).

以下示例演示如何使用密码加载加密的 PDF 文档。
>
> ````
> ```
>
>    PdfLoadOptions loadOptions = new PdfLoadOptions();
>    loadOptions.setPassword("123");
>    Watermarker watermarker = new Watermarker("C:\\Documents\\test.pdf", loadOptions);
>    // ...
>    watermarker.close();
>  
> ```
> ````



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | filePath | java.lang.String | 用于加载文档的文件路径。 |
|
|  | options | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) | 加载文档时使用的其他选项。 |
|

### Watermarker(String filePath, WatermarkerSettings settings) {#Watermarker-java.lang.String-com.groupdocs.watermark.WatermarkerSettings-}
```
public Watermarker(String filePath, WatermarkerSettings settings)
```


使用指定的文档路径和设置初始化 `[Watermarker](../../com.groupdocs.watermark/watermarker)` 类的新实例。

了解有关加载文档的更多信息：
[Loading documents](../https://docs.groupdocs.com/display/watermarkjava/Loading+documents).

以下示例演示如何全局设置可搜索对象（针对所有将在之后加载的文档
将在之后加载）。
>
> ````
> ```
>
>    WatermarkerSettings settings = new WatermarkerSettings();
>    settings.setSearchableObjects(new SearchableObjects());
>    settings.getSearchableObjects().setWordProcessingSearchableObjects(WordProcessingSearchableObjects.Hyperlinks
>                                                                     | WordProcessingSearchableObjects.Text);
>    settings.getSearchableObjects().setSpreadsheetSearchableObjects(SpreadsheetSearchableObjects.HeadersFooters);
>    settings.getSearchableObjects().setPresentationSearchableObjects(PresentationSearchableObjects.SlidesBackgrounds
>                                                                   | PresentationSearchableObjects.Shapes);
>    settings.getSearchableObjects().setDiagramSearchableObjects(DiagramSearchableObjects.None);
>    settings.getSearchableObjects().setPdfSearchableObjects(PdfSearchableObjects.All);
>
>    for (final File fileEntry : new File("D:\\files").listFiles())
>    {
>       if (fileEntry.isFile()) {
>           Watermarker watermarker = new Watermarker(fileEntry.getPath(), settings);
>           PossibleWatermarkCollection watermarks = watermarker.search();
>           // The code for working with found watermarks goes here.
>           watermarker.close();
>       }
>    }
>  
> ```
> ````



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | filePath | java.lang.String | 用于加载文档的文件路径。 |
|
|  | settings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) | 处理已加载文档时使用的其他设置。 |
|

### Watermarker(String filePath, LoadOptions options, WatermarkerSettings settings) {#Watermarker-java.lang.String-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-}
```
public Watermarker(String filePath, LoadOptions options, WatermarkerSettings settings)
```


使用指定的文档路径、加载选项和设置初始化 `[Watermarker](../../com.groupdocs.watermark/watermarker)` 类的新实例。

了解有关加载文档的更多信息：
[Loading documents](../https://docs.groupdocs.com/display/watermarknet/Loading+documents).

以下示例演示如何在电子邮件正文/主题中查找特定文本片段。
>
> ````
> ```
>
>    WatermarkerSettings settings = new WatermarkerSettings();
>    settings.setSearchableObjects(new SearchableObjects());
>    settings.getSearchableObjects().setEmailSearchableObjects(EmailSearchableObjects.Subject
>                                                            | EmailSearchableObjects.HtmlBody
>                                                            | EmailSearchableObjects.PlainTextBody);
>    EmailLoadOptions loadOptions = new EmailLoadOptions(); 
>    Watermarker watermarker = new Watermarker("D:\\test.msg", loadOptions, settings);
>    SearchCriteria criteria = new TextSearchCriteria("test", false);
>    // Note, search is performed only if you pass TextSearchCriteria instance to search() method
>    PossibleWatermarkCollection watermarks = watermarker.search(criteria);
>    // Remove found text fragments
>    watermarks.clear();
>    // Save changes
>    watermarker.save("D:\\modified_test.msg");
>    watermarker.close();
>  
> ```
> ````



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | filePath | java.lang.String | 用于加载文档的文件路径。 |
|
|  | options | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) | 加载文档时使用的其他选项。 |
|
|  | settings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) | 处理已加载文档时使用的其他设置。 |
|

### Watermarker(InputStream document) {#Watermarker-java.io.InputStream-}
```
public Watermarker(InputStream document)
```


使用指定的流初始化 `[Watermarker](../../com.groupdocs.watermark/watermarker)` 类的新实例。

了解有关加载文档的更多信息：
[Loading documents](../https://docs.groupdocs.com/display/watermarknet/Loading+documents).

以下示例演示如何加载和保存任意受支持格式的文档。
>
> ````
> ```
>
>    // Load a content from a stream.
>    FileInputStream inputStream = new FileInputStream("D:\\input.pdf");
>    FileOutputStream outputStream = new FileOutputStream("D:\\output.pdf");
>    Watermarker watermarker = new Watermarker(inputStream);
>    // Use methods of Watermarker class to add, search or remove watermarks.
>
>    // Save changes.
>    watermarker.save(outputStream);
>    watermarker.close();
>    outputStream.close();
>    inputStream.close();
>  
> ```
> ````



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 文档 | java.io.InputStream | 用于加载文档的流。 |
|

### Watermarker(InputStream document, LoadOptions options) {#Watermarker-java.io.InputStream-com.groupdocs.watermark.options.LoadOptions-}
```
public Watermarker(InputStream document, LoadOptions options)
```


使用指定的流和加载选项初始化 `[Watermarker](../../com.groupdocs.watermark/watermarker)` 类的新实例。

了解有关加载文档的更多信息：
[Loading documents](../https://docs.groupdocs.com/display/watermarknet/Loading+documents).

以下示例演示如何使用密码加载加密的 PDF 文档
>
> ````
> ```
>
>    PdfLoadOptions loadOptions = new PdfLoadOptions();
>    loadOptions.setPassword("123");
>    FileInputStream inputStream = new FileInputStream("D:\\input.pdf");
>    Watermarker watermarker = new Watermarker(inputStream, loadOptions);
>    // ...
>
>    watermarker.close();
>    inputStream.close();
>  
> ```
> ````



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 文档 | java.io.InputStream | 用于加载文档的流。 |
|
|  | options | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) | 加载文档时使用的其他选项。 |
|

### Watermarker(InputStream document, WatermarkerSettings settings) {#Watermarker-java.io.InputStream-com.groupdocs.watermark.WatermarkerSettings-}
```
public Watermarker(InputStream document, WatermarkerSettings settings)
```


使用指定的流和设置初始化 `[Watermarker](../../com.groupdocs.watermark/watermarker)` 类的新实例。

了解有关加载文档的更多信息：
[Loading documents](../https://docs.groupdocs.com/display/watermarknet/Loading+documents).

以下示例演示如何全局设置可搜索对象（针对所有将在之后加载的文档
将在之后加载）。
>
> ````
> ```
>
>    WatermarkerSettings settings = new WatermarkerSettings();
>    settings.setSearchableObjects(new SearchableObjects());
>    settings.getSearchableObjects().setWordProcessingSearchableObjects(WordProcessingSearchableObjects.Hyperlinks
>                                                                     | WordProcessingSearchableObjects.Text);
>    settings.getSearchableObjects().setSpreadsheetSearchableObjects(SpreadsheetSearchableObjects.HeadersFooters);
>    settings.getSearchableObjects().setPresentationSearchableObjects(PresentationSearchableObjects.SlidesBackgrounds
>                                                                   | PresentationSearchableObjects.Shapes);
>    settings.getSearchableObjects().setDiagramSearchableObjects(DiagramSearchableObjects.None);
>    settings.getSearchableObjects().setPdfSearchableObjects(PdfSearchableObjects.All);
>
>    for (final File fileEntry : new File("D:\\files").listFiles())
>    {
>       if (fileEntry.isFile()) {
>           FileInputStream inputStream = new FileInputStream(fileEntry.getPath());
>           Watermarker watermarker = new Watermarker(inputStream, settings);
>           PossibleWatermarkCollection watermarks = watermarker.Search();
>           // The code for working with found watermarks goes here.
>           watermarker.close();
>           inputStream.close();
>       }
>    }
>  
> ```
> ````



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 文档 | java.io.InputStream | 用于加载文档的流。 |
|
|  | settings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) | 处理已加载文档时使用的其他设置。 |
|

### Watermarker(InputStream document, LoadOptions options, WatermarkerSettings settings) {#Watermarker-java.io.InputStream-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-}
```
public Watermarker(InputStream document, LoadOptions options, WatermarkerSettings settings)
```


使用指定的流、加载选项和设置初始化该类的新实例。

了解有关加载文档的更多信息：
[Loading documents](../https://docs.groupdocs.com/display/watermarknet/Loading+documents).

以下示例演示如何全局设置可搜索对象（针对所有将在之后加载的文档
将在之后加载）。
>
> ````
> ```
>
>    WatermarkerSettings settings = new WatermarkerSettings();
>    settings.setSearchableObjects(new SearchableObjects());
>    settings.getSearchableObjects().setEmailSearchableObjects(EmailSearchableObjects.Subject
>                                                            | EmailSearchableObjects.HtmlBody
>                                                            | EmailSearchableObjects.PlainTextBody);
>    FileInputStream inputStream = new FileInputStream("D:\\test.msg");
>    FileOutputStream outputStream = new FileOutputStream("D:\\modified_test.msg");
>    EmailLoadOptions loadOptions = new EmailLoadOptions(); 
>    Watermarker watermarker = new Watermarker(inputStream, loadOptions, settings);
>    SearchCriteria criteria = new TextSearchCriteria("test", false);
>    // Note, search is performed only if you pass TextSearchCriteria instance to search() method
>    PossibleWatermarkCollection watermarks = watermarker.search(criteria);
>    // Remove found text fragments
>    watermarks.clear();
>    // Save changes
>    watermarker.save(outputStream);
>    watermarker.close();
>    outputStream.close();
>    inputStream.close();
>  
> ```
> ````



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 文档 | java.io.InputStream | 用于加载文档的流。 |
|
|  | options | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) | 加载文档时使用的其他选项。 |
|
|  | settings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) | 处理已加载文档时使用的其他设置。 |
|

### Watermarker(System.IO.Stream document, LoadOptions options, WatermarkerSettings settings) {#Watermarker-com.aspose.ms.System.IO.Stream-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-}
```
public Watermarker(System.IO.Stream document, LoadOptions options, WatermarkerSettings settings)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文档 | com.aspose.ms.System.IO.Stream |  |
| options | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) |  |
| settings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) |  |

### getSearchableObjects() {#getSearchableObjects--}
```
public final SearchableObjects getSearchableObjects()
```


获取将在水印搜索中包含的内容对象。

此方法还指定了在图像搜索中使用的内容对象。
欲了解更多信息，请参见 `#search(SearchCriteria).search(SearchCriteria)`
以及 `#getImages().getImages()` 方法。

了解更多关于搜索水印的信息：
[Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks).

以下示例演示如何从 PDF 文档中移除所有 XObjects 和 Artifacts。
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("D:\\test.pdf");
>    watermarker.getSearchableObjects().setPdfSearchableObjects(PdfSearchableObjects.XObjects
>                                                             | PdfSearchableObjects.Artifacts);
>    PossibleWatermarkCollection watermarks = watermarker.search();
>    // Remove all found objects.
>    watermarks.clear();
>    // Save changes.
>    watermarker.save("D:\\modified_test.pdf");
>    watermarker.close();
>  
> ```
> ````



**Returns:**
[SearchableObjects](../../com.groupdocs.watermark.search/searchableobjects) - The objects that are to be included in a watermark search.

### setSearchableObjects(SearchableObjects value) {#setSearchableObjects-com.groupdocs.watermark.search.SearchableObjects-}
```
public final void setSearchableObjects(SearchableObjects value)
```


设置将在水印搜索中包含的内容对象。

此方法还指定了在图像搜索中使用的内容对象。
欲了解更多信息，请参见 `#search(SearchCriteria).search(SearchCriteria)`
以及 `#getImages().getImages()` 方法。
了解更多关于搜索水印的信息：
[Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks).

以下示例演示如何从 PDF 文档中移除所有 XObjects 和 Artifacts。
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("D:\\test.pdf");
>    watermarker.getSearchableObjects().setPdfSearchableObjects(PdfSearchableObjects.XObjects
>                                                             | PdfSearchableObjects.Artifacts);
>    PossibleWatermarkCollection watermarks = watermarker.search();
>    // Remove all found objects.
>    watermarks.clear();
>    // Save changes.
>    watermarker.save("D:\\modified_test.pdf");
>    watermarker.close();
>  
> ```
> ````



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | [SearchableObjects](../../com.groupdocs.watermark.search/searchableobjects) | 将在水印搜索中包含的对象。 |
|

### dispose() {#dispose--}
```
public final void dispose()
```




### close() {#close--}
```
public final void close()
```


释放当前实例。


### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


获取已加载文档格式的信息。

了解更多关于获取文档信息的内容
[Get document info](../https://docs.groupdocs.com/display/watermarkjava/Get+document+info).

以下示例演示如何获取任何受支持类型文档的信息。
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("D:\\test.ppt");
>    IDocumentInfo info = watermarker.getDocumentInfo();
>    System.out.println("File type: " + info.getFileType());
>    System.out.println("Number of pages: " + info.getPageCount());
>    System.out.println("Document size: " + info.getSize() + " bytes");
>    watermarker.close();
>  
> ```
> ````



**Returns:**
[IDocumentInfo](../../com.groupdocs.watermark.common/idocumentinfo) - The `[IDocumentInfo](../../com.groupdocs.watermark.common/idocumentinfo)` instance that contains detected information.

### add(Watermark watermark) {#add-com.groupdocs.watermark.Watermark-}
```
public final void add(Watermark watermark)
```


向已加载的文档添加水印。

了解更多关于添加水印的信息：
[Adding watermarks](../https://docs.groupdocs.com/display/watermarkjava/Adding+watermarks).

以下示例演示如何向任何受支持类型的文档添加图像和文本水印。
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("D:\\input.pdf");
>
>    TextWatermark textWatermark = new TextWatermark("DRAFT", new Font("Arial", 19));
>    textWatermark.setHorizontalAlignment(HorizontalAlignment.Center);
>    textWatermark.setVerticalAlignment(VerticalAlignment.Top);
>    textWatermark.setConsiderParentMargins(true);
>    textWatermark.setForegroundColor(Color.getRed());
>    textWatermark.setBackground(true);
>    textWatermark.setOpacity(0.5);
>    watermarker.add(textWatermark);
>  
>    ImageWatermark imageWatermark = new ImageWatermark("D:\\draft.png"));
>    imageWatermark.setHorizontalAlignment(HorizontalAlignment.Center);
>    imageWatermark.setVerticalAlignment(VerticalAlignment.Bottom);
>    imageWatermark.setConsiderParentMargins(true);
>    imageWatermark.setBackground(true);
>    imageWatermark.setOpacity(0.5);
>    watermarker.add(imageWatermark);
>    imageWatermark.close();
>
>    watermarker.save("D:\\output.pdf");
>    watermarker.close();
>  
> ```
> ````



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | watermark | [Watermark](../../com.groupdocs.watermark/watermark) | 要添加到文档的水印。 |
|

### add(Watermark watermark, WatermarkOptions options) {#add-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.WatermarkOptions-}
```
public final void add(Watermark watermark, WatermarkOptions options)
```


使用水印选项向已加载的文档添加水印。

了解更多关于添加水印的信息：
[Adding watermarks](../https://docs.groupdocs.com/display/watermarkjava/Adding+watermarks).

以下示例演示如何向 PDF 文档的特定页面添加图像水印。
>
> ````
> ```
>
>    PdfLoadOptions loadOptions = new PdfLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\input.pdf", loadOptions);
>
>    ImageWatermark imageWatermark = new ImageWatermark("D:\\draft.png"));
>    PdfXObjectWatermarkOptions options = new PdfXObjectWatermarkOptions();
>    options.setPageIndex(0);
>    watermarker.add(imageWatermark, options);
>    imageWatermark.close();
>
>    watermarker.save("D:\\output.pdf");
>    watermarker.close();
>  
> ```
> ````



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | watermark | [Watermark](../../com.groupdocs.watermark/watermark) | 要添加到文档的水印。 |
|
|  | options | [WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions) | 添加水印时可使用的其他选项。 |
|

### remove(PossibleWatermark possibleWatermark) {#remove-com.groupdocs.watermark.search.PossibleWatermark-}
```
public final void remove(PossibleWatermark possibleWatermark)
```


从文档中移除水印。

了解更多关于移除水印的信息：
[Removing found watermarks](../https://docs.groupdocs.com/display/watermarkjava/Removing+found+watermarks).

以下示例演示如何查找并移除包含特定内容的第一个可能的水印
文本或图像（来自任何受支持类型的文档）
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("D:\\input.doc");
>    ImageSearchCriteria imageSearchCriteria = new ImageDctHashSearchCriteria("D:\\logo.png");
>    TextSearchCriteria textSearchCriteria = new TextSearchCriteria(Pattern.compile("^Company\\sName$"));
>    PossibleWatermarkCollection watermarks = watermarker.search(textSearchCriteria.or(imageSearchCriteria));
>    if (watermarks.getCount() > 0)
>    {
>        watermarker.remove(watermarks.get_Item(0));
>    }
>
>    watermarker.save("D:\\output.doc");
>    watermarker.close();
>  
> ```
> ````



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | possibleWatermark | [PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark) | 要移除的水印。 |
|

### remove(PossibleWatermarkCollection possibleWatermarks) {#remove-com.groupdocs.watermark.search.PossibleWatermarkCollection-}
```
public final void remove(PossibleWatermarkCollection possibleWatermarks)
```


从文档中移除集合中的所有水印。

了解更多关于移除水印的信息：
[Removing found watermarks](../https://docs.groupdocs.com/display/watermarkjava/Removing+found+watermarks).

以下示例演示如何查找并移除包含特定内容的所有可能的水印
文本或图像（来自任何受支持类型的文档）
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("D:\\input.doc");
>    ImageSearchCriteria imageSearchCriteria = new ImageDctHashSearchCriteria("D:\\logo.png");
>    TextSearchCriteria textSearchCriteria = new TextSearchCriteria(Pattern.compile("^Company\\sName$"));
>    PossibleWatermarkCollection watermarks = watermarker.search(textSearchCriteria.or(imageSearchCriteria));
>    watermarker.remove(watermarks);
>    watermarker.save("D:\\output.doc");
>    watermarker.close();
>  
> ```
> ````



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | possibleWatermarks | [PossibleWatermarkCollection](../../com.groupdocs.watermark.search/possiblewatermarkcollection) | 要移除的水印集合。 |
|

### save(String filePath) {#save-java.lang.String-}
```
public final void save(String filePath)
```


将文档保存到指定的文件位置。

了解更多关于保存文档的内容
[Saving documents](../https://docs.groupdocs.com/display/watermarkjava/Saving+documents).

以下示例演示如何添加水印并将文档保存到另一个文件。
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("input.pdf");
>    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
>    watermarker.add(watermark);
>    watermarker.save("output.pdf");
>    watermarker.close();
>  
> ```
> ````



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | filePath | java.lang.String | 用于保存文档数据的文件路径。 |
|

### save(OutputStream document) {#save-java.io.OutputStream-}
```
public final void save(OutputStream document)
```


将文档保存到指定的流中。

了解更多关于保存文档的内容
[Saving documents](../https://docs.groupdocs.com/display/watermarkjava/Saving+documents).

下面的示例演示如何添加水印并将文档保存到内存流。
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("input.pdf");
>    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
>    watermarker.add(watermark);
>    ByteArrayOutputStream outputStream = new ByteArrayOutputStream();
>    watermarker.save(outputStream);
>    // ...
>    outputStream.close();
>    watermarker.close();
>  
> ```
> ````



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 文档 | java.io.OutputStream | 用于保存文档数据的流。 |
|

### save(String filePath, SaveOptions options) {#save-java.lang.String-com.groupdocs.watermark.options.SaveOptions-}
```
public final void save(String filePath, SaveOptions options)
```


使用保存选项将文档保存到指定的文件位置。

了解更多关于保存文档的内容
[Saving documents](../https://docs.groupdocs.com/display/watermarkjava/Saving+documents).

下面的示例演示如何添加水印并将文档保存到另一个文件
使用默认的 `[SaveOptions](../../com.groupdocs.watermark.options/saveoptions)`。
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("input.pdf");
>    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
>    watermarker.add(watermark);
>    watermarker.save("output.pdf", new SaveOptions());
>    watermarker.close();
>  
> ```
> ````



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | filePath | java.lang.String | 用于保存文档数据的文件路径。 |
|
|  | options | [SaveOptions](../../com.groupdocs.watermark.options/saveoptions) | 保存文档时使用的其他选项。 |
|

### save(OutputStream document, SaveOptions options) {#save-java.io.OutputStream-com.groupdocs.watermark.options.SaveOptions-}
```
public final void save(OutputStream document, SaveOptions options)
```


使用保存选项将文档保存到指定的流中。

了解更多关于保存文档的内容
[Saving documents](../https://docs.groupdocs.com/display/watermarkjava/Saving+documents).

下面的示例演示如何添加水印并将文档保存到内存流
使用默认的 `[SaveOptions](../../com.groupdocs.watermark.options/saveoptions)`。
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("input.pdf");
>    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
>    watermarker.add(watermark);
>    ByteArrayOutputStream outputStream = new ByteArrayOutputStream();
>    watermarker.save(outputStream, new SaveOptions());
>    // ...
>    outputStream.close();
>    watermarker.close();
>  
> ```
> ````



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 文档 | java.io.OutputStream | 用于保存文档数据的流。 |
|
|  | options | [SaveOptions](../../com.groupdocs.watermark.options/saveoptions) | 保存文档时使用的其他选项。 |
|

### generatePreview(PreviewOptions previewOptions) {#generatePreview-com.groupdocs.watermark.options.PreviewOptions-}
```
public final void generatePreview(PreviewOptions previewOptions)
```


为文档生成预览图像。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | previewOptions | [PreviewOptions](../../com.groupdocs.watermark.options/previewoptions) | 生成预览图像时使用的其他选项。 |
|

### search() {#search--}
```
public final PossibleWatermarkCollection search()
```


搜索文档中所有可能的水印。

搜索在使用 `#setSearchableObjects(SearchableObjects).setSearchableObjects(SearchableObjects)` 指定的对象中进行。

了解更多关于搜索水印的信息
[Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks).

下面的示例演示如何统计任意受支持类型文档中可能的水印。
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("input.doc");
>    PossibleWatermarkCollection watermarks = watermarker.search();
>    System.out.println(watermarks.getCount());
>    watermarker.close();
>  
> ```
> ````



**Returns:**
[PossibleWatermarkCollection](../../com.groupdocs.watermark.search/possiblewatermarkcollection)
### search(SearchCriteria searchCriteria) {#search-com.groupdocs.watermark.search.SearchCriteria-}
```
public final PossibleWatermarkCollection search(SearchCriteria searchCriteria)
```


根据指定的搜索条件搜索可能的水印。

搜索在使用 `#setSearchableObjects(SearchableObjects).setSearchableObjects(SearchableObjects)` 指定的对象中进行。

了解更多关于搜索水印的信息
[Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks).

下面的示例演示如何查找并移除所有包含特定文本的可能水印
或图像，来自任意受支持类型的文档。
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("input.doc");
>    ImageSearchCriteria imageSearchCriteria = new ImageDctHashSearchCriteria("logo.png");
>    TextSearchCriteria textSearchCriteria = new TextSearchCriteria(Pattern.compile("^Company\\sName$"));
>    PossibleWatermarkCollection watermarks = watermarker.search(textSearchCriteria.or(imageSearchCriteria));
>    watermarks.clear();
>    watermarker.save("output.doc");
>    watermarker.close();
>  
> ```
> ````



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | searchCriteria | [SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) | 要使用的搜索条件。 |
|

**Returns:**
[PossibleWatermarkCollection](../../com.groupdocs.watermark.search/possiblewatermarkcollection)
### getImages(ImageSearchCriteria searchCriteria) {#getImages-com.groupdocs.watermark.search.ImageSearchCriteria-}
```
public final WatermarkableImageCollection getImages(ImageSearchCriteria searchCriteria)
```


根据指定的搜索条件查找图像。

搜索在使用 `#setSearchableObjects(SearchableObjects).setSearchableObjects(SearchableObjects)` 指定的对象中进行。

了解更多关于搜索水印的信息
[Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks).

下面的示例演示如何移除所有与参考图像相似的图像
来自任意受支持类型的文档。
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("input.doc");
>    ImageThumbnailSearchCriteria criteria = new ImageThumbnailSearchCriteria("reference.png");
>    WatermarkableImageCollection images = watermarker.getImages(criteria);
>    images.clear();
>    watermarker.save("output.doc");
>    watermarker.close();
>  
> ```
> ````



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | searchCriteria | [ImageSearchCriteria](../../com.groupdocs.watermark.search/imagesearchcriteria) | 要使用的搜索条件。 |
|

**Returns:**
[WatermarkableImageCollection](../../com.groupdocs.watermark.contents/watermarkableimagecollection)
### getImages() {#getImages--}
```
public final WatermarkableImageCollection getImages()
```


查找文档中的所有图像。

搜索在使用 `#setSearchableObjects(SearchableObjects).setSearchableObjects(SearchableObjects)` 指定的对象中进行。

了解更多关于搜索水印的信息
[Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks).

下面的示例演示如何向任意受支持类型文档中的所有图像添加水印。
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("input.doc");
>    // Initialize text or image watermark.
>    TextWatermark watermark = new TextWatermark("DRAFT", new Font("Arial", 19));
>
>    // Find all images in the document.
>    WatermarkableImageCollection images = watermarker.getImages();
>
>    // Add watermark.
>    for (WatermarkableImage watermarkableImage : images)
>    {
>        watermarkableImage.addWatermark(watermark);
>    }
>
>    // Save changes.
>    watermarker.save("output.doc");
>    watermarker.close();
>  
> ```
> ````



**Returns:**
[WatermarkableImageCollection](../../com.groupdocs.watermark.contents/watermarkableimagecollection) - The collection of found images.

### <T>getContent(Class<T> contentType) {#-T-getContent-java.lang.Class-T--}
```
public final T <T>getContent(Class<T> contentType)
```


返回已加载文档的 `[Content](../../com.groupdocs.watermark.contents/content)` 对象。

下面的示例演示如何对添加了水印的 PDF 文档页面进行光栅化。
>
> ````
> ```
>
>    PdfLoadOptions loadOptions = new PdfLoadOptions();
>    Watermarker watermarker = new Watermarker("input.pdf", loadOptions);
>    ImageWatermark watermark = new ImageWatermark("watermark.png")
>    watermarker.add(watermark);
>    PdfContent content = watermarker.getContent(PdfContent.class);
>    content.rasterize(300, 300, PdfImageConversionFormat.Png);
>    watermarker.save("output.pdf");
>    watermarker.close();
>  
> ```
> ````



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | contentType | java.lang.Class<T> | 请求的 `[Content](../../com.groupdocs.watermark.contents/content)` 对象类型。 |
|

**Returns:**
T - 已加载文档的 `[Content](../../com.groupdocs.watermark.contents/content)` 对象。

