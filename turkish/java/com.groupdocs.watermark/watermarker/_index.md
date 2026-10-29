---
title: "Watermarker"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "Bir belgede filigran yönetimi için sınıfı temsil eder."
type: docs
weight: 14
url: /tr/java/com.groupdocs.watermark/watermarker/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class Watermarker implements Closeable
```

Bir belgede filigran yönetimi için sınıfı temsil eder.

Aşağıdaki örnek, herhangi bir desteklenen formatın içeriğini nasıl yükleyip kaydedeceğinizi gösterir.
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


## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [Watermarker(String filePath)](#Watermarker-java.lang.String-) | Belirtilen belge yolu ile `[Watermarker](../../com.groupdocs.watermark/watermarker)` sınıfının yeni bir örneğini başlatır. |
|
|  | [Watermarker(String filePath, LoadOptions options)](#Watermarker-java.lang.String-com.groupdocs.watermark.options.LoadOptions-) | Belirtilen belge yolu ve yükleme seçenekleri ile `[Watermarker](../../com.groupdocs.watermark/watermarker)` sınıfının yeni bir örneğini başlatır. |
|
|  | [Watermarker(String filePath, WatermarkerSettings settings)](#Watermarker-java.lang.String-com.groupdocs.watermark.WatermarkerSettings-) | Belirtilen belge yolu ve ayarlarla `[Watermarker](../../com.groupdocs.watermark/watermarker)` sınıfının yeni bir örneğini başlatır. |
|
|  | [Watermarker(String filePath, LoadOptions options, WatermarkerSettings settings)](#Watermarker-java.lang.String-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-) | Belirtilen belge yolu, yükleme seçenekleri ve ayarlarla `[Watermarker](../../com.groupdocs.watermark/watermarker)` sınıfının yeni bir örneğini başlatır. |
|
|  | [Watermarker(InputStream document)](#Watermarker-java.io.InputStream-) | Belirtilen akış ile `[Watermarker](../../com.groupdocs.watermark/watermarker)` sınıfının yeni bir örneğini başlatır. |
|
|  | [Watermarker(InputStream document, LoadOptions options)](#Watermarker-java.io.InputStream-com.groupdocs.watermark.options.LoadOptions-) | Belirtilen akış ve yükleme seçenekleri ile `[Watermarker](../../com.groupdocs.watermark/watermarker)` sınıfının yeni bir örneğini başlatır. |
|
|  | [Watermarker(InputStream document, WatermarkerSettings settings)](#Watermarker-java.io.InputStream-com.groupdocs.watermark.WatermarkerSettings-) | Belirtilen akış ve ayarlarla `[Watermarker](../../com.groupdocs.watermark/watermarker)` sınıfının yeni bir örneğini başlatır. |
|
|  | [Watermarker(InputStream document, LoadOptions options, WatermarkerSettings settings)](#Watermarker-java.io.InputStream-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-) | Belirtilen akış, yükleme seçenekleri ve ayarlarla sınıfın yeni bir örneğini başlatır. |
|
| [Watermarker(System.IO.Stream document, LoadOptions options, WatermarkerSettings settings)](#Watermarker-com.aspose.ms.System.IO.Stream-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getSearchableObjects()](#getSearchableObjects--) | Bir watermark aramasına dahil edilecek içerik nesnelerini alır. |
|
|  | [setSearchableObjects(SearchableObjects value)](#setSearchableObjects-com.groupdocs.watermark.search.SearchableObjects-) | Bir watermark aramasına dahil edilecek içerik nesnelerini ayarlar. |
|
| [dispose()](#dispose--) |  |
|  | [close()](#close--) | Mevcut örneği serbest bırakır. |
|
|  | [getDocumentInfo()](#getDocumentInfo--) | Yüklenen belgenin formatı hakkında bilgileri alır. |
|
|  | [add(Watermark watermark)](#add-com.groupdocs.watermark.Watermark-) | Yüklenen belgeye bir watermark ekler. |
|
|  | [add(Watermark watermark, WatermarkOptions options)](#add-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.WatermarkOptions-) | Yüklenen belgeye watermark seçeneklerini kullanarak bir watermark ekler. |
|
|  | [remove(PossibleWatermark possibleWatermark)](#remove-com.groupdocs.watermark.search.PossibleWatermark-) | Belgeden watermark'ı kaldırır. |
|
|  | [remove(PossibleWatermarkCollection possibleWatermarks)](#remove-com.groupdocs.watermark.search.PossibleWatermarkCollection-) | Belgeden koleksiyondaki tüm filigranları kaldırır. |
|
|  | [save(String filePath)](#save-java.lang.String-) | Belgeyi belirtilen dosya konumuna kaydeder. |
|
|  | [save(OutputStream document)](#save-java.io.OutputStream-) | Belgeyi belirtilen akışa kaydeder. |
|
|  | [save(String filePath, SaveOptions options)](#save-java.lang.String-com.groupdocs.watermark.options.SaveOptions-) | Belgeyi kaydetme seçeneklerini kullanarak belirtilen dosya konumuna kaydeder. |
|
|  | [save(OutputStream document, SaveOptions options)](#save-java.io.OutputStream-com.groupdocs.watermark.options.SaveOptions-) | Belgeyi kaydetme seçeneklerini kullanarak belirtilen akışa kaydeder. |
|
|  | [generatePreview(PreviewOptions previewOptions)](#generatePreview-com.groupdocs.watermark.options.PreviewOptions-) | Belge için önizleme görüntüleri oluşturur. |
|
|  | [search()](#search--) | Belgedeki olası tüm filigranları arar. |
|
|  | [search(SearchCriteria searchCriteria)](#search-com.groupdocs.watermark.search.SearchCriteria-) | Belirtilen arama kriterlerine göre olası filigranları arar. |
|
|  | [getImages(ImageSearchCriteria searchCriteria)](#getImages-com.groupdocs.watermark.search.ImageSearchCriteria-) | Belirtilen arama kriterlerine göre görüntüleri bulur. |
|
|  | [getImages()](#getImages--) | Belgedeki tüm görüntüleri bulur. |
|
|  | [<T>getContent(Class<T> contentType)](#-T-getContent-java.lang.Class-T--) | Yüklenen belge için `[Content](../../com.groupdocs.watermark.contents/content)` nesnesini döndürür. |
|
### Watermarker(String filePath) {#Watermarker-java.lang.String-}
```
public Watermarker(String filePath)
```


Belirtilen belge yolu ile `[Watermarker](../../com.groupdocs.watermark/watermarker)` sınıfının yeni bir örneğini başlatır.

Belgeleri yükleme hakkında daha fazla bilgi edinin:
[Loading documents](../https://docs.groupdocs.com/display/watermarkjava/Loading+documents).

Aşağıdaki örnek, herhangi bir desteklenen formatın içeriğini nasıl yükleyip kaydedeceğinizi gösterir.
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePath | java.lang.String | Belgeyi yüklemek için dosya yolu. |
|

### Watermarker(String filePath, LoadOptions options) {#Watermarker-java.lang.String-com.groupdocs.watermark.options.LoadOptions-}
```
public Watermarker(String filePath, LoadOptions options)
```


Belirtilen belge yolu ve yükleme seçenekleri ile `[Watermarker](../../com.groupdocs.watermark/watermarker)` sınıfının yeni bir örneğini başlatır.

Belgeleri yükleme hakkında daha fazla bilgi edinin:
[Loading documents](../https://docs.groupdocs.com/display/watermarkjava/Loading+documents).

Aşağıdaki örnek, şifreli PDF belgesini parola kullanarak nasıl yükleyeceğinizi gösterir.
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePath | java.lang.String | Belgeyi yüklemek için dosya yolu. |
|
|  | options | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) | Bir belge yüklerken kullanılacak ek seçenekler. |
|

### Watermarker(String filePath, WatermarkerSettings settings) {#Watermarker-java.lang.String-com.groupdocs.watermark.WatermarkerSettings-}
```
public Watermarker(String filePath, WatermarkerSettings settings)
```


Belirtilen belge yolu ve ayarlarla `[Watermarker](../../com.groupdocs.watermark/watermarker)` sınıfının yeni bir örneğini başlatır.

Belgeleri yükleme hakkında daha fazla bilgi edinin:
[Loading documents](../https://docs.groupdocs.com/display/watermarkjava/Loading+documents).

Aşağıdaki örnek, aranabilir nesneleri global olarak (tüm belgeler için) nasıl ayarlayacağını gösterir (
bu işlemden sonra yüklenecek).
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePath | java.lang.String | Belgeyi yüklemek için dosya yolu. |
|
|  | settings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) | Yüklenen belgeyle çalışırken kullanılacak ek ayarlar. |
|

### Watermarker(String filePath, LoadOptions options, WatermarkerSettings settings) {#Watermarker-java.lang.String-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-}
```
public Watermarker(String filePath, LoadOptions options, WatermarkerSettings settings)
```


Belirtilen belge yolu, yükleme seçenekleri ve ayarlarla `[Watermarker](../../com.groupdocs.watermark/watermarker)` sınıfının yeni bir örneğini başlatır.

Belgeleri yükleme hakkında daha fazla bilgi edinin:
[Loading documents](../https://docs.groupdocs.com/display/watermarknet/Loading+documents).

Aşağıdaki örnek, e-posta mesajı gövdesinde/konusunda belirli metin parçacıklarını nasıl bulacağınızı gösterir.
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePath | java.lang.String | Belgeyi yüklemek için dosya yolu. |
|
|  | options | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) | Bir belge yüklerken kullanılacak ek seçenekler. |
|
|  | settings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) | Yüklenen belgeyle çalışırken kullanılacak ek ayarlar. |
|

### Watermarker(InputStream document) {#Watermarker-java.io.InputStream-}
```
public Watermarker(InputStream document)
```


Belirtilen akış ile `[Watermarker](../../com.groupdocs.watermark/watermarker)` sınıfının yeni bir örneğini başlatır.

Belgeleri yükleme hakkında daha fazla bilgi edinin:
[Loading documents](../https://docs.groupdocs.com/display/watermarknet/Loading+documents).

Aşağıdaki örnek, desteklenen herhangi bir formatta belgeyi nasıl yükleyip kaydedeceğinizi gösterir.
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | belge | java.io.InputStream | Belgeyi yüklemek için akış. |
|

### Watermarker(InputStream document, LoadOptions options) {#Watermarker-java.io.InputStream-com.groupdocs.watermark.options.LoadOptions-}
```
public Watermarker(InputStream document, LoadOptions options)
```


Belirtilen akış ve yükleme seçenekleri ile `[Watermarker](../../com.groupdocs.watermark/watermarker)` sınıfının yeni bir örneğini başlatır.

Belgeleri yükleme hakkında daha fazla bilgi edinin:
[Loading documents](../https://docs.groupdocs.com/display/watermarknet/Loading+documents).

Aşağıdaki örnek, şifreli PDF belgesini parola kullanarak nasıl yükleyeceğinizi gösterir.
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | belge | java.io.InputStream | Belgeyi yüklemek için akış. |
|
|  | options | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) | Bir belge yüklerken kullanılacak ek seçenekler. |
|

### Watermarker(InputStream document, WatermarkerSettings settings) {#Watermarker-java.io.InputStream-com.groupdocs.watermark.WatermarkerSettings-}
```
public Watermarker(InputStream document, WatermarkerSettings settings)
```


Belirtilen akış ve ayarlarla `[Watermarker](../../com.groupdocs.watermark/watermarker)` sınıfının yeni bir örneğini başlatır.

Belgeleri yükleme hakkında daha fazla bilgi edinin:
[Loading documents](../https://docs.groupdocs.com/display/watermarknet/Loading+documents).

Aşağıdaki örnek, aranabilir nesneleri global olarak (tüm belgeler için) nasıl ayarlayacağını gösterir (
bu işlemden sonra yüklenecek).
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | belge | java.io.InputStream | Belgeyi yüklemek için akış. |
|
|  | settings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) | Yüklenen belgeyle çalışırken kullanılacak ek ayarlar. |
|

### Watermarker(InputStream document, LoadOptions options, WatermarkerSettings settings) {#Watermarker-java.io.InputStream-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-}
```
public Watermarker(InputStream document, LoadOptions options, WatermarkerSettings settings)
```


Belirtilen akış, yükleme seçenekleri ve ayarlarla sınıfın yeni bir örneğini başlatır.

Belgeleri yükleme hakkında daha fazla bilgi edinin:
[Loading documents](../https://docs.groupdocs.com/display/watermarknet/Loading+documents).

Aşağıdaki örnek, aranabilir nesneleri global olarak (tüm belgeler için) nasıl ayarlayacağını gösterir (
bu işlemden sonra yüklenecek).
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | belge | java.io.InputStream | Belgeyi yüklemek için akış. |
|
|  | options | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) | Bir belge yüklerken kullanılacak ek seçenekler. |
|
|  | settings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) | Yüklenen belgeyle çalışırken kullanılacak ek ayarlar. |
|

### Watermarker(System.IO.Stream document, LoadOptions options, WatermarkerSettings settings) {#Watermarker-com.aspose.ms.System.IO.Stream-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-}
```
public Watermarker(System.IO.Stream document, LoadOptions options, WatermarkerSettings settings)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| belge | com.aspose.ms.System.IO.Stream |  |
| options | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) |  |
| settings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) |  |

### getSearchableObjects() {#getSearchableObjects--}
```
public final SearchableObjects getSearchableObjects()
```


Bir watermark aramasına dahil edilecek içerik nesnelerini alır.

Bu yöntem, görüntü aramasında kullanılan içerik nesnelerini de belirtir.
Daha fazla bilgi için `#search(SearchCriteria).search(SearchCriteria)` koduna bakın.
ve `#getImages().getImages()` yöntemlerine.

Filigran arama hakkında daha fazla bilgi edinin:
[Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks).

Aşağıdaki örnek, bir PDF belgesinden tüm XObjects ve Artifacts öğelerini nasıl kaldıracağınızı gösterir.
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


Bir watermark aramasına dahil edilecek içerik nesnelerini ayarlar.

Bu yöntem, görüntü aramasında kullanılan içerik nesnelerini de belirtir.
Daha fazla bilgi için `#search(SearchCriteria).search(SearchCriteria)` koduna bakın.
ve `#getImages().getImages()` yöntemlerine.
Filigran arama hakkında daha fazla bilgi edinin:
[Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks).

Aşağıdaki örnek, bir PDF belgesinden tüm XObjects ve Artifacts öğelerini nasıl kaldıracağınızı gösterir.
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | [SearchableObjects](../../com.groupdocs.watermark.search/searchableobjects) | Filigran aramasına dahil edilecek nesneler. |
|

### dispose() {#dispose--}
```
public final void dispose()
```




### close() {#close--}
```
public final void close()
```


Mevcut örneği serbest bırakır.


### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


Yüklenen belgenin formatı hakkında bilgileri alır.

Belge bilgilerini almayı öğrenin
[Get document info](../https://docs.groupdocs.com/display/watermarkjava/Get+document+info).

Aşağıdaki örnek, desteklenen herhangi bir türdeki belgenin bilgilerini nasıl alacağınızı gösterir.
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


Yüklenen belgeye bir watermark ekler.

Filigran ekleme hakkında daha fazla bilgi edinin:
[Adding watermarks](../https://docs.groupdocs.com/display/watermarkjava/Adding+watermarks).

Aşağıdaki örnek, desteklenen herhangi bir türdeki belgeye görüntü ve metin filigranı eklemeyi gösterir.
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | watermark | [Watermark](../../com.groupdocs.watermark/watermark) | Belgeye eklenecek filigran. |
|

### add(Watermark watermark, WatermarkOptions options) {#add-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.WatermarkOptions-}
```
public final void add(Watermark watermark, WatermarkOptions options)
```


Yüklenen belgeye watermark seçeneklerini kullanarak bir watermark ekler.

Filigran ekleme hakkında daha fazla bilgi edinin:
[Adding watermarks](../https://docs.groupdocs.com/display/watermarkjava/Adding+watermarks).

Aşağıdaki örnek, bir PDF belgesinin belirli bir sayfasına görüntü filigranı eklemeyi gösterir.
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | watermark | [Watermark](../../com.groupdocs.watermark/watermark) | Belgeye eklenecek filigran. |
|
|  | options | [WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions) | Filigran eklerken kullanılacak ek seçenekler. |
|

### remove(PossibleWatermark possibleWatermark) {#remove-com.groupdocs.watermark.search.PossibleWatermark-}
```
public final void remove(PossibleWatermark possibleWatermark)
```


Belgeden watermark'ı kaldırır.

Filigran kaldırma hakkında daha fazla bilgi edinin:
[Removing found watermarks](../https://docs.groupdocs.com/display/watermarkjava/Removing+found+watermarks).

Aşağıdaki örnek, belirli bir ... içeren ilk olası filigranı bulup kaldırmayı gösterir.
metin veya görüntüyü, desteklenen herhangi bir türdeki bir belgeden.
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | possibleWatermark | [PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark) | Kaldırılacak filigran. |
|

### remove(PossibleWatermarkCollection possibleWatermarks) {#remove-com.groupdocs.watermark.search.PossibleWatermarkCollection-}
```
public final void remove(PossibleWatermarkCollection possibleWatermarks)
```


Belgeden koleksiyondaki tüm filigranları kaldırır.

Filigran kaldırma hakkında daha fazla bilgi edinin:
[Removing found watermarks](../https://docs.groupdocs.com/display/watermarkjava/Removing+found+watermarks).

Aşağıdaki örnek, belirli bir ... içeren tüm olası filigranları bulup kaldırmayı gösterir.
metin veya görüntüyü, desteklenen herhangi bir türdeki bir belgeden.
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | possibleWatermarks | [PossibleWatermarkCollection](../../com.groupdocs.watermark.search/possiblewatermarkcollection) | Kaldırılacak filigranların koleksiyonu. |
|

### save(String filePath) {#save-java.lang.String-}
```
public final void save(String filePath)
```


Belgeyi belirtilen dosya konumuna kaydeder.

Belgeleri kaydetme hakkında daha fazla bilgi edinin
[Saving documents](../https://docs.groupdocs.com/display/watermarkjava/Saving+documents).

Aşağıdaki örnek, filigranı eklemeyi ve belgeyi başka bir dosyaya kaydetmeyi gösterir.
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePath | java.lang.String | Belge verilerinin kaydedileceği dosya yolu. |
|

### save(OutputStream document) {#save-java.io.OutputStream-}
```
public final void save(OutputStream document)
```


Belgeyi belirtilen akışa kaydeder.

Belgeleri kaydetme hakkında daha fazla bilgi edinin
[Saving documents](../https://docs.groupdocs.com/display/watermarkjava/Saving+documents).

Aşağıdaki örnek, filigranı eklemeyi ve belgeyi bellek akışına kaydetmeyi gösterir.
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | belge | java.io.OutputStream | Belge verilerinin kaydedileceği akış. |
|

### save(String filePath, SaveOptions options) {#save-java.lang.String-com.groupdocs.watermark.options.SaveOptions-}
```
public final void save(String filePath, SaveOptions options)
```


Belgeyi kaydetme seçeneklerini kullanarak belirtilen dosya konumuna kaydeder.

Belgeleri kaydetme hakkında daha fazla bilgi edinin
[Saving documents](../https://docs.groupdocs.com/display/watermarkjava/Saving+documents).

Aşağıdaki örnek, filigranı eklemeyi ve belgeyi başka bir dosyaya kaydetmeyi gösterir
varsayılan `[SaveOptions](../../com.groupdocs.watermark.options/saveoptions)` ile.
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePath | java.lang.String | Belge verilerinin kaydedileceği dosya yolu. |
|
|  | options | [SaveOptions](../../com.groupdocs.watermark.options/saveoptions) | Bir belge kaydederken kullanılacak ek seçenekler. |
|

### save(OutputStream document, SaveOptions options) {#save-java.io.OutputStream-com.groupdocs.watermark.options.SaveOptions-}
```
public final void save(OutputStream document, SaveOptions options)
```


Belgeyi kaydetme seçeneklerini kullanarak belirtilen akışa kaydeder.

Belgeleri kaydetme hakkında daha fazla bilgi edinin
[Saving documents](../https://docs.groupdocs.com/display/watermarkjava/Saving+documents).

Aşağıdaki örnek, filigranı eklemeyi ve belgeyi bellek akışına kaydetmeyi gösterir
varsayılan `[SaveOptions](../../com.groupdocs.watermark.options/saveoptions)` ile.
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | belge | java.io.OutputStream | Belge verilerinin kaydedileceği akış. |
|
|  | options | [SaveOptions](../../com.groupdocs.watermark.options/saveoptions) | Bir belge kaydederken kullanılacak ek seçenekler. |
|

### generatePreview(PreviewOptions previewOptions) {#generatePreview-com.groupdocs.watermark.options.PreviewOptions-}
```
public final void generatePreview(PreviewOptions previewOptions)
```


Belge için önizleme görüntüleri oluşturur.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | previewOptions | [PreviewOptions](../../com.groupdocs.watermark.options/previewoptions) | Ön izleme görüntüleri oluştururken kullanılacak ek seçenekler. |
|

### search() {#search--}
```
public final PossibleWatermarkCollection search()
```


Belgedeki olası tüm filigranları arar.

Arama, `#setSearchableObjects(SearchableObjects).setSearchableObjects(SearchableObjects)` ile belirtilen nesnelerde gerçekleştirilir.

Filigran arama hakkında daha fazla bilgi edinin
[Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks).

Aşağıdaki örnek, desteklenen herhangi bir türdeki belgede olası filigranların sayılmasını gösterir.
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


Belirtilen arama kriterlerine göre olası filigranları arar.

Arama, `#setSearchableObjects(SearchableObjects).setSearchableObjects(SearchableObjects)` ile belirtilen nesnelerde gerçekleştirilir.

Filigran arama hakkında daha fazla bilgi edinin
[Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks).

Aşağıdaki örnek, belirli metni içeren tüm olası filigranları bulup kaldırmayı gösterir
veya desteklenen herhangi bir türdeki bir belgeden görüntü.
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | searchCriteria | [SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) | Kullanılacak arama kriterleri. |
|

**Returns:**
[PossibleWatermarkCollection](../../com.groupdocs.watermark.search/possiblewatermarkcollection)
### getImages(ImageSearchCriteria searchCriteria) {#getImages-com.groupdocs.watermark.search.ImageSearchCriteria-}
```
public final WatermarkableImageCollection getImages(ImageSearchCriteria searchCriteria)
```


Belirtilen arama kriterlerine göre görüntüleri bulur.

Arama, `#setSearchableObjects(SearchableObjects).setSearchableObjects(SearchableObjects)` ile belirtilen nesnelerde gerçekleştirilir.

Filigran arama hakkında daha fazla bilgi edinin
[Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks).

Aşağıdaki örnek, referansa benzer tüm görüntüleri kaldırmayı gösterir
desteklenen herhangi bir türdeki bir belgeden.
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | searchCriteria | [ImageSearchCriteria](../../com.groupdocs.watermark.search/imagesearchcriteria) | Kullanılacak arama kriterleri. |
|

**Returns:**
[WatermarkableImageCollection](../../com.groupdocs.watermark.contents/watermarkableimagecollection)
### getImages() {#getImages--}
```
public final WatermarkableImageCollection getImages()
```


Belgedeki tüm görüntüleri bulur.

Arama, `#setSearchableObjects(SearchableObjects).setSearchableObjects(SearchableObjects)` ile belirtilen nesnelerde gerçekleştirilir.

Filigran arama hakkında daha fazla bilgi edinin
[Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks).

Aşağıdaki örnek, desteklenen herhangi bir türdeki bir belgede tüm görüntülere filigran eklemeyi gösterir.
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


Yüklenen belge için `[Content](../../com.groupdocs.watermark.contents/content)` nesnesini döndürür.

Aşağıdaki örnek, eklenmiş filigranla PDF belge sayfasını rasterleştirmeyi gösterir.
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | contentType | java.lang.Class<T> | `[Content](../../com.groupdocs.watermark.contents/content)` nesnesinin istenen türü. |
|

**Returns:**
T - Yüklenen belge için `[Content](../../com.groupdocs.watermark.contents/content)` nesnesi.

