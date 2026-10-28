---
title: "WordProcessingWatermarkHeaderFooterOptions"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "表示在向 Word 部分的页眉/页脚添加水印时的选项。"
type: docs
weight: 74
url: /zh/java/com.groupdocs.watermark.options/wordprocessingwatermarkheaderfooteroptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkBaseOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkbaseoptions)
```
public final class WordProcessingWatermarkHeaderFooterOptions extends WordProcessingWatermarkBaseOptions
```

表示在向 Word 部分的页眉/页脚添加水印时的选项。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [WordProcessingWatermarkHeaderFooterOptions()](#WordProcessingWatermarkHeaderFooterOptions--) | 初始化一个新的 `[WordProcessingWatermarkHeaderFooterOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkheaderfooteroptions)` 类的实例。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getSectionIndex()](#getSectionIndex--) | 获取要添加水印的节索引。 |
|
|  | [setSectionIndex(int value)](#setSectionIndex-int-) | 设置要添加水印的节索引。 |
|
|  | [getHeaderFooterType()](#getHeaderFooterType--) | 获取标识要添加水印的页眉或页脚类型的值。 |
|
|  | [setHeaderFooterType(int value)](#setHeaderFooterType-int-) | 设置标识要添加水印的页眉或页脚类型的值。 |
|
### WordProcessingWatermarkHeaderFooterOptions() {#WordProcessingWatermarkHeaderFooterOptions--}
```
public WordProcessingWatermarkHeaderFooterOptions()
```


初始化一个新的 `[WordProcessingWatermarkHeaderFooterOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkheaderfooteroptions)` 类的实例。


### getSectionIndex() {#getSectionIndex--}
```
public final int getSectionIndex()
```


获取要添加水印的节索引。


**Returns:**
int - 要添加水印的章节索引。

<br />

*** ** * ** ***

-1 means all sections.

<br />


### setSectionIndex(int value) {#setSectionIndex-int-}
```
public final void setSectionIndex(int value)
```


设置要添加水印的节索引。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | int | 要添加水印的章节索引。 |

<br />

*** ** * ** ***

-1 means all sections.

<br />

|

### getHeaderFooterType() {#getHeaderFooterType--}
```
public final int getHeaderFooterType()
```


获取标识要添加水印的页眉或页脚类型的值。


**Returns:**
int - 标识要添加水印的页眉或页脚类型的 `[OfficeHeaderFooterType](../../com.groupdocs.watermark.contents/officeheaderfootertype)` 值。

### setHeaderFooterType(int value) {#setHeaderFooterType-int-}
```
public final void setHeaderFooterType(int value)
```


设置标识要添加水印的页眉或页脚类型的值。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | int | 标识要添加水印的页眉或页脚类型的 `[OfficeHeaderFooterType](../../com.groupdocs.watermark.contents/officeheaderfootertype)` 值。 |
|

