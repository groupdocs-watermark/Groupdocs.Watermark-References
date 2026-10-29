---
title: "SpreadsheetWatermarkBaseOptions"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Clase base para opciones de adición de marca de agua a un documento de Spreadsheet."
type: docs
weight: 56
url: /es/java/com.groupdocs.watermark.options/spreadsheetwatermarkbaseoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.SpreadsheetWatermarkOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkoptions)
```
public abstract class SpreadsheetWatermarkBaseOptions extends SpreadsheetWatermarkOptions
```

Clase base para opciones de adición de marca de agua a un documento de Spreadsheet.

## Métodos

| Método | Descripción |
| --- | --- |
|  | [isLocked()](#isLocked--) | Obtiene un valor que indica si la edición de la forma en Excel está prohibida. |
|
|  | [setLocked(boolean value)](#setLocked-boolean-) | Establece un valor que indica si la edición de la forma en Excel está prohibida. |
|
|  | [getName()](#getName--) | Obtiene el nombre de una forma. |
|
|  | [setName(String value)](#setName-java.lang.String-) | Establece el nombre de una forma. |
|
|  | [getAlternativeText()](#getAlternativeText--) | Obtiene el texto descriptivo (alternativo) que se asociará a una forma. |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Establece el texto descriptivo (alternativo) que se asociará a una forma. |
|
### isLocked() {#isLocked--}
```
public final boolean isLocked()
```


Obtiene un valor que indica si la edición de la forma en Excel está prohibida.


**Returns:**
boolean - Si el valor es verdadero, la edición de la forma estará prohibida. Por defecto, el valor es falso, la forma puede editarse en Excel.

### setLocked(boolean value) {#setLocked-boolean-}
```
public final void setLocked(boolean value)
```


Establece un valor que indica si la edición de la forma en Excel está prohibida.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | boolean | Si el valor es verdadero, la edición de la forma estará prohibida. Por defecto, el valor es falso, la forma puede editarse en Excel. |
|

### getName() {#getName--}
```
public final String getName()
```


Obtiene el nombre de una forma.


**Returns:**
java.lang.String - El nombre de la forma.

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Establece el nombre de una forma.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | java.lang.String | El nombre de la forma. |
|

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


Obtiene el texto descriptivo (alternativo) que se asociará a una forma.


**Returns:**
java.lang.String - El texto descriptivo (alternativo) que se asociará con una forma.

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


Establece el texto descriptivo (alternativo) que se asociará a una forma.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | java.lang.String | El texto descriptivo (alternativo) que se asociará con una forma. |
|

