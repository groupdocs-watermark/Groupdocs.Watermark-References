---
title: "ImageThumbnailSearchCriteria"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt Suchkriterien zum Finden von Bildern in einem Inhalt dar."
type: docs
weight: 33
url: /de/java/com.groupdocs.watermark.search/imagethumbnailsearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria), [com.groupdocs.watermark.search.PageSearchCriteria](../../com.groupdocs.watermark.search/pagesearchcriteria), [com.groupdocs.watermark.search.ImageSearchCriteria](../../com.groupdocs.watermark.search/imagesearchcriteria)
```
public class ImageThumbnailSearchCriteria extends ImageSearchCriteria
```

Stellt Suchkriterien zum Finden von Bildern in einem Inhalt dar.

<br />

*** ** * ** ***

Dieses Suchkriterium verwendet ein binarisiertes Bild-Thumbnail zur Berechnung der Bildähnlichkeit.

<br />


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [ImageThumbnailSearchCriteria(String filePath)](#ImageThumbnailSearchCriteria-java.lang.String-) | Initialisiert eine neue Instanz der Klasse `[ImageThumbnailSearchCriteria](../../com.groupdocs.watermark.search/imagethumbnailsearchcriteria)` mit einem angegebenen Dateipfad. |
|
|  | [ImageThumbnailSearchCriteria(InputStream stream)](#ImageThumbnailSearchCriteria-java.io.InputStream-) | Initialisiert eine neue Instanz der Klasse `[ImageThumbnailSearchCriteria](../../com.groupdocs.watermark.search/imagethumbnailsearchcriteria)` mit einem angegebenen Stream. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getThumbnailSize()](#getThumbnailSize--) | Ermittelt die Thumbnail-Größe. |
|
|  | [setThumbnailSize(byte value)](#setThumbnailSize-byte-) | Setzt die Thumbnail-Größe. |
|
### ImageThumbnailSearchCriteria(String filePath) {#ImageThumbnailSearchCriteria-java.lang.String-}
```
public ImageThumbnailSearchCriteria(String filePath)
```


Initialisiert eine neue Instanz der Klasse `[ImageThumbnailSearchCriteria](../../com.groupdocs.watermark.search/imagethumbnailsearchcriteria)` mit einem angegebenen Dateipfad.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | filePath | java.lang.String | Der Dateipfad, von dem das Bild geladen wird. |
|

### ImageThumbnailSearchCriteria(InputStream stream) {#ImageThumbnailSearchCriteria-java.io.InputStream-}
```
public ImageThumbnailSearchCriteria(InputStream stream)
```


Initialisiert eine neue Instanz der Klasse `[ImageThumbnailSearchCriteria](../../com.groupdocs.watermark.search/imagethumbnailsearchcriteria)` mit einem angegebenen Stream.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | stream | java.io.InputStream | Der Stream, von dem das Bild geladen wird. |
|

### getThumbnailSize() {#getThumbnailSize--}
```
public final byte getThumbnailSize()
```


Ermittelt die Thumbnail-Größe.


**Returns:**
byte - Standardmäßig wird ein 32X32-Vorschaubild verwendet.

### setThumbnailSize(byte value) {#setThumbnailSize-byte-}
```
public final void setThumbnailSize(byte value)
```


Setzt die Thumbnail-Größe.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | byte | Standardmäßig wird ein 32X32-Vorschaubild verwendet. |
|

