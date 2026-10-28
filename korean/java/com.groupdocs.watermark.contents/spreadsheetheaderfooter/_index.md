---
title: "SpreadsheetHeaderFooter"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "Excel 문서의 머리글/바닥글을 나타냅니다."
type: docs
weight: 109
url: /ko/java/com.groupdocs.watermark.contents/spreadsheetheaderfooter/
---
**Inheritance:**
java.lang.Object
```
public class SpreadsheetHeaderFooter
```

Excel 문서의 머리글/바닥글을 나타냅니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [SpreadsheetHeaderFooter(SpreadsheetWorksheet worksheet, int headerFooterType)](#SpreadsheetHeaderFooter-com.groupdocs.watermark.contents.SpreadsheetWorksheet-int-) | <br /> |

|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getHeaderFooterType()](#getHeaderFooterType--) | 이 `[SpreadsheetHeaderFooter](../../com.groupdocs.watermark.contents/spreadsheetheaderfooter)`의 유형을 가져옵니다. |
|
|  | [getSections()](#getSections--) | 머리글/바닥글 섹션 컬렉션을 가져옵니다. |
|
|  | [getWorksheet()](#getWorksheet--) | 이 `[SpreadsheetHeaderFooter](../../com.groupdocs.watermark.contents/spreadsheetheaderfooter)`의 상위 워크시트를 가져옵니다. |
|
### SpreadsheetHeaderFooter(SpreadsheetWorksheet worksheet, int headerFooterType) {#SpreadsheetHeaderFooter-com.groupdocs.watermark.contents.SpreadsheetWorksheet-int-}
```
public SpreadsheetHeaderFooter(SpreadsheetWorksheet worksheet, int headerFooterType)
```


<br />



**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| worksheet | [SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet) |  |
| headerFooterType | int |  |

### getHeaderFooterType() {#getHeaderFooterType--}
```
public final int getHeaderFooterType()
```


이 `[SpreadsheetHeaderFooter](../../com.groupdocs.watermark.contents/spreadsheetheaderfooter)`의 유형을 가져옵니다.


**Returns:**
int - 이 `[SpreadsheetHeaderFooter](../../com.groupdocs.watermark.contents/spreadsheetheaderfooter)`의 유형.

### getSections() {#getSections--}
```
public final SpreadsheetHeaderFooterSectionCollection getSections()
```


머리글/바닥글 섹션 컬렉션을 가져옵니다.


**Returns:**
[SpreadsheetHeaderFooterSectionCollection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersectioncollection) - The collection of header/footer sections.

### getWorksheet() {#getWorksheet--}
```
public final SpreadsheetWorksheet getWorksheet()
```


이 `[SpreadsheetHeaderFooter](../../com.groupdocs.watermark.contents/spreadsheetheaderfooter)`의 상위 워크시트를 가져옵니다.


**Returns:**
[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet) - The parent worksheet of this `[SpreadsheetHeaderFooter](../../com.groupdocs.watermark.contents/spreadsheetheaderfooter)`.

