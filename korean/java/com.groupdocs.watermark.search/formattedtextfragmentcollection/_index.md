---
title: "FormattedTextFragmentCollection"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "서식 있는 텍스트 조각들의 가변 컬렉션을 나타냅니다."
type: docs
weight: 27
url: /ko/java/com.groupdocs.watermark.search/formattedtextfragmentcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase
```
public class FormattedTextFragmentCollection extends RemoveOnlyListBase<FormattedTextFragment>
```

서식 있는 텍스트 조각들의 가변 컬렉션을 나타냅니다.

이 컬렉션은 `[FormattedTextFragment](../../com.groupdocs.watermark.search/formattedtextfragment)` 기본 유형의 항목을 포함합니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [FormattedTextFragmentCollection(int collectionType)](#FormattedTextFragmentCollection-int-) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getCollectionType()](#getCollectionType--) | 포맷된 조각 컬렉션 유형을 가져옵니다. |
|
| [getDefaultFont()](#getDefaultFont--) |  |
| [getDefaultForegroundColor()](#getDefaultForegroundColor--) |  |
| [getDefaultBackgroundColor()](#getDefaultBackgroundColor--) |  |
| [getText()](#getText--) |  |
|  | [add(String text)](#add-java.lang.String-) | 포맷된 텍스트 조각을 컬렉션에 추가합니다. |
|
|  | [add(String text, Font font)](#add-java.lang.String-com.groupdocs.watermark.watermarks.Font-) | 포맷된 텍스트 조각을 컬렉션에 추가합니다. |
|
|  | [add(String text, Font font, Color foregroundColor)](#add-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-) | 포맷된 텍스트 조각을 컬렉션에 추가합니다. |
|
|  | [add(String text, Font font, Color foregroundColor, Color backgroundColor)](#add-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-) | 포맷된 텍스트 조각을 컬렉션에 추가합니다. |
|
|  | [insert(int index, String text)](#insert-int-java.lang.String-) | 지정된 인덱스에 포맷된 텍스트 조각을 컬렉션에 삽입합니다. |
|
|  | [insert(int index, String text, Font font)](#insert-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-) | 지정된 인덱스에 포맷된 텍스트 조각을 컬렉션에 삽입합니다. |
|
|  | [insert(int index, String text, Font font, Color foregroundColor)](#insert-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-) | 지정된 인덱스에 포맷된 텍스트 조각을 컬렉션에 삽입합니다. |
|
|  | [insert(int index, String text, Font font, Color foregroundColor, Color backgroundColor)](#insert-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-) | 지정된 인덱스에 포맷된 텍스트 조각을 컬렉션에 삽입합니다. |
|
| [createInDocument(int index, String text, Font font, Color foregroundColor, Color backgroundColor)](#createInDocument-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-) |  |
| [setText(String text)](#setText-java.lang.String-) |  |
### FormattedTextFragmentCollection(int collectionType) {#FormattedTextFragmentCollection-int-}
```
public FormattedTextFragmentCollection(int collectionType)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| collectionType | int |  |

### getCollectionType() {#getCollectionType--}
```
public final int getCollectionType()
```


포맷된 조각 컬렉션 유형을 가져옵니다.


**Returns:**
int - 포맷된 조각 컬렉션 유형.

### getDefaultFont() {#getDefaultFont--}
```
public final Font getDefaultFont()
```




**Returns:**
[Font](../../com.groupdocs.watermark.watermarks/font)
### getDefaultForegroundColor() {#getDefaultForegroundColor--}
```
public final Color getDefaultForegroundColor()
```




**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color)
### getDefaultBackgroundColor() {#getDefaultBackgroundColor--}
```
public final Color getDefaultBackgroundColor()
```




**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color)
### getText() {#getText--}
```
public String getText()
```




**Returns:**
java.lang.String
### add(String text) {#add-java.lang.String-}
```
public final void add(String text)
```


포맷된 텍스트 조각을 컬렉션에 추가합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 텍스트 | java.lang.String | 조각 텍스트. |
|

### add(String text, Font font) {#add-java.lang.String-com.groupdocs.watermark.watermarks.Font-}
```
public final void add(String text, Font font)
```


포맷된 텍스트 조각을 컬렉션에 추가합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 텍스트 | java.lang.String | 조각 텍스트. |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | 텍스트의 글꼴입니다. |
|

### add(String text, Font font, Color foregroundColor) {#add-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-}
```
public final void add(String text, Font font, Color foregroundColor)
```


포맷된 텍스트 조각을 컬렉션에 추가합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 텍스트 | java.lang.String | 조각 텍스트. |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | 텍스트의 글꼴입니다. |
|
|  | foregroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) | 텍스트의 전경색입니다. |
|

### add(String text, Font font, Color foregroundColor, Color backgroundColor) {#add-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-}
```
public final void add(String text, Font font, Color foregroundColor, Color backgroundColor)
```


포맷된 텍스트 조각을 컬렉션에 추가합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 텍스트 | java.lang.String | 조각 텍스트. |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | 텍스트의 글꼴입니다. |
|
|  | foregroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) | 텍스트의 전경색입니다. |
|
|  | backgroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) | 텍스트의 배경색입니다. |
|

### insert(int index, String text) {#insert-int-java.lang.String-}
```
public final void insert(int index, String text)
```


지정된 인덱스에 포맷된 텍스트 조각을 컬렉션에 삽입합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 인덱스 | int | 포맷된 텍스트 조각을 삽입해야 하는 0부터 시작하는 인덱스. |
|
|  | 텍스트 | java.lang.String | 조각 텍스트. |
|

### insert(int index, String text, Font font) {#insert-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-}
```
public final void insert(int index, String text, Font font)
```


지정된 인덱스에 포맷된 텍스트 조각을 컬렉션에 삽입합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 인덱스 | int | 포맷된 텍스트 조각을 삽입해야 하는 0부터 시작하는 인덱스. |
|
|  | 텍스트 | java.lang.String | 조각 텍스트. |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | 텍스트의 글꼴입니다. |
|

### insert(int index, String text, Font font, Color foregroundColor) {#insert-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-}
```
public final void insert(int index, String text, Font font, Color foregroundColor)
```


지정된 인덱스에 포맷된 텍스트 조각을 컬렉션에 삽입합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 인덱스 | int | 포맷된 텍스트 조각을 삽입해야 하는 0부터 시작하는 인덱스. |
|
|  | 텍스트 | java.lang.String | 조각 텍스트. |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | 텍스트의 글꼴입니다. |
|
|  | foregroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) | 텍스트의 전경색입니다. |
|

### insert(int index, String text, Font font, Color foregroundColor, Color backgroundColor) {#insert-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-}
```
public final void insert(int index, String text, Font font, Color foregroundColor, Color backgroundColor)
```


지정된 인덱스에 포맷된 텍스트 조각을 컬렉션에 삽입합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 인덱스 | int | 포맷된 텍스트 조각을 삽입해야 하는 0부터 시작하는 인덱스. |
|
|  | 텍스트 | java.lang.String | 조각 텍스트. |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | 텍스트의 글꼴입니다. |
|
|  | foregroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) | 텍스트의 전경색입니다. |
|
|  | backgroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) | 텍스트의 배경색입니다. |
|

### createInDocument(int index, String text, Font font, Color foregroundColor, Color backgroundColor) {#createInDocument-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-}
```
public FormattedTextFragment createInDocument(int index, String text, Font font, Color foregroundColor, Color backgroundColor)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 인덱스 | int |  |
| 텍스트 | java.lang.String |  |
| font | [Font](../../com.groupdocs.watermark.watermarks/font) |  |
| foregroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) |  |
| backgroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) |  |

**Returns:**
[FormattedTextFragment](../../com.groupdocs.watermark.search/formattedtextfragment)
### setText(String text) {#setText-java.lang.String-}
```
public void setText(String text)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 텍스트 | java.lang.String |  |

