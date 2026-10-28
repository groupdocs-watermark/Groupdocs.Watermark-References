---
title: "PresentationPreviewOptions"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Fornisce opzioni per impostare i requisiti e i delegati di flusso per la generazione dell'anteprima del documento di Presentazione."
type: docs
weight: 12
url: /it/java/com.groupdocs.watermark/presentationpreviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)
```
public class PresentationPreviewOptions extends PreviewOptions
```

Fornisce opzioni per impostare i requisiti e i delegati di flusso per la generazione dell'anteprima del documento di Presentazione.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [PresentationPreviewOptions(ICreatePageStream createPageStream)](#PresentationPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-) | Inizializza una nuova istanza della classe `[PresentationPreviewOptions](../../com.groupdocs.watermark/presentationpreviewoptions)` facendo chiudere lo stream di output. |
|
|  | [PresentationPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)](#PresentationPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | Inizializza una nuova istanza della classe `[PresentationPreviewOptions](../../com.groupdocs.watermark/presentationpreviewoptions)` facendo restituire lo stream di output al client per un uso successivo. |
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
|  | [setResolution(long value)](#setResolution-long-) | Imposta la risoluzione per le immagini generate, in punti per pollice. |
|
### PresentationPreviewOptions(ICreatePageStream createPageStream) {#PresentationPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-}
```
public PresentationPreviewOptions(ICreatePageStream createPageStream)
```


Inizializza una nuova istanza della classe `[PresentationPreviewOptions](../../com.groupdocs.watermark/presentationpreviewoptions)` facendo chiudere lo stream di output.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Crea uno stream per l'anteprima di una pagina specifica. |
|

### PresentationPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream) {#PresentationPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public PresentationPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)
```


Inizializza una nuova istanza della classe `[PresentationPreviewOptions](../../com.groupdocs.watermark/presentationpreviewoptions)` facendo restituire lo stream di output al client per un uso successivo.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Crea uno stream per l'anteprima di una pagina specifica. |
|
|  | releasePageStream | [IReleasePageStream](../../com.groupdocs.watermark.options/ireleasepagestream) | Notifica che la generazione dell'anteprima della pagina è completata e ottiene lo stream di output. |
|

### DefaultResolution {#DefaultResolution}
```
public static final long DefaultResolution
```


Risoluzione predefinita in punti per pollice.


### getResolution() {#getResolution--}
```
public final long getResolution()
```


Ottiene la risoluzione per le immagini generate, in punti per pollice.


**Returns:**
long - La risoluzione per le immagini generate, in punti per pollice.

### setResolution(long value) {#setResolution-long-}
```
public final void setResolution(long value)
```


Imposta la risoluzione per le immagini generate, in punti per pollice.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | long | La risoluzione per le immagini generate, in punti per pollice. |
|

