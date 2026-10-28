---
title: "WatermarkableImage"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "दस्तावेज़ के भीतर एक छवि को दर्शाता है।"
type: docs
weight: 127
url: /hi/java/com.groupdocs.watermark.contents/watermarkableimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.ContentPart](../../com.groupdocs.watermark.contents/contentpart)
```
public abstract class WatermarkableImage extends ContentPart
```

दस्तावेज़ के भीतर एक छवि को दर्शाता है।

**Learn more:**

* [Adding watermark to images inside a document](../https://docs.groupdocs.com/display/watermarkjava/Adding+watermark+to+images+inside+a+document)

निम्नलिखित उदाहरण दर्शाता है कि किसी भी समर्थित प्रकार के दस्तावेज़ के भीतर सभी छवियों में वॉटरमार्क कैसे जोड़ें।
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("D:\\input.doc");
>  
>    // Initialize text or image watermark.
>    TextWatermark watermark = new TextWatermark("DRAFT", new Font("Arial", 19));
>  
>    // Find all images in the content.
>    WatermarkableImageCollection images = watermarker.getImages();
>  
>    // Add watermark.
>    for (WatermarkableImage watermarkableImage : images)
>    {
>        watermarkableImage.add(watermark);
>    }
>  
>    // Save changes.
>    watermarker.save("D:\\output.doc");
>    watermarker.close();
>  
> ```
> ````


## निर्माताएँ

| निर्माता | विवरण |
| --- | --- |
| [WatermarkableImage(Content content)](#WatermarkableImage-com.groupdocs.watermark.contents.Content-) |  |
## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getHeight()](#getHeight--) | इस `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` की ऊँचाई पिक्सेल में प्राप्त करता है। |
|
|  | [getWidth()](#getWidth--) | इस `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` की चौड़ाई पिक्सेल में प्राप्त करता है। |
|
|  | [add(Watermark watermark)](#add-com.groupdocs.watermark.Watermark-) | इस `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` में वॉटरमार्क जोड़ता है। |
|
|  | [getBytes()](#getBytes--) | छवि को बाइट ऐरे के रूप में प्राप्त करता है। |
|
| [updateDocumentReference(Content parentContent)](#updateDocumentReference-com.groupdocs.watermark.contents.Content-) |  |
### WatermarkableImage(Content content) {#WatermarkableImage-com.groupdocs.watermark.contents.Content-}
```
public WatermarkableImage(Content content)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| content | [Content](../../com.groupdocs.watermark.contents/content) |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


इस `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` की ऊँचाई पिक्सेल में प्राप्त करता है।


**Returns:**
int - इस `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` की ऊँचाई पिक्सेल में।

### getWidth() {#getWidth--}
```
public final int getWidth()
```


इस `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` की चौड़ाई पिक्सेल में प्राप्त करता है।


**Returns:**
int - इस `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` की चौड़ाई पिक्सेल में।

### add(Watermark watermark) {#add-com.groupdocs.watermark.Watermark-}
```
public final void add(Watermark watermark)
```


इस `[WatermarkableImage](../../com.groupdocs.watermark.contents/watermarkableimage)` में वॉटरमार्क जोड़ता है।

यह मेथड मानता है कि वॉटरमार्क ऑफ़सेट और आकार पिक्सेल में मापे जाते हैं (यदि उन्हें असाइन किया गया है)।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | watermark | [Watermark](../../com.groupdocs.watermark/watermark) | छवि में जोड़ने के लिए वॉटरमार्क। |
|

### getBytes() {#getBytes--}
```
public final byte[] getBytes()
```


छवि को बाइट ऐरे के रूप में प्राप्त करता है।


**Returns:**
byte[] - छवि डेटा।

### updateDocumentReference(Content parentContent) {#updateDocumentReference-com.groupdocs.watermark.contents.Content-}
```
public final void updateDocumentReference(Content parentContent)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| parentContent | [Content](../../com.groupdocs.watermark.contents/content) |  |

