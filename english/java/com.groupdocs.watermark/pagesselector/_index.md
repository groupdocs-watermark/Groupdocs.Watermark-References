---
title: PagesSelector
second_title: GroupDocs.Watermark for Java API Reference
description: 
type: docs
weight: 10
url: /java/com.groupdocs.watermark/pagesselector/
---
**Inheritance:**
java.lang.Object
```
public class PagesSelector
```
## Constructors

| Constructor | Description |
| --- | --- |
| [PagesSelector()](#PagesSelector--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getPages(boolean allPages, PagesSetup pagesSetup, int totalPages, System.Nullable<Integer> pageIndex)](#getPages-boolean-com.groupdocs.watermark.PagesSetup-int-com.aspose.ms.System.Nullable-java.lang.Integer--) | Gets a list of pages based on the specified setup. |
| [getPages(boolean allPages, PagesSetup pagesSetup, int totalPages, int[] pageNumbers, boolean fromOne)](#getPages-boolean-com.groupdocs.watermark.PagesSetup-int-int---boolean-) | Gets a list of selected pages based on the specified criteria. |
### PagesSelector() {#PagesSelector--}
```
public PagesSelector()
```


### getPages(boolean allPages, PagesSetup pagesSetup, int totalPages, System.Nullable<Integer> pageIndex) {#getPages-boolean-com.groupdocs.watermark.PagesSetup-int-com.aspose.ms.System.Nullable-java.lang.Integer--}
```
public static System.Collections.Generic.List<Integer> getPages(boolean allPages, PagesSetup pagesSetup, int totalPages, System.Nullable<Integer> pageIndex)
```


Gets a list of pages based on the specified setup.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| allPages | boolean | Whether to include all pages. |
| pagesSetup | [PagesSetup](../../com.groupdocs.watermark/pagessetup) | The pages setup configuration. |
| totalPages | int | The total number of pages. |
| pageIndex | com.aspose.ms.System.Nullable<java.lang.Integer> | The specific page index (starting with 0). |

**Returns:**
com.aspose.ms.System.Collections.Generic.List<java.lang.Integer> - A list of pages based on the specified setup.
### getPages(boolean allPages, PagesSetup pagesSetup, int totalPages, int[] pageNumbers, boolean fromOne) {#getPages-boolean-com.groupdocs.watermark.PagesSetup-int-int---boolean-}
```
public static System.Collections.Generic.List<Integer> getPages(boolean allPages, PagesSetup pagesSetup, int totalPages, int[] pageNumbers, boolean fromOne)
```


Gets a list of selected pages based on the specified criteria.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| allPages | boolean | A flag indicating whether to include all pages. |
| pagesSetup | [PagesSetup](../../com.groupdocs.watermark/pagessetup) | The setup configuration for pages. |
| totalPages | int | The total number of pages in the document. |
| pageNumbers | int[] | An array of specific page numbers to include. |
| fromOne | boolean |  |

**Returns:**
com.aspose.ms.System.Collections.Generic.List<java.lang.Integer> - A sorted and distinct list of selected page numbers.
