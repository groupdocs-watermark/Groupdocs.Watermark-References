---
title: "SpreadsheetWatermarkModernWordArtOptions"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Rappresenta le opzioni quando si aggiunge una filigrana moderna di Word Art a un foglio di lavoro Spreadsheet."
type: docs
weight: 58
url: /it/java/com.groupdocs.watermark.options/spreadsheetwatermarkmodernwordartoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.SpreadsheetWatermarkOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkoptions), [com.groupdocs.watermark.options.SpreadsheetWatermarkBaseOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkbaseoptions)
```
public final class SpreadsheetWatermarkModernWordArtOptions extends SpreadsheetWatermarkBaseOptions
```

Rappresenta le opzioni quando si aggiunge una filigrana moderna di Word Art a un foglio di lavoro Spreadsheet.

**Learn more:**

* [Add watermarks to spreadsheet documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+spreadsheet+documents)

Il seguente esempio dimostra come aggiungere un watermark WordArt moderno a un documento Excel.
>
> ````
> ```
>
>    SpreadsheetLoadOptions loadOptions = new SpreadsheetLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.xls", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 14));
>
>    SpreadsheetWatermarkModernWordArtOptions options = new SpreadsheetWatermarkModernWordArtOptions();
>    options.setWorksheetIndex(-1); // default
>    options.setLocked(false); // default
>    
>    watermarker.save("D:\\watermarked_test.xlsx");
>    watermarker.close();
>  
> ```
> ````


## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [SpreadsheetWatermarkModernWordArtOptions()](#SpreadsheetWatermarkModernWordArtOptions--) | Inizializza una nuova istanza della classe `[SpreadsheetWatermarkModernWordArtOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkmodernwordartoptions)`. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getWorksheetIndex()](#getWorksheetIndex--) | Ottiene l'indice del foglio di lavoro a cui aggiungere la filigrana. |
|
|  | [setWorksheetIndex(int value)](#setWorksheetIndex-int-) | Imposta l'indice del foglio di lavoro a cui aggiungere la filigrana. |
|
### SpreadsheetWatermarkModernWordArtOptions() {#SpreadsheetWatermarkModernWordArtOptions--}
```
public SpreadsheetWatermarkModernWordArtOptions()
```


Inizializza una nuova istanza della classe `[SpreadsheetWatermarkModernWordArtOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkmodernwordartoptions)`.


### getWorksheetIndex() {#getWorksheetIndex--}
```
public final int getWorksheetIndex()
```


Ottiene l'indice del foglio di lavoro a cui aggiungere la filigrana.


**Returns:**
int - L'indice del foglio di lavoro a cui aggiungere la filigrana.

<br />

*** ** * ** ***

-1 means every worksheet.

<br />


### setWorksheetIndex(int value) {#setWorksheetIndex-int-}
```
public final void setWorksheetIndex(int value)
```


Imposta l'indice del foglio di lavoro a cui aggiungere la filigrana.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | int | L'indice del foglio di lavoro a cui aggiungere la filigrana. |

<br />

*** ** * ** ***

-1 means every worksheet.

<br />

|

