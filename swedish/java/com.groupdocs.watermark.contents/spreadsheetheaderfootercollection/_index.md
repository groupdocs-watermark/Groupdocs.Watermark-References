---
title: "SpreadsheetHeaderFooterCollection"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Representerar en samling av sidhuvuden och sidfötter i ett Excel-dokument."
type: docs
weight: 110
url: /sv/java/com.groupdocs.watermark.contents/spreadsheetheaderfootercollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase
```
public class SpreadsheetHeaderFooterCollection extends ReadOnlyListBase<SpreadsheetHeaderFooter>
```

Representerar en samling av sidhuvuden och sidfötter i ett Excel-dokument.

Denna samling innehåller objekt av typen `[SpreadsheetHeaderFooter](../../com.groupdocs.watermark.contents/spreadsheetheaderfooter)`.

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [SpreadsheetHeaderFooterCollection(SpreadsheetWorksheet worksheet)](#SpreadsheetHeaderFooterCollection-com.groupdocs.watermark.contents.SpreadsheetWorksheet-) | <br /> |

|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getByOfficeHeaderFooterType(int headerFooterType)](#getByOfficeHeaderFooterType-int-) | Hämtar sidhuvudet eller sidfoten av angiven typ. |
|
### SpreadsheetHeaderFooterCollection(SpreadsheetWorksheet worksheet) {#SpreadsheetHeaderFooterCollection-com.groupdocs.watermark.contents.SpreadsheetWorksheet-}
```
public SpreadsheetHeaderFooterCollection(SpreadsheetWorksheet worksheet)
```


<br />



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| worksheet | [SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet) |  |

### getByOfficeHeaderFooterType(int headerFooterType) {#getByOfficeHeaderFooterType-int-}
```
public final SpreadsheetHeaderFooter getByOfficeHeaderFooterType(int headerFooterType)
```


Hämtar sidhuvudet eller sidfoten av angiven typ.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | headerFooterType | int | Ett `[OfficeHeaderFooterType](../../com.groupdocs.watermark.contents/officeheaderfootertype)`-värde som anger typen av sidhuvud/sidfots som ska hämtas. |
|

**Returns:**
[SpreadsheetHeaderFooter](../../com.groupdocs.watermark.contents/spreadsheetheaderfooter) - The `[SpreadsheetHeaderFooter](../../com.groupdocs.watermark.contents/spreadsheetheaderfooter)` of specified type.

