---
title: "SpreadsheetWatermarkBaseOptions"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "用于向电子表格文档添加水印选项的基类。"
type: docs
weight: 56
url: /zh/java/com.groupdocs.watermark.options/spreadsheetwatermarkbaseoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.SpreadsheetWatermarkOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkoptions)
```
public abstract class SpreadsheetWatermarkBaseOptions extends SpreadsheetWatermarkOptions
```

用于向电子表格文档添加水印选项的基类。

## 方法

| 方法 | 描述 |
| --- | --- |
|  | [isLocked()](#isLocked--) | 获取指示在 Excel 中是否禁止编辑形状的值。 |
|
|  | [setLocked(boolean value)](#setLocked-boolean-) | 设置指示在 Excel 中是否禁止编辑形状的值。 |
|
|  | [getName()](#getName--) | 获取形状的名称。 |
|
|  | [setName(String value)](#setName-java.lang.String-) | 设置形状的名称。 |
|
|  | [getAlternativeText()](#getAlternativeText--) | 获取将与形状关联的描述性（替代）文本。 |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | 设置将与形状关联的描述性（替代）文本。 |
|
### isLocked() {#isLocked--}
```
public final boolean isLocked()
```


获取指示在 Excel 中是否禁止编辑形状的值。


**Returns:**
boolean - 如果该值为 true，则禁止编辑形状。默认情况下，该值为 false，形状可以在 Excel 中编辑。

### setLocked(boolean value) {#setLocked-boolean-}
```
public final void setLocked(boolean value)
```


设置指示在 Excel 中是否禁止编辑形状的值。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | boolean | 如果该值为 true，则禁止编辑形状。默认情况下，该值为 false，形状可以在 Excel 中编辑。 |
|

### getName() {#getName--}
```
public final String getName()
```


获取形状的名称。


**Returns:**
java.lang.String - 形状名称。

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


设置形状的名称。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | java.lang.String | 形状名称。 |
|

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


获取将与形状关联的描述性（替代）文本。


**Returns:**
java.lang.String - 将与形状关联的描述性（替代）文本。

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


设置将与形状关联的描述性（替代）文本。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | java.lang.String | 将与形状关联的描述性（替代）文本。 |
|

