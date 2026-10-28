---
title: "WordProcessingTextEffects"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "Word 문서의 텍스트 워터마크에 적용할 수 있는 효과를 나타냅니다."
type: docs
weight: 72
url: /ko/java/com.groupdocs.watermark.options/wordprocessingtexteffects/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.OfficeTextEffects](../../com.groupdocs.watermark.contents/officetexteffects)

**All Implemented Interfaces:**
[com.groupdocs.watermark.options.IWordProcessingWatermarkEffects](../../com.groupdocs.watermark.options/iwordprocessingwatermarkeffects)
```
public final class WordProcessingTextEffects extends OfficeTextEffects implements IWordProcessingWatermarkEffects
```

Word 문서의 텍스트 워터마크에 적용할 수 있는 효과를 나타냅니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [WordProcessingTextEffects()](#WordProcessingTextEffects--) | `[WordProcessingTextEffects](../../com.groupdocs.watermark.options/wordprocessingtexteffects)` 클래스의 새 인스턴스를 초기화합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getFlipOrientation()](#getFlipOrientation--) | 도형의 방향을 가져옵니다. |
|
|  | [setFlipOrientation(int value)](#setFlipOrientation-int-) | 도형의 방향을 설정합니다. |
|
### WordProcessingTextEffects() {#WordProcessingTextEffects--}
```
public WordProcessingTextEffects()
```


`[WordProcessingTextEffects](../../com.groupdocs.watermark.options/wordprocessingtexteffects)` 클래스의 새 인스턴스를 초기화합니다.


### getFlipOrientation() {#getFlipOrientation--}
```
public final int getFlipOrientation()
```


도형의 방향을 가져옵니다.

기본값은 `[WordProcessingFlipOrientation.None](../../com.groupdocs.watermark.options/wordprocessingfliporientation#None)`입니다.


**Returns:**
int - 도형의 방향 `[WordProcessingFlipOrientation](../../com.groupdocs.watermark.options/wordprocessingfliporientation)`.

### setFlipOrientation(int value) {#setFlipOrientation-int-}
```
public final void setFlipOrientation(int value)
```


도형의 방향을 설정합니다.

기본값은 `[WordProcessingFlipOrientation.None](../../com.groupdocs.watermark.options/wordprocessingfliporientation#None)`입니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | value | int | 도형의 방향 `[WordProcessingFlipOrientation](../../com.groupdocs.watermark.options/wordprocessingfliporientation)`. |
|

