---
title: "ShapePossibleWatermark"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يمثل علامة مائية على شكل في محتوى أي تنسيق مدعوم."
type: docs
weight: 55
url: /ar/java/com.groupdocs.watermark.search/shapepossiblewatermark/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark), [com.groupdocs.watermark.search.TwoDObjectPossibleWatermark](../../com.groupdocs.watermark.search/twodobjectpossiblewatermark)
```
public abstract class ShapePossibleWatermark<T> extends TwoDObjectPossibleWatermark
```

يمثل علامة مائية على شكل في محتوى أي تنسيق مدعوم.


T
: نوع الشكل.

## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getRotateAngle()](#getRotateAngle--) | يحصل على زاوية دوران الشكل بالدرجات. |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | يحصل على مجموعة مقاطع النص المنسقة للشكل. |
|
|  | [getText()](#getText--) | يحصل على نص الشكل. |
|
|  | [setText(String value)](#setText-java.lang.String-) | يضبط نص الشكل. |
|
| [getImageInternally()](#getImageInternally--) |  |
| [remove()](#remove--) |  |
### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


يحصل على زاوية دوران الشكل بالدرجات.


**Returns:**
double - زاوية دوران الشكل بالدرجات.

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public FormattedTextFragmentCollection getFormattedTextFragments()
```


يحصل على مجموعة مقاطع النص المنسقة للشكل.


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of shape.

### getText() {#getText--}
```
public String getText()
```


يحصل على نص الشكل.


**Returns:**
java.lang.String - نص الشكل.

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


يضبط نص الشكل.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | java.lang.String | نص الشكل. |
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




