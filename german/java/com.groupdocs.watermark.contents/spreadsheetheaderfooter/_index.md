---
title: "SpreadsheetHeaderFooter"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt eine Kopf-/Fußzeile in einem Excel-Dokument dar."
type: docs
weight: 109
url: /de/java/com.groupdocs.watermark.contents/spreadsheetheaderfooter/
---
**Inheritance:**
java.lang.Object
```
public class SpreadsheetHeaderFooter
```

Stellt eine Kopf-/Fußzeile in einem Excel-Dokument dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [SpreadsheetHeaderFooter(SpreadsheetWorksheet worksheet, int headerFooterType)](#SpreadsheetHeaderFooter-com.groupdocs.watermark.contents.SpreadsheetWorksheet-int-) | <br /> |

|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getHeaderFooterType()](#getHeaderFooterType--) | Ruft den Typ dieses `[SpreadsheetHeaderFooter](../../com.groupdocs.watermark.contents/spreadsheetheaderfooter)` ab. |
|
|  | [getSections()](#getSections--) | Ruft die Sammlung der Kopf-/Fußzeilenabschnitte ab. |
|
|  | [getWorksheet()](#getWorksheet--) | Ruft das übergeordnete Arbeitsblatt dieses `[SpreadsheetHeaderFooter](../../com.groupdocs.watermark.contents/spreadsheetheaderfooter)` ab. |
|
### SpreadsheetHeaderFooter(SpreadsheetWorksheet worksheet, int headerFooterType) {#SpreadsheetHeaderFooter-com.groupdocs.watermark.contents.SpreadsheetWorksheet-int-}
```
public SpreadsheetHeaderFooter(SpreadsheetWorksheet worksheet, int headerFooterType)
```


<br />



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| worksheet | [SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet) |  |
| headerFooterType | int |  |

### getHeaderFooterType() {#getHeaderFooterType--}
```
public final int getHeaderFooterType()
```


Ruft den Typ dieses `[SpreadsheetHeaderFooter](../../com.groupdocs.watermark.contents/spreadsheetheaderfooter)` ab.


**Returns:**
int - Der Typ dieses `[SpreadsheetHeaderFooter](../../com.groupdocs.watermark.contents/spreadsheetheaderfooter)`.

### getSections() {#getSections--}
```
public final SpreadsheetHeaderFooterSectionCollection getSections()
```


Ruft die Sammlung der Kopf-/Fußzeilenabschnitte ab.


**Returns:**
[SpreadsheetHeaderFooterSectionCollection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersectioncollection) - The collection of header/footer sections.

### getWorksheet() {#getWorksheet--}
```
public final SpreadsheetWorksheet getWorksheet()
```


Ruft das übergeordnete Arbeitsblatt dieses `[SpreadsheetHeaderFooter](../../com.groupdocs.watermark.contents/spreadsheetheaderfooter)` ab.


**Returns:**
[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet) - The parent worksheet of this `[SpreadsheetHeaderFooter](../../com.groupdocs.watermark.contents/spreadsheetheaderfooter)`.

