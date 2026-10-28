---
title: "PdfAnnotationWatermarkOptions"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Rappresenta le opzioni di aggiunta della filigrana quando si aggiunge una filigrana di annotazione a un documento PDF."
type: docs
weight: 28
url: /it/java/com.groupdocs.watermark.options/pdfannotationwatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.PdfWatermarkOptions](../../com.groupdocs.watermark.options/pdfwatermarkoptions)
```
public final class PdfAnnotationWatermarkOptions extends PdfWatermarkOptions
```

Rappresenta le opzioni di aggiunta della filigrana quando si aggiunge una filigrana di annotazione a un documento PDF.

**Learn more:**

* [Add watermarks to PDF documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+PDF+documents)

Il seguente esempio dimostra come aggiungere una filigrana di annotazione immagine a un documento PDF.
>
> ````
> ```
>
>    PdfLoadOptions loadOptions = new PdfLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.pdf", loadOptions);
>
>    ImageWatermark watermark = new ImageWatermark("D:\\icon.png");
>
>    PdfAnnotationWatermarkOptions options = new PdfAnnotationWatermarkOptions();
>    options.setPageIndex(-1); // default - all pages
>
>    watermarker.add(watermark, options);
>    watermarker.save("D:\\watermarked_test.pdf");
>    watermark.close();
>    watermarker.close();
>  
> ```
> ````


## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [PdfAnnotationWatermarkOptions()](#PdfAnnotationWatermarkOptions--) | Inizializza una nuova istanza della classe `[PdfAnnotationWatermarkOptions](../../com.groupdocs.watermark.options/pdfannotationwatermarkoptions)`. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getPageIndex()](#getPageIndex--) | Ottiene l'indice della pagina a cui aggiungere il watermark. |
|
|  | [setPageIndex(int value)](#setPageIndex-int-) | Imposta l'indice della pagina a cui aggiungere il watermark. |
|
|  | [getPrintOnly()](#getPrintOnly--) | Ottieni il valore che indica se l'annotazione verrà stampata, ma non visualizzata nell'applicazione di visualizzazione PDF. |
|
|  | [setPrintOnly(boolean value)](#setPrintOnly-boolean-) | Imposta il valore che indica se l'annotazione verrà stampata, ma non visualizzata nell'applicazione di visualizzazione PDF. |
|
### PdfAnnotationWatermarkOptions() {#PdfAnnotationWatermarkOptions--}
```
public PdfAnnotationWatermarkOptions()
```


Inizializza una nuova istanza della classe `[PdfAnnotationWatermarkOptions](../../com.groupdocs.watermark.options/pdfannotationwatermarkoptions)`.


### getPageIndex() {#getPageIndex--}
```
public final int getPageIndex()
```


Ottiene l'indice della pagina a cui aggiungere il watermark.


**Returns:**
int - L'indice della pagina a cui aggiungere il watermark.

<br />

*** ** * ** ***

-1 means all pages.

<br />


### setPageIndex(int value) {#setPageIndex-int-}
```
public final void setPageIndex(int value)
```


Imposta l'indice della pagina a cui aggiungere il watermark.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | int | L'indice della pagina a cui aggiungere il watermark. |

<br />

*** ** * ** ***

-1 means all pages.

<br />

|

### getPrintOnly() {#getPrintOnly--}
```
public final boolean getPrintOnly()
```


Ottieni il valore che indica se l'annotazione verrà stampata, ma non visualizzata nell'applicazione di visualizzazione PDF.


**Returns:**
boolean - Il valore che indica se l'annotazione verrà stampata, ma non visualizzata nell'applicazione di visualizzazione PDF.

### setPrintOnly(boolean value) {#setPrintOnly-boolean-}
```
public final void setPrintOnly(boolean value)
```


Imposta il valore che indica se l'annotazione verrà stampata, ma non visualizzata nell'applicazione di visualizzazione PDF.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | boolean | Il valore che indica se l'annotazione verrà stampata, ma non visualizzata nell'applicazione di visualizzazione PDF. |
|

