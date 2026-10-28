---
title: "SpreadsheetAttachmentCollection"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: "Stelt een verzameling bijlagen in een Excel‑document voor."
type: docs
weight: 102
url: /nl/java/com.groupdocs.watermark.contents/spreadsheetattachmentcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase
```
public class SpreadsheetAttachmentCollection extends RemoveOnlyListBase<SpreadsheetAttachment>
```

Stelt een verzameling bijlagen in een Excel‑document voor.

Deze collectie bevat de items van het type `[SpreadsheetAttachment](../../com.groupdocs.watermark.contents/spreadsheetattachment)`.

## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [addAttachment(byte[] fileContent, String sourceFullName, byte[] previewImageContent, double x, double y, double width, double height)](#addAttachment-byte---java.lang.String-byte---double-double-double-double-) | Voegt een bijlage toe aan de `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)`. |
|
|  | [addLink(String sourceFullName, byte[] previewImageContent, double x, double y, double width, double height)](#addLink-java.lang.String-byte---double-double-double-double-) | Voegt een bijlage toe via een link (het document zal geen bijgevoegde bestandsinhoud bevatten). |
|
|  | [removeFromDocument(SpreadsheetAttachment item)](#removeFromDocument-com.groupdocs.watermark.contents.SpreadsheetAttachment-) | <br /> |

|
### addAttachment(byte[] fileContent, String sourceFullName, byte[] previewImageContent, double x, double y, double width, double height) {#addAttachment-byte---java.lang.String-byte---double-double-double-double-}
```
public final void addAttachment(byte[] fileContent, String sourceFullName, byte[] previewImageContent, double x, double y, double width, double height)
```


Voegt een bijlage toe aan de `[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet)`.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | fileContent | byte[] | De inhoud van het bestand dat moet worden bijgevoegd. |
|
|  | sourceFullName | java.lang.String | De volledige naam van het bijgevoegde bestand (De extensie wordt gebruikt om de juiste applicatie te bepalen om het bestand te openen). |
|
|  | previewImageContent | byte[] | De voorbeeldafbeelding van het bijgevoegde bestand als een byte-array. |
|
|  | x | double | De x-coördinaat van het bijlageframe (in punten). |
|
|  | y | double | De y-coördinaat van het bijlageframe (in punten). |
|
|  | breedte | double | De breedte van het bijlageframe in punten. |
|
|  | hoogte | double | De hoogte van het bijlageframe in punten. |
|

### addLink(String sourceFullName, byte[] previewImageContent, double x, double y, double width, double height) {#addLink-java.lang.String-byte---double-double-double-double-}
```
public final void addLink(String sourceFullName, byte[] previewImageContent, double x, double y, double width, double height)
```


Voegt een bijlage toe via een link (het document zal geen bijgevoegde bestandsinhoud bevatten).


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | sourceFullName | java.lang.String | Het gekoppelde bestandspad. |
|
|  | previewImageContent | byte[] | De voorbeeldafbeelding van het bijgevoegde bestand als een byte-array. |
|
|  | x | double | De x-coördinaat van het bijlageframe (in punten). |
|
|  | y | double | De y-coördinaat van het bijlageframe (in punten). |
|
|  | breedte | double | De breedte van het bijlageframe in punten. |
|
|  | hoogte | double | De hoogte van het bijlageframe in punten. |
|

### removeFromDocument(SpreadsheetAttachment item) {#removeFromDocument-com.groupdocs.watermark.contents.SpreadsheetAttachment-}
```
public void removeFromDocument(SpreadsheetAttachment item)
```


<br />



**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [SpreadsheetAttachment](../../com.groupdocs.watermark.contents/spreadsheetattachment) |  |

