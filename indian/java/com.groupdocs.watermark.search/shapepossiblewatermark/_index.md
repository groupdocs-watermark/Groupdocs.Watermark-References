---
title: "ShapePossibleWatermark"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "किसी भी समर्थित फ़ॉर्मेट की सामग्री में आकार वॉटरमार्क का प्रतिनिधित्व करता है।"
type: docs
weight: 55
url: /hi/java/com.groupdocs.watermark.search/shapepossiblewatermark/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark), [com.groupdocs.watermark.search.TwoDObjectPossibleWatermark](../../com.groupdocs.watermark.search/twodobjectpossiblewatermark)
```
public abstract class ShapePossibleWatermark<T> extends TwoDObjectPossibleWatermark
```

किसी भी समर्थित फ़ॉर्मेट की सामग्री में आकार वॉटरमार्क का प्रतिनिधित्व करता है।


T
: आकार का प्रकार।

## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getRotateAngle()](#getRotateAngle--) | आकार का घूर्णन कोण डिग्री में प्राप्त करता है। |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | आकार के स्वरूपित टेक्स्ट फ्रैगमेंट्स का संग्रह प्राप्त करता है। |
|
|  | [getText()](#getText--) | आकार का टेक्स्ट प्राप्त करता है। |
|
|  | [setText(String value)](#setText-java.lang.String-) | आकार का टेक्स्ट सेट करता है। |
|
| [getImageInternally()](#getImageInternally--) |  |
| [remove()](#remove--) |  |
### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


आकार का घूर्णन कोण डिग्री में प्राप्त करता है।


**Returns:**
double - आकार का घूर्णन कोण डिग्री में।

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public FormattedTextFragmentCollection getFormattedTextFragments()
```


आकार के स्वरूपित टेक्स्ट फ्रैगमेंट्स का संग्रह प्राप्त करता है।


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of shape.

### getText() {#getText--}
```
public String getText()
```


आकार का टेक्स्ट प्राप्त करता है।


**Returns:**
java.lang.String - आकार का टेक्स्ट।

### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


आकार का टेक्स्ट सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | java.lang.String | आकार का टेक्स्ट। |
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




