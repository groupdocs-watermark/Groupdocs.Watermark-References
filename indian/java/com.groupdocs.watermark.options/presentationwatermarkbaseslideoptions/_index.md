---
title: "PresentationWatermarkBaseSlideOptions"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "Presentation दस्तावेज़ में वॉटरमार्क जोड़ने के विकल्पों के लिए बेस क्लास।"
type: docs
weight: 39
url: /hi/java/com.groupdocs.watermark.options/presentationwatermarkbaseslideoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.PresentationWatermarkOptions](../../com.groupdocs.watermark.options/presentationwatermarkoptions)
```
public abstract class PresentationWatermarkBaseSlideOptions extends PresentationWatermarkOptions
```

Presentation दस्तावेज़ में वॉटरमार्क जोड़ने के विकल्पों के लिए बेस क्लास।

**Learn more:**

* [Add watermarks to presentation documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+presentation+documents)

निम्न उदाहरण दर्शाता है कि कैसे एक वॉटरमार्क को Power Point प्रस्तुति की विभिन्न सेवा स्लाइड्स में जोड़ा जाए।
>
> ````
> ```
>
>    PresentationLoadOptions loadOptions = new PresentationLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.pptx", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("Test watermark", new Font("Arial", 8));
>
>    // Add watermark to all master slides
>    PresentationWatermarkMasterSlideOptions masterSlideOptions = new PresentationWatermarkMasterSlideOptions();
>    masterSlideOptions.setMasterSlideIndex(-1); // default
>    watermarker.add(watermark, masterSlideOptions);
>    
>    // Add watermark to all layout slides
>    PresentationWatermarkLayoutSlideOptions layoutSlideOptions = new PresentationWatermarkLayoutSlideOptions();
>    layoutSlideOptions.setLayoutSlideIndex(-1); // default
>    watermarker.add(watermark, layoutSlideOptions);
>    
>    // Add watermark to all notes slides
>    PresentationWatermarkNoteSlideOptions noteSlideOptions = new PresentationWatermarkNoteSlideOptions();
>    noteSlideOptions.setSlideIndex(-1); // default
>    watermarker.add(watermark, noteSlideOptions);
>    
>    // Add watermark to handout master
>    PresentationWatermarkMasterHandoutSlideOptions masterHandoutSlideOptions = new PresentationWatermarkMasterHandoutSlideOptions();
>    watermarker.add(watermark, masterHandoutSlideOptions);
>    
>    // Add watermark to notes master
>    PresentationWatermarkMasterNotesSlideOptions masterNotesSlideOptions = new PresentationWatermarkMasterNotesSlideOptions();
>    watermarker.add(watermark, masterNotesSlideOptions);
>    
>    watermarker.save("D:\\watermarked_test.pptx");
>    watermarker.close();
>  
> ```
> ````


## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [isLocked()](#isLocked--) | एक मान प्राप्त करता है जो दर्शाता है कि PowerPoint में आकार का संपादन प्रतिबंधित है या नहीं। |
|
|  | [setLocked(boolean value)](#setLocked-boolean-) | एक मान सेट करता है जो दर्शाता है कि PowerPoint में आकार का संपादन प्रतिबंधित है या नहीं। |
|
|  | [getProtectWithUnreadableCharacters()](#getProtectWithUnreadableCharacters--) | एक मान प्राप्त या सेट करता है जो दर्शाता है कि टेक्स्ट वॉटरमार्क अक्षर अपठनीय अक्षरों के साथ मिश्रित हैं या नहीं। |
|
|  | [setProtectWithUnreadableCharacters(boolean value)](#setProtectWithUnreadableCharacters-boolean-) | एक मान प्राप्त या सेट करता है जो दर्शाता है कि टेक्स्ट वॉटरमार्क अक्षर अपठनीय अक्षरों के साथ मिश्रित हैं या नहीं। |
|
|  | [getName()](#getName--) | आकार का नाम प्राप्त करता है। |
|
|  | [setName(String value)](#setName-java.lang.String-) | आकार का नाम सेट करता है। |
|
|  | [getAlternativeText()](#getAlternativeText--) | आकार से जुड़ा वर्णनात्मक (वैकल्पिक) पाठ प्राप्त करता है। |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | आकार से जुड़ा वर्णनात्मक (वैकल्पिक) पाठ सेट करता है। |
|
|  | [getEffects()](#getEffects--) | एक मान प्राप्त करता है `[PresentationImageEffects](../../com.groupdocs.watermark.options/presentationimageeffects)` या `[PresentationTextEffects](../../com.groupdocs.watermark.options/presentationtexteffects)` के लिए जो वॉटरमार्क पर लागू किए जाने वाले प्रभाव दर्शाता है। |
|
|  | [setEffects(IPresentationWatermarkEffects value)](#setEffects-com.groupdocs.watermark.options.IPresentationWatermarkEffects-) | एक मान सेट करता है `[PresentationImageEffects](../../com.groupdocs.watermark.options/presentationimageeffects)` या `[PresentationTextEffects](../../com.groupdocs.watermark.options/presentationtexteffects)` के लिए जो वॉटरमार्क पर लागू किए जाने वाले प्रभाव दर्शाता है। |
|
### isLocked() {#isLocked--}
```
public final boolean isLocked()
```


एक मान प्राप्त करता है जो दर्शाता है कि PowerPoint में आकार का संपादन प्रतिबंधित है या नहीं।


**Returns:**
boolean - यदि मान true है, तो आकार का संपादन प्रतिबंधित होगा। डिफ़ॉल्ट रूप से, मान false है, आकार को PowerPoint में संपादित किया जा सकता है।

### setLocked(boolean value) {#setLocked-boolean-}
```
public final void setLocked(boolean value)
```


एक मान सेट करता है जो दर्शाता है कि PowerPoint में आकार का संपादन प्रतिबंधित है या नहीं।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | boolean | यदि मान true है, तो आकार का संपादन प्रतिबंधित होगा। डिफ़ॉल्ट रूप से, मान false है, आकार को PowerPoint में संपादित किया जा सकता है। |
|

### getProtectWithUnreadableCharacters() {#getProtectWithUnreadableCharacters--}
```
public final boolean getProtectWithUnreadableCharacters()
```


एक मान प्राप्त या सेट करता है जो दर्शाता है कि टेक्स्ट वॉटरमार्क अक्षर अपठनीय अक्षरों के साथ मिश्रित हैं या नहीं।

यह सुरक्षा केवल तब लागू होती है जब `#isLocked().isLocked()` `true` लौटाता है।


**Returns:**
boolean - एक मान जो दर्शाता है कि टेक्स्ट वॉटरमार्क अक्षर अपठनीय अक्षरों के साथ मिश्रित हैं या नहीं।

### setProtectWithUnreadableCharacters(boolean value) {#setProtectWithUnreadableCharacters-boolean-}
```
public final void setProtectWithUnreadableCharacters(boolean value)
```


एक मान प्राप्त या सेट करता है जो दर्शाता है कि टेक्स्ट वॉटरमार्क अक्षर अपठनीय अक्षरों के साथ मिश्रित हैं या नहीं।

यह सुरक्षा केवल तब लागू होती है जब `#isLocked().isLocked()` `true` लौटाता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | boolean | एक मान जो दर्शाता है कि टेक्स्ट वॉटरमार्क अक्षर अपठनीय अक्षरों के साथ मिश्रित हैं। |
|

### getName() {#getName--}
```
public final String getName()
```


आकार का नाम प्राप्त करता है।


**Returns:**
java.lang.String - आकार का नाम।

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


आकार का नाम सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | java.lang.String | आकार का नाम। |
|

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


आकार से जुड़ा वर्णनात्मक (वैकल्पिक) पाठ प्राप्त करता है।


**Returns:**
java.lang.String - वह वर्णनात्मक (वैकल्पिक) पाठ जो एक आकार के साथ जुड़ा होगा।

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


आकार से जुड़ा वर्णनात्मक (वैकल्पिक) पाठ सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | java.lang.String | वर्णनात्मक (वैकल्पिक) पाठ जो एक आकार के साथ जुड़ा होगा। |
|

### getEffects() {#getEffects--}
```
public final IPresentationWatermarkEffects getEffects()
```


एक मान प्राप्त करता है `[PresentationImageEffects](../../com.groupdocs.watermark.options/presentationimageeffects)` या `[PresentationTextEffects](../../com.groupdocs.watermark.options/presentationtexteffects)` के लिए जो वॉटरमार्क पर लागू किए जाने वाले प्रभाव दर्शाता है।


**Returns:**
[IPresentationWatermarkEffects](../../com.groupdocs.watermark.options/ipresentationwatermarkeffects) - The value of `[PresentationImageEffects](../../com.groupdocs.watermark.options/presentationimageeffects)` or `[PresentationTextEffects](../../com.groupdocs.watermark.options/presentationtexteffects)` for effects that should be applied to the watermark.

### setEffects(IPresentationWatermarkEffects value) {#setEffects-com.groupdocs.watermark.options.IPresentationWatermarkEffects-}
```
public final void setEffects(IPresentationWatermarkEffects value)
```


एक मान सेट करता है `[PresentationImageEffects](../../com.groupdocs.watermark.options/presentationimageeffects)` या `[PresentationTextEffects](../../com.groupdocs.watermark.options/presentationtexteffects)` के लिए जो वॉटरमार्क पर लागू किए जाने वाले प्रभाव दर्शाता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | [IPresentationWatermarkEffects](../../com.groupdocs.watermark.options/ipresentationwatermarkeffects) | वॉटरमार्क पर लागू किए जाने वाले प्रभावों के लिए `[PresentationImageEffects](../../com.groupdocs.watermark.options/presentationimageeffects)` या `[PresentationTextEffects](../../com.groupdocs.watermark.options/presentationtexteffects)` का मान। |
|

