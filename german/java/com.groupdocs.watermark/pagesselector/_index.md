---
title: "PagesSelector"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: 
type: docs
weight: 10
url: /de/java/com.groupdocs.watermark/pagesselector/
---
**Inheritance:**
java.lang.Object
```
public class PagesSelector
```

<br />


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PagesSelector()](#PagesSelector--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getPages(boolean allPages, PagesSetup pagesSetup, int totalPages, System.Nullable<Integer> pageIndex)](#getPages-boolean-com.groupdocs.watermark.PagesSetup-int-com.aspose.ms.System.Nullable-java.lang.Integer--) | Ruft eine Liste von Seiten basierend auf der angegebenen Konfiguration ab. |
|
|  | [getPages(boolean allPages, PagesSetup pagesSetup, int totalPages, int[] pageNumbers, boolean fromOne)](#getPages-boolean-com.groupdocs.watermark.PagesSetup-int-int---boolean-) | Ruft eine Liste ausgewählter Seiten basierend auf den angegebenen Kriterien ab. |
|
### PagesSelector() {#PagesSelector--}
```
public PagesSelector()
```


### getPages(boolean allPages, PagesSetup pagesSetup, int totalPages, System.Nullable<Integer> pageIndex) {#getPages-boolean-com.groupdocs.watermark.PagesSetup-int-com.aspose.ms.System.Nullable-java.lang.Integer--}
```
public static System.Collections.Generic.List<Integer> getPages(boolean allPages, PagesSetup pagesSetup, int totalPages, System.Nullable<Integer> pageIndex)
```


Ruft eine Liste von Seiten basierend auf der angegebenen Konfiguration ab.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | allPages | boolean | Ob alle Seiten einbezogen werden sollen. |
|
|  | pagesSetup | [PagesSetup](../../com.groupdocs.watermark/pagessetup) | Die Konfiguration der Seiteneinrichtung. |
|
|  | totalPages | int | Die Gesamtzahl der Seiten. |
|
|  | pageIndex | com.aspose.ms.System.Nullable<java.lang.Integer> | Der spezifische Seitenindex (beginnend bei 0). |
|

**Returns:**
com.aspose.ms.System.Collections.Generic.List<java.lang.Integer> - Eine Liste von Seiten basierend auf der angegebenen Konfiguration.

### getPages(boolean allPages, PagesSetup pagesSetup, int totalPages, int[] pageNumbers, boolean fromOne) {#getPages-boolean-com.groupdocs.watermark.PagesSetup-int-int---boolean-}
```
public static System.Collections.Generic.List<Integer> getPages(boolean allPages, PagesSetup pagesSetup, int totalPages, int[] pageNumbers, boolean fromOne)
```


Ruft eine Liste ausgewählter Seiten basierend auf den angegebenen Kriterien ab.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | allPages | boolean | Ein Flag, das angibt, ob alle Seiten eingeschlossen werden sollen. |
|
|  | pagesSetup | [PagesSetup](../../com.groupdocs.watermark/pagessetup) | Die Konfigurations-Einstellung für Seiten. |
|
|  | totalPages | int | Die Gesamtzahl der Seiten im Dokument. |
|
|  | pageNumbers | int[] | Ein Array spezifischer Seitenzahlen, die eingeschlossen werden sollen. |
|
| fromOne | boolean |  |

**Returns:**
com.aspose.ms.System.Collections.Generic.List<java.lang.Integer> - Eine sortierte und eindeutige Liste ausgewählter Seitenzahlen.

