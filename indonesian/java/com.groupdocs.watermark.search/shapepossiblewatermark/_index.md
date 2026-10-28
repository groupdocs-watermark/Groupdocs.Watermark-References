---
title: "ShapePossibleWatermark"
second_title: "Referensi API GroupDocs.Watermark untuk Java"
description: "Mewakili watermark bentuk dalam konten dari format apa pun yang didukung."
type: docs
weight: 55
url: /id/java/com.groupdocs.watermark.search/shapepossiblewatermark/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark), [com.groupdocs.watermark.search.TwoDObjectPossibleWatermark](../../com.groupdocs.watermark.search/twodobjectpossiblewatermark)
```
public abstract class ShapePossibleWatermark<T> extends TwoDObjectPossibleWatermark
```

Mewakili watermark bentuk dalam konten dari format apa pun yang didukung.


T
: Tipe bentuk.

## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getRotateAngle()](#getRotateAngle--) | Mendapatkan sudut rotasi bentuk dalam derajat. |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | Mendapatkan koleksi fragmen teks terformat dari bentuk. |
|
|  | [getText()](#getText--) | Mendapatkan teks bentuk. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Mengatur teks bentuk. |
|
| [getImageInternally()](#getImageInternally--) |  |
| [remove()](#remove--) |  |
### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


Mendapatkan sudut rotasi bentuk dalam derajat.


**Returns:**
double - Sudut rotasi bentuk dalam derajat.

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public FormattedTextFragmentCollection getFormattedTextFragments()
```


Mendapatkan koleksi fragmen teks terformat dari bentuk.


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of shape.

### getText() {#getText--}
```
public String getText()
```


Mendapatkan teks bentuk.


**Returns:**
java.lang.String - Teks bentuk.

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Mengatur teks bentuk.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | value | java.lang.String | Teks bentuk. |
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




