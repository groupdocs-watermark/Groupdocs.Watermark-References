---
title: "SpreadsheetHeaderFooter"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "Excel belgesindeki bir üstbilgi/altbilgiyi temsil eder."
type: docs
weight: 109
url: /tr/java/com.groupdocs.watermark.contents/spreadsheetheaderfooter/
---
**Inheritance:**
java.lang.Object
```
public class SpreadsheetHeaderFooter
```

Excel belgesindeki bir üstbilgi/altbilgiyi temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [SpreadsheetHeaderFooter(SpreadsheetWorksheet worksheet, int headerFooterType)](#SpreadsheetHeaderFooter-com.groupdocs.watermark.contents.SpreadsheetWorksheet-int-) | <br /> |

|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getHeaderFooterType()](#getHeaderFooterType--) | Bu `[SpreadsheetHeaderFooter](../../com.groupdocs.watermark.contents/spreadsheetheaderfooter)` öğesinin tipini alır. |
|
|  | [getSections()](#getSections--) | Üstbilgi/altbilgi bölümlerinin koleksiyonunu alır. |
|
|  | [getWorksheet()](#getWorksheet--) | Bu `[SpreadsheetHeaderFooter](../../com.groupdocs.watermark.contents/spreadsheetheaderfooter)` öğesinin üst çalışma sayfasını alır. |
|
### SpreadsheetHeaderFooter(SpreadsheetWorksheet worksheet, int headerFooterType) {#SpreadsheetHeaderFooter-com.groupdocs.watermark.contents.SpreadsheetWorksheet-int-}
```
public SpreadsheetHeaderFooter(SpreadsheetWorksheet worksheet, int headerFooterType)
```


<br />



**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| worksheet | [SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet) |  |
| headerFooterType | int |  |

### getHeaderFooterType() {#getHeaderFooterType--}
```
public final int getHeaderFooterType()
```


Bu `[SpreadsheetHeaderFooter](../../com.groupdocs.watermark.contents/spreadsheetheaderfooter)` öğesinin tipini alır.


**Returns:**
int - Bu `[SpreadsheetHeaderFooter](../../com.groupdocs.watermark.contents/spreadsheetheaderfooter)` öğesinin tipi.

### getSections() {#getSections--}
```
public final SpreadsheetHeaderFooterSectionCollection getSections()
```


Üstbilgi/altbilgi bölümlerinin koleksiyonunu alır.


**Returns:**
[SpreadsheetHeaderFooterSectionCollection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersectioncollection) - The collection of header/footer sections.

### getWorksheet() {#getWorksheet--}
```
public final SpreadsheetWorksheet getWorksheet()
```


Bu `[SpreadsheetHeaderFooter](../../com.groupdocs.watermark.contents/spreadsheetheaderfooter)` öğesinin üst çalışma sayfasını alır.


**Returns:**
[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet) - The parent worksheet of this `[SpreadsheetHeaderFooter](../../com.groupdocs.watermark.contents/spreadsheetheaderfooter)`.

