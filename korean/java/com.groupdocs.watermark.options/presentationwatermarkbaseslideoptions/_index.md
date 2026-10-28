---
title: "PresentationWatermarkBaseSlideOptions"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "Presentation 문서에 대한 워터마크 추가 옵션의 기본 클래스입니다."
type: docs
weight: 39
url: /ko/java/com.groupdocs.watermark.options/presentationwatermarkbaseslideoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.PresentationWatermarkOptions](../../com.groupdocs.watermark.options/presentationwatermarkoptions)
```
public abstract class PresentationWatermarkBaseSlideOptions extends PresentationWatermarkOptions
```

Presentation 문서에 대한 워터마크 추가 옵션의 기본 클래스입니다.

**Learn more:**

* [Add watermarks to presentation documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+presentation+documents)

다음 예제는 Power Point 프레젠테이션의 다양한 서비스 슬라이드에 워터마크를 추가하는 방법을 보여줍니다.
>
> ````
> ```
>
>    PresentationLoadOptions loadOptions = new PresentationLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.pptx", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("Test watermark", new Font("Arial", 8));
>
>    // Add watermark to all master slides
>    PresentationWatermarkMasterSlideOptions masterSlideOptions = new PresentationWatermarkMasterSlideOptions();
>    masterSlideOptions.setMasterSlideIndex(-1); // default
>    watermarker.add(watermark, masterSlideOptions);
>    
>    // Add watermark to all layout slides
>    PresentationWatermarkLayoutSlideOptions layoutSlideOptions = new PresentationWatermarkLayoutSlideOptions();
>    layoutSlideOptions.setLayoutSlideIndex(-1); // default
>    watermarker.add(watermark, layoutSlideOptions);
>    
>    // Add watermark to all notes slides
>    PresentationWatermarkNoteSlideOptions noteSlideOptions = new PresentationWatermarkNoteSlideOptions();
>    noteSlideOptions.setSlideIndex(-1); // default
>    watermarker.add(watermark, noteSlideOptions);
>    
>    // Add watermark to handout master
>    PresentationWatermarkMasterHandoutSlideOptions masterHandoutSlideOptions = new PresentationWatermarkMasterHandoutSlideOptions();
>    watermarker.add(watermark, masterHandoutSlideOptions);
>    
>    // Add watermark to notes master
>    PresentationWatermarkMasterNotesSlideOptions masterNotesSlideOptions = new PresentationWatermarkMasterNotesSlideOptions();
>    watermarker.add(watermark, masterNotesSlideOptions);
>    
>    watermarker.save("D:\\watermarked_test.pptx");
>    watermarker.close();
>  
> ```
> ````


## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [isLocked()](#isLocked--) | PowerPoint에서 도형 편집이 금지되어 있는지 여부를 나타내는 값을 가져옵니다. |
|
|  | [setLocked(boolean value)](#setLocked-boolean-) | PowerPoint에서 도형 편집이 금지되어 있는지 여부를 나타내는 값을 설정합니다. |
|
|  | [getProtectWithUnreadableCharacters()](#getProtectWithUnreadableCharacters--) | 텍스트 워터마크 문자와 읽을 수 없는 문자가 혼합되어 있는지 여부를 나타내는 값을 가져오거나 설정합니다. |
|
|  | [setProtectWithUnreadableCharacters(boolean value)](#setProtectWithUnreadableCharacters-boolean-) | 텍스트 워터마크 문자와 읽을 수 없는 문자가 혼합되어 있는지 여부를 나타내는 값을 가져오거나 설정합니다. |
|
|  | [getName()](#getName--) | 도형의 이름을 가져옵니다. |
|
|  | [setName(String value)](#setName-java.lang.String-) | 도형의 이름을 설정합니다. |
|
|  | [getAlternativeText()](#getAlternativeText--) | 도형에 연결될 설명(대체) 텍스트를 가져옵니다. |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | 도형에 연결될 설명(대체) 텍스트를 설정합니다. |
|
|  | [getEffects()](#getEffects--) | 워터마크에 적용할 효과를 위해 `[PresentationImageEffects](../../com.groupdocs.watermark.options/presentationimageeffects)` 또는 `[PresentationTextEffects](../../com.groupdocs.watermark.options/presentationtexteffects)` 값을 가져옵니다. |
|
|  | [setEffects(IPresentationWatermarkEffects value)](#setEffects-com.groupdocs.watermark.options.IPresentationWatermarkEffects-) | 워터마크에 적용할 효과를 위해 `[PresentationImageEffects](../../com.groupdocs.watermark.options/presentationimageeffects)` 또는 `[PresentationTextEffects](../../com.groupdocs.watermark.options/presentationtexteffects)` 값을 설정합니다. |
|
### isLocked() {#isLocked--}
```
public final boolean isLocked()
```


PowerPoint에서 도형 편집이 금지되어 있는지 여부를 나타내는 값을 가져옵니다.


**Returns:**
boolean - 값이 true이면 도형 편집이 금지됩니다. 기본값은 false이며, PowerPoint에서 도형을 편집할 수 있습니다.

### setLocked(boolean value) {#setLocked-boolean-}
```
public final void setLocked(boolean value)
```


PowerPoint에서 도형 편집이 금지되어 있는지 여부를 나타내는 값을 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | boolean | 값이 true이면 도형 편집이 금지됩니다. 기본값은 false이며, PowerPoint에서 도형을 편집할 수 있습니다. |
|

### getProtectWithUnreadableCharacters() {#getProtectWithUnreadableCharacters--}
```
public final boolean getProtectWithUnreadableCharacters()
```


텍스트 워터마크 문자와 읽을 수 없는 문자가 혼합되어 있는지 여부를 나타내는 값을 가져오거나 설정합니다.

이 보호는 `#isLocked().isLocked()`가 `true`를 반환할 때만 적용됩니다.


**Returns:**
boolean - 텍스트 워터마크 문자와 읽을 수 없는 문자가 혼합되어 있는지 여부를 나타내는 값.

### setProtectWithUnreadableCharacters(boolean value) {#setProtectWithUnreadableCharacters-boolean-}
```
public final void setProtectWithUnreadableCharacters(boolean value)
```


텍스트 워터마크 문자와 읽을 수 없는 문자가 혼합되어 있는지 여부를 나타내는 값을 가져오거나 설정합니다.

이 보호는 `#isLocked().isLocked()`가 `true`를 반환할 때만 적용됩니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | boolean | 텍스트 워터마크 문자와 읽을 수 없는 문자가 혼합되어 있는지 여부를 나타내는 값. |
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
public final IPresentationWatermarkEffects getEffects()
```


워터마크에 적용할 효과를 위해 `[PresentationImageEffects](../../com.groupdocs.watermark.options/presentationimageeffects)` 또는 `[PresentationTextEffects](../../com.groupdocs.watermark.options/presentationtexteffects)` 값을 가져옵니다.


**Returns:**
[IPresentationWatermarkEffects](../../com.groupdocs.watermark.options/ipresentationwatermarkeffects) - The value of `[PresentationImageEffects](../../com.groupdocs.watermark.options/presentationimageeffects)` or `[PresentationTextEffects](../../com.groupdocs.watermark.options/presentationtexteffects)` for effects that should be applied to the watermark.

### setEffects(IPresentationWatermarkEffects value) {#setEffects-com.groupdocs.watermark.options.IPresentationWatermarkEffects-}
```
public final void setEffects(IPresentationWatermarkEffects value)
```


워터마크에 적용할 효과를 위해 `[PresentationImageEffects](../../com.groupdocs.watermark.options/presentationimageeffects)` 또는 `[PresentationTextEffects](../../com.groupdocs.watermark.options/presentationtexteffects)` 값을 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | value | [IPresentationWatermarkEffects](../../com.groupdocs.watermark.options/ipresentationwatermarkeffects) | 워터마크에 적용되어야 하는 효과에 대한 `[PresentationImageEffects](../../com.groupdocs.watermark.options/presentationimageeffects)` 또는 `[PresentationTextEffects](../../com.groupdocs.watermark.options/presentationtexteffects)` 값. |
|

