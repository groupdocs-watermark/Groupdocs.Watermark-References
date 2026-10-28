---
title: "PresentationFormattedTextFragment"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "表示 PowerPoint 文档中格式化文本的片段。"
type: docs
weight: 82
url: /zh/java/com.groupdocs.watermark.contents/presentationformattedtextfragment/
---
**Inheritance:**
java.lang.Object，[com.groupdocs.watermark.search.FormattedTextFragment](../../com.groupdocs.watermark.search/formattedtextfragment)

**All Implemented Interfaces:**
[com.groupdocs.watermark.contents.IPresentationHyperlinkContainer](../../com.groupdocs.watermark.contents/ipresentationhyperlinkcontainer)
```
public class PresentationFormattedTextFragment extends FormattedTextFragment implements IPresentationHyperlinkContainer
```

表示 PowerPoint 文档中格式化文本的片段。

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
|  | [getHyperlink(int actionType)](#getHyperlink-int-) | 获取与文本关联的超链接。 |
|
|  | [setHyperlink(int actionType, String url)](#setHyperlink-int-java.lang.String-) | 设置与文本关联的超链接。 |
|
### getText() {#getText--}
```
public String getText()
```


获取片段文本。


**Returns:**
java.lang.String - 片段文本。

### getFont() {#getFont--}
```
public Font getFont()
```


获取文本的字体。


**Returns:**
[Font](../../com.groupdocs.watermark.watermarks/font) - The font of the text.

### getForegroundColor() {#getForegroundColor--}
```
public Color getForegroundColor()
```


获取文本的前景颜色。


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The foreground color of the text.

### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


获取文本的背景颜色。


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The background color of the text.

### getHyperlink(int actionType) {#getHyperlink-int-}
```
public final String getHyperlink(int actionType)
```


获取与文本关联的超链接。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | actionType | int | 激活超链接的操作。 |
|

**Returns:**
java.lang.String - 在指定操作上激活的超链接的 URL。

### setHyperlink(int actionType, String url) {#setHyperlink-int-java.lang.String-}
```
public final void setHyperlink(int actionType, String url)
```


设置与文本关联的超链接。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | actionType | int | 激活超链接的操作。 |
|
|  | url | java.lang.String | 超链接 URL。 |
|

