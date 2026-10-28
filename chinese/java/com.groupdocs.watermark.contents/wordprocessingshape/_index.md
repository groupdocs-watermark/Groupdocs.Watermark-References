---
title: "WordProcessingShape"
second_title: "GroupDocs.Watermark for Java API Reference"
description: "表示 Word 文档中的绘图形状。"
type: docs
weight: 141
url: /zh/java/com.groupdocs.watermark.contents/wordprocessingshape/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.IRotatableTwoDObject](../../com.groupdocs.watermark.search/irotatabletwodobject), [com.groupdocs.watermark.search.IHyperlinkContainer](../../com.groupdocs.watermark.search/ihyperlinkcontainer)
```
public class WordProcessingShape extends ShapeSearchAdapter implements IRotatableTwoDObject, IHyperlinkContainer
```

表示 Word 文档中的绘图形状。

## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getSection()](#getSection--) | 获取此 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` 的父节。 |
|
|  | [getHeaderFooter()](#getHeaderFooter--) | 获取此 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` 的父页眉/页脚（如果存在）。 |
|
|  | [getShapeType()](#getShapeType--) | 获取形状类型。 |
|
|  | [isWordArt()](#isWordArt--) | 获取一个值，指示此 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` 是否为 WordArt 对象。 |
|
|  | [getAlternativeText()](#getAlternativeText--) | 获取与此 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` 关联的描述性（替代）文本。 |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | 设置与此 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` 关联的描述性（替代）文本。 |
|
|  | [getName()](#getName--) | 获取此 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` 的名称。 |
|
|  | [getBehindText()](#getBehindText--) | 获取一个值，指示形状是位于文本之上还是之下。 |
|
|  | [setBehindText(boolean value)](#setBehindText-boolean-) | 设置一个值，指示形状是位于文本之上还是之下。 |
|
|  | [getText()](#getText--) | 获取此 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` 的文本。 |
|
|  | [setText(String value)](#setText-java.lang.String-) | 设置此 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` 的文本。 |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | 获取此 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` 的格式化文本片段集合。 |
|
|  | [getImage()](#getImage--) | 获取此 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` 的图像。 |
|
|  | [setImage(WordProcessingWatermarkableImage value)](#setImage-com.groupdocs.watermark.contents.WordProcessingWatermarkableImage-) | 设置此 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` 的图像。 |
|
|  | [getHorizontalAlignment()](#getHorizontalAlignment--) | 获取一个值，指定形状的水平定位方式。 |
|
|  | [getVerticalAlignment()](#getVerticalAlignment--) | 获取一个值，指定形状的垂直定位方式。 |
|
|  | [getRelativeHorizontalPosition()](#getRelativeHorizontalPosition--) | 获取一个值，指定形状水平定位的参照对象。 |
|
|  | [getRelativeVerticalPosition()](#getRelativeVerticalPosition--) | 获取一个值，指定形状在垂直方向上的位置。 |
|
| [getImageFillFormat()](#getImageFillFormat--) |  |
| [getAsposeWordsShape()](#getAsposeWordsShape--) |  |
|  | [getHyperlink()](#getHyperlink--) | 获取与此 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` 关联的超链接。 |
|
|  | [setHyperlink(String value)](#setHyperlink-java.lang.String-) | 设置与此 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` 关联的超链接。 |
|
|  | [getWidth()](#getWidth--) | 获取此 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` 的宽度（单位：点）。 |
|
|  | [setWidth(double value)](#setWidth-double-) | 设置此 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` 的宽度（单位：点）。 |
|
|  | [getHeight()](#getHeight--) | 获取此 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` 的高度（单位：点）。 |
|
|  | [setHeight(double value)](#setHeight-double-) | 设置此 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` 的高度（单位：点）。 |
|
|  | [getRotateAngle()](#getRotateAngle--) | 获取此 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` 的旋转角度（单位：度）。 |
|
|  | [setRotateAngle(double value)](#setRotateAngle-double-) | 设置此 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` 的旋转角度（单位：度）。 |
|
|  | [getX()](#getX--) | 获取或设置此 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` 相对于页面左边界的水平偏移量（单位：点）。 |
|
|  | [setX(double value)](#setX-double-) | 获取或设置此 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` 相对于页面左边界的水平偏移量（单位：点）。 |
|
|  | [getY()](#getY--) | 获取此 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` 相对于页面顶部边界的垂直偏移量（单位：点）。 |
|
|  | [setY(double value)](#setY-double-) | 设置此 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` 相对于页面顶部边界的垂直偏移量（单位：点）。 |
|
| [getFormattedTextFragmentsForSearch()](#getFormattedTextFragmentsForSearch--) |  |
| [getTextForSearch()](#getTextForSearch--) |  |
| [setFoundWatermarkText(String value)](#setFoundWatermarkText-java.lang.String-) |  |
| [getImageForSearch()](#getImageForSearch--) |  |
| [setFoundWatermarkImage(byte[] imageData)](#setFoundWatermarkImage-byte---) |  |
### getSection() {#getSection--}
```
public final WordProcessingSection getSection()
```


获取此 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` 的父节。


**Returns:**
[WordProcessingSection](../../com.groupdocs.watermark.contents/wordprocessingsection) - The parent section of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### getHeaderFooter() {#getHeaderFooter--}
```
public final WordProcessingHeaderFooter getHeaderFooter()
```


获取此 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` 的父页眉/页脚（如果存在）。


**Returns:**
[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter) - The parent header/footer of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### getShapeType() {#getShapeType--}
```
public final int getShapeType()
```


获取形状类型。


**Returns:**
int - 形状类型。

### isWordArt() {#isWordArt--}
```
public final boolean isWordArt()
```


获取一个值，指示此 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` 是否为 WordArt 对象。


**Returns:**
boolean - 若形状是 WordArt 对象则为 true；否则为 false。

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


获取与此 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` 关联的描述性（替代）文本。


**Returns:**
java.lang.String - 与此 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` 关联的描述性（替代）文本。

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


设置与此 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` 关联的描述性（替代）文本。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | java.lang.String | 与此 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` 关联的描述性（替代）文本。 |
|

### getName() {#getName--}
```
public final String getName()
```


获取此 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` 的名称。


**Returns:**
java.lang.String - 此 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` 的名称。

### getBehindText() {#getBehindText--}
```
public final boolean getBehindText()
```


获取一个值，指示形状是位于文本之上还是之下。


**Returns:**
boolean - 指示形状是位于文本之上还是之下的值。如果形状位于文本之后，则为 true；否则为 false。

### setBehindText(boolean value) {#setBehindText-boolean-}
```
public final void setBehindText(boolean value)
```


设置一个值，指示形状是位于文本之上还是之下。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | boolean | 指示形状是位于文本之上还是之下的值。如果形状位于文本之后，则为 true；否则为 false。 |
|

### getText() {#getText--}
```
public final String getText()
```


获取此 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` 的文本。


**Returns:**
java.lang.String - 此 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` 的文本。

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


设置此 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` 的文本。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | java.lang.String | 此 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` 的文本。 |
|

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public final FormattedTextFragmentCollection getFormattedTextFragments()
```


获取此 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` 的格式化文本片段集合。


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### getImage() {#getImage--}
```
public final WordProcessingWatermarkableImage getImage()
```


获取此 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` 的图像。


**Returns:**
[WordProcessingWatermarkableImage](../../com.groupdocs.watermark.contents/wordprocessingwatermarkableimage) - The image of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` or `null` if the shape has no image.

### setImage(WordProcessingWatermarkableImage value) {#setImage-com.groupdocs.watermark.contents.WordProcessingWatermarkableImage-}
```
public final void setImage(WordProcessingWatermarkableImage value)
```


设置此 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` 的图像。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | [WordProcessingWatermarkableImage](../../com.groupdocs.watermark.contents/wordprocessingwatermarkableimage) | 此 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` 的图像，若要删除图像则为 `null`。 |
|

### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public final int getHorizontalAlignment()
```


获取一个值，指定形状的水平定位方式。


**Returns:**
int - 水平对齐值。

### getVerticalAlignment() {#getVerticalAlignment--}
```
public final int getVerticalAlignment()
```


获取一个值，指定形状的垂直定位方式。


**Returns:**
int - 垂直对齐值。

### getRelativeHorizontalPosition() {#getRelativeHorizontalPosition--}
```
public final int getRelativeHorizontalPosition()
```


获取一个值，指定形状水平定位的参照对象。


**Returns:**
int - 相对水平位置值。

### getRelativeVerticalPosition() {#getRelativeVerticalPosition--}
```
public final int getRelativeVerticalPosition()
```


获取一个值，指定形状在垂直方向上的位置。


**Returns:**
int - 相对垂直位置值。

### getImageFillFormat() {#getImageFillFormat--}
```
public final WordProcessingImageFillFormat getImageFillFormat()
```




**Returns:**
[WordProcessingImageFillFormat](../../com.groupdocs.watermark.internal/wordprocessingimagefillformat)
### getAsposeWordsShape() {#getAsposeWordsShape--}
```
public final Shape getAsposeWordsShape()
```




**Returns:**
com.aspose.words.Shape
### getHyperlink() {#getHyperlink--}
```
public final String getHyperlink()
```


获取与此 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` 关联的超链接。


**Returns:**
java.lang.String - 与此 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` 关联的超链接。

### setHyperlink(String value) {#setHyperlink-java.lang.String-}
```
public final void setHyperlink(String value)
```


设置与此 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` 关联的超链接。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | java.lang.String | 与此 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` 关联的超链接。 |
|

### getWidth() {#getWidth--}
```
public final double getWidth()
```


获取此 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` 的宽度（单位：点）。


**Returns:**
double - 此 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` 的宽度（单位：点）。

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


设置此 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` 的宽度（单位：点）。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | double | 此 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` 的宽度（单位：点）。 |
|

### getHeight() {#getHeight--}
```
public final double getHeight()
```


获取此 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` 的高度（单位：点）。


**Returns:**
double - 此 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` 的高度（单位：点）。

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


设置此 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` 的高度（单位：点）。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | double | 此 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` 的高度（单位：点）。 |
|

### getRotateAngle() {#getRotateAngle--}
```
public final double getRotateAngle()
```


获取此 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` 的旋转角度（单位：度）。


**Returns:**
double - 此 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` 的旋转角度（单位：度）。

### setRotateAngle(double value) {#setRotateAngle-double-}
```
public final void setRotateAngle(double value)
```


设置此 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` 的旋转角度（单位：度）。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | double | 此 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` 的旋转角度（单位：度）。 |
|

### getX() {#getX--}
```
public final double getX()
```


获取或设置此 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` 相对于页面左边界的水平偏移量（单位：点）。


**Returns:**
double - 此 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` 的 X 坐标。

### setX(double value) {#setX-double-}
```
public final void setX(double value)
```


获取或设置此 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` 相对于页面左边界的水平偏移量（单位：点）。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | double | 此 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` 的 X 坐标。 |
|

### getY() {#getY--}
```
public final double getY()
```


获取此 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` 相对于页面顶部边界的垂直偏移量（单位：点）。


**Returns:**
double - 此 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` 的 Y 坐标。

### setY(double value) {#setY-double-}
```
public final void setY(double value)
```


设置此 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` 相对于页面顶部边界的垂直偏移量（单位：点）。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | double | 此 `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` 的 Y 坐标。 |
|

### getFormattedTextFragmentsForSearch() {#getFormattedTextFragmentsForSearch--}
```
public FormattedTextFragmentCollection getFormattedTextFragmentsForSearch()
```




**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection)
### getTextForSearch() {#getTextForSearch--}
```
public String getTextForSearch()
```




**Returns:**
java.lang.String
### setFoundWatermarkText(String value) {#setFoundWatermarkText-java.lang.String-}
```
public void setFoundWatermarkText(String value)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getImageForSearch() {#getImageForSearch--}
```
public WatermarkableImage getImageForSearch()
```




**Returns:**
[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)
### setFoundWatermarkImage(byte[] imageData) {#setFoundWatermarkImage-byte---}
```
public void setFoundWatermarkImage(byte[] imageData)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| imageData | byte[] |  |

