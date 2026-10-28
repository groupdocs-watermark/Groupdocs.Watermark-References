---
title: "SpreadsheetShape"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "Excel दस्तावेज़ में एक ड्रॉइंग शेप का प्रतिनिधित्व करता है।"
type: docs
weight: 117
url: /hi/java/com.groupdocs.watermark.contents/spreadsheetshape/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.ShapeSearchAdapter](../../com.groupdocs.watermark.search/shapesearchadapter)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.IRotatableTwoDObject](../../com.groupdocs.watermark.search/irotatabletwodobject), [com.groupdocs.watermark.search.IHyperlinkContainer](../../com.groupdocs.watermark.search/ihyperlinkcontainer)
```
public class SpreadsheetShape extends ShapeSearchAdapter implements IRotatableTwoDObject, IHyperlinkContainer
```

Excel दस्तावेज़ में एक ड्रॉइंग शेप का प्रतिनिधित्व करता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getWorksheet()](#getWorksheet--) | इस `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` की पैरेंट वर्कशीट प्राप्त करता है। |
|
|  | [getAutoShapeType()](#getAutoShapeType--) | ऑटो शेप प्रकार प्राप्त करता है। |
|
|  | [getMsoDrawingType()](#getMsoDrawingType--) | MSO ड्राइंग प्रकार प्राप्त करता है। |
|
|  | [getText()](#getText--) | इस `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` का टेक्स्ट प्राप्त करता है। |
|
|  | [setText(String value)](#setText-java.lang.String-) | इस `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` का टेक्स्ट सेट करता है। |
|
|  | [getFormattedTextFragments()](#getFormattedTextFragments--) | इस `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` के फ़ॉर्मेटेड टेक्स्ट फ्रैगमेंट्स का संग्रह प्राप्त करता है। |
|
|  | [getImage()](#getImage--) | इस `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` की इमेज प्राप्त करता है। |
|
|  | [setImage(SpreadsheetWatermarkableImage value)](#setImage-com.groupdocs.watermark.contents.SpreadsheetWatermarkableImage-) | इस `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` की इमेज सेट करता है। |
|
|  | [getImageFillFormat()](#getImageFillFormat--) | इस `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` की इमेज फ़िल फ़ॉर्मेट सेटिंग्स प्राप्त करता है। |
|
|  | [getId()](#getId--) | इस `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` की पहचानकर्ता प्राप्त करता है। |
|
|  | [getAlternativeText()](#getAlternativeText--) | इस `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` से संबंधित वर्णनात्मक (वैकल्पिक) टेक्स्ट प्राप्त करता है। |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | इस `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` से संबंधित वर्णनात्मक (वैकल्पिक) टेक्स्ट सेट करता है। |
|
|  | [isWordArt()](#isWordArt--) | इस `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` का WordArt ऑब्जेक्ट है या नहीं, यह दर्शाने वाला मान प्राप्त करता है। |
|
|  | [getName()](#getName--) | इस `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` का नाम प्राप्त करता है। |
|
|  | [getAsposeCellsShape()](#getAsposeCellsShape--) | <br /> |

|
|  | [getHyperlink()](#getHyperlink--) | इस `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` से जुड़ा हाइपरलिंक प्राप्त करता है। |
|
|  | [setHyperlink(String value)](#setHyperlink-java.lang.String-) | इस `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` से जुड़ा हाइपरलिंक सेट करता है। |
|
|  | [getX()](#getX--) | इस `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` का वर्कशीट बाएँ किनारे से क्षैतिज ऑफसेट पॉइंट्स में प्राप्त करता है। |
|
|  | [setX(double value)](#setX-double-) | इस `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` का वर्कशीट बाएँ किनारे से क्षैतिज ऑफसेट पॉइंट्स में सेट करता है। |
|
|  | [getY()](#getY--) | इस `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` का वर्कशीट शीर्ष किनारे से ऊर्ध्वाधर ऑफसेट पॉइंट्स में प्राप्त करता है। |
|
|  | [setY(double value)](#setY-double-) | इस `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` का वर्कशीट शीर्ष किनारे से ऊर्ध्वाधर ऑफसेट पॉइंट्स में सेट करता है। |
|
|  | [getWidth()](#getWidth--) | इस `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` की चौड़ाई को पॉइंट्स में प्राप्त करता है। |
|
|  | [setWidth(double value)](#setWidth-double-) | इस `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` की चौड़ाई को पॉइंट्स में सेट करता है। |
|
|  | [getHeight()](#getHeight--) | इस `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` की ऊँचाई को पॉइंट्स में प्राप्त करता है। |
|
|  | [setHeight(double value)](#setHeight-double-) | इस `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` की ऊँचाई को पॉइंट्स में सेट करता है। |
|
|  | [getRotateAngle()](#getRotateAngle--) | इस `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` का घुमाव कोण डिग्री में प्राप्त या सेट करता है। |
|
|  | [setRotateAngle(double value)](#setRotateAngle-double-) | इस `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` का घुमाव कोण डिग्री में प्राप्त या सेट करता है। |
|
|  | [getImageForSearch()](#getImageForSearch--) | <br /> |

|
|  | [setFoundWatermarkImage(byte[] imageData)](#setFoundWatermarkImage-byte---) | <br /> |

|
|  | [getFormattedTextFragmentsForSearch()](#getFormattedTextFragmentsForSearch--) | <br /> |

|
|  | [getTextForSearch()](#getTextForSearch--) | <br /> |

|
|  | [setFoundWatermarkText(String value)](#setFoundWatermarkText-java.lang.String-) | <br /> |

|
### getWorksheet() {#getWorksheet--}
```
public final SpreadsheetWorksheet getWorksheet()
```


इस `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` की पैरेंट वर्कशीट प्राप्त करता है।


**Returns:**
[SpreadsheetWorksheet](../../com.groupdocs.watermark.contents/spreadsheetworksheet) - The parent worksheet of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### getAutoShapeType() {#getAutoShapeType--}
```
public final int getAutoShapeType()
```


ऑटो शेप प्रकार प्राप्त करता है।


**Returns:**
int - ऑटो आकार प्रकार।

### getMsoDrawingType() {#getMsoDrawingType--}
```
public final int getMsoDrawingType()
```


MSO ड्राइंग प्रकार प्राप्त करता है।


**Returns:**
int - mso ड्राइंग प्रकार।

### getText() {#getText--}
```
public final String getText()
```


इस `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` का टेक्स्ट प्राप्त करता है।


**Returns:**
java.lang.String - इस `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` का पाठ।

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


इस `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` का टेक्स्ट सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | java.lang.String | इस `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` का पाठ। |
|

### getFormattedTextFragments() {#getFormattedTextFragments--}
```
public final FormattedTextFragmentCollection getFormattedTextFragments()
```


इस `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` के फ़ॉर्मेटेड टेक्स्ट फ्रैगमेंट्स का संग्रह प्राप्त करता है।


**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection) - The collection of formatted text fragments of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### getImage() {#getImage--}
```
public final SpreadsheetWatermarkableImage getImage()
```


इस `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` की इमेज प्राप्त करता है।


**Returns:**
[SpreadsheetWatermarkableImage](../../com.groupdocs.watermark.contents/spreadsheetwatermarkableimage) - The image of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` or null if the shape has no image.

### setImage(SpreadsheetWatermarkableImage value) {#setImage-com.groupdocs.watermark.contents.SpreadsheetWatermarkableImage-}
```
public final void setImage(SpreadsheetWatermarkableImage value)
```


इस `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` की इमेज सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | [SpreadsheetWatermarkableImage](../../com.groupdocs.watermark.contents/spreadsheetwatermarkableimage) | इस `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` की छवि या null यदि छवि को हटाना चाहिए। |
|

### getImageFillFormat() {#getImageFillFormat--}
```
public final SpreadsheetImageFillFormat getImageFillFormat()
```


इस `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` की इमेज फ़िल फ़ॉर्मेट सेटिंग्स प्राप्त करता है।


**Returns:**
[SpreadsheetImageFillFormat](../../com.groupdocs.watermark.contents/spreadsheetimagefillformat) - The image fill format settings of this `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)`.

### getId() {#getId--}
```
public final int getId()
```


इस `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` की पहचानकर्ता प्राप्त करता है।


**Returns:**
int - इस `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` की पहचानकर्ता।

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


इस `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` से संबंधित वर्णनात्मक (वैकल्पिक) टेक्स्ट प्राप्त करता है।


**Returns:**
java.lang.String - इस `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` से जुड़ा वर्णनात्मक (वैकल्पिक) पाठ।

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


इस `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` से संबंधित वर्णनात्मक (वैकल्पिक) टेक्स्ट सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | java.lang.String | इस `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` से जुड़ा वर्णनात्मक (वैकल्पिक) पाठ। |
|

### isWordArt() {#isWordArt--}
```
public final boolean isWordArt()
```


इस `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` का WordArt ऑब्जेक्ट है या नहीं, यह दर्शाने वाला मान प्राप्त करता है।


**Returns:**
boolean - यदि आकार WordArt ऑब्जेक्ट है तो true; अन्यथा false।

### getName() {#getName--}
```
public final String getName()
```


इस `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` का नाम प्राप्त करता है।


**Returns:**
java.lang.String - इस `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` का नाम।

### getAsposeCellsShape() {#getAsposeCellsShape--}
```
public final Shape getAsposeCellsShape()
```


<br />



**Returns:**
com.aspose.cells.Shape
### getHyperlink() {#getHyperlink--}
```
public final String getHyperlink()
```


इस `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` से जुड़ा हाइपरलिंक प्राप्त करता है।


**Returns:**
java.lang.String - इस `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` से जुड़ा हाइपरलिंक।

### setHyperlink(String value) {#setHyperlink-java.lang.String-}
```
public final void setHyperlink(String value)
```


इस `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` से जुड़ा हाइपरलिंक सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | java.lang.String | इस `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` से जुड़ा हाइपरलिंक। |
|

### getX() {#getX--}
```
public final double getX()
```


इस `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` का वर्कशीट बाएँ किनारे से क्षैतिज ऑफसेट पॉइंट्स में प्राप्त करता है।


**Returns:**
double - इस `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` का x-निर्देशांक।

### setX(double value) {#setX-double-}
```
public final void setX(double value)
```


इस `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` का वर्कशीट बाएँ किनारे से क्षैतिज ऑफसेट पॉइंट्स में सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | double | इस `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` का x-निर्देशांक। |
|

### getY() {#getY--}
```
public final double getY()
```


इस `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` का वर्कशीट शीर्ष किनारे से ऊर्ध्वाधर ऑफसेट पॉइंट्स में प्राप्त करता है।


**Returns:**
double - इस `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` का y-निर्देशांक।

### setY(double value) {#setY-double-}
```
public final void setY(double value)
```


इस `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` का वर्कशीट शीर्ष किनारे से ऊर्ध्वाधर ऑफसेट पॉइंट्स में सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | double | इस `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` का y-निर्देशांक। |
|

### getWidth() {#getWidth--}
```
public final double getWidth()
```


इस `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` की चौड़ाई को पॉइंट्स में प्राप्त करता है।


**Returns:**
double - इस `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` की चौड़ाई पॉइंट्स में।

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


इस `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` की चौड़ाई को पॉइंट्स में सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | double | इस `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` की चौड़ाई पॉइंट्स में। |
|

### getHeight() {#getHeight--}
```
public final double getHeight()
```


इस `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` की ऊँचाई को पॉइंट्स में प्राप्त करता है।


**Returns:**
double - इस `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` की ऊँचाई पॉइंट्स में।

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


इस `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` की ऊँचाई को पॉइंट्स में सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | double | इस `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` की ऊँचाई पॉइंट्स में। |
|

### getRotateAngle() {#getRotateAngle--}
```
public final double getRotateAngle()
```


इस `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` का घुमाव कोण डिग्री में प्राप्त या सेट करता है।


**Returns:**
double - इस `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` का घुमाव कोण डिग्री में।

### setRotateAngle(double value) {#setRotateAngle-double-}
```
public final void setRotateAngle(double value)
```


इस `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` का घुमाव कोण डिग्री में प्राप्त या सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | double | इस `[SpreadsheetShape](../../com.groupdocs.watermark.contents/spreadsheetshape)` का घुमाव कोण डिग्री में। |
|

### getImageForSearch() {#getImageForSearch--}
```
public WatermarkableImage getImageForSearch()
```


<br />



**Returns:**
[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)
### setFoundWatermarkImage(byte[] imageData) {#setFoundWatermarkImage-byte---}
```
public void setFoundWatermarkImage(byte[] imageData)
```


<br />



**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| imageData | byte[] |  |

### getFormattedTextFragmentsForSearch() {#getFormattedTextFragmentsForSearch--}
```
public FormattedTextFragmentCollection getFormattedTextFragmentsForSearch()
```


<br />



**Returns:**
[FormattedTextFragmentCollection](../../com.groupdocs.watermark.search/formattedtextfragmentcollection)
### getTextForSearch() {#getTextForSearch--}
```
public String getTextForSearch()
```


<br />



**Returns:**
java.lang.String
### setFoundWatermarkText(String value) {#setFoundWatermarkText-java.lang.String-}
```
public void setFoundWatermarkText(String value)
```


<br />



**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

