---
title: "PagesSelector"
second_title: "GroupDocs.Watermark pour Java Référence API"
description: 
type: docs
weight: 10
url: /fr/java/com.groupdocs.watermark/pagesselector/
---
**Inheritance:**
java.lang.Object
```
public class PagesSelector
```

<br />


## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PagesSelector()](#PagesSelector--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getPages(boolean allPages, PagesSetup pagesSetup, int totalPages, System.Nullable<Integer> pageIndex)](#getPages-boolean-com.groupdocs.watermark.PagesSetup-int-com.aspose.ms.System.Nullable-java.lang.Integer--) | Obtient une liste de pages basée sur la configuration spécifiée. |
|
|  | [getPages(boolean allPages, PagesSetup pagesSetup, int totalPages, int[] pageNumbers, boolean fromOne)](#getPages-boolean-com.groupdocs.watermark.PagesSetup-int-int---boolean-) | Obtient une liste de pages sélectionnées basée sur les critères spécifiés. |
|
### PagesSelector() {#PagesSelector--}
```
public PagesSelector()
```


### getPages(boolean allPages, PagesSetup pagesSetup, int totalPages, System.Nullable<Integer> pageIndex) {#getPages-boolean-com.groupdocs.watermark.PagesSetup-int-com.aspose.ms.System.Nullable-java.lang.Integer--}
```
public static System.Collections.Generic.List<Integer> getPages(boolean allPages, PagesSetup pagesSetup, int totalPages, System.Nullable<Integer> pageIndex)
```


Obtient une liste de pages basée sur la configuration spécifiée.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | allPages | boolean | Indique s'il faut inclure toutes les pages. |
|
|  | pagesSetup | [PagesSetup](../../com.groupdocs.watermark/pagessetup) | La configuration de la mise en place des pages. |
|
|  | totalPages | int | Le nombre total de pages. |
|
|  | pageIndex | com.aspose.ms.System.Nullable<java.lang.Integer> | L'index de page spécifique (commençant à 0). |
|

**Returns:**
com.aspose.ms.System.Collections.Generic.List<java.lang.Integer> - Une liste de pages basée sur la configuration spécifiée.

### getPages(boolean allPages, PagesSetup pagesSetup, int totalPages, int[] pageNumbers, boolean fromOne) {#getPages-boolean-com.groupdocs.watermark.PagesSetup-int-int---boolean-}
```
public static System.Collections.Generic.List<Integer> getPages(boolean allPages, PagesSetup pagesSetup, int totalPages, int[] pageNumbers, boolean fromOne)
```


Obtient une liste de pages sélectionnées basée sur les critères spécifiés.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | allPages | boolean | Un indicateur indiquant s'il faut inclure toutes les pages. |
|
|  | pagesSetup | [PagesSetup](../../com.groupdocs.watermark/pagessetup) | La configuration de la mise en place des pages. |
|
|  | totalPages | int | Le nombre total de pages dans le document. |
|
|  | pageNumbers | int[] | Un tableau de numéros de pages spécifiques à inclure. |
|
| fromOne | boolean |  |

**Returns:**
com.aspose.ms.System.Collections.Generic.List<java.lang.Integer> - Une liste triée et distincte de numéros de pages sélectionnés.

