---
title: "PagesSelector"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: 
type: docs
weight: 10
url: /nl/java/com.groupdocs.watermark/pagesselector/
---
**Inheritance:**
java.lang.Object
```
public class PagesSelector
```

<br />


## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [PagesSelector()](#PagesSelector--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getPages(boolean allPages, PagesSetup pagesSetup, int totalPages, System.Nullable<Integer> pageIndex)](#getPages-boolean-com.groupdocs.watermark.PagesSetup-int-com.aspose.ms.System.Nullable-java.lang.Integer--) | Haalt een lijst met pagina's op op basis van de opgegeven configuratie. |
|
|  | [getPages(boolean allPages, PagesSetup pagesSetup, int totalPages, int[] pageNumbers, boolean fromOne)](#getPages-boolean-com.groupdocs.watermark.PagesSetup-int-int---boolean-) | Haalt een lijst met geselecteerde pagina's op op basis van de opgegeven criteria. |
|
### PagesSelector() {#PagesSelector--}
```
public PagesSelector()
```


### getPages(boolean allPages, PagesSetup pagesSetup, int totalPages, System.Nullable<Integer> pageIndex) {#getPages-boolean-com.groupdocs.watermark.PagesSetup-int-com.aspose.ms.System.Nullable-java.lang.Integer--}
```
public static System.Collections.Generic.List<Integer> getPages(boolean allPages, PagesSetup pagesSetup, int totalPages, System.Nullable<Integer> pageIndex)
```


Haalt een lijst met pagina's op op basis van de opgegeven configuratie.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | allPages | boolean | Of alle pagina's moeten worden opgenomen. |
|
|  | pagesSetup | [PagesSetup](../../com.groupdocs.watermark/pagessetup) | De configuratie voor de paginainstelling. |
|
|  | totalPages | int | Het totale aantal pagina's. |
|
|  | pageIndex | com.aspose.ms.System.Nullable<java.lang.Integer> | De specifieke pagina-index (beginnend bij 0). |
|

**Returns:**
com.aspose.ms.System.Collections.Generic.List<java.lang.Integer> - Een lijst met pagina's op basis van de opgegeven configuratie.

### getPages(boolean allPages, PagesSetup pagesSetup, int totalPages, int[] pageNumbers, boolean fromOne) {#getPages-boolean-com.groupdocs.watermark.PagesSetup-int-int---boolean-}
```
public static System.Collections.Generic.List<Integer> getPages(boolean allPages, PagesSetup pagesSetup, int totalPages, int[] pageNumbers, boolean fromOne)
```


Haalt een lijst met geselecteerde pagina's op op basis van de opgegeven criteria.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | allPages | boolean | Een vlag die aangeeft of alle pagina's moeten worden opgenomen. |
|
|  | pagesSetup | [PagesSetup](../../com.groupdocs.watermark/pagessetup) | De configuratie voor de pagina-instelling. |
|
|  | totalPages | int | Het totale aantal pagina's in het document. |
|
|  | pageNumbers | int[] | Een array met specifieke paginanummers om op te nemen. |
|
| fromOne | boolean |  |

**Returns:**
com.aspose.ms.System.Collections.Generic.List<java.lang.Integer> - Een gesorteerde en unieke lijst met geselecteerde paginanummers.

