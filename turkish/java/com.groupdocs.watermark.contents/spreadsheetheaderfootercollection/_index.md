---
title: "SpreadsheetHeaderFooterCollection"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "Excel belgesindeki üstbilgi ve altbilgilerin bir koleksiyonunu temsil eder."
type: docs
weight: 110
url: /tr/java/com.groupdocs.watermark.contents/spreadsheetheaderfootercollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase
```
public class SpreadsheetHeaderFooterCollection extends ReadOnlyListBase<SpreadsheetHeaderFooter>
```

Excel belgesindeki üstbilgi ve altbilgilerin bir koleksiyonunu temsil eder.

Bu koleksiyon, `[SpreadsheetHeaderFooter](../../com.groupdocs.watermark.contents/spreadsheetheaderfooter)` tipindeki öğeleri içerir.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [SpreadsheetHeaderFooterCollection(SpreadsheetWorksheet worksheet)](#SpreadsheetHeaderFooterCollection-com.groupdocs.watermark.contents.SpreadsheetWorksheet-) | <br /> |

|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getByOfficeHeaderFooterType(int headerFooterType)](#getByOfficeHeaderFooterType-int-) | Belirtilen tipteki üstbilgi veya altbilgiyi alır. |
|
### SpreadsheetHeaderFooterCollection(SpreadsheetWorksheet worksheet) {#SpreadsheetHeaderFooterCollection-com.groupdocs.watermark.contents.SpreadsheetWorksheet-}
```
public SpreadsheetHeaderFooterCollection(SpreadsheetWorksheet worksheet)
```


<br />



**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| worksheet | [SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet) |  |

### getByOfficeHeaderFooterType(int headerFooterType) {#getByOfficeHeaderFooterType-int-}
```
public final SpreadsheetHeaderFooter getByOfficeHeaderFooterType(int headerFooterType)
```


Belirtilen tipteki üstbilgi veya altbilgiyi alır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | headerFooterType | int | Alınacak üstbilgi/altbilgi tipini belirten bir `[OfficeHeaderFooterType](../../com.groupdocs.watermark.contents/officeheaderfootertype)` değeri. |
|

**Returns:**
[SpreadsheetHeaderFooter](../../com.groupdocs.watermark.contents/spreadsheetheaderfooter) - The `[SpreadsheetHeaderFooter](../../com.groupdocs.watermark.contents/spreadsheetheaderfooter)` of specified type.

