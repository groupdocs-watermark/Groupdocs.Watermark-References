---
title: "WordProcessingShapeSettings"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "Word 문서의 도형 워터마크에 적용할 수 있는 설정을 나타냅니다."
type: docs
weight: 71
url: /ko/java/com.groupdocs.watermark.options/wordprocessingshapesettings/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.OfficeShapeSettings](../../com.groupdocs.watermark.contents/officeshapesettings)
```
public final class WordProcessingShapeSettings extends OfficeShapeSettings
```

Word 문서의 도형 워터마크에 적용할 수 있는 설정을 나타냅니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [WordProcessingShapeSettings()](#WordProcessingShapeSettings--) | `[WordProcessingShapeSettings](../../com.groupdocs.watermark.options/wordprocessingshapesettings)` 클래스의 새 인스턴스를 초기화합니다. |
|
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
|  | [getPageNumbers()](#getPageNumbers--) | 워터마크를 추가할 페이지 번호를 가져옵니다. |
|
|  | [setPageNumbers(int[] value)](#setPageNumbers-int---) | 워터마크를 추가할 페이지 번호를 설정합니다. |
|
### WordProcessingShapeSettings() {#WordProcessingShapeSettings--}
```
public WordProcessingShapeSettings()
```


`[WordProcessingShapeSettings](../../com.groupdocs.watermark.options/wordprocessingshapesettings)` 클래스의 새 인스턴스를 초기화합니다.


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
int - `[WordProcessingLockType](../../com.groupdocs.watermark.options/wordprocessinglocktype)`의 워터마크 잠금 유형.

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
|  | value | int | `[WordProcessingLockType](../../com.groupdocs.watermark.options/wordprocessinglocktype)`의 워터마크 잠금 유형. |
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

### getPageNumbers() {#getPageNumbers--}
```
public final int[] getPageNumbers()
```


워터마크를 추가할 페이지 번호를 가져옵니다.


**Returns:**
int[] - 워터마크를 추가할 페이지 번호.

<br />

*** ** * ** ***

모든 숫자는 1보다 크거나 같아야 합니다. 이 속성은 워터마크를 문서에 추가할 때만 사용됩니다. 값이 null이면 워터마크가 모든 페이지에 추가됩니다.

<br />


### setPageNumbers(int[] value) {#setPageNumbers-int---}
```
public final void setPageNumbers(int[] value)
```


워터마크를 추가할 페이지 번호를 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | int[] | 워터마크를 추가할 페이지 번호. |

<br />

*** ** * ** ***

모든 숫자는 1보다 크거나 같아야 합니다. 이 속성은 워터마크를 문서에 추가할 때만 사용됩니다. 값이 null이면 워터마크가 모든 페이지에 추가됩니다.

<br />

|

