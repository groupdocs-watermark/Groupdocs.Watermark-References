---
title: "WordProcessingWatermarkPagesOptions"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "表示在向 Word 文档页面添加水印时的选项。"
type: docs
weight: 76
url: /zh/java/com.groupdocs.watermark.options/wordprocessingwatermarkpagesoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkBaseOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkbaseoptions)
```
public final class WordProcessingWatermarkPagesOptions extends WordProcessingWatermarkBaseOptions
```

表示在向 Word 文档页面添加水印时的选项。

**Learn more:**

* [Add watermarks to word processing documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+word+processing+documents)

以下示例演示如何向 Word 文档的特定页面添加水印。
>
> ````
> ```
>
>    WordProcessingLoadOptions loadOptions = new WordProcessingLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.doc", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 14));
>
>    WordProcessingWatermarkPagesOptions options = new WordProcessingWatermarkPagesOptions();
>    options.setPageNumbers(new int[] { 1 });
>    
>    watermarker.save("D:\\watermarked_test.doc");
>    watermarker.close();
>  
> ```
> ````


## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [WordProcessingWatermarkPagesOptions()](#WordProcessingWatermarkPagesOptions--) | 初始化一个新的 `[WordProcessingWatermarkPagesOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkpagesoptions)` 类的实例。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getPageNumbers()](#getPageNumbers--) | 获取要添加水印的页面编号。 |
|
|  | [setPageNumbers(int[] value)](#setPageNumbers-int---) | 设置要添加水印的页面编号。 |
|
### WordProcessingWatermarkPagesOptions() {#WordProcessingWatermarkPagesOptions--}
```
public WordProcessingWatermarkPagesOptions()
```


初始化一个新的 `[WordProcessingWatermarkPagesOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkpagesoptions)` 类的实例。


### getPageNumbers() {#getPageNumbers--}
```
public final int[] getPageNumbers()
```


获取要添加水印的页面编号。


**Returns:**
int[] - 要添加水印的页面编号。

<br />

*** ** * ** ***

所有数字必须大于或等于 1。此属性仅在向文档添加水印时使用。如果此值为  null  或为空，则水印会添加到所有页面。

<br />


### setPageNumbers(int[] value) {#setPageNumbers-int---}
```
public final void setPageNumbers(int[] value)
```


设置要添加水印的页面编号。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | int[] | 要添加水印的页面编号。 |

<br />

*** ** * ** ***

所有数字必须大于或等于 1。此属性仅在向文档添加水印时使用。如果此值为  null  或为空，则水印会添加到所有页面。

<br />

|

