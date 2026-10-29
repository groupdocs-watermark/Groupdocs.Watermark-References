---
title: "Watermarker"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Representerar en klass för vattenstämpelhantering i ett dokument."
type: docs
weight: 14
url: /sv/java/com.groupdocs.watermark/watermarker/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class Watermarker implements Closeable
```

Representerar en klass för vattenstämpelhantering i ett dokument.

Följande exempel visar hur man laddar och sparar innehållet i vilket som helst stödd format.
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


## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [Watermarker(String filePath)](#Watermarker-java.lang.String-) | Initierar en ny instans av klassen `[Watermarker](../../com.groupdocs.watermark/watermarker)` med den angivna dokumentvägen. |
|
|  | [Watermarker(String filePath, LoadOptions options)](#Watermarker-java.lang.String-com.groupdocs.watermark.options.LoadOptions-) | Initierar en ny instans av klassen `[Watermarker](../../com.groupdocs.watermark/watermarker)` med den angivna dokumentvägen och laddningsalternativen. |
|
|  | [Watermarker(String filePath, WatermarkerSettings settings)](#Watermarker-java.lang.String-com.groupdocs.watermark.WatermarkerSettings-) | Initierar en ny instans av klassen `[Watermarker](../../com.groupdocs.watermark/watermarker)` med den angivna dokumentvägen och inställningarna. |
|
|  | [Watermarker(String filePath, LoadOptions options, WatermarkerSettings settings)](#Watermarker-java.lang.String-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-) | Initierar en ny instans av klassen `[Watermarker](../../com.groupdocs.watermark/watermarker)` med den angivna dokumentvägen, laddningsalternativen och inställningarna. |
|
|  | [Watermarker(InputStream document)](#Watermarker-java.io.InputStream-) | Initierar en ny instans av klassen `[Watermarker](../../com.groupdocs.watermark/watermarker)` med den angivna strömmen. |
|
|  | [Watermarker(InputStream document, LoadOptions options)](#Watermarker-java.io.InputStream-com.groupdocs.watermark.options.LoadOptions-) | Initierar en ny instans av klassen `[Watermarker](../../com.groupdocs.watermark/watermarker)` med den angivna strömmen och laddningsalternativen. |
|
|  | [Watermarker(InputStream document, WatermarkerSettings settings)](#Watermarker-java.io.InputStream-com.groupdocs.watermark.WatermarkerSettings-) | Initierar en ny instans av klassen `[Watermarker](../../com.groupdocs.watermark/watermarker)` med den angivna strömmen och inställningarna. |
|
|  | [Watermarker(InputStream document, LoadOptions options, WatermarkerSettings settings)](#Watermarker-java.io.InputStream-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-) | Initierar en ny instans av klassen med den angivna strömmen, laddningsalternativen och inställningarna. |
|
| [Watermarker(System.IO.Stream document, LoadOptions options, WatermarkerSettings settings)](#Watermarker-com.aspose.ms.System.IO.Stream-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getSearchableObjects()](#getSearchableObjects--) | Hämtar innehållsobjekten som ska inkluderas i en vattenstämpelsökning. |
|
|  | [setSearchableObjects(SearchableObjects value)](#setSearchableObjects-com.groupdocs.watermark.search.SearchableObjects-) | Ställer in innehållsobjekten som ska inkluderas i en vattenstämpelsökning. |
|
| [dispose()](#dispose--) |  |
|  | [close()](#close--) | Avslutar den aktuella instansen. |
|
|  | [getDocumentInfo()](#getDocumentInfo--) | Hämtar information om formatet för det laddade dokumentet. |
|
|  | [add(Watermark watermark)](#add-com.groupdocs.watermark.Watermark-) | Lägger till en vattenstämpel i det laddade dokumentet. |
|
|  | [add(Watermark watermark, WatermarkOptions options)](#add-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.WatermarkOptions-) | Lägger till en vattenstämpel i det laddade dokumentet med hjälp av vattenstämpelalternativ. |
|
|  | [remove(PossibleWatermark possibleWatermark)](#remove-com.groupdocs.watermark.search.PossibleWatermark-) | Tar bort vattenstämpel från dokumentet. |
|
|  | [remove(PossibleWatermarkCollection possibleWatermarks)](#remove-com.groupdocs.watermark.search.PossibleWatermarkCollection-) | Tar bort alla vattenstämplar i samlingen från dokumentet. |
|
|  | [save(String filePath)](#save-java.lang.String-) | Sparar dokumentet till den angivna filplatsen. |
|
|  | [save(OutputStream document)](#save-java.io.OutputStream-) | Sparar dokumentet till den angivna strömmen. |
|
|  | [save(String filePath, SaveOptions options)](#save-java.lang.String-com.groupdocs.watermark.options.SaveOptions-) | Sparar dokumentet till den angivna filplatsen med sparalternativ. |
|
|  | [save(OutputStream document, SaveOptions options)](#save-java.io.OutputStream-com.groupdocs.watermark.options.SaveOptions-) | Sparar dokumentet till den angivna strömmen med sparalternativ. |
|
|  | [generatePreview(PreviewOptions previewOptions)](#generatePreview-com.groupdocs.watermark.options.PreviewOptions-) | Skapar förhandsgranskningsbilder för dokumentet. |
|
|  | [search()](#search--) | Söker efter alla möjliga vattenmärken i dokumentet. |
|
|  | [search(SearchCriteria searchCriteria)](#search-com.groupdocs.watermark.search.SearchCriteria-) | Söker möjliga vattenmärken enligt angivna sökkriterier. |
|
|  | [getImages(ImageSearchCriteria searchCriteria)](#getImages-com.groupdocs.watermark.search.ImageSearchCriteria-) | Hittar bilder enligt angivna sökkriterier. |
|
|  | [getImages()](#getImages--) | Hittar alla bilder i dokumentet. |
|
|  | [<T>getContent(Class<T> contentType)](#-T-getContent-java.lang.Class-T--) | Returnerar `[Content](../../com.groupdocs.watermark.contents/content)`-objektet för det inlästa dokumentet. |
|
### Watermarker(String filePath) {#Watermarker-java.lang.String-}
```
public Watermarker(String filePath)
```


Initierar en ny instans av klassen `[Watermarker](../../com.groupdocs.watermark/watermarker)` med den angivna dokumentvägen.

Läs mer om att ladda dokument:
[Loading documents](../https://docs.groupdocs.com/display/watermarkjava/Loading+documents).

Följande exempel visar hur man laddar och sparar innehållet i vilket som helst stödd format.
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filePath | java.lang.String | Filsökvägen för att ladda dokumentet från. |
|

### Watermarker(String filePath, LoadOptions options) {#Watermarker-java.lang.String-com.groupdocs.watermark.options.LoadOptions-}
```
public Watermarker(String filePath, LoadOptions options)
```


Initierar en ny instans av klassen `[Watermarker](../../com.groupdocs.watermark/watermarker)` med den angivna dokumentvägen och laddningsalternativen.

Läs mer om att ladda dokument:
[Loading documents](../https://docs.groupdocs.com/display/watermarkjava/Loading+documents).

Följande exempel visar hur man laddar ett krypterat PDF-dokument med lösenord.
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filePath | java.lang.String | Filsökvägen för att ladda dokumentet från. |
|
|  | options | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) | Ytterligare alternativ att använda vid inläsning av ett dokument. |
|

### Watermarker(String filePath, WatermarkerSettings settings) {#Watermarker-java.lang.String-com.groupdocs.watermark.WatermarkerSettings-}
```
public Watermarker(String filePath, WatermarkerSettings settings)
```


Initierar en ny instans av klassen `[Watermarker](../../com.groupdocs.watermark/watermarker)` med den angivna dokumentvägen och inställningarna.

Läs mer om att ladda dokument:
[Loading documents](../https://docs.groupdocs.com/display/watermarkjava/Loading+documents).

Följande exempel visar hur man ställer in sökbara objekt globalt (för alla dokument som
kommer att laddas efter det).
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filePath | java.lang.String | Filsökvägen för att ladda dokumentet från. |
|
|  | settings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) | Ytterligare inställningar att använda när man arbetar med ett inläst dokument. |
|

### Watermarker(String filePath, LoadOptions options, WatermarkerSettings settings) {#Watermarker-java.lang.String-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-}
```
public Watermarker(String filePath, LoadOptions options, WatermarkerSettings settings)
```


Initierar en ny instans av klassen `[Watermarker](../../com.groupdocs.watermark/watermarker)` med den angivna dokumentvägen, laddningsalternativen och inställningarna.

Läs mer om att ladda dokument:
[Loading documents](../https://docs.groupdocs.com/display/watermarknet/Loading+documents).

Följande exempel visar hur man hittar specifika textfragment i e-postmeddelandets brödtext/ämne.
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filePath | java.lang.String | Filsökvägen för att ladda dokumentet från. |
|
|  | options | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) | Ytterligare alternativ att använda vid inläsning av ett dokument. |
|
|  | settings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) | Ytterligare inställningar att använda när man arbetar med ett inläst dokument. |
|

### Watermarker(InputStream document) {#Watermarker-java.io.InputStream-}
```
public Watermarker(InputStream document)
```


Initierar en ny instans av klassen `[Watermarker](../../com.groupdocs.watermark/watermarker)` med den angivna strömmen.

Läs mer om att ladda dokument:
[Loading documents](../https://docs.groupdocs.com/display/watermarknet/Loading+documents).

Följande exempel visar hur man laddar och sparar ett dokument i vilket som helst stödd format.
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | dokument | java.io.InputStream | Strömmen att ladda dokumentet från. |
|

### Watermarker(InputStream document, LoadOptions options) {#Watermarker-java.io.InputStream-com.groupdocs.watermark.options.LoadOptions-}
```
public Watermarker(InputStream document, LoadOptions options)
```


Initierar en ny instans av klassen `[Watermarker](../../com.groupdocs.watermark/watermarker)` med den angivna strömmen och laddningsalternativen.

Läs mer om att ladda dokument:
[Loading documents](../https://docs.groupdocs.com/display/watermarknet/Loading+documents).

Följande exempel visar hur man laddar ett krypterat PDF-dokument med lösenord
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | dokument | java.io.InputStream | Strömmen att ladda dokumentet från. |
|
|  | options | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) | Ytterligare alternativ att använda vid inläsning av ett dokument. |
|

### Watermarker(InputStream document, WatermarkerSettings settings) {#Watermarker-java.io.InputStream-com.groupdocs.watermark.WatermarkerSettings-}
```
public Watermarker(InputStream document, WatermarkerSettings settings)
```


Initierar en ny instans av klassen `[Watermarker](../../com.groupdocs.watermark/watermarker)` med den angivna strömmen och inställningarna.

Läs mer om att ladda dokument:
[Loading documents](../https://docs.groupdocs.com/display/watermarknet/Loading+documents).

Följande exempel visar hur man ställer in sökbara objekt globalt (för alla dokument som
kommer att laddas efter det).
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | dokument | java.io.InputStream | Strömmen att ladda dokumentet från. |
|
|  | settings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) | Ytterligare inställningar att använda när man arbetar med ett inläst dokument. |
|

### Watermarker(InputStream document, LoadOptions options, WatermarkerSettings settings) {#Watermarker-java.io.InputStream-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-}
```
public Watermarker(InputStream document, LoadOptions options, WatermarkerSettings settings)
```


Initierar en ny instans av klassen med den angivna strömmen, laddningsalternativen och inställningarna.

Läs mer om att ladda dokument:
[Loading documents](../https://docs.groupdocs.com/display/watermarknet/Loading+documents).

Följande exempel visar hur man ställer in sökbara objekt globalt (för alla dokument som
kommer att laddas efter det).
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | dokument | java.io.InputStream | Strömmen att ladda dokumentet från. |
|
|  | options | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) | Ytterligare alternativ att använda vid inläsning av ett dokument. |
|
|  | settings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) | Ytterligare inställningar att använda när man arbetar med ett inläst dokument. |
|

### Watermarker(System.IO.Stream document, LoadOptions options, WatermarkerSettings settings) {#Watermarker-com.aspose.ms.System.IO.Stream-com.groupdocs.watermark.options.LoadOptions-com.groupdocs.watermark.WatermarkerSettings-}
```
public Watermarker(System.IO.Stream document, LoadOptions options, WatermarkerSettings settings)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dokument | com.aspose.ms.System.IO.Stream |  |
| options | [LoadOptions](../../com.groupdocs.watermark.options/loadoptions) |  |
| settings | [WatermarkerSettings](../../com.groupdocs.watermark/watermarkersettings) |  |

### getSearchableObjects() {#getSearchableObjects--}
```
public final SearchableObjects getSearchableObjects()
```


Hämtar innehållsobjekten som ska inkluderas i en vattenstämpelsökning.

Denna metod specificerar också innehållsobjekt som används i bildsökning.
För mer information se `#search(SearchCriteria).search(SearchCriteria)`
och `#getImages().getImages()`-metoderna.

Läs mer om att söka vattenmärken:
[Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks).

Följande exempel visar hur man tar bort alla XObjects och Artefakter från ett PDF-dokument.
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


Ställer in innehållsobjekten som ska inkluderas i en vattenstämpelsökning.

Denna metod specificerar också innehållsobjekt som används i bildsökning.
För mer information se `#search(SearchCriteria).search(SearchCriteria)`
och `#getImages().getImages()`-metoderna.
Läs mer om att söka vattenmärken:
[Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks).

Följande exempel visar hur man tar bort alla XObjects och Artefakter från ett PDF-dokument.
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | [SearchableObjects](../../com.groupdocs.watermark.search/searchableobjects) | Objekten som ska inkluderas i en vattenmärkesökning. |
|

### dispose() {#dispose--}
```
public final void dispose()
```




### close() {#close--}
```
public final void close()
```


Avslutar den aktuella instansen.


### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


Hämtar information om formatet för det laddade dokumentet.

Läs mer om att hämta dokumentinformation
[Get document info](../https://docs.groupdocs.com/display/watermarkjava/Get+document+info).

Följande exempel visar hur man får information om ett dokument av vilken som helst stödjande typ.
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


Lägger till en vattenstämpel i det laddade dokumentet.

Läs mer om att lägga till vattenmärken:
[Adding watermarks](../https://docs.groupdocs.com/display/watermarkjava/Adding+watermarks).

Följande exempel visar hur man lägger till bild- och textvattenmärke i ett dokument av vilken som helst stödjande typ.
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | watermark | [Watermark](../../com.groupdocs.watermark/watermark) | Vattenmärket att lägga till i dokumentet. |
|

### add(Watermark watermark, WatermarkOptions options) {#add-com.groupdocs.watermark.Watermark-com.groupdocs.watermark.options.WatermarkOptions-}
```
public final void add(Watermark watermark, WatermarkOptions options)
```


Lägger till en vattenstämpel i det laddade dokumentet med hjälp av vattenstämpelalternativ.

Läs mer om att lägga till vattenmärken:
[Adding watermarks](../https://docs.groupdocs.com/display/watermarkjava/Adding+watermarks).

Följande exempel visar hur man lägger till ett bildvattenmärke på en specifik sida i ett PDF-dokument.
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | watermark | [Watermark](../../com.groupdocs.watermark/watermark) | Vattenmärket att lägga till i dokumentet. |
|
|  | options | [WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions) | Ytterligare alternativ att använda när vattenmärket läggs till. |
|

### remove(PossibleWatermark possibleWatermark) {#remove-com.groupdocs.watermark.search.PossibleWatermark-}
```
public final void remove(PossibleWatermark possibleWatermark)
```


Tar bort vattenstämpel från dokumentet.

Läs mer om att ta bort vattenmärken:
[Removing found watermarks](../https://docs.groupdocs.com/display/watermarkjava/Removing+found+watermarks).

Följande exempel visar hur man hittar och tar bort det första möjliga vattenmärket som innehåller särskilt
text eller bild från ett dokument av vilken som helst stödjande typ.
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | possibleWatermark | [PossibleWatermark](../../com.groupdocs.watermark.search/possiblewatermark) | Vattenmärket att ta bort. |
|

### remove(PossibleWatermarkCollection possibleWatermarks) {#remove-com.groupdocs.watermark.search.PossibleWatermarkCollection-}
```
public final void remove(PossibleWatermarkCollection possibleWatermarks)
```


Tar bort alla vattenstämplar i samlingen från dokumentet.

Läs mer om att ta bort vattenmärken:
[Removing found watermarks](../https://docs.groupdocs.com/display/watermarkjava/Removing+found+watermarks).

Följande exempel visar hur man hittar och tar bort alla möjliga vattenmärken som innehåller särskilt
text eller bild från ett dokument av vilken som helst stödjande typ.
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | possibleWatermarks | [PossibleWatermarkCollection](../../com.groupdocs.watermark.search/possiblewatermarkcollection) | Samlingen av vattenmärken att ta bort. |
|

### save(String filePath) {#save-java.lang.String-}
```
public final void save(String filePath)
```


Sparar dokumentet till den angivna filplatsen.

Läs mer om att spara dokumenten
[Saving documents](../https://docs.groupdocs.com/display/watermarkjava/Saving+documents).

Följande exempel visar hur man lägger till vattenmärket och sparar dokumentet till en annan fil.
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filePath | java.lang.String | Filvägen för att spara dokumentdata till. |
|

### save(OutputStream document) {#save-java.io.OutputStream-}
```
public final void save(OutputStream document)
```


Sparar dokumentet till den angivna strömmen.

Läs mer om att spara dokumenten
[Saving documents](../https://docs.groupdocs.com/display/watermarkjava/Saving+documents).

Följande exempel visar hur man lägger till en vattenstämpel och sparar dokumentet till minnesströmmen.
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | dokument | java.io.OutputStream | Strömmen för att spara dokumentdata till. |
|

### save(String filePath, SaveOptions options) {#save-java.lang.String-com.groupdocs.watermark.options.SaveOptions-}
```
public final void save(String filePath, SaveOptions options)
```


Sparar dokumentet till den angivna filplatsen med sparalternativ.

Läs mer om att spara dokumenten
[Saving documents](../https://docs.groupdocs.com/display/watermarkjava/Saving+documents).

Följande exempel visar hur man lägger till vattenstämpeln och sparar dokumentet till en annan fil
med standard `[SaveOptions](../../com.groupdocs.watermark.options/saveoptions)`.
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filePath | java.lang.String | Filvägen för att spara dokumentdata till. |
|
|  | options | [SaveOptions](../../com.groupdocs.watermark.options/saveoptions) | Ytterligare alternativ att använda när ett dokument sparas. |
|

### save(OutputStream document, SaveOptions options) {#save-java.io.OutputStream-com.groupdocs.watermark.options.SaveOptions-}
```
public final void save(OutputStream document, SaveOptions options)
```


Sparar dokumentet till den angivna strömmen med sparalternativ.

Läs mer om att spara dokumenten
[Saving documents](../https://docs.groupdocs.com/display/watermarkjava/Saving+documents).

Följande exempel visar hur man lägger till vattenstämpel och sparar dokumentet till minnesströmmen
med standard `[SaveOptions](../../com.groupdocs.watermark.options/saveoptions)`.
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | dokument | java.io.OutputStream | Strömmen för att spara dokumentdata till. |
|
|  | options | [SaveOptions](../../com.groupdocs.watermark.options/saveoptions) | Ytterligare alternativ att använda när ett dokument sparas. |
|

### generatePreview(PreviewOptions previewOptions) {#generatePreview-com.groupdocs.watermark.options.PreviewOptions-}
```
public final void generatePreview(PreviewOptions previewOptions)
```


Skapar förhandsgranskningsbilder för dokumentet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | previewOptions | [PreviewOptions](../../com.groupdocs.watermark.options/previewoptions) | Ytterligare alternativ att använda vid generering av förhandsgranskningsbilder. |
|

### search() {#search--}
```
public final PossibleWatermarkCollection search()
```


Söker efter alla möjliga vattenmärken i dokumentet.

Sökningen utförs i objekt som specificerats med `#setSearchableObjects(SearchableObjects).setSearchableObjects(SearchableObjects)`.

Läs mer om att söka efter vattenstämplar
[Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks).

Följande exempel visar hur man räknar möjliga vattenstämplar i ett dokument av vilken som helst stödjande typ.
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


Söker möjliga vattenmärken enligt angivna sökkriterier.

Sökningen utförs i objekt som specificerats med `#setSearchableObjects(SearchableObjects).setSearchableObjects(SearchableObjects)`.

Läs mer om att söka efter vattenstämplar
[Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks).

Följande exempel visar hur man hittar och tar bort alla möjliga vattenstämplar som innehåller specifik text
eller bild från ett dokument av vilken som helst stödjande typ.
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | searchCriteria | [SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria) | Sök kriterier att använda. |
|

**Returns:**
[PossibleWatermarkCollection](../../com.groupdocs.watermark.search/possiblewatermarkcollection)
### getImages(ImageSearchCriteria searchCriteria) {#getImages-com.groupdocs.watermark.search.ImageSearchCriteria-}
```
public final WatermarkableImageCollection getImages(ImageSearchCriteria searchCriteria)
```


Hittar bilder enligt angivna sökkriterier.

Sökningen utförs i objekt som specificerats med `#setSearchableObjects(SearchableObjects).setSearchableObjects(SearchableObjects)`.

Läs mer om att söka efter vattenstämplar
[Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks).

Följande exempel visar hur man tar bort alla bilder som liknar referensen
från ett dokument av vilken som helst stödjande typ.
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | searchCriteria | [ImageSearchCriteria](../../com.groupdocs.watermark.search/imagesearchcriteria) | Sök kriterier att använda. |
|

**Returns:**
[WatermarkableImageCollection](../../com.groupdocs.watermark.contents/watermarkableimagecollection)
### getImages() {#getImages--}
```
public final WatermarkableImageCollection getImages()
```


Hittar alla bilder i dokumentet.

Sökningen utförs i objekt som specificerats med `#setSearchableObjects(SearchableObjects).setSearchableObjects(SearchableObjects)`.

Läs mer om att söka efter vattenstämplar
[Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks).

Följande exempel visar hur man lägger till vattenstämpel på alla bilder i ett dokument av vilken som helst stödjande typ.
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


Returnerar `[Content](../../com.groupdocs.watermark.contents/content)`-objektet för det inlästa dokumentet.

Följande exempel visar hur man rasteriserar en PDF-dokumentsida med tillagd vattenstämpel.
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | contentType | java.lang.Class<T> | Den begärda typen av ett `[Content](../../com.groupdocs.watermark.contents/content)`-objekt. |
|

**Returns:**
T - Det `[Content](../../com.groupdocs.watermark.contents/content)`-objektet för det inlästa dokumentet.

