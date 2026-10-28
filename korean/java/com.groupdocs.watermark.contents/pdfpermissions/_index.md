---
title: "PdfPermissions"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "PDF 문서에 대한 사용자 권한을 나타냅니다."
type: docs
weight: 68
url: /ko/java/com.groupdocs.watermark.contents/pdfpermissions/
---
**Inheritance:**
java.lang.Object
```
public final class PdfPermissions
```

pdf 문서에 대한 사용자의 권한을 나타냅니다.

## 필드

| 필드 | 설명 |
| --- | --- |
|  | [PrintDocument](#PrintDocument) | 콘텐츠를 인쇄합니다. |
|
|  | [ModifyContent](#ModifyContent) | 콘텐츠를 수정합니다. |
|
|  | [ExtractContent](#ExtractContent) | 문서에서 텍스트와 그래픽을 복사하거나 기타 방식으로 추출합니다. |
|
|  | [ModifyTextAnnotations](#ModifyTextAnnotations) | 텍스트 주석을 추가하거나 수정합니다. |
|
|  | [FillForm](#FillForm) | 기존 인터랙티브 양식 필드를 채웁니다. |
|
|  | [ExtractContentWithDisabilities](#ExtractContentWithDisabilities) | 텍스트와 그래픽을 추출합니다. |
|
|  | [AssembleDocument](#AssembleDocument) | 콘텐츠를 조합합니다. |
|
|  | [PrintingQuality](#PrintingQuality) | PDF 문서의 정확한 디지털 복사본을 생성할 수 있는 표현으로 콘텐츠를 인쇄합니다. |
|
### PrintDocument {#PrintDocument}
```
public static final int PrintDocument
```


콘텐츠를 인쇄합니다.

리비전 2의 보안 핸들러: 콘텐츠를 인쇄합니다.

리비전 3 이상의 보안 핸들러: 콘텐츠를 인쇄합니다
(가능한 경우 최고 품질 수준이 아닐 수 있으며, 여부에 따라
`#PrintingQuality.PrintingQuality`도 설정된 경우).


### ModifyContent {#ModifyContent}
```
public static final int ModifyContent
```


콘텐츠를 수정합니다.

다른 작업으로 문서의 내용을 수정합니다
`#ModifyTextAnnotations.ModifyTextAnnotations`, `#FillForm.FillForm`에 의해 제어되는 작업보다.


### ExtractContent {#ExtractContent}
```
public static final int ExtractContent
```


문서에서 텍스트와 그래픽을 복사하거나 기타 방식으로 추출합니다.

리비전 2의 보안 핸들러: 콘텐츠에서 텍스트와 그래픽을 복사하거나 기타 방식으로 추출합니다,
텍스트와 그래픽을 추출하는 것을 포함하여(접근성을 지원하기 위해 사용자에게
장애인 또는 기타 목적을 위해).

리비전 3 이상 보안 핸들러: 텍스트와 그래픽을 복사하거나 기타 방식으로 추출
제어되는 작업 이외의 방식으로 콘텐츠를
`#ExtractContentWithDisabilities.ExtractContentWithDisabilities`.


### ModifyTextAnnotations {#ModifyTextAnnotations}
```
public static final int ModifyTextAnnotations
```


텍스트 주석을 추가하거나 수정합니다.

텍스트 주석을 추가하거나 수정하고, 대화형 양식 필드를 채웁니다,
그리고, `#ModifyContent.ModifyContent` 가 또한 설정된 경우,
대화형 양식 필드(서명 필드 포함)를 생성하거나 수정합니다.


### FillForm {#FillForm}
```
public static final int FillForm
```


기존 인터랙티브 양식 필드를 채웁니다.

리비전 3 이상 보안 핸들러: 기존 대화형 양식 필드를 채웁니다
(서명 필드 포함), `#ModifyTextAnnotations.ModifyTextAnnotations` 가 비활성화된 경우에도.


### ExtractContentWithDisabilities {#ExtractContentWithDisabilities}
```
public static final int ExtractContentWithDisabilities
```


텍스트와 그래픽을 추출합니다.

리비전 3 이상 보안 핸들러: 텍스트와 그래픽을 추출합니다
(장애인 사용자에 대한 접근성을 지원하거나 기타 목적을 위해).


### AssembleDocument {#AssembleDocument}
```
public static final int AssembleDocument
```


콘텐츠를 조합합니다.

리비전 3 이상 보안 핸들러: 콘텐츠를 조합합니다 (삽입, 회전 또는 페이지 삭제
그리고 북마크 또는 썸네일 이미지를 생성합니다), `#ModifyContent.ModifyContent` 가 비활성화된 경우에도.


### PrintingQuality {#PrintingQuality}
```
public static final int PrintingQuality
```


PDF 문서의 정확한 디지털 복사본을 생성할 수 있는 표현으로 콘텐츠를 인쇄합니다.

리비전 3 이상 보안 핸들러: 콘텐츠를 신뢰할 수 있는 표현으로 인쇄합니다
PDF 문서의 디지털 사본을 생성할 수 있습니다. 이 비트가 비활성화된 경우(``#PrintDocument.PrintDocument`
설정된 경우), 인쇄는 외관의 저수준 표현으로 제한되며, 품질이 저하될 수 있습니다.


