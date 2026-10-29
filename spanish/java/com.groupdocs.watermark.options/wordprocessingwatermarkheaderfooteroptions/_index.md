---
title: "WordProcessingWatermarkHeaderFooterOptions"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Representa las opciones al agregar la marca de agua al encabezado/pie de sección de Word."
type: docs
weight: 74
url: /es/java/com.groupdocs.watermark.options/wordprocessingwatermarkheaderfooteroptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkBaseOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkbaseoptions)
```
public final class WordProcessingWatermarkHeaderFooterOptions extends WordProcessingWatermarkBaseOptions
```

Representa las opciones al agregar la marca de agua al encabezado/pie de sección de Word.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [WordProcessingWatermarkHeaderFooterOptions()](#WordProcessingWatermarkHeaderFooterOptions--) | Inicializa una nueva instancia de la clase `[WordProcessingWatermarkHeaderFooterOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkheaderfooteroptions)`. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getSectionIndex()](#getSectionIndex--) | Obtiene el índice de una sección a la que se añadirá la marca de agua. |
|
|  | [setSectionIndex(int value)](#setSectionIndex-int-) | Establece el índice de una sección a la que se añadirá la marca de agua. |
|
|  | [getHeaderFooterType()](#getHeaderFooterType--) | Obtiene el valor que identifica el tipo de encabezado o pie de página al que se añadirá la marca de agua. |
|
|  | [setHeaderFooterType(int value)](#setHeaderFooterType-int-) | Establece el valor que identifica el tipo de encabezado o pie de página al que se añadirá la marca de agua. |
|
### WordProcessingWatermarkHeaderFooterOptions() {#WordProcessingWatermarkHeaderFooterOptions--}
```
public WordProcessingWatermarkHeaderFooterOptions()
```


Inicializa una nueva instancia de la clase `[WordProcessingWatermarkHeaderFooterOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkheaderfooteroptions)`.


### getSectionIndex() {#getSectionIndex--}
```
public final int getSectionIndex()
```


Obtiene el índice de una sección a la que se añadirá la marca de agua.


**Returns:**
int - El índice de una sección al que se añadirá la marca de agua.

<br />

*** ** * ** ***

-1 means all sections.

<br />


### setSectionIndex(int value) {#setSectionIndex-int-}
```
public final void setSectionIndex(int value)
```


Establece el índice de una sección a la que se añadirá la marca de agua.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | int | El índice de una sección al que se añadirá la marca de agua. |

<br />

*** ** * ** ***

-1 means all sections.

<br />

|

### getHeaderFooterType() {#getHeaderFooterType--}
```
public final int getHeaderFooterType()
```


Obtiene el valor que identifica el tipo de encabezado o pie de página al que se añadirá la marca de agua.


**Returns:**
int - El valor del tipo `[OfficeHeaderFooterType](../../com.groupdocs.watermark.contents/officeheaderfootertype)` que identifica el tipo de encabezado o pie de página al que se añadirá la marca de agua.

### setHeaderFooterType(int value) {#setHeaderFooterType-int-}
```
public final void setHeaderFooterType(int value)
```


Establece el valor que identifica el tipo de encabezado o pie de página al que se añadirá la marca de agua.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | int | El valor del tipo `[OfficeHeaderFooterType](../../com.groupdocs.watermark.contents/officeheaderfootertype)` que identifica el tipo de encabezado o pie de página al que se añadirá la marca de agua. |
|

