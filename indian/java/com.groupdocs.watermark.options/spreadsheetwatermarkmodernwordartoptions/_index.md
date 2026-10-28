---
title: "SpreadsheetWatermarkModernWordArtOptions"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "स्प्रेडशीट वर्कशीट में आधुनिक वर्ड आर्ट वॉटरमार्क जोड़ते समय विकल्पों का प्रतिनिधित्व करता है।"
type: docs
weight: 58
url: /hi/java/com.groupdocs.watermark.options/spreadsheetwatermarkmodernwordartoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.SpreadsheetWatermarkOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkoptions), [com.groupdocs.watermark.options.SpreadsheetWatermarkBaseOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkbaseoptions)
```
public final class SpreadsheetWatermarkModernWordArtOptions extends SpreadsheetWatermarkBaseOptions
```

स्प्रेडशीट वर्कशीट में आधुनिक वर्ड आर्ट वॉटरमार्क जोड़ते समय विकल्पों का प्रतिनिधित्व करता है।

**Learn more:**

* [Add watermarks to spreadsheet documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+spreadsheet+documents)

निम्नलिखित उदाहरण दिखाता है कि Excel दस्तावेज़ में आधुनिक WordArt वॉटरमार्क कैसे जोड़ें।
>
> ````
> ```
>
>    SpreadsheetLoadOptions loadOptions = new SpreadsheetLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.xls", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 14));
>
>    SpreadsheetWatermarkModernWordArtOptions options = new SpreadsheetWatermarkModernWordArtOptions();
>    options.setWorksheetIndex(-1); // default
>    options.setLocked(false); // default
>    
>    watermarker.save("D:\\watermarked_test.xlsx");
>    watermarker.close();
>  
> ```
> ````


## निर्माताएँ

| निर्माता | विवरण |
| --- | --- |
|  | [SpreadsheetWatermarkModernWordArtOptions()](#SpreadsheetWatermarkModernWordArtOptions--) | एक नया उदाहरण प्रारंभ करता है `[SpreadsheetWatermarkModernWordArtOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkmodernwordartoptions)` क्लास का। |
|
## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getWorksheetIndex()](#getWorksheetIndex--) | वॉटरमार्क जोड़ने के लिए वर्कशीट का इंडेक्स प्राप्त करता है। |
|
|  | [setWorksheetIndex(int value)](#setWorksheetIndex-int-) | वॉटरमार्क जोड़ने के लिए वर्कशीट का इंडेक्स सेट करता है। |
|
### SpreadsheetWatermarkModernWordArtOptions() {#SpreadsheetWatermarkModernWordArtOptions--}
```
public SpreadsheetWatermarkModernWordArtOptions()
```


एक नया उदाहरण प्रारंभ करता है `[SpreadsheetWatermarkModernWordArtOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkmodernwordartoptions)` क्लास का।


### getWorksheetIndex() {#getWorksheetIndex--}
```
public final int getWorksheetIndex()
```


वॉटरमार्क जोड़ने के लिए वर्कशीट का इंडेक्स प्राप्त करता है।


**Returns:**
int - वॉटरमार्क जोड़ने के लिए वर्कशीट का इंडेक्स।

<br />

*** ** * ** ***

-1 means every worksheet.

<br />


### setWorksheetIndex(int value) {#setWorksheetIndex-int-}
```
public final void setWorksheetIndex(int value)
```


वॉटरमार्क जोड़ने के लिए वर्कशीट का इंडेक्स सेट करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | मान | int | वॉटरमार्क जोड़ने के लिए वर्कशीट का इंडेक्स। |

<br />

*** ** * ** ***

-1 means every worksheet.

<br />

|

