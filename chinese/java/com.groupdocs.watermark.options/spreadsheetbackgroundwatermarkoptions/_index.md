---
title: "SpreadsheetBackgroundWatermarkOptions"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "表示在将水印作为背景添加到电子表格工作表时的选项。"
type: docs
weight: 49
url: /zh/java/com.groupdocs.watermark.options/spreadsheetbackgroundwatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.SpreadsheetWatermarkOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkoptions)
```
public final class SpreadsheetBackgroundWatermarkOptions extends SpreadsheetWatermarkOptions
```

表示在将水印作为背景添加到电子表格工作表时的选项。

**Learn more:**

* [Add watermarks to spreadsheet documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+spreadsheet+documents)

下面的示例演示了如何将文字水印添加到 Excel 文档工作表作为背景。
>
> ````
> ```
>
>    SpreadsheetLoadOptions loadOptions = new SpreadsheetLoadOptions();
>    Watermarker watermarker = new Watermarker("C:\\Documents\\test.xlsx", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("Test watermark", new Font("Arial", 36));
>
>    SpreadsheetBackgroundWatermarkOptions options = new SpreadsheetBackgroundWatermarkOptions();
>    options.setWorksheetIndex(-1); // default
>    options.setBackgroundWidth(800);
>    options.setBackgroundHeight(600);
>    
>    watermarker.save("C:\\Documents\\watermarked_test.xlsx");
>    watermarker.close();
>  
> ```
> ````


## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [SpreadsheetBackgroundWatermarkOptions()](#SpreadsheetBackgroundWatermarkOptions--) | 初始化一个 `[SpreadsheetBackgroundWatermarkOptions](../../com.groupdocs.watermark.options/spreadsheetbackgroundwatermarkoptions)` 类的新实例。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getWorksheetIndex()](#getWorksheetIndex--) | 获取要添加水印的工作表的索引。 |
|
|  | [setWorksheetIndex(int value)](#setWorksheetIndex-int-) | 设置要添加水印的工作表索引。 |
|
|  | [getBackgroundWidth()](#getBackgroundWidth--) | 获取背景图像的期望宽度（像素）。 |
|
|  | [setBackgroundWidth(int value)](#setBackgroundWidth-int-) | 设置背景图像的期望宽度（像素）。 |
|
|  | [getBackgroundHeight()](#getBackgroundHeight--) | 获取或设置背景图像的期望高度（像素）。 |
|
|  | [setBackgroundHeight(int value)](#setBackgroundHeight-int-) | 获取或设置背景图像的期望高度（像素）。 |
|
### SpreadsheetBackgroundWatermarkOptions() {#SpreadsheetBackgroundWatermarkOptions--}
```
public SpreadsheetBackgroundWatermarkOptions()
```


初始化一个 `[SpreadsheetBackgroundWatermarkOptions](../../com.groupdocs.watermark.options/spreadsheetbackgroundwatermarkoptions)` 类的新实例。


### getWorksheetIndex() {#getWorksheetIndex--}
```
public final int getWorksheetIndex()
```


获取要添加水印的工作表的索引。

-1 means every worksheet.


**Returns:**
int - 要添加水印的工作表索引。

### setWorksheetIndex(int value) {#setWorksheetIndex-int-}
```
public final void setWorksheetIndex(int value)
```


设置要添加水印的工作表索引。

-1 means every worksheet.


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | int | 要添加水印的工作表索引。 |
|

### getBackgroundWidth() {#getBackgroundWidth--}
```
public final int getBackgroundWidth()
```


获取背景图像的期望宽度（像素）。


**Returns:**
int - 背景图像的期望宽度（像素）。

### setBackgroundWidth(int value) {#setBackgroundWidth-int-}
```
public final void setBackgroundWidth(int value)
```


设置背景图像的期望宽度（像素）。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | int | 背景图像的期望宽度（像素）。 |
|

### getBackgroundHeight() {#getBackgroundHeight--}
```
public final int getBackgroundHeight()
```


获取或设置背景图像的期望高度（像素）。


**Returns:**
int - 背景图像的期望高度（像素）。

### setBackgroundHeight(int value) {#setBackgroundHeight-int-}
```
public final void setBackgroundHeight(int value)
```


获取或设置背景图像的期望高度（像素）。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | int | 背景图像的期望高度（像素）。 |
|

