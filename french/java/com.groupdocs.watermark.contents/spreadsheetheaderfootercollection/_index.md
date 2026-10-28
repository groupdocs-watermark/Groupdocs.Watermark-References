---
title: "SpreadsheetHeaderFooterCollection"
second_title: "GroupDocs.Watermark pour Java Référence API"
description: "Représente une collection d'en-têtes et de pieds de page dans un document Excel."
type: docs
weight: 110
url: /fr/java/com.groupdocs.watermark.contents/spreadsheetheaderfootercollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase
```
public class SpreadsheetHeaderFooterCollection extends ReadOnlyListBase<SpreadsheetHeaderFooter>
```

Représente une collection d'en-têtes et de pieds de page dans un document Excel.

Cette collection contient les éléments du type `[SpreadsheetHeaderFooter](../../com.groupdocs.watermark.contents/spreadsheetheaderfooter)`.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [SpreadsheetHeaderFooterCollection(SpreadsheetWorksheet worksheet)](#SpreadsheetHeaderFooterCollection-com.groupdocs.watermark.contents.SpreadsheetWorksheet-) | <br /> |

|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getByOfficeHeaderFooterType(int headerFooterType)](#getByOfficeHeaderFooterType-int-) | Obtient l'en-tête ou le pied de page du type spécifié. |
|
### SpreadsheetHeaderFooterCollection(SpreadsheetWorksheet worksheet) {#SpreadsheetHeaderFooterCollection-com.groupdocs.watermark.contents.SpreadsheetWorksheet-}
```
public SpreadsheetHeaderFooterCollection(SpreadsheetWorksheet worksheet)
```


<br />



**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| worksheet | [SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet) |  |

### getByOfficeHeaderFooterType(int headerFooterType) {#getByOfficeHeaderFooterType-int-}
```
public final SpreadsheetHeaderFooter getByOfficeHeaderFooterType(int headerFooterType)
```


Obtient l'en-tête ou le pied de page du type spécifié.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | headerFooterType | int | Une valeur `[OfficeHeaderFooterType](../../com.groupdocs.watermark.contents/officeheaderfootertype)` qui spécifie le type de l'en-tête/pied de page à obtenir. |
|

**Returns:**
[SpreadsheetHeaderFooter](../../com.groupdocs.watermark.contents/spreadsheetheaderfooter) - The `[SpreadsheetHeaderFooter](../../com.groupdocs.watermark.contents/spreadsheetheaderfooter)` of specified type.

