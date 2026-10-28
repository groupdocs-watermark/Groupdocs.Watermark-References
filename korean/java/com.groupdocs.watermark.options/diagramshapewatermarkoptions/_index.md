---
title: "DiagramShapeWatermarkOptions"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "Visio 문서에 도형 워터마크를 추가할 때의 워터마크 추가 옵션을 나타냅니다."
type: docs
weight: 14
url: /ko/java/com.groupdocs.watermark.options/diagramshapewatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.DiagramWatermarkOptions](../../com.groupdocs.watermark.options/diagramwatermarkoptions)
```
public final class DiagramShapeWatermarkOptions extends DiagramWatermarkOptions
```

Visio 문서에 도형 워터마크를 추가할 때의 워터마크 추가 옵션을 나타냅니다.

**Learn more:**

* [Add watermarks to diagram documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+diagram+documents)

다음 예제는 Visio 문서의 모든 페이지에 보호 워터마크를 추가하는 방법을 보여줍니다.
>
> ````
> ```
>
>    DiagramLoadOptions loadOptions = new DiagramLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.vsdx", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("watermark test", new Font("Arial", 42));
>
>    DiagramShapeWatermarkOptions options = new DiagramShapeWatermarkOptions();
>    options.setLocked(true);
>    options.setPlacementType(DiagramWatermarkPlacementType.AllPages);
>
>    watermarker.add(watermark, options);
>    watermarker.save("D:\\watermarked_test.vsdx");
>    watermarker.close();
>  
> ```
> ````


## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [DiagramShapeWatermarkOptions()](#DiagramShapeWatermarkOptions--) | `[DiagramShapeWatermarkOptions](../../com.groupdocs.watermark.options/diagramshapewatermarkoptions)` 클래스의 새 인스턴스를 초기화합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getPlacementType()](#getPlacementType--) | 워터마크를 추가할 페이지를 지정하는 값을 가져옵니다. |
|
|  | [setPlacementType(int value)](#setPlacementType-int-) | 워터마크를 추가할 페이지를 지정하는 값을 가져오거나 설정합니다. |
|
### DiagramShapeWatermarkOptions() {#DiagramShapeWatermarkOptions--}
```
public DiagramShapeWatermarkOptions()
```


`[DiagramShapeWatermarkOptions](../../com.groupdocs.watermark.options/diagramshapewatermarkoptions)` 클래스의 새 인스턴스를 초기화합니다.


### getPlacementType() {#getPlacementType--}
```
public final int getPlacementType()
```


워터마크를 추가할 페이지를 지정하는 값을 가져옵니다.


**Returns:**
int - 워터마크를 추가할 페이지를 지정하는 `[DiagramWatermarkPlacementType](../../com.groupdocs.watermark.contents/diagramwatermarkplacementtype)`입니다.

### setPlacementType(int value) {#setPlacementType-int-}
```
public final void setPlacementType(int value)
```


워터마크를 추가할 페이지를 지정하는 값을 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | value | int | 워터마크를 추가할 페이지를 지정하는 `[DiagramWatermarkPlacementType](../../com.groupdocs.watermark.contents/diagramwatermarkplacementtype)`입니다. |
|

