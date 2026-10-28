---
title: "ImageDctHashSearchCriteria"
second_title: "GroupDocs.Watermark के लिए Java API संदर्भ"
description: "दस्तावेज़ में छवियों को खोजने के लिए एक खोज मानदंड का प्रतिनिधित्व करता है।"
type: docs
weight: 31
url: /hi/java/com.groupdocs.watermark.search/imagedcthashsearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria), [com.groupdocs.watermark.search.PageSearchCriteria](../../com.groupdocs.watermark.search/pagesearchcriteria), [com.groupdocs.watermark.search.ImageSearchCriteria](../../com.groupdocs.watermark.search/imagesearchcriteria)
```
public class ImageDctHashSearchCriteria extends ImageSearchCriteria
```

दस्तावेज़ में छवियों को खोजने के लिए एक खोज मानदंड का प्रतिनिधित्व करता है।

यह खोज मानदंड इमेज समानता की गणना के लिए DCT-आधारित परसेप्चुअल इमेज हैश का उपयोग करता है।

**Learn more:**

* [Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks)

निम्न उदाहरण दिखाता है कि संलग्न फ़ाइलों (pdf) में छवियों की खोज कैसे की जाए।
>
> ````
> ```
>
>    WatermarkerSettings settings = new WatermarkerSettings();
>    settings.setSearchableObjects(new SearchableObjects());
>    settings.getSearchableObjects().setPdfSearchableObjects(PdfSearchableObjects.All);
>    PdfLoadOptions loadOptions = new PdfLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.pdf", loadOptions);
>    
>    // Specify sample image to compare document images with
>    ImageSearchCriteria criteria = new ImageDctHashSearchCriteria("D:\\sample.png");
>    // Search for similar images
>    PossibleWatermarkCollection possibleWatermarks = watermarker.search(criteria);
>    // Remove or modify found image watermarks
>    // ...
>    
>    watermarker.close();
>  
> ```
> ````


## निर्माताएँ

| निर्माता | विवरण |
| --- | --- |
|  | [ImageDctHashSearchCriteria(String filePath)](#ImageDctHashSearchCriteria-java.lang.String-) | निर्दिष्ट फ़ाइल पथ के साथ `[ImageDctHashSearchCriteria](../../com.groupdocs.watermark.search/imagedcthashsearchcriteria)` क्लास का नया इंस्टेंस प्रारंभ करता है। |
|
|  | [ImageDctHashSearchCriteria(InputStream stream)](#ImageDctHashSearchCriteria-java.io.InputStream-) | निर्दिष्ट स्ट्रीम के साथ `[ImageDctHashSearchCriteria](../../com.groupdocs.watermark.search/imagedcthashsearchcriteria)` क्लास का नया इंस्टेंस प्रारंभ करता है। |
|
| [ImageDctHashSearchCriteria(System.IO.Stream stream)](#ImageDctHashSearchCriteria-com.aspose.ms.System.IO.Stream-) |  |
### ImageDctHashSearchCriteria(String filePath) {#ImageDctHashSearchCriteria-java.lang.String-}
```
public ImageDctHashSearchCriteria(String filePath)
```


निर्दिष्ट फ़ाइल पथ के साथ `[ImageDctHashSearchCriteria](../../com.groupdocs.watermark.search/imagedcthashsearchcriteria)` क्लास का नया इंस्टेंस प्रारंभ करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | filePath | java.lang.String | छवि लोड करने के लिए फ़ाइल पथ। |
|

### ImageDctHashSearchCriteria(InputStream stream) {#ImageDctHashSearchCriteria-java.io.InputStream-}
```
public ImageDctHashSearchCriteria(InputStream stream)
```


निर्दिष्ट स्ट्रीम के साथ `[ImageDctHashSearchCriteria](../../com.groupdocs.watermark.search/imagedcthashsearchcriteria)` क्लास का नया इंस्टेंस प्रारंभ करता है।


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | stream | java.io.InputStream | छवि लोड करने के लिए स्ट्रीम। |
|

### ImageDctHashSearchCriteria(System.IO.Stream stream) {#ImageDctHashSearchCriteria-com.aspose.ms.System.IO.Stream-}
```
public ImageDctHashSearchCriteria(System.IO.Stream stream)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

