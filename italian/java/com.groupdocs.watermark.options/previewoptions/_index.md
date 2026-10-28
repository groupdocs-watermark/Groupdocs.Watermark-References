---
title: "PreviewOptions"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Fornisce opzioni per impostare i requisiti e i delegati di flusso per la generazione dell'anteprima."
type: docs
weight: 47
url: /it/java/com.groupdocs.watermark.options/previewoptions/
---
**Inheritance:**
java.lang.Object
```
public class PreviewOptions
```

Fornisce opzioni per impostare i requisiti e i delegati di flusso per la generazione dell'anteprima.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [PreviewOptions(ICreatePageStream createPageStream)](#PreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-) | Inizializza una nuova istanza della classe `[PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)` facendo chiudere lo stream di output. |
|
|  | [PreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)](#PreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | Inizializza una nuova istanza della classe `[PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)` facendo restituire lo stream di output al client per un uso successivo. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getWidth()](#getWidth--) | Ottiene la larghezza dell'anteprima della pagina. |
|
|  | [setWidth(int value)](#setWidth-int-) | Imposta la larghezza dell'anteprima della pagina. |
|
|  | [getHeight()](#getHeight--) | Ottiene l'altezza dell'anteprima della pagina. |
|
|  | [setHeight(int value)](#setHeight-int-) | Imposta l'altezza dell'anteprima della pagina. |
|
|  | [getPageNumbers()](#getPageNumbers--) | Ottiene un array di numeri di pagina per generare le anteprime. |
|
|  | [setPageNumbers(int[] value)](#setPageNumbers-int---) | Imposta un array di numeri di pagina per generare le anteprime. |
|
|  | [getPreviewFormat()](#getPreviewFormat--) | Ottiene il formato dell'immagine di anteprima. |
|
|  | [setPreviewFormat(int value)](#setPreviewFormat-int-) | Imposta il formato dell'immagine di anteprima. |
|
|  | [getCreatePageStream()](#getCreatePageStream--) | Ottiene un'istanza della classe di creazione dello stream di pagina. |
|
|  | [setCreatePageStream(ICreatePageStream value)](#setCreatePageStream-com.groupdocs.watermark.options.ICreatePageStream-) | Imposta un'istanza della classe di creazione dello stream di pagina. |
|
|  | [getReleasePageStream()](#getReleasePageStream--) | Ottiene un'istanza della classe di completamento dell'anteprima della pagina. |
|
|  | [setReleasePageStream(IReleasePageStream value)](#setReleasePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | Imposta un'istanza della classe di completamento dell'anteprima della pagina. |
|
### PreviewOptions(ICreatePageStream createPageStream) {#PreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-}
```
public PreviewOptions(ICreatePageStream createPageStream)
```


Inizializza una nuova istanza della classe `[PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)` facendo chiudere lo stream di output.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Crea uno stream per l'anteprima di una pagina specifica. |
|

### PreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream) {#PreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public PreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)
```


Inizializza una nuova istanza della classe `[PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)` facendo restituire lo stream di output al client per un uso successivo.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Crea uno stream per l'anteprima di una pagina specifica. |
|
|  | releasePageStream | [IReleasePageStream](../../com.groupdocs.watermark.options/ireleasepagestream) | Notifica che la generazione dell'anteprima della pagina è completata e ottiene lo stream di output. |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Ottiene la larghezza dell'anteprima della pagina.


**Returns:**
int - La larghezza dell'anteprima della pagina.

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Imposta la larghezza dell'anteprima della pagina.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | int | La larghezza dell'anteprima della pagina. |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Ottiene l'altezza dell'anteprima della pagina.


**Returns:**
int - L'altezza dell'anteprima della pagina.

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Imposta l'altezza dell'anteprima della pagina.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | int | L'altezza dell'anteprima della pagina. |
|

### getPageNumbers() {#getPageNumbers--}
```
public final int[] getPageNumbers()
```


Ottiene un array di numeri di pagina per generare le anteprime.


**Returns:**
int[] - L'array di numeri di pagina per generare le anteprime.

### setPageNumbers(int[] value) {#setPageNumbers-int---}
```
public final void setPageNumbers(int[] value)
```


Imposta un array di numeri di pagina per generare le anteprime.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | int[] | L'array di numeri di pagina per generare le anteprime. |
|

### getPreviewFormat() {#getPreviewFormat--}
```
public final int getPreviewFormat()
```


Ottiene il formato dell'immagine di anteprima.


**Returns:**
int - Il formato dell'immagine di anteprima.

### setPreviewFormat(int value) {#setPreviewFormat-int-}
```
public final void setPreviewFormat(int value)
```


Imposta il formato dell'immagine di anteprima.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | int | Il formato dell'immagine di anteprima. |
|

### getCreatePageStream() {#getCreatePageStream--}
```
public final ICreatePageStream getCreatePageStream()
```


Ottiene un'istanza della classe di creazione dello stream di pagina.


**Returns:**
[ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) - The instance of the page stream creation class.

### setCreatePageStream(ICreatePageStream value) {#setCreatePageStream-com.groupdocs.watermark.options.ICreatePageStream-}
```
public final void setCreatePageStream(ICreatePageStream value)
```


Imposta un'istanza della classe di creazione dello stream di pagina.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | L'istanza della classe di creazione del flusso di pagina. |
|

### getReleasePageStream() {#getReleasePageStream--}
```
public final IReleasePageStream getReleasePageStream()
```


Ottiene un'istanza della classe di completamento dell'anteprima della pagina.


**Returns:**
[IReleasePageStream](../../com.groupdocs.watermark.options/ireleasepagestream) - The instance of the page preview completion delegate.

### setReleasePageStream(IReleasePageStream value) {#setReleasePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public final void setReleasePageStream(IReleasePageStream value)
```


Imposta un'istanza della classe di completamento dell'anteprima della pagina.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | [IReleasePageStream](../../com.groupdocs.watermark.options/ireleasepagestream) | L'istanza del delegato di completamento dell'anteprima della pagina. |
|

