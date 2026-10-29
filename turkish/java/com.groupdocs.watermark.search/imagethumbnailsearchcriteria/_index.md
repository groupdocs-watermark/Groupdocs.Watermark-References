---
title: "ImageThumbnailSearchCriteria"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "İçerikte görüntü bulmak için arama kriterlerini temsil eder."
type: docs
weight: 33
url: /tr/java/com.groupdocs.watermark.search/imagethumbnailsearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria), [com.groupdocs.watermark.search.PageSearchCriteria](../../com.groupdocs.watermark.search/pagesearchcriteria), [com.groupdocs.watermark.search.ImageSearchCriteria](../../com.groupdocs.watermark.search/imagesearchcriteria)
```
public class ImageThumbnailSearchCriteria extends ImageSearchCriteria
```

İçerikte görüntü bulmak için arama kriterlerini temsil eder.

<br />

*** ** * ** ***

Bu arama kriteri, görüntü benzerliğini hesaplamak için ikilileştirilmiş görüntü küçük resmi kullanır.

<br />


## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [ImageThumbnailSearchCriteria(String filePath)](#ImageThumbnailSearchCriteria-java.lang.String-) | Belirtilen dosya yolu ile yeni bir `[ImageThumbnailSearchCriteria](../../com.groupdocs.watermark.search/imagethumbnailsearchcriteria)` sınıf örneği başlatır. |
|
|  | [ImageThumbnailSearchCriteria(InputStream stream)](#ImageThumbnailSearchCriteria-java.io.InputStream-) | Belirtilen akış ile yeni bir `[ImageThumbnailSearchCriteria](../../com.groupdocs.watermark.search/imagethumbnailsearchcriteria)` sınıf örneği başlatır. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getThumbnailSize()](#getThumbnailSize--) | Küçük resim boyutunu alır. |
|
|  | [setThumbnailSize(byte value)](#setThumbnailSize-byte-) | Küçük resim boyutunu ayarlar. |
|
### ImageThumbnailSearchCriteria(String filePath) {#ImageThumbnailSearchCriteria-java.lang.String-}
```
public ImageThumbnailSearchCriteria(String filePath)
```


Belirtilen dosya yolu ile yeni bir `[ImageThumbnailSearchCriteria](../../com.groupdocs.watermark.search/imagethumbnailsearchcriteria)` sınıf örneği başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePath | java.lang.String | Görüntünün yükleneceği dosya yolu. |
|

### ImageThumbnailSearchCriteria(InputStream stream) {#ImageThumbnailSearchCriteria-java.io.InputStream-}
```
public ImageThumbnailSearchCriteria(InputStream stream)
```


Belirtilen akış ile yeni bir `[ImageThumbnailSearchCriteria](../../com.groupdocs.watermark.search/imagethumbnailsearchcriteria)` sınıf örneği başlatır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | stream | java.io.InputStream | Görüntünün yükleneceği akış. |
|

### getThumbnailSize() {#getThumbnailSize--}
```
public final byte getThumbnailSize()
```


Küçük resim boyutunu alır.


**Returns:**
byte - Varsayılan olarak 32X32 küçük resim kullanılacaktır.

### setThumbnailSize(byte value) {#setThumbnailSize-byte-}
```
public final void setThumbnailSize(byte value)
```


Küçük resim boyutunu ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | byte | Varsayılan olarak 32X32 küçük resim kullanılacaktır. |
|

