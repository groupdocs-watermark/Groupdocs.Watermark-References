---
title: "SpreadsheetHeaderFooterCollection"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt eine Sammlung von Kopf- und Fußzeilen in einem Excel-Dokument dar."
type: docs
weight: 110
url: /de/java/com.groupdocs.watermark.contents/spreadsheetheaderfootercollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase
```
public class SpreadsheetHeaderFooterCollection extends ReadOnlyListBase<SpreadsheetHeaderFooter>
```

Stellt eine Sammlung von Kopf- und Fußzeilen in einem Excel-Dokument dar.

Diese Sammlung enthält die Elemente des Typs `[SpreadsheetHeaderFooter](../../com.groupdocs.watermark.contents/spreadsheetheaderfooter)`.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [SpreadsheetHeaderFooterCollection(SpreadsheetWorksheet worksheet)](#SpreadsheetHeaderFooterCollection-com.groupdocs.watermark.contents.SpreadsheetWorksheet-) | <br /> |

|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getByOfficeHeaderFooterType(int headerFooterType)](#getByOfficeHeaderFooterType-int-) | Ruft die Kopf- oder Fußzeile des angegebenen Typs ab. |
|
### SpreadsheetHeaderFooterCollection(SpreadsheetWorksheet worksheet) {#SpreadsheetHeaderFooterCollection-com.groupdocs.watermark.contents.SpreadsheetWorksheet-}
```
public SpreadsheetHeaderFooterCollection(SpreadsheetWorksheet worksheet)
```


<br />



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| worksheet | [SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet) |  |

### getByOfficeHeaderFooterType(int headerFooterType) {#getByOfficeHeaderFooterType-int-}
```
public final SpreadsheetHeaderFooter getByOfficeHeaderFooterType(int headerFooterType)
```


Ruft die Kopf- oder Fußzeile des angegebenen Typs ab.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | headerFooterType | int | Ein `[OfficeHeaderFooterType](../../com.groupdocs.watermark.contents/officeheaderfootertype)`‑Wert, der den Typ der abzurufenden Kopf‑ oder Fußzeile angibt. |
|

**Returns:**
[SpreadsheetHeaderFooter](../../com.groupdocs.watermark.contents/spreadsheetheaderfooter) - The `[SpreadsheetHeaderFooter](../../com.groupdocs.watermark.contents/spreadsheetheaderfooter)` of specified type.

