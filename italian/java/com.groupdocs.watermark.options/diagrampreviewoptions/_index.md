---
title: "DiagramPreviewOptions"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Fornisce opzioni per impostare i requisiti e i delegati di flusso per la generazione dell'anteprima del documento Diagram."
type: docs
weight: 12
url: /it/java/com.groupdocs.watermark.options/diagrampreviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)
```
public class DiagramPreviewOptions extends PreviewOptions
```

Fornisce opzioni per impostare i requisiti e i delegati di flusso per la generazione dell'anteprima del documento Diagram.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [DiagramPreviewOptions(ICreatePageStream createPageStream)](#DiagramPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-) | Inizializza una nuova istanza della classe `[DiagramPreviewOptions](../../com.groupdocs.watermark.options/diagrampreviewoptions)` facendo chiudere lo stream di output. |
|
|  | [DiagramPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)](#DiagramPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | Inizializza una nuova istanza della classe `[DiagramPreviewOptions](../../com.groupdocs.watermark.options/diagrampreviewoptions)` facendo restituire lo stream di output al client per un uso successivo. |
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
|  | [getHighQualityRendering()](#getHighQualityRendering--) | Ottiene il flag per il rendering ad alta qualità. |
|
|  | [setHighQualityRendering(boolean value)](#setHighQualityRendering-boolean-) | Imposta il flag per il rendering ad alta qualità. |
|
### DiagramPreviewOptions(ICreatePageStream createPageStream) {#DiagramPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-}
```
public DiagramPreviewOptions(ICreatePageStream createPageStream)
```


Inizializza una nuova istanza della classe `[DiagramPreviewOptions](../../com.groupdocs.watermark.options/diagrampreviewoptions)` facendo chiudere lo stream di output.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Crea uno stream per l'anteprima di una pagina specifica. |
|

### DiagramPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream) {#DiagramPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public DiagramPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)
```


Inizializza una nuova istanza della classe `[DiagramPreviewOptions](../../com.groupdocs.watermark.options/diagrampreviewoptions)` facendo restituire lo stream di output al client per un uso successivo.


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

Il valore predefinito è 300.

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

Il valore predefinito è 300.

<br />

|

### getHighQualityRendering() {#getHighQualityRendering--}
```
public final boolean getHighQualityRendering()
```


Ottiene il flag per il rendering ad alta qualità.


**Returns:**
boolean - Il flag per il rendering ad alta qualità.

<br />

*** ** * ** ***

Il rendering ad alta qualità utilizza più risorse. Il valore predefinito è false.

<br />


### setHighQualityRendering(boolean value) {#setHighQualityRendering-boolean-}
```
public final void setHighQualityRendering(boolean value)
```


Imposta il flag per il rendering ad alta qualità.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | boolean | Il flag per il rendering ad alta qualità. |

<br />

*** ** * ** ***

Il rendering ad alta qualità utilizza più risorse. Il valore predefinito è false.

<br />

|

