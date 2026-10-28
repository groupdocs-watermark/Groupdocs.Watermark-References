---
title: "SpreadsheetHeaderFooterCollection"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "Excel 문서의 머리글 및 바닥글 컬렉션을 나타냅니다."
type: docs
weight: 110
url: /ko/java/com.groupdocs.watermark.contents/spreadsheetheaderfootercollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase
```
public class SpreadsheetHeaderFooterCollection extends ReadOnlyListBase<SpreadsheetHeaderFooter>
```

Excel 문서의 머리글 및 바닥글 컬렉션을 나타냅니다.

이 컬렉션은 `[SpreadsheetHeaderFooter](../../com.groupdocs.watermark.contents/spreadsheetheaderfooter)` 유형의 항목을 포함합니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [SpreadsheetHeaderFooterCollection(SpreadsheetWorksheet worksheet)](#SpreadsheetHeaderFooterCollection-com.groupdocs.watermark.contents.SpreadsheetWorksheet-) | <br /> |

|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getByOfficeHeaderFooterType(int headerFooterType)](#getByOfficeHeaderFooterType-int-) | 지정된 유형의 머리글 또는 바닥글을 가져옵니다. |
|
### SpreadsheetHeaderFooterCollection(SpreadsheetWorksheet worksheet) {#SpreadsheetHeaderFooterCollection-com.groupdocs.watermark.contents.SpreadsheetWorksheet-}
```
public SpreadsheetHeaderFooterCollection(SpreadsheetWorksheet worksheet)
```


<br />



**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| worksheet | [SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet) |  |

### getByOfficeHeaderFooterType(int headerFooterType) {#getByOfficeHeaderFooterType-int-}
```
public final SpreadsheetHeaderFooter getByOfficeHeaderFooterType(int headerFooterType)
```


지정된 유형의 머리글 또는 바닥글을 가져옵니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | headerFooterType | int | `[OfficeHeaderFooterType](../../com.groupdocs.watermark.contents/officeheaderfootertype)` 값으로, 가져올 머리글/바닥글의 유형을 지정합니다. |
|

**Returns:**
[SpreadsheetHeaderFooter](../../com.groupdocs.watermark.contents/spreadsheetheaderfooter) - The `[SpreadsheetHeaderFooter](../../com.groupdocs.watermark.contents/spreadsheetheaderfooter)` of specified type.

