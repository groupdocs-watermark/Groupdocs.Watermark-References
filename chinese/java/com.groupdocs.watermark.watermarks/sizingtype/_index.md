---
title: "SizingType"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "指定应如何计算水印大小。"
type: docs
weight: 16
url: /zh/java/com.groupdocs.watermark.watermarks/sizingtype/
---
**Inheritance:**
java.lang.Object
```
public final class SizingType
```

指定应如何计算水印大小。

## 字段

| 字段 | 描述 |
| --- | --- |
|  | [Auto](#Auto) | 水印应根据其内容自动调整大小。 |
|
|  | [Absolute](#Absolute) | 水印应精确地设置为 `[Watermark.getWidth()](../../com.groupdocs.watermark/watermark#getWidth--)` |
以及 `[Watermark.getHeight()](../../com.groupdocs.watermark/watermark#getHeight--)`。
|
|  | [ScaleToParentDimensions](#ScaleToParentDimensions) | 水印应使用以下方式相对于父级尺寸进行缩放 |
指定的 `[Watermark.getScaleFactor()](../../com.groupdocs.watermark/watermark#getScaleFactor--)`。
|
|  | [ScaleToParentArea](#ScaleToParentArea) | 水印应使用指定的 `[Watermark.getScaleFactor()](../../com.groupdocs.watermark/watermark#getScaleFactor--)` 相对于父级区域进行缩放。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [toString(int value)](#toString-int-) | 返回 `[SizingType](../../com.groupdocs.watermark.watermarks/sizingtype)` 值的字符串表示形式。 |
|
|  | [parse(String value)](#parse-java.lang.String-) | 将字符串解析为 `[SizingType](../../com.groupdocs.watermark.watermarks/sizingtype)` 枚举值。 |
|
### Auto {#Auto}
```
public static final int Auto
```


水印应根据其内容自动调整大小。


### Absolute {#Absolute}
```
public static final int Absolute
```


水印应精确地设置为 `[Watermark.getWidth()](../../com.groupdocs.watermark/watermark#getWidth--)`
以及 `[Watermark.getHeight()](../../com.groupdocs.watermark/watermark#getHeight--)`。


### ScaleToParentDimensions {#ScaleToParentDimensions}
```
public static final int ScaleToParentDimensions
```


水印应使用以下方式相对于父级尺寸进行缩放
指定的 `[Watermark.getScaleFactor()](../../com.groupdocs.watermark/watermark#getScaleFactor--)`。


### ScaleToParentArea {#ScaleToParentArea}
```
public static final int ScaleToParentArea
```


水印应使用指定的 `[Watermark.getScaleFactor()](../../com.groupdocs.watermark/watermark#getScaleFactor--)` 相对于父级区域进行缩放。


### toString(int value) {#toString-int-}
```
public static final String toString(int value)
```


返回 `[SizingType](../../com.groupdocs.watermark.watermarks/sizingtype)` 值的字符串表示形式。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | int | 要转换的值。 |
|

**Returns:**
java.lang.String - `[SizingType](../../com.groupdocs.watermark.watermarks/sizingtype)` 值的字符串表示形式。

### parse(String value) {#parse-java.lang.String-}
```
public static final int parse(String value)
```


将字符串解析为 `[SizingType](../../com.groupdocs.watermark.watermarks/sizingtype)` 枚举值。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | java.lang.String | 要解析的字符串。 |
|

**Returns:**
int - `[SizingType](../../com.groupdocs.watermark.watermarks/sizingtype)` 枚举值。

