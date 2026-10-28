---
title: "PdfWatermarkableImage"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "Pdf 문서 내부의 이미지를 나타냅니다."
type: docs
weight: 72
url: /ko/java/com.groupdocs.watermark.contents/pdfwatermarkableimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart), [com.groupdocs.watermark.contents.WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)
```
public class PdfWatermarkableImage extends WatermarkableImage
```

Pdf 문서 내부의 이미지를 나타냅니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [PdfWatermarkableImage(byte[] imageData)](#PdfWatermarkableImage-byte---) | 지정된 이미지 데이터를 사용하여 `[PdfWatermarkableImage](../../com.groupdocs.watermark.contents/pdfwatermarkableimage)` 클래스의 새 인스턴스를 초기화합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [fetchOrCreate(XImageCollection imageCollection, String nameInCollection, PdfContent content)](#fetchOrCreate-com.aspose.pdf.XImageCollection-java.lang.String-com.groupdocs.watermark.contents.PdfContent-) | <br /> |

|
### PdfWatermarkableImage(byte[] imageData) {#PdfWatermarkableImage-byte---}
```
public PdfWatermarkableImage(byte[] imageData)
```


지정된 이미지 데이터를 사용하여 `[PdfWatermarkableImage](../../com.groupdocs.watermark.contents/pdfwatermarkableimage)` 클래스의 새 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | imageData | byte[] | `[PdfWatermarkableImage](../../com.groupdocs.watermark.contents/pdfwatermarkableimage)`를 생성할 때 사용할 부호 없는 바이트 배열입니다. |
|

### fetchOrCreate(XImageCollection imageCollection, String nameInCollection, PdfContent content) {#fetchOrCreate-com.aspose.pdf.XImageCollection-java.lang.String-com.groupdocs.watermark.contents.PdfContent-}
```
public static PdfWatermarkableImage fetchOrCreate(XImageCollection imageCollection, String nameInCollection, PdfContent content)
```


<br />



**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| imageCollection | com.aspose.pdf.XImageCollection |  |
| nameInCollection | java.lang.String |  |
| content | [PdfContent](../../com.groupdocs.watermark.contents/pdfcontent) |  |

**Returns:**
[PdfWatermarkableImage](../../com.groupdocs.watermark.contents/pdfwatermarkableimage)
