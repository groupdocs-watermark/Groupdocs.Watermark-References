---
title: "DiagramPageWatermarkOptions"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "表示在 Visio 文档的特定页面添加形状水印时的水印添加选项。"
type: docs
weight: 11
url: /zh/java/com.groupdocs.watermark.options/diagrampagewatermarkoptions/
---
**Inheritance:**
java.lang.Object，[com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions)，[com.groupdocs.watermark.options.DiagramWatermarkOptions](../../com.groupdocs.watermark.options/diagramwatermarkoptions)
```
public final class DiagramPageWatermarkOptions extends DiagramWatermarkOptions
```

表示在 Visio 文档的特定页面添加形状水印时的水印添加选项。

**Learn more:**

* [Add watermarks to diagram documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+diagram+documents)

以下示例演示如何向 Visio 文档的第一页添加受保护的水印。
>
> ````
> ```
>
>    DiagramLoadOptions loadOptions = new DiagramLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.vsdx", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("watermark test", new Font("Arial", 42));
>
>    DiagramPageWatermarkOptions options = new DiagramPageWatermarkOptions();
>    options.setLocked(true);
>    options.setPageIndex(0);
>
>    watermarker.add(watermark, options);
>    watermarker.save("D:\\watermarked_test.vsdx");
>    watermarker.close();
>  
> ```
> ````


## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [DiagramPageWatermarkOptions()](#DiagramPageWatermarkOptions--) | 初始化一个新的 `[DiagramPageWatermarkOptions](../../com.groupdocs.watermark.options/diagrampagewatermarkoptions)` 类的实例。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getPageIndex()](#getPageIndex--) | 获取要添加水印的页面索引。 |
|
|  | [setPageIndex(int value)](#setPageIndex-int-) | 设置要添加水印的页面索引。 |
|
### DiagramPageWatermarkOptions() {#DiagramPageWatermarkOptions--}
```
public DiagramPageWatermarkOptions()
```


初始化一个新的 `[DiagramPageWatermarkOptions](../../com.groupdocs.watermark.options/diagrampagewatermarkoptions)` 类的实例。


### getPageIndex() {#getPageIndex--}
```
public final int getPageIndex()
```


获取要添加水印的页面索引。


**Returns:**
int - 要添加水印的页面索引。

### setPageIndex(int value) {#setPageIndex-int-}
```
public final void setPageIndex(int value)
```


设置要添加水印的页面索引。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | int | 要添加水印的页面索引。 |
|

