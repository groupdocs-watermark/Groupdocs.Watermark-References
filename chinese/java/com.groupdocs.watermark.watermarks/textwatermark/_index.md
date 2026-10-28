---
title: "TextWatermark"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "表示文本水印。"
type: docs
weight: 18
url: /zh/java/com.groupdocs.watermark.watermarks/textwatermark/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.Watermark](../../com.groupdocs.watermark/watermark)
```
public class TextWatermark extends Watermark
```

表示文本水印。

**Learn more:**

* [Adding text watermarks](../https://docs.groupdocs.com/display/watermarkjava/Adding+text+watermarks)

以下示例演示了如何根据父级大小缩放文本水印。
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("C:\\test.some_ext");
>    TextWatermark watermark = new TextWatermark("test watermark", new Font("Arial", 36));
>
>    watermark.setHorizontalAlignment(HorizontalAlignment.Center);
>    watermark.setVerticalAlignment(VerticalAlignment.Center);
>    watermark.setSizingType(SizingType.ScaleToParentDimensions);
>    watermark.setRotateAngle(45);
>    watermark.setScaleFactor(0.4);
>
>    watermarker.add(watermark);
>
>    watermarker.save("C:\\modified_test.some_ext");
>    watermarker.close();
>  
> ```
> ````


## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [TextWatermark(String text, Font font)](#TextWatermark-java.lang.String-com.groupdocs.watermark.watermarks.Font-) | 使用指定的文本和字体初始化 `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)` 类的新实例。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getText()](#getText--) | 获取用于水印的文本。 |
|
|  | [setText(String value)](#setText-java.lang.String-) | 设置用于水印的文本。 |
|
|  | [getFont()](#getFont--) | 获取文本的字体。 |
|
|  | [setFont(Font value)](#setFont-com.groupdocs.watermark.watermarks.Font-) | 设置文本的字体。 |
|
|  | [getForegroundColor()](#getForegroundColor--) | 获取文本的前景颜色。 |
|
|  | [setForegroundColor(Color value)](#setForegroundColor-com.groupdocs.watermark.watermarks.Color-) | 设置文本的前景颜色。 |
|
|  | [getBackgroundColor()](#getBackgroundColor--) | 获取文本的背景颜色。 |
|
|  | [setBackgroundColor(Color value)](#setBackgroundColor-com.groupdocs.watermark.watermarks.Color-) | 设置文本的背景颜色。 |
|
|  | [getTextAlignment()](#getTextAlignment--) | 获取水印 `[TextAlignment](../../com.groupdocs.watermark.watermarks/textalignment)`。 |
|
|  | [setTextAlignment(int value)](#setTextAlignment-int-) | 设置水印 `[TextAlignment](../../com.groupdocs.watermark.watermarks/textalignment)`。 |
|
| [isImageWatermark()](#isImageWatermark--) |  |
| [isTextWatermark()](#isTextWatermark--) |  |
| [getForegroundColorConsideringOpacity()](#getForegroundColorConsideringOpacity--) |  |
| [getBackgroundColorConsideringOpacity()](#getBackgroundColorConsideringOpacity--) |  |
| [getSize()](#getSize--) |  |
|  | [getPadding()](#getPadding--) | 获取此 `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)` 的填充设置。 |
|
|  | [setPadding(Thickness value)](#setPadding-com.groupdocs.watermark.Thickness-) | 设置此 `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)` 的填充设置。 |
|
| [deepClone()](#deepClone--) |  |
| [hasSameValues(Watermark watermark)](#hasSameValues-com.groupdocs.watermark.Watermark-) |  |
| [createGeometry(ContentPartGeometry parent)](#createGeometry-com.groupdocs.watermark.internal.ContentPartGeometry-) |  |
### TextWatermark(String text, Font font) {#TextWatermark-java.lang.String-com.groupdocs.watermark.watermarks.Font-}
```
public TextWatermark(String text, Font font)
```


使用指定的文本和字体初始化 `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)` 类的新实例。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 文本 | java.lang.String | 用于水印的文本。 |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | 文本的字体。 |
|

### getText() {#getText--}
```
public final String getText()
```


获取用于水印的文本。


**Returns:**
java.lang.String - 表示水印文本的字符串。

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


设置用于水印的文本。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | java.lang.String | 表示水印文本的字符串。 |
|

### getFont() {#getFont--}
```
public final Font getFont()
```


获取文本的字体。


**Returns:**
[Font](../../com.groupdocs.watermark.watermarks/font) - The font of the text.

### setFont(Font value) {#setFont-com.groupdocs.watermark.watermarks.Font-}
```
public final void setFont(Font value)
```


设置文本的字体。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | [Font](../../com.groupdocs.watermark.watermarks/font) | 文本的字体。 |
|

### getForegroundColor() {#getForegroundColor--}
```
public final Color getForegroundColor()
```


获取文本的前景颜色。


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The foreground color of the text.

### setForegroundColor(Color value) {#setForegroundColor-com.groupdocs.watermark.watermarks.Color-}
```
public final void setForegroundColor(Color value)
```


设置文本的前景颜色。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | [Color](../../com.groupdocs.watermark.watermarks/color) | 文本的前景颜色。 |
|

### getBackgroundColor() {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```


获取文本的背景颜色。


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The background color of the text.

### setBackgroundColor(Color value) {#setBackgroundColor-com.groupdocs.watermark.watermarks.Color-}
```
public final void setBackgroundColor(Color value)
```


设置文本的背景颜色。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | [Color](../../com.groupdocs.watermark.watermarks/color) | 文本的背景颜色。 |
|

### getTextAlignment() {#getTextAlignment--}
```
public final int getTextAlignment()
```


获取水印 `[TextAlignment](../../com.groupdocs.watermark.watermarks/textalignment)`。

默认值是 `[TextAlignment.Left](../../com.groupdocs.watermark.watermarks/textalignment#Left)`。


**Returns:**
int - 水印 `[TextAlignment](../../com.groupdocs.watermark.watermarks/textalignment)`。

### setTextAlignment(int value) {#setTextAlignment-int-}
```
public final void setTextAlignment(int value)
```


设置水印 `[TextAlignment](../../com.groupdocs.watermark.watermarks/textalignment)`。

默认值是 `[TextAlignment.Left](../../com.groupdocs.watermark.watermarks/textalignment#Left)`。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | int | 水印 `[TextAlignment](../../com.groupdocs.watermark.watermarks/textalignment)`。 |
|

### isImageWatermark() {#isImageWatermark--}
```
public boolean isImageWatermark()
```




**Returns:**
boolean
### isTextWatermark() {#isTextWatermark--}
```
public boolean isTextWatermark()
```




**Returns:**
boolean
### getForegroundColorConsideringOpacity() {#getForegroundColorConsideringOpacity--}
```
public final Color getForegroundColorConsideringOpacity()
```




**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color)
### getBackgroundColorConsideringOpacity() {#getBackgroundColorConsideringOpacity--}
```
public final Color getBackgroundColorConsideringOpacity()
```




**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color)
### getSize() {#getSize--}
```
public SizeD getSize()
```




**Returns:**
[SizeD](../../com.groupdocs.watermark.internal/sized)
### getPadding() {#getPadding--}
```
public final Thickness getPadding()
```


获取此 `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)` 的填充设置。此属性仅适用于图像文件。


**Returns:**
[Thickness](../../com.groupdocs.watermark/thickness) - The padding settings of this `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)`.

### setPadding(Thickness value) {#setPadding-com.groupdocs.watermark.Thickness-}
```
public final void setPadding(Thickness value)
```


设置此 `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)` 的填充设置。此属性仅适用于图像文件。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | [Thickness](../../com.groupdocs.watermark/thickness) | 此 `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)` 的填充设置。 |
|

### deepClone() {#deepClone--}
```
public Watermark deepClone()
```




**Returns:**
[Watermark](../../com.groupdocs.watermark/watermark)
### hasSameValues(Watermark watermark) {#hasSameValues-com.groupdocs.watermark.Watermark-}
```
public boolean hasSameValues(Watermark watermark)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |

**Returns:**
boolean
### createGeometry(ContentPartGeometry parent) {#createGeometry-com.groupdocs.watermark.internal.ContentPartGeometry-}
```
public WatermarkGeometry createGeometry(ContentPartGeometry parent)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| parent | [ContentPartGeometry](../../com.groupdocs.watermark.internal/contentpartgeometry) |  |

**Returns:**
[WatermarkGeometry](../../com.groupdocs.watermark.internal/watermarkgeometry)
