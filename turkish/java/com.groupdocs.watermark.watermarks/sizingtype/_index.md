---
title: "SizingType"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "Filigran boyutunun nasıl hesaplanması gerektiğini belirtir."
type: docs
weight: 16
url: /tr/java/com.groupdocs.watermark.watermarks/sizingtype/
---
**Inheritance:**
java.lang.Object
```
public final class SizingType
```

Filigran boyutunun nasıl hesaplanması gerektiğini belirtir.

## Alanlar

| Alan | Açıklama |
| --- | --- |
|  | [Auto](#Auto) | Filigran, içeriğine göre otomatik olarak boyutlandırılmalıdır. |
|
|  | [Absolute](#Absolute) | Filigran, tam bir `[Watermark.getWidth()](../../com.groupdocs.watermark/watermark#getWidth--)` boyutuna ayarlanmalıdır. |
ve `[Watermark.getHeight()](../../com.groupdocs.watermark/watermark#getHeight--)`.
|
|  | [ScaleToParentDimensions](#ScaleToParentDimensions) | Filigran, üst öğenin boyutlarına göre, aşağıdakini kullanarak ölçeklendirilmelidir. |
belirtilen `[Watermark.getScaleFactor()](../../com.groupdocs.watermark/watermark#getScaleFactor--)`.
|
|  | [ScaleToParentArea](#ScaleToParentArea) | Filigran, üst öğenin alanına göre, belirtilen `[Watermark.getScaleFactor()](../../com.groupdocs.watermark/watermark#getScaleFactor--)` kullanılarak ölçeklendirilmelidir. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [toString(int value)](#toString-int-) | `[SizingType](../../com.groupdocs.watermark.watermarks/sizingtype)` değerinin dize temsili döndürülür. |
|
|  | [parse(String value)](#parse-java.lang.String-) | Bir dizeyi `[SizingType](../../com.groupdocs.watermark.watermarks/sizingtype)` enum değerine ayrıştırır. |
|
### Auto {#Auto}
```
public static final int Auto
```


Filigran, içeriğine göre otomatik olarak boyutlandırılmalıdır.


### Absolute {#Absolute}
```
public static final int Absolute
```


Filigran, tam bir `[Watermark.getWidth()](../../com.groupdocs.watermark/watermark#getWidth--)` boyutuna ayarlanmalıdır.
ve `[Watermark.getHeight()](../../com.groupdocs.watermark/watermark#getHeight--)`.


### ScaleToParentDimensions {#ScaleToParentDimensions}
```
public static final int ScaleToParentDimensions
```


Filigran, üst öğenin boyutlarına göre, aşağıdakini kullanarak ölçeklendirilmelidir.
belirtilen `[Watermark.getScaleFactor()](../../com.groupdocs.watermark/watermark#getScaleFactor--)`.


### ScaleToParentArea {#ScaleToParentArea}
```
public static final int ScaleToParentArea
```


Filigran, üst öğenin alanına göre, belirtilen `[Watermark.getScaleFactor()](../../com.groupdocs.watermark/watermark#getScaleFactor--)` kullanılarak ölçeklendirilmelidir.


### toString(int value) {#toString-int-}
```
public static final String toString(int value)
```


`[SizingType](../../com.groupdocs.watermark.watermarks/sizingtype)` değerinin dize temsili döndürülür.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | int | Dönüştürülecek değer. |
|

**Returns:**
java.lang.String - `[SizingType](../../com.groupdocs.watermark.watermarks/sizingtype)` değerinin dize temsili.

### parse(String value) {#parse-java.lang.String-}
```
public static final int parse(String value)
```


Bir dizeyi `[SizingType](../../com.groupdocs.watermark.watermarks/sizingtype)` enum değerine ayrıştırır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | java.lang.String | Ayrıştırılacak dize. |
|

**Returns:**
int - `[SizingType](../../com.groupdocs.watermark.watermarks/sizingtype)` enum değeri.

