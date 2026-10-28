---
title: "AttachedImagePossibleWatermark"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "किसी भी समर्थित फ़ॉर्मेट की सामग्री में संलग्न छवि वॉटरमार्क का प्रतिनिधित्व करता है।"
type: docs
weight: 11
url: /hi/java/com.groupdocs.watermark.search/attachedimagepossiblewatermark/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark)
```
public abstract class AttachedImagePossibleWatermark<T> extends PossibleWatermark
```

किसी भी समर्थित फ़ॉर्मेट की सामग्री में संलग्न छवि वॉटरमार्क का प्रतिनिधित्व करता है।


T
: अटैचमेंट का प्रकार।

## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getParent()](#getParent--) | `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)` का पैरेंट प्राप्त करता है। |
|
|  | [getWidth()](#getWidth--) | `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)` की चौड़ाई प्राप्त करता है। |
|
|  | [getHeight()](#getHeight--) | `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)` की ऊँचाई प्राप्त करता है। |
|
|  | [getX()](#getX--) | `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)` का x-निर्देशांक प्राप्त करता है। |
|
|  | [getY()](#getY--) | `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)` का y-निर्देशांक प्राप्त करता है। |
|
|  | [getRotateAngle()](#getRotateAngle--) | `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)` का घूर्णन कोण डिग्री में प्राप्त करता है। |
|
|  | [getUnitOfMeasurement()](#getUnitOfMeasurement--) | इस `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)` की मापन इकाई `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` प्राप्त करता है। |
|
| [getImageInternally()](#getImageInternally--) |  |
| [remove()](#remove--) |  |
### getParent() {#getParent--}
```
public ContentPart getParent()
```


`[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)` का पैरेंट प्राप्त करता है।


**Returns:**
[ContentPart](../../com.groupdocs.watermark.contents/contentpart) - The parent of this `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)`.

### getWidth() {#getWidth--}
```
public double getWidth()
```


`[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)` की चौड़ाई प्राप्त करता है।


**Returns:**
double - इस `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)` की चौड़ाई।

### getHeight() {#getHeight--}
```
public double getHeight()
```


`[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)` की ऊँचाई प्राप्त करता है।


**Returns:**
double - इस `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)` की ऊँचाई।

### getX() {#getX--}
```
public double getX()
```


`[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)` का x-निर्देशांक प्राप्त करता है।


**Returns:**
double - इस `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)` का x-निर्देशांक।

### getY() {#getY--}
```
public double getY()
```


`[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)` का y-निर्देशांक प्राप्त करता है।


**Returns:**
double - इस `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)` का y-निर्देशांक।

### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


`[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)` का घूर्णन कोण डिग्री में प्राप्त करता है।


**Returns:**
double - इस `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)` का घुमाव कोण।

### getUnitOfMeasurement() {#getUnitOfMeasurement--}
```
public int getUnitOfMeasurement()
```


इस `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)` की मापन इकाई `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` प्राप्त करता है।


**Returns:**
int - इस `[AttachedImagePossibleWatermark](../../com.groupdocs.watermark.search/attachedimagepossiblewatermark)` का `[UnitOfMeasurement](../../com.groupdocs.watermark.common/unitofmeasurement)` माप इकाई।

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




