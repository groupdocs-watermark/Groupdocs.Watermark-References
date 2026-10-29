---
title: "PagesSelector"
second_title: "GroupDocs.Watermark för Java API-referens"
description: 
type: docs
weight: 10
url: /sv/java/com.groupdocs.watermark/pagesselector/
---
**Inheritance:**
java.lang.Object
```
public class PagesSelector
```

<br />


## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [PagesSelector()](#PagesSelector--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getPages(boolean allPages, PagesSetup pagesSetup, int totalPages, System.Nullable<Integer> pageIndex)](#getPages-boolean-com.groupdocs.watermark.PagesSetup-int-com.aspose.ms.System.Nullable-java.lang.Integer--) | Hämtar en lista med sidor baserat på den angivna konfigurationen. |
|
|  | [getPages(boolean allPages, PagesSetup pagesSetup, int totalPages, int[] pageNumbers, boolean fromOne)](#getPages-boolean-com.groupdocs.watermark.PagesSetup-int-int---boolean-) | Hämtar en lista med valda sidor baserat på de angivna kriterierna. |
|
### PagesSelector() {#PagesSelector--}
```
public PagesSelector()
```


### getPages(boolean allPages, PagesSetup pagesSetup, int totalPages, System.Nullable<Integer> pageIndex) {#getPages-boolean-com.groupdocs.watermark.PagesSetup-int-com.aspose.ms.System.Nullable-java.lang.Integer--}
```
public static System.Collections.Generic.List<Integer> getPages(boolean allPages, PagesSetup pagesSetup, int totalPages, System.Nullable<Integer> pageIndex)
```


Hämtar en lista med sidor baserat på den angivna konfigurationen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | allPages | boolean | Om alla sidor ska inkluderas. |
|
|  | pagesSetup | [PagesSetup](../../com.groupdocs.watermark/pagessetup) | Konfigurationen för sidinställningarna. |
|
|  | totalPages | int | Det totala antalet sidor. |
|
|  | pageIndex | com.aspose.ms.System.Nullable<java.lang.Integer> | Det specifika sidindexet (börjar med 0). |
|

**Returns:**
com.aspose.ms.System.Collections.Generic.List<java.lang.Integer> - En lista med sidor baserat på den angivna konfigurationen.

### getPages(boolean allPages, PagesSetup pagesSetup, int totalPages, int[] pageNumbers, boolean fromOne) {#getPages-boolean-com.groupdocs.watermark.PagesSetup-int-int---boolean-}
```
public static System.Collections.Generic.List<Integer> getPages(boolean allPages, PagesSetup pagesSetup, int totalPages, int[] pageNumbers, boolean fromOne)
```


Hämtar en lista med valda sidor baserat på de angivna kriterierna.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | allPages | boolean | En flagga som indikerar om alla sidor ska inkluderas. |
|
|  | pagesSetup | [PagesSetup](../../com.groupdocs.watermark/pagessetup) | Konfigurationsinställningarna för sidor. |
|
|  | totalPages | int | Det totala antalet sidor i dokumentet. |
|
|  | pageNumbers | int[] | En array med specifika sidnummer att inkludera. |
|
| fromOne | boolean |  |

**Returns:**
com.aspose.ms.System.Collections.Generic.List<java.lang.Integer> - En sorterad och unik lista med valda sidnummer.

