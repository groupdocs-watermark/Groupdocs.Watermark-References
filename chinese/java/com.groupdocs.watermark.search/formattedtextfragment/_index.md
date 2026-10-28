---
title: "FormattedTextFragment"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "提供用于内容中格式化文本片段的抽象基类。"
type: docs
weight: 26
url: /zh/java/com.groupdocs.watermark.search/formattedtextfragment/
---
**Inheritance:**
java.lang.Object
```
public abstract class FormattedTextFragment
```

提供用于内容中格式化文本片段的抽象基类。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [FormattedTextFragment()](#FormattedTextFragment--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getText()](#getText--) | 获取片段文本。 |
|
|  | [getFont()](#getFont--) | 获取文本的字体。 |
|
|  | [getForegroundColor()](#getForegroundColor--) | 获取文本的前景颜色。 |
|
|  | [getBackgroundColor()](#getBackgroundColor--) | 获取文本的背景颜色。 |
|
### FormattedTextFragment() {#FormattedTextFragment--}
```
public FormattedTextFragment()
```




### getText() {#getText--}
```
public abstract String getText()
```


获取片段文本。


**Returns:**
java.lang.String - 片段文本。

### getFont() {#getFont--}
```
public abstract Font getFont()
```


获取文本的字体。


**Returns:**
[Font](../../com.groupdocs.watermark.watermarks/font) - The font of the text.

### getForegroundColor() {#getForegroundColor--}
```
public abstract Color getForegroundColor()
```


获取文本的前景颜色。


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The foreground color of the text.

### getBackgroundColor() {#getBackgroundColor--}
```
public abstract Color getBackgroundColor()
```


获取文本的背景颜色。


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The background color of the text.

