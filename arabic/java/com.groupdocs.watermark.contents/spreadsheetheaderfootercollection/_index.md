---
title: "SpreadsheetHeaderFooterCollection"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يمثل مجموعة من الترويسات والتذييلات في مستند Excel."
type: docs
weight: 110
url: /ar/java/com.groupdocs.watermark.contents/spreadsheetheaderfootercollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase
```
public class SpreadsheetHeaderFooterCollection extends ReadOnlyListBase<SpreadsheetHeaderFooter>
```

يمثل مجموعة من الترويسات والتذييلات في مستند Excel.

هذه المجموعة تحتوي على العناصر من النوع `[SpreadsheetHeaderFooter](../../com.groupdocs.watermark.contents/spreadsheetheaderfooter)`.

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [SpreadsheetHeaderFooterCollection(SpreadsheetWorksheet worksheet)](#SpreadsheetHeaderFooterCollection-com.groupdocs.watermark.contents.SpreadsheetWorksheet-) | <br /> |

|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getByOfficeHeaderFooterType(int headerFooterType)](#getByOfficeHeaderFooterType-int-) | يحصل على الرأس أو التذييل من النوع المحدد. |
|
### SpreadsheetHeaderFooterCollection(SpreadsheetWorksheet worksheet) {#SpreadsheetHeaderFooterCollection-com.groupdocs.watermark.contents.SpreadsheetWorksheet-}
```
public SpreadsheetHeaderFooterCollection(SpreadsheetWorksheet worksheet)
```


<br />



**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| worksheet | [SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet) |  |

### getByOfficeHeaderFooterType(int headerFooterType) {#getByOfficeHeaderFooterType-int-}
```
public final SpreadsheetHeaderFooter getByOfficeHeaderFooterType(int headerFooterType)
```


يحصل على الرأس أو التذييل من النوع المحدد.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | headerFooterType | int | قيمة `[OfficeHeaderFooterType](../../com.groupdocs.watermark.contents/officeheaderfootertype)` تحدد نوع الرأس/التذييل المراد الحصول عليه. |
|

**Returns:**
[SpreadsheetHeaderFooter](../../com.groupdocs.watermark.contents/spreadsheetheaderfooter) - The `[SpreadsheetHeaderFooter](../../com.groupdocs.watermark.contents/spreadsheetheaderfooter)` of specified type.

