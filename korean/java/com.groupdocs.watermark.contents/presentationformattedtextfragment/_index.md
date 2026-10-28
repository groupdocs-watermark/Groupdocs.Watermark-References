---
title: "PresentationFormattedTextFragment"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "PowerPoint 문서에서 서식이 지정된 텍스트 조각을 나타냅니다."
type: docs
weight: 82
url: /ko/java/com.groupdocs.watermark.contents/presentationformattedtextfragment/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.FormattedTextFragment](../../com.groupdocs.watermark.search/formattedtextfragment)

**All Implemented Interfaces:**
[com.groupdocs.watermark.contents.IPresentationHyperlinkContainer](../../com.groupdocs.watermark.contents/ipresentationhyperlinkcontainer)
```
public class PresentationFormattedTextFragment extends FormattedTextFragment implements IPresentationHyperlinkContainer
```

PowerPoint 문서에서 서식이 지정된 텍스트 조각을 나타냅니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getText()](#getText--) | 조각 텍스트를 가져옵니다. |
|
|  | [getFont()](#getFont--) | 텍스트의 글꼴을 가져옵니다. |
|
|  | [getForegroundColor()](#getForegroundColor--) | 텍스트의 전경색을 가져옵니다. |
|
|  | [getBackgroundColor()](#getBackgroundColor--) | 텍스트의 배경색을 가져옵니다. |
|
|  | [getHyperlink(int actionType)](#getHyperlink-int-) | 텍스트와 연결된 하이퍼링크를 가져옵니다. |
|
|  | [setHyperlink(int actionType, String url)](#setHyperlink-int-java.lang.String-) | 텍스트와 연결된 하이퍼링크를 설정합니다. |
|
### getText() {#getText--}
```
public String getText()
```


조각 텍스트를 가져옵니다.


**Returns:**
java.lang.String - 조각 텍스트.

### getFont() {#getFont--}
```
public Font getFont()
```


텍스트의 글꼴을 가져옵니다.


**Returns:**
[Font](../../com.groupdocs.watermark.watermarks/font) - The font of the text.

### getForegroundColor() {#getForegroundColor--}
```
public Color getForegroundColor()
```


텍스트의 전경색을 가져옵니다.


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The foreground color of the text.

### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


텍스트의 배경색을 가져옵니다.


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The background color of the text.

### getHyperlink(int actionType) {#getHyperlink-int-}
```
public final String getHyperlink(int actionType)
```


텍스트와 연결된 하이퍼링크를 가져옵니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | actionType | int | 하이퍼링크를 활성화하는 동작. |
|

**Returns:**
java.lang.String - 지정된 동작에서 활성화되는 하이퍼링크의 URL.

### setHyperlink(int actionType, String url) {#setHyperlink-int-java.lang.String-}
```
public final void setHyperlink(int actionType, String url)
```


텍스트와 연결된 하이퍼링크를 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | actionType | int | 하이퍼링크를 활성화하는 동작. |
|
|  | url | java.lang.String | 하이퍼링크 URL. |
|

