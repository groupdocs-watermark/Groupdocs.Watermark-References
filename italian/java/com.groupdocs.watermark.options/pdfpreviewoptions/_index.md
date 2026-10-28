---
title: "PdfPreviewOptions"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Fornisce opzioni per impostare i requisiti e i delegati di stream per la generazione dell'anteprima di un documento PDF."
type: docs
weight: 31
url: /it/java/com.groupdocs.watermark.options/pdfpreviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)
```
public class PdfPreviewOptions extends PreviewOptions
```

Fornisce opzioni per impostare i requisiti e i delegati di stream per la generazione dell'anteprima di un documento PDF.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [PdfPreviewOptions(ICreatePageStream createPageStream)](#PdfPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-) | Inizializza una nuova istanza della classe `[PdfPreviewOptions](../../com.groupdocs.watermark.options/pdfpreviewoptions)` facendo chiudere lo stream di output. |
|
|  | [PdfPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)](#PdfPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | Inizializza una nuova istanza della classe `[PdfPreviewOptions](../../com.groupdocs.watermark.options/pdfpreviewoptions)` facendo restituire lo stream di output al client per un uso successivo. |
|
## Campi

| Campo | Descrizione |
| --- | --- |
|  | [DefaultResolution](#DefaultResolution) | Risoluzione predefinita in punti per pollice. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getResolution()](#getResolution--) | Ottiene la risoluzione per le immagini generate, in punti per pollice. |
|
|  | [setResolution(int value)](#setResolution-int-) | Imposta la risoluzione per le immagini generate, in punti per pollice. |
|
### PdfPreviewOptions(ICreatePageStream createPageStream) {#PdfPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-}
```
public PdfPreviewOptions(ICreatePageStream createPageStream)
```


Inizializza una nuova istanza della classe `[PdfPreviewOptions](../../com.groupdocs.watermark.options/pdfpreviewoptions)` facendo chiudere lo stream di output.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Crea uno stream per l'anteprima di una pagina specifica. |
|

### PdfPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream) {#PdfPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public PdfPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)
```


Inizializza una nuova istanza della classe `[PdfPreviewOptions](../../com.groupdocs.watermark.options/pdfpreviewoptions)` facendo restituire lo stream di output al client per un uso successivo.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Crea uno stream per l'anteprima di una pagina specifica. |
|
|  | releasePageStream | [IReleasePageStream](../../com.groupdocs.watermark.options/ireleasepagestream) | Notifica che la generazione dell'anteprima della pagina è completata e ottiene lo stream di output. |
|

### DefaultResolution {#DefaultResolution}
```
public static final int DefaultResolution
```


Risoluzione predefinita in punti per pollice.


### getResolution() {#getResolution--}
```
public final int getResolution()
```


Ottiene la risoluzione per le immagini generate, in punti per pollice.


**Returns:**
int - La risoluzione per le immagini generate, in punti per pollice.

<br />

*** ** * ** ***

Il valore predefinito è 150.

<br />


### setResolution(int value) {#setResolution-int-}
```
public final void setResolution(int value)
```


Imposta la risoluzione per le immagini generate, in punti per pollice.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | int | La risoluzione per le immagini generate, in punti per pollice. |

<br />

*** ** * ** ***

Il valore predefinito è 150.

<br />

|

