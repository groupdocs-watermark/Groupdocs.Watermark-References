---
title: "PagesSelector"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: 
type: docs
weight: 10
url: /ar/java/com.groupdocs.watermark/pagesselector/
---
**Inheritance:**
java.lang.Object
```
public class PagesSelector
```

<br />


## المنشئات

| منشئ | الوصف |
| --- | --- |
| [PagesSelector()](#PagesSelector--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getPages(boolean allPages, PagesSetup pagesSetup, int totalPages, System.Nullable<Integer> pageIndex)](#getPages-boolean-com.groupdocs.watermark.PagesSetup-int-com.aspose.ms.System.Nullable-java.lang.Integer--) | يحصل على قائمة بالصفحات بناءً على الإعداد المحدد. |
|
|  | [getPages(boolean allPages, PagesSetup pagesSetup, int totalPages, int[] pageNumbers, boolean fromOne)](#getPages-boolean-com.groupdocs.watermark.PagesSetup-int-int---boolean-) | يحصل على قائمة بالصفحات المحددة بناءً على المعايير المحددة. |
|
### PagesSelector() {#PagesSelector--}
```
public PagesSelector()
```


### getPages(boolean allPages, PagesSetup pagesSetup, int totalPages, System.Nullable<Integer> pageIndex) {#getPages-boolean-com.groupdocs.watermark.PagesSetup-int-com.aspose.ms.System.Nullable-java.lang.Integer--}
```
public static System.Collections.Generic.List<Integer> getPages(boolean allPages, PagesSetup pagesSetup, int totalPages, System.Nullable<Integer> pageIndex)
```


يحصل على قائمة بالصفحات بناءً على الإعداد المحدد.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | allPages | boolean | ما إذا كان يجب تضمين جميع الصفحات. |
|
|  | pagesSetup | [PagesSetup](../../com.groupdocs.watermark/pagessetup) | تكوين إعداد الصفحات. |
|
|  | totalPages | int | العدد الإجمالي للصفحات. |
|
|  | pageIndex | com.aspose.ms.System.Nullable<java.lang.Integer> | فهرس الصفحة المحددة (يبدأ من 0). |
|

**Returns:**
com.aspose.ms.System.Collections.Generic.List<java.lang.Integer> - قائمة بالصفحات بناءً على الإعداد المحدد.

### getPages(boolean allPages, PagesSetup pagesSetup, int totalPages, int[] pageNumbers, boolean fromOne) {#getPages-boolean-com.groupdocs.watermark.PagesSetup-int-int---boolean-}
```
public static System.Collections.Generic.List<Integer> getPages(boolean allPages, PagesSetup pagesSetup, int totalPages, int[] pageNumbers, boolean fromOne)
```


يحصل على قائمة بالصفحات المحددة بناءً على المعايير المحددة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | allPages | boolean | علامة تشير إلى ما إذا كان يجب تضمين جميع الصفحات. |
|
|  | pagesSetup | [PagesSetup](../../com.groupdocs.watermark/pagessetup) | تكوين الإعداد للصفحات. |
|
|  | totalPages | int | العدد الإجمالي للصفحات في المستند. |
|
|  | pageNumbers | int[] | مصفوفة من أرقام الصفحات المحددة لتضمينها. |
|
| fromOne | boolean |  |

**Returns:**
com.aspose.ms.System.Collections.Generic.List<java.lang.Integer> - قائمة مرتبة ومتميزة بأرقام الصفحات المحددة.

