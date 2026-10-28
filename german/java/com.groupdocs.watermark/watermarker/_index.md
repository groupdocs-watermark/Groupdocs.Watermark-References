---
title: "Watermarker"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt eine Klasse für die Wasserzeichenverwaltung in einem Dokument dar."
type: docs
weight: 14
url: /de/java/com.groupdocs.watermark/watermarker/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class Watermarker implements Closeable
```

Stellt eine Klasse für die Wasserzeichenverwaltung in einem Dokument dar.

Das folgende Beispiel zeigt, wie man den Inhalt eines beliebigen unterstützten Formats lädt und speichert.
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


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [Watermarker(String filePath)](#Watermarker-java.lang.String-) | Initialisiert eine neue Instanz der `[Watermarker](../../com.groupdocs.watermark/watermarker)` Klasse mit dem angegebenen Dokumentpfad. |
|
|  | [Watermarker(String filePath, LoadOptions options)](#Watermarker-java.lang.String-com.groupdocs.watermark.options.LoadOptions-) | Initialisiert eine neue Instanz der `[Watermarker](../../com.groupdocs.watermark/watermarker)` Klasse mit dem angegebenen Dokumentpfad und Ladeoptionen. |
|
|  | [Watermarker(String filePath, WatermarkerSettings settings)](#Watermarker-java.lang.String-com.groupdocs.watermark.WatermarkerSettings-) | Initialisiert eine neue Instanz der `[Watermarker](../../com.groupdocs.watermark/watermarker)` Klasse mit dem angegebenen Dokumentpfad und Einstellungen. |
|
|  | [Watermarker(String filePath, LoadOptions options, WatermarkerSettings settings)](#Watermarker-java.lang.String-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-) | Initialisiert eine neue Instanz der `[Watermarker](../../com.groupdocs.watermark/watermarker)` Klasse mit dem angegebenen Dokumentpfad, Ladeoptionen und Einstellungen. |
|
|  | [Watermarker(InputStream document)](#Watermarker-java.io.InputStream-) | Initialisiert eine neue Instanz der `[Watermarker](../../com.groupdocs.watermark/watermarker)` Klasse mit dem angegebenen Stream. |
|
|  | [Watermarker(InputStream document, LoadOptions options)](#Watermarker-java.io.InputStream-com.groupdocs.watermark.options.LoadOptions-) | Initialisiert eine neue Instanz der `[Watermarker](../../com.groupdocs.watermark/watermarker)` Klasse mit dem angegebenen Stream und Ladeoptionen. |
|
|  | [Watermarker(InputStream document, WatermarkerSettings settings)](#Watermarker-java.io.InputStream-com.groupdocs.watermark.WatermarkerSettings-) | Initialisiert eine neue Instanz der `[Watermarker](../../com.groupdocs.watermark/watermarker)` Klasse mit dem angegebenen Stream und Einstellungen. |
|
|  | [Watermarker(InputStream document, LoadOptions options, WatermarkerSettings settings)](#Watermarker-java.io.InputStream-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-) | Initialisiert eine neue Instanz der Klasse mit dem angegebenen Stream, Ladeoptionen und Einstellungen. |
|
| [Watermarker(System.IO.Stream document, LoadOptions options, WatermarkerSettings settings)](#Watermarker-com.aspose.ms.System.IO.Stream-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getSearchableObjects()](#getSearchableObjects--) | Ruft die Inhaltsobjekte ab, die in einer Wasserzeichen‑Suche enthalten sein sollen. |
|
|  | [setSearchableObjects(SearchableObjects value)](#setSearchableObjects-com.groupdocs.watermark.search.SearchableObjects-) | Setzt die Inhaltsobjekte, die in einer Wasserzeichen‑Suche enthalten sein sollen. |
|
| [dispose()](#dispose--) |  |
|  | [close()](#close--) | Gibt die aktuelle Instanz frei. |
|
|  | [getDocumentInfo()](#getDocumentInfo--) | Ruft die Informationen über das Format des geladenen Dokuments ab. |
|
|  | [add(Watermark watermark)](#add-com.groupdocs.watermark.Watermark-) | Fügt dem geladenen Dokument ein Wasserzeichen hinzu. |
|
|  | [add(Watermark watermark, WatermarkOptions options)](#add-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.WatermarkOptions-) | Fügt dem geladenen Dokument ein Wasserzeichen mithilfe von Wasserzeichen‑Optionen hinzu. |
|
|  | [remove(PossibleWatermark possibleWatermark)](#remove-com.groupdocs.watermark.search.PossibleWatermark-) | Entfernt das Wasserzeichen aus dem Dokument. |
|
|  | [remove(PossibleWatermarkCollection possibleWatermarks)](#remove-com.groupdocs.watermark.search.PossibleWatermarkCollection-) | Entfernt alle Wasserzeichen aus der Sammlung aus dem Dokument. |
|
|  | [save(String filePath)](#save-java.lang.String-) | Speichert das Dokument am angegebenen Speicherort. |
|
|  | [save(OutputStream document)](#save-java.io.OutputStream-) | Speichert das Dokument im angegebenen Stream. |
|
|  | [save(String filePath, SaveOptions options)](#save-java.lang.String-com.groupdocs.watermark.options.SaveOptions-) | Speichert das Dokument am angegebenen Speicherort unter Verwendung von Speicheroptionen. |
|
|  | [save(OutputStream document, SaveOptions options)](#save-java.io.OutputStream-com.groupdocs.watermark.options.SaveOptions-) | Speichert das Dokument im angegebenen Stream unter Verwendung von Speicheroptionen. |
|
|  | [generatePreview(PreviewOptions previewOptions)](#generatePreview-com.groupdocs.watermark.options.PreviewOptions-) | Erstellt Vorschaubilder für das Dokument. |
|
|  | [search()](#search--) | Durchsucht alle möglichen Wasserzeichen im Dokument. |
|
|  | [search(SearchCriteria searchCriteria)](#search-com.groupdocs.watermark.search.SearchCriteria-) | Durchsucht mögliche Wasserzeichen gemäß den angegebenen Suchkriterien. |
|
|  | [getImages(ImageSearchCriteria searchCriteria)](#getImages-com.groupdocs.watermark.search.ImageSearchCriteria-) | Findet Bilder gemäß den angegebenen Suchkriterien. |
|
|  | [getImages()](#getImages--) | Findet alle Bilder im Dokument. |
|
|  | [<T>getContent(Class<T> contentType)](#-T-getContent-java.lang.Class-T--) | Gibt das `[Content](../../com.groupdocs.watermark.contents/content)`-Objekt für das geladene Dokument zurück. |
|
### Watermarker(String filePath) {#Watermarker-java.lang.String-}
```
public Watermarker(String filePath)
```


Initialisiert eine neue Instanz der `[Watermarker](../../com.groupdocs.watermark/watermarker)` Klasse mit dem angegebenen Dokumentpfad.

Erfahren Sie mehr über das Laden von Dokumenten:
[Loading documents](../https://docs.groupdocs.com/display/watermarkjava/Loading+documents).

Das folgende Beispiel zeigt, wie man den Inhalt eines beliebigen unterstützten Formats lädt und speichert.
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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | filePath | java.lang.String | Der Dateipfad, von dem das Dokument geladen wird. |
|

### Watermarker(String filePath, LoadOptions options) {#Watermarker-java.lang.String-com.groupdocs.watermark.options.LoadOptions-}
```
public Watermarker(String filePath, LoadOptions options)
```


Initialisiert eine neue Instanz der `[Watermarker](../../com.groupdocs.watermark/watermarker)` Klasse mit dem angegebenen Dokumentpfad und Ladeoptionen.

Erfahren Sie mehr über das Laden von Dokumenten:
[Loading documents](../https://docs.groupdocs.com/display/watermarkjava/Loading+documents).

Das folgende Beispiel zeigt, wie ein verschlüsseltes PDF-Dokument mit einem Passwort geladen wird.
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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | filePath | java.lang.String | Der Dateipfad, von dem das Dokument geladen wird. |
|
|  | options | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) | Zusätzliche Optionen, die beim Laden eines Dokuments verwendet werden. |
|

### Watermarker(String filePath, WatermarkerSettings settings) {#Watermarker-java.lang.String-com.groupdocs.watermark.WatermarkerSettings-}
```
public Watermarker(String filePath, WatermarkerSettings settings)
```


Initialisiert eine neue Instanz der `[Watermarker](../../com.groupdocs.watermark/watermarker)` Klasse mit dem angegebenen Dokumentpfad und Einstellungen.

Erfahren Sie mehr über das Laden von Dokumenten:
[Loading documents](../https://docs.groupdocs.com/display/watermarkjava/Loading+documents).

Das folgende Beispiel zeigt, wie durchsuchbare Objekte global festgelegt werden (für alle Dokumente, die
nachdem sie geladen werden).
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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | filePath | java.lang.String | Der Dateipfad, von dem das Dokument geladen wird. |
|
|  | settings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) | Zusätzliche Einstellungen, die bei der Arbeit mit dem geladenen Dokument verwendet werden. |
|

### Watermarker(String filePath, LoadOptions options, WatermarkerSettings settings) {#Watermarker-java.lang.String-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-}
```
public Watermarker(String filePath, LoadOptions options, WatermarkerSettings settings)
```


Initialisiert eine neue Instanz der `[Watermarker](../../com.groupdocs.watermark/watermarker)` Klasse mit dem angegebenen Dokumentpfad, Ladeoptionen und Einstellungen.

Erfahren Sie mehr über das Laden von Dokumenten:
[Loading documents](../https://docs.groupdocs.com/display/watermarknet/Loading+documents).

Das folgende Beispiel zeigt, wie bestimmte Textfragmente im E-Mail-Nachrichtentext/-Betreff gefunden werden.
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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | filePath | java.lang.String | Der Dateipfad, von dem das Dokument geladen wird. |
|
|  | options | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) | Zusätzliche Optionen, die beim Laden eines Dokuments verwendet werden. |
|
|  | settings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) | Zusätzliche Einstellungen, die bei der Arbeit mit dem geladenen Dokument verwendet werden. |
|

### Watermarker(InputStream document) {#Watermarker-java.io.InputStream-}
```
public Watermarker(InputStream document)
```


Initialisiert eine neue Instanz der `[Watermarker](../../com.groupdocs.watermark/watermarker)` Klasse mit dem angegebenen Stream.

Erfahren Sie mehr über das Laden von Dokumenten:
[Loading documents](../https://docs.groupdocs.com/display/watermarknet/Loading+documents).

Das folgende Beispiel zeigt, wie ein Dokument in einem beliebigen unterstützten Format geladen und gespeichert wird.
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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Dokument | java.io.InputStream | Der Stream, aus dem das Dokument geladen wird. |
|

### Watermarker(InputStream document, LoadOptions options) {#Watermarker-java.io.InputStream-com.groupdocs.watermark.options.LoadOptions-}
```
public Watermarker(InputStream document, LoadOptions options)
```


Initialisiert eine neue Instanz der `[Watermarker](../../com.groupdocs.watermark/watermarker)` Klasse mit dem angegebenen Stream und Ladeoptionen.

Erfahren Sie mehr über das Laden von Dokumenten:
[Loading documents](../https://docs.groupdocs.com/display/watermarknet/Loading+documents).

Das folgende Beispiel zeigt, wie ein verschlüsseltes PDF-Dokument mit einem Passwort geladen wird
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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Dokument | java.io.InputStream | Der Stream, aus dem das Dokument geladen wird. |
|
|  | options | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) | Zusätzliche Optionen, die beim Laden eines Dokuments verwendet werden. |
|

### Watermarker(InputStream document, WatermarkerSettings settings) {#Watermarker-java.io.InputStream-com.groupdocs.watermark.WatermarkerSettings-}
```
public Watermarker(InputStream document, WatermarkerSettings settings)
```


Initialisiert eine neue Instanz der `[Watermarker](../../com.groupdocs.watermark/watermarker)` Klasse mit dem angegebenen Stream und Einstellungen.

Erfahren Sie mehr über das Laden von Dokumenten:
[Loading documents](../https://docs.groupdocs.com/display/watermarknet/Loading+documents).

Das folgende Beispiel zeigt, wie durchsuchbare Objekte global festgelegt werden (für alle Dokumente, die
nachdem sie geladen werden).
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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Dokument | java.io.InputStream | Der Stream, aus dem das Dokument geladen wird. |
|
|  | settings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) | Zusätzliche Einstellungen, die bei der Arbeit mit dem geladenen Dokument verwendet werden. |
|

### Watermarker(InputStream document, LoadOptions options, WatermarkerSettings settings) {#Watermarker-java.io.InputStream-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-}
```
public Watermarker(InputStream document, LoadOptions options, WatermarkerSettings settings)
```


Initialisiert eine neue Instanz der Klasse mit dem angegebenen Stream, Ladeoptionen und Einstellungen.

Erfahren Sie mehr über das Laden von Dokumenten:
[Loading documents](../https://docs.groupdocs.com/display/watermarknet/Loading+documents).

Das folgende Beispiel zeigt, wie durchsuchbare Objekte global festgelegt werden (für alle Dokumente, die
nachdem sie geladen werden).
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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Dokument | java.io.InputStream | Der Stream, aus dem das Dokument geladen wird. |
|
|  | options | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) | Zusätzliche Optionen, die beim Laden eines Dokuments verwendet werden. |
|
|  | settings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) | Zusätzliche Einstellungen, die bei der Arbeit mit dem geladenen Dokument verwendet werden. |
|

### Watermarker(System.IO.Stream document, LoadOptions options, WatermarkerSettings settings) {#Watermarker-com.aspose.ms.System.IO.Stream-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-}
```
public Watermarker(System.IO.Stream document, LoadOptions options, WatermarkerSettings settings)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Dokument | com.aspose.ms.System.IO.Stream |  |
| options | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) |  |
| settings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) |  |

### getSearchableObjects() {#getSearchableObjects--}
```
public final SearchableObjects getSearchableObjects()
```


Ruft die Inhaltsobjekte ab, die in einer Wasserzeichen‑Suche enthalten sein sollen.

Diese Methode gibt außerdem Inhaltsobjekte an, die bei der Bildsuche verwendet werden.
Weitere Informationen finden Sie unter `#search(SearchCriteria).search(SearchCriteria)`
und die Methoden `#getImages().getImages()`.

Erfahren Sie mehr über das Suchen von Wasserzeichen:
[Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks).

Das folgende Beispiel zeigt, wie alle XObjects und Artefakte aus einem PDF-Dokument entfernt werden.
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


Setzt die Inhaltsobjekte, die in einer Wasserzeichen‑Suche enthalten sein sollen.

Diese Methode gibt außerdem Inhaltsobjekte an, die bei der Bildsuche verwendet werden.
Weitere Informationen finden Sie unter `#search(SearchCriteria).search(SearchCriteria)`
und die Methoden `#getImages().getImages()`.
Erfahren Sie mehr über das Suchen von Wasserzeichen:
[Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks).

Das folgende Beispiel zeigt, wie alle XObjects und Artefakte aus einem PDF-Dokument entfernt werden.
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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | [SearchableObjects](../../com.groupdocs.watermark.search/searchableobjects) | Die Objekte, die in die Wasserzeichensuche einbezogen werden sollen. |
|

### dispose() {#dispose--}
```
public final void dispose()
```




### close() {#close--}
```
public final void close()
```


Gibt die aktuelle Instanz frei.


### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


Ruft die Informationen über das Format des geladenen Dokuments ab.

Erfahren Sie mehr über das Abrufen von Dokumentinformationen
[Get document info](../https://docs.groupdocs.com/display/watermarkjava/Get+document+info).

Das folgende Beispiel zeigt, wie Informationen über ein Dokument eines beliebigen unterstützten Typs abgerufen werden.
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


Fügt dem geladenen Dokument ein Wasserzeichen hinzu.

Erfahren Sie mehr über das Hinzufügen von Wasserzeichen:
[Adding watermarks](../https://docs.groupdocs.com/display/watermarkjava/Adding+watermarks).

Das folgende Beispiel zeigt, wie ein Bild- und Textwasserzeichen zu einem Dokument eines beliebigen unterstützten Typs hinzugefügt wird.
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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | watermark | [Watermark](../../com.groupdocs.watermark/watermark) | Das hinzuzufügende Wasserzeichen für das Dokument. |
|

### add(Watermark watermark, WatermarkOptions options) {#add-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.WatermarkOptions-}
```
public final void add(Watermark watermark, WatermarkOptions options)
```


Fügt dem geladenen Dokument ein Wasserzeichen mithilfe von Wasserzeichen‑Optionen hinzu.

Erfahren Sie mehr über das Hinzufügen von Wasserzeichen:
[Adding watermarks](../https://docs.groupdocs.com/display/watermarkjava/Adding+watermarks).

Das folgende Beispiel zeigt, wie ein Bildwasserzeichen zu einer bestimmten Seite eines PDF-Dokuments hinzugefügt wird.
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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | watermark | [Watermark](../../com.groupdocs.watermark/watermark) | Das hinzuzufügende Wasserzeichen für das Dokument. |
|
|  | options | [WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions) | Zusätzliche Optionen, die beim Hinzufügen des Wasserzeichens verwendet werden können. |
|

### remove(PossibleWatermark possibleWatermark) {#remove-com.groupdocs.watermark.search.PossibleWatermark-}
```
public final void remove(PossibleWatermark possibleWatermark)
```


Entfernt das Wasserzeichen aus dem Dokument.

Erfahren Sie mehr über das Entfernen von Wasserzeichen:
[Removing found watermarks](../https://docs.groupdocs.com/display/watermarkjava/Removing+found+watermarks).

Das folgende Beispiel zeigt, wie das erste mögliche Wasserzeichen, das ein bestimmtes
Text oder Bild aus einem Dokument eines beliebigen unterstützten Typs enthält, gefunden und entfernt wird.
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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | possibleWatermark | [PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark) | Das zu entfernende Wasserzeichen. |
|

### remove(PossibleWatermarkCollection possibleWatermarks) {#remove-com.groupdocs.watermark.search.PossibleWatermarkCollection-}
```
public final void remove(PossibleWatermarkCollection possibleWatermarks)
```


Entfernt alle Wasserzeichen aus der Sammlung aus dem Dokument.

Erfahren Sie mehr über das Entfernen von Wasserzeichen:
[Removing found watermarks](../https://docs.groupdocs.com/display/watermarkjava/Removing+found+watermarks).

Das folgende Beispiel zeigt, wie alle möglichen Wasserzeichen, die ein bestimmtes
Text oder Bild aus einem Dokument eines beliebigen unterstützten Typs enthält, gefunden und entfernt wird.
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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | possibleWatermarks | [PossibleWatermarkCollection](../../com.groupdocs.watermark.search/possiblewatermarkcollection) | Die Sammlung der zu entfernenden Wasserzeichen. |
|

### save(String filePath) {#save-java.lang.String-}
```
public final void save(String filePath)
```


Speichert das Dokument am angegebenen Speicherort.

Erfahren Sie mehr über das Speichern von Dokumenten
[Saving documents](../https://docs.groupdocs.com/display/watermarkjava/Saving+documents).

Das folgende Beispiel zeigt, wie das Wasserzeichen hinzugefügt und das Dokument in einer anderen Datei gespeichert wird.
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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | filePath | java.lang.String | Der Dateipfad, in dem die Dokumentdaten gespeichert werden. |
|

### save(OutputStream document) {#save-java.io.OutputStream-}
```
public final void save(OutputStream document)
```


Speichert das Dokument im angegebenen Stream.

Erfahren Sie mehr über das Speichern von Dokumenten
[Saving documents](../https://docs.groupdocs.com/display/watermarkjava/Saving+documents).

Das folgende Beispiel zeigt, wie man ein Wasserzeichen hinzufügt und das Dokument in den Speicherstrom speichert.
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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Dokument | java.io.OutputStream | Der Stream, in dem die Dokumentdaten gespeichert werden. |
|

### save(String filePath, SaveOptions options) {#save-java.lang.String-com.groupdocs.watermark.options.SaveOptions-}
```
public final void save(String filePath, SaveOptions options)
```


Speichert das Dokument am angegebenen Speicherort unter Verwendung von Speicheroptionen.

Erfahren Sie mehr über das Speichern von Dokumenten
[Saving documents](../https://docs.groupdocs.com/display/watermarkjava/Saving+documents).

Das folgende Beispiel zeigt, wie man das Wasserzeichen hinzufügt und das Dokument in einer anderen Datei speichert
mit dem Standard `[SaveOptions](../../com.groupdocs.watermark.options/saveoptions)`.
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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | filePath | java.lang.String | Der Dateipfad, in dem die Dokumentdaten gespeichert werden. |
|
|  | options | [SaveOptions](../../com.groupdocs.watermark.options/saveoptions) | Zusätzliche Optionen, die beim Speichern eines Dokuments verwendet werden. |
|

### save(OutputStream document, SaveOptions options) {#save-java.io.OutputStream-com.groupdocs.watermark.options.SaveOptions-}
```
public final void save(OutputStream document, SaveOptions options)
```


Speichert das Dokument im angegebenen Stream unter Verwendung von Speicheroptionen.

Erfahren Sie mehr über das Speichern von Dokumenten
[Saving documents](../https://docs.groupdocs.com/display/watermarkjava/Saving+documents).

Das folgende Beispiel zeigt, wie man ein Wasserzeichen hinzufügt und das Dokument in den Speicherstrom speichert
mit dem Standard `[SaveOptions](../../com.groupdocs.watermark.options/saveoptions)`.
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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Dokument | java.io.OutputStream | Der Stream, in dem die Dokumentdaten gespeichert werden. |
|
|  | options | [SaveOptions](../../com.groupdocs.watermark.options/saveoptions) | Zusätzliche Optionen, die beim Speichern eines Dokuments verwendet werden. |
|

### generatePreview(PreviewOptions previewOptions) {#generatePreview-com.groupdocs.watermark.options.PreviewOptions-}
```
public final void generatePreview(PreviewOptions previewOptions)
```


Erstellt Vorschaubilder für das Dokument.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | previewOptions | [PreviewOptions](../../com.groupdocs.watermark.options/previewoptions) | Zusätzliche Optionen, die beim Erzeugen von Vorschaubildern verwendet werden. |
|

### search() {#search--}
```
public final PossibleWatermarkCollection search()
```


Durchsucht alle möglichen Wasserzeichen im Dokument.

Die Suche wird in Objekten durchgeführt, die mit `#setSearchableObjects(SearchableObjects).setSearchableObjects(SearchableObjects)` angegeben sind.

Erfahren Sie mehr über die Suche nach Wasserzeichen
[Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks).

Das folgende Beispiel zeigt, wie man die möglichen Wasserzeichen in einem Dokument eines beliebigen unterstützten Typs zählt.
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


Durchsucht mögliche Wasserzeichen gemäß den angegebenen Suchkriterien.

Die Suche wird in Objekten durchgeführt, die mit `#setSearchableObjects(SearchableObjects).setSearchableObjects(SearchableObjects)` angegeben sind.

Erfahren Sie mehr über die Suche nach Wasserzeichen
[Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks).

Das folgende Beispiel zeigt, wie man alle möglichen Wasserzeichen, die einen bestimmten Text enthalten, findet und entfernt
oder ein Bild aus einem Dokument eines beliebigen unterstützten Typs.
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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | searchCriteria | [SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) | Die zu verwendenden Suchkriterien. |
|

**Returns:**
[PossibleWatermarkCollection](../../com.groupdocs.watermark.search/possiblewatermarkcollection)
### getImages(ImageSearchCriteria searchCriteria) {#getImages-com.groupdocs.watermark.search.ImageSearchCriteria-}
```
public final WatermarkableImageCollection getImages(ImageSearchCriteria searchCriteria)
```


Findet Bilder gemäß den angegebenen Suchkriterien.

Die Suche wird in Objekten durchgeführt, die mit `#setSearchableObjects(SearchableObjects).setSearchableObjects(SearchableObjects)` angegeben sind.

Erfahren Sie mehr über die Suche nach Wasserzeichen
[Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks).

Das folgende Beispiel zeigt, wie man alle Bilder entfernt, die dem Referenzbild ähneln
aus einem Dokument eines beliebigen unterstützten Typs.
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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | searchCriteria | [ImageSearchCriteria](../../com.groupdocs.watermark.search/imagesearchcriteria) | Die zu verwendenden Suchkriterien. |
|

**Returns:**
[WatermarkableImageCollection](../../com.groupdocs.watermark.contents/watermarkableimagecollection)
### getImages() {#getImages--}
```
public final WatermarkableImageCollection getImages()
```


Findet alle Bilder im Dokument.

Die Suche wird in Objekten durchgeführt, die mit `#setSearchableObjects(SearchableObjects).setSearchableObjects(SearchableObjects)` angegeben sind.

Erfahren Sie mehr über die Suche nach Wasserzeichen
[Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks).

Das folgende Beispiel zeigt, wie man ein Wasserzeichen zu allen Bildern in einem Dokument eines beliebigen unterstützten Typs hinzufügt.
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


Gibt das `[Content](../../com.groupdocs.watermark.contents/content)`-Objekt für das geladene Dokument zurück.

Das folgende Beispiel zeigt, wie man eine PDF-Dokumentseite mit hinzugefügtem Wasserzeichen rasterisiert.
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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | contentType | java.lang.Class<T> | Der angeforderte Typ eines `[Content](../../com.groupdocs.watermark.contents/content)`-Objekts. |
|

**Returns:**
T - Das `[Content](../../com.groupdocs.watermark.contents/content)`-Objekt für das geladene Dokument.

