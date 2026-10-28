---
title: "OfficeImageEffects"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "表示可应用于办公内容图像水印的效果。"
type: docs
weight: 45
url: /zh/java/com.groupdocs.watermark.contents/officeimageeffects/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.watermark.internal.IDocumentSpecificSettings](../../com.groupdocs.watermark.internal/idocumentspecificsettings)
```
public abstract class OfficeImageEffects implements IDocumentSpecificSettings
```

表示可应用于办公内容图像水印的效果。

## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getBorderLineFormat()](#getBorderLineFormat--) | 获取图像边框的线条格式设置。 |
|
|  | [setBorderLineFormat(OfficeLineFormat value)](#setBorderLineFormat-com.groupdocs.watermark.contents.OfficeLineFormat-) | 设置图像边框的线条格式设置。 |
|
|  | [getGrayScale()](#getGrayScale--) | 获取指示图片是否以灰度模式显示的值。 |
|
|  | [setGrayScale(boolean value)](#setGrayScale-boolean-) | 设置指示图片是否以灰度模式显示的值。 |
|
|  | [getChromaKey()](#getChromaKey--) | 获取将被视为透明的图像颜色值。 |
|
|  | [setChromaKey(Color value)](#setChromaKey-com.groupdocs.watermark.watermarks.Color-) | 设置将被视为透明的图像颜色值。 |
|
|  | [getBrightness()](#getBrightness--) | 获取图片的亮度。 |
|
|  | [setBrightness(double value)](#setBrightness-double-) | 设置图片的亮度。 |
|
|  | [getContrast()](#getContrast--) | 获取指定图片的对比度。 |
|
|  | [setContrast(double value)](#setContrast-double-) | 设置指定图片的对比度。 |
|
### getBorderLineFormat() {#getBorderLineFormat--}
```
public final OfficeLineFormat getBorderLineFormat()
```


获取图像边框的线条格式设置。


**Returns:**
[OfficeLineFormat](../../com.groupdocs.watermark.contents/officelineformat) - Instance of  OfficeLineFormat  class, representing shape line format.

### setBorderLineFormat(OfficeLineFormat value) {#setBorderLineFormat-com.groupdocs.watermark.contents.OfficeLineFormat-}
```
public final void setBorderLineFormat(OfficeLineFormat value)
```


设置图像边框的线条格式设置。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | [OfficeLineFormat](../../com.groupdocs.watermark.contents/officelineformat) | OfficeLineFormat 类的实例，表示形状线条格式。 |
|

### getGrayScale() {#getGrayScale--}
```
public final boolean getGrayScale()
```


获取指示图片是否以灰度模式显示的值。


**Returns:**
boolean - 默认值为 false。

### setGrayScale(boolean value) {#setGrayScale-boolean-}
```
public final void setGrayScale(boolean value)
```


设置指示图片是否以灰度模式显示的值。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | boolean | 默认值为 false。 |
|

### getChromaKey() {#getChromaKey--}
```
public final Color getChromaKey()
```


获取将被视为透明的图像颜色值。


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The default value is fully transparent color.

### setChromaKey(Color value) {#setChromaKey-com.groupdocs.watermark.watermarks.Color-}
```
public final void setChromaKey(Color value)
```


设置将被视为透明的图像颜色值。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | [Color](../../com.groupdocs.watermark.watermarks/color) | 默认值为全透明颜色。 |
|

### getBrightness() {#getBrightness--}
```
public final double getBrightness()
```


获取图片的亮度。此属性的值必须
取值范围为 0.0（最暗）至 1.0（最亮）。


**Returns:**
double - 默认值为 0.5。

### setBrightness(double value) {#setBrightness-double-}
```
public final void setBrightness(double value)
```


设置图片的亮度。此属性的值必须
取值范围为 0.0（最暗）至 1.0（最亮）。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | double | 默认值为 0.5。 |
|

### getContrast() {#getContrast--}
```
public final double getContrast()
```


获取指定图片的对比度。此属性的值
必须是 0.0（最低对比度）至 1.0（最高对比度）之间的数字。


**Returns:**
double - 默认值为 0.5。

### setContrast(double value) {#setContrast-double-}
```
public final void setContrast(double value)
```


设置指定图片的对比度。此属性的值
必须是 0.0（最低对比度）至 1.0（最高对比度）之间的数字。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | double | 默认值为 0.5。 |
|

