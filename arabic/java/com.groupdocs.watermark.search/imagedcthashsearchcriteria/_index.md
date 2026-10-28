---
title: "ImageDctHashSearchCriteria"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يمثل معيار بحث للعثور على الصور في المستند."
type: docs
weight: 31
url: /ar/java/com.groupdocs.watermark.search/imagedcthashsearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria), [com.groupdocs.watermark.search.PageSearchCriteria](../../com.groupdocs.watermark.search/pagesearchcriteria), [com.groupdocs.watermark.search.ImageSearchCriteria](../../com.groupdocs.watermark.search/imagesearchcriteria)
```
public class ImageDctHashSearchCriteria extends ImageSearchCriteria
```

يمثل معيار بحث للعثور على الصور في المستند.

يستخدم هذا المعيار للبحث تجزئة صورة إدراكية تعتمد على DCT لحساب تشابه الصور.

**Learn more:**

* [Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks)

يوضح المثال التالي كيفية البحث عن الصور في الملفات المرفقة (pdf).
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


## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [ImageDctHashSearchCriteria(String filePath)](#ImageDctHashSearchCriteria-java.lang.String-) | ينشئ مثيلاً جديدًا من الفئة `[ImageDctHashSearchCriteria](../../com.groupdocs.watermark.search/imagedcthashsearchcriteria)` بمسار ملف محدد. |
|
|  | [ImageDctHashSearchCriteria(InputStream stream)](#ImageDctHashSearchCriteria-java.io.InputStream-) | ينشئ مثيلاً جديدًا من الفئة `[ImageDctHashSearchCriteria](../../com.groupdocs.watermark.search/imagedcthashsearchcriteria)` بتدفق محدد. |
|
| [ImageDctHashSearchCriteria(System.IO.Stream stream)](#ImageDctHashSearchCriteria-com.aspose.ms.System.IO.Stream-) |  |
### ImageDctHashSearchCriteria(String filePath) {#ImageDctHashSearchCriteria-java.lang.String-}
```
public ImageDctHashSearchCriteria(String filePath)
```


ينشئ مثيلاً جديدًا من الفئة `[ImageDctHashSearchCriteria](../../com.groupdocs.watermark.search/imagedcthashsearchcriteria)` بمسار ملف محدد.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePath | java.lang.String | مسار الملف لتحميل الصورة منه. |
|

### ImageDctHashSearchCriteria(InputStream stream) {#ImageDctHashSearchCriteria-java.io.InputStream-}
```
public ImageDctHashSearchCriteria(InputStream stream)
```


ينشئ مثيلاً جديدًا من الفئة `[ImageDctHashSearchCriteria](../../com.groupdocs.watermark.search/imagedcthashsearchcriteria)` بتدفق محدد.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | stream | java.io.InputStream | التدفق لتحميل الصورة منه. |
|

### ImageDctHashSearchCriteria(System.IO.Stream stream) {#ImageDctHashSearchCriteria-com.aspose.ms.System.IO.Stream-}
```
public ImageDctHashSearchCriteria(System.IO.Stream stream)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

