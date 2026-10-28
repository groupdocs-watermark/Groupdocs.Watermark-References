---
title: "SpreadsheetHeaderFooter"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Rappresenta un'intestazione/piè di pagina in un documento Excel."
type: docs
weight: 109
url: /it/java/com.groupdocs.watermark.contents/spreadsheetheaderfooter/
---
**Inheritance:**
java.lang.Object
```
public class SpreadsheetHeaderFooter
```

Rappresenta un'intestazione/piè di pagina in un documento Excel.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [SpreadsheetHeaderFooter(SpreadsheetWorksheet worksheet, int headerFooterType)](#SpreadsheetHeaderFooter-com.groupdocs.watermark.contents.SpreadsheetWorksheet-int-) | <br /> |

|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getHeaderFooterType()](#getHeaderFooterType--) | Ottiene il tipo di questo `[SpreadsheetHeaderFooter](../../com.groupdocs.watermark.contents/spreadsheetheaderfooter)`. |
|
|  | [getSections()](#getSections--) | Ottiene la raccolta delle sezioni intestazione/piè di pagina. |
|
|  | [getWorksheet()](#getWorksheet--) | Ottiene il foglio di lavoro genitore di questo `[SpreadsheetHeaderFooter](../../com.groupdocs.watermark.contents/spreadsheetheaderfooter)`. |
|
### SpreadsheetHeaderFooter(SpreadsheetWorksheet worksheet, int headerFooterType) {#SpreadsheetHeaderFooter-com.groupdocs.watermark.contents.SpreadsheetWorksheet-int-}
```
public SpreadsheetHeaderFooter(SpreadsheetWorksheet worksheet, int headerFooterType)
```


<br />



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| worksheet | [SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet) |  |
| headerFooterType | int |  |

### getHeaderFooterType() {#getHeaderFooterType--}
```
public final int getHeaderFooterType()
```


Ottiene il tipo di questo `[SpreadsheetHeaderFooter](../../com.groupdocs.watermark.contents/spreadsheetheaderfooter)`.


**Returns:**
int - Il tipo di questo `[SpreadsheetHeaderFooter](../../com.groupdocs.watermark.contents/spreadsheetheaderfooter)`.

### getSections() {#getSections--}
```
public final SpreadsheetHeaderFooterSectionCollection getSections()
```


Ottiene la raccolta delle sezioni intestazione/piè di pagina.


**Returns:**
[SpreadsheetHeaderFooterSectionCollection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersectioncollection) - The collection of header/footer sections.

### getWorksheet() {#getWorksheet--}
```
public final SpreadsheetWorksheet getWorksheet()
```


Ottiene il foglio di lavoro genitore di questo `[SpreadsheetHeaderFooter](../../com.groupdocs.watermark.contents/spreadsheetheaderfooter)`.


**Returns:**
[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet) - The parent worksheet of this `[SpreadsheetHeaderFooter](../../com.groupdocs.watermark.contents/spreadsheetheaderfooter)`.

