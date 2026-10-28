---
title: "EmailPreviewOptions"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Fornisce opzioni per impostare i requisiti e i delegati di flusso per la generazione dell'anteprima del documento Email."
type: docs
weight: 17
url: /it/java/com.groupdocs.watermark.options/emailpreviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)
```
public class EmailPreviewOptions extends PreviewOptions
```

Fornisce opzioni per impostare i requisiti e i delegati di flusso per la generazione dell'anteprima del documento Email.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [EmailPreviewOptions(ICreatePageStream createPageStream)](#EmailPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-) | Inizializza una nuova istanza della classe `[EmailPreviewOptions](../../com.groupdocs.watermark.options/emailpreviewoptions)` facendo chiudere lo stream di output. |
|
|  | [EmailPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)](#EmailPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | Inizializza una nuova istanza della classe `[EmailPreviewOptions](../../com.groupdocs.watermark.options/emailpreviewoptions)` facendo restituire lo stream di output al client per un ulteriore utilizzo. |
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
### EmailPreviewOptions(ICreatePageStream createPageStream) {#EmailPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-}
```
public EmailPreviewOptions(ICreatePageStream createPageStream)
```


Inizializza una nuova istanza della classe `[EmailPreviewOptions](../../com.groupdocs.watermark.options/emailpreviewoptions)` facendo chiudere lo stream di output.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Crea uno stream per l'anteprima di una pagina specifica. |
|

### EmailPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream) {#EmailPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public EmailPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)
```


Inizializza una nuova istanza della classe `[EmailPreviewOptions](../../com.groupdocs.watermark.options/emailpreviewoptions)` facendo restituire lo stream di output al client per un ulteriore utilizzo.


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

