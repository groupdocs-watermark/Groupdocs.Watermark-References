---
title: "SpreadsheetAttachmentCollection"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Representerar en samling av bilagor i ett Excel-dokument."
type: docs
weight: 102
url: /sv/java/com.groupdocs.watermark.contents/spreadsheetattachmentcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase
```
public class SpreadsheetAttachmentCollection extends RemoveOnlyListBase<SpreadsheetAttachment>
```

Representerar en samling av bilagor i ett Excel-dokument.

Denna samling innehåller objekt av typen `[SpreadsheetAttachment](../../com.groupdocs.watermark.contents/spreadsheetattachment)`.

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [addAttachment(byte[] fileContent, String sourceFullName, byte[] previewImageContent, double x, double y, double width, double height)](#addAttachment-byte---java.lang.String-byte---double-double-double-double-) | Lägger till en bilaga till `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)`. |
|
|  | [addLink(String sourceFullName, byte[] previewImageContent, double x, double y, double width, double height)](#addLink-java.lang.String-byte---double-double-double-double-) | Lägger till en bilaga via en länk (dokumentet kommer inte att innehålla bilagt filinnehåll). |
|
|  | [removeFromDocument(SpreadsheetAttachment item)](#removeFromDocument-com.groupdocs.watermark.contents.SpreadsheetAttachment-) | <br /> |

|
### addAttachment(byte[] fileContent, String sourceFullName, byte[] previewImageContent, double x, double y, double width, double height) {#addAttachment-byte---java.lang.String-byte---double-double-double-double-}
```
public final void addAttachment(byte[] fileContent, String sourceFullName, byte[] previewImageContent, double x, double y, double width, double height)
```


Lägger till en bilaga till `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)`.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | fileContent | byte[] | Innehållet i filen som ska bifogas. |
|
|  | sourceFullName | java.lang.String | Det fullständiga namnet på den bifogade filen (filändelsen används för att bestämma lämplig applikation för att öppna filen). |
|
|  | previewImageContent | byte[] | Den bifogade filens förhandsgranskningsbild som en bytearray. |
|
|  | x | double | X-koordinaten för bilagans ram (i punkter). |
|
|  | y | double | Y-koordinaten för bilagans ram (i punkter). |
|
|  | bredd | double | Bredden på bilagans ram i punkter. |
|
|  | höjd | double | Höjden på bilagans ram i punkter. |
|

### addLink(String sourceFullName, byte[] previewImageContent, double x, double y, double width, double height) {#addLink-java.lang.String-byte---double-double-double-double-}
```
public final void addLink(String sourceFullName, byte[] previewImageContent, double x, double y, double width, double height)
```


Lägger till en bilaga via en länk (dokumentet kommer inte att innehålla bilagt filinnehåll).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | sourceFullName | java.lang.String | Den länkade filsökvägen. |
|
|  | previewImageContent | byte[] | Den bifogade filens förhandsgranskningsbild som en bytearray. |
|
|  | x | double | X-koordinaten för bilagans ram (i punkter). |
|
|  | y | double | Y-koordinaten för bilagans ram (i punkter). |
|
|  | bredd | double | Bredden på bilagans ram i punkter. |
|
|  | höjd | double | Höjden på bilagans ram i punkter. |
|

### removeFromDocument(SpreadsheetAttachment item) {#removeFromDocument-com.groupdocs.watermark.contents.SpreadsheetAttachment-}
```
public void removeFromDocument(SpreadsheetAttachment item)
```


<br />



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [SpreadsheetAttachment](../../com.groupdocs.watermark.contents/spreadsheetattachment) |  |

