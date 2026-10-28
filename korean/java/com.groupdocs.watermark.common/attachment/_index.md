---
title: "Attachment"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "문서에 첨부된 파일을 나타냅니다."
type: docs
weight: 10
url: /ko/java/com.groupdocs.watermark.common/attachment/
---
**Inheritance:**
java.lang.Object
```
public abstract class Attachment
```

문서에 첨부된 파일을 나타냅니다.

**Learn more**

* [Email attachments](../https://docs.groupdocs.com/display/watermarkjava/Email+attachments)
* [Attachments in PDF document](../https://docs.groupdocs.com/display/watermarkjava/Attachments+in+PDF+document)
* [Working with spreadsheet document attachments](../https://docs.groupdocs.com/display/watermarkjava/Working+with+spreadsheet+document+attachments)

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getDocumentInfo()](#getDocumentInfo--) | 첨부된 파일에 저장된 문서에 대한 정보를 가져옵니다. |
|
|  | [getContent()](#getContent--) | 첨부된 파일 내용을 가져옵니다. |
|
|  | [setContent(byte[] value)](#setContent-byte---) | 첨부된 파일 내용을 설정합니다. |
|
|  | [createWatermarker()](#createWatermarker--) | 첨부된 파일에서 내용을 로드합니다. |
|
|  | [createWatermarker(LoadOptions loadOptions)](#createWatermarker-com.groupdocs.watermark.options.LoadOptions-) | 지정된 로드 옵션을 사용하여 첨부된 파일에서 내용을 로드합니다. |
|
|  | [createWatermarker(LoadOptions loadOptions, WatermarkerSettings watermarkerSettings)](#createWatermarker-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-) | 지정된 로드 옵션 및 설정을 사용하여 첨부된 파일에서 내용을 로드합니다. |
|
|  | [getContentStream()](#getContentStream--) | 첨부된 파일에서 스트림을 가져옵니다. |
|
|  | [setContentStream(System.IO.Stream stream)](#setContentStream-com.aspose.ms.System.IO.Stream-) | 스트림을 사용하여 첨부된 파일을 업데이트합니다. |
|
|  | [updateContent(Watermarker updatedVersion)](#updateContent-com.groupdocs.watermark.Watermarker-) | 첨부된 내용을 업데이트합니다. |
|
### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


첨부된 파일에 저장된 문서에 대한 정보를 가져옵니다.


**Returns:**
[IDocumentInfo](../../com.groupdocs.watermark.common/idocumentinfo) - The `[IDocumentInfo](../../com.groupdocs.watermark.common/idocumentinfo)` instance that contains detected information.

### getContent() {#getContent--}
```
public abstract byte[] getContent()
```


첨부된 파일 내용을 가져옵니다.


**Returns:**
byte[] - 첨부된 파일 내용.

### setContent(byte[] value) {#setContent-byte---}
```
public abstract void setContent(byte[] value)
```


첨부된 파일 내용을 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | byte[] | 첨부된 파일 내용. |
|

### createWatermarker() {#createWatermarker--}
```
public final Watermarker createWatermarker()
```


첨부된 파일에서 내용을 로드합니다.


**Returns:**
[Watermarker](../../com.groupdocs.watermark/watermarker) - The instance of appropriate descendant of `[Content](../../com.groupdocs.watermark.contents/content)` class.

### createWatermarker(LoadOptions loadOptions) {#createWatermarker-com.groupdocs.watermark.options.LoadOptions-}
```
public final Watermarker createWatermarker(LoadOptions loadOptions)
```


지정된 로드 옵션을 사용하여 첨부된 파일에서 내용을 로드합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | loadOptions | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) | 첨부 파일 내용을 로드할 때 사용할 추가 옵션. |
|

**Returns:**
[Watermarker](../../com.groupdocs.watermark/watermarker) - The instance of appropriate descendant of `[Content](../../com.groupdocs.watermark.contents/content)` class.

### createWatermarker(LoadOptions loadOptions, WatermarkerSettings watermarkerSettings) {#createWatermarker-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-}
```
public final Watermarker createWatermarker(LoadOptions loadOptions, WatermarkerSettings watermarkerSettings)
```


지정된 로드 옵션 및 설정을 사용하여 첨부된 파일에서 내용을 로드합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | loadOptions | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) | 첨부 파일 내용을 로드할 때 사용할 추가 옵션. |
|
|  | watermarkerSettings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) | 로드된 문서를 작업할 때 사용할 추가 설정입니다. |
|

**Returns:**
[Watermarker](../../com.groupdocs.watermark/watermarker) - The instance of appropriate descendant of `[Content](../../com.groupdocs.watermark.contents/content)` class.

### getContentStream() {#getContentStream--}
```
public System.IO.Stream getContentStream()
```


첨부된 파일에서 스트림을 가져옵니다.


**Returns:**
com.aspose.ms.System.IO.Stream - 파일 내용을 읽을 스트림.

### setContentStream(System.IO.Stream stream) {#setContentStream-com.aspose.ms.System.IO.Stream-}
```
public void setContentStream(System.IO.Stream stream)
```


스트림을 사용하여 첨부된 파일을 업데이트합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 스트림 | com.aspose.ms.System.IO.Stream | 첨부된 파일을 업데이트할 스트림. |
|

### updateContent(Watermarker updatedVersion) {#updateContent-com.groupdocs.watermark.Watermarker-}
```
public final void updateContent(Watermarker updatedVersion)
```


첨부된 내용을 업데이트합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | updatedVersion | [Watermarker](../../com.groupdocs.watermark/watermarker) | 업데이트된 내용 버전. |
|

