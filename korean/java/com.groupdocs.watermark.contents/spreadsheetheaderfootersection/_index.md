---
title: "SpreadsheetHeaderFooterSection"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "Excel 문서의 머리글/바닥글 섹션을 나타냅니다."
type: docs
weight: 111
url: /ko/java/com.groupdocs.watermark.contents/spreadsheetheaderfootersection/
---
**Inheritance:**
java.lang.Object
```
public class SpreadsheetHeaderFooterSection
```

Excel 문서의 머리글/바닥글 섹션을 나타냅니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getSectionType()](#getSectionType--) | 이 `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)`의 유형을 가져옵니다. |
|
|  | [getHeaderFooter()](#getHeaderFooter--) | 이 `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)`의 상위 머리글/바닥글을 가져옵니다. |
|
|  | [getScript()](#getScript--) | 이 `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)`의 스크립트 서식을 가져옵니다. |
|
|  | [setScript(String value)](#setScript-java.lang.String-) | 이 `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)`의 스크립트 서식을 설정합니다. |
|
|  | [getImage()](#getImage--) | 이 `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)`의 이미지를 가져옵니다. |
|
|  | [setImage(SpreadsheetWatermarkableImage value)](#setImage-com.groupdocs.watermark.contents.SpreadsheetWatermarkableImage-) | 이 `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)`의 이미지를 설정합니다. |
|
|  | [getImageData()](#getImageData--) | <br /> |

|
|  | [setImageData(byte[] value)](#setImageData-byte---) | <br /> |

|
|  | [resetImageReference()](#resetImageReference--) | <br /> |

|
### getSectionType() {#getSectionType--}
```
public final int getSectionType()
```


이 `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)`의 유형을 가져옵니다.


**Returns:**
int - 이 `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)`의 유형.

### getHeaderFooter() {#getHeaderFooter--}
```
public final SpreadsheetHeaderFooter getHeaderFooter()
```


이 `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)`의 상위 머리글/바닥글을 가져옵니다.


**Returns:**
[SpreadsheetHeaderFooter](../../com.groupdocs.watermark.contents/spreadsheetheaderfooter) - The parent header/footer of this `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)`.

### getScript() {#getScript--}
```
public final String getScript()
```


이 `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)`의 스크립트 서식을 가져옵니다.


**Returns:**
java.lang.String - 이 `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)`의 스크립트 내용.

### setScript(String value) {#setScript-java.lang.String-}
```
public final void setScript(String value)
```


이 `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)`의 스크립트 서식을 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | value | java.lang.String | 이 `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)`의 스크립트 내용. |
|

### getImage() {#getImage--}
```
public final SpreadsheetWatermarkableImage getImage()
```


이 `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)`의 이미지를 가져옵니다.


**Returns:**
[SpreadsheetWatermarkableImage](../../com.groupdocs.watermark.contents/spreadsheetwatermarkableimage) - The image of this `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)` or `null` if the section has no image.

### setImage(SpreadsheetWatermarkableImage value) {#setImage-com.groupdocs.watermark.contents.SpreadsheetWatermarkableImage-}
```
public final void setImage(SpreadsheetWatermarkableImage value)
```


이 `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)`의 이미지를 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | value | [SpreadsheetWatermarkableImage](../../com.groupdocs.watermark.contents/spreadsheetwatermarkableimage) | 이 `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)`의 이미지 또는 이미지를 제거해야 하는 경우 `null`. |
|

### getImageData() {#getImageData--}
```
public final byte[] getImageData()
```


<br />



**Returns:**
byte[]
### setImageData(byte[] value) {#setImageData-byte---}
```
public final void setImageData(byte[] value)
```


<br />



**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | byte[] |  |

### resetImageReference() {#resetImageReference--}
```
public final void resetImageReference()
```


<br />



