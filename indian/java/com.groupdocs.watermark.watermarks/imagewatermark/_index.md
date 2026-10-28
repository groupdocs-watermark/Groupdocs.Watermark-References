---
title: "ImageWatermark"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "इमेज वॉटरमार्क का प्रतिनिधित्व करता है।"
type: docs
weight: 13
url: /hi/java/com.groupdocs.watermark.watermarks/imagewatermark/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.Watermark](../../com.groupdocs.watermark/watermark)

**All Implemented Interfaces:**
java.io.Closeable
```
public final class ImageWatermark extends Watermark implements Closeable
```

इमेज वॉटरमार्क का प्रतिनिधित्व करता है।

**Learn more:**

* [Adding image watermarks](../https://docs.groupdocs.com/display/watermarkjava/Adding+image+watermarks)

निम्नलिखित उदाहरण दर्शाता है कि किसी भी समर्थित प्रकार के दस्तावेज़ में इमेज वॉटरमार्क कैसे जोड़ें।
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("C:\\test.some_ext");
>    ImageWatermark watermark = new ImageWatermark("C:\\watermark.png");
>
>    watermark.setHorizontalAlignment(HorizontalAlignment.Center);
>    watermark.setVerticalAlignment(VerticalAlignment.Center);
>    watermarker.add(watermark);
>
>    watermarker.save("C:\\modified_test.some_ext");
>    watermark.close();
>    watermarker.close();
>  
> ```
> ````


## निर्माताएँ

| निर्माता | विवरण |
| --- | --- |
|  | [ImageWatermark(String filePath)](#ImageWatermark-java.lang.String-) | निर्दिष्ट फ़ाइल पथ के साथ `[ImageWatermark](../../com.groupdocs.watermark.watermarks/imagewatermark)` क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है। |
|
|  | [ImageWatermark(InputStream stream)](#ImageWatermark-java.io.InputStream-) | निर्दिष्ट स्ट्रीम के साथ `[ImageWatermark](../../com.groupdocs.watermark.watermarks/imagewatermark)` क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है। |
|
| [ImageWatermark(System.IO.Stream stream)](#ImageWatermark-com.aspose.ms.System.IO.Stream-) |  |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [isImageWatermark()](#isImageWatermark--) |  |
| [isTextWatermark()](#isTextWatermark--) |  |
| [getStream()](#getStream--) |  |
| [getTransparentImageContainer()](#getTransparentImageContainer--) |  |
| [getSize()](#getSize--) |  |
| [dispose()](#dispose--) |  |
| [deepClone()](#deepClone--) |  |
| [hasSameValues(Watermark watermark)](#hasSameValues-com.groupdocs.watermark.Watermark-) |  |
| [createGeometry(ContentPartGeometry parent)](#createGeometry-com.groupdocs.watermark.internal.ContentPartGeometry-) |  |
|  | [close()](#close--) | वर्तमान इंस्टेंस को नष्ट करता है। |
|
### ImageWatermark(String filePath) {#ImageWatermark-java.lang.String-}
```
public ImageWatermark(String filePath)
```


निर्दिष्ट फ़ाइल पथ के साथ `[ImageWatermark](../../com.groupdocs.watermark.watermarks/imagewatermark)` क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | filePath | java.lang.String | वॉटरमार्क के रूप में उपयोग की जाने वाली इमेज का पथ। |
|

### ImageWatermark(InputStream stream) {#ImageWatermark-java.io.InputStream-}
```
public ImageWatermark(InputStream stream)
```


निर्दिष्ट स्ट्रीम के साथ `[ImageWatermark](../../com.groupdocs.watermark.watermarks/imagewatermark)` क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | stream | java.io.InputStream | वॉटरमार्क के रूप में उपयोग की जाने वाली इमेज को सम्मिलित करने वाली स्ट्रीम। |
|

### ImageWatermark(System.IO.Stream stream) {#ImageWatermark-com.aspose.ms.System.IO.Stream-}
```
public ImageWatermark(System.IO.Stream stream)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### isImageWatermark() {#isImageWatermark--}
```
public boolean isImageWatermark()
```




**Returns:**
boolean
### isTextWatermark() {#isTextWatermark--}
```
public boolean isTextWatermark()
```




**Returns:**
boolean
### getStream() {#getStream--}
```
public final StreamContainer getStream()
```




**Returns:**
[StreamContainer](../../com.groupdocs.watermark.internal/streamcontainer)
### getTransparentImageContainer() {#getTransparentImageContainer--}
```
public final StreamContainer getTransparentImageContainer()
```




**Returns:**
[StreamContainer](../../com.groupdocs.watermark.internal/streamcontainer)
### getSize() {#getSize--}
```
public SizeD getSize()
```




**Returns:**
[SizeD](../../com.groupdocs.watermark.internal/sized)
### dispose() {#dispose--}
```
public final void dispose()
```




### deepClone() {#deepClone--}
```
public Watermark deepClone()
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
public WatermarkGeometry createGeometry(ContentPartGeometry parent)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| parent | [ContentPartGeometry](../../com.groupdocs.watermark.internal/contentpartgeometry) |  |

**Returns:**
[WatermarkGeometry](../../com.groupdocs.watermark.internal/watermarkgeometry)
### close() {#close--}
```
public final void close()
```


वर्तमान इंस्टेंस को नष्ट करता है।


