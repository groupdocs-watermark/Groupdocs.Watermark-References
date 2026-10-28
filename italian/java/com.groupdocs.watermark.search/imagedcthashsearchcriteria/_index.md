---
title: "ImageDctHashSearchCriteria"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Rappresenta un criterio di ricerca per trovare immagini in un documento."
type: docs
weight: 31
url: /it/java/com.groupdocs.watermark.search/imagedcthashsearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria), [com.groupdocs.watermark.search.PageSearchCriteria](../../com.groupdocs.watermark.search/pagesearchcriteria), [com.groupdocs.watermark.search.ImageSearchCriteria](../../com.groupdocs.watermark.search/imagesearchcriteria)
```
public class ImageDctHashSearchCriteria extends ImageSearchCriteria
```

Rappresenta un criterio di ricerca per trovare immagini in un documento.

Questo criterio di ricerca utilizza hash immagine percettivo basato su DCT per calcolare la somiglianza delle immagini.

**Learn more:**

* [Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks)

Il seguente esempio dimostra come cercare immagini nei file allegati (pdf).
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


## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [ImageDctHashSearchCriteria(String filePath)](#ImageDctHashSearchCriteria-java.lang.String-) | Inizializza una nuova istanza della classe `[ImageDctHashSearchCriteria](../../com.groupdocs.watermark.search/imagedcthashsearchcriteria)` con un percorso file specificato. |
|
|  | [ImageDctHashSearchCriteria(InputStream stream)](#ImageDctHashSearchCriteria-java.io.InputStream-) | Inizializza una nuova istanza della classe `[ImageDctHashSearchCriteria](../../com.groupdocs.watermark.search/imagedcthashsearchcriteria)` con uno stream specificato. |
|
| [ImageDctHashSearchCriteria(System.IO.Stream stream)](#ImageDctHashSearchCriteria-com.aspose.ms.System.IO.Stream-) |  |
### ImageDctHashSearchCriteria(String filePath) {#ImageDctHashSearchCriteria-java.lang.String-}
```
public ImageDctHashSearchCriteria(String filePath)
```


Inizializza una nuova istanza della classe `[ImageDctHashSearchCriteria](../../com.groupdocs.watermark.search/imagedcthashsearchcriteria)` con un percorso file specificato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | filePath | java.lang.String | Il percorso del file da cui caricare l'immagine. |
|

### ImageDctHashSearchCriteria(InputStream stream) {#ImageDctHashSearchCriteria-java.io.InputStream-}
```
public ImageDctHashSearchCriteria(InputStream stream)
```


Inizializza una nuova istanza della classe `[ImageDctHashSearchCriteria](../../com.groupdocs.watermark.search/imagedcthashsearchcriteria)` con uno stream specificato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | stream | java.io.InputStream | Il flusso da cui caricare l'immagine. |
|

### ImageDctHashSearchCriteria(System.IO.Stream stream) {#ImageDctHashSearchCriteria-com.aspose.ms.System.IO.Stream-}
```
public ImageDctHashSearchCriteria(System.IO.Stream stream)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

