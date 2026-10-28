---
title: "SpreadsheetWatermarkShapeOptions"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Rappresenta le opzioni quando si aggiunge una filigrana forma a un foglio di lavoro Spreadsheet."
type: docs
weight: 60
url: /it/java/com.groupdocs.watermark.options/spreadsheetwatermarkshapeoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.SpreadsheetWatermarkOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkoptions), [com.groupdocs.watermark.options.SpreadsheetWatermarkBaseOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkbaseoptions)
```
public final class SpreadsheetWatermarkShapeOptions extends SpreadsheetWatermarkBaseOptions
```

Rappresenta le opzioni quando si aggiunge una filigrana forma a un foglio di lavoro Spreadsheet.

**Learn more:**

* [Add watermarks to spreadsheet documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+spreadsheet+documents)

Il seguente esempio dimostra come aggiungere una filigrana a un foglio di lavoro specifico di un documento Excel.
>
> ````
> ```
>
>    SpreadsheetLoadOptions loadOptions = new SpreadsheetLoadOptions();
>    Watermarker watermarker = new Watermarker("D:\\test.xls", loadOptions);
>
>    TextWatermark watermark = new TextWatermark("Test", new Font("Arial", 14));
>
>    SpreadsheetWatermarkShapeOptions options = new SpreadsheetWatermarkShapeOptions();
>    options.setWorksheetIndex(0);
>    
>    watermarker.save("D:\\watermarked_test.xlsx");
>    watermarker.close();
>  
> ```
> ````


## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [SpreadsheetWatermarkShapeOptions()](#SpreadsheetWatermarkShapeOptions--) | Inizializza una nuova istanza della classe `[SpreadsheetWatermarkShapeOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkshapeoptions)`. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getWorksheetIndex()](#getWorksheetIndex--) | Ottiene l'indice del foglio di lavoro a cui aggiungere la filigrana. |
|
|  | [setWorksheetIndex(int value)](#setWorksheetIndex-int-) | Imposta l'indice del foglio di lavoro a cui aggiungere la filigrana. |
|
|  | [getEffects()](#getEffects--) | Ottiene un valore di `[SpreadsheetImageEffects](../../com.groupdocs.watermark.options/spreadsheetimageeffects)` o `[SpreadsheetTextEffects](../../com.groupdocs.watermark.options/spreadsheettexteffects)` per gli effetti da applicare alla filigrana. |
|
|  | [setEffects(ISpreadsheetWatermarkEffects value)](#setEffects-com.groupdocs.watermark.options.ISpreadsheetWatermarkEffects-) | Ottiene o imposta un valore di `[SpreadsheetImageEffects](../../com.groupdocs.watermark.options/spreadsheetimageeffects)` o `[SpreadsheetTextEffects](../../com.groupdocs.watermark.options/spreadsheettexteffects)` per gli effetti da applicare alla filigrana. |
|
### SpreadsheetWatermarkShapeOptions() {#SpreadsheetWatermarkShapeOptions--}
```
public SpreadsheetWatermarkShapeOptions()
```


Inizializza una nuova istanza della classe `[SpreadsheetWatermarkShapeOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkshapeoptions)`.


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

### getEffects() {#getEffects--}
```
public final ISpreadsheetWatermarkEffects getEffects()
```


Ottiene un valore di `[SpreadsheetImageEffects](../../com.groupdocs.watermark.options/spreadsheetimageeffects)` o `[SpreadsheetTextEffects](../../com.groupdocs.watermark.options/spreadsheettexteffects)` per gli effetti da applicare alla filigrana.


**Returns:**
[ISpreadsheetWatermarkEffects](../../com.groupdocs.watermark.options/ispreadsheetwatermarkeffects) - The `[SpreadsheetImageEffects](../../com.groupdocs.watermark.options/spreadsheetimageeffects)` or `[SpreadsheetTextEffects](../../com.groupdocs.watermark.options/spreadsheettexteffects)` for effects that should be applied to the watermark.

### setEffects(ISpreadsheetWatermarkEffects value) {#setEffects-com.groupdocs.watermark.options.ISpreadsheetWatermarkEffects-}
```
public final void setEffects(ISpreadsheetWatermarkEffects value)
```


Ottiene o imposta un valore di `[SpreadsheetImageEffects](../../com.groupdocs.watermark.options/spreadsheetimageeffects)` o `[SpreadsheetTextEffects](../../com.groupdocs.watermark.options/spreadsheettexteffects)` per gli effetti da applicare alla filigrana.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | [ISpreadsheetWatermarkEffects](../../com.groupdocs.watermark.options/ispreadsheetwatermarkeffects) | Il `[SpreadsheetImageEffects](../../com.groupdocs.watermark.options/spreadsheetimageeffects)` o `[SpreadsheetTextEffects](../../com.groupdocs.watermark.options/spreadsheettexteffects)` per gli effetti che devono essere applicati al watermark. |
|

