---
title: "Watermarker"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Rappresenta una classe per la gestione dei watermark in un documento."
type: docs
weight: 14
url: /it/java/com.groupdocs.watermark/watermarker/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class Watermarker implements Closeable
```

Rappresenta una classe per la gestione dei watermark in un documento.

Il seguente esempio dimostra come caricare e salvare il contenuto di qualsiasi formato supportato.
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


## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [Watermarker(String filePath)](#Watermarker-java.lang.String-) | Inizializza una nuova istanza della classe `[Watermarker](../../com.groupdocs.watermark/watermarker)` con il percorso del documento specificato. |
|
|  | [Watermarker(String filePath, LoadOptions options)](#Watermarker-java.lang.String-com.groupdocs.watermark.options.LoadOptions-) | Inizializza una nuova istanza della classe `[Watermarker](../../com.groupdocs.watermark/watermarker)` con il percorso del documento specificato e le opzioni di caricamento. |
|
|  | [Watermarker(String filePath, WatermarkerSettings settings)](#Watermarker-java.lang.String-com.groupdocs.watermark.WatermarkerSettings-) | Inizializza una nuova istanza della classe `[Watermarker](../../com.groupdocs.watermark/watermarker)` con il percorso del documento specificato e le impostazioni. |
|
|  | [Watermarker(String filePath, LoadOptions options, WatermarkerSettings settings)](#Watermarker-java.lang.String-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-) | Inizializza una nuova istanza della classe `[Watermarker](../../com.groupdocs.watermark/watermarker)` con il percorso del documento specificato, le opzioni di caricamento e le impostazioni. |
|
|  | [Watermarker(InputStream document)](#Watermarker-java.io.InputStream-) | Inizializza una nuova istanza della classe `[Watermarker](../../com.groupdocs.watermark/watermarker)` con lo stream specificato. |
|
|  | [Watermarker(InputStream document, LoadOptions options)](#Watermarker-java.io.InputStream-com.groupdocs.watermark.options.LoadOptions-) | Inizializza una nuova istanza della classe `[Watermarker](../../com.groupdocs.watermark/watermarker)` con lo stream specificato e le opzioni di caricamento. |
|
|  | [Watermarker(InputStream document, WatermarkerSettings settings)](#Watermarker-java.io.InputStream-com.groupdocs.watermark.WatermarkerSettings-) | Inizializza una nuova istanza della classe `[Watermarker](../../com.groupdocs.watermark/watermarker)` con lo stream specificato e le impostazioni. |
|
|  | [Watermarker(InputStream document, LoadOptions options, WatermarkerSettings settings)](#Watermarker-java.io.InputStream-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-) | Inizializza una nuova istanza della classe con lo stream specificato, le opzioni di caricamento e le impostazioni. |
|
| [Watermarker(System.IO.Stream document, LoadOptions options, WatermarkerSettings settings)](#Watermarker-com.aspose.ms.System.IO.Stream-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getSearchableObjects()](#getSearchableObjects--) | Ottiene gli oggetti di contenuto da includere in una ricerca di filigrana. |
|
|  | [setSearchableObjects(SearchableObjects value)](#setSearchableObjects-com.groupdocs.watermark.search.SearchableObjects-) | Imposta gli oggetti di contenuto da includere in una ricerca di filigrana. |
|
| [dispose()](#dispose--) |  |
|  | [close()](#close--) | Rilascia l'istanza corrente. |
|
|  | [getDocumentInfo()](#getDocumentInfo--) | Ottiene le informazioni sul formato del documento caricato. |
|
|  | [add(Watermark watermark)](#add-com.groupdocs.watermark.Watermark-) | Aggiunge una filigrana al documento caricato. |
|
|  | [add(Watermark watermark, WatermarkOptions options)](#add-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.WatermarkOptions-) | Aggiunge una filigrana al documento caricato utilizzando le opzioni di filigrana. |
|
|  | [remove(PossibleWatermark possibleWatermark)](#remove-com.groupdocs.watermark.search.PossibleWatermark-) | Rimuove la filigrana dal documento. |
|
|  | [remove(PossibleWatermarkCollection possibleWatermarks)](#remove-com.groupdocs.watermark.search.PossibleWatermarkCollection-) | Rimuove tutte le filigrane nella collezione dal documento. |
|
|  | [save(String filePath)](#save-java.lang.String-) | Salva il documento nella posizione file specificata. |
|
|  | [save(OutputStream document)](#save-java.io.OutputStream-) | Salva il documento nello stream specificato. |
|
|  | [save(String filePath, SaveOptions options)](#save-java.lang.String-com.groupdocs.watermark.options.SaveOptions-) | Salva il documento nella posizione file specificata usando le opzioni di salvataggio. |
|
|  | [save(OutputStream document, SaveOptions options)](#save-java.io.OutputStream-com.groupdocs.watermark.options.SaveOptions-) | Salva il documento nello stream specificato usando le opzioni di salvataggio. |
|
|  | [generatePreview(PreviewOptions previewOptions)](#generatePreview-com.groupdocs.watermark.options.PreviewOptions-) | Genera immagini di anteprima per il documento. |
|
|  | [search()](#search--) | Cerca tutte le possibili filigrane nel documento. |
|
|  | [search(SearchCriteria searchCriteria)](#search-com.groupdocs.watermark.search.SearchCriteria-) | Cerca le filigrane possibili secondo i criteri di ricerca specificati. |
|
|  | [getImages(ImageSearchCriteria searchCriteria)](#getImages-com.groupdocs.watermark.search.ImageSearchCriteria-) | Trova le immagini secondo i criteri di ricerca specificati. |
|
|  | [getImages()](#getImages--) | Trova tutte le immagini nel documento. |
|
|  | [<T>getContent(Class<T> contentType)](#-T-getContent-java.lang.Class-T--) | Restituisce il `[Content](../../com.groupdocs.watermark.contents/content)` oggetto per il documento caricato. |
|
### Watermarker(String filePath) {#Watermarker-java.lang.String-}
```
public Watermarker(String filePath)
```


Inizializza una nuova istanza della classe `[Watermarker](../../com.groupdocs.watermark/watermarker)` con il percorso del documento specificato.

Maggiori informazioni sul caricamento dei documenti:
[Loading documents](../https://docs.groupdocs.com/display/watermarkjava/Loading+documents).

Il seguente esempio dimostra come caricare e salvare il contenuto di qualsiasi formato supportato.
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | filePath | java.lang.String | Il percorso del file da cui caricare il documento. |
|

### Watermarker(String filePath, LoadOptions options) {#Watermarker-java.lang.String-com.groupdocs.watermark.options.LoadOptions-}
```
public Watermarker(String filePath, LoadOptions options)
```


Inizializza una nuova istanza della classe `[Watermarker](../../com.groupdocs.watermark/watermarker)` con il percorso del documento specificato e le opzioni di caricamento.

Maggiori informazioni sul caricamento dei documenti:
[Loading documents](../https://docs.groupdocs.com/display/watermarkjava/Loading+documents).

Il seguente esempio dimostra come caricare un documento PDF crittografato usando la password.
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | filePath | java.lang.String | Il percorso del file da cui caricare il documento. |
|
|  | options | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) | Opzioni aggiuntive da utilizzare durante il caricamento di un documento. |
|

### Watermarker(String filePath, WatermarkerSettings settings) {#Watermarker-java.lang.String-com.groupdocs.watermark.WatermarkerSettings-}
```
public Watermarker(String filePath, WatermarkerSettings settings)
```


Inizializza una nuova istanza della classe `[Watermarker](../../com.groupdocs.watermark/watermarker)` con il percorso del documento specificato e le impostazioni.

Maggiori informazioni sul caricamento dei documenti:
[Loading documents](../https://docs.groupdocs.com/display/watermarkjava/Loading+documents).

Il seguente esempio dimostra come impostare gli oggetti ricercabili globalmente (per tutti i documenti che
verranno caricati successivamente).
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | filePath | java.lang.String | Il percorso del file da cui caricare il documento. |
|
|  | settings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) | Impostazioni aggiuntive da utilizzare quando si lavora con il documento caricato. |
|

### Watermarker(String filePath, LoadOptions options, WatermarkerSettings settings) {#Watermarker-java.lang.String-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-}
```
public Watermarker(String filePath, LoadOptions options, WatermarkerSettings settings)
```


Inizializza una nuova istanza della classe `[Watermarker](../../com.groupdocs.watermark/watermarker)` con il percorso del documento specificato, le opzioni di caricamento e le impostazioni.

Maggiori informazioni sul caricamento dei documenti:
[Loading documents](../https://docs.groupdocs.com/display/watermarknet/Loading+documents).

Il seguente esempio dimostra come trovare particolari frammenti di testo nel corpo/oggetto del messaggio email.
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | filePath | java.lang.String | Il percorso del file da cui caricare il documento. |
|
|  | options | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) | Opzioni aggiuntive da utilizzare durante il caricamento di un documento. |
|
|  | settings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) | Impostazioni aggiuntive da utilizzare quando si lavora con il documento caricato. |
|

### Watermarker(InputStream document) {#Watermarker-java.io.InputStream-}
```
public Watermarker(InputStream document)
```


Inizializza una nuova istanza della classe `[Watermarker](../../com.groupdocs.watermark/watermarker)` con lo stream specificato.

Maggiori informazioni sul caricamento dei documenti:
[Loading documents](../https://docs.groupdocs.com/display/watermarknet/Loading+documents).

Il seguente esempio dimostra come caricare e salvare un documento in qualsiasi formato supportato.
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | documento | java.io.InputStream | Il flusso da cui caricare il documento. |
|

### Watermarker(InputStream document, LoadOptions options) {#Watermarker-java.io.InputStream-com.groupdocs.watermark.options.LoadOptions-}
```
public Watermarker(InputStream document, LoadOptions options)
```


Inizializza una nuova istanza della classe `[Watermarker](../../com.groupdocs.watermark/watermarker)` con lo stream specificato e le opzioni di caricamento.

Maggiori informazioni sul caricamento dei documenti:
[Loading documents](../https://docs.groupdocs.com/display/watermarknet/Loading+documents).

Il seguente esempio dimostra come caricare un documento PDF crittografato usando una password.
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | documento | java.io.InputStream | Il flusso da cui caricare il documento. |
|
|  | options | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) | Opzioni aggiuntive da utilizzare durante il caricamento di un documento. |
|

### Watermarker(InputStream document, WatermarkerSettings settings) {#Watermarker-java.io.InputStream-com.groupdocs.watermark.WatermarkerSettings-}
```
public Watermarker(InputStream document, WatermarkerSettings settings)
```


Inizializza una nuova istanza della classe `[Watermarker](../../com.groupdocs.watermark/watermarker)` con lo stream specificato e le impostazioni.

Maggiori informazioni sul caricamento dei documenti:
[Loading documents](../https://docs.groupdocs.com/display/watermarknet/Loading+documents).

Il seguente esempio dimostra come impostare gli oggetti ricercabili globalmente (per tutti i documenti che
verranno caricati successivamente).
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | documento | java.io.InputStream | Il flusso da cui caricare il documento. |
|
|  | settings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) | Impostazioni aggiuntive da utilizzare quando si lavora con il documento caricato. |
|

### Watermarker(InputStream document, LoadOptions options, WatermarkerSettings settings) {#Watermarker-java.io.InputStream-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-}
```
public Watermarker(InputStream document, LoadOptions options, WatermarkerSettings settings)
```


Inizializza una nuova istanza della classe con lo stream specificato, le opzioni di caricamento e le impostazioni.

Maggiori informazioni sul caricamento dei documenti:
[Loading documents](../https://docs.groupdocs.com/display/watermarknet/Loading+documents).

Il seguente esempio dimostra come impostare gli oggetti ricercabili globalmente (per tutti i documenti che
verranno caricati successivamente).
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | documento | java.io.InputStream | Il flusso da cui caricare il documento. |
|
|  | options | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) | Opzioni aggiuntive da utilizzare durante il caricamento di un documento. |
|
|  | settings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) | Impostazioni aggiuntive da utilizzare quando si lavora con il documento caricato. |
|

### Watermarker(System.IO.Stream document, LoadOptions options, WatermarkerSettings settings) {#Watermarker-com.aspose.ms.System.IO.Stream-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-}
```
public Watermarker(System.IO.Stream document, LoadOptions options, WatermarkerSettings settings)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| documento | com.aspose.ms.System.IO.Stream |  |
| options | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) |  |
| settings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) |  |

### getSearchableObjects() {#getSearchableObjects--}
```
public final SearchableObjects getSearchableObjects()
```


Ottiene gli oggetti di contenuto da includere in una ricerca di filigrana.

Questo metodo specifica anche gli oggetti di contenuto che sono usati nella ricerca di immagini.
Per ulteriori informazioni vedere `#search(SearchCriteria).search(SearchCriteria)`
e i metodi `#getImages().getImages()`.

Scopri di più sulla ricerca di filigrane:
[Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks).

Il seguente esempio dimostra come rimuovere tutti gli XObject e gli Artifact da un documento PDF.
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


Imposta gli oggetti di contenuto da includere in una ricerca di filigrana.

Questo metodo specifica anche gli oggetti di contenuto che sono usati nella ricerca di immagini.
Per ulteriori informazioni vedere `#search(SearchCriteria).search(SearchCriteria)`
e i metodi `#getImages().getImages()`.
Scopri di più sulla ricerca di filigrane:
[Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks).

Il seguente esempio dimostra come rimuovere tutti gli XObject e gli Artifact da un documento PDF.
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | [SearchableObjects](../../com.groupdocs.watermark.search/searchableobjects) | Gli oggetti da includere in una ricerca di filigrane. |
|

### dispose() {#dispose--}
```
public final void dispose()
```




### close() {#close--}
```
public final void close()
```


Rilascia l'istanza corrente.


### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


Ottiene le informazioni sul formato del documento caricato.

Scopri di più su come ottenere le informazioni del documento
[Get document info](../https://docs.groupdocs.com/display/watermarkjava/Get+document+info).

Il seguente esempio dimostra come ottenere informazioni su un documento di qualsiasi tipo supportato.
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


Aggiunge una filigrana al documento caricato.

Scopri di più sull'aggiunta di filigrane:
[Adding watermarks](../https://docs.groupdocs.com/display/watermarkjava/Adding+watermarks).

Il seguente esempio dimostra come aggiungere una filigrana immagine e testo a un documento di qualsiasi tipo supportato.
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | watermark | [Watermark](../../com.groupdocs.watermark/watermark) | La filigrana da aggiungere al documento. |
|

### add(Watermark watermark, WatermarkOptions options) {#add-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.WatermarkOptions-}
```
public final void add(Watermark watermark, WatermarkOptions options)
```


Aggiunge una filigrana al documento caricato utilizzando le opzioni di filigrana.

Scopri di più sull'aggiunta di filigrane:
[Adding watermarks](../https://docs.groupdocs.com/display/watermarkjava/Adding+watermarks).

Il seguente esempio dimostra come aggiungere una filigrana immagine a una pagina specifica di un documento PDF.
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | watermark | [Watermark](../../com.groupdocs.watermark/watermark) | La filigrana da aggiungere al documento. |
|
|  | options | [WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions) | Opzioni aggiuntive da utilizzare quando si aggiunge la filigrana. |
|

### remove(PossibleWatermark possibleWatermark) {#remove-com.groupdocs.watermark.search.PossibleWatermark-}
```
public final void remove(PossibleWatermark possibleWatermark)
```


Rimuove la filigrana dal documento.

Scopri di più sulla rimozione di filigrane:
[Removing found watermarks](../https://docs.groupdocs.com/display/watermarkjava/Removing+found+watermarks).

Il seguente esempio dimostra come trovare e rimuovere la prima possibile filigrana contenente particolari
testo o immagine da un documento di qualsiasi tipo supportato.
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | possibleWatermark | [PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark) | La filigrana da rimuovere. |
|

### remove(PossibleWatermarkCollection possibleWatermarks) {#remove-com.groupdocs.watermark.search.PossibleWatermarkCollection-}
```
public final void remove(PossibleWatermarkCollection possibleWatermarks)
```


Rimuove tutte le filigrane nella collezione dal documento.

Scopri di più sulla rimozione di filigrane:
[Removing found watermarks](../https://docs.groupdocs.com/display/watermarkjava/Removing+found+watermarks).

Il seguente esempio dimostra come trovare e rimuovere tutte le possibili filigrane contenenti particolari
testo o immagine da un documento di qualsiasi tipo supportato.
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | possibleWatermarks | [PossibleWatermarkCollection](../../com.groupdocs.watermark.search/possiblewatermarkcollection) | La collezione di filigrane da rimuovere. |
|

### save(String filePath) {#save-java.lang.String-}
```
public final void save(String filePath)
```


Salva il documento nella posizione file specificata.

Scopri di più sul salvataggio dei documenti
[Saving documents](../https://docs.groupdocs.com/display/watermarkjava/Saving+documents).

Il seguente esempio dimostra come aggiungere la filigrana e salvare il documento in un altro file.
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | filePath | java.lang.String | Il percorso del file in cui salvare i dati del documento. |
|

### save(OutputStream document) {#save-java.io.OutputStream-}
```
public final void save(OutputStream document)
```


Salva il documento nello stream specificato.

Scopri di più sul salvataggio dei documenti
[Saving documents](../https://docs.groupdocs.com/display/watermarkjava/Saving+documents).

Il seguente esempio dimostra come aggiungere una filigrana e salvare il documento nello stream di memoria.
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | documento | java.io.OutputStream | Lo stream in cui salvare i dati del documento. |
|

### save(String filePath, SaveOptions options) {#save-java.lang.String-com.groupdocs.watermark.options.SaveOptions-}
```
public final void save(String filePath, SaveOptions options)
```


Salva il documento nella posizione file specificata usando le opzioni di salvataggio.

Scopri di più sul salvataggio dei documenti
[Saving documents](../https://docs.groupdocs.com/display/watermarkjava/Saving+documents).

Il seguente esempio dimostra come aggiungere la filigrana e salvare il documento in un altro file
con le impostazioni predefinite `[SaveOptions](../../com.groupdocs.watermark.options/saveoptions)`.
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | filePath | java.lang.String | Il percorso del file in cui salvare i dati del documento. |
|
|  | options | [SaveOptions](../../com.groupdocs.watermark.options/saveoptions) | Opzioni aggiuntive da utilizzare durante il salvataggio di un documento. |
|

### save(OutputStream document, SaveOptions options) {#save-java.io.OutputStream-com.groupdocs.watermark.options.SaveOptions-}
```
public final void save(OutputStream document, SaveOptions options)
```


Salva il documento nello stream specificato usando le opzioni di salvataggio.

Scopri di più sul salvataggio dei documenti
[Saving documents](../https://docs.groupdocs.com/display/watermarkjava/Saving+documents).

Il seguente esempio dimostra come aggiungere una filigrana e salvare il documento nello stream di memoria
con le impostazioni predefinite `[SaveOptions](../../com.groupdocs.watermark.options/saveoptions)`.
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | documento | java.io.OutputStream | Lo stream in cui salvare i dati del documento. |
|
|  | options | [SaveOptions](../../com.groupdocs.watermark.options/saveoptions) | Opzioni aggiuntive da utilizzare durante il salvataggio di un documento. |
|

### generatePreview(PreviewOptions previewOptions) {#generatePreview-com.groupdocs.watermark.options.PreviewOptions-}
```
public final void generatePreview(PreviewOptions previewOptions)
```


Genera immagini di anteprima per il documento.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | previewOptions | [PreviewOptions](../../com.groupdocs.watermark.options/previewoptions) | Opzioni aggiuntive da utilizzare durante la generazione di immagini di anteprima. |
|

### search() {#search--}
```
public final PossibleWatermarkCollection search()
```


Cerca tutte le possibili filigrane nel documento.

La ricerca viene eseguita negli oggetti specificati con `#setSearchableObjects(SearchableObjects).setSearchableObjects(SearchableObjects)`.

Scopri di più sulla ricerca delle filigrane
[Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks).

Il seguente esempio dimostra come contare le filigrane possibili in un documento di qualsiasi tipo supportato.
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


Cerca le filigrane possibili secondo i criteri di ricerca specificati.

La ricerca viene eseguita negli oggetti specificati con `#setSearchableObjects(SearchableObjects).setSearchableObjects(SearchableObjects)`.

Scopri di più sulla ricerca delle filigrane
[Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks).

Il seguente esempio dimostra come trovare e rimuovere tutte le filigrane possibili contenenti un testo specifico
o immagine da un documento di qualsiasi tipo supportato.
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | searchCriteria | [SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) | I criteri di ricerca da utilizzare. |
|

**Returns:**
[PossibleWatermarkCollection](../../com.groupdocs.watermark.search/possiblewatermarkcollection)
### getImages(ImageSearchCriteria searchCriteria) {#getImages-com.groupdocs.watermark.search.ImageSearchCriteria-}
```
public final WatermarkableImageCollection getImages(ImageSearchCriteria searchCriteria)
```


Trova le immagini secondo i criteri di ricerca specificati.

La ricerca viene eseguita negli oggetti specificati con `#setSearchableObjects(SearchableObjects).setSearchableObjects(SearchableObjects)`.

Scopri di più sulla ricerca delle filigrane
[Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks).

Il seguente esempio dimostra come rimuovere tutte le immagini simili al riferimento
da un documento di qualsiasi tipo supportato.
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | searchCriteria | [ImageSearchCriteria](../../com.groupdocs.watermark.search/imagesearchcriteria) | I criteri di ricerca da utilizzare. |
|

**Returns:**
[WatermarkableImageCollection](../../com.groupdocs.watermark.contents/watermarkableimagecollection)
### getImages() {#getImages--}
```
public final WatermarkableImageCollection getImages()
```


Trova tutte le immagini nel documento.

La ricerca viene eseguita negli oggetti specificati con `#setSearchableObjects(SearchableObjects).setSearchableObjects(SearchableObjects)`.

Scopri di più sulla ricerca delle filigrane
[Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks).

Il seguente esempio dimostra come aggiungere una filigrana a tutte le immagini in un documento di qualsiasi tipo supportato.
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


Restituisce il `[Content](../../com.groupdocs.watermark.contents/content)` oggetto per il documento caricato.

Il seguente esempio dimostra come rasterizzare la pagina di un documento PDF con una filigrana aggiunta.
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | contentType | java.lang.Class<T> | Il tipo richiesto di un oggetto `[Content](../../com.groupdocs.watermark.contents/content)`. |
|

**Returns:**
T - L'oggetto `[Content](../../com.groupdocs.watermark.contents/content)` per il documento caricato.

