---
title: "WatermarkableImage"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "문서 내부의 이미지를 나타냅니다."
type: docs
weight: 127
url: /ko/java/com.groupdocs.watermark.contents/watermarkableimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart)
```
public abstract class WatermarkableImage extends ContentPart
```

문서 내부의 이미지를 나타냅니다.

**Learn more:**

* [Adding watermark to images inside a document](../https://docs.groupdocs.com/display/watermarkjava/Adding+watermark+to+images+inside+a+document)

다음 예제는 지원되는 모든 유형의 문서 내 모든 이미지에 워터마크를 추가하는 방법을 보여줍니다.
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("D:\\input.doc");
>  
>    // Initialize text or image watermark.
>    TextWatermark watermark = new TextWatermark("DRAFT", new Font("Arial", 19));
>  
>    // Find all images in the content.
>    WatermarkableImageCollection images = watermarker.getImages();
>  
>    // Add watermark.
>    for (WatermarkableImage watermarkableImage : images)
>    {
>        watermarkableImage.add(watermark);
>    }
>  
>    // Save changes.
>    watermarker.save("D:\\output.doc");
>    watermarker.close();
>  
> ```
> ````


## 생성자

| 생성자 | 설명 |
| --- | --- |
| [WatermarkableImage(Content content)](#WatermarkableImage-com.groupdocs.watermark.contents.Content-) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getHeight()](#getHeight--) | 이 `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)`의 높이를 픽셀 단위로 가져옵니다. |
|
|  | [getWidth()](#getWidth--) | 이 `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)`의 너비를 픽셀 단위로 가져옵니다. |
|
|  | [add(Watermark watermark)](#add-com.groupdocs.watermark.Watermark-) | 이 `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)`에 워터마크를 추가합니다. |
|
|  | [getBytes()](#getBytes--) | 이미지를 바이트 배열로 가져옵니다. |
|
| [updateDocumentReference(Content parentContent)](#updateDocumentReference-com.groupdocs.watermark.contents.Content-) |  |
### WatermarkableImage(Content content) {#WatermarkableImage-com.groupdocs.watermark.contents.Content-}
```
public WatermarkableImage(Content content)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| content | [Content](../../com.groupdocs.watermark.contents/content) |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


이 `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)`의 높이를 픽셀 단위로 가져옵니다.


**Returns:**
int - 이 `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)`의 높이를 픽셀 단위로 나타냅니다.

### getWidth() {#getWidth--}
```
public final int getWidth()
```


이 `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)`의 너비를 픽셀 단위로 가져옵니다.


**Returns:**
int - 이 `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)`의 너비를 픽셀 단위로 나타냅니다.

### add(Watermark watermark) {#add-com.groupdocs.watermark.Watermark-}
```
public final void add(Watermark watermark)
```


이 `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)`에 워터마크를 추가합니다.

이 메서드는 워터마크 오프셋 및 크기가 픽셀 단위로 측정된다고 가정합니다(할당된 경우).


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | watermark | [Watermark](../../com.groupdocs.watermark/watermark) | 이미지에 추가할 워터마크입니다. |
|

### getBytes() {#getBytes--}
```
public final byte[] getBytes()
```


이미지를 바이트 배열로 가져옵니다.


**Returns:**
byte[] - 이미지 데이터입니다.

### updateDocumentReference(Content parentContent) {#updateDocumentReference-com.groupdocs.watermark.contents.Content-}
```
public final void updateDocumentReference(Content parentContent)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| parentContent | [Content](../../com.groupdocs.watermark.contents/content) |  |

