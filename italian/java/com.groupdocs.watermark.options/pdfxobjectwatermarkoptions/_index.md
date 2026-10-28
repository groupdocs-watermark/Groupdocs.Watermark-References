---
title: "PdfXObjectWatermarkOptions"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Rappresenta le opzioni di aggiunta della filigrana quando si aggiunge una filigrana XObject a un documento PDF."
type: docs
weight: 34
url: /it/java/com.groupdocs.watermark.options/pdfxobjectwatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.PdfWatermarkOptions](../../com.groupdocs.watermark.options/pdfwatermarkoptions)
```
public final class PdfXObjectWatermarkOptions extends PdfWatermarkOptions
```

Rappresenta le opzioni di aggiunta della filigrana quando si aggiunge una filigrana XObject a un documento PDF.

**Learn more:**

* [Add watermarks to PDF documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+PDF+documents)

Il seguente esempio dimostra come aggiungere un watermark a una pagina specifica di un documento pdf.
>
> ````
> ```
>
>    PdfLoadOptions loadOptions = new PdfLoadOptions();
>    Watermarker watermarker = new Watermarker("C:\\doc.pdf", loadOptions);
>
>    ImageWatermark watermark = new ImageWatermark("C:\\watermark.png");
>
>    PdfXObjectWatermarkOptions options = new PdfXObjectWatermarkOptions();
>    options.setPageIndex(0);
>
>    watermarker.add(watermark, options);
>    watermarker.save("C:\\watermarked_doc.pdf");
>    watermark.close();
>    watermarker.close();
>  
> ```
> ````


## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [PdfXObjectWatermarkOptions()](#PdfXObjectWatermarkOptions--) | Inizializza una nuova istanza della classe `[PdfXObjectWatermarkOptions](../../com.groupdocs.watermark.options/pdfxobjectwatermarkoptions)`. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getPageIndex()](#getPageIndex--) | Ottiene l'indice della pagina a cui aggiungere il watermark. |
|
|  | [setPageIndex(int value)](#setPageIndex-int-) | Imposta l'indice della pagina a cui aggiungere il watermark. |
|
### PdfXObjectWatermarkOptions() {#PdfXObjectWatermarkOptions--}
```
public PdfXObjectWatermarkOptions()
```


Inizializza una nuova istanza della classe `[PdfXObjectWatermarkOptions](../../com.groupdocs.watermark.options/pdfxobjectwatermarkoptions)`.


### getPageIndex() {#getPageIndex--}
```
public final int getPageIndex()
```


Ottiene l'indice della pagina a cui aggiungere il watermark.


**Returns:**
int - L'indice della pagina a cui aggiungere il watermark.

### setPageIndex(int value) {#setPageIndex-int-}
```
public final void setPageIndex(int value)
```


Imposta l'indice della pagina a cui aggiungere il watermark.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | int | L'indice della pagina a cui aggiungere il watermark. |
|

