---
title: "SpreadsheetHeaderFooter"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يمثل ترويسة/تذييل في مستند Excel."
type: docs
weight: 109
url: /ar/java/com.groupdocs.watermark.contents/spreadsheetheaderfooter/
---
**Inheritance:**
java.lang.Object
```
public class SpreadsheetHeaderFooter
```

يمثل ترويسة/تذييل في مستند Excel.

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [SpreadsheetHeaderFooter(SpreadsheetWorksheet worksheet, int headerFooterType)](#SpreadsheetHeaderFooter-com.groupdocs.watermark.contents.SpreadsheetWorksheet-int-) | <br /> |

|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getHeaderFooterType()](#getHeaderFooterType--) | يحصل على نوع هذا `[SpreadsheetHeaderFooter](../../com.groupdocs.watermark.contents/spreadsheetheaderfooter)`. |
|
|  | [getSections()](#getSections--) | يحصل على مجموعة أقسام الرأس/التذييل. |
|
|  | [getWorksheet()](#getWorksheet--) | يحصل على ورقة العمل الأصلية لهذا `[SpreadsheetHeaderFooter](../../com.groupdocs.watermark.contents/spreadsheetheaderfooter)`. |
|
### SpreadsheetHeaderFooter(SpreadsheetWorksheet worksheet, int headerFooterType) {#SpreadsheetHeaderFooter-com.groupdocs.watermark.contents.SpreadsheetWorksheet-int-}
```
public SpreadsheetHeaderFooter(SpreadsheetWorksheet worksheet, int headerFooterType)
```


<br />



**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| worksheet | [SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet) |  |
| headerFooterType | int |  |

### getHeaderFooterType() {#getHeaderFooterType--}
```
public final int getHeaderFooterType()
```


يحصل على نوع هذا `[SpreadsheetHeaderFooter](../../com.groupdocs.watermark.contents/spreadsheetheaderfooter)`.


**Returns:**
int - نوع هذا `[SpreadsheetHeaderFooter](../../com.groupdocs.watermark.contents/spreadsheetheaderfooter)`.

### getSections() {#getSections--}
```
public final SpreadsheetHeaderFooterSectionCollection getSections()
```


يحصل على مجموعة أقسام الرأس/التذييل.


**Returns:**
[SpreadsheetHeaderFooterSectionCollection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersectioncollection) - The collection of header/footer sections.

### getWorksheet() {#getWorksheet--}
```
public final SpreadsheetWorksheet getWorksheet()
```


يحصل على ورقة العمل الأصلية لهذا `[SpreadsheetHeaderFooter](../../com.groupdocs.watermark.contents/spreadsheetheaderfooter)`.


**Returns:**
[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet) - The parent worksheet of this `[SpreadsheetHeaderFooter](../../com.groupdocs.watermark.contents/spreadsheetheaderfooter)`.

