---
title: "DiagramPageWatermarkOptions"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "Visio 문서의 특정 페이지에 도형 워터마크를 추가할 때의 워터마크 추가 옵션을 나타냅니다."
type: docs
weight: 11
url: /ko/java/com.groupdocs.watermark.options/diagrampagewatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.DiagramWatermarkOptions](../../com.groupdocs.watermark.options/diagramwatermarkoptions)
```
public final class DiagramPageWatermarkOptions extends DiagramWatermarkOptions
```

Visio 문서의 특정 페이지에 도형 워터마크를 추가할 때의 워터마크 추가 옵션을 나타냅니다.

**Learn more:**

* [Add watermarks to diagram documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+diagram+documents)

다음 예제는 Visio 문서의 첫 페이지에 보호된 워터마크를 추가하는 방법을 보여줍니다.
>
> ````
> ```
>
>    DiagramLoadOptions loadOptions = new DiagramLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.vsdx", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("watermark test", new Font("Arial", 42));
>
>    DiagramPageWatermarkOptions options = new DiagramPageWatermarkOptions();
>    options.setLocked(true);
>    options.setPageIndex(0);
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
|  | [DiagramPageWatermarkOptions()](#DiagramPageWatermarkOptions--) | `[DiagramPageWatermarkOptions](../../com.groupdocs.watermark.options/diagrampagewatermarkoptions)` 클래스의 새 인스턴스를 초기화합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getPageIndex()](#getPageIndex--) | 워터마크를 추가할 페이지 인덱스를 가져옵니다. |
|
|  | [setPageIndex(int value)](#setPageIndex-int-) | 워터마크를 추가할 페이지 인덱스를 설정합니다. |
|
### DiagramPageWatermarkOptions() {#DiagramPageWatermarkOptions--}
```
public DiagramPageWatermarkOptions()
```


`[DiagramPageWatermarkOptions](../../com.groupdocs.watermark.options/diagrampagewatermarkoptions)` 클래스의 새 인스턴스를 초기화합니다.


### getPageIndex() {#getPageIndex--}
```
public final int getPageIndex()
```


워터마크를 추가할 페이지 인덱스를 가져옵니다.


**Returns:**
int - 워터마크를 추가할 페이지 인덱스.

### setPageIndex(int value) {#setPageIndex-int-}
```
public final void setPageIndex(int value)
```


워터마크를 추가할 페이지 인덱스를 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | int | 워터마크를 추가할 페이지 인덱스. |
|

