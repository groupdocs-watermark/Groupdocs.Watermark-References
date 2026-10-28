---
title: "SpreadsheetHeaderFooterCollection"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: "Stelt een verzameling kop‑ en voetteksten in een Excel‑document voor."
type: docs
weight: 110
url: /nl/java/com.groupdocs.watermark.contents/spreadsheetheaderfootercollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase
```
public class SpreadsheetHeaderFooterCollection extends ReadOnlyListBase<SpreadsheetHeaderFooter>
```

Stelt een verzameling kop‑ en voetteksten in een Excel‑document voor.

Deze collectie bevat de items van het type `[SpreadsheetHeaderFooter](../../com.groupdocs.watermark.contents/spreadsheetheaderfooter)`.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [SpreadsheetHeaderFooterCollection(SpreadsheetWorksheet worksheet)](#SpreadsheetHeaderFooterCollection-com.groupdocs.watermark.contents.SpreadsheetWorksheet-) | <br /> |

|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getByOfficeHeaderFooterType(int headerFooterType)](#getByOfficeHeaderFooterType-int-) | Haalt de koptekst of voettekst op van het opgegeven type. |
|
### SpreadsheetHeaderFooterCollection(SpreadsheetWorksheet worksheet) {#SpreadsheetHeaderFooterCollection-com.groupdocs.watermark.contents.SpreadsheetWorksheet-}
```
public SpreadsheetHeaderFooterCollection(SpreadsheetWorksheet worksheet)
```


<br />



**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| worksheet | [SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet) |  |

### getByOfficeHeaderFooterType(int headerFooterType) {#getByOfficeHeaderFooterType-int-}
```
public final SpreadsheetHeaderFooter getByOfficeHeaderFooterType(int headerFooterType)
```


Haalt de koptekst of voettekst op van het opgegeven type.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | headerFooterType | int | Een `[OfficeHeaderFooterType](../../com.groupdocs.watermark.contents/officeheaderfootertype)` waarde die het type van de op te halen koptekst/voettekst specificeert. |
|

**Returns:**
[SpreadsheetHeaderFooter](../../com.groupdocs.watermark.contents/spreadsheetheaderfooter) - The `[SpreadsheetHeaderFooter](../../com.groupdocs.watermark.contents/spreadsheetheaderfooter)` of specified type.

