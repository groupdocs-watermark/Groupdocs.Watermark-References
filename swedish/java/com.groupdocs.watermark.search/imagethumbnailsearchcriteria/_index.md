---
title: "ImageThumbnailSearchCriteria"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Representerar sökkriterier för att hitta bilder i ett innehåll."
type: docs
weight: 33
url: /sv/java/com.groupdocs.watermark.search/imagethumbnailsearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria), [com.groupdocs.watermark.search.PageSearchCriteria](../../com.groupdocs.watermark.search/pagesearchcriteria), [com.groupdocs.watermark.search.ImageSearchCriteria](../../com.groupdocs.watermark.search/imagesearchcriteria)
```
public class ImageThumbnailSearchCriteria extends ImageSearchCriteria
```

Representerar sökkriterier för att hitta bilder i ett innehåll.

<br />

*** ** * ** ***

Detta sökkriterium använder en binäriserad bildminiatyr för att beräkna bildlikhet.

<br />


## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [ImageThumbnailSearchCriteria(String filePath)](#ImageThumbnailSearchCriteria-java.lang.String-) | Initierar en ny instans av klassen `[ImageThumbnailSearchCriteria](../../com.groupdocs.watermark.search/imagethumbnailsearchcriteria)` med en angiven filväg. |
|
|  | [ImageThumbnailSearchCriteria(InputStream stream)](#ImageThumbnailSearchCriteria-java.io.InputStream-) | Initierar en ny instans av klassen `[ImageThumbnailSearchCriteria](../../com.groupdocs.watermark.search/imagethumbnailsearchcriteria)` med en angiven ström. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getThumbnailSize()](#getThumbnailSize--) | Hämtar miniatyrstorlek. |
|
|  | [setThumbnailSize(byte value)](#setThumbnailSize-byte-) | Ställer in miniatyrstorlek. |
|
### ImageThumbnailSearchCriteria(String filePath) {#ImageThumbnailSearchCriteria-java.lang.String-}
```
public ImageThumbnailSearchCriteria(String filePath)
```


Initierar en ny instans av klassen `[ImageThumbnailSearchCriteria](../../com.groupdocs.watermark.search/imagethumbnailsearchcriteria)` med en angiven filväg.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filePath | java.lang.String | Filsökvägen för att läsa in bilden från. |
|

### ImageThumbnailSearchCriteria(InputStream stream) {#ImageThumbnailSearchCriteria-java.io.InputStream-}
```
public ImageThumbnailSearchCriteria(InputStream stream)
```


Initierar en ny instans av klassen `[ImageThumbnailSearchCriteria](../../com.groupdocs.watermark.search/imagethumbnailsearchcriteria)` med en angiven ström.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | stream | java.io.InputStream | Strömmen för att läsa in bilden från. |
|

### getThumbnailSize() {#getThumbnailSize--}
```
public final byte getThumbnailSize()
```


Hämtar miniatyrstorlek.


**Returns:**
byte - Som standard används en 32x32 miniatyr.

### setThumbnailSize(byte value) {#setThumbnailSize-byte-}
```
public final void setThumbnailSize(byte value)
```


Ställer in miniatyrstorlek.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | byte | Som standard används en 32x32 miniatyr. |
|

