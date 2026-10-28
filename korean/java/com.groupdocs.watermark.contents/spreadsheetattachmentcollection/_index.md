---
title: "SpreadsheetAttachmentCollection"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "Excel 문서의 첨부 파일 컬렉션을 나타냅니다."
type: docs
weight: 102
url: /ko/java/com.groupdocs.watermark.contents/spreadsheetattachmentcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase
```
public class SpreadsheetAttachmentCollection extends RemoveOnlyListBase<SpreadsheetAttachment>
```

Excel 문서의 첨부 파일 컬렉션을 나타냅니다.

이 컬렉션은 `[SpreadsheetAttachment](../../com.groupdocs.watermark.contents/spreadsheetattachment)` 유형의 항목을 포함합니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [addAttachment(byte[] fileContent, String sourceFullName, byte[] previewImageContent, double x, double y, double width, double height)](#addAttachment-byte---java.lang.String-byte---double-double-double-double-) | `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)`에 첨부 파일을 추가합니다. |
|
|  | [addLink(String sourceFullName, byte[] previewImageContent, double x, double y, double width, double height)](#addLink-java.lang.String-byte---double-double-double-double-) | 링크를 통해 첨부 파일을 추가합니다(문서에 첨부 파일 내용이 포함되지 않습니다). |
|
|  | [removeFromDocument(SpreadsheetAttachment item)](#removeFromDocument-com.groupdocs.watermark.contents.SpreadsheetAttachment-) | <br /> |

|
### addAttachment(byte[] fileContent, String sourceFullName, byte[] previewImageContent, double x, double y, double width, double height) {#addAttachment-byte---java.lang.String-byte---double-double-double-double-}
```
public final void addAttachment(byte[] fileContent, String sourceFullName, byte[] previewImageContent, double x, double y, double width, double height)
```


`[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)`에 첨부 파일을 추가합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | fileContent | byte[] | 첨부될 파일의 내용입니다. |
|
|  | sourceFullName | java.lang.String | 첨부된 파일의 전체 이름(확장자는 파일을 열 적절한 애플리케이션을 결정하는 데 사용됩니다). |
|
|  | previewImageContent | byte[] | 첨부된 파일 미리보기 이미지를 바이트 배열로. |
|
|  | x | double | 첨부 프레임의 x좌표(포인트 단위). |
|
|  | y | double | 첨부 프레임의 y좌표(포인트 단위). |
|
|  | 너비 | double | 포인트 단위의 첨부 프레임 너비. |
|
|  | 높이 | double | 포인트 단위의 첨부 프레임 높이. |
|

### addLink(String sourceFullName, byte[] previewImageContent, double x, double y, double width, double height) {#addLink-java.lang.String-byte---double-double-double-double-}
```
public final void addLink(String sourceFullName, byte[] previewImageContent, double x, double y, double width, double height)
```


링크를 통해 첨부 파일을 추가합니다(문서에 첨부 파일 내용이 포함되지 않습니다).


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | sourceFullName | java.lang.String | 링크된 파일 경로입니다. |
|
|  | previewImageContent | byte[] | 첨부된 파일 미리보기 이미지를 바이트 배열로. |
|
|  | x | double | 첨부 프레임의 x좌표(포인트 단위). |
|
|  | y | double | 첨부 프레임의 y좌표(포인트 단위). |
|
|  | 너비 | double | 포인트 단위의 첨부 프레임 너비. |
|
|  | 높이 | double | 포인트 단위의 첨부 프레임 높이. |
|

### removeFromDocument(SpreadsheetAttachment item) {#removeFromDocument-com.groupdocs.watermark.contents.SpreadsheetAttachment-}
```
public void removeFromDocument(SpreadsheetAttachment item)
```


<br />



**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| item | [SpreadsheetAttachment](../../com.groupdocs.watermark.contents/spreadsheetattachment) |  |

