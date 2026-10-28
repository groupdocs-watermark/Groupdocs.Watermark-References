---
title: "ImageColorHistogramSearchCriteria"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Rappresenta i criteri di ricerca per trovare immagini in un contenuto."
type: docs
weight: 30
url: /it/java/com.groupdocs.watermark.search/imagecolorhistogramsearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria), [com.groupdocs.watermark.search.PageSearchCriteria](../../com.groupdocs.watermark.search/pagesearchcriteria), [com.groupdocs.watermark.search.ImageSearchCriteria](../../com.groupdocs.watermark.search/imagesearchcriteria)
```
public class ImageColorHistogramSearchCriteria extends ImageSearchCriteria
```

Rappresenta i criteri di ricerca per trovare immagini in un contenuto.

<br />

*** ** * ** ***

Questo criterio di ricerca utilizza gli istogrammi di colore dell'immagine per calcolare la similarità delle immagini.

<br />


## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [ImageColorHistogramSearchCriteria(String filePath)](#ImageColorHistogramSearchCriteria-java.lang.String-) | Inizializza una nuova istanza della classe `[ImageColorHistogramSearchCriteria](../../com.groupdocs.watermark.search/imagecolorhistogramsearchcriteria)` con un percorso file specificato. |
|
|  | [ImageColorHistogramSearchCriteria(InputStream stream)](#ImageColorHistogramSearchCriteria-java.io.InputStream-) | Inizializza una nuova istanza della classe `[ImageColorHistogramSearchCriteria](../../com.groupdocs.watermark.search/imagecolorhistogramsearchcriteria)` con uno stream specificato. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getBinsCount()](#getBinsCount--) | Restituisce il numero di bin che verranno usati per costruire gli istogrammi di colore. |
|
|  | [setBinsCount(byte value)](#setBinsCount-byte-) | Imposta il numero di bin che verranno usati per costruire gli istogrammi di colore. |
|
### ImageColorHistogramSearchCriteria(String filePath) {#ImageColorHistogramSearchCriteria-java.lang.String-}
```
public ImageColorHistogramSearchCriteria(String filePath)
```


Inizializza una nuova istanza della classe `[ImageColorHistogramSearchCriteria](../../com.groupdocs.watermark.search/imagecolorhistogramsearchcriteria)` con un percorso file specificato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | filePath | java.lang.String | Il percorso del file da cui caricare l'immagine. |
|

### ImageColorHistogramSearchCriteria(InputStream stream) {#ImageColorHistogramSearchCriteria-java.io.InputStream-}
```
public ImageColorHistogramSearchCriteria(InputStream stream)
```


Inizializza una nuova istanza della classe `[ImageColorHistogramSearchCriteria](../../com.groupdocs.watermark.search/imagecolorhistogramsearchcriteria)` con uno stream specificato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | stream | java.io.InputStream | Il flusso da cui caricare l'immagine. |
|

### getBinsCount() {#getBinsCount--}
```
public final byte getBinsCount()
```


Restituisce il numero di bin che verranno usati per costruire gli istogrammi di colore.


**Returns:**
byte - Il valore predefinito è 10.

### setBinsCount(byte value) {#setBinsCount-byte-}
```
public final void setBinsCount(byte value)
```


Imposta il numero di bin che verranno usati per costruire gli istogrammi di colore.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | byte | Il valore predefinito è 10. |
|

