---
title: "SpreadsheetWatermarkShapeOptions"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Representa opciones al agregar una marca de agua de forma a una hoja de cálculo de Spreadsheet."
type: docs
weight: 60
url: /es/java/com.groupdocs.watermark.options/spreadsheetwatermarkshapeoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.SpreadsheetWatermarkOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkoptions), [com.groupdocs.watermark.options.SpreadsheetWatermarkBaseOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkbaseoptions)
```
public final class SpreadsheetWatermarkShapeOptions extends SpreadsheetWatermarkBaseOptions
```

Representa opciones al agregar una marca de agua de forma a una hoja de cálculo de Spreadsheet.

**Learn more:**

* [Add watermarks to spreadsheet documents](../https://docs.groupdocs.com/display/watermarkjava/Add+watermarks+to+spreadsheet+documents)

El siguiente ejemplo muestra cómo agregar una marca de agua a una hoja de cálculo específica de un documento de Excel.
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


## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [SpreadsheetWatermarkShapeOptions()](#SpreadsheetWatermarkShapeOptions--) | Inicializa una nueva instancia de la clase `[SpreadsheetWatermarkShapeOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkshapeoptions)`. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getWorksheetIndex()](#getWorksheetIndex--) | Obtiene el índice de la hoja de cálculo a la que se agregará la marca de agua. |
|
|  | [setWorksheetIndex(int value)](#setWorksheetIndex-int-) | Establece el índice de la hoja de cálculo a la que se agregará la marca de agua. |
|
|  | [getEffects()](#getEffects--) | Obtiene un valor de `[SpreadsheetImageEffects](../../com.groupdocs.watermark.options/spreadsheetimageeffects)` o `[SpreadsheetTextEffects](../../com.groupdocs.watermark.options/spreadsheettexteffects)` para los efectos que se deben aplicar a la marca de agua. |
|
|  | [setEffects(ISpreadsheetWatermarkEffects value)](#setEffects-com.groupdocs.watermark.options.ISpreadsheetWatermarkEffects-) | Obtiene o establece un valor de `[SpreadsheetImageEffects](../../com.groupdocs.watermark.options/spreadsheetimageeffects)` o `[SpreadsheetTextEffects](../../com.groupdocs.watermark.options/spreadsheettexteffects)` para los efectos que se deben aplicar a la marca de agua. |
|
### SpreadsheetWatermarkShapeOptions() {#SpreadsheetWatermarkShapeOptions--}
```
public SpreadsheetWatermarkShapeOptions()
```


Inicializa una nueva instancia de la clase `[SpreadsheetWatermarkShapeOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkshapeoptions)`.


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

### getEffects() {#getEffects--}
```
public final ISpreadsheetWatermarkEffects getEffects()
```


Obtiene un valor de `[SpreadsheetImageEffects](../../com.groupdocs.watermark.options/spreadsheetimageeffects)` o `[SpreadsheetTextEffects](../../com.groupdocs.watermark.options/spreadsheettexteffects)` para los efectos que se deben aplicar a la marca de agua.


**Returns:**
[ISpreadsheetWatermarkEffects](../../com.groupdocs.watermark.options/ispreadsheetwatermarkeffects) - The `[SpreadsheetImageEffects](../../com.groupdocs.watermark.options/spreadsheetimageeffects)` or `[SpreadsheetTextEffects](../../com.groupdocs.watermark.options/spreadsheettexteffects)` for effects that should be applied to the watermark.

### setEffects(ISpreadsheetWatermarkEffects value) {#setEffects-com.groupdocs.watermark.options.ISpreadsheetWatermarkEffects-}
```
public final void setEffects(ISpreadsheetWatermarkEffects value)
```


Obtiene o establece un valor de `[SpreadsheetImageEffects](../../com.groupdocs.watermark.options/spreadsheetimageeffects)` o `[SpreadsheetTextEffects](../../com.groupdocs.watermark.options/spreadsheettexteffects)` para los efectos que se deben aplicar a la marca de agua.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | [ISpreadsheetWatermarkEffects](../../com.groupdocs.watermark.options/ispreadsheetwatermarkeffects) | El `[SpreadsheetImageEffects](../../com.groupdocs.watermark.options/spreadsheetimageeffects)` o `[SpreadsheetTextEffects](../../com.groupdocs.watermark.options/spreadsheettexteffects)` para los efectos que deben aplicarse a la marca de agua. |
|

