---
title: "TextWatermark"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "텍스트 워터마크를 나타냅니다."
type: docs
weight: 18
url: /ko/java/com.groupdocs.watermark.watermarks/textwatermark/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.Watermark](../../com.groupdocs.watermark/watermark)
```
public class TextWatermark extends Watermark
```

텍스트 워터마크를 나타냅니다.

**Learn more:**

* [Adding text watermarks](../https://docs.groupdocs.com/display/watermarkjava/Adding+text+watermarks)

다음 예제는 부모 크기에 따라 텍스트 워터마크를 확대/축소하는 방법을 보여줍니다.
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


## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [TextWatermark(String text, Font font)](#TextWatermark-java.lang.String-com.groupdocs.watermark.watermarks.Font-) | 지정된 텍스트와 폰트를 사용하여 새 인스턴스를 초기화합니다 `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)` 클래스. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getText()](#getText--) | 워터마크에 사용할 텍스트를 가져옵니다. |
|
|  | [setText(String value)](#setText-java.lang.String-) | 워터마크에 사용할 텍스트를 설정합니다. |
|
|  | [getFont()](#getFont--) | 텍스트의 글꼴을 가져옵니다. |
|
|  | [setFont(Font value)](#setFont-com.groupdocs.watermark.watermarks.Font-) | 텍스트의 글꼴을 설정합니다. |
|
|  | [getForegroundColor()](#getForegroundColor--) | 텍스트의 전경색을 가져옵니다. |
|
|  | [setForegroundColor(Color value)](#setForegroundColor-com.groupdocs.watermark.watermarks.Color-) | 텍스트의 전경색을 설정합니다. |
|
|  | [getBackgroundColor()](#getBackgroundColor--) | 텍스트의 배경색을 가져옵니다. |
|
|  | [setBackgroundColor(Color value)](#setBackgroundColor-com.groupdocs.watermark.watermarks.Color-) | 텍스트의 배경색을 설정합니다. |
|
|  | [getTextAlignment()](#getTextAlignment--) | 워터마크 `[TextAlignment](../../com.groupdocs.watermark.watermarks/textalignment)`을(를) 가져옵니다. |
|
|  | [setTextAlignment(int value)](#setTextAlignment-int-) | 워터마크 `[TextAlignment](../../com.groupdocs.watermark.watermarks/textalignment)`을(를) 설정합니다. |
|
| [isImageWatermark()](#isImageWatermark--) |  |
| [isTextWatermark()](#isTextWatermark--) |  |
| [getForegroundColorConsideringOpacity()](#getForegroundColorConsideringOpacity--) |  |
| [getBackgroundColorConsideringOpacity()](#getBackgroundColorConsideringOpacity--) |  |
| [getSize()](#getSize--) |  |
|  | [getPadding()](#getPadding--) | 이 `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)`의 패딩 설정을 가져옵니다. |
|
|  | [setPadding(Thickness value)](#setPadding-com.groupdocs.watermark.Thickness-) | 이 `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)`의 패딩 설정을 설정합니다. |
|
| [deepClone()](#deepClone--) |  |
| [hasSameValues(Watermark watermark)](#hasSameValues-com.groupdocs.watermark.Watermark-) |  |
| [createGeometry(ContentPartGeometry parent)](#createGeometry-com.groupdocs.watermark.internal.ContentPartGeometry-) |  |
### TextWatermark(String text, Font font) {#TextWatermark-java.lang.String-com.groupdocs.watermark.watermarks.Font-}
```
public TextWatermark(String text, Font font)
```


지정된 텍스트와 폰트를 사용하여 새 인스턴스를 초기화합니다 `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)` 클래스.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 텍스트 | java.lang.String | 워터마크에 사용할 텍스트입니다. |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | 텍스트의 글꼴입니다. |
|

### getText() {#getText--}
```
public final String getText()
```


워터마크에 사용할 텍스트를 가져옵니다.


**Returns:**
java.lang.String - 워터마크 텍스트를 나타내는 문자열입니다.

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


워터마크에 사용할 텍스트를 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | java.lang.String | 워터마크 텍스트를 나타내는 문자열입니다. |
|

### getFont() {#getFont--}
```
public final Font getFont()
```


텍스트의 글꼴을 가져옵니다.


**Returns:**
[Font](../../com.groupdocs.watermark.watermarks/font) - The font of the text.

### setFont(Font value) {#setFont-com.groupdocs.watermark.watermarks.Font-}
```
public final void setFont(Font value)
```


텍스트의 글꼴을 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | value | [Font](../../com.groupdocs.watermark.watermarks/font) | 텍스트의 글꼴입니다. |
|

### getForegroundColor() {#getForegroundColor--}
```
public final Color getForegroundColor()
```


텍스트의 전경색을 가져옵니다.


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The foreground color of the text.

### setForegroundColor(Color value) {#setForegroundColor-com.groupdocs.watermark.watermarks.Color-}
```
public final void setForegroundColor(Color value)
```


텍스트의 전경색을 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | value | [Color](../../com.groupdocs.watermark.watermarks/color) | 텍스트의 전경색입니다. |
|

### getBackgroundColor() {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```


텍스트의 배경색을 가져옵니다.


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The background color of the text.

### setBackgroundColor(Color value) {#setBackgroundColor-com.groupdocs.watermark.watermarks.Color-}
```
public final void setBackgroundColor(Color value)
```


텍스트의 배경색을 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | value | [Color](../../com.groupdocs.watermark.watermarks/color) | 텍스트의 배경색입니다. |
|

### getTextAlignment() {#getTextAlignment--}
```
public final int getTextAlignment()
```


워터마크 `[TextAlignment](../../com.groupdocs.watermark.watermarks/textalignment)`을(를) 가져옵니다.

기본값은 `[TextAlignment.Left](../../com.groupdocs.watermark.watermarks/textalignment#Left)`입니다.


**Returns:**
int - 워터마크 `[TextAlignment](../../com.groupdocs.watermark.watermarks/textalignment)`입니다.

### setTextAlignment(int value) {#setTextAlignment-int-}
```
public final void setTextAlignment(int value)
```


워터마크 `[TextAlignment](../../com.groupdocs.watermark.watermarks/textalignment)`을(를) 설정합니다.

기본값은 `[TextAlignment.Left](../../com.groupdocs.watermark.watermarks/textalignment#Left)`입니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | value | int | 워터마크 `[TextAlignment](../../com.groupdocs.watermark.watermarks/textalignment)`입니다. |
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


이 `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)`의 패딩 설정을 가져옵니다. 이 속성은 이미지 파일에만 적용됩니다.


**Returns:**
[Thickness](../../com.groupdocs.watermark/thickness) - The padding settings of this `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)`.

### setPadding(Thickness value) {#setPadding-com.groupdocs.watermark.Thickness-}
```
public final void setPadding(Thickness value)
```


이 `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)`의 패딩 설정을 설정합니다. 이 속성은 이미지 파일에만 적용됩니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | value | [Thickness](../../com.groupdocs.watermark/thickness) | 이 `[TextWatermark](../../com.groupdocs.watermark.watermarks/textwatermark)`의 패딩 설정입니다. |
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
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |

**Returns:**
boolean
### createGeometry(ContentPartGeometry parent) {#createGeometry-com.groupdocs.watermark.internal.ContentPartGeometry-}
```
public WatermarkGeometry createGeometry(ContentPartGeometry parent)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| parent | [ContentPartGeometry](../../com.groupdocs.watermark.internal/contentpartgeometry) |  |

**Returns:**
[WatermarkGeometry](../../com.groupdocs.watermark.internal/watermarkgeometry)
