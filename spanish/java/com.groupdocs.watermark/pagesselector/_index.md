---
title: "PagesSelector"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: 
type: docs
weight: 10
url: /es/java/com.groupdocs.watermark/pagesselector/
---
**Inheritance:**
java.lang.Object
```
public class PagesSelector
```

<br />


## Constructores

| Constructor | Descripción |
| --- | --- |
| [PagesSelector()](#PagesSelector--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getPages(boolean allPages, PagesSetup pagesSetup, int totalPages, System.Nullable<Integer> pageIndex)](#getPages-boolean-com.groupdocs.watermark.PagesSetup-int-com.aspose.ms.System.Nullable-java.lang.Integer--) | Obtiene una lista de páginas basada en la configuración especificada. |
|
|  | [getPages(boolean allPages, PagesSetup pagesSetup, int totalPages, int[] pageNumbers, boolean fromOne)](#getPages-boolean-com.groupdocs.watermark.PagesSetup-int-int---boolean-) | Obtiene una lista de páginas seleccionadas basada en los criterios especificados. |
|
### PagesSelector() {#PagesSelector--}
```
public PagesSelector()
```


### getPages(boolean allPages, PagesSetup pagesSetup, int totalPages, System.Nullable<Integer> pageIndex) {#getPages-boolean-com.groupdocs.watermark.PagesSetup-int-com.aspose.ms.System.Nullable-java.lang.Integer--}
```
public static System.Collections.Generic.List<Integer> getPages(boolean allPages, PagesSetup pagesSetup, int totalPages, System.Nullable<Integer> pageIndex)
```


Obtiene una lista de páginas basada en la configuración especificada.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | allPages | boolean | Si se deben incluir todas las páginas. |
|
|  | pagesSetup | [PagesSetup](../../com.groupdocs.watermark/pagessetup) | La configuración de la configuración de páginas. |
|
|  | totalPages | int | El número total de páginas. |
|
|  | pageIndex | com.aspose.ms.System.Nullable<java.lang.Integer> | El índice de página específico (comenzando en 0). |
|

**Returns:**
com.aspose.ms.System.Collections.Generic.List<java.lang.Integer> - Una lista de páginas basada en la configuración especificada.

### getPages(boolean allPages, PagesSetup pagesSetup, int totalPages, int[] pageNumbers, boolean fromOne) {#getPages-boolean-com.groupdocs.watermark.PagesSetup-int-int---boolean-}
```
public static System.Collections.Generic.List<Integer> getPages(boolean allPages, PagesSetup pagesSetup, int totalPages, int[] pageNumbers, boolean fromOne)
```


Obtiene una lista de páginas seleccionadas basada en los criterios especificados.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | allPages | boolean | Una bandera que indica si se deben incluir todas las páginas. |
|
|  | pagesSetup | [PagesSetup](../../com.groupdocs.watermark/pagessetup) | La configuración de la configuración para páginas. |
|
|  | totalPages | int | El número total de páginas en el documento. |
|
|  | pageNumbers | int[] | Una matriz de números de página específicos para incluir. |
|
| fromOne | boolean |  |

**Returns:**
com.aspose.ms.System.Collections.Generic.List<java.lang.Integer> - Una lista ordenada y distinta de números de página seleccionados.

