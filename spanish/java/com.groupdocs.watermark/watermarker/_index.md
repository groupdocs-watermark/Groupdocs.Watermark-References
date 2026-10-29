---
title: "Watermarker"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Representa una clase para la gestión de marcas de agua en un documento."
type: docs
weight: 14
url: /es/java/com.groupdocs.watermark/watermarker/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class Watermarker implements Closeable
```

Representa una clase para la gestión de marcas de agua en un documento.

El siguiente ejemplo muestra cómo cargar y guardar el contenido de cualquier formato compatible.
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


## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [Watermarker(String filePath)](#Watermarker-java.lang.String-) | Inicializa una nueva instancia de la clase `[Watermarker](../../com.groupdocs.watermark/watermarker)` con la ruta del documento especificada. |
|
|  | [Watermarker(String filePath, LoadOptions options)](#Watermarker-java.lang.String-com.groupdocs.watermark.options.LoadOptions-) | Inicializa una nueva instancia de la clase `[Watermarker](../../com.groupdocs.watermark/watermarker)` con la ruta del documento especificada y opciones de carga. |
|
|  | [Watermarker(String filePath, WatermarkerSettings settings)](#Watermarker-java.lang.String-com.groupdocs.watermark.WatermarkerSettings-) | Inicializa una nueva instancia de la clase `[Watermarker](../../com.groupdocs.watermark/watermarker)` con la ruta del documento especificada y la configuración. |
|
|  | [Watermarker(String filePath, LoadOptions options, WatermarkerSettings settings)](#Watermarker-java.lang.String-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-) | Inicializa una nueva instancia de la clase `[Watermarker](../../com.groupdocs.watermark/watermarker)` con la ruta del documento especificada, opciones de carga y la configuración. |
|
|  | [Watermarker(InputStream document)](#Watermarker-java.io.InputStream-) | Inicializa una nueva instancia de la clase `[Watermarker](../../com.groupdocs.watermark/watermarker)` con el flujo especificado. |
|
|  | [Watermarker(InputStream document, LoadOptions options)](#Watermarker-java.io.InputStream-com.groupdocs.watermark.options.LoadOptions-) | Inicializa una nueva instancia de la clase `[Watermarker](../../com.groupdocs.watermark/watermarker)` con el flujo especificado y opciones de carga. |
|
|  | [Watermarker(InputStream document, WatermarkerSettings settings)](#Watermarker-java.io.InputStream-com.groupdocs.watermark.WatermarkerSettings-) | Inicializa una nueva instancia de la clase `[Watermarker](../../com.groupdocs.watermark/watermarker)` con el flujo especificado y la configuración. |
|
|  | [Watermarker(InputStream document, LoadOptions options, WatermarkerSettings settings)](#Watermarker-java.io.InputStream-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-) | Inicializa una nueva instancia de la clase con el flujo especificado, opciones de carga y la configuración. |
|
| [Watermarker(System.IO.Stream document, LoadOptions options, WatermarkerSettings settings)](#Watermarker-com.aspose.ms.System.IO.Stream-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getSearchableObjects()](#getSearchableObjects--) | Obtiene los objetos de contenido que se incluirán en una búsqueda de marca de agua. |
|
|  | [setSearchableObjects(SearchableObjects value)](#setSearchableObjects-com.groupdocs.watermark.search.SearchableObjects-) | Establece los objetos de contenido que se incluirán en una búsqueda de marca de agua. |
|
| [dispose()](#dispose--) |  |
|  | [close()](#close--) | Elimina la instancia actual. |
|
|  | [getDocumentInfo()](#getDocumentInfo--) | Obtiene la información sobre el formato del documento cargado. |
|
|  | [add(Watermark watermark)](#add-com.groupdocs.watermark.Watermark-) | Agrega una marca de agua al documento cargado. |
|
|  | [add(Watermark watermark, WatermarkOptions options)](#add-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.WatermarkOptions-) | Agrega una marca de agua al documento cargado usando opciones de marca de agua. |
|
|  | [remove(PossibleWatermark possibleWatermark)](#remove-com.groupdocs.watermark.search.PossibleWatermark-) | Elimina la marca de agua del documento. |
|
|  | [remove(PossibleWatermarkCollection possibleWatermarks)](#remove-com.groupdocs.watermark.search.PossibleWatermarkCollection-) | Elimina todas las marcas de agua de la colección del documento. |
|
|  | [save(String filePath)](#save-java.lang.String-) | Guarda el documento en la ubicación de archivo especificada. |
|
|  | [save(OutputStream document)](#save-java.io.OutputStream-) | Guarda el documento en el flujo especificado. |
|
|  | [save(String filePath, SaveOptions options)](#save-java.lang.String-com.groupdocs.watermark.options.SaveOptions-) | Guarda el documento en la ubicación de archivo especificada usando opciones de guardado. |
|
|  | [save(OutputStream document, SaveOptions options)](#save-java.io.OutputStream-com.groupdocs.watermark.options.SaveOptions-) | Guarda el documento en el flujo especificado usando opciones de guardado. |
|
|  | [generatePreview(PreviewOptions previewOptions)](#generatePreview-com.groupdocs.watermark.options.PreviewOptions-) | Genera imágenes de vista previa para el documento. |
|
|  | [search()](#search--) | Busca todas las marcas de agua posibles en el documento. |
|
|  | [search(SearchCriteria searchCriteria)](#search-com.groupdocs.watermark.search.SearchCriteria-) | Busca marcas de agua posibles según los criterios de búsqueda especificados. |
|
|  | [getImages(ImageSearchCriteria searchCriteria)](#getImages-com.groupdocs.watermark.search.ImageSearchCriteria-) | Encuentra imágenes según los criterios de búsqueda especificados. |
|
|  | [getImages()](#getImages--) | Encuentra todas las imágenes en el documento. |
|
|  | [<T>getContent(Class<T> contentType)](#-T-getContent-java.lang.Class-T--) | Devuelve el objeto `[Content](../../com.groupdocs.watermark.contents/content)` para el documento cargado. |
|
### Watermarker(String filePath) {#Watermarker-java.lang.String-}
```
public Watermarker(String filePath)
```


Inicializa una nueva instancia de la clase `[Watermarker](../../com.groupdocs.watermark/watermarker)` con la ruta del documento especificada.

Obtén más información sobre la carga de documentos:
[Loading documents](../https://docs.groupdocs.com/display/watermarkjava/Loading+documents).

El siguiente ejemplo muestra cómo cargar y guardar el contenido de cualquier formato compatible.
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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | filePath | java.lang.String | La ruta del archivo desde la cual cargar el documento. |
|

### Watermarker(String filePath, LoadOptions options) {#Watermarker-java.lang.String-com.groupdocs.watermark.options.LoadOptions-}
```
public Watermarker(String filePath, LoadOptions options)
```


Inicializa una nueva instancia de la clase `[Watermarker](../../com.groupdocs.watermark/watermarker)` con la ruta del documento especificada y opciones de carga.

Obtén más información sobre la carga de documentos:
[Loading documents](../https://docs.groupdocs.com/display/watermarkjava/Loading+documents).

El siguiente ejemplo muestra cómo cargar un documento PDF cifrado usando una contraseña.
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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | filePath | java.lang.String | La ruta del archivo desde la cual cargar el documento. |
|
|  | options | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) | Opciones adicionales para usar al cargar un documento. |
|

### Watermarker(String filePath, WatermarkerSettings settings) {#Watermarker-java.lang.String-com.groupdocs.watermark.WatermarkerSettings-}
```
public Watermarker(String filePath, WatermarkerSettings settings)
```


Inicializa una nueva instancia de la clase `[Watermarker](../../com.groupdocs.watermark/watermarker)` con la ruta del documento especificada y la configuración.

Obtén más información sobre la carga de documentos:
[Loading documents](../https://docs.groupdocs.com/display/watermarkjava/Loading+documents).

El siguiente ejemplo muestra cómo establecer objetos buscables globalmente (para todos los documentos que
se cargarán después de eso).
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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | filePath | java.lang.String | La ruta del archivo desde la cual cargar el documento. |
|
|  | settings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) | Configuraciones adicionales para usar al trabajar con el documento cargado. |
|

### Watermarker(String filePath, LoadOptions options, WatermarkerSettings settings) {#Watermarker-java.lang.String-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-}
```
public Watermarker(String filePath, LoadOptions options, WatermarkerSettings settings)
```


Inicializa una nueva instancia de la clase `[Watermarker](../../com.groupdocs.watermark/watermarker)` con la ruta del documento especificada, opciones de carga y la configuración.

Obtén más información sobre la carga de documentos:
[Loading documents](../https://docs.groupdocs.com/display/watermarknet/Loading+documents).

El siguiente ejemplo muestra cómo encontrar fragmentos de texto particulares en el cuerpo/asunto del mensaje de correo electrónico.
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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | filePath | java.lang.String | La ruta del archivo desde la cual cargar el documento. |
|
|  | options | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) | Opciones adicionales para usar al cargar un documento. |
|
|  | settings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) | Configuraciones adicionales para usar al trabajar con el documento cargado. |
|

### Watermarker(InputStream document) {#Watermarker-java.io.InputStream-}
```
public Watermarker(InputStream document)
```


Inicializa una nueva instancia de la clase `[Watermarker](../../com.groupdocs.watermark/watermarker)` con el flujo especificado.

Obtén más información sobre la carga de documentos:
[Loading documents](../https://docs.groupdocs.com/display/watermarknet/Loading+documents).

El siguiente ejemplo muestra cómo cargar y guardar un documento en cualquier formato compatible.
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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | documento | java.io.InputStream | El flujo para cargar el documento. |
|

### Watermarker(InputStream document, LoadOptions options) {#Watermarker-java.io.InputStream-com.groupdocs.watermark.options.LoadOptions-}
```
public Watermarker(InputStream document, LoadOptions options)
```


Inicializa una nueva instancia de la clase `[Watermarker](../../com.groupdocs.watermark/watermarker)` con el flujo especificado y opciones de carga.

Obtén más información sobre la carga de documentos:
[Loading documents](../https://docs.groupdocs.com/display/watermarknet/Loading+documents).

El siguiente ejemplo muestra cómo cargar un documento PDF cifrado usando una contraseña
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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | documento | java.io.InputStream | El flujo para cargar el documento. |
|
|  | options | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) | Opciones adicionales para usar al cargar un documento. |
|

### Watermarker(InputStream document, WatermarkerSettings settings) {#Watermarker-java.io.InputStream-com.groupdocs.watermark.WatermarkerSettings-}
```
public Watermarker(InputStream document, WatermarkerSettings settings)
```


Inicializa una nueva instancia de la clase `[Watermarker](../../com.groupdocs.watermark/watermarker)` con el flujo especificado y la configuración.

Obtén más información sobre la carga de documentos:
[Loading documents](../https://docs.groupdocs.com/display/watermarknet/Loading+documents).

El siguiente ejemplo muestra cómo establecer objetos buscables globalmente (para todos los documentos que
se cargarán después de eso).
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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | documento | java.io.InputStream | El flujo para cargar el documento. |
|
|  | settings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) | Configuraciones adicionales para usar al trabajar con el documento cargado. |
|

### Watermarker(InputStream document, LoadOptions options, WatermarkerSettings settings) {#Watermarker-java.io.InputStream-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-}
```
public Watermarker(InputStream document, LoadOptions options, WatermarkerSettings settings)
```


Inicializa una nueva instancia de la clase con el flujo especificado, opciones de carga y la configuración.

Obtén más información sobre la carga de documentos:
[Loading documents](../https://docs.groupdocs.com/display/watermarknet/Loading+documents).

El siguiente ejemplo muestra cómo establecer objetos buscables globalmente (para todos los documentos que
se cargarán después de eso).
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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | documento | java.io.InputStream | El flujo para cargar el documento. |
|
|  | options | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) | Opciones adicionales para usar al cargar un documento. |
|
|  | settings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) | Configuraciones adicionales para usar al trabajar con el documento cargado. |
|

### Watermarker(System.IO.Stream document, LoadOptions options, WatermarkerSettings settings) {#Watermarker-com.aspose.ms.System.IO.Stream-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-}
```
public Watermarker(System.IO.Stream document, LoadOptions options, WatermarkerSettings settings)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| documento | com.aspose.ms.System.IO.Stream |  |
| options | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) |  |
| settings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) |  |

### getSearchableObjects() {#getSearchableObjects--}
```
public final SearchableObjects getSearchableObjects()
```


Obtiene los objetos de contenido que se incluirán en una búsqueda de marca de agua.

Este método también especifica objetos de contenido que se utilizan en la búsqueda de imágenes.
Para obtener más información, vea `#search(SearchCriteria).search(SearchCriteria)`
y los métodos `#getImages().getImages()`.

Obtenga más información sobre la búsqueda de marcas de agua:
[Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks).

El siguiente ejemplo muestra cómo eliminar todos los XObjects y Artefactos de un documento PDF.
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


Establece los objetos de contenido que se incluirán en una búsqueda de marca de agua.

Este método también especifica objetos de contenido que se utilizan en la búsqueda de imágenes.
Para obtener más información, vea `#search(SearchCriteria).search(SearchCriteria)`
y los métodos `#getImages().getImages()`.
Obtenga más información sobre la búsqueda de marcas de agua:
[Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks).

El siguiente ejemplo muestra cómo eliminar todos los XObjects y Artefactos de un documento PDF.
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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | [SearchableObjects](../../com.groupdocs.watermark.search/searchableobjects) | Los objetos que se incluirán en una búsqueda de marcas de agua. |
|

### dispose() {#dispose--}
```
public final void dispose()
```




### close() {#close--}
```
public final void close()
```


Elimina la instancia actual.


### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


Obtiene la información sobre el formato del documento cargado.

Obtenga más información sobre cómo obtener la información del documento
[Get document info](../https://docs.groupdocs.com/display/watermarkjava/Get+document+info).

El siguiente ejemplo muestra cómo obtener información sobre un documento de cualquier tipo compatible.
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


Agrega una marca de agua al documento cargado.

Obtenga más información sobre cómo agregar marcas de agua:
[Adding watermarks](../https://docs.groupdocs.com/display/watermarkjava/Adding+watermarks).

El siguiente ejemplo muestra cómo agregar una marca de agua de imagen y texto a un documento de cualquier tipo compatible.
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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | watermark | [Watermark](../../com.groupdocs.watermark/watermark) | La marca de agua a agregar al documento. |
|

### add(Watermark watermark, WatermarkOptions options) {#add-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.WatermarkOptions-}
```
public final void add(Watermark watermark, WatermarkOptions options)
```


Agrega una marca de agua al documento cargado usando opciones de marca de agua.

Obtenga más información sobre cómo agregar marcas de agua:
[Adding watermarks](../https://docs.groupdocs.com/display/watermarkjava/Adding+watermarks).

El siguiente ejemplo muestra cómo agregar una marca de agua de imagen a una página específica de un documento PDF.
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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | watermark | [Watermark](../../com.groupdocs.watermark/watermark) | La marca de agua a agregar al documento. |
|
|  | options | [WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions) | Opciones adicionales para usar al agregar la marca de agua. |
|

### remove(PossibleWatermark possibleWatermark) {#remove-com.groupdocs.watermark.search.PossibleWatermark-}
```
public final void remove(PossibleWatermark possibleWatermark)
```


Elimina la marca de agua del documento.

Obtenga más información sobre cómo eliminar marcas de agua:
[Removing found watermarks](../https://docs.groupdocs.com/display/watermarkjava/Removing+found+watermarks).

El siguiente ejemplo muestra cómo encontrar y eliminar la primera posible marca de agua que contiene un determinado
texto o imagen de un documento de cualquier tipo compatible.
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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | possibleWatermark | [PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark) | La marca de agua a eliminar. |
|

### remove(PossibleWatermarkCollection possibleWatermarks) {#remove-com.groupdocs.watermark.search.PossibleWatermarkCollection-}
```
public final void remove(PossibleWatermarkCollection possibleWatermarks)
```


Elimina todas las marcas de agua de la colección del documento.

Obtenga más información sobre cómo eliminar marcas de agua:
[Removing found watermarks](../https://docs.groupdocs.com/display/watermarkjava/Removing+found+watermarks).

El siguiente ejemplo muestra cómo encontrar y eliminar todas las posibles marcas de agua que contienen un determinado
texto o imagen de un documento de cualquier tipo compatible.
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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | possibleWatermarks | [PossibleWatermarkCollection](../../com.groupdocs.watermark.search/possiblewatermarkcollection) | La colección de marcas de agua a eliminar. |
|

### save(String filePath) {#save-java.lang.String-}
```
public final void save(String filePath)
```


Guarda el documento en la ubicación de archivo especificada.

Obtenga más información sobre cómo guardar los documentos
[Saving documents](../https://docs.groupdocs.com/display/watermarkjava/Saving+documents).

El siguiente ejemplo muestra cómo agregar la marca de agua y guardar el documento en otro archivo.
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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | filePath | java.lang.String | La ruta del archivo donde guardar los datos del documento. |
|

### save(OutputStream document) {#save-java.io.OutputStream-}
```
public final void save(OutputStream document)
```


Guarda el documento en el flujo especificado.

Obtenga más información sobre cómo guardar los documentos
[Saving documents](../https://docs.groupdocs.com/display/watermarkjava/Saving+documents).

El siguiente ejemplo muestra cómo agregar una marca de agua y guardar el documento en el flujo de memoria.
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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | documento | java.io.OutputStream | El flujo donde guardar los datos del documento. |
|

### save(String filePath, SaveOptions options) {#save-java.lang.String-com.groupdocs.watermark.options.SaveOptions-}
```
public final void save(String filePath, SaveOptions options)
```


Guarda el documento en la ubicación de archivo especificada usando opciones de guardado.

Obtenga más información sobre cómo guardar los documentos
[Saving documents](../https://docs.groupdocs.com/display/watermarkjava/Saving+documents).

El siguiente ejemplo muestra cómo agregar la marca de agua y guardar el documento en otro archivo
con los `[SaveOptions](../../com.groupdocs.watermark.options/saveoptions)` predeterminados.
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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | filePath | java.lang.String | La ruta del archivo donde guardar los datos del documento. |
|
|  | options | [SaveOptions](../../com.groupdocs.watermark.options/saveoptions) | Opciones adicionales para usar al guardar un documento. |
|

### save(OutputStream document, SaveOptions options) {#save-java.io.OutputStream-com.groupdocs.watermark.options.SaveOptions-}
```
public final void save(OutputStream document, SaveOptions options)
```


Guarda el documento en el flujo especificado usando opciones de guardado.

Obtenga más información sobre cómo guardar los documentos
[Saving documents](../https://docs.groupdocs.com/display/watermarkjava/Saving+documents).

El siguiente ejemplo muestra cómo agregar una marca de agua y guardar el documento en el flujo de memoria
con los `[SaveOptions](../../com.groupdocs.watermark.options/saveoptions)` predeterminados.
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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | documento | java.io.OutputStream | El flujo donde guardar los datos del documento. |
|
|  | options | [SaveOptions](../../com.groupdocs.watermark.options/saveoptions) | Opciones adicionales para usar al guardar un documento. |
|

### generatePreview(PreviewOptions previewOptions) {#generatePreview-com.groupdocs.watermark.options.PreviewOptions-}
```
public final void generatePreview(PreviewOptions previewOptions)
```


Genera imágenes de vista previa para el documento.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | previewOptions | [PreviewOptions](../../com.groupdocs.watermark.options/previewoptions) | Opciones adicionales para usar al generar imágenes de vista previa. |
|

### search() {#search--}
```
public final PossibleWatermarkCollection search()
```


Busca todas las marcas de agua posibles en el documento.

La búsqueda se realiza en los objetos especificados con `#setSearchableObjects(SearchableObjects).setSearchableObjects(SearchableObjects)`.

Obtén más información sobre la búsqueda de marcas de agua
[Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks).

El siguiente ejemplo muestra cómo contar las posibles marcas de agua en un documento de cualquier tipo compatible.
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


Busca marcas de agua posibles según los criterios de búsqueda especificados.

La búsqueda se realiza en los objetos especificados con `#setSearchableObjects(SearchableObjects).setSearchableObjects(SearchableObjects)`.

Obtén más información sobre la búsqueda de marcas de agua
[Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks).

El siguiente ejemplo muestra cómo encontrar y eliminar todas las posibles marcas de agua que contienen texto específico
o imagen de un documento de cualquier tipo compatible.
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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | searchCriteria | [SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) | Los criterios de búsqueda a usar. |
|

**Returns:**
[PossibleWatermarkCollection](../../com.groupdocs.watermark.search/possiblewatermarkcollection)
### getImages(ImageSearchCriteria searchCriteria) {#getImages-com.groupdocs.watermark.search.ImageSearchCriteria-}
```
public final WatermarkableImageCollection getImages(ImageSearchCriteria searchCriteria)
```


Encuentra imágenes según los criterios de búsqueda especificados.

La búsqueda se realiza en los objetos especificados con `#setSearchableObjects(SearchableObjects).setSearchableObjects(SearchableObjects)`.

Obtén más información sobre la búsqueda de marcas de agua
[Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks).

El siguiente ejemplo muestra cómo eliminar todas las imágenes que son similares a la referencia
de un documento de cualquier tipo compatible.
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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | searchCriteria | [ImageSearchCriteria](../../com.groupdocs.watermark.search/imagesearchcriteria) | Los criterios de búsqueda a usar. |
|

**Returns:**
[WatermarkableImageCollection](../../com.groupdocs.watermark.contents/watermarkableimagecollection)
### getImages() {#getImages--}
```
public final WatermarkableImageCollection getImages()
```


Encuentra todas las imágenes en el documento.

La búsqueda se realiza en los objetos especificados con `#setSearchableObjects(SearchableObjects).setSearchableObjects(SearchableObjects)`.

Obtén más información sobre la búsqueda de marcas de agua
[Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks).

El siguiente ejemplo muestra cómo agregar una marca de agua a todas las imágenes en un documento de cualquier tipo compatible.
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


Devuelve el objeto `[Content](../../com.groupdocs.watermark.contents/content)` para el documento cargado.

El siguiente ejemplo muestra cómo rasterizar la página de un documento PDF con una marca de agua añadida.
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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | contentType | java.lang.Class<T> | El tipo solicitado de un objeto `[Content](../../com.groupdocs.watermark.contents/content)`. |
|

**Returns:**
T - El objeto `[Content](../../com.groupdocs.watermark.contents/content)` para el documento cargado.

