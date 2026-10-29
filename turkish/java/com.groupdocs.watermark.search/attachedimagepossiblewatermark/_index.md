---
title: "AttachedImagePossibleWatermark"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "Herhangi bir desteklenen formatın içeriğinde ekli görüntü filigranını temsil eder."
type: docs
weight: 11
url: /tr/java/com.groupdocs.watermark.search/attachedimagepossiblewatermark/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)
```
public abstract class AttachedImagePossibleWatermark<T> extends PossibleWatermark
```

Herhangi bir desteklenen formatın içeriğinde ekli görüntü filigranını temsil eder.


T
: Ek'in türü.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getParent()](#getParent--) | Bu `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)` öğesinin üst öğesini alır. |
|
|  | [getWidth()](#getWidth--) | Bu `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)` öğesinin genişliğini alır. |
|
|  | [getHeight()](#getHeight--) | Bu `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)` öğesinin yüksekliğini alır. |
|
|  | [getX()](#getX--) | Bu `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)` öğesinin x-koordinatını alır. |
|
|  | [getY()](#getY--) | Bu `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)` öğesinin y koordinatını alır. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Bu `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)` öğesinin döndürme açısını derece cinsinden alır. |
|
|  | [getUnitOfMeasurement()](#getUnitOfMeasurement--) | Bu `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)` öğesinin ölçü birimini `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` alır. |
|
| [getImageInternally()](#getImageInternally--) |  |
| [remove()](#remove--) |  |
### getParent() {#getParent--}
```
public ContentPart getParent()
```


Bu `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)` öğesinin üst öğesini alır.


**Returns:**
[ContentPart](../../com.groupdocs.watermark.contents/contentpart) - The parent of this `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)`.

### getWidth() {#getWidth--}
```
public double getWidth()
```


Bu `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)` öğesinin genişliğini alır.


**Returns:**
double - Bu `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)` öğesinin genişliği.

### getHeight() {#getHeight--}
```
public double getHeight()
```


Bu `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)` öğesinin yüksekliğini alır.


**Returns:**
double - Bu `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)` öğesinin yüksekliği.

### getX() {#getX--}
```
public double getX()
```


Bu `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)` öğesinin x-koordinatını alır.


**Returns:**
double - Bu `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)` öğesinin x koordinatı.

### getY() {#getY--}
```
public double getY()
```


Bu `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)` öğesinin y koordinatını alır.


**Returns:**
double - Bu `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)` öğesinin y koordinatı.

### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


Bu `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)` öğesinin döndürme açısını derece cinsinden alır.


**Returns:**
double - Bu `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)` öğesinin döndürme açısı.

### getUnitOfMeasurement() {#getUnitOfMeasurement--}
```
public int getUnitOfMeasurement()
```


Bu `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)` öğesinin ölçü birimini `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` alır.


**Returns:**
int - Bu `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)` öğesinin ölçü birimi `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)`.

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




