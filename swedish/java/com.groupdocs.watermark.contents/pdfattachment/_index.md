---
title: "PdfAttachment"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Representerar en fil bifogad till ett pdf-innehåll."
type: docs
weight: 58
url: /sv/java/com.groupdocs.watermark.contents/pdfattachment/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.common.Attachment](../../com.groupdocs.watermark.common/attachment)
```
public class PdfAttachment extends Attachment
```

Representerar en fil bifogad till ett pdf-innehåll.

**Learn more:**

* [Attachments in PDF document](../https://docs.groupdocs.com/display/watermarkjava/Attachments+in+PDF+document)

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getName()](#getName--) | Hämtar namnet på den bifogade filen. |
|
|  | [setName(String value)](#setName-java.lang.String-) | Ställer in namnet på den bifogade filen. |
|
|  | [getDescription()](#getDescription--) | Hämtar beskrivningen av den bifogade filen. |
|
|  | [setDescription(String value)](#setDescription-java.lang.String-) | Sätter beskrivningen av den bifogade filen. |
|
|  | [getContent()](#getContent--) | Hämtar det bifogade filinnehållet. |
|
|  | [setContent(byte[] value)](#setContent-byte---) | Ställer in det bifogade filinnehållet. |
|
| [setContentStream(System.IO.Stream stream)](#setContentStream-com.aspose.ms.System.IO.Stream-) |  |
| [getContentStream()](#getContentStream--) |  |
### getName() {#getName--}
```
public final String getName()
```


Hämtar namnet på den bifogade filen.


**Returns:**
java.lang.String - Namnet på den bifogade filen.

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Ställer in namnet på den bifogade filen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | java.lang.String | Namnet på den bifogade filen. |
|

### getDescription() {#getDescription--}
```
public final String getDescription()
```


Hämtar beskrivningen av den bifogade filen.


**Returns:**
java.lang.String - Beskrivningen av den bifogade filen.

### setDescription(String value) {#setDescription-java.lang.String-}
```
public final void setDescription(String value)
```


Sätter beskrivningen av den bifogade filen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | java.lang.String | Beskrivningen av den bifogade filen. |
|

### getContent() {#getContent--}
```
public byte[] getContent()
```


Hämtar det bifogade filinnehållet.


**Returns:**
byte[] - Det bifogade filinnehållet.

### setContent(byte[] value) {#setContent-byte---}
```
public void setContent(byte[] value)
```


Ställer in det bifogade filinnehållet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | byte[] | Det bifogade filinnehållet. |
|

### setContentStream(System.IO.Stream stream) {#setContentStream-com.aspose.ms.System.IO.Stream-}
```
public void setContentStream(System.IO.Stream stream)
```


Uppdaterar den bifogade filen från en ström.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### getContentStream() {#getContentStream--}
```
public System.IO.Stream getContentStream()
```


Hämtar en ström från den bifogade filen.


**Returns:**
com.aspose.ms.System.IO.Stream
