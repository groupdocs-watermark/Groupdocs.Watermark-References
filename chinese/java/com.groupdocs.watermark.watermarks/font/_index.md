---
title: "Font"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "表示字体的类。"
type: docs
weight: 11
url: /zh/java/com.groupdocs.watermark.watermarks/font/
---
**Inheritance:**
java.lang.Object
```
public final class Font
```

表示字体的类。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [Font(String fontFamilyName, float size)](#Font-java.lang.String-float-) | 使用指定的字体族名称和大小初始化 `[Font](../../com.groupdocs.watermark.watermarks/font)` 类的新实例。 |
|
|  | [Font(String fontFamilyName, float size, int style)](#Font-java.lang.String-float-int-) | 使用指定的字体族名称、大小和样式初始化 `[Font](../../com.groupdocs.watermark.watermarks/font)` 类的新实例。 |
|
| [Font(String fontFamilyName, String folderPath, float size)](#Font-java.lang.String-java.lang.String-float-) |  |
| [Font(String fontFamilyName, String folderPath, float size, FontStyle style)](#Font-java.lang.String-java.lang.String-float-com.groupdocs.watermark.watermarks.FontStyle-) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getFolderPath()](#getFolderPath--) |  |
| [setFolderPath(String folderPath)](#setFolderPath-java.lang.String-) |  |
|  | [getFamilyName()](#getFamilyName--) | 获取此 `[Font](../../com.groupdocs.watermark.watermarks/font)` 的族名称。 |
|
|  | [getSize()](#getSize--) | 获取此 `[Font](../../com.groupdocs.watermark.watermarks/font)` 的大小。 |
|
|  | [getStyle()](#getStyle--) | 获取此 `[Font](../../com.groupdocs.watermark.watermarks/font)` 的 `[FontStyle](../../com.groupdocs.watermark.watermarks/fontstyle)`。 |
|
|  | [getBold()](#getBold--) | 获取一个值，指示字体是否为粗体。 |
|
|  | [getItalic()](#getItalic--) | 获取一个值，指示字体是否为斜体。 |
|
|  | [getStrikeout()](#getStrikeout--) | 获取一个值，指示字体是否指定在字体上划横线。 |
|
|  | [getUnderline()](#getUnderline--) | 获取一个值，指示字体是否带下划线。 |
|
### Font(String fontFamilyName, float size) {#Font-java.lang.String-float-}
```
public Font(String fontFamilyName, float size)
```


使用指定的字体族名称和大小初始化 `[Font](../../com.groupdocs.watermark.watermarks/font)` 类的新实例。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | fontFamilyName | java.lang.String | 字体族名称。 |
|
|  | size | float | 新字体的大小。 |
|

### Font(String fontFamilyName, float size, int style) {#Font-java.lang.String-float-int-}
```
public Font(String fontFamilyName, float size, int style)
```


使用指定的字体族名称、大小和样式初始化 `[Font](../../com.groupdocs.watermark.watermarks/font)` 类的新实例。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | fontFamilyName | java.lang.String | 字体族名称。 |
|
|  | size | float | 新字体的大小。 |
|
|  | style | int | 新字体的 `[FontStyle](../../com.groupdocs.watermark.watermarks/fontstyle)`。 |
|

### Font(String fontFamilyName, String folderPath, float size) {#Font-java.lang.String-java.lang.String-float-}
```
public Font(String fontFamilyName, String folderPath, float size)
```


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fontFamilyName | java.lang.String |  |
| folderPath | java.lang.String |  |
| size | float |  |

### Font(String fontFamilyName, String folderPath, float size, FontStyle style) {#Font-java.lang.String-java.lang.String-float-com.groupdocs.watermark.watermarks.FontStyle-}
```
public Font(String fontFamilyName, String folderPath, float size, FontStyle style)
```


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fontFamilyName | java.lang.String |  |
| folderPath | java.lang.String |  |
| size | float |  |
| style | [FontStyle](../../com.groupdocs.watermark.watermarks/fontstyle) |  |

### getFolderPath() {#getFolderPath--}
```
public String getFolderPath()
```




**Returns:**
java.lang.String
### setFolderPath(String folderPath) {#setFolderPath-java.lang.String-}
```
public void setFolderPath(String folderPath)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| folderPath | java.lang.String |  |

### getFamilyName() {#getFamilyName--}
```
public final String getFamilyName()
```


获取此 `[Font](../../com.groupdocs.watermark.watermarks/font)` 的族名称。


**Returns:**
java.lang.String - 此 `[Font](../../com.groupdocs.watermark.watermarks/font)` 的族名称。

### getSize() {#getSize--}
```
public final float getSize()
```


获取此 `[Font](../../com.groupdocs.watermark.watermarks/font)` 的大小。


**Returns:**
float - 此 `[Font](../../com.groupdocs.watermark.watermarks/font)` 的大小。

### getStyle() {#getStyle--}
```
public final int getStyle()
```


获取此 `[Font](../../com.groupdocs.watermark.watermarks/font)` 的 `[FontStyle](../../com.groupdocs.watermark.watermarks/fontstyle)`。

默认值是 `[FontStyle.Regular](../../com.groupdocs.watermark.watermarks/fontstyle#Regular)`（普通文本）。


**Returns:**
int - 此 `[Font](../../com.groupdocs.watermark.watermarks/font)` 的 `[FontStyle](../../com.groupdocs.watermark.watermarks/fontstyle)`。

### getBold() {#getBold--}
```
public final boolean getBold()
```


获取一个值，指示字体是否为粗体。


**Returns:**
boolean - 如果此字体为粗体，则为 True；否则为 false。

### getItalic() {#getItalic--}
```
public final boolean getItalic()
```


获取一个值，指示字体是否为斜体。


**Returns:**
boolean - 如果此字体为斜体，则为 True；否则为 false。

### getStrikeout() {#getStrikeout--}
```
public final boolean getStrikeout()
```


获取一个值，指示字体是否指定在字体上划横线。


**Returns:**
boolean - 如果此字体在字体上划横线，则为 True；否则为 false。

### getUnderline() {#getUnderline--}
```
public final boolean getUnderline()
```


获取一个值，指示字体是否带下划线。


**Returns:**
boolean - 如果此字体带下划线，则为 True；否则为 false。

