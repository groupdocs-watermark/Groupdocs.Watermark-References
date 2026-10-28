---
title: "PdfArtifactWatermarkOptions"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Rappresenta le opzioni di aggiunta della filigrana quando si aggiunge una filigrana di artefatto a un documento PDF."
type: docs
weight: 29
url: /it/java/com.groupdocs.watermark.options/pdfartifactwatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.PdfWatermarkOptions](../../com.groupdocs.watermark.options/pdfwatermarkoptions)
```
public final class PdfArtifactWatermarkOptions extends PdfWatermarkOptions
```

Rappresenta le opzioni di aggiunta della filigrana quando si aggiunge una filigrana di artefatto a un documento PDF.

**Leran more:**

* [Add watermarks to PDF documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+PDF+documents)

Il seguente esempio dimostra come aggiungere un watermark immagine artifact a un documento PDF.
>
> ````
> ```
>
>    PdfLoadOptions loadOptions = new PdfLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.pdf", loadOptions);
>
>    ImageWatermark watermark = new ImageWatermark("D:\\icon.png");
>
>    PdfArtifactWatermarkOptions options = new PdfArtifactWatermarkOptions();
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
|  | [PdfArtifactWatermarkOptions()](#PdfArtifactWatermarkOptions--) | Inizializza una nuova istanza della classe `[PdfArtifactWatermarkOptions](../../com.groupdocs.watermark.options/pdfartifactwatermarkoptions)`. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getPageIndex()](#getPageIndex--) | Ottiene l'indice della pagina a cui aggiungere il watermark. |
|
|  | [setPageIndex(int value)](#setPageIndex-int-) | Imposta l'indice della pagina a cui aggiungere il watermark. |
|
### PdfArtifactWatermarkOptions() {#PdfArtifactWatermarkOptions--}
```
public PdfArtifactWatermarkOptions()
```


Inizializza una nuova istanza della classe `[PdfArtifactWatermarkOptions](../../com.groupdocs.watermark.options/pdfartifactwatermarkoptions)`.


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

