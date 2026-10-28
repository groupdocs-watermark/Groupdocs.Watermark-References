---
title: "SpreadsheetHeaderFooterSectionCollection"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt eine Sammlung von Kopf-/Fußzeilenabschnitten dar."
type: docs
weight: 112
url: /de/java/com.groupdocs.watermark.contents/spreadsheetheaderfootersectioncollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase
```
public class SpreadsheetHeaderFooterSectionCollection extends ReadOnlyListBase<SpreadsheetHeaderFooterSection>
```

Stellt eine Sammlung von Kopf-/Fußzeilenabschnitten dar.

Diese Sammlung enthält die Elemente des Typs `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)`.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [SpreadsheetHeaderFooterSectionCollection(SpreadsheetHeaderFooter headerFooter)](#SpreadsheetHeaderFooterSectionCollection-com.groupdocs.watermark.contents.SpreadsheetHeaderFooter-) | <br /> |

|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getBySpreadsheetHeaderFooterSectionType(int headerFooterSectionType)](#getBySpreadsheetHeaderFooterSectionType-int-) | Ruft den Kopf‑/Fußzeilenabschnitt des angegebenen Typs ab. |
|
### SpreadsheetHeaderFooterSectionCollection(SpreadsheetHeaderFooter headerFooter) {#SpreadsheetHeaderFooterSectionCollection-com.groupdocs.watermark.contents.SpreadsheetHeaderFooter-}
```
public SpreadsheetHeaderFooterSectionCollection(SpreadsheetHeaderFooter headerFooter)
```


<br />



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| headerFooter | [SpreadsheetHeaderFooter](../../com.groupdocs.watermark.contents/spreadsheetheaderfooter) |  |

### getBySpreadsheetHeaderFooterSectionType(int headerFooterSectionType) {#getBySpreadsheetHeaderFooterSectionType-int-}
```
public final SpreadsheetHeaderFooterSection getBySpreadsheetHeaderFooterSectionType(int headerFooterSectionType)
```


Ruft den Kopf‑/Fußzeilenabschnitt des angegebenen Typs ab.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | headerFooterSectionType | int | Ein `[SpreadsheetHeaderFooterSectionType](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersectiontype)`‑Wert, der den Typ des abzurufenden Abschnitts angibt. |
|

**Returns:**
[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection) - The `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)` of specified type.

