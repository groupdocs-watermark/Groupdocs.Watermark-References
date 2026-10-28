---
title: "SpreadsheetHeaderFooterSectionCollection"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Rappresenta una raccolta di sezioni di intestazione/piè di pagina."
type: docs
weight: 112
url: /it/java/com.groupdocs.watermark.contents/spreadsheetheaderfootersectioncollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase
```
public class SpreadsheetHeaderFooterSectionCollection extends ReadOnlyListBase<SpreadsheetHeaderFooterSection>
```

Rappresenta una raccolta di sezioni di intestazione/piè di pagina.

Questa collezione contiene gli elementi di tipo `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)`.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [SpreadsheetHeaderFooterSectionCollection(SpreadsheetHeaderFooter headerFooter)](#SpreadsheetHeaderFooterSectionCollection-com.groupdocs.watermark.contents.SpreadsheetHeaderFooter-) | <br /> |

|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getBySpreadsheetHeaderFooterSectionType(int headerFooterSectionType)](#getBySpreadsheetHeaderFooterSectionType-int-) | Ottiene la sezione intestazione/piè di pagina del tipo specificato. |
|
### SpreadsheetHeaderFooterSectionCollection(SpreadsheetHeaderFooter headerFooter) {#SpreadsheetHeaderFooterSectionCollection-com.groupdocs.watermark.contents.SpreadsheetHeaderFooter-}
```
public SpreadsheetHeaderFooterSectionCollection(SpreadsheetHeaderFooter headerFooter)
```


<br />



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| headerFooter | [SpreadsheetHeaderFooter](../../com.groupdocs.watermark.contents/spreadsheetheaderfooter) |  |

### getBySpreadsheetHeaderFooterSectionType(int headerFooterSectionType) {#getBySpreadsheetHeaderFooterSectionType-int-}
```
public final SpreadsheetHeaderFooterSection getBySpreadsheetHeaderFooterSectionType(int headerFooterSectionType)
```


Ottiene la sezione intestazione/piè di pagina del tipo specificato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | headerFooterSectionType | int | Un valore `[SpreadsheetHeaderFooterSectionType](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersectiontype)` che specifica il tipo di sezione da ottenere. |
|

**Returns:**
[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection) - The `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)` of specified type.

