---
title: Watermarker
second_title: GroupDocs.Watermark for Java API Reference
description: Represents a class for watermark management in a document.
type: docs
weight: 12
url: /java/com.groupdocs.watermark/watermarker/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class Watermarker implements Closeable
```

Represents a class for watermark management in a document.

The following example demonstrates how to load and save a content of any supported format.

> ```
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
> ```
## Constructors

| Constructor | Description |
| --- | --- |
| [Watermarker(String filePath)](#Watermarker-java.lang.String-) | Initializes a new instance of the `[Watermarker](../../com.groupdocs.watermark/watermarker)` class with the specified document path. |
| [Watermarker(String filePath, LoadOptions options)](#Watermarker-java.lang.String-com.groupdocs.watermark.options.LoadOptions-) | Initializes a new instance of the `[Watermarker](../../com.groupdocs.watermark/watermarker)` class with the specified document path and load options. |
| [Watermarker(String filePath, WatermarkerSettings settings)](#Watermarker-java.lang.String-com.groupdocs.watermark.WatermarkerSettings-) | Initializes a new instance of the `[Watermarker](../../com.groupdocs.watermark/watermarker)` class with the specified document path and settings. |
| [Watermarker(String filePath, LoadOptions options, WatermarkerSettings settings)](#Watermarker-java.lang.String-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-) | Initializes a new instance of the `[Watermarker](../../com.groupdocs.watermark/watermarker)` class with the specified document path, load options and settings. |
| [Watermarker(InputStream document)](#Watermarker-java.io.InputStream-) | Initializes a new instance of the `[Watermarker](../../com.groupdocs.watermark/watermarker)` class with the specified stream. |
| [Watermarker(InputStream document, LoadOptions options)](#Watermarker-java.io.InputStream-com.groupdocs.watermark.options.LoadOptions-) | Initializes a new instance of the `[Watermarker](../../com.groupdocs.watermark/watermarker)` class with the specified stream and load options. |
| [Watermarker(InputStream document, WatermarkerSettings settings)](#Watermarker-java.io.InputStream-com.groupdocs.watermark.WatermarkerSettings-) | Initializes a new instance of the `[Watermarker](../../com.groupdocs.watermark/watermarker)` class with the specified stream and settings. |
| [Watermarker(InputStream document, LoadOptions options, WatermarkerSettings settings)](#Watermarker-java.io.InputStream-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-) | Initializes a new instance of the  class with the specified stream, load options and settings. |
| [Watermarker(System.IO.Stream document, LoadOptions options, WatermarkerSettings settings)](#Watermarker-com.aspose.ms.System.IO.Stream-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-) |  |
## Methods

| Method | Description |
| --- | --- |
| [getSearchableObjects()](#getSearchableObjects--) | Gets the content objects that are to be included in a watermark search. |
| [setSearchableObjects(SearchableObjects value)](#setSearchableObjects-com.groupdocs.watermark.search.SearchableObjects-) | Sets the content objects that are to be included in a watermark search. |
| [dispose()](#dispose--) |  |
| [close()](#close--) | Disposes the current instance. |
| [getDocumentInfo()](#getDocumentInfo--) | Gets the information about the format of the loaded document. |
| [add(Watermark watermark)](#add-com.groupdocs.watermark.Watermark-) | Adds a watermark to the loaded document. |
| [add(Watermark watermark, WatermarkOptions options)](#add-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.WatermarkOptions-) | Adds a watermark to the loaded document using watermark options. |
| [remove(PossibleWatermark possibleWatermark)](#remove-com.groupdocs.watermark.search.PossibleWatermark-) | Removes watermark from the document. |
| [remove(PossibleWatermarkCollection possibleWatermarks)](#remove-com.groupdocs.watermark.search.PossibleWatermarkCollection-) | Removes all watermarks in the collection from the document. |
| [save(String filePath)](#save-java.lang.String-) | Saves the document to the specified file location. |
| [save(OutputStream document)](#save-java.io.OutputStream-) | Saves the document to the specified stream. |
| [save(String filePath, SaveOptions options)](#save-java.lang.String-com.groupdocs.watermark.options.SaveOptions-) | Saves the document to the specified file location using save options. |
| [save(OutputStream document, SaveOptions options)](#save-java.io.OutputStream-com.groupdocs.watermark.options.SaveOptions-) | Saves the document to the specified stream using save options. |
| [generatePreview(PreviewOptions previewOptions)](#generatePreview-com.groupdocs.watermark.options.PreviewOptions-) | Generates preview images for the document. |
| [search()](#search--) | Searches all possible watermarks in the document. |
| [search(SearchCriteria searchCriteria)](#search-com.groupdocs.watermark.search.SearchCriteria-) | Searches possible watermarks according to specified search criteria. |
| [getImages(ImageSearchCriteria searchCriteria)](#getImages-com.groupdocs.watermark.search.ImageSearchCriteria-) | Finds images according to specified search criteria. |
| [getImages()](#getImages--) | Finds all images in the document. |
| [<T>getContent(Class<T> contentType)](#-T-getContent-java.lang.Class-T--) | Returns the `[Content](../../com.groupdocs.watermark.contents/content)` object for the loaded document. |
### Watermarker(String filePath) {#Watermarker-java.lang.String-}
```
public Watermarker(String filePath)
```


Initializes a new instance of the `[Watermarker](../../com.groupdocs.watermark/watermarker)` class with the specified document path.

Learn more about loading documents: [Loading documents][].

The following example demonstrates how to load and save a content of any supported format.

> ```
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
> ```


[Loading documents]: https://docs.groupdocs.com/display/watermarkjava/Loading+documents

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The file path to load the document from. |

### Watermarker(String filePath, LoadOptions options) {#Watermarker-java.lang.String-com.groupdocs.watermark.options.LoadOptions-}
```
public Watermarker(String filePath, LoadOptions options)
```


Initializes a new instance of the `[Watermarker](../../com.groupdocs.watermark/watermarker)` class with the specified document path and load options.

Learn more about loading documents: [Loading documents][].

The following example demonstrates how to load encrypted PDF document using password.

> ```
> ```
> 
>    PdfLoadOptions loadOptions = new PdfLoadOptions();
>    loadOptions.setPassword("123");
>    Watermarker watermarker = new Watermarker("C:\\Documents\\test.pdf", loadOptions);
>    // ...
>    watermarker.close();
>  
> ```
> ```


[Loading documents]: https://docs.groupdocs.com/display/watermarkjava/Loading+documents

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The file path to load document from. |
| options | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) | Additional options to use when loading a document. |

### Watermarker(String filePath, WatermarkerSettings settings) {#Watermarker-java.lang.String-com.groupdocs.watermark.WatermarkerSettings-}
```
public Watermarker(String filePath, WatermarkerSettings settings)
```


Initializes a new instance of the `[Watermarker](../../com.groupdocs.watermark/watermarker)` class with the specified document path and settings.

Learn more about loading documents: [Loading documents][].

The following example demonstrates how to set searchable objects globally (for all documents that will be loaded after that).

> ```
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
> ```


[Loading documents]: https://docs.groupdocs.com/display/watermarkjava/Loading+documents

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The file path to load document from. |
| settings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) | Additional settings to use when working with loaded document. |

### Watermarker(String filePath, LoadOptions options, WatermarkerSettings settings) {#Watermarker-java.lang.String-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-}
```
public Watermarker(String filePath, LoadOptions options, WatermarkerSettings settings)
```


Initializes a new instance of the `[Watermarker](../../com.groupdocs.watermark/watermarker)` class with the specified document path, load options and settings.

Learn more about loading documents: [Loading documents][].

The following example demonstrates how to find particular text fragments in email message body/subject.

> ```
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
> ```


[Loading documents]: https://docs.groupdocs.com/display/watermarknet/Loading+documents

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The file path to load document from. |
| options | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) | Additional options to use when loading a document. |
| settings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) | Additional settings to use when working with loaded document. |

### Watermarker(InputStream document) {#Watermarker-java.io.InputStream-}
```
public Watermarker(InputStream document)
```


Initializes a new instance of the `[Watermarker](../../com.groupdocs.watermark/watermarker)` class with the specified stream.

Learn more about loading documents: [Loading documents][].

The following example demonstrates how to load and save a document of any supported format.

> ```
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
> ```


[Loading documents]: https://docs.groupdocs.com/display/watermarknet/Loading+documents

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | java.io.InputStream | The stream to load document from. |

### Watermarker(InputStream document, LoadOptions options) {#Watermarker-java.io.InputStream-com.groupdocs.watermark.options.LoadOptions-}
```
public Watermarker(InputStream document, LoadOptions options)
```


Initializes a new instance of the `[Watermarker](../../com.groupdocs.watermark/watermarker)` class with the specified stream and load options.

Learn more about loading documents: [Loading documents][].

The following example demonstrates how to load encrypted PDF document using password

> ```
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
> ```


[Loading documents]: https://docs.groupdocs.com/display/watermarknet/Loading+documents

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | java.io.InputStream | The stream to load document from. |
| options | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) | Additional options to use when loading a document. |

### Watermarker(InputStream document, WatermarkerSettings settings) {#Watermarker-java.io.InputStream-com.groupdocs.watermark.WatermarkerSettings-}
```
public Watermarker(InputStream document, WatermarkerSettings settings)
```


Initializes a new instance of the `[Watermarker](../../com.groupdocs.watermark/watermarker)` class with the specified stream and settings.

Learn more about loading documents: [Loading documents][].

The following example demonstrates how to set searchable objects globally (for all documents that will be loaded after that).

> ```
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
> ```


[Loading documents]: https://docs.groupdocs.com/display/watermarknet/Loading+documents

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | java.io.InputStream | The stream to load document from. |
| settings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) | Additional settings to use when working with loaded document. |

### Watermarker(InputStream document, LoadOptions options, WatermarkerSettings settings) {#Watermarker-java.io.InputStream-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-}
```
public Watermarker(InputStream document, LoadOptions options, WatermarkerSettings settings)
```


Initializes a new instance of the  class with the specified stream, load options and settings.

Learn more about loading documents: [Loading documents][].

The following example demonstrates how to set searchable objects globally (for all documents that will be loaded after that).

> ```
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
> ```


[Loading documents]: https://docs.groupdocs.com/display/watermarknet/Loading+documents

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | java.io.InputStream | The stream to load document from. |
| options | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) | Additional options to use when loading a document. |
| settings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) | Additional settings to use when working with loaded document. |

### Watermarker(System.IO.Stream document, LoadOptions options, WatermarkerSettings settings) {#Watermarker-com.aspose.ms.System.IO.Stream-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-}
```
public Watermarker(System.IO.Stream document, LoadOptions options, WatermarkerSettings settings)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | com.aspose.ms.System.IO.Stream |  |
| options | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) |  |
| settings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) |  |

### getSearchableObjects() {#getSearchableObjects--}
```
public final SearchableObjects getSearchableObjects()
```


Gets the content objects that are to be included in a watermark search.

This mathod also specifies content objects which are used in image search. For more information see `#search(SearchCriteria).search(SearchCriteria)` and `#getImages().getImages()` methods.

Learn more about searching watermarks: [Searching watermarks][].

The following example demonstrates how to remove all XObjects and Artifacts from a pdf document.

> ```
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
> ```


[Searching watermarks]: https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks

**Returns:**
[SearchableObjects](../../com.groupdocs.watermark.search/searchableobjects) - The objects that are to be included in a watermark search.
### setSearchableObjects(SearchableObjects value) {#setSearchableObjects-com.groupdocs.watermark.search.SearchableObjects-}
```
public final void setSearchableObjects(SearchableObjects value)
```


Sets the content objects that are to be included in a watermark search.

This mathod also specifies content objects which are used in image search. For more information see `#search(SearchCriteria).search(SearchCriteria)` and `#getImages().getImages()` methods. Learn more about searching watermarks: [Searching watermarks][].

The following example demonstrates how to remove all XObjects and Artifacts from a pdf document.

> ```
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
> ```


[Searching watermarks]: https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [SearchableObjects](../../com.groupdocs.watermark.search/searchableobjects) | The objects that are to be included in a watermark search. |

### dispose() {#dispose--}
```
public final void dispose()
```




### close() {#close--}
```
public final void close()
```


Disposes the current instance.

### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


Gets the information about the format of the loaded document.

Learn more about getting the document information [Get document info][].

The following example demonstrates how to get information about a document of any supported type.

> ```
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
> ```


[Get document info]: https://docs.groupdocs.com/display/watermarkjava/Get+document+info

**Returns:**
[IDocumentInfo](../../com.groupdocs.watermark.common/idocumentinfo) - The `[IDocumentInfo](../../com.groupdocs.watermark.common/idocumentinfo)` instance that contains detected information.
### add(Watermark watermark) {#add-com.groupdocs.watermark.Watermark-}
```
public final void add(Watermark watermark)
```


Adds a watermark to the loaded document.

Learn more about adding watermarks: [Adding watermarks][].

The following example demonstrates how to add image and text watermark to a document of any supported type.

> ```
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
> ```


[Adding watermarks]: https://docs.groupdocs.com/display/watermarkjava/Adding+watermarks

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) | The watermark to add to the document. |

### add(Watermark watermark, WatermarkOptions options) {#add-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.WatermarkOptions-}
```
public final void add(Watermark watermark, WatermarkOptions options)
```


Adds a watermark to the loaded document using watermark options.

Learn more about adding watermarks: [Adding watermarks][].

The following example demonstrates how to add an image watermark to a particular page of a pdf document.

> ```
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
> ```


[Adding watermarks]: https://docs.groupdocs.com/display/watermarkjava/Adding+watermarks

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| watermark | [Watermark](../../com.groupdocs.watermark/watermark) | The watermark to add to the document. |
| options | [WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions) | Additional options to use when adding the watermark. |

### remove(PossibleWatermark possibleWatermark) {#remove-com.groupdocs.watermark.search.PossibleWatermark-}
```
public final void remove(PossibleWatermark possibleWatermark)
```


Removes watermark from the document.

Learn more about removing watermarks: [Removing found watermarks][].

The following example demonstrates how to find and remove the first possible watermark containing particular text or image from a document of any supported type.

> ```
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
> ```


[Removing found watermarks]: https://docs.groupdocs.com/display/watermarkjava/Removing+found+watermarks

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| possibleWatermark | [PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark) | The watermark to remove. |

### remove(PossibleWatermarkCollection possibleWatermarks) {#remove-com.groupdocs.watermark.search.PossibleWatermarkCollection-}
```
public final void remove(PossibleWatermarkCollection possibleWatermarks)
```


Removes all watermarks in the collection from the document.

Learn more about removing watermarks: [Removing found watermarks][].

The following example demonstrates how to find and remove all possible watermarks containing particular text or image from a document of any supported type.

> ```
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
> ```


[Removing found watermarks]: https://docs.groupdocs.com/display/watermarkjava/Removing+found+watermarks

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| possibleWatermarks | [PossibleWatermarkCollection](../../com.groupdocs.watermark.search/possiblewatermarkcollection) | The collection of watermarks to remove. |

### save(String filePath) {#save-java.lang.String-}
```
public final void save(String filePath)
```


Saves the document to the specified file location.

Learn more about saving the documents [Saving documents][].

The following example demonstrates how to add the watermark and save the document to another file.

> ```
> ```
> 
>    Watermarker watermarker = new Watermarker("input.pdf");
>    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
>    watermarker.add(watermark);
>    watermarker.save("output.pdf");
>    watermarker.close();
>  
> ```
> ```


[Saving documents]: https://docs.groupdocs.com/display/watermarkjava/Saving+documents

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The file path to save the document data to. |

### save(OutputStream document) {#save-java.io.OutputStream-}
```
public final void save(OutputStream document)
```


Saves the document to the specified stream.

Learn more about saving the documents [Saving documents][].

The following example demonstrates how to add watermark and save the document to the memory stream.

> ```
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
> ```


[Saving documents]: https://docs.groupdocs.com/display/watermarkjava/Saving+documents

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | java.io.OutputStream | The stream to save the document data to. |

### save(String filePath, SaveOptions options) {#save-java.lang.String-com.groupdocs.watermark.options.SaveOptions-}
```
public final void save(String filePath, SaveOptions options)
```


Saves the document to the specified file location using save options.

Learn more about saving the documents [Saving documents][].

The following example demonstrates how to add the watermark and save the document to another file with default `[SaveOptions](../../com.groupdocs.watermark.options/saveoptions)`.

> ```
> ```
> 
>    Watermarker watermarker = new Watermarker("input.pdf");
>    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
>    watermarker.add(watermark);
>    watermarker.save("output.pdf", new SaveOptions());
>    watermarker.close();
>  
> ```
> ```


[Saving documents]: https://docs.groupdocs.com/display/watermarkjava/Saving+documents

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The file path to save the document data to. |
| options | [SaveOptions](../../com.groupdocs.watermark.options/saveoptions) | Additional options to use when saving a document. |

### save(OutputStream document, SaveOptions options) {#save-java.io.OutputStream-com.groupdocs.watermark.options.SaveOptions-}
```
public final void save(OutputStream document, SaveOptions options)
```


Saves the document to the specified stream using save options.

Learn more about saving the documents [Saving documents][].

The following example demonstrates how to add watermark and save the document to the memory stream with default `[SaveOptions](../../com.groupdocs.watermark.options/saveoptions)`.

> ```
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
> ```


[Saving documents]: https://docs.groupdocs.com/display/watermarkjava/Saving+documents

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | java.io.OutputStream | The stream to save the document data to. |
| options | [SaveOptions](../../com.groupdocs.watermark.options/saveoptions) | Additional options to use when saving a document. |

### generatePreview(PreviewOptions previewOptions) {#generatePreview-com.groupdocs.watermark.options.PreviewOptions-}
```
public final void generatePreview(PreviewOptions previewOptions)
```


Generates preview images for the document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| previewOptions | [PreviewOptions](../../com.groupdocs.watermark.options/previewoptions) | Additional options to use when generating preview images. |

### search() {#search--}
```
public final PossibleWatermarkCollection search()
```


Searches all possible watermarks in the document.

The search is conducted in objects specified with `#setSearchableObjects(SearchableObjects).setSearchableObjects(SearchableObjects)`.

Learn more about searching watermarks [Searching watermarks][].

The following example demonstrates how to count the possible watermarks in a document of any supported type.

> ```
> ```
> 
>    Watermarker watermarker = new Watermarker("input.doc");
>    PossibleWatermarkCollection watermarks = watermarker.search();
>    System.out.println(watermarks.getCount());
>    watermarker.close();
>  
> ```
> ```


[Searching watermarks]: https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks

**Returns:**
[PossibleWatermarkCollection](../../com.groupdocs.watermark.search/possiblewatermarkcollection)
### search(SearchCriteria searchCriteria) {#search-com.groupdocs.watermark.search.SearchCriteria-}
```
public final PossibleWatermarkCollection search(SearchCriteria searchCriteria)
```


Searches possible watermarks according to specified search criteria.

The search is conducted in objects specified with `#setSearchableObjects(SearchableObjects).setSearchableObjects(SearchableObjects)`.

Learn more about searching watermarks [Searching watermarks][].

The following example demonstrates how to find and remove all possible watermarks containing particular text or image from a document of any supported type.

> ```
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
> ```


[Searching watermarks]: https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| searchCriteria | [SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) | The search criteria to use. |

**Returns:**
[PossibleWatermarkCollection](../../com.groupdocs.watermark.search/possiblewatermarkcollection)
### getImages(ImageSearchCriteria searchCriteria) {#getImages-com.groupdocs.watermark.search.ImageSearchCriteria-}
```
public final WatermarkableImageCollection getImages(ImageSearchCriteria searchCriteria)
```


Finds images according to specified search criteria.

The search is conducted in objects specified with `#setSearchableObjects(SearchableObjects).setSearchableObjects(SearchableObjects)`.

Learn more about searching watermarks [Searching watermarks][].

The following example demonstrates how to remove all images that are similar to the reference from a document of any supported type.

> ```
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
> ```


[Searching watermarks]: https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| searchCriteria | [ImageSearchCriteria](../../com.groupdocs.watermark.search/imagesearchcriteria) | The search criteria to use. |

**Returns:**
[WatermarkableImageCollection](../../com.groupdocs.watermark.contents/watermarkableimagecollection)
### getImages() {#getImages--}
```
public final WatermarkableImageCollection getImages()
```


Finds all images in the document.

The search is conducted in objects specified with `#setSearchableObjects(SearchableObjects).setSearchableObjects(SearchableObjects)`.

Learn more about searching watermarks [Searching watermarks][].

The following example demonstrates how to add watermark to all images in a document of any supported type.

> ```
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
> ```


[Searching watermarks]: https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks

**Returns:**
[WatermarkableImageCollection](../../com.groupdocs.watermark.contents/watermarkableimagecollection) - The collection of found images.
### <T>getContent(Class<T> contentType) {#-T-getContent-java.lang.Class-T--}
```
public final T <T>getContent(Class<T> contentType)
```


Returns the `[Content](../../com.groupdocs.watermark.contents/content)` object for the loaded document.

The following example demonstrates how to rasterize pdf document page with added watermark.

> ```
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
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| contentType | java.lang.Class<T> | The requested type of a `[Content](../../com.groupdocs.watermark.contents/content)` object. |

**Returns:**
T - The `[Content](../../com.groupdocs.watermark.contents/content)` object for the loaded document.
