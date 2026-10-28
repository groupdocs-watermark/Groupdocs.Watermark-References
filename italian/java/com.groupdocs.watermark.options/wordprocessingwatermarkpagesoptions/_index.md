---
title: "WordProcessingWatermarkPagesOptions"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Rappresenta le opzioni quando si aggiunge la filigrana alle pagine di un documento Word."
type: docs
weight: 76
url: /it/java/com.groupdocs.watermark.options/wordprocessingwatermarkpagesoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkBaseOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkbaseoptions)
```
public final class WordProcessingWatermarkPagesOptions extends WordProcessingWatermarkBaseOptions
```

Rappresenta le opzioni quando si aggiunge la filigrana alle pagine di un documento Word.

**Learn more:**

* [Add watermarks to word processing documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+word+processing+documents)

Il seguente esempio dimostra come aggiungere un watermark a una pagina specifica di un documento Word.
>
> ````
> ```
>
>    WordProcessingLoadOptions loadOptions = new WordProcessingLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.doc", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 14));
>
>    WordProcessingWatermarkPagesOptions options = new WordProcessingWatermarkPagesOptions();
>    options.setPageNumbers(new int[] { 1 });
>    
>    watermarker.save("D:\\watermarked_test.doc");
>    watermarker.close();
>  
> ```
> ````


## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [WordProcessingWatermarkPagesOptions()](#WordProcessingWatermarkPagesOptions--) | Inizializza una nuova istanza della classe `[WordProcessingWatermarkPagesOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkpagesoptions)`. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getPageNumbers()](#getPageNumbers--) | Ottiene i numeri di pagina a cui aggiungere il watermark. |
|
|  | [setPageNumbers(int[] value)](#setPageNumbers-int---) | Imposta i numeri di pagina a cui aggiungere il watermark. |
|
### WordProcessingWatermarkPagesOptions() {#WordProcessingWatermarkPagesOptions--}
```
public WordProcessingWatermarkPagesOptions()
```


Inizializza una nuova istanza della classe `[WordProcessingWatermarkPagesOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkpagesoptions)`.


### getPageNumbers() {#getPageNumbers--}
```
public final int[] getPageNumbers()
```


Ottiene i numeri di pagina a cui aggiungere il watermark.


**Returns:**
int[] - I numeri di pagina a cui aggiungere il watermark.

<br />

*** ** * ** ***

Tutti i numeri devono essere maggiori o uguali a 1. Questa proprietà è utilizzata solo quando si aggiunge il watermark a un documento. Se questo valore è  null  o vuoto, il watermark viene aggiunto a tutte le pagine.

<br />


### setPageNumbers(int[] value) {#setPageNumbers-int---}
```
public final void setPageNumbers(int[] value)
```


Imposta i numeri di pagina a cui aggiungere il watermark.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | int[] | I numeri di pagina a cui aggiungere il watermark. |

<br />

*** ** * ** ***

Tutti i numeri devono essere maggiori o uguali a 1. Questa proprietà è utilizzata solo quando si aggiunge il watermark a un documento. Se questo valore è  null  o vuoto, il watermark viene aggiunto a tutte le pagine.

<br />

|

