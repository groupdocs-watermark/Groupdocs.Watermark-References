---
title: "SpreadsheetBackgroundWatermarkOptions"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "स्प्रेडशीट वर्कशीट में पृष्ठभूमि के रूप में वॉटरमार्क जोड़ते समय विकल्पों का प्रतिनिधित्व करता है।"
type: docs
weight: 49
url: /hi/java/com.groupdocs.watermark.options/spreadsheetbackgroundwatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.SpreadsheetWatermarkOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkoptions)
```
public final class SpreadsheetBackgroundWatermarkOptions extends SpreadsheetWatermarkOptions
```

स्प्रेडशीट वर्कशीट में पृष्ठभूमि के रूप में वॉटरमार्क जोड़ते समय विकल्पों का प्रतिनिधित्व करता है।

**Learn more:**

* [Add watermarks to spreadsheet documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+spreadsheet+documents)

निम्न उदाहरण दिखाता है कि Excel दस्तावेज़ वर्कशीट में टेक्स्ट वॉटरमार्क को पृष्ठभूमि के रूप में कैसे जोड़ें।
>
> ````
> ```
>
>    SpreadsheetLoadOptions loadOptions = new SpreadsheetLoadOptions();
>    Watermarker watermarker = new Watermarker("C:\\Documents\\test.xlsx", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("Test watermark", new Font("Arial", 36));
>
>    SpreadsheetBackgroundWatermarkOptions options = new SpreadsheetBackgroundWatermarkOptions();
>    options.setWorksheetIndex(-1); // default
>    options.setBackgroundWidth(800);
>    options.setBackgroundHeight(600);
>    
>    watermarker.save("C:\\Documents\\watermarked_test.xlsx");
>    watermarker.close();
>  
> ```
> ````


## निर्माताएँ

| निर्माता | विवरण |
| --- | --- |
|  | [SpreadsheetBackgroundWatermarkOptions()](#SpreadsheetBackgroundWatermarkOptions--) | नया उदाहरण प्रारंभ करता है `[SpreadsheetBackgroundWatermarkOptions](../../com.groupdocs.watermark.options/spreadsheetbackgroundwatermarkoptions)` क्लास का। |
|
## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getWorksheetIndex()](#getWorksheetIndex--) | वॉटरमार्क जोड़ने के लिए वर्कशीट का इंडेक्स प्राप्त करें। |
|
|  | [setWorksheetIndex(int value)](#setWorksheetIndex-int-) | वॉटरमार्क जोड़ने के लिए वर्कशीट का इंडेक्स सेट करता है। |
|
|  | [getBackgroundWidth()](#getBackgroundWidth--) | पृष्ठभूमि छवि की इच्छित चौड़ाई पिक्सेल में प्राप्त करें। |
|
|  | [setBackgroundWidth(int value)](#setBackgroundWidth-int-) | पृष्ठभूमि छवि की इच्छित चौड़ाई पिक्सेल में सेट करता है। |
|
|  | [getBackgroundHeight()](#getBackgroundHeight--) | पृष्ठभूमि छवि की इच्छित ऊँचाई पिक्सेल में प्राप्त करता या सेट करता है। |
|
|  | [setBackgroundHeight(int value)](#setBackgroundHeight-int-) | पृष्ठभूमि छवि की इच्छित ऊँचाई पिक्सेल में प्राप्त करता या सेट करता है। |
|
### SpreadsheetBackgroundWatermarkOptions() {#SpreadsheetBackgroundWatermarkOptions--}
```
public SpreadsheetBackgroundWatermarkOptions()
```


नया उदाहरण प्रारंभ करता है `[SpreadsheetBackgroundWatermarkOptions](../../com.groupdocs.watermark.options/spreadsheetbackgroundwatermarkoptions)` क्लास का।


### getWorksheetIndex() {#getWorksheetIndex--}
```
public final int getWorksheetIndex()
```


वॉटरमार्क जोड़ने के लिए वर्कशीट का इंडेक्स प्राप्त करें।

-1 means every worksheet.


**Returns:**
int - वॉटरमार्क जोड़ने के लिए वर्कशीट का इंडेक्स।

### setWorksheetIndex(int value) {#setWorksheetIndex-int-}
```
public final void setWorksheetIndex(int value)
```


वॉटरमार्क जोड़ने के लिए वर्कशीट का इंडेक्स सेट करता है।

-1 means every worksheet.


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | int | वॉटरमार्क जोड़ने के लिए वर्कशीट का इंडेक्स। |
|

### getBackgroundWidth() {#getBackgroundWidth--}
```
public final int getBackgroundWidth()
```


पृष्ठभूमि छवि की इच्छित चौड़ाई पिक्सेल में प्राप्त करें।


**Returns:**
int - पृष्ठभूमि छवि की इच्छित चौड़ाई पिक्सेल में।

### setBackgroundWidth(int value) {#setBackgroundWidth-int-}
```
public final void setBackgroundWidth(int value)
```


पृष्ठभूमि छवि की इच्छित चौड़ाई पिक्सेल में सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | int | पृष्ठभूमि छवि की इच्छित चौड़ाई पिक्सेल में। |
|

### getBackgroundHeight() {#getBackgroundHeight--}
```
public final int getBackgroundHeight()
```


पृष्ठभूमि छवि की इच्छित ऊँचाई पिक्सेल में प्राप्त करता या सेट करता है।


**Returns:**
int - पृष्ठभूमि छवि की इच्छित ऊँचाई पिक्सेल में।

### setBackgroundHeight(int value) {#setBackgroundHeight-int-}
```
public final void setBackgroundHeight(int value)
```


पृष्ठभूमि छवि की इच्छित ऊँचाई पिक्सेल में प्राप्त करता या सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | int | पृष्ठभूमि छवि की इच्छित ऊँचाई पिक्सेल में। |
|

