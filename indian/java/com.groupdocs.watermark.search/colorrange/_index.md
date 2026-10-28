---
title: "ColorRange"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "रंगों की एक रेंज का प्रतिनिधित्व करता है।"
type: docs
weight: 12
url: /hi/java/com.groupdocs.watermark.search/colorrange/
---
**Inheritance:**
java.lang.Object
```
public class ColorRange
```

रंगों की एक सीमा का प्रतिनिधित्व करता है। RGB रंग के HSB प्रतिनिधित्व का उपयोग करके सीमाएँ निर्दिष्ट करता है।

## निर्माताएँ

| निर्माता | विवरण |
| --- | --- |
|  | [ColorRange()](#ColorRange--) | नए `[ColorRange](../../com.groupdocs.watermark.search/colorrange)` क्लास का एक नया उदाहरण प्रारंभ करता है। |
|
|  | [ColorRange(Color exactColor)](#ColorRange-com.groupdocs.watermark.watermarks.Color-) | निर्दिष्ट सटीक रंग के साथ नए `[ColorRange](../../com.groupdocs.watermark.search/colorrange)` क्लास का एक नया उदाहरण प्रारंभ करता है। |
|
## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getMinHue()](#getMinHue--) | शुरुआती ह्यू मान डिग्री में प्राप्त करता है। |
|
|  | [setMinHue(float value)](#setMinHue-float-) | शुरुआती ह्यू मान डिग्री में सेट करता है। |
|
|  | [getMaxHue()](#getMaxHue--) | अंतिम ह्यू मान डिग्री में प्राप्त करता है। |
|
|  | [setMaxHue(float value)](#setMaxHue-float-) | अंतिम ह्यू मान डिग्री में सेट करता है। |
|
|  | [getMinSaturation()](#getMinSaturation--) | शुरुआती संतृप्ति मान प्राप्त करता है। |
|
|  | [setMinSaturation(float value)](#setMinSaturation-float-) | शुरुआती संतृप्ति मान सेट करता है। |
|
|  | [getMaxSaturation()](#getMaxSaturation--) | अंतिम संतृप्ति मान प्राप्त करता है। |
|
|  | [setMaxSaturation(float value)](#setMaxSaturation-float-) | अंतिम संतृप्ति मान सेट करता है। |
|
|  | [getMinBrightness()](#getMinBrightness--) | शुरुआती चमक मान प्राप्त करता है। |
|
|  | [setMinBrightness(float value)](#setMinBrightness-float-) | शुरुआती चमक मान सेट करता है। |
|
|  | [getMaxBrightness()](#getMaxBrightness--) | अंतिम चमक मान प्राप्त करता है। |
|
|  | [setMaxBrightness(float value)](#setMaxBrightness-float-) | अंतिम चमक मान सेट करता है। |
|
|  | [isEmpty()](#isEmpty--) | एक मान प्राप्त करता है जो दर्शाता है कि केवल खाली रंग सीमा में है या नहीं। |
|
|  | [setEmpty(boolean value)](#setEmpty-boolean-) | रेंज में केवल खाली रंग है या नहीं, यह दर्शाने के लिए मान सेट करता है। |
|
### ColorRange() {#ColorRange--}
```
public ColorRange()
```


नए `[ColorRange](../../com.groupdocs.watermark.search/colorrange)` क्लास का एक नया उदाहरण प्रारंभ करता है।


### ColorRange(Color exactColor) {#ColorRange-com.groupdocs.watermark.watermarks.Color-}
```
public ColorRange(Color exactColor)
```


निर्दिष्ट सटीक रंग के साथ नए `[ColorRange](../../com.groupdocs.watermark.search/colorrange)` क्लास का एक नया उदाहरण प्रारंभ करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | exactColor | [Color](../../com.groupdocs.watermark.watermarks/color) | रेंज जिस सटीक रंग से बनाई गई है। |
|

### getMinHue() {#getMinHue--}
```
public final float getMinHue()
```


शुरुआती ह्यू मान डिग्री में प्राप्त करता है।


**Returns:**
float - प्रारंभिक ह्यू मान, डिग्री में।

### setMinHue(float value) {#setMinHue-float-}
```
public final void setMinHue(float value)
```


शुरुआती ह्यू मान डिग्री में सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | float | प्रारंभिक ह्यू मान, डिग्री में। |
|

### getMaxHue() {#getMaxHue--}
```
public final float getMaxHue()
```


अंतिम ह्यू मान डिग्री में प्राप्त करता है।


**Returns:**
float - समाप्ति ह्यू मान, डिग्री में।

### setMaxHue(float value) {#setMaxHue-float-}
```
public final void setMaxHue(float value)
```


अंतिम ह्यू मान डिग्री में सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | float | समाप्ति ह्यू मान, डिग्री में। |
|

### getMinSaturation() {#getMinSaturation--}
```
public final float getMinSaturation()
```


शुरुआती संतृप्ति मान प्राप्त करता है।


**Returns:**
float - संतृप्ति 0.0 से 1.0 तक होती है, जहाँ 0.0 ग्रेस्केल है और 1.0 सबसे अधिक संतृप्त है।

### setMinSaturation(float value) {#setMinSaturation-float-}
```
public final void setMinSaturation(float value)
```


शुरुआती संतृप्ति मान सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | float | संतृप्ति 0.0 से 1.0 तक होती है, जहाँ 0.0 ग्रेस्केल है और 1.0 सबसे अधिक संतृप्त है। |
|

### getMaxSaturation() {#getMaxSaturation--}
```
public final float getMaxSaturation()
```


अंतिम संतृप्ति मान प्राप्त करता है।


**Returns:**
float - संतृप्ति 0.0 से 1.0 तक होती है, जहाँ 0.0 ग्रेस्केल है और 1.0 सबसे अधिक संतृप्त है।

### setMaxSaturation(float value) {#setMaxSaturation-float-}
```
public final void setMaxSaturation(float value)
```


अंतिम संतृप्ति मान सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | float | संतृप्ति 0.0 से 1.0 तक होती है, जहाँ 0.0 ग्रेस्केल है और 1.0 सबसे अधिक संतृप्त है। |
|

### getMinBrightness() {#getMinBrightness--}
```
public final float getMinBrightness()
```


शुरुआती चमक मान प्राप्त करता है।


**Returns:**
float - चमक 0.0 से 1.0 तक होती है, जहाँ 0.0 काला दर्शाता है और 1.0 सफेद दर्शाता है।

### setMinBrightness(float value) {#setMinBrightness-float-}
```
public final void setMinBrightness(float value)
```


शुरुआती चमक मान सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | float | चमक 0.0 से 1.0 तक होती है, जहाँ 0.0 काला दर्शाता है और 1.0 सफेद दर्शाता है। |
|

### getMaxBrightness() {#getMaxBrightness--}
```
public final float getMaxBrightness()
```


अंतिम चमक मान प्राप्त करता है।


**Returns:**
float - चमक 0.0 से 1.0 तक होती है, जहाँ 0.0 काला दर्शाता है और 1.0 सफेद दर्शाता है।

### setMaxBrightness(float value) {#setMaxBrightness-float-}
```
public final void setMaxBrightness(float value)
```


अंतिम चमक मान सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | float | चमक 0.0 से 1.0 तक होती है, जहाँ 0.0 काला दर्शाता है और 1.0 सफेद दर्शाता है। |
|

### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


एक मान प्राप्त करता है जो दर्शाता है कि केवल खाली रंग सीमा में है या नहीं।


**Returns:**
boolean - यदि रेंज में केवल खाली रंग है (HSB रेंज को अनदेखा किया जाता है) तो सत्य; अन्यथा असत्य।

### setEmpty(boolean value) {#setEmpty-boolean-}
```
public final void setEmpty(boolean value)
```


रेंज में केवल खाली रंग है या नहीं, यह दर्शाने के लिए मान सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | boolean | यदि रेंज में केवल खाली रंग है (HSB रेंज को अनदेखा किया जाता है) तो सत्य; अन्यथा असत्य। |
|

