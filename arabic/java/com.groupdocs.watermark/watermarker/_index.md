---
title: "محدد العلامات المائية"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يمثل فئة لإدارة العلامات المائية في مستند."
type: docs
weight: 14
url: /ar/java/com.groupdocs.watermark/watermarker/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class Watermarker implements Closeable
```

يمثل فئة لإدارة العلامات المائية في مستند.

يوضح المثال التالي كيفية تحميل وحفظ محتوى بأي تنسيق مدعوم.
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


## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [Watermarker(String filePath)](#Watermarker-java.lang.String-) | يُهيئ نسخة جديدة من الفئة `[Watermarker](../../com.groupdocs.watermark/watermarker)` بالمسار المحدد للمستند. |
|
|  | [Watermarker(String filePath, LoadOptions options)](#Watermarker-java.lang.String-com.groupdocs.watermark.options.LoadOptions-) | يُهيئ نسخة جديدة من الفئة `[Watermarker](../../com.groupdocs.watermark/watermarker)` بالمسار المحدد للمستند وخيارات التحميل. |
|
|  | [Watermarker(String filePath, WatermarkerSettings settings)](#Watermarker-java.lang.String-com.groupdocs.watermark.WatermarkerSettings-) | يُهيئ نسخة جديدة من الفئة `[Watermarker](../../com.groupdocs.watermark/watermarker)` بالمسار المحدد للمستند والإعدادات. |
|
|  | [Watermarker(String filePath, LoadOptions options, WatermarkerSettings settings)](#Watermarker-java.lang.String-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-) | يُهيئ نسخة جديدة من الفئة `[Watermarker](../../com.groupdocs.watermark/watermarker)` بالمسار المحدد للمستند، وخيارات التحميل، والإعدادات. |
|
|  | [Watermarker(InputStream document)](#Watermarker-java.io.InputStream-) | يُهيئ نسخة جديدة من الفئة `[Watermarker](../../com.groupdocs.watermark/watermarker)` باستخدام الدفق المحدد. |
|
|  | [Watermarker(InputStream document, LoadOptions options)](#Watermarker-java.io.InputStream-com.groupdocs.watermark.options.LoadOptions-) | يُهيئ نسخة جديدة من الفئة `[Watermarker](../../com.groupdocs.watermark/watermarker)` باستخدام الدفق المحدد وخيارات التحميل. |
|
|  | [Watermarker(InputStream document, WatermarkerSettings settings)](#Watermarker-java.io.InputStream-com.groupdocs.watermark.WatermarkerSettings-) | يُهيئ نسخة جديدة من الفئة `[Watermarker](../../com.groupdocs.watermark/watermarker)` باستخدام الدفق المحدد والإعدادات. |
|
|  | [Watermarker(InputStream document, LoadOptions options, WatermarkerSettings settings)](#Watermarker-java.io.InputStream-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-) | يُهيئ نسخة جديدة من الفئة باستخدام الدفق المحدد، وخيارات التحميل، والإعدادات. |
|
| [Watermarker(System.IO.Stream document, LoadOptions options, WatermarkerSettings settings)](#Watermarker-com.aspose.ms.System.IO.Stream-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getSearchableObjects()](#getSearchableObjects--) | يحصل على كائنات المحتوى التي يجب تضمينها في بحث العلامة المائية. |
|
|  | [setSearchableObjects(SearchableObjects value)](#setSearchableObjects-com.groupdocs.watermark.search.SearchableObjects-) | يضبط كائنات المحتوى التي يجب تضمينها في بحث العلامة المائية. |
|
| [dispose()](#dispose--) |  |
|  | [close()](#close--) | يتخلص من النسخة الحالية. |
|
|  | [getDocumentInfo()](#getDocumentInfo--) | يحصل على المعلومات حول تنسيق المستند المحمَّل. |
|
|  | [add(Watermark watermark)](#add-com.groupdocs.watermark.Watermark-) | يضيف علامة مائية إلى المستند المحمَّل. |
|
|  | [add(Watermark watermark, WatermarkOptions options)](#add-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.WatermarkOptions-) | يضيف علامة مائية إلى المستند المحمَّل باستخدام خيارات العلامة المائية. |
|
|  | [remove(PossibleWatermark possibleWatermark)](#remove-com.groupdocs.watermark.search.PossibleWatermark-) | يزيل العلامة المائية من المستند. |
|
|  | [remove(PossibleWatermarkCollection possibleWatermarks)](#remove-com.groupdocs.watermark.search.PossibleWatermarkCollection-) | يزيل جميع العلامات المائية في المجموعة من المستند. |
|
|  | [save(String filePath)](#save-java.lang.String-) | يحفظ المستند في موقع الملف المحدد. |
|
|  | [save(OutputStream document)](#save-java.io.OutputStream-) | يحفظ المستند في الدفق المحدد. |
|
|  | [save(String filePath, SaveOptions options)](#save-java.lang.String-com.groupdocs.watermark.options.SaveOptions-) | يحفظ المستند في موقع الملف المحدد باستخدام خيارات الحفظ. |
|
|  | [save(OutputStream document, SaveOptions options)](#save-java.io.OutputStream-com.groupdocs.watermark.options.SaveOptions-) | يحفظ المستند في الدفق المحدد باستخدام خيارات الحفظ. |
|
|  | [generatePreview(PreviewOptions previewOptions)](#generatePreview-com.groupdocs.watermark.options.PreviewOptions-) | ينشئ صورًا مسبقة للمعاينة للمستند. |
|
|  | [search()](#search--) | يبحث عن جميع العلامات المائية الممكنة في المستند. |
|
|  | [search(SearchCriteria searchCriteria)](#search-com.groupdocs.watermark.search.SearchCriteria-) | يبحث عن العلامات المائية الممكنة وفقًا لمعايير البحث المحددة. |
|
|  | [getImages(ImageSearchCriteria searchCriteria)](#getImages-com.groupdocs.watermark.search.ImageSearchCriteria-) | يجد الصور وفقًا لمعايير البحث المحددة. |
|
|  | [getImages()](#getImages--) | يجد جميع الصور في المستند. |
|
|  | [<T>getContent(Class<T> contentType)](#-T-getContent-java.lang.Class-T--) | يعيد كائن `[Content](../../com.groupdocs.watermark.contents/content)` للمستند المحمَّل. |
|
### Watermarker(String filePath) {#Watermarker-java.lang.String-}
```
public Watermarker(String filePath)
```


يُهيئ نسخة جديدة من الفئة `[Watermarker](../../com.groupdocs.watermark/watermarker)` بالمسار المحدد للمستند.

تعرف على المزيد حول تحميل المستندات:
[Loading documents](../https://docs.groupdocs.com/display/watermarkjava/Loading+documents).

يوضح المثال التالي كيفية تحميل وحفظ محتوى بأي تنسيق مدعوم.
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
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePath | java.lang.String | مسار الملف لتحميل المستند منه. |
|

### Watermarker(String filePath, LoadOptions options) {#Watermarker-java.lang.String-com.groupdocs.watermark.options.LoadOptions-}
```
public Watermarker(String filePath, LoadOptions options)
```


يُهيئ نسخة جديدة من الفئة `[Watermarker](../../com.groupdocs.watermark/watermarker)` بالمسار المحدد للمستند وخيارات التحميل.

تعرف على المزيد حول تحميل المستندات:
[Loading documents](../https://docs.groupdocs.com/display/watermarkjava/Loading+documents).

يوضح المثال التالي كيفية تحميل مستند PDF مشفر باستخدام كلمة مرور.
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
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePath | java.lang.String | مسار الملف لتحميل المستند منه. |
|
|  | options | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) | خيارات إضافية لاستخدامها عند تحميل مستند. |
|

### Watermarker(String filePath, WatermarkerSettings settings) {#Watermarker-java.lang.String-com.groupdocs.watermark.WatermarkerSettings-}
```
public Watermarker(String filePath, WatermarkerSettings settings)
```


يُهيئ نسخة جديدة من الفئة `[Watermarker](../../com.groupdocs.watermark/watermarker)` بالمسار المحدد للمستند والإعدادات.

تعرف على المزيد حول تحميل المستندات:
[Loading documents](../https://docs.groupdocs.com/display/watermarkjava/Loading+documents).

يوضح المثال التالي كيفية تعيين الكائنات القابلة للبحث عالميًا (لكل المستندات التي
سيتم تحميلها بعد ذلك).
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
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePath | java.lang.String | مسار الملف لتحميل المستند منه. |
|
|  | settings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) | إعدادات إضافية لاستخدامها عند العمل مع المستند المحمَّل. |
|

### Watermarker(String filePath, LoadOptions options, WatermarkerSettings settings) {#Watermarker-java.lang.String-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-}
```
public Watermarker(String filePath, LoadOptions options, WatermarkerSettings settings)
```


يُهيئ نسخة جديدة من الفئة `[Watermarker](../../com.groupdocs.watermark/watermarker)` بالمسار المحدد للمستند، وخيارات التحميل، والإعدادات.

تعرف على المزيد حول تحميل المستندات:
[Loading documents](../https://docs.groupdocs.com/display/watermarknet/Loading+documents).

يوضح المثال التالي كيفية العثور على مقاطع نصية معينة في جسم/موضوع رسالة البريد الإلكتروني.
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
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePath | java.lang.String | مسار الملف لتحميل المستند منه. |
|
|  | options | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) | خيارات إضافية لاستخدامها عند تحميل مستند. |
|
|  | settings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) | إعدادات إضافية لاستخدامها عند العمل مع المستند المحمَّل. |
|

### Watermarker(InputStream document) {#Watermarker-java.io.InputStream-}
```
public Watermarker(InputStream document)
```


يُهيئ نسخة جديدة من الفئة `[Watermarker](../../com.groupdocs.watermark/watermarker)` باستخدام الدفق المحدد.

تعرف على المزيد حول تحميل المستندات:
[Loading documents](../https://docs.groupdocs.com/display/watermarknet/Loading+documents).

يوضح المثال التالي كيفية تحميل وحفظ مستند بأي تنسيق مدعوم.
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
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | مستند | java.io.InputStream | التدفق لتحميل المستند منه. |
|

### Watermarker(InputStream document, LoadOptions options) {#Watermarker-java.io.InputStream-com.groupdocs.watermark.options.LoadOptions-}
```
public Watermarker(InputStream document, LoadOptions options)
```


يُهيئ نسخة جديدة من الفئة `[Watermarker](../../com.groupdocs.watermark/watermarker)` باستخدام الدفق المحدد وخيارات التحميل.

تعرف على المزيد حول تحميل المستندات:
[Loading documents](../https://docs.groupdocs.com/display/watermarknet/Loading+documents).

المثال التالي يوضح كيفية تحميل مستند PDF مشفر باستخدام كلمة المرور
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
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | مستند | java.io.InputStream | التدفق لتحميل المستند منه. |
|
|  | options | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) | خيارات إضافية لاستخدامها عند تحميل مستند. |
|

### Watermarker(InputStream document, WatermarkerSettings settings) {#Watermarker-java.io.InputStream-com.groupdocs.watermark.WatermarkerSettings-}
```
public Watermarker(InputStream document, WatermarkerSettings settings)
```


يُهيئ نسخة جديدة من الفئة `[Watermarker](../../com.groupdocs.watermark/watermarker)` باستخدام الدفق المحدد والإعدادات.

تعرف على المزيد حول تحميل المستندات:
[Loading documents](../https://docs.groupdocs.com/display/watermarknet/Loading+documents).

يوضح المثال التالي كيفية تعيين الكائنات القابلة للبحث عالميًا (لكل المستندات التي
سيتم تحميلها بعد ذلك).
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
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | مستند | java.io.InputStream | التدفق لتحميل المستند منه. |
|
|  | settings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) | إعدادات إضافية لاستخدامها عند العمل مع المستند المحمَّل. |
|

### Watermarker(InputStream document, LoadOptions options, WatermarkerSettings settings) {#Watermarker-java.io.InputStream-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-}
```
public Watermarker(InputStream document, LoadOptions options, WatermarkerSettings settings)
```


يُهيئ نسخة جديدة من الفئة باستخدام الدفق المحدد، وخيارات التحميل، والإعدادات.

تعرف على المزيد حول تحميل المستندات:
[Loading documents](../https://docs.groupdocs.com/display/watermarknet/Loading+documents).

يوضح المثال التالي كيفية تعيين الكائنات القابلة للبحث عالميًا (لكل المستندات التي
سيتم تحميلها بعد ذلك).
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
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | مستند | java.io.InputStream | التدفق لتحميل المستند منه. |
|
|  | options | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) | خيارات إضافية لاستخدامها عند تحميل مستند. |
|
|  | settings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) | إعدادات إضافية لاستخدامها عند العمل مع المستند المحمَّل. |
|

### Watermarker(System.IO.Stream document, LoadOptions options, WatermarkerSettings settings) {#Watermarker-com.aspose.ms.System.IO.Stream-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-}
```
public Watermarker(System.IO.Stream document, LoadOptions options, WatermarkerSettings settings)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| مستند | com.aspose.ms.System.IO.Stream |  |
| options | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) |  |
| settings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) |  |

### getSearchableObjects() {#getSearchableObjects--}
```
public final SearchableObjects getSearchableObjects()
```


يحصل على كائنات المحتوى التي يجب تضمينها في بحث العلامة المائية.

هذه الطريقة أيضًا تحدد كائنات المحتوى التي تُستخدم في البحث عن الصور.
لمزيد من المعلومات راجع `#search(SearchCriteria).search(SearchCriteria)`
وطرق `#getImages().getImages()`

تعرف على المزيد حول البحث عن العلامات المائية:
[Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks).

المثال التالي يوضح كيفية إزالة جميع XObjects وArtifacts من مستند PDF.
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


يضبط كائنات المحتوى التي يجب تضمينها في بحث العلامة المائية.

هذه الطريقة أيضًا تحدد كائنات المحتوى التي تُستخدم في البحث عن الصور.
لمزيد من المعلومات راجع `#search(SearchCriteria).search(SearchCriteria)`
وطرق `#getImages().getImages()`
تعرف على المزيد حول البحث عن العلامات المائية:
[Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks).

المثال التالي يوضح كيفية إزالة جميع XObjects وArtifacts من مستند PDF.
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
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | [SearchableObjects](../../com.groupdocs.watermark.search/searchableobjects) | الكائنات التي يجب تضمينها في بحث العلامة المائية. |
|

### dispose() {#dispose--}
```
public final void dispose()
```




### close() {#close--}
```
public final void close()
```


يتخلص من النسخة الحالية.


### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


يحصل على المعلومات حول تنسيق المستند المحمَّل.

تعرف على المزيد حول الحصول على معلومات المستند
[Get document info](../https://docs.groupdocs.com/display/watermarkjava/Get+document+info).

المثال التالي يوضح كيفية الحصول على معلومات حول مستند من أي نوع مدعوم.
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


يضيف علامة مائية إلى المستند المحمَّل.

تعرف على المزيد حول إضافة العلامات المائية:
[Adding watermarks](../https://docs.groupdocs.com/display/watermarkjava/Adding+watermarks).

المثال التالي يوضح كيفية إضافة علامة مائية صورة ونص إلى مستند من أي نوع مدعوم.
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
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | watermark | [Watermark](../../com.groupdocs.watermark/watermark) | العلامة المائية لإضافتها إلى المستند. |
|

### add(Watermark watermark, WatermarkOptions options) {#add-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.WatermarkOptions-}
```
public final void add(Watermark watermark, WatermarkOptions options)
```


يضيف علامة مائية إلى المستند المحمَّل باستخدام خيارات العلامة المائية.

تعرف على المزيد حول إضافة العلامات المائية:
[Adding watermarks](../https://docs.groupdocs.com/display/watermarkjava/Adding+watermarks).

المثال التالي يوضح كيفية إضافة علامة مائية صورة إلى صفحة معينة من مستند PDF.
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
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | watermark | [Watermark](../../com.groupdocs.watermark/watermark) | العلامة المائية لإضافتها إلى المستند. |
|
|  | options | [WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions) | خيارات إضافية للاستخدام عند إضافة العلامة المائية. |
|

### remove(PossibleWatermark possibleWatermark) {#remove-com.groupdocs.watermark.search.PossibleWatermark-}
```
public final void remove(PossibleWatermark possibleWatermark)
```


يزيل العلامة المائية من المستند.

تعرف على المزيد حول إزالة العلامات المائية:
[Removing found watermarks](../https://docs.groupdocs.com/display/watermarkjava/Removing+found+watermarks).

المثال التالي يوضح كيفية العثور على وإزالة أول علامة مائية محتملة تحتوي على معينة
نص أو صورة من مستند من أي نوع مدعوم.
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
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | possibleWatermark | [PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark) | العلامة المائية لإزالتها. |
|

### remove(PossibleWatermarkCollection possibleWatermarks) {#remove-com.groupdocs.watermark.search.PossibleWatermarkCollection-}
```
public final void remove(PossibleWatermarkCollection possibleWatermarks)
```


يزيل جميع العلامات المائية في المجموعة من المستند.

تعرف على المزيد حول إزالة العلامات المائية:
[Removing found watermarks](../https://docs.groupdocs.com/display/watermarkjava/Removing+found+watermarks).

المثال التالي يوضح كيفية العثور على وإزالة جميع العلامات المائية المحتملة التي تحتوي على معينة
نص أو صورة من مستند من أي نوع مدعوم.
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
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | possibleWatermarks | [PossibleWatermarkCollection](../../com.groupdocs.watermark.search/possiblewatermarkcollection) | مجموعة العلامات المائية لإزالتها. |
|

### save(String filePath) {#save-java.lang.String-}
```
public final void save(String filePath)
```


يحفظ المستند في موقع الملف المحدد.

تعرف على المزيد حول حفظ المستندات
[Saving documents](../https://docs.groupdocs.com/display/watermarkjava/Saving+documents).

المثال التالي يوضح كيفية إضافة العلامة المائية وحفظ المستند في ملف آخر.
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
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePath | java.lang.String | مسار الملف لحفظ بيانات المستند فيه. |
|

### save(OutputStream document) {#save-java.io.OutputStream-}
```
public final void save(OutputStream document)
```


يحفظ المستند في الدفق المحدد.

تعرف على المزيد حول حفظ المستندات
[Saving documents](../https://docs.groupdocs.com/display/watermarkjava/Saving+documents).

المثال التالي يوضح كيفية إضافة العلامة المائية وحفظ المستند إلى تدفق الذاكرة.
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
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | مستند | java.io.OutputStream | التدفق لحفظ بيانات المستند فيه. |
|

### save(String filePath, SaveOptions options) {#save-java.lang.String-com.groupdocs.watermark.options.SaveOptions-}
```
public final void save(String filePath, SaveOptions options)
```


يحفظ المستند في موقع الملف المحدد باستخدام خيارات الحفظ.

تعرف على المزيد حول حفظ المستندات
[Saving documents](../https://docs.groupdocs.com/display/watermarkjava/Saving+documents).

المثال التالي يوضح كيفية إضافة العلامة المائية وحفظ المستند في ملف آخر
بالإعدادات الافتراضية `[SaveOptions](../../com.groupdocs.watermark.options/saveoptions)`.
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
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePath | java.lang.String | مسار الملف لحفظ بيانات المستند فيه. |
|
|  | options | [SaveOptions](../../com.groupdocs.watermark.options/saveoptions) | خيارات إضافية للاستخدام عند حفظ المستند. |
|

### save(OutputStream document, SaveOptions options) {#save-java.io.OutputStream-com.groupdocs.watermark.options.SaveOptions-}
```
public final void save(OutputStream document, SaveOptions options)
```


يحفظ المستند في الدفق المحدد باستخدام خيارات الحفظ.

تعرف على المزيد حول حفظ المستندات
[Saving documents](../https://docs.groupdocs.com/display/watermarkjava/Saving+documents).

المثال التالي يوضح كيفية إضافة العلامة المائية وحفظ المستند إلى تدفق الذاكرة
بالإعدادات الافتراضية `[SaveOptions](../../com.groupdocs.watermark.options/saveoptions)`.
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
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | مستند | java.io.OutputStream | التدفق لحفظ بيانات المستند فيه. |
|
|  | options | [SaveOptions](../../com.groupdocs.watermark.options/saveoptions) | خيارات إضافية للاستخدام عند حفظ المستند. |
|

### generatePreview(PreviewOptions previewOptions) {#generatePreview-com.groupdocs.watermark.options.PreviewOptions-}
```
public final void generatePreview(PreviewOptions previewOptions)
```


ينشئ صورًا مسبقة للمعاينة للمستند.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | previewOptions | [PreviewOptions](../../com.groupdocs.watermark.options/previewoptions) | خيارات إضافية للاستخدام عند إنشاء صور المعاينة. |
|

### search() {#search--}
```
public final PossibleWatermarkCollection search()
```


يبحث عن جميع العلامات المائية الممكنة في المستند.

يتم إجراء البحث في الكائنات المحددة باستخدام `#setSearchableObjects(SearchableObjects).setSearchableObjects(SearchableObjects)`.

تعرف على المزيد حول البحث عن العلامات المائية
[Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks).

المثال التالي يوضح كيفية عد العلامات المائية الممكنة في مستند من أي نوع مدعوم.
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


يبحث عن العلامات المائية الممكنة وفقًا لمعايير البحث المحددة.

يتم إجراء البحث في الكائنات المحددة باستخدام `#setSearchableObjects(SearchableObjects).setSearchableObjects(SearchableObjects)`.

تعرف على المزيد حول البحث عن العلامات المائية
[Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks).

المثال التالي يوضح كيفية العثور على جميع العلامات المائية الممكنة وإزالتها التي تحتوي على نص معين
أو صورة من مستند من أي نوع مدعوم.
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
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | searchCriteria | [SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) | معايير البحث للاستخدام. |
|

**Returns:**
[PossibleWatermarkCollection](../../com.groupdocs.watermark.search/possiblewatermarkcollection)
### getImages(ImageSearchCriteria searchCriteria) {#getImages-com.groupdocs.watermark.search.ImageSearchCriteria-}
```
public final WatermarkableImageCollection getImages(ImageSearchCriteria searchCriteria)
```


يجد الصور وفقًا لمعايير البحث المحددة.

يتم إجراء البحث في الكائنات المحددة باستخدام `#setSearchableObjects(SearchableObjects).setSearchableObjects(SearchableObjects)`.

تعرف على المزيد حول البحث عن العلامات المائية
[Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks).

المثال التالي يوضح كيفية إزالة جميع الصور المشابهة للمرجع
من مستند من أي نوع مدعوم.
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
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | searchCriteria | [ImageSearchCriteria](../../com.groupdocs.watermark.search/imagesearchcriteria) | معايير البحث للاستخدام. |
|

**Returns:**
[WatermarkableImageCollection](../../com.groupdocs.watermark.contents/watermarkableimagecollection)
### getImages() {#getImages--}
```
public final WatermarkableImageCollection getImages()
```


يجد جميع الصور في المستند.

يتم إجراء البحث في الكائنات المحددة باستخدام `#setSearchableObjects(SearchableObjects).setSearchableObjects(SearchableObjects)`.

تعرف على المزيد حول البحث عن العلامات المائية
[Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks).

المثال التالي يوضح كيفية إضافة العلامة المائية إلى جميع الصور في مستند من أي نوع مدعوم.
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


يعيد كائن `[Content](../../com.groupdocs.watermark.contents/content)` للمستند المحمَّل.

المثال التالي يوضح كيفية تحويل صفحة مستند PDF إلى نقطية مع إضافة العلامة المائية.
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
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | contentType | java.lang.Class<T> | النوع المطلوب لكائن `[Content](../../com.groupdocs.watermark.contents/content)`. |
|

**Returns:**
T - كائن `[Content](../../com.groupdocs.watermark.contents/content)` للمستند المحمَّل.

