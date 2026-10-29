---
title: "SpreadsheetBackgroundWatermarkOptions"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Representa opciones al agregar la marca de agua como fondo a una hoja de cálculo de Spreadsheet."
type: docs
weight: 49
url: /es/java/com.groupdocs.watermark.options/spreadsheetbackgroundwatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.SpreadsheetWatermarkOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkoptions)
```
public final class SpreadsheetBackgroundWatermarkOptions extends SpreadsheetWatermarkOptions
```

Representa opciones al agregar la marca de agua como fondo a una hoja de cálculo de Spreadsheet.

**Learn more:**

* [Add watermarks to spreadsheet documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+spreadsheet+documents)

El siguiente ejemplo muestra cómo agregar una marca de agua de texto a una hoja de cálculo de Excel como fondo.
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


## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [SpreadsheetBackgroundWatermarkOptions()](#SpreadsheetBackgroundWatermarkOptions--) | Inicializa una nueva instancia de la clase `[SpreadsheetBackgroundWatermarkOptions](../../com.groupdocs.watermark.options/spreadsheetbackgroundwatermarkoptions)`. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getWorksheetIndex()](#getWorksheetIndex--) | Obtenga el índice de la hoja de cálculo a la que se añadirá la marca de agua. |
|
|  | [setWorksheetIndex(int value)](#setWorksheetIndex-int-) | Establece el índice de la hoja de cálculo a la que se agregará la marca de agua. |
|
|  | [getBackgroundWidth()](#getBackgroundWidth--) | Obtenga el ancho deseado de la imagen de fondo en píxeles. |
|
|  | [setBackgroundWidth(int value)](#setBackgroundWidth-int-) | Establece el ancho deseado de la imagen de fondo en píxeles. |
|
|  | [getBackgroundHeight()](#getBackgroundHeight--) | Obtiene o establece la altura deseada de la imagen de fondo en píxeles. |
|
|  | [setBackgroundHeight(int value)](#setBackgroundHeight-int-) | Obtiene o establece la altura deseada de la imagen de fondo en píxeles. |
|
### SpreadsheetBackgroundWatermarkOptions() {#SpreadsheetBackgroundWatermarkOptions--}
```
public SpreadsheetBackgroundWatermarkOptions()
```


Inicializa una nueva instancia de la clase `[SpreadsheetBackgroundWatermarkOptions](../../com.groupdocs.watermark.options/spreadsheetbackgroundwatermarkoptions)`.


### getWorksheetIndex() {#getWorksheetIndex--}
```
public final int getWorksheetIndex()
```


Obtenga el índice de la hoja de cálculo a la que se añadirá la marca de agua.

-1 means every worksheet.


**Returns:**
int - El índice de la hoja de cálculo a la que se agregará la marca de agua.

### setWorksheetIndex(int value) {#setWorksheetIndex-int-}
```
public final void setWorksheetIndex(int value)
```


Establece el índice de la hoja de cálculo a la que se agregará la marca de agua.

-1 means every worksheet.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | int | El índice de la hoja de cálculo a la que se agregará la marca de agua. |
|

### getBackgroundWidth() {#getBackgroundWidth--}
```
public final int getBackgroundWidth()
```


Obtenga el ancho deseado de la imagen de fondo en píxeles.


**Returns:**
int - El ancho deseado de la imagen de fondo en píxeles.

### setBackgroundWidth(int value) {#setBackgroundWidth-int-}
```
public final void setBackgroundWidth(int value)
```


Establece el ancho deseado de la imagen de fondo en píxeles.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | int | El ancho deseado de la imagen de fondo en píxeles. |
|

### getBackgroundHeight() {#getBackgroundHeight--}
```
public final int getBackgroundHeight()
```


Obtiene o establece la altura deseada de la imagen de fondo en píxeles.


**Returns:**
int - La altura deseada de la imagen de fondo en píxeles.

### setBackgroundHeight(int value) {#setBackgroundHeight-int-}
```
public final void setBackgroundHeight(int value)
```


Obtiene o establece la altura deseada de la imagen de fondo en píxeles.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | int | La altura deseada de la imagen de fondo en píxeles. |
|

