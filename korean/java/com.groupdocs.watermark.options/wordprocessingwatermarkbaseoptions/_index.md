---
title: "WordProcessingWatermarkBaseOptions"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "Word 문서에 워터마크 추가 옵션을 위한 기본 클래스입니다."
type: docs
weight: 73
url: /ko/java/com.groupdocs.watermark.options/wordprocessingwatermarkbaseoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkoptions)
```
public abstract class WordProcessingWatermarkBaseOptions extends WordProcessingWatermarkOptions
```

Word 문서에 워터마크 추가 옵션을 위한 기본 클래스입니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [isLocked()](#isLocked--) | Word에서 도형 편집이 금지되는지 여부를 나타내는 값을 가져옵니다. |
|
|  | [setLocked(boolean value)](#setLocked-boolean-) | Word에서 도형 편집이 금지되는지 여부를 나타내는 값을 설정합니다. |
|
|  | [getLockType()](#getLockType--) | 워터마크 잠금 유형을 가져옵니다. |
|
|  | [setLockType(int value)](#setLockType-int-) | 워터마크 잠금 유형을 설정합니다. |
|
|  | [getPassword()](#getPassword--) | 워터마크를 잠그는 데 사용되는 비밀번호를 가져옵니다. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | 워터마크를 잠그는 데 사용되는 비밀번호를 설정합니다. |
|
|  | [getName()](#getName--) | 도형의 이름을 가져옵니다. |
|
|  | [setName(String value)](#setName-java.lang.String-) | 도형의 이름을 설정합니다. |
|
|  | [getAlternativeText()](#getAlternativeText--) | 도형에 연결될 설명(대체) 텍스트를 가져옵니다. |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | 도형에 연결될 설명(대체) 텍스트를 설정합니다. |
|
| [getEffects()](#getEffects--) |  |
| [setEffects(IWordProcessingWatermarkEffects value)](#setEffects-com.groupdocs.watermark.options.IWordProcessingWatermarkEffects-) |  |
### isLocked() {#isLocked--}
```
public final boolean isLocked()
```


Word에서 도형 편집이 금지되는지 여부를 나타내는 값을 가져옵니다.


**Returns:**
boolean - 값이 true이면 도형 편집이 금지됩니다. 기본값은 false이며, 도형은 Word에서 편집할 수 있습니다.

### setLocked(boolean value) {#setLocked-boolean-}
```
public final void setLocked(boolean value)
```


Word에서 도형 편집이 금지되는지 여부를 나타내는 값을 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | boolean | 값이 true이면 도형 편집이 금지됩니다. 기본값은 false이며, Word에서 도형을 편집할 수 있습니다. |
|

### getLockType() {#getLockType--}
```
public final int getLockType()
```


워터마크 잠금 유형을 가져옵니다.


**Returns:**
int - 워터마크 `[WordProcessingLockType](../../com.groupdocs.watermark.options/wordprocessinglocktype)` 잠금 유형.

### setLockType(int value) {#setLockType-int-}
```
public final void setLockType(int value)
```


워터마크 잠금 유형을 설정합니다.

`[WordProcessingLockType.AllowOnlyFormFields](../../com.groupdocs.watermark.options/wordprocessinglocktype#AllowOnlyFormFields)` 값은 다음과 함께 사용할 수 없습니다.
`[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter)` 유형의 객체.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | value | int | 워터마크 `[WordProcessingLockType](../../com.groupdocs.watermark.options/wordprocessinglocktype)` 잠금 유형. |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


워터마크를 잠그는 데 사용되는 비밀번호를 가져옵니다.


**Returns:**
java.lang.String - 워터마크를 잠그는 데 사용되는 비밀번호.

### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


워터마크를 잠그는 데 사용되는 비밀번호를 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | java.lang.String | 워터마크를 잠그는 데 사용되는 비밀번호. |
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

### getEffects() {#getEffects--}
```
public final IWordProcessingWatermarkEffects getEffects()
```




**Returns:**
[IWordProcessingWatermarkEffects](../../com.groupdocs.watermark.options/iwordprocessingwatermarkeffects)
### setEffects(IWordProcessingWatermarkEffects value) {#setEffects-com.groupdocs.watermark.options.IWordProcessingWatermarkEffects-}
```
public final void setEffects(IWordProcessingWatermarkEffects value)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IWordProcessingWatermarkEffects](../../com.groupdocs.watermark.options/iwordprocessingwatermarkeffects) |  |

