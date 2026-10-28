---
title: "PresentationBaseSlide"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "PowerPoint 문서에서 모든 유형의 슬라이드에 대한 추상 기본 클래스를 제공합니다."
type: docs
weight: 78
url: /ko/java/com.groupdocs.watermark.contents/presentationbaseslide/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart)
```
public abstract class PresentationBaseSlide extends ContentPart
```

PowerPoint 문서에서 모든 유형의 슬라이드에 대한 추상 기본 클래스를 제공합니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getShapes()](#getShapes--) | 프레젠테이션의 모든 도형 컬렉션을 가져옵니다. |
|
|  | [getCharts()](#getCharts--) | 프레젠테이션의 모든 차트 컬렉션을 가져옵니다. |
|
|  | [getImageFillFormat()](#getImageFillFormat--) | 프레젠테이션의 이미지 채우기 형식 설정을 가져옵니다. |
|
|  | [getAsposeSlidesSlide()](#getAsposeSlidesSlide--) | <br /> |

|
|  | [getWidth()](#getWidth--) | <br /> |

|
|  | [getHeight()](#getHeight--) | <br /> |

|
|  | [addWatermark(Watermark watermark, PresentationShapeSettings shapeSettings, IPresentationWatermarkEffects effects)](#addWatermark-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.contents.PresentationShapeSettings-com.groupdocs.watermark.options.IPresentationWatermarkEffects-) | <br /> |

|
### getShapes() {#getShapes--}
```
public final PresentationShapeCollection getShapes()
```


프레젠테이션의 모든 도형 컬렉션을 가져옵니다.


**Returns:**
[PresentationShapeCollection](../../com.groupdocs.watermark.contents/presentationshapecollection) - The collection of all shapes of the presentation.

### getCharts() {#getCharts--}
```
public final PresentationChartCollection getCharts()
```


프레젠테이션의 모든 차트 컬렉션을 가져옵니다.


**Returns:**
[PresentationChartCollection](../../com.groupdocs.watermark.contents/presentationchartcollection) - The collection of all charts on the presentation.

### getImageFillFormat() {#getImageFillFormat--}
```
public final PresentationImageFillFormat getImageFillFormat()
```


프레젠테이션의 이미지 채우기 형식 설정을 가져옵니다.


**Returns:**
[PresentationImageFillFormat](../../com.groupdocs.watermark.contents/presentationimagefillformat) - The image fill format settings of the presentation.

### getAsposeSlidesSlide() {#getAsposeSlidesSlide--}
```
public final IBaseSlide getAsposeSlidesSlide()
```


<br />



**Returns:**
com.aspose.slides.IBaseSlide
### getWidth() {#getWidth--}
```
public double getWidth()
```


<br />



**Returns:**
double
### getHeight() {#getHeight--}
```
public double getHeight()
```


<br />



**Returns:**
double
### addWatermark(Watermark watermark, PresentationShapeSettings shapeSettings, IPresentationWatermarkEffects effects) {#addWatermark-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.contents.PresentationShapeSettings-com.groupdocs.watermark.options.IPresentationWatermarkEffects-}
```
public final void addWatermark(Watermark watermark, PresentationShapeSettings shapeSettings, IPresentationWatermarkEffects effects)
```


<br />



**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| shapeSettings | [PresentationShapeSettings](../../com.groupdocs.watermark.contents/presentationshapesettings) |  |
| effects | [IPresentationWatermarkEffects](../../com.groupdocs.watermark.options/ipresentationwatermarkeffects) |  |

