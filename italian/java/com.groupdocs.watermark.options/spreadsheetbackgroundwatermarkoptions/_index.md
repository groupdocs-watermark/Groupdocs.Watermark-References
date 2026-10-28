---
title: "SpreadsheetBackgroundWatermarkOptions"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Rappresenta le opzioni quando si aggiunge la filigrana come sfondo a un foglio di lavoro Spreadsheet."
type: docs
weight: 49
url: /it/java/com.groupdocs.watermark.options/spreadsheetbackgroundwatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.SpreadsheetWatermarkOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkoptions)
```
public final class SpreadsheetBackgroundWatermarkOptions extends SpreadsheetWatermarkOptions
```

Rappresenta le opzioni quando si aggiunge la filigrana come sfondo a un foglio di lavoro Spreadsheet.

**Learn more:**

* [Add watermarks to spreadsheet documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+spreadsheet+documents)

Il seguente esempio dimostra come aggiungere una filigrana di testo a un foglio di lavoro di un documento Excel come sfondo.
>
> ````
> ```
>
>    SpreadsheetLoadOptions loadOptions = new SpreadsheetLoadOptions();
>    Watermarker watermarker = new Watermarker("C:\\Documents\\test.xlsx", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("Test watermark", new Font("Arial", 36));
>
>    SpreadsheetBackgroundWatermarkOptions options = new SpreadsheetBackgroundWatermarkOptions();
>    options.setWorksheetIndex(-1); // default
>    options.setBackgroundWidth(800);
>    options.setBackgroundHeight(600);
>    
>    watermarker.save("C:\\Documents\\watermarked_test.xlsx");
>    watermarker.close();
>  
> ```
> ````


## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [SpreadsheetBackgroundWatermarkOptions()](#SpreadsheetBackgroundWatermarkOptions--) | Inizializza una nuova istanza della classe `[SpreadsheetBackgroundWatermarkOptions](../../com.groupdocs.watermark.options/spreadsheetbackgroundwatermarkoptions)`. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getWorksheetIndex()](#getWorksheetIndex--) | Ottieni l'indice del foglio di lavoro a cui aggiungere la filigrana. |
|
|  | [setWorksheetIndex(int value)](#setWorksheetIndex-int-) | Imposta l'indice del foglio di lavoro a cui aggiungere la filigrana. |
|
|  | [getBackgroundWidth()](#getBackgroundWidth--) | Ottieni la larghezza desiderata dell'immagine di sfondo in pixel. |
|
|  | [setBackgroundWidth(int value)](#setBackgroundWidth-int-) | Imposta la larghezza desiderata dell'immagine di sfondo in pixel. |
|
|  | [getBackgroundHeight()](#getBackgroundHeight--) | Ottiene o imposta l'altezza desiderata dell'immagine di sfondo in pixel. |
|
|  | [setBackgroundHeight(int value)](#setBackgroundHeight-int-) | Ottiene o imposta l'altezza desiderata dell'immagine di sfondo in pixel. |
|
### SpreadsheetBackgroundWatermarkOptions() {#SpreadsheetBackgroundWatermarkOptions--}
```
public SpreadsheetBackgroundWatermarkOptions()
```


Inizializza una nuova istanza della classe `[SpreadsheetBackgroundWatermarkOptions](../../com.groupdocs.watermark.options/spreadsheetbackgroundwatermarkoptions)`.


### getWorksheetIndex() {#getWorksheetIndex--}
```
public final int getWorksheetIndex()
```


Ottieni l'indice del foglio di lavoro a cui aggiungere la filigrana.

-1 means every worksheet.


**Returns:**
int - L'indice del foglio di lavoro a cui aggiungere la filigrana.

### setWorksheetIndex(int value) {#setWorksheetIndex-int-}
```
public final void setWorksheetIndex(int value)
```


Imposta l'indice del foglio di lavoro a cui aggiungere la filigrana.

-1 means every worksheet.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | int | L'indice del foglio di lavoro a cui aggiungere la filigrana. |
|

### getBackgroundWidth() {#getBackgroundWidth--}
```
public final int getBackgroundWidth()
```


Ottieni la larghezza desiderata dell'immagine di sfondo in pixel.


**Returns:**
int - La larghezza desiderata dell'immagine di sfondo in pixel.

### setBackgroundWidth(int value) {#setBackgroundWidth-int-}
```
public final void setBackgroundWidth(int value)
```


Imposta la larghezza desiderata dell'immagine di sfondo in pixel.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | int | La larghezza desiderata dell'immagine di sfondo in pixel. |
|

### getBackgroundHeight() {#getBackgroundHeight--}
```
public final int getBackgroundHeight()
```


Ottiene o imposta l'altezza desiderata dell'immagine di sfondo in pixel.


**Returns:**
int - L'altezza desiderata dell'immagine di sfondo in pixel.

### setBackgroundHeight(int value) {#setBackgroundHeight-int-}
```
public final void setBackgroundHeight(int value)
```


Ottiene o imposta l'altezza desiderata dell'immagine di sfondo in pixel.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | int | L'altezza desiderata dell'immagine di sfondo in pixel. |
|

