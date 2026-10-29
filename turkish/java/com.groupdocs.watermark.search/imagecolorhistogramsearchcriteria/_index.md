---
title: "ImageColorHistogramSearchCriteria"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "İçerikte görüntü bulmak için arama kriterlerini temsil eder."
type: docs
weight: 30
url: /tr/java/com.groupdocs.watermark.search/imagecolorhistogramsearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria), [com.groupdocs.watermark.search.PageSearchCriteria](../../com.groupdocs.watermark.search/pagesearchcriteria), [com.groupdocs.watermark.search.ImageSearchCriteria](../../com.groupdocs.watermark.search/imagesearchcriteria)
```
public class ImageColorHistogramSearchCriteria extends ImageSearchCriteria
```

İçerikte görüntü bulmak için arama kriterlerini temsil eder.

<br />

*** ** * ** ***

Bu arama ölçütü, görüntü benzerliğini hesaplamak için görüntü renk histogramlarını kullanır.

<br />


## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [ImageColorHistogramSearchCriteria(String filePath)](#ImageColorHistogramSearchCriteria-java.lang.String-) | Belirtilen dosya yolu ile `[ImageColorHistogramSearchCriteria](../../com.groupdocs.watermark.search/imagecolorhistogramsearchcriteria)` sınıfının yeni bir örneğini başlatır. |
|
|  | [ImageColorHistogramSearchCriteria(InputStream stream)](#ImageColorHistogramSearchCriteria-java.io.InputStream-) | Belirtilen akış ile `[ImageColorHistogramSearchCriteria](../../com.groupdocs.watermark.search/imagecolorhistogramsearchcriteria)` sınıfının yeni bir örneğini başlatır. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getBinsCount()](#getBinsCount--) | Renk histogramlarını oluşturmak için kullanılacak kutucuk sayısını alır. |
|
|  | [setBinsCount(byte value)](#setBinsCount-byte-) | Renk histogramlarını oluşturmak için kullanılacak kutucuk sayısını ayarlar. |
|
### ImageColorHistogramSearchCriteria(String filePath) {#ImageColorHistogramSearchCriteria-java.lang.String-}
```
public ImageColorHistogramSearchCriteria(String filePath)
```


Belirtilen dosya yolu ile `[ImageColorHistogramSearchCriteria](../../com.groupdocs.watermark.search/imagecolorhistogramsearchcriteria)` sınıfının yeni bir örneğini başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePath | java.lang.String | Görüntünün yükleneceği dosya yolu. |
|

### ImageColorHistogramSearchCriteria(InputStream stream) {#ImageColorHistogramSearchCriteria-java.io.InputStream-}
```
public ImageColorHistogramSearchCriteria(InputStream stream)
```


Belirtilen akış ile `[ImageColorHistogramSearchCriteria](../../com.groupdocs.watermark.search/imagecolorhistogramsearchcriteria)` sınıfının yeni bir örneğini başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | stream | java.io.InputStream | Görüntünün yükleneceği akış. |
|

### getBinsCount() {#getBinsCount--}
```
public final byte getBinsCount()
```


Renk histogramlarını oluşturmak için kullanılacak kutucuk sayısını alır.


**Returns:**
byte - Varsayılan değer 10'dur.

### setBinsCount(byte value) {#setBinsCount-byte-}
```
public final void setBinsCount(byte value)
```


Renk histogramlarını oluşturmak için kullanılacak kutucuk sayısını ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | byte | Varsayılan değer 10'dur. |
|

