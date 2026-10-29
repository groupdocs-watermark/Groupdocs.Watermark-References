---
title: "PagesSelector"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: 
type: docs
weight: 10
url: /tr/java/com.groupdocs.watermark/pagesselector/
---
**Inheritance:**
java.lang.Object
```
public class PagesSelector
```

<br />


## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PagesSelector()](#PagesSelector--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getPages(boolean allPages, PagesSetup pagesSetup, int totalPages, System.Nullable<Integer> pageIndex)](#getPages-boolean-com.groupdocs.watermark.PagesSetup-int-com.aspose.ms.System.Nullable-java.lang.Integer--) | Belirtilen kurulum temelinde sayfaların bir listesini alır. |
|
|  | [getPages(boolean allPages, PagesSetup pagesSetup, int totalPages, int[] pageNumbers, boolean fromOne)](#getPages-boolean-com.groupdocs.watermark.PagesSetup-int-int---boolean-) | Belirtilen kriterlere göre seçilen sayfaların bir listesini alır. |
|
### PagesSelector() {#PagesSelector--}
```
public PagesSelector()
```


### getPages(boolean allPages, PagesSetup pagesSetup, int totalPages, System.Nullable<Integer> pageIndex) {#getPages-boolean-com.groupdocs.watermark.PagesSetup-int-com.aspose.ms.System.Nullable-java.lang.Integer--}
```
public static System.Collections.Generic.List<Integer> getPages(boolean allPages, PagesSetup pagesSetup, int totalPages, System.Nullable<Integer> pageIndex)
```


Belirtilen kurulum temelinde sayfaların bir listesini alır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | allPages | boolean | Tüm sayfaları dahil edip etmeyeceği. |
|
|  | pagesSetup | [PagesSetup](../../com.groupdocs.watermark/pagessetup) | Sayfa kurulum yapılandırması. |
|
|  | totalPages | int | Toplam sayfa sayısı. |
|
|  | pageIndex | com.aspose.ms.System.Nullable<java.lang.Integer> | Belirli sayfa indeksi (0'dan başlayarak). |
|

**Returns:**
com.aspose.ms.System.Collections.Generic.List<java.lang.Integer> - Belirtilen kurulum temelinde sayfaların bir listesi.

### getPages(boolean allPages, PagesSetup pagesSetup, int totalPages, int[] pageNumbers, boolean fromOne) {#getPages-boolean-com.groupdocs.watermark.PagesSetup-int-int---boolean-}
```
public static System.Collections.Generic.List<Integer> getPages(boolean allPages, PagesSetup pagesSetup, int totalPages, int[] pageNumbers, boolean fromOne)
```


Belirtilen kriterlere göre seçilen sayfaların bir listesini alır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | allPages | boolean | Tüm sayfaları dahil edip etmeyeceğini gösteren bir bayrak. |
|
|  | pagesSetup | [PagesSetup](../../com.groupdocs.watermark/pagessetup) | Sayfalar için kurulum yapılandırması. |
|
|  | totalPages | int | Belge içindeki toplam sayfa sayısı. |
|
|  | pageNumbers | int[] | Dahil edilecek belirli sayfa numaralarının bir dizisi. |
|
| fromOne | boolean |  |

**Returns:**
com.aspose.ms.System.Collections.Generic.List<java.lang.Integer> - Seçilen sayfa numaralarının sıralı ve benzersiz bir listesi.

