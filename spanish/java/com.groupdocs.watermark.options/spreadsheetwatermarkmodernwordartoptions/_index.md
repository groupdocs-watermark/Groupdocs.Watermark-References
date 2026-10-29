---
title: "SpreadsheetWatermarkModernWordArtOptions"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Representa opciones al agregar una marca de agua de arte de texto moderno a una hoja de cálculo de Spreadsheet."
type: docs
weight: 58
url: /es/java/com.groupdocs.watermark.options/spreadsheetwatermarkmodernwordartoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.SpreadsheetWatermarkOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkoptions), [com.groupdocs.watermark.options.SpreadsheetWatermarkBaseOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkbaseoptions)
```
public final class SpreadsheetWatermarkModernWordArtOptions extends SpreadsheetWatermarkBaseOptions
```

Representa opciones al agregar una marca de agua de arte de texto moderno a una hoja de cálculo de Spreadsheet.

**Learn more:**

* [Add watermarks to spreadsheet documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+spreadsheet+documents)

El siguiente ejemplo muestra cómo agregar una marca de agua moderna de WordArt a un documento de Excel.
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


## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [SpreadsheetWatermarkModernWordArtOptions()](#SpreadsheetWatermarkModernWordArtOptions--) | Inicializa una nueva instancia de la clase `[SpreadsheetWatermarkModernWordArtOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkmodernwordartoptions)`. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getWorksheetIndex()](#getWorksheetIndex--) | Obtiene el índice de la hoja de cálculo a la que se agregará la marca de agua. |
|
|  | [setWorksheetIndex(int value)](#setWorksheetIndex-int-) | Establece el índice de la hoja de cálculo a la que se agregará la marca de agua. |
|
### SpreadsheetWatermarkModernWordArtOptions() {#SpreadsheetWatermarkModernWordArtOptions--}
```
public SpreadsheetWatermarkModernWordArtOptions()
```


Inicializa una nueva instancia de la clase `[SpreadsheetWatermarkModernWordArtOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkmodernwordartoptions)`.


### getWorksheetIndex() {#getWorksheetIndex--}
```
public final int getWorksheetIndex()
```


Obtiene el índice de la hoja de cálculo a la que se agregará la marca de agua.


**Returns:**
int - El índice de la hoja de cálculo a la que se agregará la marca de agua.

<br />

*** ** * ** ***

-1 means every worksheet.

<br />


### setWorksheetIndex(int value) {#setWorksheetIndex-int-}
```
public final void setWorksheetIndex(int value)
```


Establece el índice de la hoja de cálculo a la que se agregará la marca de agua.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | int | El índice de la hoja de cálculo a la que se agregará la marca de agua. |

<br />

*** ** * ** ***

-1 means every worksheet.

<br />

|

