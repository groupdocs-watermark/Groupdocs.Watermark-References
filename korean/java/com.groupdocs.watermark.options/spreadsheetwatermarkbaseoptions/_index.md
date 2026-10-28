---
title: "SpreadsheetWatermarkBaseOptions"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "스프레드시트 문서에 워터마크 추가 옵션을 위한 기본 클래스입니다."
type: docs
weight: 56
url: /ko/java/com.groupdocs.watermark.options/spreadsheetwatermarkbaseoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.SpreadsheetWatermarkOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkoptions)
```
public abstract class SpreadsheetWatermarkBaseOptions extends SpreadsheetWatermarkOptions
```

스프레드시트 문서에 워터마크 추가 옵션을 위한 기본 클래스입니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [isLocked()](#isLocked--) | Excel에서 도형 편집이 금지되는지 여부를 나타내는 값을 가져옵니다. |
|
|  | [setLocked(boolean value)](#setLocked-boolean-) | Excel에서 도형 편집이 금지되는지 여부를 나타내는 값을 설정합니다. |
|
|  | [getName()](#getName--) | 도형의 이름을 가져옵니다. |
|
|  | [setName(String value)](#setName-java.lang.String-) | 도형의 이름을 설정합니다. |
|
|  | [getAlternativeText()](#getAlternativeText--) | 도형에 연결될 설명(대체) 텍스트를 가져옵니다. |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | 도형에 연결될 설명(대체) 텍스트를 설정합니다. |
|
### isLocked() {#isLocked--}
```
public final boolean isLocked()
```


Excel에서 도형 편집이 금지되는지 여부를 나타내는 값을 가져옵니다.


**Returns:**
boolean - 값이 true이면 도형 편집이 금지됩니다. 기본값은 false이며, 도형은 Excel에서 편집할 수 있습니다.

### setLocked(boolean value) {#setLocked-boolean-}
```
public final void setLocked(boolean value)
```


Excel에서 도형 편집이 금지되는지 여부를 나타내는 값을 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | boolean | 값이 true이면 도형 편집이 금지됩니다. 기본값은 false이며, 도형은 Excel에서 편집할 수 있습니다. |
|

### getName() {#getName--}
```
public final String getName()
```


도형의 이름을 가져옵니다.


**Returns:**
java.lang.String - 도형 이름입니다.

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


도형의 이름을 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | java.lang.String | 도형 이름. |
|

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


도형에 연결될 설명(대체) 텍스트를 가져옵니다.


**Returns:**
java.lang.String - 도형에 연결될 설명(대체) 텍스트입니다.

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


도형에 연결될 설명(대체) 텍스트를 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | java.lang.String | 도형에 연결될 설명(대체) 텍스트입니다. |
|

