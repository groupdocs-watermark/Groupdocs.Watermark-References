---
title: "SpreadsheetHeaderFooterSectionCollection"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Representerar en samling av sidhuvud/sidfotsavsnitt."
type: docs
weight: 112
url: /sv/java/com.groupdocs.watermark.contents/spreadsheetheaderfootersectioncollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase
```
public class SpreadsheetHeaderFooterSectionCollection extends ReadOnlyListBase<SpreadsheetHeaderFooterSection>
```

Representerar en samling av sidhuvud/sidfotsavsnitt.

Denna samling innehåller objekt av typen `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)`.

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [SpreadsheetHeaderFooterSectionCollection(SpreadsheetHeaderFooter headerFooter)](#SpreadsheetHeaderFooterSectionCollection-com.groupdocs.watermark.contents.SpreadsheetHeaderFooter-) | <br /> |

|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getBySpreadsheetHeaderFooterSectionType(int headerFooterSectionType)](#getBySpreadsheetHeaderFooterSectionType-int-) | Hämtar rubrik-/sidfotsektionen av angiven typ. |
|
### SpreadsheetHeaderFooterSectionCollection(SpreadsheetHeaderFooter headerFooter) {#SpreadsheetHeaderFooterSectionCollection-com.groupdocs.watermark.contents.SpreadsheetHeaderFooter-}
```
public SpreadsheetHeaderFooterSectionCollection(SpreadsheetHeaderFooter headerFooter)
```


<br />



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| headerFooter | [SpreadsheetHeaderFooter](../../com.groupdocs.watermark.contents/spreadsheetheaderfooter) |  |

### getBySpreadsheetHeaderFooterSectionType(int headerFooterSectionType) {#getBySpreadsheetHeaderFooterSectionType-int-}
```
public final SpreadsheetHeaderFooterSection getBySpreadsheetHeaderFooterSectionType(int headerFooterSectionType)
```


Hämtar rubrik-/sidfotsektionen av angiven typ.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | headerFooterSectionType | int | Ett `[SpreadsheetHeaderFooterSectionType](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersectiontype)`-värde som specificerar typen av sektionen som ska hämtas. |
|

**Returns:**
[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection) - The `[SpreadsheetHeaderFooterSection](../../com.groupdocs.watermark.contents/spreadsheetheaderfootersection)` of specified type.

