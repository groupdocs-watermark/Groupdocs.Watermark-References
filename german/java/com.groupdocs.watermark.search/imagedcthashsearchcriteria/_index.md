---
title: "ImageDctHashSearchCriteria"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt ein Suchkriterium zum Finden von Bildern in einem Dokument dar."
type: docs
weight: 31
url: /de/java/com.groupdocs.watermark.search/imagedcthashsearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria), [com.groupdocs.watermark.search.PageSearchCriteria](../../com.groupdocs.watermark.search/pagesearchcriteria), [com.groupdocs.watermark.search.ImageSearchCriteria](../../com.groupdocs.watermark.search/imagesearchcriteria)
```
public class ImageDctHashSearchCriteria extends ImageSearchCriteria
```

Stellt ein Suchkriterium zum Finden von Bildern in einem Dokument dar.

Dieses Suchkriterium verwendet DCT‑basierten perceptual image hash zur Berechnung der Bildähnlichkeit.

**Learn more:**

* [Searching watermarks](../https://docs.groupdocs.com/display/watermarkjava/Searching+watermarks)

Das folgende Beispiel zeigt, wie man nach Bildern in den angehängten Dateien (pdf) sucht.
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


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [ImageDctHashSearchCriteria(String filePath)](#ImageDctHashSearchCriteria-java.lang.String-) | Initialisiert eine neue Instanz der `[ImageDctHashSearchCriteria](../../com.groupdocs.watermark.search/imagedcthashsearchcriteria)`‑Klasse mit einem angegebenen Dateipfad. |
|
|  | [ImageDctHashSearchCriteria(InputStream stream)](#ImageDctHashSearchCriteria-java.io.InputStream-) | Initialisiert eine neue Instanz der `[ImageDctHashSearchCriteria](../../com.groupdocs.watermark.search/imagedcthashsearchcriteria)`‑Klasse mit einem angegebenen Stream. |
|
| [ImageDctHashSearchCriteria(System.IO.Stream stream)](#ImageDctHashSearchCriteria-com.aspose.ms.System.IO.Stream-) |  |
### ImageDctHashSearchCriteria(String filePath) {#ImageDctHashSearchCriteria-java.lang.String-}
```
public ImageDctHashSearchCriteria(String filePath)
```


Initialisiert eine neue Instanz der `[ImageDctHashSearchCriteria](../../com.groupdocs.watermark.search/imagedcthashsearchcriteria)`‑Klasse mit einem angegebenen Dateipfad.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | filePath | java.lang.String | Der Dateipfad, von dem das Bild geladen wird. |
|

### ImageDctHashSearchCriteria(InputStream stream) {#ImageDctHashSearchCriteria-java.io.InputStream-}
```
public ImageDctHashSearchCriteria(InputStream stream)
```


Initialisiert eine neue Instanz der `[ImageDctHashSearchCriteria](../../com.groupdocs.watermark.search/imagedcthashsearchcriteria)`‑Klasse mit einem angegebenen Stream.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | stream | java.io.InputStream | Der Stream, von dem das Bild geladen wird. |
|

### ImageDctHashSearchCriteria(System.IO.Stream stream) {#ImageDctHashSearchCriteria-com.aspose.ms.System.IO.Stream-}
```
public ImageDctHashSearchCriteria(System.IO.Stream stream)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

