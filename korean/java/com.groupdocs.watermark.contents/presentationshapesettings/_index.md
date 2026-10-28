---
title: "PresentationShapeSettings"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "PowerPoint 문서의 도형 워터마크에 적용할 수 있는 설정을 나타냅니다."
type: docs
weight: 95
url: /ko/java/com.groupdocs.watermark.contents/presentationshapesettings/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.OfficeShapeSettings](../../com.groupdocs.watermark.contents/officeshapesettings)
```
public final class PresentationShapeSettings extends OfficeShapeSettings
```

PowerPoint 문서의 도형 워터마크에 적용할 수 있는 설정을 나타냅니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [PresentationShapeSettings()](#PresentationShapeSettings--) | `[PresentationShapeSettings](../../com.groupdocs.watermark.contents/presentationshapesettings)` 클래스의 새 인스턴스를 초기화합니다. |
|
## 필드

| 필드 | 설명 |
| --- | --- |
|  | [UnreadableCharacter](#UnreadableCharacter) | <br /> |

|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [isLocked()](#isLocked--) | PowerPoint에서 도형 편집이 금지되어 있는지 여부를 나타내는 값을 가져옵니다. |
|
|  | [setLocked(boolean value)](#setLocked-boolean-) | PowerPoint에서 도형 편집이 금지되어 있는지 여부를 나타내는 값을 설정합니다. |
|
|  | [getProtectWithUnreadableCharacters()](#getProtectWithUnreadableCharacters--) | 텍스트 워터마크 문자가 읽을 수 없는 문자와 혼합되는지 여부를 나타내는 값을 가져옵니다. |
|
|  | [setProtectWithUnreadableCharacters(boolean value)](#setProtectWithUnreadableCharacters-boolean-) | 텍스트 워터마크 문자가 읽을 수 없는 문자와 혼합되는지 여부를 나타내는 값을 설정합니다. |
|
### PresentationShapeSettings() {#PresentationShapeSettings--}
```
public PresentationShapeSettings()
```


`[PresentationShapeSettings](../../com.groupdocs.watermark.contents/presentationshapesettings)` 클래스의 새 인스턴스를 초기화합니다.


### UnreadableCharacter {#UnreadableCharacter}
```
public static final char UnreadableCharacter
```


<br />



### isLocked() {#isLocked--}
```
public final boolean isLocked()
```


PowerPoint에서 도형 편집이 금지되어 있는지 여부를 나타내는 값을 가져옵니다.


**Returns:**
boolean - `true`이면 도형 편집이 금지되고, `false`이면 PowerPoint에서 도형을 편집할 수 있습니다.

### setLocked(boolean value) {#setLocked-boolean-}
```
public final void setLocked(boolean value)
```


PowerPoint에서 도형 편집이 금지되어 있는지 여부를 나타내는 값을 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | boolean | `true`이면 도형 편집이 금지되어야 하고, `false`이면 PowerPoint에서 도형을 편집할 수 있습니다. |
|

### getProtectWithUnreadableCharacters() {#getProtectWithUnreadableCharacters--}
```
public final boolean getProtectWithUnreadableCharacters()
```


텍스트 워터마크 문자가 읽을 수 없는 문자와 혼합되는지 여부를 나타내는 값을 가져옵니다.

이 보호는 `#isLocked().isLocked()`가 `true`를 반환할 때만 적용됩니다.


**Returns:**
boolean - 텍스트 워터마크 문자와 읽을 수 없는 문자가 혼합되어 있는지 여부를 나타내는 값.

### setProtectWithUnreadableCharacters(boolean value) {#setProtectWithUnreadableCharacters-boolean-}
```
public final void setProtectWithUnreadableCharacters(boolean value)
```


텍스트 워터마크 문자가 읽을 수 없는 문자와 혼합되는지 여부를 나타내는 값을 설정합니다.

이 보호는 `#isLocked().isLocked()`가 `true`를 반환할 때만 적용됩니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | boolean | 텍스트 워터마크 문자와 읽을 수 없는 문자가 혼합되어 있는지 여부를 나타내는 값. |
|

