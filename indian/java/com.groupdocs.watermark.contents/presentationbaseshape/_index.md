---
title: "PresentationBaseShape"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "PowerPoint दस्तावेज़ में सभी प्रकार के आकारों के लिए सारभूत बेस क्लास प्रदान करता है।"
type: docs
weight: 77
url: /hi/java/com.groupdocs.watermark.contents/presentationbaseshape/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.ITwoDObject](../../com.groupdocs.watermark.search/itwodobject), [com.groupdocs.watermark.contents.IPresentationHyperlinkContainer](../../com.groupdocs.watermark.contents/ipresentationhyperlinkcontainer)
```
public abstract class PresentationBaseShape extends ShapeSearchAdapter implements ITwoDObject, IPresentationHyperlinkContainer
```

PowerPoint दस्तावेज़ में सभी प्रकार के आकारों के लिए सारभूत बेस क्लास प्रदान करता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getPresentation()](#getPresentation--) | इस `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` की पैरेंट प्रस्तुति प्राप्त करता है। |
|
|  | [getImageFillFormat()](#getImageFillFormat--) | इस `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` की इमेज फ़िल फ़ॉर्मेट सेटिंग्स प्राप्त करता है। |
|
|  | [getName()](#getName--) | इस `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` का नाम प्राप्त करता है। |
|
|  | [getAlternativeText()](#getAlternativeText--) | इस `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` से जुड़ा वर्णनात्मक (वैकल्पिक) टेक्स्ट प्राप्त करता है। |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | इस `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` से जुड़ा वर्णनात्मक (वैकल्पिक) टेक्स्ट सेट करता है। |
|
|  | [getId()](#getId--) | इस `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` की पहचानकर्ता प्राप्त करता है। |
|
|  | [getZOrderPosition()](#getZOrderPosition--) | z-ऑर्डर में इस `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` की स्थिति प्राप्त करता है। |
|
|  | [getHyperlink(int actionType)](#getHyperlink-int-) | इस `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` से जुड़ा हाइपरलिंक प्राप्त करता है। |
|
|  | [setHyperlink(int actionType, String url)](#setHyperlink-int-java.lang.String-) | इस `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` से जुड़ा हाइपरलिंक सेट करता है। |
|
|  | [getX()](#getX--) | प्रेजेंटेशन के बाएँ बॉर्डर से इस `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` का क्षैतिज ऑफ़सेट पॉइंट्स में प्राप्त करता है। |
|
|  | [setX(double value)](#setX-double-) | प्रेजेंटेशन के बाएँ बॉर्डर से इस `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` का क्षैतिज ऑफ़सेट पॉइंट्स में सेट करता है। |
|
|  | [getY()](#getY--) | प्रेजेंटेशन के शीर्ष बॉर्डर से इस `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` का ऊर्ध्वाधर ऑफ़सेट पॉइंट्स में प्राप्त या सेट करता है। |
|
|  | [setY(double value)](#setY-double-) | प्रेजेंटेशन के शीर्ष बॉर्डर से इस `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` का ऊर्ध्वाधर ऑफ़सेट पॉइंट्स में प्राप्त या सेट करता है। |
|
|  | [getWidth()](#getWidth--) | इस `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` की चौड़ाई पॉइंट्स में प्राप्त करता है। |
|
|  | [setWidth(double value)](#setWidth-double-) | इस `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` की चौड़ाई पॉइंट्स में सेट करता है। |
|
|  | [getHeight()](#getHeight--) | इस `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` की ऊँचाई पॉइंट्स में प्राप्त करता है। |
|
|  | [setHeight(double value)](#setHeight-double-) | इस `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` की ऊँचाई पॉइंट्स में सेट करता है। |
|
### getPresentation() {#getPresentation--}
```
public final PresentationBaseSlide getPresentation()
```


इस `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` की पैरेंट प्रस्तुति प्राप्त करता है।


**Returns:**
[PresentationBaseSlide](../../com.groupdocs.watermark.contents/presentationbaseslide) - The parent presentation of this `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.

### getImageFillFormat() {#getImageFillFormat--}
```
public final PresentationImageFillFormat getImageFillFormat()
```


इस `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` की इमेज फ़िल फ़ॉर्मेट सेटिंग्स प्राप्त करता है।


**Returns:**
[PresentationImageFillFormat](../../com.groupdocs.watermark.contents/presentationimagefillformat) - The image fill format settings of this `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)`.

### getName() {#getName--}
```
public final String getName()
```


इस `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` का नाम प्राप्त करता है।


**Returns:**
java.lang.String - इस `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` का नाम।

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


इस `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` से जुड़ा वर्णनात्मक (वैकल्पिक) टेक्स्ट प्राप्त करता है।


**Returns:**
java.lang.String - इस `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` से जुड़ा वर्णनात्मक (वैकल्पिक) टेक्स्ट।

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


इस `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` से जुड़ा वर्णनात्मक (वैकल्पिक) टेक्स्ट सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | java.lang.String | इस `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` से जुड़ा वर्णनात्मक (वैकल्पिक) टेक्स्ट। |
|

### getId() {#getId--}
```
public final long getId()
```


इस `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` की पहचानकर्ता प्राप्त करता है।


**Returns:**
long - इस `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` की पहचानकर्ता।

### getZOrderPosition() {#getZOrderPosition--}
```
public final int getZOrderPosition()
```


z-ऑर्डर में इस `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` की स्थिति प्राप्त करता है।

उच्च z-ऑर्डर वाला आकार हमेशा कम z-ऑर्डर वाले आकार के सामने रहता है।


**Returns:**
int - इस `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` की z-ऑर्डर में स्थिति।

### getHyperlink(int actionType) {#getHyperlink-int-}
```
public final String getHyperlink(int actionType)
```


इस `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` से जुड़ा हाइपरलिंक प्राप्त करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | actionType | int | हाइपरलिंक को सक्रिय करने वाली क्रिया। |
|

**Returns:**
java.lang.String - निर्दिष्ट क्रिया पर सक्रिय होने वाली हाइपरलिंक का URL।

### setHyperlink(int actionType, String url) {#setHyperlink-int-java.lang.String-}
```
public final void setHyperlink(int actionType, String url)
```


इस `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` से जुड़ा हाइपरलिंक सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | actionType | int | हाइपरलिंक को सक्रिय करने वाली क्रिया। |
|
|  | URL | java.lang.String | हाइपरलिंक URL। |
|

### getX() {#getX--}
```
public final double getX()
```


प्रेजेंटेशन के बाएँ बॉर्डर से इस `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` का क्षैतिज ऑफ़सेट पॉइंट्स में प्राप्त करता है।


**Returns:**
double - इस `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` का x-निर्देशांक।

### setX(double value) {#setX-double-}
```
public final void setX(double value)
```


प्रेजेंटेशन के बाएँ बॉर्डर से इस `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` का क्षैतिज ऑफ़सेट पॉइंट्स में सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | double | इस `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` का x-निर्देशांक। |
|

### getY() {#getY--}
```
public final double getY()
```


प्रेजेंटेशन के शीर्ष बॉर्डर से इस `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` का ऊर्ध्वाधर ऑफ़सेट पॉइंट्स में प्राप्त या सेट करता है।


**Returns:**
double - इस `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` का y-निर्देशांक।

### setY(double value) {#setY-double-}
```
public final void setY(double value)
```


प्रेजेंटेशन के शीर्ष बॉर्डर से इस `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` का ऊर्ध्वाधर ऑफ़सेट पॉइंट्स में प्राप्त या सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | double | इस `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` का y-निर्देशांक। |
|

### getWidth() {#getWidth--}
```
public final double getWidth()
```


इस `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` की चौड़ाई पॉइंट्स में प्राप्त करता है।


**Returns:**
double - इस `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` की चौड़ाई पॉइंट्स में।

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


इस `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` की चौड़ाई पॉइंट्स में सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | double | इस `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` की चौड़ाई पॉइंट्स में। |
|

### getHeight() {#getHeight--}
```
public final double getHeight()
```


इस `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` की ऊँचाई पॉइंट्स में प्राप्त करता है।


**Returns:**
double - इस `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` की ऊँचाई पॉइंट्स में।

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


इस `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` की ऊँचाई पॉइंट्स में सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | double | इस `[PresentationBaseShape](../../com.groupdocs.watermark.contents/presentationbaseshape)` की ऊँचाई पॉइंट्स में। |
|

