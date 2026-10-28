---
title: "ImageThumbnailSearchCriteria"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: "Stelt zoekcriteria voor het vinden van afbeeldingen in een inhoud voor."
type: docs
weight: 33
url: /nl/java/com.groupdocs.watermark.search/imagethumbnailsearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria), [com.groupdocs.watermark.search.PageSearchCriteria](../../com.groupdocs.watermark.search/pagesearchcriteria), [com.groupdocs.watermark.search.ImageSearchCriteria](../../com.groupdocs.watermark.search/imagesearchcriteria)
```
public class ImageThumbnailSearchCriteria extends ImageSearchCriteria
```

Stelt zoekcriteria voor het vinden van afbeeldingen in een inhoud voor.

<br />

*** ** * ** ***

Dit zoekcriterium gebruikt een binair gemaakte miniatuurafbeelding voor het berekenen van afbeeldingsgelijkenis.

<br />


## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [ImageThumbnailSearchCriteria(String filePath)](#ImageThumbnailSearchCriteria-java.lang.String-) | Initialiseert een nieuw exemplaar van de klasse `[ImageThumbnailSearchCriteria](../../com.groupdocs.watermark.search/imagethumbnailsearchcriteria)` met een opgegeven bestandspad. |
|
|  | [ImageThumbnailSearchCriteria(InputStream stream)](#ImageThumbnailSearchCriteria-java.io.InputStream-) | Initialiseert een nieuw exemplaar van de klasse `[ImageThumbnailSearchCriteria](../../com.groupdocs.watermark.search/imagethumbnailsearchcriteria)` met een opgegeven stream. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getThumbnailSize()](#getThumbnailSize--) | Haalt de miniatuurgrootte op. |
|
|  | [setThumbnailSize(byte value)](#setThumbnailSize-byte-) | Stelt de miniatuurgrootte in. |
|
### ImageThumbnailSearchCriteria(String filePath) {#ImageThumbnailSearchCriteria-java.lang.String-}
```
public ImageThumbnailSearchCriteria(String filePath)
```


Initialiseert een nieuw exemplaar van de klasse `[ImageThumbnailSearchCriteria](../../com.groupdocs.watermark.search/imagethumbnailsearchcriteria)` met een opgegeven bestandspad.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePath | java.lang.String | Het bestandspad om de afbeelding van te laden. |
|

### ImageThumbnailSearchCriteria(InputStream stream) {#ImageThumbnailSearchCriteria-java.io.InputStream-}
```
public ImageThumbnailSearchCriteria(InputStream stream)
```


Initialiseert een nieuw exemplaar van de klasse `[ImageThumbnailSearchCriteria](../../com.groupdocs.watermark.search/imagethumbnailsearchcriteria)` met een opgegeven stream.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | stream | java.io.InputStream | De stream om de afbeelding van te laden. |
|

### getThumbnailSize() {#getThumbnailSize--}
```
public final byte getThumbnailSize()
```


Haalt de miniatuurgrootte op.


**Returns:**
byte - Standaard wordt een 32X32 miniatuur gebruikt.

### setThumbnailSize(byte value) {#setThumbnailSize-byte-}
```
public final void setThumbnailSize(byte value)
```


Stelt de miniatuurgrootte in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | byte | Standaard wordt een 32X32 miniatuur gebruikt. |
|

