---
title: "ImageWatermark"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "이미지 워터마크를 나타냅니다."
type: docs
weight: 13
url: /ko/java/com.groupdocs.watermark.watermarks/imagewatermark/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.Watermark](../../com.groupdocs.watermark/watermark)

**All Implemented Interfaces:**
java.io.Closeable
```
public final class ImageWatermark extends Watermark implements Closeable
```

이미지 워터마크를 나타냅니다.

**Learn more:**

* [Adding image watermarks](../https://docs.groupdocs.com/display/watermarkjava/Adding+image+watermarks)

다음 예제는 지원되는 모든 유형의 문서에 이미지 워터마크를 추가하는 방법을 보여줍니다.
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("C:\\test.some_ext");
>    ImageWatermark watermark = new ImageWatermark("C:\\watermark.png");
>
>    watermark.setHorizontalAlignment(HorizontalAlignment.Center);
>    watermark.setVerticalAlignment(VerticalAlignment.Center);
>    watermarker.add(watermark);
>
>    watermarker.save("C:\\modified_test.some_ext");
>    watermark.close();
>    watermarker.close();
>  
> ```
> ````


## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [ImageWatermark(String filePath)](#ImageWatermark-java.lang.String-) | 지정된 파일 경로를 사용하여 `[ImageWatermark](../../com.groupdocs.watermark.watermarks/imagewatermark)` 클래스의 새 인스턴스를 초기화합니다. |
|
|  | [ImageWatermark(InputStream stream)](#ImageWatermark-java.io.InputStream-) | 지정된 스트림을 사용하여 `[ImageWatermark](../../com.groupdocs.watermark.watermarks/imagewatermark)` 클래스의 새 인스턴스를 초기화합니다. |
|
| [ImageWatermark(System.IO.Stream stream)](#ImageWatermark-com.aspose.ms.System.IO.Stream-) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [isImageWatermark()](#isImageWatermark--) |  |
| [isTextWatermark()](#isTextWatermark--) |  |
| [getStream()](#getStream--) |  |
| [getTransparentImageContainer()](#getTransparentImageContainer--) |  |
| [getSize()](#getSize--) |  |
| [dispose()](#dispose--) |  |
| [deepClone()](#deepClone--) |  |
| [hasSameValues(Watermark watermark)](#hasSameValues-com.groupdocs.watermark.Watermark-) |  |
| [createGeometry(ContentPartGeometry parent)](#createGeometry-com.groupdocs.watermark.internal.ContentPartGeometry-) |  |
|  | [close()](#close--) | 현재 인스턴스를 해제합니다. |
|
### ImageWatermark(String filePath) {#ImageWatermark-java.lang.String-}
```
public ImageWatermark(String filePath)
```


지정된 파일 경로를 사용하여 `[ImageWatermark](../../com.groupdocs.watermark.watermarks/imagewatermark)` 클래스의 새 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | filePath | java.lang.String | 워터마크로 사용할 이미지의 경로입니다. |
|

### ImageWatermark(InputStream stream) {#ImageWatermark-java.io.InputStream-}
```
public ImageWatermark(InputStream stream)
```


지정된 스트림을 사용하여 `[ImageWatermark](../../com.groupdocs.watermark.watermarks/imagewatermark)` 클래스의 새 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 스트림 | java.io.InputStream | 워터마크로 사용할 이미지를 포함하는 스트림입니다. |
|

### ImageWatermark(System.IO.Stream stream) {#ImageWatermark-com.aspose.ms.System.IO.Stream-}
```
public ImageWatermark(System.IO.Stream stream)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 스트림 | com.aspose.ms.System.IO.Stream |  |

### isImageWatermark() {#isImageWatermark--}
```
public boolean isImageWatermark()
```




**Returns:**
boolean
### isTextWatermark() {#isTextWatermark--}
```
public boolean isTextWatermark()
```




**Returns:**
boolean
### getStream() {#getStream--}
```
public final StreamContainer getStream()
```




**Returns:**
[StreamContainer](../../com.groupdocs.watermark.internal/streamcontainer)
### getTransparentImageContainer() {#getTransparentImageContainer--}
```
public final StreamContainer getTransparentImageContainer()
```




**Returns:**
[StreamContainer](../../com.groupdocs.watermark.internal/streamcontainer)
### getSize() {#getSize--}
```
public SizeD getSize()
```




**Returns:**
[SizeD](../../com.groupdocs.watermark.internal/sized)
### dispose() {#dispose--}
```
public final void dispose()
```




### deepClone() {#deepClone--}
```
public Watermark deepClone()
```




**Returns:**
[Watermark](../../com.groupdocs.watermark/watermark)
### hasSameValues(Watermark watermark) {#hasSameValues-com.groupdocs.watermark.Watermark-}
```
public boolean hasSameValues(Watermark watermark)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |

**Returns:**
boolean
### createGeometry(ContentPartGeometry parent) {#createGeometry-com.groupdocs.watermark.internal.ContentPartGeometry-}
```
public WatermarkGeometry createGeometry(ContentPartGeometry parent)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| parent | [ContentPartGeometry](../../com.groupdocs.watermark.internal/contentpartgeometry) |  |

**Returns:**
[WatermarkGeometry](../../com.groupdocs.watermark.internal/watermarkgeometry)
### close() {#close--}
```
public final void close()
```


현재 인스턴스를 해제합니다.


