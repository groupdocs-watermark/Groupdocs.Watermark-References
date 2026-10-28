---
title: "SpreadsheetHeaderFooterSectionCollection"
second_title: "Java용 GroupDocs.Watermark API 레퍼런스"
description: "머리글/바닥글 섹션 컬렉션을 나타냅니다."
type: docs
weight: 112
url: /ko/java/com.groupdocs.watermark.contents/spreadsheetheaderfootersectioncollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase
```
public class SpreadsheetHeaderFooterSectionCollection extends ReadOnlyListBase<SpreadsheetHeaderFooterSection>
```

머리글/바닥글 섹션 컬렉션을 나타냅니다.

이 컬렉션은 `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)` 유형의 항목을 포함합니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [SpreadsheetHeaderFooterSectionCollection(SpreadsheetHeaderFooter headerFooter)](#SpreadsheetHeaderFooterSectionCollection-com.groupdocs.watermark.contents.SpreadsheetHeaderFooter-) | <br /> |

|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getBySpreadsheetHeaderFooterSectionType(int headerFooterSectionType)](#getBySpreadsheetHeaderFooterSectionType-int-) | 지정된 유형의 머리글/바닥글 섹션을 가져옵니다. |
|
### SpreadsheetHeaderFooterSectionCollection(SpreadsheetHeaderFooter headerFooter) {#SpreadsheetHeaderFooterSectionCollection-com.groupdocs.watermark.contents.SpreadsheetHeaderFooter-}
```
public SpreadsheetHeaderFooterSectionCollection(SpreadsheetHeaderFooter headerFooter)
```


<br />



**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| headerFooter | [SpreadsheetHeaderFooter](../../com.groupdocs.watermark.contents/spreadsheetheaderfooter) |  |

### getBySpreadsheetHeaderFooterSectionType(int headerFooterSectionType) {#getBySpreadsheetHeaderFooterSectionType-int-}
```
public final SpreadsheetHeaderFooterSection getBySpreadsheetHeaderFooterSectionType(int headerFooterSectionType)
```


지정된 유형의 머리글/바닥글 섹션을 가져옵니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | headerFooterSectionType | int | 가져올 섹션의 유형을 지정하는 `[SpreadsheetHeaderFooterSectionType](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersectiontype)` 값입니다. |
|

**Returns:**
[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection) - The `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)` of specified type.

