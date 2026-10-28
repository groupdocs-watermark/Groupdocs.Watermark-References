---
title: "SpreadsheetWatermarkShapeOptions"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "表示在向电子表格工作表添加形状水印时的选项。"
type: docs
weight: 60
url: /zh/java/com.groupdocs.watermark.options/spreadsheetwatermarkshapeoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.SpreadsheetWatermarkOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkoptions), [com.groupdocs.watermark.options.SpreadsheetWatermarkBaseOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkbaseoptions)
```
public final class SpreadsheetWatermarkShapeOptions extends SpreadsheetWatermarkBaseOptions
```

表示在向电子表格工作表添加形状水印时的选项。

**Learn more:**

* [Add watermarks to spreadsheet documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+spreadsheet+documents)

以下示例演示了如何向 Excel 文档的特定工作表添加水印。
>
> ````
> ```
>
>    SpreadsheetLoadOptions loadOptions = new SpreadsheetLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.xls", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 14));
>
>    SpreadsheetWatermarkShapeOptions options = new SpreadsheetWatermarkShapeOptions();
>    options.setWorksheetIndex(0);
>    
>    watermarker.save("D:\\watermarked_test.xlsx");
>    watermarker.close();
>  
> ```
> ````


## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [SpreadsheetWatermarkShapeOptions()](#SpreadsheetWatermarkShapeOptions--) | 初始化一个新的 `[SpreadsheetWatermarkShapeOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkshapeoptions)` 类实例。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getWorksheetIndex()](#getWorksheetIndex--) | 获取要添加水印的工作表索引。 |
|
|  | [setWorksheetIndex(int value)](#setWorksheetIndex-int-) | 设置要添加水印的工作表索引。 |
|
|  | [getEffects()](#getEffects--) | 获取 `[SpreadsheetImageEffects](../../com.groupdocs.watermark.options/spreadsheetimageeffects)` 或 `[SpreadsheetTextEffects](../../com.groupdocs.watermark.options/spreadsheettexteffects)` 的值，以指定应应用于水印的效果。 |
|
|  | [setEffects(ISpreadsheetWatermarkEffects value)](#setEffects-com.groupdocs.watermark.options.ISpreadsheetWatermarkEffects-) | 获取或设置 `[SpreadsheetImageEffects](../../com.groupdocs.watermark.options/spreadsheetimageeffects)` 或 `[SpreadsheetTextEffects](../../com.groupdocs.watermark.options/spreadsheettexteffects)` 的值，以指定应应用于水印的效果。 |
|
### SpreadsheetWatermarkShapeOptions() {#SpreadsheetWatermarkShapeOptions--}
```
public SpreadsheetWatermarkShapeOptions()
```


初始化一个新的 `[SpreadsheetWatermarkShapeOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkshapeoptions)` 类实例。


### getWorksheetIndex() {#getWorksheetIndex--}
```
public final int getWorksheetIndex()
```


获取要添加水印的工作表索引。


**Returns:**
int - 要添加水印的工作表索引。

<br />

*** ** * ** ***

-1 means every worksheet.

<br />


### setWorksheetIndex(int value) {#setWorksheetIndex-int-}
```
public final void setWorksheetIndex(int value)
```


设置要添加水印的工作表索引。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | int | 要添加水印的工作表索引。 |

<br />

*** ** * ** ***

-1 means every worksheet.

<br />

|

### getEffects() {#getEffects--}
```
public final ISpreadsheetWatermarkEffects getEffects()
```


获取 `[SpreadsheetImageEffects](../../com.groupdocs.watermark.options/spreadsheetimageeffects)` 或 `[SpreadsheetTextEffects](../../com.groupdocs.watermark.options/spreadsheettexteffects)` 的值，以指定应应用于水印的效果。


**Returns:**
[ISpreadsheetWatermarkEffects](../../com.groupdocs.watermark.options/ispreadsheetwatermarkeffects) - The `[SpreadsheetImageEffects](../../com.groupdocs.watermark.options/spreadsheetimageeffects)` or `[SpreadsheetTextEffects](../../com.groupdocs.watermark.options/spreadsheettexteffects)` for effects that should be applied to the watermark.

### setEffects(ISpreadsheetWatermarkEffects value) {#setEffects-com.groupdocs.watermark.options.ISpreadsheetWatermarkEffects-}
```
public final void setEffects(ISpreadsheetWatermarkEffects value)
```


获取或设置 `[SpreadsheetImageEffects](../../com.groupdocs.watermark.options/spreadsheetimageeffects)` 或 `[SpreadsheetTextEffects](../../com.groupdocs.watermark.options/spreadsheettexteffects)` 的值，以指定应应用于水印的效果。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | [ISpreadsheetWatermarkEffects](../../com.groupdocs.watermark.options/ispreadsheetwatermarkeffects) | 用于应当应用于水印的效果的 `[SpreadsheetImageEffects](../../com.groupdocs.watermark.options/spreadsheetimageeffects)` 或 `[SpreadsheetTextEffects](../../com.groupdocs.watermark.options/spreadsheettexteffects)`。 |
|

