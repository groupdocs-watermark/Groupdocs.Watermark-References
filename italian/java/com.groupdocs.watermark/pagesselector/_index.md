---
title: "PagesSelector"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: 
type: docs
weight: 10
url: /it/java/com.groupdocs.watermark/pagesselector/
---
**Inheritance:**
java.lang.Object
```
public class PagesSelector
```

<br />


## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PagesSelector()](#PagesSelector--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getPages(boolean allPages, PagesSetup pagesSetup, int totalPages, System.Nullable<Integer> pageIndex)](#getPages-boolean-com.groupdocs.watermark.PagesSetup-int-com.aspose.ms.System.Nullable-java.lang.Integer--) | Ottiene un elenco di pagine basato sulla configurazione specificata. |
|
|  | [getPages(boolean allPages, PagesSetup pagesSetup, int totalPages, int[] pageNumbers, boolean fromOne)](#getPages-boolean-com.groupdocs.watermark.PagesSetup-int-int---boolean-) | Ottiene un elenco di pagine selezionate basato sui criteri specificati. |
|
### PagesSelector() {#PagesSelector--}
```
public PagesSelector()
```


### getPages(boolean allPages, PagesSetup pagesSetup, int totalPages, System.Nullable<Integer> pageIndex) {#getPages-boolean-com.groupdocs.watermark.PagesSetup-int-com.aspose.ms.System.Nullable-java.lang.Integer--}
```
public static System.Collections.Generic.List<Integer> getPages(boolean allPages, PagesSetup pagesSetup, int totalPages, System.Nullable<Integer> pageIndex)
```


Ottiene un elenco di pagine basato sulla configurazione specificata.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | allPages | boolean | Indica se includere tutte le pagine. |
|
|  | pagesSetup | [PagesSetup](../../com.groupdocs.watermark/pagessetup) | La configurazione dell'impostazione delle pagine. |
|
|  | totalPages | int | Il numero totale di pagine. |
|
|  | pageIndex | com.aspose.ms.System.Nullable<java.lang.Integer> | L'indice della pagina specifica (a partire da 0). |
|

**Returns:**
com.aspose.ms.System.Collections.Generic.List<java.lang.Integer> - Un elenco di pagine basato sulla configurazione specificata.

### getPages(boolean allPages, PagesSetup pagesSetup, int totalPages, int[] pageNumbers, boolean fromOne) {#getPages-boolean-com.groupdocs.watermark.PagesSetup-int-int---boolean-}
```
public static System.Collections.Generic.List<Integer> getPages(boolean allPages, PagesSetup pagesSetup, int totalPages, int[] pageNumbers, boolean fromOne)
```


Ottiene un elenco di pagine selezionate basato sui criteri specificati.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | allPages | boolean | Un flag che indica se includere tutte le pagine. |
|
|  | pagesSetup | [PagesSetup](../../com.groupdocs.watermark/pagessetup) | La configurazione dell'impostazione per le pagine. |
|
|  | totalPages | int | Il numero totale di pagine nel documento. |
|
|  | pageNumbers | int[] | Un array di numeri di pagina specifici da includere. |
|
| fromOne | boolean |  |

**Returns:**
com.aspose.ms.System.Collections.Generic.List<java.lang.Integer> - Un elenco ordinato e distinto di numeri di pagina selezionati.

