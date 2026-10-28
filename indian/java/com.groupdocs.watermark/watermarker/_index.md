---
title: "Watermarker"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "दस्तावेज़ में वॉटरमार्क प्रबंधन के लिए एक क्लास का प्रतिनिधित्व करता है।"
type: docs
weight: 14
url: /hi/java/com.groupdocs.watermark/watermarker/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class Watermarker implements Closeable
```

दस्तावेज़ में वॉटरमार्क प्रबंधन के लिए एक क्लास का प्रतिनिधित्व करता है।

निम्न उदाहरण दर्शाता है कि किसी भी समर्थित फ़ॉर्मेट की सामग्री को कैसे लोड और सहेजा जाए।
>
> ````
> ```
>
>    // Load a content from a file.
>    Watermarker watermarker = new Watermarker("D:\\input.pdf");
>
>    // Use methods of Watermarker class to add, search or remove watermarks.
>
>    // Save changes.
>    watermarker.save("D:\\output.pdf");
>
>    // Free resources.
>    watermarker.close();
>  
> ```
> ````


## निर्माताएँ

| निर्माता | विवरण |
| --- | --- |
|  | [Watermarker(String filePath)](#Watermarker-java.lang.String-) | निर्दिष्ट दस्तावेज़ पथ के साथ `[Watermarker](../../com.groupdocs.watermark/watermarker)` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
|
|  | [Watermarker(String filePath, LoadOptions options)](#Watermarker-java.lang.String-com.groupdocs.watermark.options.LoadOptions-) | निर्दिष्ट दस्तावेज़ पथ और लोड विकल्पों के साथ `[Watermarker](../../com.groupdocs.watermark/watermarker)` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
|
|  | [Watermarker(String filePath, WatermarkerSettings settings)](#Watermarker-java.lang.String-com.groupdocs.watermark.WatermarkerSettings-) | निर्दिष्ट दस्तावेज़ पथ और सेटिंग्स के साथ `[Watermarker](../../com.groupdocs.watermark/watermarker)` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
|
|  | [Watermarker(String filePath, LoadOptions options, WatermarkerSettings settings)](#Watermarker-java.lang.String-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-) | निर्दिष्ट दस्तावेज़ पथ, लोड विकल्प और सेटिंग्स के साथ `[Watermarker](../../com.groupdocs.watermark/watermarker)` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
|
|  | [Watermarker(InputStream document)](#Watermarker-java.io.InputStream-) | निर्दिष्ट स्ट्रीम के साथ `[Watermarker](../../com.groupdocs.watermark/watermarker)` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
|
|  | [Watermarker(InputStream document, LoadOptions options)](#Watermarker-java.io.InputStream-com.groupdocs.watermark.options.LoadOptions-) | निर्दिष्ट स्ट्रीम और लोड विकल्पों के साथ `[Watermarker](../../com.groupdocs.watermark/watermarker)` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
|
|  | [Watermarker(InputStream document, WatermarkerSettings settings)](#Watermarker-java.io.InputStream-com.groupdocs.watermark.WatermarkerSettings-) | निर्दिष्ट स्ट्रीम और सेटिंग्स के साथ `[Watermarker](../../com.groupdocs.watermark/watermarker)` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
|
|  | [Watermarker(InputStream document, LoadOptions options, WatermarkerSettings settings)](#Watermarker-java.io.InputStream-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-) | निर्दिष्ट स्ट्रीम, लोड विकल्प और सेटिंग्स के साथ क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
|
| [Watermarker(System.IO.Stream document, LoadOptions options, WatermarkerSettings settings)](#Watermarker-com.aspose.ms.System.IO.Stream-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-) |  |
## विधियाँ

| विधि | विवरण |
| --- | --- |
|  | [getSearchableObjects()](#getSearchableObjects--) | वॉटरमार्क खोज में शामिल किए जाने वाले सामग्री ऑब्जेक्ट्स को प्राप्त करता है। |
|
|  | [setSearchableObjects(SearchableObjects value)](#setSearchableObjects-com.groupdocs.watermark.search.SearchableObjects-) | वॉटरमार्क खोज में शामिल किए जाने वाले सामग्री ऑब्जेक्ट्स को सेट करता है। |
|
| [dispose()](#dispose--) |  |
|  | [close()](#close--) | वर्तमान इंस्टेंस को नष्ट करता है। |
|
|  | [getDocumentInfo()](#getDocumentInfo--) | लोड किए गए दस्तावेज़ के फ़ॉर्मेट के बारे में जानकारी प्राप्त करता है। |
|
|  | [add(Watermark watermark)](#add-com.groupdocs.watermark.Watermark-) | लोड किए गए दस्तावेज़ में एक वॉटरमार्क जोड़ता है। |
|
|  | [add(Watermark watermark, WatermarkOptions options)](#add-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.WatermarkOptions-) | वॉटरमार्क विकल्पों का उपयोग करके लोड किए गए दस्तावेज़ में वॉटरमार्क जोड़ता है। |
|
|  | [remove(PossibleWatermark possibleWatermark)](#remove-com.groupdocs.watermark.search.PossibleWatermark-) | दस्तावेज़ से वॉटरमार्क हटाता है। |
|
|  | [remove(PossibleWatermarkCollection possibleWatermarks)](#remove-com.groupdocs.watermark.search.PossibleWatermarkCollection-) | संग्रह में सभी वॉटरमार्क को दस्तावेज़ से हटाता है। |
|
|  | [save(String filePath)](#save-java.lang.String-) | दस्तावेज़ को निर्दिष्ट फ़ाइल स्थान पर सहेजता है। |
|
|  | [save(OutputStream document)](#save-java.io.OutputStream-) | दस्तावेज़ को निर्दिष्ट स्ट्रीम पर सहेजता है। |
|
|  | [save(String filePath, SaveOptions options)](#save-java.lang.String-com.groupdocs.watermark.options.SaveOptions-) | सहेजने के विकल्पों का उपयोग करके दस्तावेज़ को निर्दिष्ट फ़ाइल स्थान पर सहेजता है। |
|
|  | [save(OutputStream document, SaveOptions options)](#save-java.io.OutputStream-com.groupdocs.watermark.options.SaveOptions-) | सहेजने के विकल्पों का उपयोग करके दस्तावेज़ को निर्दिष्ट स्ट्रीम पर सहेजता है। |
|
|  | [generatePreview(PreviewOptions previewOptions)](#generatePreview-com.groupdocs.watermark.options.PreviewOptions-) | दस्तावेज़ के लिए पूर्वावलोकन छवियां उत्पन्न करता है। |
|
|  | [search()](#search--) | दस्तावेज़ में सभी संभावित वॉटरमार्क खोजता है। |
|
|  | [search(SearchCriteria searchCriteria)](#search-com.groupdocs.watermark.search.SearchCriteria-) | निर्दिष्ट खोज मानदंडों के अनुसार संभावित वॉटरमार्क खोजता है। |
|
|  | [getImages(ImageSearchCriteria searchCriteria)](#getImages-com.groupdocs.watermark.search.ImageSearchCriteria-) | निर्दिष्ट खोज मानदंडों के अनुसार छवियां खोजता है। |
|
|  | [getImages()](#getImages--) | दस्तावेज़ में सभी छवियां खोजता है। |
|
|  | [<T>getContent(Class<T> contentType)](#-T-getContent-java.lang.Class-T--) | लोड किए गए दस्तावेज़ के लिए `[Content](../../com.groupdocs.watermark.contents/content)` ऑब्जेक्ट लौटाता है। |
|
### Watermarker(String filePath) {#Watermarker-java.lang.String-}
```
public Watermarker(String filePath)
```


निर्दिष्ट दस्तावेज़ पथ के साथ `[Watermarker](../../com.groupdocs.watermark/watermarker)` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

दस्तावेज़ लोड करने के बारे में अधिक जानें:
[Loading documents](../https://docs.groupdocs.com/display/watermarkjava/Loading+documents).

निम्न उदाहरण दर्शाता है कि किसी भी समर्थित फ़ॉर्मेट की सामग्री को कैसे लोड और सहेजा जाए।
>
> ````
> ```
>
>    // Load a content from a file.
>    Watermarker watermarker = new Watermarker("D:\\input.pdf");
>
>    // Use methods of Watermarker class to add, search or remove watermarks.
>
>    // Save changes.
>    watermarker.save("D:\\output.pdf");
>
>    // Free resources.
>    watermarker.close();
>  
> ```
> ````



**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | filePath | java.lang.String | दस्तावेज़ लोड करने के लिए फ़ाइल पथ। |
|

### Watermarker(String filePath, LoadOptions options) {#Watermarker-java.lang.String-com.groupdocs.watermark.options.LoadOptions-}
```
public Watermarker(String filePath, LoadOptions options)
```


निर्दिष्ट दस्तावेज़ पथ और लोड विकल्पों के साथ `[Watermarker](../../com.groupdocs.watermark/watermarker)` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

दस्तावेज़ लोड करने के बारे में अधिक जानें:
[Loading documents](../https://docs.groupdocs.com/display/watermarkjava/Loading+documents).

निम्नलिखित उदाहरण दिखाता है कि पासवर्ड का उपयोग करके एन्क्रिप्टेड PDF दस्तावेज़ को कैसे लोड किया जाए।
>
> ````
> ```
>
>    PdfLoadOptions loadOptions = new PdfLoadOptions();
>    loadOptions.setPassword("123");
>    Watermarker watermarker = new Watermarker("C:\\Documents\\test.pdf", loadOptions);
>    // ...
>    watermarker.close();
>  
> ```
> ````



**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | filePath | java.lang.String | दस्तावेज़ लोड करने के लिए फ़ाइल पथ। |
|
|  | options | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) | दस्तावेज़ लोड करते समय उपयोग करने के लिए अतिरिक्त विकल्प। |
|

### Watermarker(String filePath, WatermarkerSettings settings) {#Watermarker-java.lang.String-com.groupdocs.watermark.WatermarkerSettings-}
```
public Watermarker(String filePath, WatermarkerSettings settings)
```


निर्दिष्ट दस्तावेज़ पथ और सेटिंग्स के साथ `[Watermarker](../../com.groupdocs.watermark/watermarker)` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

दस्तावेज़ लोड करने के बारे में अधिक जानें:
[Loading documents](../https://docs.groupdocs.com/display/watermarkjava/Loading+documents).

निम्नलिखित उदाहरण दिखाता है कि खोज योग्य ऑब्जेक्ट्स को वैश्विक रूप से कैसे सेट किया जाए (सभी दस्तावेज़ों के लिए जो
उसके बाद लोड किए जाएंगे)।
>
> ````
> ```
>
>    WatermarkerSettings settings = new WatermarkerSettings();
>    settings.setSearchableObjects(new SearchableObjects());
>    settings.getSearchableObjects().setWordProcessingSearchableObjects(WordProcessingSearchableObjects.Hyperlinks
>                                                                     | WordProcessingSearchableObjects.Text);
>    settings.getSearchableObjects().setSpreadsheetSearchableObjects(SpreadsheetSearchableObjects.HeadersFooters);
>    settings.getSearchableObjects().setPresentationSearchableObjects(PresentationSearchableObjects.SlidesBackgrounds
>                                                                   | PresentationSearchableObjects.Shapes);
>    settings.getSearchableObjects().setDiagramSearchableObjects(DiagramSearchableObjects.None);
>    settings.getSearchableObjects().setPdfSearchableObjects(PdfSearchableObjects.All);
>
>    for (final File fileEntry : new File("D:\\files").listFiles())
>    {
>       if (fileEntry.isFile()) {
>           Watermarker watermarker = new Watermarker(fileEntry.getPath(), settings);
>           PossibleWatermarkCollection watermarks = watermarker.search();
>           // The code for working with found watermarks goes here.
>           watermarker.close();
>       }
>    }
>  
> ```
> ````



**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | filePath | java.lang.String | दस्तावेज़ लोड करने के लिए फ़ाइल पथ। |
|
|  | settings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) | लोड किए गए दस्तावेज़ के साथ काम करते समय उपयोग करने के लिए अतिरिक्त सेटिंग्स। |
|

### Watermarker(String filePath, LoadOptions options, WatermarkerSettings settings) {#Watermarker-java.lang.String-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-}
```
public Watermarker(String filePath, LoadOptions options, WatermarkerSettings settings)
```


निर्दिष्ट दस्तावेज़ पथ, लोड विकल्प और सेटिंग्स के साथ `[Watermarker](../../com.groupdocs.watermark/watermarker)` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

दस्तावेज़ लोड करने के बारे में अधिक जानें:
[Loading documents](../https://docs.groupdocs.com/display/watermarknet/Loading+documents).

निम्नलिखित उदाहरण दिखाता है कि ईमेल संदेश के बॉडी/विषय में विशिष्ट टेक्स्ट अंशों को कैसे खोजा जाए।
>
> ````
> ```
>
>    WatermarkerSettings settings = new WatermarkerSettings();
>    settings.setSearchableObjects(new SearchableObjects());
>    settings.getSearchableObjects().setEmailSearchableObjects(EmailSearchableObjects.Subject
>                                                            | EmailSearchableObjects.HtmlBody
>                                                            | EmailSearchableObjects.PlainTextBody);
>    EmailLoadOptions loadOptions = new EmailLoadOptions(); 
>    Watermarker watermarker = new Watermarker("D:\\test.msg", loadOptions, settings);
>    SearchCriteria criteria = new TextSearchCriteria("test", false);
>    // Note, search is performed only if you pass TextSearchCriteria instance to search() method
>    PossibleWatermarkCollection watermarks = watermarker.search(criteria);
>    // Remove found text fragments
>    watermarks.clear();
>    // Save changes
>    watermarker.save("D:\\modified_test.msg");
>    watermarker.close();
>  
> ```
> ````



**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | filePath | java.lang.String | दस्तावेज़ लोड करने के लिए फ़ाइल पथ। |
|
|  | options | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) | दस्तावेज़ लोड करते समय उपयोग करने के लिए अतिरिक्त विकल्प। |
|
|  | settings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) | लोड किए गए दस्तावेज़ के साथ काम करते समय उपयोग करने के लिए अतिरिक्त सेटिंग्स। |
|

### Watermarker(InputStream document) {#Watermarker-java.io.InputStream-}
```
public Watermarker(InputStream document)
```


निर्दिष्ट स्ट्रीम के साथ `[Watermarker](../../com.groupdocs.watermark/watermarker)` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

दस्तावेज़ लोड करने के बारे में अधिक जानें:
[Loading documents](../https://docs.groupdocs.com/display/watermarknet/Loading+documents).

निम्नलिखित उदाहरण दिखाता है कि किसी भी समर्थित फ़ॉर्मेट के दस्तावेज़ को कैसे लोड और सहेजा जाए।
>
> ````
> ```
>
>    // Load a content from a stream.
>    FileInputStream inputStream = new FileInputStream("D:\\input.pdf");
>    FileOutputStream outputStream = new FileOutputStream("D:\\output.pdf");
>    Watermarker watermarker = new Watermarker(inputStream);
>    // Use methods of Watermarker class to add, search or remove watermarks.
>
>    // Save changes.
>    watermarker.save(outputStream);
>    watermarker.close();
>    outputStream.close();
>    inputStream.close();
>  
> ```
> ````



**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | दस्तावेज़ | java.io.InputStream | दस्तावेज़ लोड करने के लिए स्ट्रीम। |
|

### Watermarker(InputStream document, LoadOptions options) {#Watermarker-java.io.InputStream-com.groupdocs.watermark.options.LoadOptions-}
```
public Watermarker(InputStream document, LoadOptions options)
```


निर्दिष्ट स्ट्रीम और लोड विकल्पों के साथ `[Watermarker](../../com.groupdocs.watermark/watermarker)` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

दस्तावेज़ लोड करने के बारे में अधिक जानें:
[Loading documents](../https://docs.groupdocs.com/display/watermarknet/Loading+documents).

निम्नलिखित उदाहरण दिखाता है कि पासवर्ड का उपयोग करके एन्क्रिप्टेड PDF दस्तावेज़ को कैसे लोड किया जाए।
>
> ````
> ```
>
>    PdfLoadOptions loadOptions = new PdfLoadOptions();
>    loadOptions.setPassword("123");
>    FileInputStream inputStream = new FileInputStream("D:\\input.pdf");
>    Watermarker watermarker = new Watermarker(inputStream, loadOptions);
>    // ...
>
>    watermarker.close();
>    inputStream.close();
>  
> ```
> ````



**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | दस्तावेज़ | java.io.InputStream | दस्तावेज़ लोड करने के लिए स्ट्रीम। |
|
|  | options | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) | दस्तावेज़ लोड करते समय उपयोग करने के लिए अतिरिक्त विकल्प। |
|

### Watermarker(InputStream document, WatermarkerSettings settings) {#Watermarker-java.io.InputStream-com.groupdocs.watermark.WatermarkerSettings-}
```
public Watermarker(InputStream document, WatermarkerSettings settings)
```


निर्दिष्ट स्ट्रीम और सेटिंग्स के साथ `[Watermarker](../../com.groupdocs.watermark/watermarker)` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

दस्तावेज़ लोड करने के बारे में अधिक जानें:
[Loading documents](../https://docs.groupdocs.com/display/watermarknet/Loading+documents).

निम्नलिखित उदाहरण दिखाता है कि खोज योग्य ऑब्जेक्ट्स को वैश्विक रूप से कैसे सेट किया जाए (सभी दस्तावेज़ों के लिए जो
उसके बाद लोड किए जाएंगे)।
>
> ````
> ```
>
>    WatermarkerSettings settings = new WatermarkerSettings();
>    settings.setSearchableObjects(new SearchableObjects());
>    settings.getSearchableObjects().setWordProcessingSearchableObjects(WordProcessingSearchableObjects.Hyperlinks
>                                                                     | WordProcessingSearchableObjects.Text);
>    settings.getSearchableObjects().setSpreadsheetSearchableObjects(SpreadsheetSearchableObjects.HeadersFooters);
>    settings.getSearchableObjects().setPresentationSearchableObjects(PresentationSearchableObjects.SlidesBackgrounds
>                                                                   | PresentationSearchableObjects.Shapes);
>    settings.getSearchableObjects().setDiagramSearchableObjects(DiagramSearchableObjects.None);
>    settings.getSearchableObjects().setPdfSearchableObjects(PdfSearchableObjects.All);
>
>    for (final File fileEntry : new File("D:\\files").listFiles())
>    {
>       if (fileEntry.isFile()) {
>           FileInputStream inputStream = new FileInputStream(fileEntry.getPath());
>           Watermarker watermarker = new Watermarker(inputStream, settings);
>           PossibleWatermarkCollection watermarks = watermarker.Search();
>           // The code for working with found watermarks goes here.
>           watermarker.close();
>           inputStream.close();
>       }
>    }
>  
> ```
> ````



**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | दस्तावेज़ | java.io.InputStream | दस्तावेज़ लोड करने के लिए स्ट्रीम। |
|
|  | settings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) | लोड किए गए दस्तावेज़ के साथ काम करते समय उपयोग करने के लिए अतिरिक्त सेटिंग्स। |
|

### Watermarker(InputStream document, LoadOptions options, WatermarkerSettings settings) {#Watermarker-java.io.InputStream-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-}
```
public Watermarker(InputStream document, LoadOptions options, WatermarkerSettings settings)
```


निर्दिष्ट स्ट्रीम, लोड विकल्प और सेटिंग्स के साथ क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

दस्तावेज़ लोड करने के बारे में अधिक जानें:
[Loading documents](../https://docs.groupdocs.com/display/watermarknet/Loading+documents).

निम्नलिखित उदाहरण दिखाता है कि खोज योग्य ऑब्जेक्ट्स को वैश्विक रूप से कैसे सेट किया जाए (सभी दस्तावेज़ों के लिए जो
उसके बाद लोड किए जाएंगे)।
>
> ````
> ```
>
>    WatermarkerSettings settings = new WatermarkerSettings();
>    settings.setSearchableObjects(new SearchableObjects());
>    settings.getSearchableObjects().setEmailSearchableObjects(EmailSearchableObjects.Subject
>                                                            | EmailSearchableObjects.HtmlBody
>                                                            | EmailSearchableObjects.PlainTextBody);
>    FileInputStream inputStream = new FileInputStream("D:\\test.msg");
>    FileOutputStream outputStream = new FileOutputStream("D:\\modified_test.msg");
>    EmailLoadOptions loadOptions = new EmailLoadOptions(); 
>    Watermarker watermarker = new Watermarker(inputStream, loadOptions, settings);
>    SearchCriteria criteria = new TextSearchCriteria("test", false);
>    // Note, search is performed only if you pass TextSearchCriteria instance to search() method
>    PossibleWatermarkCollection watermarks = watermarker.search(criteria);
>    // Remove found text fragments
>    watermarks.clear();
>    // Save changes
>    watermarker.save(outputStream);
>    watermarker.close();
>    outputStream.close();
>    inputStream.close();
>  
> ```
> ````



**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | दस्तावेज़ | java.io.InputStream | दस्तावेज़ लोड करने के लिए स्ट्रीम। |
|
|  | options | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) | दस्तावेज़ लोड करते समय उपयोग करने के लिए अतिरिक्त विकल्प। |
|
|  | settings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) | लोड किए गए दस्तावेज़ के साथ काम करते समय उपयोग करने के लिए अतिरिक्त सेटिंग्स। |
|

### Watermarker(System.IO.Stream document, LoadOptions options, WatermarkerSettings settings) {#Watermarker-com.aspose.ms.System.IO.Stream-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-}
```
public Watermarker(System.IO.Stream document, LoadOptions options, WatermarkerSettings settings)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| दस्तावेज़ | com.aspose.ms.System.IO.Stream |  |
| options | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) |  |
| settings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) |  |

### getSearchableObjects() {#getSearchableObjects--}
```
public final SearchableObjects getSearchableObjects()
```


वॉटरमार्क खोज में शामिल किए जाने वाले सामग्री ऑब्जेक्ट्स को प्राप्त करता है।

यह विधि भी उन कंटेंट ऑब्जेक्ट्स को निर्दिष्ट करती है जो इमेज खोज में उपयोग होते हैं।
अधिक जानकारी के लिए देखें `#search(SearchCriteria).search(SearchCriteria)`
और `#getImages().getImages()` मेथड्स।

वॉटरमार्क खोज के बारे में अधिक जानें:
[Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks).

निम्नलिखित उदाहरण दिखाता है कि PDF दस्तावेज़ से सभी XObjects और आर्टिफैक्ट्स को कैसे हटाया जाए।
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("D:\\test.pdf");
>    watermarker.getSearchableObjects().setPdfSearchableObjects(PdfSearchableObjects.XObjects
>                                                             | PdfSearchableObjects.Artifacts);
>    PossibleWatermarkCollection watermarks = watermarker.search();
>    // Remove all found objects.
>    watermarks.clear();
>    // Save changes.
>    watermarker.save("D:\\modified_test.pdf");
>    watermarker.close();
>  
> ```
> ````



**Returns:**
[SearchableObjects](../../com.groupdocs.watermark.search/searchableobjects) - The objects that are to be included in a watermark search.

### setSearchableObjects(SearchableObjects value) {#setSearchableObjects-com.groupdocs.watermark.search.SearchableObjects-}
```
public final void setSearchableObjects(SearchableObjects value)
```


वॉटरमार्क खोज में शामिल किए जाने वाले सामग्री ऑब्जेक्ट्स को सेट करता है।

यह विधि भी उन कंटेंट ऑब्जेक्ट्स को निर्दिष्ट करती है जो इमेज खोज में उपयोग होते हैं।
अधिक जानकारी के लिए देखें `#search(SearchCriteria).search(SearchCriteria)`
और `#getImages().getImages()` मेथड्स।
वॉटरमार्क खोज के बारे में अधिक जानें:
[Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks).

निम्नलिखित उदाहरण दिखाता है कि PDF दस्तावेज़ से सभी XObjects और आर्टिफैक्ट्स को कैसे हटाया जाए।
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("D:\\test.pdf");
>    watermarker.getSearchableObjects().setPdfSearchableObjects(PdfSearchableObjects.XObjects
>                                                             | PdfSearchableObjects.Artifacts);
>    PossibleWatermarkCollection watermarks = watermarker.search();
>    // Remove all found objects.
>    watermarks.clear();
>    // Save changes.
>    watermarker.save("D:\\modified_test.pdf");
>    watermarker.close();
>  
> ```
> ````



**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | value | [SearchableObjects](../../com.groupdocs.watermark.search/searchableobjects) | वॉटरमार्क खोज में शामिल किए जाने वाले ऑब्जेक्ट्स। |
|

### dispose() {#dispose--}
```
public final void dispose()
```




### close() {#close--}
```
public final void close()
```


वर्तमान इंस्टेंस को नष्ट करता है।


### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


लोड किए गए दस्तावेज़ के फ़ॉर्मेट के बारे में जानकारी प्राप्त करता है।

दस्तावेज़ जानकारी प्राप्त करने के बारे में अधिक जानें
[Get document info](../https://docs.groupdocs.com/display/watermarkjava/Get+document+info).

निम्नलिखित उदाहरण दिखाता है कि किसी भी समर्थित प्रकार के दस्तावेज़ की जानकारी कैसे प्राप्त की जाए।
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("D:\\test.ppt");
>    IDocumentInfo info = watermarker.getDocumentInfo();
>    System.out.println("File type: " + info.getFileType());
>    System.out.println("Number of pages: " + info.getPageCount());
>    System.out.println("Document size: " + info.getSize() + " bytes");
>    watermarker.close();
>  
> ```
> ````



**Returns:**
[IDocumentInfo](../../com.groupdocs.watermark.common/idocumentinfo) - The `[IDocumentInfo](../../com.groupdocs.watermark.common/idocumentinfo)` instance that contains detected information.

### add(Watermark watermark) {#add-com.groupdocs.watermark.Watermark-}
```
public final void add(Watermark watermark)
```


लोड किए गए दस्तावेज़ में एक वॉटरमार्क जोड़ता है।

वॉटरमार्क जोड़ने के बारे में अधिक जानें:
[Adding watermarks](../https://docs.groupdocs.com/display/watermarkjava/Adding+watermarks).

निम्नलिखित उदाहरण दिखाता है कि किसी भी समर्थित प्रकार के दस्तावेज़ में इमेज और टेक्स्ट वॉटरमार्क कैसे जोड़ा जाए।
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("D:\\input.pdf");
>
>    TextWatermark textWatermark = new TextWatermark("DRAFT", new Font("Arial", 19));
>    textWatermark.setHorizontalAlignment(HorizontalAlignment.Center);
>    textWatermark.setVerticalAlignment(VerticalAlignment.Top);
>    textWatermark.setConsiderParentMargins(true);
>    textWatermark.setForegroundColor(Color.getRed());
>    textWatermark.setBackground(true);
>    textWatermark.setOpacity(0.5);
>    watermarker.add(textWatermark);
>  
>    ImageWatermark imageWatermark = new ImageWatermark("D:\\draft.png"));
>    imageWatermark.setHorizontalAlignment(HorizontalAlignment.Center);
>    imageWatermark.setVerticalAlignment(VerticalAlignment.Bottom);
>    imageWatermark.setConsiderParentMargins(true);
>    imageWatermark.setBackground(true);
>    imageWatermark.setOpacity(0.5);
>    watermarker.add(imageWatermark);
>    imageWatermark.close();
>
>    watermarker.save("D:\\output.pdf");
>    watermarker.close();
>  
> ```
> ````



**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | watermark | [Watermark](../../com.groupdocs.watermark/watermark) | दस्तावेज़ में जोड़ने के लिए वॉटरमार्क। |
|

### add(Watermark watermark, WatermarkOptions options) {#add-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.WatermarkOptions-}
```
public final void add(Watermark watermark, WatermarkOptions options)
```


वॉटरमार्क विकल्पों का उपयोग करके लोड किए गए दस्तावेज़ में वॉटरमार्क जोड़ता है।

वॉटरमार्क जोड़ने के बारे में अधिक जानें:
[Adding watermarks](../https://docs.groupdocs.com/display/watermarkjava/Adding+watermarks).

निम्नलिखित उदाहरण दिखाता है कि PDF दस्तावेज़ के किसी विशेष पृष्ठ पर इमेज वॉटरमार्क कैसे जोड़ा जाए।
>
> ````
> ```
>
>    PdfLoadOptions loadOptions = new PdfLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\input.pdf", loadOptions);
>
>    ImageWatermark imageWatermark = new ImageWatermark("D:\\draft.png"));
>    PdfXObjectWatermarkOptions options = new PdfXObjectWatermarkOptions();
>    options.setPageIndex(0);
>    watermarker.add(imageWatermark, options);
>    imageWatermark.close();
>
>    watermarker.save("D:\\output.pdf");
>    watermarker.close();
>  
> ```
> ````



**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | watermark | [Watermark](../../com.groupdocs.watermark/watermark) | दस्तावेज़ में जोड़ने के लिए वॉटरमार्क। |
|
|  | options | [WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions) | वॉटरमार्क जोड़ते समय उपयोग करने के लिए अतिरिक्त विकल्प। |
|

### remove(PossibleWatermark possibleWatermark) {#remove-com.groupdocs.watermark.search.PossibleWatermark-}
```
public final void remove(PossibleWatermark possibleWatermark)
```


दस्तावेज़ से वॉटरमार्क हटाता है।

वॉटरमार्क हटाने के बारे में अधिक जानें:
[Removing found watermarks](../https://docs.groupdocs.com/display/watermarkjava/Removing+found+watermarks).

निम्नलिखित उदाहरण दिखाता है कि विशिष्ट वाले पहले संभावित वॉटरमार्क को कैसे खोजें और हटाएँ
किसी भी समर्थित प्रकार के दस्तावेज़ से टेक्स्ट या इमेज।
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("D:\\input.doc");
>    ImageSearchCriteria imageSearchCriteria = new ImageDctHashSearchCriteria("D:\\logo.png");
>    TextSearchCriteria textSearchCriteria = new TextSearchCriteria(Pattern.compile("^Company\\sName$"));
>    PossibleWatermarkCollection watermarks = watermarker.search(textSearchCriteria.or(imageSearchCriteria));
>    if (watermarks.getCount() > 0)
>    {
>        watermarker.remove(watermarks.get_Item(0));
>    }
>
>    watermarker.save("D:\\output.doc");
>    watermarker.close();
>  
> ```
> ````



**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | possibleWatermark | [PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark) | हटाने के लिए वॉटरमार्क। |
|

### remove(PossibleWatermarkCollection possibleWatermarks) {#remove-com.groupdocs.watermark.search.PossibleWatermarkCollection-}
```
public final void remove(PossibleWatermarkCollection possibleWatermarks)
```


संग्रह में सभी वॉटरमार्क को दस्तावेज़ से हटाता है।

वॉटरमार्क हटाने के बारे में अधिक जानें:
[Removing found watermarks](../https://docs.groupdocs.com/display/watermarkjava/Removing+found+watermarks).

निम्नलिखित उदाहरण दिखाता है कि विशिष्ट वाले सभी संभावित वॉटरमार्क को कैसे खोजें और हटाएँ
किसी भी समर्थित प्रकार के दस्तावेज़ से टेक्स्ट या इमेज।
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("D:\\input.doc");
>    ImageSearchCriteria imageSearchCriteria = new ImageDctHashSearchCriteria("D:\\logo.png");
>    TextSearchCriteria textSearchCriteria = new TextSearchCriteria(Pattern.compile("^Company\\sName$"));
>    PossibleWatermarkCollection watermarks = watermarker.search(textSearchCriteria.or(imageSearchCriteria));
>    watermarker.remove(watermarks);
>    watermarker.save("D:\\output.doc");
>    watermarker.close();
>  
> ```
> ````



**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | possibleWatermarks | [PossibleWatermarkCollection](../../com.groupdocs.watermark.search/possiblewatermarkcollection) | हटाने के लिए वॉटरमार्क का संग्रह। |
|

### save(String filePath) {#save-java.lang.String-}
```
public final void save(String filePath)
```


दस्तावेज़ को निर्दिष्ट फ़ाइल स्थान पर सहेजता है।

दस्तावेज़ सहेजने के बारे में अधिक जानें
[Saving documents](../https://docs.groupdocs.com/display/watermarkjava/Saving+documents).

निम्नलिखित उदाहरण दिखाता है कि वॉटरमार्क कैसे जोड़ें और दस्तावेज़ को किसी अन्य फ़ाइल में सहेजें।
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("input.pdf");
>    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
>    watermarker.add(watermark);
>    watermarker.save("output.pdf");
>    watermarker.close();
>  
> ```
> ````



**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | filePath | java.lang.String | दस्तावेज़ डेटा को सहेजने के लिए फ़ाइल पथ। |
|

### save(OutputStream document) {#save-java.io.OutputStream-}
```
public final void save(OutputStream document)
```


दस्तावेज़ को निर्दिष्ट स्ट्रीम पर सहेजता है।

दस्तावेज़ सहेजने के बारे में अधिक जानें
[Saving documents](../https://docs.groupdocs.com/display/watermarkjava/Saving+documents).

निम्नलिखित उदाहरण दिखाता है कि वॉटरमार्क कैसे जोड़ें और दस्तावेज़ को मेमोरी स्ट्रीम में कैसे सहेजें।
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("input.pdf");
>    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
>    watermarker.add(watermark);
>    ByteArrayOutputStream outputStream = new ByteArrayOutputStream();
>    watermarker.save(outputStream);
>    // ...
>    outputStream.close();
>    watermarker.close();
>  
> ```
> ````



**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | दस्तावेज़ | java.io.OutputStream | दस्तावेज़ डेटा को सहेजने के लिए स्ट्रीम। |
|

### save(String filePath, SaveOptions options) {#save-java.lang.String-com.groupdocs.watermark.options.SaveOptions-}
```
public final void save(String filePath, SaveOptions options)
```


सहेजने के विकल्पों का उपयोग करके दस्तावेज़ को निर्दिष्ट फ़ाइल स्थान पर सहेजता है।

दस्तावेज़ सहेजने के बारे में अधिक जानें
[Saving documents](../https://docs.groupdocs.com/display/watermarkjava/Saving+documents).

निम्नलिखित उदाहरण दिखाता है कि वॉटरमार्क कैसे जोड़ें और दस्तावेज़ को किसी अन्य फ़ाइल में कैसे सहेजें।
डिफ़ॉल्ट `[SaveOptions](../../com.groupdocs.watermark.options/saveoptions)` के साथ।
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("input.pdf");
>    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
>    watermarker.add(watermark);
>    watermarker.save("output.pdf", new SaveOptions());
>    watermarker.close();
>  
> ```
> ````



**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | filePath | java.lang.String | दस्तावेज़ डेटा को सहेजने के लिए फ़ाइल पथ। |
|
|  | options | [SaveOptions](../../com.groupdocs.watermark.options/saveoptions) | दस्तावेज़ सहेजते समय उपयोग करने के लिए अतिरिक्त विकल्प। |
|

### save(OutputStream document, SaveOptions options) {#save-java.io.OutputStream-com.groupdocs.watermark.options.SaveOptions-}
```
public final void save(OutputStream document, SaveOptions options)
```


सहेजने के विकल्पों का उपयोग करके दस्तावेज़ को निर्दिष्ट स्ट्रीम पर सहेजता है।

दस्तावेज़ सहेजने के बारे में अधिक जानें
[Saving documents](../https://docs.groupdocs.com/display/watermarkjava/Saving+documents).

निम्नलिखित उदाहरण दिखाता है कि वॉटरमार्क कैसे जोड़ें और दस्तावेज़ को मेमोरी स्ट्रीम में कैसे सहेजें।
डिफ़ॉल्ट `[SaveOptions](../../com.groupdocs.watermark.options/saveoptions)` के साथ।
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("input.pdf");
>    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
>    watermarker.add(watermark);
>    ByteArrayOutputStream outputStream = new ByteArrayOutputStream();
>    watermarker.save(outputStream, new SaveOptions());
>    // ...
>    outputStream.close();
>    watermarker.close();
>  
> ```
> ````



**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | दस्तावेज़ | java.io.OutputStream | दस्तावेज़ डेटा को सहेजने के लिए स्ट्रीम। |
|
|  | options | [SaveOptions](../../com.groupdocs.watermark.options/saveoptions) | दस्तावेज़ सहेजते समय उपयोग करने के लिए अतिरिक्त विकल्प। |
|

### generatePreview(PreviewOptions previewOptions) {#generatePreview-com.groupdocs.watermark.options.PreviewOptions-}
```
public final void generatePreview(PreviewOptions previewOptions)
```


दस्तावेज़ के लिए पूर्वावलोकन छवियां उत्पन्न करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | previewOptions | [PreviewOptions](../../com.groupdocs.watermark.options/previewoptions) | पूर्वावलोकन छवियों को उत्पन्न करते समय उपयोग करने के लिए अतिरिक्त विकल्प। |
|

### search() {#search--}
```
public final PossibleWatermarkCollection search()
```


दस्तावेज़ में सभी संभावित वॉटरमार्क खोजता है।

खोज उन वस्तुओं में की जाती है जो `#setSearchableObjects(SearchableObjects).setSearchableObjects(SearchableObjects)` के साथ निर्दिष्ट हैं।

वॉटरमार्क खोज के बारे में अधिक जानें।
[Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks).

निम्नलिखित उदाहरण दिखाता है कि किसी भी समर्थित प्रकार के दस्तावेज़ में संभावित वॉटरमार्क को कैसे गिना जाए।
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("input.doc");
>    PossibleWatermarkCollection watermarks = watermarker.search();
>    System.out.println(watermarks.getCount());
>    watermarker.close();
>  
> ```
> ````



**Returns:**
[PossibleWatermarkCollection](../../com.groupdocs.watermark.search/possiblewatermarkcollection)
### search(SearchCriteria searchCriteria) {#search-com.groupdocs.watermark.search.SearchCriteria-}
```
public final PossibleWatermarkCollection search(SearchCriteria searchCriteria)
```


निर्दिष्ट खोज मानदंडों के अनुसार संभावित वॉटरमार्क खोजता है।

खोज उन वस्तुओं में की जाती है जो `#setSearchableObjects(SearchableObjects).setSearchableObjects(SearchableObjects)` के साथ निर्दिष्ट हैं।

वॉटरमार्क खोज के बारे में अधिक जानें।
[Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks).

निम्नलिखित उदाहरण दिखाता है कि विशेष पाठ वाले सभी संभावित वॉटरमार्क को कैसे खोजें और हटाएँ।
या किसी भी समर्थित प्रकार के दस्तावेज़ से छवि।
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("input.doc");
>    ImageSearchCriteria imageSearchCriteria = new ImageDctHashSearchCriteria("logo.png");
>    TextSearchCriteria textSearchCriteria = new TextSearchCriteria(Pattern.compile("^Company\\sName$"));
>    PossibleWatermarkCollection watermarks = watermarker.search(textSearchCriteria.or(imageSearchCriteria));
>    watermarks.clear();
>    watermarker.save("output.doc");
>    watermarker.close();
>  
> ```
> ````



**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | searchCriteria | [SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) | उपयोग करने के लिए खोज मानदंड। |
|

**Returns:**
[PossibleWatermarkCollection](../../com.groupdocs.watermark.search/possiblewatermarkcollection)
### getImages(ImageSearchCriteria searchCriteria) {#getImages-com.groupdocs.watermark.search.ImageSearchCriteria-}
```
public final WatermarkableImageCollection getImages(ImageSearchCriteria searchCriteria)
```


निर्दिष्ट खोज मानदंडों के अनुसार छवियां खोजता है।

खोज उन वस्तुओं में की जाती है जो `#setSearchableObjects(SearchableObjects).setSearchableObjects(SearchableObjects)` के साथ निर्दिष्ट हैं।

वॉटरमार्क खोज के बारे में अधिक जानें।
[Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks).

निम्नलिखित उदाहरण दिखाता है कि संदर्भ के समान सभी छवियों को कैसे हटाएँ।
किसी भी समर्थित प्रकार के दस्तावेज़ से।
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("input.doc");
>    ImageThumbnailSearchCriteria criteria = new ImageThumbnailSearchCriteria("reference.png");
>    WatermarkableImageCollection images = watermarker.getImages(criteria);
>    images.clear();
>    watermarker.save("output.doc");
>    watermarker.close();
>  
> ```
> ````



**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | searchCriteria | [ImageSearchCriteria](../../com.groupdocs.watermark.search/imagesearchcriteria) | उपयोग करने के लिए खोज मानदंड। |
|

**Returns:**
[WatermarkableImageCollection](../../com.groupdocs.watermark.contents/watermarkableimagecollection)
### getImages() {#getImages--}
```
public final WatermarkableImageCollection getImages()
```


दस्तावेज़ में सभी छवियां खोजता है।

खोज उन वस्तुओं में की जाती है जो `#setSearchableObjects(SearchableObjects).setSearchableObjects(SearchableObjects)` के साथ निर्दिष्ट हैं।

वॉटरमार्क खोज के बारे में अधिक जानें।
[Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks).

निम्नलिखित उदाहरण दिखाता है कि किसी भी समर्थित प्रकार के दस्तावेज़ में सभी छवियों में वॉटरमार्क कैसे जोड़ें।
>
> ````
> ```
>
>    Watermarker watermarker = new Watermarker("input.doc");
>    // Initialize text or image watermark.
>    TextWatermark watermark = new TextWatermark("DRAFT", new Font("Arial", 19));
>
>    // Find all images in the document.
>    WatermarkableImageCollection images = watermarker.getImages();
>
>    // Add watermark.
>    for (WatermarkableImage watermarkableImage : images)
>    {
>        watermarkableImage.addWatermark(watermark);
>    }
>
>    // Save changes.
>    watermarker.save("output.doc");
>    watermarker.close();
>  
> ```
> ````



**Returns:**
[WatermarkableImageCollection](../../com.groupdocs.watermark.contents/watermarkableimagecollection) - The collection of found images.

### <T>getContent(Class<T> contentType) {#-T-getContent-java.lang.Class-T--}
```
public final T <T>getContent(Class<T> contentType)
```


लोड किए गए दस्तावेज़ के लिए `[Content](../../com.groupdocs.watermark.contents/content)` ऑब्जेक्ट लौटाता है।

निम्नलिखित उदाहरण दिखाता है कि जोड़े गए वॉटरमार्क के साथ PDF दस्तावेज़ पृष्ठ को कैसे रास्टराइज़ करें।
>
> ````
> ```
>
>    PdfLoadOptions loadOptions = new PdfLoadOptions();
>    Watermarker watermarker = new Watermarker("input.pdf", loadOptions);
>    ImageWatermark watermark = new ImageWatermark("watermark.png")
>    watermarker.add(watermark);
>    PdfContent content = watermarker.getContent(PdfContent.class);
>    content.rasterize(300, 300, PdfImageConversionFormat.Png);
>    watermarker.save("output.pdf");
>    watermarker.close();
>  
> ```
> ````



**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | contentType | java.lang.Class<T> | एक `[Content](../../com.groupdocs.watermark.contents/content)` वस्तु का अनुरोधित प्रकार। |
|

**Returns:**
T - लोड किए गए दस्तावेज़ के लिए `[Content](../../com.groupdocs.watermark.contents/content)` वस्तु।

