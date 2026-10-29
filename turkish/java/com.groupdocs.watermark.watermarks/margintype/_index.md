---
title: "MarginType"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "Kenar boşluğu değerlerinin nasıl yorumlanması gerektiğini belirtir."
type: docs
weight: 14
url: /tr/java/com.groupdocs.watermark.watermarks/margintype/
---
**Inheritance:**
java.lang.Object
```
public final class MarginType
```

Kenar boşluğu değerlerinin nasıl yorumlanması gerektiğini belirtir.

## Alanlar

| Alan | Açıklama |
| --- | --- |
|  | [Absolute](#Absolute) | İçerik birimlerinde ölçülen kenar boşluğu değeri. |
|
|  | [RelativeToParentDimensions](#RelativeToParentDimensions) | Kenar boşluğu değeri, uygun üst öğe boyutunun bir bölümü olarak yorumlanmalıdır. |
|
|  | [RelativeToParentMinDimension](#RelativeToParentMinDimension) | Kenar boşluğu değeri, üst öğenin minimum boyutunun bir bölümü olarak yorumlanmalıdır. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [toString(int value)](#toString-int-) | `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)` değerinin dize temsilini döndürür. |
|
|  | [parse(String value)](#parse-java.lang.String-) | Bir dizeyi `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)` enum değerine ayrıştırır. |
|
### Absolute {#Absolute}
```
public static final int Absolute
```


İçerik birimlerinde ölçülen kenar boşluğu değeri.


### RelativeToParentDimensions {#RelativeToParentDimensions}
```
public static final int RelativeToParentDimensions
```


Kenar boşluğu değeri, uygun üst öğe boyutunun bir bölümü olarak yorumlanmalıdır.


Sol ve sağ kenar boşlukları üst öğenin genişliğine göre relasyondur,
üst ve alt kenar boşlukları üst öğenin yüksekliğine göre relasyondur.
Bu tip seçilirse, kenar boşluğu değeri 0.0 ile 1.0 arasında olmalıdır.


### RelativeToParentMinDimension {#RelativeToParentMinDimension}
```
public static final int RelativeToParentMinDimension
```


Kenar boşluğu değeri, üst öğenin minimum boyutunun bir bölümü olarak yorumlanmalıdır.


Bu tip seçilirse, kenar boşluğu değeri 0.0 ile 1.0 arasında olmalıdır.


### toString(int value) {#toString-int-}
```
public static final String toString(int value)
```


`[MarginType](../../com.groupdocs.watermark.watermarks/margintype)` değerinin dize temsilini döndürür.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | int | Dönüştürülecek değer. |
|

**Returns:**
java.lang.String - `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)` değerinin dize temsili.

### parse(String value) {#parse-java.lang.String-}
```
public static final int parse(String value)
```


Bir dizeyi `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)` enum değerine ayrıştırır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | java.lang.String | Ayrıştırılacak dize. |
|

**Returns:**
int - `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)` enum değeri.

