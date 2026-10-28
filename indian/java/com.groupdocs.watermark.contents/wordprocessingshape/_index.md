---
title: "WordProcessingShape"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "Word दस्तावेज़ में एक ड्राइंग आकार को दर्शाता है।"
type: docs
weight: 141
url: /hi/java/com.groupdocs.watermark.contents/wordprocessingshape/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.IRotatableTwoDObject](../../com.groupdocs.watermark.search/irotatabletwodobject), [com.groupdocs.watermark.search.IHyperlinkContainer](../../com.groupdocs.watermark.search/ihyperlinkcontainer)
```
public class WordProcessingShape extends ShapeSearchAdapter implements IRotatableTwoDObject, IHyperlinkContainer
```

Word दस्तावेज़ में एक ड्राइंग आकार को दर्शाता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getSection()](#getSection--) | इस `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` का पैरेंट सेक्शन प्राप्त करता है। |
|
|  | [getHeaderFooter()](#getHeaderFooter--) | यदि मौजूद हो तो इस `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` का पैरेंट हेडर/फ़ूटर प्राप्त करता है। |
|
|  | [getShapeType()](#getShapeType--) | शेप प्रकार प्राप्त करता है। |
|
|  | [isWordArt()](#isWordArt--) | यह पता लगाने के लिए मान प्राप्त करता है कि यह `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` WordArt ऑब्जेक्ट है या नहीं। |
|
|  | [getAlternativeText()](#getAlternativeText--) | इस `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` से जुड़ा वर्णनात्मक (वैकल्पिक) टेक्स्ट प्राप्त करता है। |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | इस `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` से जुड़ा वर्णनात्मक (वैकल्पिक) टेक्स्ट सेट करता है। |
|
|  | [getName()](#getName--) | इस `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` का नाम प्राप्त करता है। |
|
|  | [getBehindText()](#getBehindText--) | शेप टेक्स्ट के ऊपर या पीछे है यह दर्शाने वाला मान प्राप्त करता है। |
|
|  | [setBehindText(boolean value)](#setBehindText-boolean-) | शेप टेक्स्ट के ऊपर या पीछे है यह दर्शाने वाला मान सेट करता है। |
|
|  | [getText()](#getText--) | इस `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` का टेक्स्ट प्राप्त करता है। |
|
|  | [setText(String value)](#setText-java.lang.String-) | इस `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` का टेक्स्ट सेट करता है। |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | इस `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` के फॉर्मेटेड टेक्स्ट फ्रैगमेंट्स का संग्रह प्राप्त करता है। |
|
|  | [getImage()](#getImage--) | इस `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` की इमेज प्राप्त करता है। |
|
|  | [setImage(WordProcessingWatermarkableImage value)](#setImage-com.groupdocs.watermark.contents.WordProcessingWatermarkableImage-) | इस `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` की इमेज सेट करता है। |
|
|  | [getHorizontalAlignment()](#getHorizontalAlignment--) | शेप क्षैतिज रूप से कैसे स्थित है यह निर्दिष्ट करने वाला मान प्राप्त करता है। |
|
|  | [getVerticalAlignment()](#getVerticalAlignment--) | शेप लंबवत रूप से कैसे स्थित है यह निर्दिष्ट करने वाला मान प्राप्त करता है। |
|
|  | [getRelativeHorizontalPosition()](#getRelativeHorizontalPosition--) | शेप क्षैतिज रूप से किस पर स्थित है यह निर्दिष्ट करने वाला मान प्राप्त करता है। |
|
|  | [getRelativeVerticalPosition()](#getRelativeVerticalPosition--) | शेप लंबवत रूप से किस पर स्थित है यह निर्दिष्ट करने वाला मान प्राप्त करता है। |
|
| [getImageFillFormat()](#getImageFillFormat--) |  |
| [getAsposeWordsShape()](#getAsposeWordsShape--) |  |
|  | [getHyperlink()](#getHyperlink--) | इस `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` से जुड़ा हाइपरलिंक प्राप्त करता है। |
|
|  | [setHyperlink(String value)](#setHyperlink-java.lang.String-) | इस `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` से जुड़ा हाइपरलिंक सेट करता है। |
|
|  | [getWidth()](#getWidth--) | इस `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` की चौड़ाई पॉइंट्स में प्राप्त करता है। |
|
|  | [setWidth(double value)](#setWidth-double-) | इस `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` की चौड़ाई पॉइंट्स में सेट करता है। |
|
|  | [getHeight()](#getHeight--) | इस `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` की ऊँचाई पॉइंट्स में प्राप्त करता है। |
|
|  | [setHeight(double value)](#setHeight-double-) | इस `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` की ऊँचाई पॉइंट्स में सेट करता है। |
|
|  | [getRotateAngle()](#getRotateAngle--) | इस `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` का घुमाव कोण डिग्री में प्राप्त करता है। |
|
|  | [setRotateAngle(double value)](#setRotateAngle-double-) | इस `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` का घुमाव कोण डिग्री में सेट करता है। |
|
|  | [getX()](#getX--) | इस `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` का पृष्ठ बाएँ किनारे से क्षैतिज ऑफ़सेट पॉइंट्स में प्राप्त या सेट करता है। |
|
|  | [setX(double value)](#setX-double-) | इस `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` का पृष्ठ बाएँ किनारे से क्षैतिज ऑफ़सेट पॉइंट्स में प्राप्त या सेट करता है। |
|
|  | [getY()](#getY--) | इस `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` का पृष्ठ शीर्ष किनारे से लंबवत ऑफ़सेट पॉइंट्स में प्राप्त करता है। |
|
|  | [setY(double value)](#setY-double-) | इस `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` का पृष्ठ शीर्ष किनारे से लंबवत ऑफ़सेट पॉइंट्स में सेट करता है। |
|
| [getFormattedTextFragmentsForSearch()](#getFormattedTextFragmentsForSearch--) |  |
| [getTextForSearch()](#getTextForSearch--) |  |
| [setFoundWatermarkText(String value)](#setFoundWatermarkText-java.lang.String-) |  |
| [getImageForSearch()](#getImageForSearch--) |  |
| [setFoundWatermarkImage(byte[] imageData)](#setFoundWatermarkImage-byte---) |  |
### getSection() {#getSection--}
```
public final WordProcessingSection getSection()
```


इस `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` का पैरेंट सेक्शन प्राप्त करता है।


**Returns:**
[WordProcessingSection](../../com.groupdocs.watermark.contents/wordprocessingsection) - The parent section of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### getHeaderFooter() {#getHeaderFooter--}
```
public final WordProcessingHeaderFooter getHeaderFooter()
```


यदि मौजूद हो तो इस `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` का पैरेंट हेडर/फ़ूटर प्राप्त करता है।


**Returns:**
[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter) - The parent header/footer of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### getShapeType() {#getShapeType--}
```
public final int getShapeType()
```


शेप प्रकार प्राप्त करता है।


**Returns:**
int - आकार का प्रकार।

### isWordArt() {#isWordArt--}
```
public final boolean isWordArt()
```


यह पता लगाने के लिए मान प्राप्त करता है कि यह `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` WordArt ऑब्जेक्ट है या नहीं।


**Returns:**
boolean - यदि आकार WordArt ऑब्जेक्ट है तो true; अन्यथा false।

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


इस `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` से जुड़ा वर्णनात्मक (वैकल्पिक) टेक्स्ट प्राप्त करता है।


**Returns:**
java.lang.String - इस `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` से जुड़ा वर्णनात्मक (वैकल्पिक) पाठ।

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


इस `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` से जुड़ा वर्णनात्मक (वैकल्पिक) टेक्स्ट सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | java.lang.String | इस `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` से जुड़ा वर्णनात्मक (वैकल्पिक) पाठ। |
|

### getName() {#getName--}
```
public final String getName()
```


इस `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` का नाम प्राप्त करता है।


**Returns:**
java.lang.String - इस `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` का नाम।

### getBehindText() {#getBehindText--}
```
public final boolean getBehindText()
```


शेप टेक्स्ट के ऊपर या पीछे है यह दर्शाने वाला मान प्राप्त करता है।


**Returns:**
boolean - वह मान जो दर्शाता है कि आकार पाठ के ऊपर है या पीछे। यदि आकार पाठ के पीछे है तो true; अन्यथा false।

### setBehindText(boolean value) {#setBehindText-boolean-}
```
public final void setBehindText(boolean value)
```


शेप टेक्स्ट के ऊपर या पीछे है यह दर्शाने वाला मान सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | boolean | वह मान जो दर्शाता है कि आकार पाठ के ऊपर है या पीछे। यदि आकार पाठ के पीछे है तो true; अन्यथा false। |
|

### getText() {#getText--}
```
public final String getText()
```


इस `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` का टेक्स्ट प्राप्त करता है।


**Returns:**
java.lang.String - इस `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` का पाठ।

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


इस `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` का टेक्स्ट सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | java.lang.String | इस `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` का पाठ। |
|

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public final FormattedTextFragmentCollection getFormattedTextFragments()
```


इस `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` के फॉर्मेटेड टेक्स्ट फ्रैगमेंट्स का संग्रह प्राप्त करता है।


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)`.

### getImage() {#getImage--}
```
public final WordProcessingWatermarkableImage getImage()
```


इस `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` की इमेज प्राप्त करता है।


**Returns:**
[WordProcessingWatermarkableImage](../../com.groupdocs.watermark.contents/wordprocessingwatermarkableimage) - The image of this `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` or `null` if the shape has no image.

### setImage(WordProcessingWatermarkableImage value) {#setImage-com.groupdocs.watermark.contents.WordProcessingWatermarkableImage-}
```
public final void setImage(WordProcessingWatermarkableImage value)
```


इस `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` की इमेज सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | [WordProcessingWatermarkableImage](../../com.groupdocs.watermark.contents/wordprocessingwatermarkableimage) | इस `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` की छवि या `null` यदि छवि को हटाना हो। |
|

### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public final int getHorizontalAlignment()
```


शेप क्षैतिज रूप से कैसे स्थित है यह निर्दिष्ट करने वाला मान प्राप्त करता है।


**Returns:**
int - क्षैतिज संरेखण मान।

### getVerticalAlignment() {#getVerticalAlignment--}
```
public final int getVerticalAlignment()
```


शेप लंबवत रूप से कैसे स्थित है यह निर्दिष्ट करने वाला मान प्राप्त करता है।


**Returns:**
int - लंबवत संरेखण मान।

### getRelativeHorizontalPosition() {#getRelativeHorizontalPosition--}
```
public final int getRelativeHorizontalPosition()
```


शेप क्षैतिज रूप से किस पर स्थित है यह निर्दिष्ट करने वाला मान प्राप्त करता है।


**Returns:**
int - सापेक्ष क्षैतिज स्थिति मान।

### getRelativeVerticalPosition() {#getRelativeVerticalPosition--}
```
public final int getRelativeVerticalPosition()
```


शेप लंबवत रूप से किस पर स्थित है यह निर्दिष्ट करने वाला मान प्राप्त करता है।


**Returns:**
int - सापेक्ष लंबवत स्थिति मान।

### getImageFillFormat() {#getImageFillFormat--}
```
public final WordProcessingImageFillFormat getImageFillFormat()
```




**Returns:**
[WordProcessingImageFillFormat](../../com.groupdocs.watermark.internal/wordprocessingimagefillformat)
### getAsposeWordsShape() {#getAsposeWordsShape--}
```
public final Shape getAsposeWordsShape()
```




**Returns:**
com.aspose.words.Shape
### getHyperlink() {#getHyperlink--}
```
public final String getHyperlink()
```


इस `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` से जुड़ा हाइपरलिंक प्राप्त करता है।


**Returns:**
java.lang.String - इस `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` से जुड़ा हाइपरलिंक।

### setHyperlink(String value) {#setHyperlink-java.lang.String-}
```
public final void setHyperlink(String value)
```


इस `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` से जुड़ा हाइपरलिंक सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | java.lang.String | इस `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` से जुड़ा हाइपरलिंक। |
|

### getWidth() {#getWidth--}
```
public final double getWidth()
```


इस `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` की चौड़ाई पॉइंट्स में प्राप्त करता है।


**Returns:**
double - इस `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` की चौड़ाई पॉइंट्स में।

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


इस `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` की चौड़ाई पॉइंट्स में सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | double | इस `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` की चौड़ाई पॉइंट्स में। |
|

### getHeight() {#getHeight--}
```
public final double getHeight()
```


इस `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` की ऊँचाई पॉइंट्स में प्राप्त करता है।


**Returns:**
double - इस `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` की ऊँचाई पॉइंट्स में।

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


इस `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` की ऊँचाई पॉइंट्स में सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | double | इस `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` की ऊँचाई पॉइंट्स में। |
|

### getRotateAngle() {#getRotateAngle--}
```
public final double getRotateAngle()
```


इस `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` का घुमाव कोण डिग्री में प्राप्त करता है।


**Returns:**
double - इस `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` का घुमाव कोण डिग्री में।

### setRotateAngle(double value) {#setRotateAngle-double-}
```
public final void setRotateAngle(double value)
```


इस `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` का घुमाव कोण डिग्री में सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | double | इस `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` का घुमाव कोण डिग्री में। |
|

### getX() {#getX--}
```
public final double getX()
```


इस `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` का पृष्ठ बाएँ किनारे से क्षैतिज ऑफ़सेट पॉइंट्स में प्राप्त या सेट करता है।


**Returns:**
double - इस `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` का x-निर्देशांक।

### setX(double value) {#setX-double-}
```
public final void setX(double value)
```


इस `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` का पृष्ठ बाएँ किनारे से क्षैतिज ऑफ़सेट पॉइंट्स में प्राप्त या सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | double | इस `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` का x-निर्देशांक। |
|

### getY() {#getY--}
```
public final double getY()
```


इस `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` का पृष्ठ शीर्ष किनारे से लंबवत ऑफ़सेट पॉइंट्स में प्राप्त करता है।


**Returns:**
double - इस `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` का y-निर्देशांक।

### setY(double value) {#setY-double-}
```
public final void setY(double value)
```


इस `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` का पृष्ठ शीर्ष किनारे से लंबवत ऑफ़सेट पॉइंट्स में सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | double | इस `[WordProcessingShape](../../com.groupdocs.watermark.contents/wordprocessingshape)` का y-निर्देशांक। |
|

### getFormattedTextFragmentsForSearch() {#getFormattedTextFragmentsForSearch--}
```
public FormattedTextFragmentCollection getFormattedTextFragmentsForSearch()
```




**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection)
### getTextForSearch() {#getTextForSearch--}
```
public String getTextForSearch()
```




**Returns:**
java.lang.String
### setFoundWatermarkText(String value) {#setFoundWatermarkText-java.lang.String-}
```
public void setFoundWatermarkText(String value)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getImageForSearch() {#getImageForSearch--}
```
public WatermarkableImage getImageForSearch()
```




**Returns:**
[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)
### setFoundWatermarkImage(byte[] imageData) {#setFoundWatermarkImage-byte---}
```
public void setFoundWatermarkImage(byte[] imageData)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| imageData | byte[] |  |

