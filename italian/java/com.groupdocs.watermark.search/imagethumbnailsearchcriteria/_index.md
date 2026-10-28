---
title: "ImageThumbnailSearchCriteria"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Rappresenta i criteri di ricerca per trovare immagini in un contenuto."
type: docs
weight: 33
url: /it/java/com.groupdocs.watermark.search/imagethumbnailsearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria), [com.groupdocs.watermark.search.PageSearchCriteria](../../com.groupdocs.watermark.search/pagesearchcriteria), [com.groupdocs.watermark.search.ImageSearchCriteria](../../com.groupdocs.watermark.search/imagesearchcriteria)
```
public class ImageThumbnailSearchCriteria extends ImageSearchCriteria
```

Rappresenta i criteri di ricerca per trovare immagini in un contenuto.

<br />

*** ** * ** ***

Questo criterio di ricerca utilizza una miniatura binarizzata dell'immagine per calcolare la somiglianza delle immagini.

<br />


## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [ImageThumbnailSearchCriteria(String filePath)](#ImageThumbnailSearchCriteria-java.lang.String-) | Inizializza una nuova istanza della classe `[ImageThumbnailSearchCriteria](../../com.groupdocs.watermark.search/imagethumbnailsearchcriteria)` con un percorso file specificato. |
|
|  | [ImageThumbnailSearchCriteria(InputStream stream)](#ImageThumbnailSearchCriteria-java.io.InputStream-) | Inizializza una nuova istanza della classe `[ImageThumbnailSearchCriteria](../../com.groupdocs.watermark.search/imagethumbnailsearchcriteria)` con uno stream specificato. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getThumbnailSize()](#getThumbnailSize--) | Restituisce la dimensione della miniatura. |
|
|  | [setThumbnailSize(byte value)](#setThumbnailSize-byte-) | Imposta la dimensione della miniatura. |
|
### ImageThumbnailSearchCriteria(String filePath) {#ImageThumbnailSearchCriteria-java.lang.String-}
```
public ImageThumbnailSearchCriteria(String filePath)
```


Inizializza una nuova istanza della classe `[ImageThumbnailSearchCriteria](../../com.groupdocs.watermark.search/imagethumbnailsearchcriteria)` con un percorso file specificato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | filePath | java.lang.String | Il percorso del file da cui caricare l'immagine. |
|

### ImageThumbnailSearchCriteria(InputStream stream) {#ImageThumbnailSearchCriteria-java.io.InputStream-}
```
public ImageThumbnailSearchCriteria(InputStream stream)
```


Inizializza una nuova istanza della classe `[ImageThumbnailSearchCriteria](../../com.groupdocs.watermark.search/imagethumbnailsearchcriteria)` con uno stream specificato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | stream | java.io.InputStream | Il flusso da cui caricare l'immagine. |
|

### getThumbnailSize() {#getThumbnailSize--}
```
public final byte getThumbnailSize()
```


Restituisce la dimensione della miniatura.


**Returns:**
byte - Per impostazione predefinita verrà utilizzata una miniatura 32X32.

### setThumbnailSize(byte value) {#setThumbnailSize-byte-}
```
public final void setThumbnailSize(byte value)
```


Imposta la dimensione della miniatura.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | byte | Per impostazione predefinita verrà utilizzata una miniatura 32X32. |
|

