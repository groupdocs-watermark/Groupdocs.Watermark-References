---
title: "Watermarker"
second_title: "GroupDocs.Watermark pour Java Référence API"
description: "Représente une classe pour la gestion des filigranes dans un document."
type: docs
weight: 14
url: /fr/java/com.groupdocs.watermark/watermarker/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class Watermarker implements Closeable
```

Représente une classe pour la gestion des filigranes dans un document.

L'exemple suivant montre comment charger et enregistrer le contenu de tout format pris en charge.
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


## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [Watermarker(String filePath)](#Watermarker-java.lang.String-) | Initialise une nouvelle instance de la classe `[Watermarker](../../com.groupdocs.watermark/watermarker)` avec le chemin de document spécifié. |
|
|  | [Watermarker(String filePath, LoadOptions options)](#Watermarker-java.lang.String-com.groupdocs.watermark.options.LoadOptions-) | Initialise une nouvelle instance de la classe `[Watermarker](../../com.groupdocs.watermark/watermarker)` avec le chemin de document et les options de chargement spécifiés. |
|
|  | [Watermarker(String filePath, WatermarkerSettings settings)](#Watermarker-java.lang.String-com.groupdocs.watermark.WatermarkerSettings-) | Initialise une nouvelle instance de la classe `[Watermarker](../../com.groupdocs.watermark/watermarker)` avec le chemin de document et les paramètres spécifiés. |
|
|  | [Watermarker(String filePath, LoadOptions options, WatermarkerSettings settings)](#Watermarker-java.lang.String-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-) | Initialise une nouvelle instance de la classe `[Watermarker](../../com.groupdocs.watermark/watermarker)` avec le chemin de document, les options de chargement et les paramètres spécifiés. |
|
|  | [Watermarker(InputStream document)](#Watermarker-java.io.InputStream-) | Initialise une nouvelle instance de la classe `[Watermarker](../../com.groupdocs.watermark/watermarker)` avec le flux spécifié. |
|
|  | [Watermarker(InputStream document, LoadOptions options)](#Watermarker-java.io.InputStream-com.groupdocs.watermark.options.LoadOptions-) | Initialise une nouvelle instance de la classe `[Watermarker](../../com.groupdocs.watermark/watermarker)` avec le flux et les options de chargement spécifiés. |
|
|  | [Watermarker(InputStream document, WatermarkerSettings settings)](#Watermarker-java.io.InputStream-com.groupdocs.watermark.WatermarkerSettings-) | Initialise une nouvelle instance de la classe `[Watermarker](../../com.groupdocs.watermark/watermarker)` avec le flux et les paramètres spécifiés. |
|
|  | [Watermarker(InputStream document, LoadOptions options, WatermarkerSettings settings)](#Watermarker-java.io.InputStream-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-) | Initialise une nouvelle instance de la classe avec le flux, les options de chargement et les paramètres spécifiés. |
|
| [Watermarker(System.IO.Stream document, LoadOptions options, WatermarkerSettings settings)](#Watermarker-com.aspose.ms.System.IO.Stream-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getSearchableObjects()](#getSearchableObjects--) | Obtient les objets de contenu qui doivent être inclus dans une recherche de filigrane. |
|
|  | [setSearchableObjects(SearchableObjects value)](#setSearchableObjects-com.groupdocs.watermark.search.SearchableObjects-) | Définit les objets de contenu qui doivent être inclus dans une recherche de filigrane. |
|
| [dispose()](#dispose--) |  |
|  | [close()](#close--) | Libère l'instance actuelle. |
|
|  | [getDocumentInfo()](#getDocumentInfo--) | Obtient les informations sur le format du document chargé. |
|
|  | [add(Watermark watermark)](#add-com.groupdocs.watermark.Watermark-) | Ajoute un filigrane au document chargé. |
|
|  | [add(Watermark watermark, WatermarkOptions options)](#add-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.WatermarkOptions-) | Ajoute un filigrane au document chargé en utilisant les options de filigrane. |
|
|  | [remove(PossibleWatermark possibleWatermark)](#remove-com.groupdocs.watermark.search.PossibleWatermark-) | Supprime le filigrane du document. |
|
|  | [remove(PossibleWatermarkCollection possibleWatermarks)](#remove-com.groupdocs.watermark.search.PossibleWatermarkCollection-) | Supprime tous les filigranes de la collection du document. |
|
|  | [save(String filePath)](#save-java.lang.String-) | Enregistre le document à l'emplacement de fichier spécifié. |
|
|  | [save(OutputStream document)](#save-java.io.OutputStream-) | Enregistre le document dans le flux spécifié. |
|
|  | [save(String filePath, SaveOptions options)](#save-java.lang.String-com.groupdocs.watermark.options.SaveOptions-) | Enregistre le document à l'emplacement de fichier spécifié en utilisant les options d'enregistrement. |
|
|  | [save(OutputStream document, SaveOptions options)](#save-java.io.OutputStream-com.groupdocs.watermark.options.SaveOptions-) | Enregistre le document dans le flux spécifié en utilisant les options d'enregistrement. |
|
|  | [generatePreview(PreviewOptions previewOptions)](#generatePreview-com.groupdocs.watermark.options.PreviewOptions-) | Génère des images d'aperçu pour le document. |
|
|  | [search()](#search--) | Recherche toutes les filigranes possibles dans le document. |
|
|  | [search(SearchCriteria searchCriteria)](#search-com.groupdocs.watermark.search.SearchCriteria-) | Recherche les filigranes possibles selon les critères de recherche spécifiés. |
|
|  | [getImages(ImageSearchCriteria searchCriteria)](#getImages-com.groupdocs.watermark.search.ImageSearchCriteria-) | Trouve les images selon les critères de recherche spécifiés. |
|
|  | [getImages()](#getImages--) | Trouve toutes les images dans le document. |
|
|  | [<T>getContent(Class<T> contentType)](#-T-getContent-java.lang.Class-T--) | Renvoie l'objet `[Content](../../com.groupdocs.watermark.contents/content)` pour le document chargé. |
|
### Watermarker(String filePath) {#Watermarker-java.lang.String-}
```
public Watermarker(String filePath)
```


Initialise une nouvelle instance de la classe `[Watermarker](../../com.groupdocs.watermark/watermarker)` avec le chemin de document spécifié.

En savoir plus sur le chargement des documents :
[Loading documents](../https://docs.groupdocs.com/display/watermarkjava/Loading+documents).

L'exemple suivant montre comment charger et enregistrer le contenu de tout format pris en charge.
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
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.lang.String | Le chemin du fichier à partir duquel charger le document. |
|

### Watermarker(String filePath, LoadOptions options) {#Watermarker-java.lang.String-com.groupdocs.watermark.options.LoadOptions-}
```
public Watermarker(String filePath, LoadOptions options)
```


Initialise une nouvelle instance de la classe `[Watermarker](../../com.groupdocs.watermark/watermarker)` avec le chemin de document et les options de chargement spécifiés.

En savoir plus sur le chargement des documents :
[Loading documents](../https://docs.groupdocs.com/display/watermarkjava/Loading+documents).

L'exemple suivant montre comment charger un document PDF chiffré en utilisant un mot de passe.
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
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.lang.String | Le chemin du fichier à partir duquel charger le document. |
|
|  | options | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) | Options supplémentaires à utiliser lors du chargement d'un document. |
|

### Watermarker(String filePath, WatermarkerSettings settings) {#Watermarker-java.lang.String-com.groupdocs.watermark.WatermarkerSettings-}
```
public Watermarker(String filePath, WatermarkerSettings settings)
```


Initialise une nouvelle instance de la classe `[Watermarker](../../com.groupdocs.watermark/watermarker)` avec le chemin de document et les paramètres spécifiés.

En savoir plus sur le chargement des documents :
[Loading documents](../https://docs.groupdocs.com/display/watermarkjava/Loading+documents).

L'exemple suivant montre comment définir les objets recherchables globalement (pour tous les documents qui
seront chargés après cela).
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
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.lang.String | Le chemin du fichier à partir duquel charger le document. |
|
|  | settings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) | Paramètres supplémentaires à utiliser lors du travail avec le document chargé. |
|

### Watermarker(String filePath, LoadOptions options, WatermarkerSettings settings) {#Watermarker-java.lang.String-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-}
```
public Watermarker(String filePath, LoadOptions options, WatermarkerSettings settings)
```


Initialise une nouvelle instance de la classe `[Watermarker](../../com.groupdocs.watermark/watermarker)` avec le chemin de document, les options de chargement et les paramètres spécifiés.

En savoir plus sur le chargement des documents :
[Loading documents](../https://docs.groupdocs.com/display/watermarknet/Loading+documents).

L'exemple suivant montre comment trouver des fragments de texte particuliers dans le corps/sujet d'un message électronique.
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
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.lang.String | Le chemin du fichier à partir duquel charger le document. |
|
|  | options | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) | Options supplémentaires à utiliser lors du chargement d'un document. |
|
|  | settings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) | Paramètres supplémentaires à utiliser lors du travail avec le document chargé. |
|

### Watermarker(InputStream document) {#Watermarker-java.io.InputStream-}
```
public Watermarker(InputStream document)
```


Initialise une nouvelle instance de la classe `[Watermarker](../../com.groupdocs.watermark/watermarker)` avec le flux spécifié.

En savoir plus sur le chargement des documents :
[Loading documents](../https://docs.groupdocs.com/display/watermarknet/Loading+documents).

L'exemple suivant montre comment charger et enregistrer un document de n'importe quel format pris en charge.
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
| Paramètre | Type | Description |
| --- | --- | --- |
|  | document | java.io.InputStream | Le flux à partir duquel charger le document. |
|

### Watermarker(InputStream document, LoadOptions options) {#Watermarker-java.io.InputStream-com.groupdocs.watermark.options.LoadOptions-}
```
public Watermarker(InputStream document, LoadOptions options)
```


Initialise une nouvelle instance de la classe `[Watermarker](../../com.groupdocs.watermark/watermarker)` avec le flux et les options de chargement spécifiés.

En savoir plus sur le chargement des documents :
[Loading documents](../https://docs.groupdocs.com/display/watermarknet/Loading+documents).

L'exemple suivant montre comment charger un document PDF chiffré à l'aide d'un mot de passe
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
| Paramètre | Type | Description |
| --- | --- | --- |
|  | document | java.io.InputStream | Le flux à partir duquel charger le document. |
|
|  | options | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) | Options supplémentaires à utiliser lors du chargement d'un document. |
|

### Watermarker(InputStream document, WatermarkerSettings settings) {#Watermarker-java.io.InputStream-com.groupdocs.watermark.WatermarkerSettings-}
```
public Watermarker(InputStream document, WatermarkerSettings settings)
```


Initialise une nouvelle instance de la classe `[Watermarker](../../com.groupdocs.watermark/watermarker)` avec le flux et les paramètres spécifiés.

En savoir plus sur le chargement des documents :
[Loading documents](../https://docs.groupdocs.com/display/watermarknet/Loading+documents).

L'exemple suivant montre comment définir les objets recherchables globalement (pour tous les documents qui
seront chargés après cela).
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
| Paramètre | Type | Description |
| --- | --- | --- |
|  | document | java.io.InputStream | Le flux à partir duquel charger le document. |
|
|  | settings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) | Paramètres supplémentaires à utiliser lors du travail avec le document chargé. |
|

### Watermarker(InputStream document, LoadOptions options, WatermarkerSettings settings) {#Watermarker-java.io.InputStream-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-}
```
public Watermarker(InputStream document, LoadOptions options, WatermarkerSettings settings)
```


Initialise une nouvelle instance de la classe avec le flux, les options de chargement et les paramètres spécifiés.

En savoir plus sur le chargement des documents :
[Loading documents](../https://docs.groupdocs.com/display/watermarknet/Loading+documents).

L'exemple suivant montre comment définir les objets recherchables globalement (pour tous les documents qui
seront chargés après cela).
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
| Paramètre | Type | Description |
| --- | --- | --- |
|  | document | java.io.InputStream | Le flux à partir duquel charger le document. |
|
|  | options | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) | Options supplémentaires à utiliser lors du chargement d'un document. |
|
|  | settings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) | Paramètres supplémentaires à utiliser lors du travail avec le document chargé. |
|

### Watermarker(System.IO.Stream document, LoadOptions options, WatermarkerSettings settings) {#Watermarker-com.aspose.ms.System.IO.Stream-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-}
```
public Watermarker(System.IO.Stream document, LoadOptions options, WatermarkerSettings settings)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| document | com.aspose.ms.System.IO.Stream |  |
| options | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) |  |
| settings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) |  |

### getSearchableObjects() {#getSearchableObjects--}
```
public final SearchableObjects getSearchableObjects()
```


Obtient les objets de contenu qui doivent être inclus dans une recherche de filigrane.

Cette méthode spécifie également les objets de contenu qui sont utilisés dans la recherche d'images.
Pour plus d'informations, voir `#search(SearchCriteria).search(SearchCriteria)`
et les méthodes `#getImages().getImages()`.

En savoir plus sur la recherche de filigranes :
[Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks).

L'exemple suivant montre comment supprimer tous les XObjects et les Artefacts d'un document PDF.
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


Définit les objets de contenu qui doivent être inclus dans une recherche de filigrane.

Cette méthode spécifie également les objets de contenu qui sont utilisés dans la recherche d'images.
Pour plus d'informations, voir `#search(SearchCriteria).search(SearchCriteria)`
et les méthodes `#getImages().getImages()`.
En savoir plus sur la recherche de filigranes :
[Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks).

L'exemple suivant montre comment supprimer tous les XObjects et les Artefacts d'un document PDF.
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
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | [SearchableObjects](../../com.groupdocs.watermark.search/searchableobjects) | Les objets qui doivent être inclus dans la recherche de filigrane. |
|

### dispose() {#dispose--}
```
public final void dispose()
```




### close() {#close--}
```
public final void close()
```


Libère l'instance actuelle.


### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


Obtient les informations sur le format du document chargé.

En savoir plus sur l'obtention des informations du document
[Get document info](../https://docs.groupdocs.com/display/watermarkjava/Get+document+info).

L'exemple suivant montre comment obtenir des informations sur un document de tout type pris en charge.
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


Ajoute un filigrane au document chargé.

En savoir plus sur l'ajout de filigranes :
[Adding watermarks](../https://docs.groupdocs.com/display/watermarkjava/Adding+watermarks).

L'exemple suivant montre comment ajouter un filigrane image et texte à un document de tout type pris en charge.
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
| Paramètre | Type | Description |
| --- | --- | --- |
|  | watermark | [Watermark](../../com.groupdocs.watermark/watermark) | Le filigrane à ajouter au document. |
|

### add(Watermark watermark, WatermarkOptions options) {#add-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.WatermarkOptions-}
```
public final void add(Watermark watermark, WatermarkOptions options)
```


Ajoute un filigrane au document chargé en utilisant les options de filigrane.

En savoir plus sur l'ajout de filigranes :
[Adding watermarks](../https://docs.groupdocs.com/display/watermarkjava/Adding+watermarks).

L'exemple suivant montre comment ajouter un filigrane image à une page particulière d'un document PDF.
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
| Paramètre | Type | Description |
| --- | --- | --- |
|  | watermark | [Watermark](../../com.groupdocs.watermark/watermark) | Le filigrane à ajouter au document. |
|
|  | options | [WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions) | Options supplémentaires à utiliser lors de l'ajout du filigrane. |
|

### remove(PossibleWatermark possibleWatermark) {#remove-com.groupdocs.watermark.search.PossibleWatermark-}
```
public final void remove(PossibleWatermark possibleWatermark)
```


Supprime le filigrane du document.

En savoir plus sur la suppression de filigranes :
[Removing found watermarks](../https://docs.groupdocs.com/display/watermarkjava/Removing+found+watermarks).

L'exemple suivant montre comment trouver et supprimer le premier filigrane possible contenant un élément particulier
texte ou image d'un document de tout type pris en charge.
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
| Paramètre | Type | Description |
| --- | --- | --- |
|  | possibleWatermark | [PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark) | Le filigrane à supprimer. |
|

### remove(PossibleWatermarkCollection possibleWatermarks) {#remove-com.groupdocs.watermark.search.PossibleWatermarkCollection-}
```
public final void remove(PossibleWatermarkCollection possibleWatermarks)
```


Supprime tous les filigranes de la collection du document.

En savoir plus sur la suppression de filigranes :
[Removing found watermarks](../https://docs.groupdocs.com/display/watermarkjava/Removing+found+watermarks).

L'exemple suivant montre comment trouver et supprimer tous les filigranes possibles contenant un élément particulier
texte ou image d'un document de tout type pris en charge.
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
| Paramètre | Type | Description |
| --- | --- | --- |
|  | possibleWatermarks | [PossibleWatermarkCollection](../../com.groupdocs.watermark.search/possiblewatermarkcollection) | La collection de filigranes à supprimer. |
|

### save(String filePath) {#save-java.lang.String-}
```
public final void save(String filePath)
```


Enregistre le document à l'emplacement de fichier spécifié.

En savoir plus sur l'enregistrement des documents
[Saving documents](../https://docs.groupdocs.com/display/watermarkjava/Saving+documents).

L'exemple suivant montre comment ajouter le filigrane et enregistrer le document dans un autre fichier.
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
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.lang.String | Le chemin du fichier où enregistrer les données du document. |
|

### save(OutputStream document) {#save-java.io.OutputStream-}
```
public final void save(OutputStream document)
```


Enregistre le document dans le flux spécifié.

En savoir plus sur l'enregistrement des documents
[Saving documents](../https://docs.groupdocs.com/display/watermarkjava/Saving+documents).

L'exemple suivant montre comment ajouter un filigrane et enregistrer le document dans le flux mémoire.
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
| Paramètre | Type | Description |
| --- | --- | --- |
|  | document | java.io.OutputStream | Le flux où enregistrer les données du document. |
|

### save(String filePath, SaveOptions options) {#save-java.lang.String-com.groupdocs.watermark.options.SaveOptions-}
```
public final void save(String filePath, SaveOptions options)
```


Enregistre le document à l'emplacement de fichier spécifié en utilisant les options d'enregistrement.

En savoir plus sur l'enregistrement des documents
[Saving documents](../https://docs.groupdocs.com/display/watermarkjava/Saving+documents).

L'exemple suivant montre comment ajouter le filigrane et enregistrer le document dans un autre fichier
avec les `[SaveOptions](../../com.groupdocs.watermark.options/saveoptions)` par défaut.
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
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.lang.String | Le chemin du fichier où enregistrer les données du document. |
|
|  | options | [SaveOptions](../../com.groupdocs.watermark.options/saveoptions) | Options supplémentaires à utiliser lors de l'enregistrement d'un document. |
|

### save(OutputStream document, SaveOptions options) {#save-java.io.OutputStream-com.groupdocs.watermark.options.SaveOptions-}
```
public final void save(OutputStream document, SaveOptions options)
```


Enregistre le document dans le flux spécifié en utilisant les options d'enregistrement.

En savoir plus sur l'enregistrement des documents
[Saving documents](../https://docs.groupdocs.com/display/watermarkjava/Saving+documents).

L'exemple suivant montre comment ajouter un filigrane et enregistrer le document dans le flux mémoire
avec les `[SaveOptions](../../com.groupdocs.watermark.options/saveoptions)` par défaut.
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
| Paramètre | Type | Description |
| --- | --- | --- |
|  | document | java.io.OutputStream | Le flux où enregistrer les données du document. |
|
|  | options | [SaveOptions](../../com.groupdocs.watermark.options/saveoptions) | Options supplémentaires à utiliser lors de l'enregistrement d'un document. |
|

### generatePreview(PreviewOptions previewOptions) {#generatePreview-com.groupdocs.watermark.options.PreviewOptions-}
```
public final void generatePreview(PreviewOptions previewOptions)
```


Génère des images d'aperçu pour le document.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | previewOptions | [PreviewOptions](../../com.groupdocs.watermark.options/previewoptions) | Options supplémentaires à utiliser lors de la génération d'images d'aperçu. |
|

### search() {#search--}
```
public final PossibleWatermarkCollection search()
```


Recherche toutes les filigranes possibles dans le document.

La recherche est effectuée dans les objets spécifiés avec `#setSearchableObjects(SearchableObjects).setSearchableObjects(SearchableObjects)`.

En savoir plus sur la recherche de filigranes
[Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks).

L'exemple suivant montre comment compter les filigranes possibles dans un document de tout type pris en charge.
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


Recherche les filigranes possibles selon les critères de recherche spécifiés.

La recherche est effectuée dans les objets spécifiés avec `#setSearchableObjects(SearchableObjects).setSearchableObjects(SearchableObjects)`.

En savoir plus sur la recherche de filigranes
[Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks).

L'exemple suivant montre comment trouver et supprimer tous les filigranes possibles contenant un texte particulier
ou une image d'un document de tout type pris en charge.
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
| Paramètre | Type | Description |
| --- | --- | --- |
|  | searchCriteria | [SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) | Les critères de recherche à utiliser. |
|

**Returns:**
[PossibleWatermarkCollection](../../com.groupdocs.watermark.search/possiblewatermarkcollection)
### getImages(ImageSearchCriteria searchCriteria) {#getImages-com.groupdocs.watermark.search.ImageSearchCriteria-}
```
public final WatermarkableImageCollection getImages(ImageSearchCriteria searchCriteria)
```


Trouve les images selon les critères de recherche spécifiés.

La recherche est effectuée dans les objets spécifiés avec `#setSearchableObjects(SearchableObjects).setSearchableObjects(SearchableObjects)`.

En savoir plus sur la recherche de filigranes
[Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks).

L'exemple suivant montre comment supprimer toutes les images similaires à la référence
d'un document de tout type pris en charge.
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
| Paramètre | Type | Description |
| --- | --- | --- |
|  | searchCriteria | [ImageSearchCriteria](../../com.groupdocs.watermark.search/imagesearchcriteria) | Les critères de recherche à utiliser. |
|

**Returns:**
[WatermarkableImageCollection](../../com.groupdocs.watermark.contents/watermarkableimagecollection)
### getImages() {#getImages--}
```
public final WatermarkableImageCollection getImages()
```


Trouve toutes les images dans le document.

La recherche est effectuée dans les objets spécifiés avec `#setSearchableObjects(SearchableObjects).setSearchableObjects(SearchableObjects)`.

En savoir plus sur la recherche de filigranes
[Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks).

L'exemple suivant montre comment ajouter un filigrane à toutes les images d'un document de tout type pris en charge.
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


Renvoie l'objet `[Content](../../com.groupdocs.watermark.contents/content)` pour le document chargé.

L'exemple suivant montre comment rasteriser la page d'un document PDF avec un filigrane ajouté.
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
| Paramètre | Type | Description |
| --- | --- | --- |
|  | contentType | java.lang.Class<T> | Le type demandé d'un objet `[Content](../../com.groupdocs.watermark.contents/content)`. |
|

**Returns:**
T - L'objet `[Content](../../com.groupdocs.watermark.contents/content)` pour le document chargé.

