---
title: "Font"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "글꼴을 나타내는 클래스입니다."
type: docs
weight: 11
url: /ko/java/com.groupdocs.watermark.watermarks/font/
---
**Inheritance:**
java.lang.Object
```
public final class Font
```

글꼴을 나타내는 클래스입니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [Font(String fontFamilyName, float size)](#Font-java.lang.String-float-) | 지정된 글꼴 패밀리 이름과 크기를 사용하여 `[Font](../../com.groupdocs.watermark.watermarks/font)` 클래스의 새 인스턴스를 초기화합니다. |
|
|  | [Font(String fontFamilyName, float size, int style)](#Font-java.lang.String-float-int-) | 지정된 글꼴 패밀리 이름, 크기 및 스타일을 사용하여 `[Font](../../com.groupdocs.watermark.watermarks/font)` 클래스의 새 인스턴스를 초기화합니다. |
|
| [Font(String fontFamilyName, String folderPath, float size)](#Font-java.lang.String-java.lang.String-float-) |  |
| [Font(String fontFamilyName, String folderPath, float size, FontStyle style)](#Font-java.lang.String-java.lang.String-float-com.groupdocs.watermark.watermarks.FontStyle-) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getFolderPath()](#getFolderPath--) |  |
| [setFolderPath(String folderPath)](#setFolderPath-java.lang.String-) |  |
|  | [getFamilyName()](#getFamilyName--) | 이 `[Font](../../com.groupdocs.watermark.watermarks/font)` 의 패밀리 이름을 가져옵니다. |
|
|  | [getSize()](#getSize--) | 이 `[Font](../../com.groupdocs.watermark.watermarks/font)` 의 크기를 가져옵니다. |
|
|  | [getStyle()](#getStyle--) | 이 `[Font](../../com.groupdocs.watermark.watermarks/font)` 에 대한 `[FontStyle](../../com.groupdocs.watermark.watermarks/fontstyle)` 를 가져옵니다. |
|
|  | [getBold()](#getBold--) | 글꼴이 굵게 표시되는지 여부를 나타내는 값을 가져옵니다. |
|
|  | [getItalic()](#getItalic--) | 글꼴이 이탤릭인지 여부를 나타내는 값을 가져옵니다. |
|
|  | [getStrikeout()](#getStrikeout--) | 글꼴에 가로줄이 지정되어 있는지 여부를 나타내는 값을 가져옵니다. |
|
|  | [getUnderline()](#getUnderline--) | 글꼴에 밑줄이 있는지 여부를 나타내는 값을 가져옵니다. |
|
### Font(String fontFamilyName, float size) {#Font-java.lang.String-float-}
```
public Font(String fontFamilyName, float size)
```


지정된 글꼴 패밀리 이름과 크기를 사용하여 `[Font](../../com.groupdocs.watermark.watermarks/font)` 클래스의 새 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | fontFamilyName | java.lang.String | 글꼴 패밀리 이름입니다. |
|
|  | size | float | 새 글꼴의 크기입니다. |
|

### Font(String fontFamilyName, float size, int style) {#Font-java.lang.String-float-int-}
```
public Font(String fontFamilyName, float size, int style)
```


지정된 글꼴 패밀리 이름, 크기 및 스타일을 사용하여 `[Font](../../com.groupdocs.watermark.watermarks/font)` 클래스의 새 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | fontFamilyName | java.lang.String | 글꼴 패밀리 이름입니다. |
|
|  | size | float | 새 글꼴의 크기입니다. |
|
|  | style | int | 새 글꼴의 `[FontStyle](../../com.groupdocs.watermark.watermarks/fontstyle)`입니다. |
|

### Font(String fontFamilyName, String folderPath, float size) {#Font-java.lang.String-java.lang.String-float-}
```
public Font(String fontFamilyName, String folderPath, float size)
```


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fontFamilyName | java.lang.String |  |
| folderPath | java.lang.String |  |
| size | float |  |

### Font(String fontFamilyName, String folderPath, float size, FontStyle style) {#Font-java.lang.String-java.lang.String-float-com.groupdocs.watermark.watermarks.FontStyle-}
```
public Font(String fontFamilyName, String folderPath, float size, FontStyle style)
```


**Parameters:**
| 매개변수 | 유형 | 설명 |
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
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| folderPath | java.lang.String |  |

### getFamilyName() {#getFamilyName--}
```
public final String getFamilyName()
```


이 `[Font](../../com.groupdocs.watermark.watermarks/font)` 의 패밀리 이름을 가져옵니다.


**Returns:**
java.lang.String - 이 `[Font](../../com.groupdocs.watermark.watermarks/font)`의 패밀리 이름입니다.

### getSize() {#getSize--}
```
public final float getSize()
```


이 `[Font](../../com.groupdocs.watermark.watermarks/font)` 의 크기를 가져옵니다.


**Returns:**
float - 이 `[Font](../../com.groupdocs.watermark.watermarks/font)`의 크기입니다.

### getStyle() {#getStyle--}
```
public final int getStyle()
```


이 `[Font](../../com.groupdocs.watermark.watermarks/font)` 에 대한 `[FontStyle](../../com.groupdocs.watermark.watermarks/fontstyle)` 를 가져옵니다.

기본값은 `[FontStyle.Regular](../../com.groupdocs.watermark.watermarks/fontstyle#Regular)`(일반 텍스트)입니다.


**Returns:**
int - 이 `[Font](../../com.groupdocs.watermark.watermarks/font)`의 `[FontStyle](../../com.groupdocs.watermark.watermarks/fontstyle)`입니다.

### getBold() {#getBold--}
```
public final boolean getBold()
```


글꼴이 굵게 표시되는지 여부를 나타내는 값을 가져옵니다.


**Returns:**
boolean - 이 글꼴이 굵게 표시되면 true; 그렇지 않으면 false.

### getItalic() {#getItalic--}
```
public final boolean getItalic()
```


글꼴이 이탤릭인지 여부를 나타내는 값을 가져옵니다.


**Returns:**
boolean - 이 글꼴이 이탤릭이면 true; 그렇지 않으면 false.

### getStrikeout() {#getStrikeout--}
```
public final boolean getStrikeout()
```


글꼴에 가로줄이 지정되어 있는지 여부를 나타내는 값을 가져옵니다.


**Returns:**
boolean - 이 글꼴에 가로줄이 지정되어 있으면 true; 그렇지 않으면 false.

### getUnderline() {#getUnderline--}
```
public final boolean getUnderline()
```


글꼴에 밑줄이 있는지 여부를 나타내는 값을 가져옵니다.


**Returns:**
boolean - 이 글꼴에 밑줄이 있으면 true; 그렇지 않으면 false.

