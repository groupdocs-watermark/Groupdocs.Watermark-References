---
title: "FormattedTextFragmentCollection"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "表示可变的格式化文本片段集合。"
type: docs
weight: 27
url: /zh/java/com.groupdocs.watermark.search/formattedtextfragmentcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase
```
public class FormattedTextFragmentCollection extends RemoveOnlyListBase<FormattedTextFragment>
```

表示可变的格式化文本片段集合。

此集合包含 `[FormattedTextFragment](../../com.groupdocs.watermark.search/formattedtextfragment)` 基类型的项。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [FormattedTextFragmentCollection(int collectionType)](#FormattedTextFragmentCollection-int-) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getCollectionType()](#getCollectionType--) | 获取格式化片段集合的类型。 |
|
| [getDefaultFont()](#getDefaultFont--) |  |
| [getDefaultForegroundColor()](#getDefaultForegroundColor--) |  |
| [getDefaultBackgroundColor()](#getDefaultBackgroundColor--) |  |
| [getText()](#getText--) |  |
|  | [add(String text)](#add-java.lang.String-) | 向集合添加一个格式化文本片段。 |
|
|  | [add(String text, Font font)](#add-java.lang.String-com.groupdocs.watermark.watermarks.Font-) | 向集合添加一个格式化文本片段。 |
|
|  | [add(String text, Font font, Color foregroundColor)](#add-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-) | 向集合添加一个格式化文本片段。 |
|
|  | [add(String text, Font font, Color foregroundColor, Color backgroundColor)](#add-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-) | 向集合添加一个格式化文本片段。 |
|
|  | [insert(int index, String text)](#insert-int-java.lang.String-) | 在指定索引处将格式化文本片段插入集合。 |
|
|  | [insert(int index, String text, Font font)](#insert-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-) | 在指定索引处将格式化文本片段插入集合。 |
|
|  | [insert(int index, String text, Font font, Color foregroundColor)](#insert-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-) | 在指定索引处将格式化文本片段插入集合。 |
|
|  | [insert(int index, String text, Font font, Color foregroundColor, Color backgroundColor)](#insert-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-) | 在指定索引处将格式化文本片段插入集合。 |
|
| [createInDocument(int index, String text, Font font, Color foregroundColor, Color backgroundColor)](#createInDocument-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-) |  |
| [setText(String text)](#setText-java.lang.String-) |  |
### FormattedTextFragmentCollection(int collectionType) {#FormattedTextFragmentCollection-int-}
```
public FormattedTextFragmentCollection(int collectionType)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| collectionType | int |  |

### getCollectionType() {#getCollectionType--}
```
public final int getCollectionType()
```


获取格式化片段集合的类型。


**Returns:**
int - 格式化片段集合的类型。

### getDefaultFont() {#getDefaultFont--}
```
public final Font getDefaultFont()
```




**Returns:**
[Font](../../com.groupdocs.watermark.watermarks/font)
### getDefaultForegroundColor() {#getDefaultForegroundColor--}
```
public final Color getDefaultForegroundColor()
```




**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color)
### getDefaultBackgroundColor() {#getDefaultBackgroundColor--}
```
public final Color getDefaultBackgroundColor()
```




**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color)
### getText() {#getText--}
```
public String getText()
```




**Returns:**
java.lang.String
### add(String text) {#add-java.lang.String-}
```
public final void add(String text)
```


向集合添加一个格式化文本片段。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 文本 | java.lang.String | 片段文本。 |
|

### add(String text, Font font) {#add-java.lang.String-com.groupdocs.watermark.watermarks.Font-}
```
public final void add(String text, Font font)
```


向集合添加一个格式化文本片段。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 文本 | java.lang.String | 片段文本。 |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | 文本的字体。 |
|

### add(String text, Font font, Color foregroundColor) {#add-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-}
```
public final void add(String text, Font font, Color foregroundColor)
```


向集合添加一个格式化文本片段。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 文本 | java.lang.String | 片段文本。 |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | 文本的字体。 |
|
|  | foregroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) | 文本的前景颜色。 |
|

### add(String text, Font font, Color foregroundColor, Color backgroundColor) {#add-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-}
```
public final void add(String text, Font font, Color foregroundColor, Color backgroundColor)
```


向集合添加一个格式化文本片段。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 文本 | java.lang.String | 片段文本。 |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | 文本的字体。 |
|
|  | foregroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) | 文本的前景颜色。 |
|
|  | backgroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) | 文本的背景颜色。 |
|

### insert(int index, String text) {#insert-int-java.lang.String-}
```
public final void insert(int index, String text)
```


在指定索引处将格式化文本片段插入集合。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | index | int | 应插入格式化文本片段的零基索引。 |
|
|  | 文本 | java.lang.String | 片段文本。 |
|

### insert(int index, String text, Font font) {#insert-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-}
```
public final void insert(int index, String text, Font font)
```


在指定索引处将格式化文本片段插入集合。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | index | int | 应插入格式化文本片段的零基索引。 |
|
|  | 文本 | java.lang.String | 片段文本。 |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | 文本的字体。 |
|

### insert(int index, String text, Font font, Color foregroundColor) {#insert-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-}
```
public final void insert(int index, String text, Font font, Color foregroundColor)
```


在指定索引处将格式化文本片段插入集合。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | index | int | 应插入格式化文本片段的零基索引。 |
|
|  | 文本 | java.lang.String | 片段文本。 |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | 文本的字体。 |
|
|  | foregroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) | 文本的前景颜色。 |
|

### insert(int index, String text, Font font, Color foregroundColor, Color backgroundColor) {#insert-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-}
```
public final void insert(int index, String text, Font font, Color foregroundColor, Color backgroundColor)
```


在指定索引处将格式化文本片段插入集合。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | index | int | 应插入格式化文本片段的零基索引。 |
|
|  | 文本 | java.lang.String | 片段文本。 |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | 文本的字体。 |
|
|  | foregroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) | 文本的前景颜色。 |
|
|  | backgroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) | 文本的背景颜色。 |
|

### createInDocument(int index, String text, Font font, Color foregroundColor, Color backgroundColor) {#createInDocument-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-}
```
public FormattedTextFragment createInDocument(int index, String text, Font font, Color foregroundColor, Color backgroundColor)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |
| 文本 | java.lang.String |  |
| font | [Font](../../com.groupdocs.watermark.watermarks/font) |  |
| foregroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) |  |
| backgroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) |  |

**Returns:**
[FormattedTextFragment](../../com.groupdocs.watermark.search/formattedtextfragment)
### setText(String text) {#setText-java.lang.String-}
```
public void setText(String text)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文本 | java.lang.String |  |

