---
title: "वॉटरमार्क"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "एक वॉटरमार्क का प्रतिनिधित्व करता है जिसे दस्तावेज़ में जोड़ा जाएगा।"
type: docs
weight: 13
url: /hi/java/com.groupdocs.watermark/watermark/
---
**Inheritance:**
java.lang.Object
```
public abstract class Watermark
```

एक वॉटरमार्क का प्रतिनिधित्व करता है जिसे दस्तावेज़ में जोड़ा जाएगा।

**Learn more**

* More details about watermark properties:
  [Adding text watermarks](../https://docs.groupdocs.com/display/watermarkjava/Adding+text+watermarks).

* More advanced watermarking topics: [Adding watermarks](../https://docs.groupdocs.com/display/watermarkjava/Adding+watermarks)

## निर्माताएँ

| निर्माता | विवरण |
| --- | --- |
| [Watermark()](#Watermark--) |  |
## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getOpacity()](#getOpacity--) | इस `[Watermark](../../com.groupdocs.watermark/watermark)` की अपारदर्शिता को प्राप्त या सेट करता है। |
|
|  | [setOpacity(double value)](#setOpacity-double-) | इस `[Watermark](../../com.groupdocs.watermark/watermark)` की अपारदर्शिता को प्राप्त या सेट करता है। |
|
|  | [getY()](#getY--) | इस `[Watermark](../../com.groupdocs.watermark/watermark)` का y-निर्देशांक प्राप्त करता है। |
|
|  | [setY(double value)](#setY-double-) | इस `[Watermark](../../com.groupdocs.watermark/watermark)` का y-निर्देशांक सेट करता है। |
|
|  | [getX()](#getX--) | इस `[Watermark](../../com.groupdocs.watermark/watermark)` का x-निर्देशांक प्राप्त करता है। |
|
|  | [setX(double value)](#setX-double-) | इस `[Watermark](../../com.groupdocs.watermark/watermark)` का x-निर्देशांक सेट करता है। |
|
|  | [getVerticalAlignment()](#getVerticalAlignment--) | इस `[Watermark](../../com.groupdocs.watermark/watermark)` का लंबवत संरेखण प्राप्त करता है। |
|
|  | [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | इस `[Watermark](../../com.groupdocs.watermark/watermark)` का लंबवत संरेखण सेट करता है। |
|
|  | [getHorizontalAlignment()](#getHorizontalAlignment--) | इस `[Watermark](../../com.groupdocs.watermark/watermark)` का क्षैतिज संरेखण प्राप्त करता है। |
|
|  | [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | इस `[Watermark](../../com.groupdocs.watermark/watermark)` का क्षैतिज संरेखण सेट करता है। |
|
|  | [getRotateAngle()](#getRotateAngle--) | इस `[Watermark](../../com.groupdocs.watermark/watermark)` का घूर्णन कोण डिग्री में प्राप्त करता है। |
|
|  | [setRotateAngle(double value)](#setRotateAngle-double-) | इस `[Watermark](../../com.groupdocs.watermark/watermark)` का घूर्णन कोण डिग्री में सेट करता है। |
|
|  | [isBackground()](#isBackground--) | एक मान प्राप्त करता है जो दर्शाता है कि वॉटरमार्क को पृष्ठभूमि में रखा जाना चाहिए या नहीं। |
|
|  | [setBackground(boolean value)](#setBackground-boolean-) | एक मान सेट करता है जो दर्शाता है कि वॉटरमार्क को पृष्ठभूमि में रखा जाना चाहिए या नहीं। |
|
|  | [getMargins()](#getMargins--) | इस `[Watermark](../../com.groupdocs.watermark/watermark)` की मार्जिन सेटिंग्स प्राप्त करता है। |
|
|  | [setMargins(Margins value)](#setMargins-com.groupdocs.watermark.watermarks.Margins-) | इस `[Watermark](../../com.groupdocs.watermark/watermark)` की मार्जिन सेटिंग्स सेट करता है। |
|
|  | [getPagesSetup()](#getPagesSetup--) | इस `[Watermark](../../com.groupdocs.watermark/watermark)` की पृष्ठ सेटअप सेटिंग्स प्राप्त करता है। |
|
|  | [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.watermark.PagesSetup-) | इस `[Watermark](../../com.groupdocs.watermark/watermark)` की पृष्ठ सेटअप सेटिंग्स सेट करता है। |
|
|  | [getHeight()](#getHeight--) | इस `[Watermark](../../com.groupdocs.watermark/watermark)` की वांछित ऊँचाई प्राप्त करता है। |
|
|  | [setHeight(double value)](#setHeight-double-) | इस `[Watermark](../../com.groupdocs.watermark/watermark)` की वांछित ऊँचाई सेट करता है। |
|
|  | [getWidth()](#getWidth--) | इस `[Watermark](../../com.groupdocs.watermark/watermark)` की वांछित चौड़ाई प्राप्त करता है। |
|
|  | [setWidth(double value)](#setWidth-double-) | इस `[Watermark](../../com.groupdocs.watermark/watermark)` की वांछित चौड़ाई सेट करता है। |
|
|  | [getScaleFactor()](#getScaleFactor--) | एक मान प्राप्त करता है जो निर्धारित करता है कि वॉटरमार्क का आकार पैरेंट आकार पर कैसे निर्भर करता है। |
|
|  | [setScaleFactor(double value)](#setScaleFactor-double-) | एक मान सेट करता है जो निर्धारित करता है कि वॉटरमार्क का आकार पैरेंट आकार पर कैसे निर्भर करता है। |
|
|  | [getSizingType()](#getSizingType--) | एक मान प्राप्त करता है जो यह निर्दिष्ट करता है कि वॉटरमार्क को कैसे आकार देना चाहिए। |
|
|  | [setSizingType(int value)](#setSizingType-int-) | एक मान सेट करता है जो यह निर्दिष्ट करता है कि वॉटरमार्क को कैसे आकार देना चाहिए। |
|
|  | [getConsiderParentMargins()](#getConsiderParentMargins--) | एक मान प्राप्त करता है जो इंगित करता है कि वॉटरमार्क का आकार और निर्देशांक गणना किए गए हैं |
पैरेंट मार्जिन को ध्यान में रखते हुए।
|
|  | [setConsiderParentMargins(boolean value)](#setConsiderParentMargins-boolean-) | एक मान सेट करता है जो इंगित करता है कि वॉटरमार्क का आकार और निर्देशांक गणना किए गए हैं |
पैरेंट मार्जिन को ध्यान में रखते हुए।
|
| [isImageWatermark()](#isImageWatermark--) |  |
| [isTextWatermark()](#isTextWatermark--) |  |
| [getTransparency()](#getTransparency--) |  |
| [getSize()](#getSize--) |  |
| [getTileOptions()](#getTileOptions--) |  |
| [setTileOptions(TileOptions tileOptions)](#setTileOptions-com.groupdocs.watermark.watermarks.TileOptions-) |  |
| [copyPropertiesValues(Watermark source, Watermark destination)](#copyPropertiesValues-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.Watermark-) |  |
| [deepClone()](#deepClone--) |  |
| [hasSameValues(Watermark watermark)](#hasSameValues-com.groupdocs.watermark.Watermark-) |  |
| [createGeometry(ContentPartGeometry parent)](#createGeometry-com.groupdocs.watermark.internal.ContentPartGeometry-) |  |
### Watermark() {#Watermark--}
```
public Watermark()
```




### getOpacity() {#getOpacity--}
```
public final double getOpacity()
```


इस `[Watermark](../../com.groupdocs.watermark/watermark)` की अपारदर्शिता को प्राप्त या सेट करता है।

अपारदर्शिता का मान 0 और 1 के बीच होना चाहिए। डिफ़ॉल्ट मान 1 है।


**Returns:**
double - इस `[Watermark](../../com.groupdocs.watermark/watermark)` की अपारदर्शिता।

### setOpacity(double value) {#setOpacity-double-}
```
public final void setOpacity(double value)
```


इस `[Watermark](../../com.groupdocs.watermark/watermark)` की अपारदर्शिता को प्राप्त या सेट करता है।

अपारदर्शिता का मान 0 और 1 के बीच होना चाहिए। डिफ़ॉल्ट मान 1 है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | double | इस `[Watermark](../../com.groupdocs.watermark/watermark)` की अपारदर्शिता। |
|

### getY() {#getY--}
```
public final double getY()
```


इस `[Watermark](../../com.groupdocs.watermark/watermark)` का y-निर्देशांक प्राप्त करता है।


**Returns:**
double - इस `[Watermark](../../com.groupdocs.watermark/watermark)` का y-निर्देशांक।

### setY(double value) {#setY-double-}
```
public final void setY(double value)
```


इस `[Watermark](../../com.groupdocs.watermark/watermark)` का y-निर्देशांक सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | double | इस `[Watermark](../../com.groupdocs.watermark/watermark)` का y-निर्देशांक। |
|

### getX() {#getX--}
```
public final double getX()
```


इस `[Watermark](../../com.groupdocs.watermark/watermark)` का x-निर्देशांक प्राप्त करता है।


**Returns:**
double - इस `[Watermark](../../com.groupdocs.watermark/watermark)` का x-निर्देशांक।

### setX(double value) {#setX-double-}
```
public final void setX(double value)
```


इस `[Watermark](../../com.groupdocs.watermark/watermark)` का x-निर्देशांक सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | double | इस `[Watermark](../../com.groupdocs.watermark/watermark)` का x-निर्देशांक। |
|

### getVerticalAlignment() {#getVerticalAlignment--}
```
public final int getVerticalAlignment()
```


इस `[Watermark](../../com.groupdocs.watermark/watermark)` का लंबवत संरेखण प्राप्त करता है।

डिफ़ॉल्ट मान है `[VerticalAlignment.None](../../com.groupdocs.watermark.common/verticalalignment#None)`।


**Returns:**
int - इस `[Watermark](../../com.groupdocs.watermark/watermark)` का `[VerticalAlignment](../../com.groupdocs.watermark.common/verticalalignment)`।

### setVerticalAlignment(int value) {#setVerticalAlignment-int-}
```
public final void setVerticalAlignment(int value)
```


इस `[Watermark](../../com.groupdocs.watermark/watermark)` का लंबवत संरेखण सेट करता है।

डिफ़ॉल्ट मान है `[VerticalAlignment.None](../../com.groupdocs.watermark.common/verticalalignment#None)`।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | int | इस `[Watermark](../../com.groupdocs.watermark/watermark)` का `[VerticalAlignment](../../com.groupdocs.watermark.common/verticalalignment)`। |
|

### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public final int getHorizontalAlignment()
```


इस `[Watermark](../../com.groupdocs.watermark/watermark)` का क्षैतिज संरेखण प्राप्त करता है।

डिफ़ॉल्ट मान है `[HorizontalAlignment.None](../../com.groupdocs.watermark.common/horizontalalignment#None)`।


**Returns:**
int - इस `[Watermark](../../com.groupdocs.watermark/watermark)` का `[HorizontalAlignment](../../com.groupdocs.watermark.common/horizontalalignment)`।

### setHorizontalAlignment(int value) {#setHorizontalAlignment-int-}
```
public final void setHorizontalAlignment(int value)
```


इस `[Watermark](../../com.groupdocs.watermark/watermark)` का क्षैतिज संरेखण सेट करता है।

डिफ़ॉल्ट मान है `[HorizontalAlignment.None](../../com.groupdocs.watermark.common/horizontalalignment#None)`।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | int | इस `[Watermark](../../com.groupdocs.watermark/watermark)` का `[HorizontalAlignment](../../com.groupdocs.watermark.common/horizontalalignment)`। |
|

### getRotateAngle() {#getRotateAngle--}
```
public final double getRotateAngle()
```


इस `[Watermark](../../com.groupdocs.watermark/watermark)` का घूर्णन कोण डिग्री में प्राप्त करता है।


**Returns:**
double - इस `[Watermark](../../com.groupdocs.watermark/watermark)` का घूर्णन कोण डिग्री में।

### setRotateAngle(double value) {#setRotateAngle-double-}
```
public final void setRotateAngle(double value)
```


इस `[Watermark](../../com.groupdocs.watermark/watermark)` का घूर्णन कोण डिग्री में सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | double | इस `[Watermark](../../com.groupdocs.watermark/watermark)` का घूर्णन कोण डिग्री में। |
|

### isBackground() {#isBackground--}
```
public final boolean isBackground()
```


एक मान प्राप्त करता है जो दर्शाता है कि वॉटरमार्क को पृष्ठभूमि में रखा जाना चाहिए या नहीं।


**Returns:**
boolean - यदि मान true है, तो वॉटरमार्क नीचे रखा जाएगा। डिफ़ॉल्ट रूप से, मान false है, वॉटरमार्क ऊपर रखा जाएगा।

### setBackground(boolean value) {#setBackground-boolean-}
```
public final void setBackground(boolean value)
```


एक मान सेट करता है जो दर्शाता है कि वॉटरमार्क को पृष्ठभूमि में रखा जाना चाहिए या नहीं।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | boolean | यदि मान true है, तो वॉटरमार्क नीचे रखा जाएगा। डिफ़ॉल्ट रूप से, मान false है, वॉटरमार्क ऊपर रखा जाएगा। |
|

### getMargins() {#getMargins--}
```
public final Margins getMargins()
```


इस `[Watermark](../../com.groupdocs.watermark/watermark)` की मार्जिन सेटिंग्स प्राप्त करता है।


**Returns:**
[Margins](../../com.groupdocs.watermark.watermarks/margins) - The margin settings of this `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setMargins(Margins value) {#setMargins-com.groupdocs.watermark.watermarks.Margins-}
```
public final void setMargins(Margins value)
```


इस `[Watermark](../../com.groupdocs.watermark/watermark)` की मार्जिन सेटिंग्स सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | [Margins](../../com.groupdocs.watermark.watermarks/margins) | इस `[Watermark](../../com.groupdocs.watermark/watermark)` की मार्जिन सेटिंग्स। |
|

### getPagesSetup() {#getPagesSetup--}
```
public final PagesSetup getPagesSetup()
```


इस `[Watermark](../../com.groupdocs.watermark/watermark)` की पृष्ठ सेटअप सेटिंग्स प्राप्त करता है।


**Returns:**
[PagesSetup](../../com.groupdocs.watermark/pagessetup) - The pages setup settings of this `[Watermark](../../com.groupdocs.watermark/watermark)`.

### setPagesSetup(PagesSetup value) {#setPagesSetup-com.groupdocs.watermark.PagesSetup-}
```
public final void setPagesSetup(PagesSetup value)
```


इस `[Watermark](../../com.groupdocs.watermark/watermark)` की पृष्ठ सेटअप सेटिंग्स सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | [PagesSetup](../../com.groupdocs.watermark/pagessetup) | इस `[Watermark](../../com.groupdocs.watermark/watermark)` की पृष्ठ सेटअप सेटिंग्स। |
|

### getHeight() {#getHeight--}
```
public final double getHeight()
```


इस `[Watermark](../../com.groupdocs.watermark/watermark)` की वांछित ऊँचाई प्राप्त करता है।


**Returns:**
double - इस `[Watermark](../../com.groupdocs.watermark/watermark)` की वांछित ऊँचाई।

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


इस `[Watermark](../../com.groupdocs.watermark/watermark)` की वांछित ऊँचाई सेट करता है।

इस प्रॉपर्टी को सेट करने से `#getSizingType().getSizingType()` का मान भी बदल जाएगा।
प्रॉपर्टी को `[SizingType.Absolute](../../com.groupdocs.watermark.watermarks/sizingtype#Absolute)` पर सेट किया जाता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | double | इस `[Watermark](../../com.groupdocs.watermark/watermark)` की वांछित ऊँचाई। |
|

### getWidth() {#getWidth--}
```
public final double getWidth()
```


इस `[Watermark](../../com.groupdocs.watermark/watermark)` की वांछित चौड़ाई प्राप्त करता है।


**Returns:**
double - इस `[Watermark](../../com.groupdocs.watermark/watermark)` की वांछित चौड़ाई।

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


इस `[Watermark](../../com.groupdocs.watermark/watermark)` की वांछित चौड़ाई सेट करता है।

इस प्रॉपर्टी को सेट करने से `#getSizingType().getSizingType()` का मान भी बदल जाएगा।
प्रॉपर्टी को `[SizingType.Absolute](../../com.groupdocs.watermark.watermarks/sizingtype#Absolute)` पर सेट किया जाता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | double | इस `[Watermark](../../com.groupdocs.watermark/watermark)` की वांछित चौड़ाई। |
|

### getScaleFactor() {#getScaleFactor--}
```
public final double getScaleFactor()
```


एक मान प्राप्त करता है जो निर्धारित करता है कि वॉटरमार्क का आकार पैरेंट आकार पर कैसे निर्भर करता है।

मान 0 और 1 के बीच होना चाहिए।


**Returns:**
double - इस `[Watermark](../../com.groupdocs.watermark/watermark)` का स्केल फ़ैक्टर।

### setScaleFactor(double value) {#setScaleFactor-double-}
```
public final void setScaleFactor(double value)
```


एक मान सेट करता है जो निर्धारित करता है कि वॉटरमार्क का आकार पैरेंट आकार पर कैसे निर्भर करता है।

मान 0 और 1 के बीच होना चाहिए।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | double | इस `[Watermark](../../com.groupdocs.watermark/watermark)` का स्केल फ़ैक्टर। |
|

### getSizingType() {#getSizingType--}
```
public final int getSizingType()
```


एक मान प्राप्त करता है जो यह निर्दिष्ट करता है कि वॉटरमार्क को कैसे आकार देना चाहिए।


**Returns:**
int - साइजिंग प्रकार।

### setSizingType(int value) {#setSizingType-int-}
```
public final void setSizingType(int value)
```


एक मान सेट करता है जो यह निर्दिष्ट करता है कि वॉटरमार्क को कैसे आकार देना चाहिए।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | int | साइजिंग प्रकार। |
|

### getConsiderParentMargins() {#getConsiderParentMargins--}
```
public final boolean getConsiderParentMargins()
```


एक मान प्राप्त करता है जो इंगित करता है कि वॉटरमार्क का आकार और निर्देशांक गणना किए गए हैं
पैरेंट मार्जिन को ध्यान में रखते हुए।


**Returns:**
boolean - यदि मान true है, तो वॉटरमार्क का आकार और निर्देशांक पैरेंट मार्जिन को ध्यान में रखकर गणना किए जाते हैं। डिफ़ॉल्ट रूप से, मान false है, पैरेंट मार्जिन को नजरअंदाज किया जाता है।

### setConsiderParentMargins(boolean value) {#setConsiderParentMargins-boolean-}
```
public final void setConsiderParentMargins(boolean value)
```


एक मान सेट करता है जो इंगित करता है कि वॉटरमार्क का आकार और निर्देशांक गणना किए गए हैं
पैरेंट मार्जिन को ध्यान में रखते हुए।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | boolean | यदि मान true है, तो वॉटरमार्क का आकार और निर्देशांक पैरेंट मार्जिन को ध्यान में रखकर गणना किए जाते हैं। डिफ़ॉल्ट रूप से, मान false है, पैरेंट मार्जिन को नजरअंदाज किया जाता है। |
|

### isImageWatermark() {#isImageWatermark--}
```
public abstract boolean isImageWatermark()
```




**Returns:**
boolean
### isTextWatermark() {#isTextWatermark--}
```
public abstract boolean isTextWatermark()
```




**Returns:**
boolean
### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```




**Returns:**
double
### getSize() {#getSize--}
```
public abstract SizeD getSize()
```




**Returns:**
[SizeD](../../com.groupdocs.watermark.internal/sized)
### getTileOptions() {#getTileOptions--}
```
public TileOptions getTileOptions()
```




**Returns:**
[TileOptions](../../com.groupdocs.watermark.watermarks/tileoptions)
### setTileOptions(TileOptions tileOptions) {#setTileOptions-com.groupdocs.watermark.watermarks.TileOptions-}
```
public void setTileOptions(TileOptions tileOptions)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| tileOptions | [TileOptions](../../com.groupdocs.watermark.watermarks/tileoptions) |  |

### copyPropertiesValues(Watermark source, Watermark destination) {#copyPropertiesValues-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.Watermark-}
```
public static void copyPropertiesValues(Watermark source, Watermark destination)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| source | [Watermark](../../com.groupdocs.watermark/watermark) |  |
| destination | [Watermark](../../com.groupdocs.watermark/watermark) |  |

### deepClone() {#deepClone--}
```
public abstract Watermark deepClone()
```




**Returns:**
[Watermark](../../com.groupdocs.watermark/watermark)
### hasSameValues(Watermark watermark) {#hasSameValues-com.groupdocs.watermark.Watermark-}
```
public boolean hasSameValues(Watermark watermark)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) |  |

**Returns:**
boolean
### createGeometry(ContentPartGeometry parent) {#createGeometry-com.groupdocs.watermark.internal.ContentPartGeometry-}
```
public abstract WatermarkGeometry createGeometry(ContentPartGeometry parent)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| parent | [ContentPartGeometry](../../com.groupdocs.watermark.internal/contentpartgeometry) |  |

**Returns:**
[WatermarkGeometry](../../com.groupdocs.watermark.internal/watermarkgeometry)
