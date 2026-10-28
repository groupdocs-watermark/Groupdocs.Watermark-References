---
title: "FormattedTextFragment"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "콘텐츠 내 서식 있는 텍스트 조각에 대한 추상 기본 클래스를 제공합니다."
type: docs
weight: 26
url: /ko/java/com.groupdocs.watermark.search/formattedtextfragment/
---
**Inheritance:**
java.lang.Object
```
public abstract class FormattedTextFragment
```

콘텐츠 내 서식 있는 텍스트 조각에 대한 추상 기본 클래스를 제공합니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [FormattedTextFragment()](#FormattedTextFragment--) |  |
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
### FormattedTextFragment() {#FormattedTextFragment--}
```
public FormattedTextFragment()
```




### getText() {#getText--}
```
public abstract String getText()
```


조각 텍스트를 가져옵니다.


**Returns:**
java.lang.String - 조각 텍스트.

### getFont() {#getFont--}
```
public abstract Font getFont()
```


텍스트의 글꼴을 가져옵니다.


**Returns:**
[Font](../../com.groupdocs.watermark.watermarks/font) - The font of the text.

### getForegroundColor() {#getForegroundColor--}
```
public abstract Color getForegroundColor()
```


텍스트의 전경색을 가져옵니다.


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The foreground color of the text.

### getBackgroundColor() {#getBackgroundColor--}
```
public abstract Color getBackgroundColor()
```


텍스트의 배경색을 가져옵니다.


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The background color of the text.

