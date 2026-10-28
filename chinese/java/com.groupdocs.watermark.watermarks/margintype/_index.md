---
title: "MarginType"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "指定应如何解释边距值。"
type: docs
weight: 14
url: /zh/java/com.groupdocs.watermark.watermarks/margintype/
---
**Inheritance:**
java.lang.Object
```
public final class MarginType
```

指定应如何解释边距值。

## 字段

| 字段 | 描述 |
| --- | --- |
|  | [Absolute](#Absolute) | 以内容单位测量的边距值。 |
|
|  | [RelativeToParentDimensions](#RelativeToParentDimensions) | 边距值应解释为相应父维度的一部分。 |
|
|  | [RelativeToParentMinDimension](#RelativeToParentMinDimension) | 边距值应解释为父最小维度的一部分。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [toString(int value)](#toString-int-) | 返回 `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)` 值的字符串表示形式。 |
|
|  | [parse(String value)](#parse-java.lang.String-) | 将字符串解析为 `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)` 枚举值。 |
|
### Absolute {#Absolute}
```
public static final int Absolute
```


以内容单位测量的边距值。


### RelativeToParentDimensions {#RelativeToParentDimensions}
```
public static final int RelativeToParentDimensions
```


边距值应解释为相应父维度的一部分。


左侧和右侧边距相对于父宽度，
上侧和下侧边距相对于父高度。
如果选择此类型，边距值必须在 0.0 到 1.0 之间。


### RelativeToParentMinDimension {#RelativeToParentMinDimension}
```
public static final int RelativeToParentMinDimension
```


边距值应解释为父最小维度的一部分。


如果选择此类型，边距值必须在 0.0 到 1.0 之间。


### toString(int value) {#toString-int-}
```
public static final String toString(int value)
```


返回 `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)` 值的字符串表示形式。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | int | 要转换的值。 |
|

**Returns:**
java.lang.String - `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)` 值的字符串表示形式。

### parse(String value) {#parse-java.lang.String-}
```
public static final int parse(String value)
```


将字符串解析为 `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)` 枚举值。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | java.lang.String | 要解析的字符串。 |
|

**Returns:**
int - `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)` 枚举值。

