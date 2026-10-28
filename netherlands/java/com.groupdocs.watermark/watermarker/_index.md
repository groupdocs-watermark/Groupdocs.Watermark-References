---
title: "Watermarker"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: "Stelt een klasse voor voor watermerkbeheer in een document."
type: docs
weight: 14
url: /nl/java/com.groupdocs.watermark/watermarker/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class Watermarker implements Closeable
```

Stelt een klasse voor voor watermerkbeheer in een document.

Het volgende voorbeeld toont hoe je de inhoud van elk ondersteund formaat kunt laden en opslaan.
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


## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [Watermarker(String filePath)](#Watermarker-java.lang.String-) | Initialiseert een nieuw exemplaar van de `[Watermarker](../../com.groupdocs.watermark/watermarker)` klasse met het opgegeven documentpad. |
|
|  | [Watermarker(String filePath, LoadOptions options)](#Watermarker-java.lang.String-com.groupdocs.watermark.options.LoadOptions-) | Initialiseert een nieuw exemplaar van de `[Watermarker](../../com.groupdocs.watermark/watermarker)` klasse met het opgegeven documentpad en laadopties. |
|
|  | [Watermarker(String filePath, WatermarkerSettings settings)](#Watermarker-java.lang.String-com.groupdocs.watermark.WatermarkerSettings-) | Initialiseert een nieuw exemplaar van de `[Watermarker](../../com.groupdocs.watermark/watermarker)` klasse met het opgegeven documentpad en instellingen. |
|
|  | [Watermarker(String filePath, LoadOptions options, WatermarkerSettings settings)](#Watermarker-java.lang.String-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-) | Initialiseert een nieuw exemplaar van de `[Watermarker](../../com.groupdocs.watermark/watermarker)` klasse met het opgegeven documentpad, laadopties en instellingen. |
|
|  | [Watermarker(InputStream document)](#Watermarker-java.io.InputStream-) | Initialiseert een nieuw exemplaar van de `[Watermarker](../../com.groupdocs.watermark/watermarker)` klasse met de opgegeven stream. |
|
|  | [Watermarker(InputStream document, LoadOptions options)](#Watermarker-java.io.InputStream-com.groupdocs.watermark.options.LoadOptions-) | Initialiseert een nieuw exemplaar van de `[Watermarker](../../com.groupdocs.watermark/watermarker)` klasse met de opgegeven stream en laadopties. |
|
|  | [Watermarker(InputStream document, WatermarkerSettings settings)](#Watermarker-java.io.InputStream-com.groupdocs.watermark.WatermarkerSettings-) | Initialiseert een nieuw exemplaar van de `[Watermarker](../../com.groupdocs.watermark/watermarker)` klasse met de opgegeven stream en instellingen. |
|
|  | [Watermarker(InputStream document, LoadOptions options, WatermarkerSettings settings)](#Watermarker-java.io.InputStream-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-) | Initialiseert een nieuw exemplaar van de klasse met de opgegeven stream, laadopties en instellingen. |
|
| [Watermarker(System.IO.Stream document, LoadOptions options, WatermarkerSettings settings)](#Watermarker-com.aspose.ms.System.IO.Stream-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getSearchableObjects()](#getSearchableObjects--) | Haalt de inhoudsobjecten op die moeten worden opgenomen in een watermerkzoekopdracht. |
|
|  | [setSearchableObjects(SearchableObjects value)](#setSearchableObjects-com.groupdocs.watermark.search.SearchableObjects-) | Stelt de inhoudsobjecten in die moeten worden opgenomen in een watermerkzoekopdracht. |
|
| [dispose()](#dispose--) |  |
|  | [close()](#close--) | Verwijdert de huidige instantie. |
|
|  | [getDocumentInfo()](#getDocumentInfo--) | Haalt de informatie op over het formaat van het geladen document. |
|
|  | [add(Watermark watermark)](#add-com.groupdocs.watermark.Watermark-) | Voegt een watermerk toe aan het geladen document. |
|
|  | [add(Watermark watermark, WatermarkOptions options)](#add-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.WatermarkOptions-) | Voegt een watermerk toe aan het geladen document met behulp van watermerkopties. |
|
|  | [remove(PossibleWatermark possibleWatermark)](#remove-com.groupdocs.watermark.search.PossibleWatermark-) | Verwijdert het watermerk uit het document. |
|
|  | [remove(PossibleWatermarkCollection possibleWatermarks)](#remove-com.groupdocs.watermark.search.PossibleWatermarkCollection-) | Verwijdert alle watermerken in de collectie uit het document. |
|
|  | [save(String filePath)](#save-java.lang.String-) | Slaat het document op op de opgegeven bestandslocatie. |
|
|  | [save(OutputStream document)](#save-java.io.OutputStream-) | Slaat het document op in de opgegeven stream. |
|
|  | [save(String filePath, SaveOptions options)](#save-java.lang.String-com.groupdocs.watermark.options.SaveOptions-) | Slaat het document op op de opgegeven bestandslocatie met behulp van opslagopties. |
|
|  | [save(OutputStream document, SaveOptions options)](#save-java.io.OutputStream-com.groupdocs.watermark.options.SaveOptions-) | Slaat het document op in de opgegeven stream met behulp van opslagopties. |
|
|  | [generatePreview(PreviewOptions previewOptions)](#generatePreview-com.groupdocs.watermark.options.PreviewOptions-) | Genereert voorbeeldafbeeldingen voor het document. |
|
|  | [search()](#search--) | Zoekt alle mogelijke watermerken in het document. |
|
|  | [search(SearchCriteria searchCriteria)](#search-com.groupdocs.watermark.search.SearchCriteria-) | Zoekt mogelijke watermerken volgens de opgegeven zoekcriteria. |
|
|  | [getImages(ImageSearchCriteria searchCriteria)](#getImages-com.groupdocs.watermark.search.ImageSearchCriteria-) | Vindt afbeeldingen volgens de opgegeven zoekcriteria. |
|
|  | [getImages()](#getImages--) | Vindt alle afbeeldingen in het document. |
|
|  | [<T>getContent(Class<T> contentType)](#-T-getContent-java.lang.Class-T--) | Retourneert het `[Content](../../com.groupdocs.watermark.contents/content)` object voor het geladen document. |
|
### Watermarker(String filePath) {#Watermarker-java.lang.String-}
```
public Watermarker(String filePath)
```


Initialiseert een nieuw exemplaar van de `[Watermarker](../../com.groupdocs.watermark/watermarker)` klasse met het opgegeven documentpad.

Meer informatie over het laden van documenten:
[Loading documents](../https://docs.groupdocs.com/display/watermarkjava/Loading+documents).

Het volgende voorbeeld toont hoe je de inhoud van elk ondersteund formaat kunt laden en opslaan.
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePath | java.lang.String | Het bestandspad om het document van te laden. |
|

### Watermarker(String filePath, LoadOptions options) {#Watermarker-java.lang.String-com.groupdocs.watermark.options.LoadOptions-}
```
public Watermarker(String filePath, LoadOptions options)
```


Initialiseert een nieuw exemplaar van de `[Watermarker](../../com.groupdocs.watermark/watermarker)` klasse met het opgegeven documentpad en laadopties.

Meer informatie over het laden van documenten:
[Loading documents](../https://docs.groupdocs.com/display/watermarkjava/Loading+documents).

Het volgende voorbeeld toont hoe een versleuteld PDF-document te laden met een wachtwoord.
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePath | java.lang.String | Het bestandspad om het document van te laden. |
|
|  | options | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) | Aanvullende opties om te gebruiken bij het laden van een document. |
|

### Watermarker(String filePath, WatermarkerSettings settings) {#Watermarker-java.lang.String-com.groupdocs.watermark.WatermarkerSettings-}
```
public Watermarker(String filePath, WatermarkerSettings settings)
```


Initialiseert een nieuw exemplaar van de `[Watermarker](../../com.groupdocs.watermark/watermarker)` klasse met het opgegeven documentpad en instellingen.

Meer informatie over het laden van documenten:
[Loading documents](../https://docs.groupdocs.com/display/watermarkjava/Loading+documents).

Het volgende voorbeeld toont hoe doorzoekbare objecten globaal in te stellen (voor alle documenten die
later worden geladen).
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePath | java.lang.String | Het bestandspad om het document van te laden. |
|
|  | settings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) | Aanvullende instellingen om te gebruiken bij het werken met een geladen document. |
|

### Watermarker(String filePath, LoadOptions options, WatermarkerSettings settings) {#Watermarker-java.lang.String-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-}
```
public Watermarker(String filePath, LoadOptions options, WatermarkerSettings settings)
```


Initialiseert een nieuw exemplaar van de `[Watermarker](../../com.groupdocs.watermark/watermarker)` klasse met het opgegeven documentpad, laadopties en instellingen.

Meer informatie over het laden van documenten:
[Loading documents](../https://docs.groupdocs.com/display/watermarknet/Loading+documents).

Het volgende voorbeeld toont hoe specifieke tekstfragmenten te vinden in de hoofdtekst/onderwerp van een e‑mailbericht.
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePath | java.lang.String | Het bestandspad om het document van te laden. |
|
|  | options | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) | Aanvullende opties om te gebruiken bij het laden van een document. |
|
|  | settings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) | Aanvullende instellingen om te gebruiken bij het werken met een geladen document. |
|

### Watermarker(InputStream document) {#Watermarker-java.io.InputStream-}
```
public Watermarker(InputStream document)
```


Initialiseert een nieuw exemplaar van de `[Watermarker](../../com.groupdocs.watermark/watermarker)` klasse met de opgegeven stream.

Meer informatie over het laden van documenten:
[Loading documents](../https://docs.groupdocs.com/display/watermarknet/Loading+documents).

Het volgende voorbeeld toont hoe een document in elk ondersteund formaat te laden en op te slaan.
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | document | java.io.InputStream | De stream om het document van te laden. |
|

### Watermarker(InputStream document, LoadOptions options) {#Watermarker-java.io.InputStream-com.groupdocs.watermark.options.LoadOptions-}
```
public Watermarker(InputStream document, LoadOptions options)
```


Initialiseert een nieuw exemplaar van de `[Watermarker](../../com.groupdocs.watermark/watermarker)` klasse met de opgegeven stream en laadopties.

Meer informatie over het laden van documenten:
[Loading documents](../https://docs.groupdocs.com/display/watermarknet/Loading+documents).

Het volgende voorbeeld laat zien hoe een versleuteld PDF-document te laden met een wachtwoord.
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | document | java.io.InputStream | De stream om het document van te laden. |
|
|  | options | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) | Aanvullende opties om te gebruiken bij het laden van een document. |
|

### Watermarker(InputStream document, WatermarkerSettings settings) {#Watermarker-java.io.InputStream-com.groupdocs.watermark.WatermarkerSettings-}
```
public Watermarker(InputStream document, WatermarkerSettings settings)
```


Initialiseert een nieuw exemplaar van de `[Watermarker](../../com.groupdocs.watermark/watermarker)` klasse met de opgegeven stream en instellingen.

Meer informatie over het laden van documenten:
[Loading documents](../https://docs.groupdocs.com/display/watermarknet/Loading+documents).

Het volgende voorbeeld toont hoe doorzoekbare objecten globaal in te stellen (voor alle documenten die
later worden geladen).
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | document | java.io.InputStream | De stream om het document van te laden. |
|
|  | settings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) | Aanvullende instellingen om te gebruiken bij het werken met een geladen document. |
|

### Watermarker(InputStream document, LoadOptions options, WatermarkerSettings settings) {#Watermarker-java.io.InputStream-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-}
```
public Watermarker(InputStream document, LoadOptions options, WatermarkerSettings settings)
```


Initialiseert een nieuw exemplaar van de klasse met de opgegeven stream, laadopties en instellingen.

Meer informatie over het laden van documenten:
[Loading documents](../https://docs.groupdocs.com/display/watermarknet/Loading+documents).

Het volgende voorbeeld toont hoe doorzoekbare objecten globaal in te stellen (voor alle documenten die
later worden geladen).
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | document | java.io.InputStream | De stream om het document van te laden. |
|
|  | options | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) | Aanvullende opties om te gebruiken bij het laden van een document. |
|
|  | settings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) | Aanvullende instellingen om te gebruiken bij het werken met een geladen document. |
|

### Watermarker(System.IO.Stream document, LoadOptions options, WatermarkerSettings settings) {#Watermarker-com.aspose.ms.System.IO.Stream-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-}
```
public Watermarker(System.IO.Stream document, LoadOptions options, WatermarkerSettings settings)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| document | com.aspose.ms.System.IO.Stream |  |
| options | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) |  |
| settings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) |  |

### getSearchableObjects() {#getSearchableObjects--}
```
public final SearchableObjects getSearchableObjects()
```


Haalt de inhoudsobjecten op die moeten worden opgenomen in een watermerkzoekopdracht.

Deze methode specificeert ook contentobjecten die worden gebruikt bij het zoeken naar afbeeldingen.
Voor meer informatie zie `#search(SearchCriteria).search(SearchCriteria)`
en `#getImages().getImages()` methoden.

Meer informatie over het zoeken naar watermerken:
[Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks).

Het volgende voorbeeld laat zien hoe alle XObjects en artefacten uit een pdf-document te verwijderen.
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


Stelt de inhoudsobjecten in die moeten worden opgenomen in een watermerkzoekopdracht.

Deze methode specificeert ook contentobjecten die worden gebruikt bij het zoeken naar afbeeldingen.
Voor meer informatie zie `#search(SearchCriteria).search(SearchCriteria)`
en `#getImages().getImages()` methoden.
Meer informatie over het zoeken naar watermerken:
[Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks).

Het volgende voorbeeld laat zien hoe alle XObjects en artefacten uit een pdf-document te verwijderen.
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | [SearchableObjects](../../com.groupdocs.watermark.search/searchableobjects) | De objecten die moeten worden opgenomen in een watermerkzoekopdracht. |
|

### dispose() {#dispose--}
```
public final void dispose()
```




### close() {#close--}
```
public final void close()
```


Verwijdert de huidige instantie.


### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


Haalt de informatie op over het formaat van het geladen document.

Meer informatie over het verkrijgen van documentinformatie
[Get document info](../https://docs.groupdocs.com/display/watermarkjava/Get+document+info).

Het volgende voorbeeld laat zien hoe informatie over een document van elk ondersteund type op te halen.
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


Voegt een watermerk toe aan het geladen document.

Meer informatie over het toevoegen van watermerken:
[Adding watermarks](../https://docs.groupdocs.com/display/watermarkjava/Adding+watermarks).

Het volgende voorbeeld laat zien hoe een afbeelding- en tekstwatermerk aan een document van elk ondersteund type toe te voegen.
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | watermark | [Watermark](../../com.groupdocs.watermark/watermark) | Het watermerk om aan het document toe te voegen. |
|

### add(Watermark watermark, WatermarkOptions options) {#add-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.WatermarkOptions-}
```
public final void add(Watermark watermark, WatermarkOptions options)
```


Voegt een watermerk toe aan het geladen document met behulp van watermerkopties.

Meer informatie over het toevoegen van watermerken:
[Adding watermarks](../https://docs.groupdocs.com/display/watermarkjava/Adding+watermarks).

Het volgende voorbeeld laat zien hoe een afbeeldingwatermerk toe te voegen aan een specifieke pagina van een pdf-document.
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | watermark | [Watermark](../../com.groupdocs.watermark/watermark) | Het watermerk om aan het document toe te voegen. |
|
|  | options | [WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions) | Aanvullende opties om te gebruiken bij het toevoegen van het watermerk. |
|

### remove(PossibleWatermark possibleWatermark) {#remove-com.groupdocs.watermark.search.PossibleWatermark-}
```
public final void remove(PossibleWatermark possibleWatermark)
```


Verwijdert het watermerk uit het document.

Meer informatie over het verwijderen van watermerken:
[Removing found watermarks](../https://docs.groupdocs.com/display/watermarkjava/Removing+found+watermarks).

Het volgende voorbeeld laat zien hoe het eerste mogelijke watermerk dat een bepaald
tekst of afbeelding uit een document van elk ondersteund type.
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | possibleWatermark | [PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark) | Het watermerk om te verwijderen. |
|

### remove(PossibleWatermarkCollection possibleWatermarks) {#remove-com.groupdocs.watermark.search.PossibleWatermarkCollection-}
```
public final void remove(PossibleWatermarkCollection possibleWatermarks)
```


Verwijdert alle watermerken in de collectie uit het document.

Meer informatie over het verwijderen van watermerken:
[Removing found watermarks](../https://docs.groupdocs.com/display/watermarkjava/Removing+found+watermarks).

Het volgende voorbeeld laat zien hoe alle mogelijke watermerken die een bepaald
tekst of afbeelding uit een document van elk ondersteund type.
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | possibleWatermarks | [PossibleWatermarkCollection](../../com.groupdocs.watermark.search/possiblewatermarkcollection) | De verzameling watermerken om te verwijderen. |
|

### save(String filePath) {#save-java.lang.String-}
```
public final void save(String filePath)
```


Slaat het document op op de opgegeven bestandslocatie.

Meer informatie over het opslaan van de documenten
[Saving documents](../https://docs.groupdocs.com/display/watermarkjava/Saving+documents).

Het volgende voorbeeld laat zien hoe het watermerk toe te voegen en het document op te slaan in een ander bestand.
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePath | java.lang.String | Het bestandspad om de documentgegevens op te slaan. |
|

### save(OutputStream document) {#save-java.io.OutputStream-}
```
public final void save(OutputStream document)
```


Slaat het document op in de opgegeven stream.

Meer informatie over het opslaan van de documenten
[Saving documents](../https://docs.groupdocs.com/display/watermarkjava/Saving+documents).

Het volgende voorbeeld toont hoe een watermerk toe te voegen en het document op te slaan in de memory stream.
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | document | java.io.OutputStream | De stream om de documentgegevens op te slaan. |
|

### save(String filePath, SaveOptions options) {#save-java.lang.String-com.groupdocs.watermark.options.SaveOptions-}
```
public final void save(String filePath, SaveOptions options)
```


Slaat het document op op de opgegeven bestandslocatie met behulp van opslagopties.

Meer informatie over het opslaan van de documenten
[Saving documents](../https://docs.groupdocs.com/display/watermarkjava/Saving+documents).

Het volgende voorbeeld toont hoe het watermerk toe te voegen en het document op te slaan in een ander bestand
met standaard `[SaveOptions](../../com.groupdocs.watermark.options/saveoptions)`.
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePath | java.lang.String | Het bestandspad om de documentgegevens op te slaan. |
|
|  | options | [SaveOptions](../../com.groupdocs.watermark.options/saveoptions) | Aanvullende opties om te gebruiken bij het opslaan van een document. |
|

### save(OutputStream document, SaveOptions options) {#save-java.io.OutputStream-com.groupdocs.watermark.options.SaveOptions-}
```
public final void save(OutputStream document, SaveOptions options)
```


Slaat het document op in de opgegeven stream met behulp van opslagopties.

Meer informatie over het opslaan van de documenten
[Saving documents](../https://docs.groupdocs.com/display/watermarkjava/Saving+documents).

Het volgende voorbeeld toont hoe een watermerk toe te voegen en het document op te slaan in de memory stream
met standaard `[SaveOptions](../../com.groupdocs.watermark.options/saveoptions)`.
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | document | java.io.OutputStream | De stream om de documentgegevens op te slaan. |
|
|  | options | [SaveOptions](../../com.groupdocs.watermark.options/saveoptions) | Aanvullende opties om te gebruiken bij het opslaan van een document. |
|

### generatePreview(PreviewOptions previewOptions) {#generatePreview-com.groupdocs.watermark.options.PreviewOptions-}
```
public final void generatePreview(PreviewOptions previewOptions)
```


Genereert voorbeeldafbeeldingen voor het document.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | previewOptions | [PreviewOptions](../../com.groupdocs.watermark.options/previewoptions) | Aanvullende opties om te gebruiken bij het genereren van voorbeeldafbeeldingen. |
|

### search() {#search--}
```
public final PossibleWatermarkCollection search()
```


Zoekt alle mogelijke watermerken in het document.

De zoekopdracht wordt uitgevoerd in objecten gespecificeerd met `#setSearchableObjects(SearchableObjects).setSearchableObjects(SearchableObjects)`.

Meer informatie over het zoeken naar watermerken
[Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks).

Het volgende voorbeeld toont hoe het aantal mogelijke watermerken in een document van elk ondersteund type te tellen.
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


Zoekt mogelijke watermerken volgens de opgegeven zoekcriteria.

De zoekopdracht wordt uitgevoerd in objecten gespecificeerd met `#setSearchableObjects(SearchableObjects).setSearchableObjects(SearchableObjects)`.

Meer informatie over het zoeken naar watermerken
[Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks).

Het volgende voorbeeld toont hoe alle mogelijke watermerken die specifieke tekst bevatten te vinden en te verwijderen
of afbeelding uit een document van elk ondersteund type.
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | searchCriteria | [SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) | De te gebruiken zoekcriteria. |
|

**Returns:**
[PossibleWatermarkCollection](../../com.groupdocs.watermark.search/possiblewatermarkcollection)
### getImages(ImageSearchCriteria searchCriteria) {#getImages-com.groupdocs.watermark.search.ImageSearchCriteria-}
```
public final WatermarkableImageCollection getImages(ImageSearchCriteria searchCriteria)
```


Vindt afbeeldingen volgens de opgegeven zoekcriteria.

De zoekopdracht wordt uitgevoerd in objecten gespecificeerd met `#setSearchableObjects(SearchableObjects).setSearchableObjects(SearchableObjects)`.

Meer informatie over het zoeken naar watermerken
[Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks).

Het volgende voorbeeld toont hoe alle afbeeldingen die vergelijkbaar zijn met de referentie te verwijderen
uit een document van elk ondersteund type.
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | searchCriteria | [ImageSearchCriteria](../../com.groupdocs.watermark.search/imagesearchcriteria) | De te gebruiken zoekcriteria. |
|

**Returns:**
[WatermarkableImageCollection](../../com.groupdocs.watermark.contents/watermarkableimagecollection)
### getImages() {#getImages--}
```
public final WatermarkableImageCollection getImages()
```


Vindt alle afbeeldingen in het document.

De zoekopdracht wordt uitgevoerd in objecten gespecificeerd met `#setSearchableObjects(SearchableObjects).setSearchableObjects(SearchableObjects)`.

Meer informatie over het zoeken naar watermerken
[Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks).

Het volgende voorbeeld toont hoe een watermerk toe te voegen aan alle afbeeldingen in een document van elk ondersteund type.
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


Retourneert het `[Content](../../com.groupdocs.watermark.contents/content)` object voor het geladen document.

Het volgende voorbeeld toont hoe een pdf-documentpagina te rasteren met een toegevoegd watermerk.
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | contentType | java.lang.Class<T> | Het aangevraagde type van een `[Content](../../com.groupdocs.watermark.contents/content)` object. |
|

**Returns:**
T - Het `[Content](../../com.groupdocs.watermark.contents/content)` object voor het geladen document.

