---
title: "PreviewOptions"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Tillhandahåller alternativ för att sätta krav och strömbaserade delegater för generering av förhandsgranskning."
type: docs
weight: 47
url: /sv/java/com.groupdocs.watermark.options/previewoptions/
---
**Inheritance:**
java.lang.Object
```
public class PreviewOptions
```

Tillhandahåller alternativ för att sätta krav och strömbaserade delegater för generering av förhandsgranskning.

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [PreviewOptions(ICreatePageStream createPageStream)](#PreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-) | Initierar en ny instans av klassen `[PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)` som gör att utdataflödet stängs. |
|
|  | [PreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)](#PreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | Initierar en ny instans av `[PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)`-klassen som gör att utdataflödet returneras till klienten för vidare användning. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getWidth()](#getWidth--) | Hämtar sidans förhandsgranskningsbredd. |
|
|  | [setWidth(int value)](#setWidth-int-) | Ställer in sidans förhandsgranskningsbredd. |
|
|  | [getHeight()](#getHeight--) | Hämtar sidans förhandsgranskningshöjd. |
|
|  | [setHeight(int value)](#setHeight-int-) | Ställer in sidans förhandsgranskningshöjd. |
|
|  | [getPageNumbers()](#getPageNumbers--) | Hämtar en array av sidnummer för att generera förhandsgranskningar. |
|
|  | [setPageNumbers(int[] value)](#setPageNumbers-int---) | Ställer in en array av sidnummer för att generera förhandsgranskningar. |
|
|  | [getPreviewFormat()](#getPreviewFormat--) | Hämtar formatet för förhandsgranskningsbilden. |
|
|  | [setPreviewFormat(int value)](#setPreviewFormat-int-) | Ställer in formatet för förhandsgranskningsbilden. |
|
|  | [getCreatePageStream()](#getCreatePageStream--) | Hämtar en instans av klassen för skapande av sidström. |
|
|  | [setCreatePageStream(ICreatePageStream value)](#setCreatePageStream-com.groupdocs.watermark.options.ICreatePageStream-) | Ställer in en instans av klassen för skapande av sidström. |
|
|  | [getReleasePageStream()](#getReleasePageStream--) | Hämtar en instans av klassen för slutförande av sidförhandsgranskning. |
|
|  | [setReleasePageStream(IReleasePageStream value)](#setReleasePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | Ställer in en instans av klassen för slutförande av sidförhandsgranskning. |
|
### PreviewOptions(ICreatePageStream createPageStream) {#PreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-}
```
public PreviewOptions(ICreatePageStream createPageStream)
```


Initierar en ny instans av klassen `[PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)` som gör att utdataflödet stängs.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Skapar en ström för en specifik sidoförhandsgranskning. |
|

### PreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream) {#PreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public PreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)
```


Initierar en ny instans av `[PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)`-klassen som gör att utdataflödet returneras till klienten för vidare användning.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Skapar en ström för en specifik sidoförhandsgranskning. |
|
|  | releasePageStream | [IReleasePageStream](../../com.groupdocs.watermark.options/ireleasepagestream) | Meddelar att sidoförhandsgranskningens generering är klar och hämtar utdataströmmen. |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Hämtar sidans förhandsgranskningsbredd.


**Returns:**
int - Sidans förhandsgranskningsbredd.

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Ställer in sidans förhandsgranskningsbredd.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | int | Sidans förhandsgranskningsbredd. |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Hämtar sidans förhandsgranskningshöjd.


**Returns:**
int - Sidans förhandsgranskningshöjd.

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Ställer in sidans förhandsgranskningshöjd.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | int | Sidans förhandsgranskningshöjd. |
|

### getPageNumbers() {#getPageNumbers--}
```
public final int[] getPageNumbers()
```


Hämtar en array av sidnummer för att generera förhandsgranskningar.


**Returns:**
int[] - Arrayen av sidnummer för att generera förhandsgranskningar.

### setPageNumbers(int[] value) {#setPageNumbers-int---}
```
public final void setPageNumbers(int[] value)
```


Ställer in en array av sidnummer för att generera förhandsgranskningar.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | int[] | Arrayen av sidnummer för att generera förhandsgranskningar. |
|

### getPreviewFormat() {#getPreviewFormat--}
```
public final int getPreviewFormat()
```


Hämtar formatet för förhandsgranskningsbilden.


**Returns:**
int - Formatet för förhandsgranskningsbilden.

### setPreviewFormat(int value) {#setPreviewFormat-int-}
```
public final void setPreviewFormat(int value)
```


Ställer in formatet för förhandsgranskningsbilden.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | int | Formatet för förhandsgranskningsbilden. |
|

### getCreatePageStream() {#getCreatePageStream--}
```
public final ICreatePageStream getCreatePageStream()
```


Hämtar en instans av klassen för skapande av sidström.


**Returns:**
[ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) - The instance of the page stream creation class.

### setCreatePageStream(ICreatePageStream value) {#setCreatePageStream-com.groupdocs.watermark.options.ICreatePageStream-}
```
public final void setCreatePageStream(ICreatePageStream value)
```


Ställer in en instans av klassen för skapande av sidström.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Instansen av klassen för skapande av sidström. |
|

### getReleasePageStream() {#getReleasePageStream--}
```
public final IReleasePageStream getReleasePageStream()
```


Hämtar en instans av klassen för slutförande av sidförhandsgranskning.


**Returns:**
[IReleasePageStream](../../com.groupdocs.watermark.options/ireleasepagestream) - The instance of the page preview completion delegate.

### setReleasePageStream(IReleasePageStream value) {#setReleasePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public final void setReleasePageStream(IReleasePageStream value)
```


Ställer in en instans av klassen för slutförande av sidförhandsgranskning.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | [IReleasePageStream](../../com.groupdocs.watermark.options/ireleasepagestream) | Instansen av delegaten för slutförande av sidförhandsgranskning. |
|

