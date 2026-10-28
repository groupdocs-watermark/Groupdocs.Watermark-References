---
title: "WordProcessingPreviewOptions"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Fornisce opzioni per impostare i requisiti e i delegati di flusso per la generazione dell'anteprima di un documento WordProcessing."
type: docs
weight: 69
url: /it/java/com.groupdocs.watermark.options/wordprocessingpreviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)
```
public class WordProcessingPreviewOptions extends PreviewOptions
```

Fornisce opzioni per impostare i requisiti e i delegati di flusso per la generazione dell'anteprima di un documento WordProcessing.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [WordProcessingPreviewOptions(ICreatePageStream createPageStream)](#WordProcessingPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-) | Inizializza una nuova istanza della classe `[WordProcessingPreviewOptions](../../com.groupdocs.watermark.options/wordprocessingpreviewoptions)` facendo chiudere lo stream di output. |
|
|  | [WordProcessingPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)](#WordProcessingPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | Inizializza una nuova istanza della classe `[WordProcessingPreviewOptions](../../com.groupdocs.watermark.options/wordprocessingpreviewoptions)` facendo restituire lo stream di output al client per un ulteriore utilizzo. |
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
|  | [setResolution(float value)](#setResolution-float-) | Imposta la risoluzione per le immagini generate, in punti per pollice. |
|
### WordProcessingPreviewOptions(ICreatePageStream createPageStream) {#WordProcessingPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-}
```
public WordProcessingPreviewOptions(ICreatePageStream createPageStream)
```


Inizializza una nuova istanza della classe `[WordProcessingPreviewOptions](../../com.groupdocs.watermark.options/wordprocessingpreviewoptions)` facendo chiudere lo stream di output.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Crea uno stream per l'anteprima di una pagina specifica. |
|

### WordProcessingPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream) {#WordProcessingPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public WordProcessingPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)
```


Inizializza una nuova istanza della classe `[WordProcessingPreviewOptions](../../com.groupdocs.watermark.options/wordprocessingpreviewoptions)` facendo restituire lo stream di output al client per un ulteriore utilizzo.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Crea uno stream per l'anteprima di una pagina specifica. |
|
|  | releasePageStream | [IReleasePageStream](../../com.groupdocs.watermark.options/ireleasepagestream) | Notifica che la generazione dell'anteprima della pagina è completata e ottiene lo stream di output. |
|

### DefaultResolution {#DefaultResolution}
```
public static final float DefaultResolution
```


Risoluzione predefinita in punti per pollice.


### getResolution() {#getResolution--}
```
public final float getResolution()
```


Ottiene la risoluzione per le immagini generate, in punti per pollice.


**Returns:**
float - La risoluzione per le immagini generate, in punti per pollice.

<br />

*** ** * ** ***

Il valore predefinito è 96.

<br />


### setResolution(float value) {#setResolution-float-}
```
public final void setResolution(float value)
```


Imposta la risoluzione per le immagini generate, in punti per pollice.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | float | La risoluzione per le immagini generate, in punti per pollice. |

<br />

*** ** * ** ***

Il valore predefinito è 96.

<br />

|

