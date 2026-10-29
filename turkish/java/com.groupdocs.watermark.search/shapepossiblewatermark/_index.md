---
title: "ShapePossibleWatermark"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "Herhangi bir desteklenen formatın içeriğinde şekil filigranını temsil eder."
type: docs
weight: 55
url: /tr/java/com.groupdocs.watermark.search/shapepossiblewatermark/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark), [com.groupdocs.watermark.search.TwoDObjectPossibleWatermark](../../com.groupdocs.watermark.search/twodobjectpossiblewatermark)
```
public abstract class ShapePossibleWatermark<T> extends TwoDObjectPossibleWatermark
```

Herhangi bir desteklenen formatın içeriğinde şekil filigranını temsil eder.


T
: Şeklin tipi.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getRotateAngle()](#getRotateAngle--) | Şeklin derece cinsinden döndürme açısını alır. |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | Şeklin biçimlendirilmiş metin parçacıkları koleksiyonunu alır. |
|
|  | [getText()](#getText--) | Şeklin metnini alır. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Şeklin metnini ayarlar. |
|
| [getImageInternally()](#getImageInternally--) |  |
| [remove()](#remove--) |  |
### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


Şeklin derece cinsinden döndürme açısını alır.


**Returns:**
double - Şeklin derece cinsinden döndürme açısı.

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public FormattedTextFragmentCollection getFormattedTextFragments()
```


Şeklin biçimlendirilmiş metin parçacıkları koleksiyonunu alır.


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of shape.

### getText() {#getText--}
```
public String getText()
```


Şeklin metnini alır.


**Returns:**
java.lang.String - Şeklin metni.

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Şeklin metnini ayarlar.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | java.lang.String | Şeklin metni. |
|

### getImageInternally() {#getImageInternally--}
```
public WatermarkableImage getImageInternally()
```




**Returns:**
[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)
### remove() {#remove--}
```
public void remove()
```




