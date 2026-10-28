---
title: "OfficeLineFormat"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Rappresenta il formato della linea della forma."
type: docs
weight: 47
url: /it/java/com.groupdocs.watermark.contents/officelineformat/
---
**Inheritance:**
java.lang.Object
```
public final class OfficeLineFormat
```

Rappresenta il formato della linea della forma.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [OfficeLineFormat()](#OfficeLineFormat--) | Inizializza una nuova istanza della classe `[OfficeLineFormat](../../com.groupdocs.watermark.contents/officelineformat)`. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getWeight()](#getWeight--) | Ottiene lo spessore del pennello che traccia il percorso di una forma. |
|
|  | [setWeight(double value)](#setWeight-double-) | Imposta lo spessore del pennello che traccia il percorso di una forma. |
|
|  | [getColor()](#getColor--) | Ottiene il colore della linea. |
|
|  | [setColor(Color value)](#setColor-com.groupdocs.watermark.watermarks.Color-) | Imposta il colore della linea. |
|
|  | [getOpacity()](#getOpacity--) | Ottiene l'opacità della linea. |
|
|  | [setOpacity(double value)](#setOpacity-double-) | Imposta l'opacità della linea. |
|
|  | [getEnabled()](#getEnabled--) | Ottiene un valore che indica se una forma sarà tracciata. |
|
|  | [setEnabled(boolean value)](#setEnabled-boolean-) | Imposta un valore che indica se una forma sarà tracciata. |
|
|  | [getDashStyle()](#getDashStyle--) | Ottiene il modello di punti e trattini per una linea. |
|
|  | [setDashStyle(int value)](#setDashStyle-int-) | Imposta il modello di punti e trattini per una linea. |
|
|  | [getLineStyle()](#getLineStyle--) | Ottiene lo stile della linea. |
|
|  | [setLineStyle(int value)](#setLineStyle-int-) | Imposta lo stile della linea. |
|
|  | [getTransparency()](#getTransparency--) | <br /> |

|
|  | [getColorConsideringOpacity()](#getColorConsideringOpacity--) | <br /> |

|
### OfficeLineFormat() {#OfficeLineFormat--}
```
public OfficeLineFormat()
```


Inizializza una nuova istanza della classe `[OfficeLineFormat](../../com.groupdocs.watermark.contents/officelineformat)`.


### getWeight() {#getWeight--}
```
public final double getWeight()
```


Ottiene lo spessore del pennello che traccia il percorso di una forma.


**Returns:**
double - Lo spessore della linea in punti. Il valore predefinito è 0.75.

### setWeight(double value) {#setWeight-double-}
```
public final void setWeight(double value)
```


Imposta lo spessore del pennello che traccia il percorso di una forma.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | double | Lo spessore della linea in punti. Il valore predefinito è 0.75. |
|

### getColor() {#getColor--}
```
public final Color getColor()
```


Ottiene il colore della linea.

Il valore predefinito è `[Color.getBlack()](../../com.groupdocs.watermark.watermarks/color#getBlack--)`.


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The color of the line.

### setColor(Color value) {#setColor-com.groupdocs.watermark.watermarks.Color-}
```
public final void setColor(Color value)
```


Imposta il colore della linea.

Il valore predefinito è `[Color.getBlack()](../../com.groupdocs.watermark.watermarks/color#getBlack--)`.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | [Color](../../com.groupdocs.watermark.watermarks/color) | Il colore della linea. |
|

### getOpacity() {#getOpacity--}
```
public final double getOpacity()
```


Ottiene l'opacità della linea.


**Returns:**
double - Il valore deve essere compreso tra 0 e 1. Il valore predefinito è 1.

### setOpacity(double value) {#setOpacity-double-}
```
public final void setOpacity(double value)
```


Imposta l'opacità della linea.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | double | Il valore deve essere compreso tra 0 e 1. Il valore predefinito è 1. |
|

### getEnabled() {#getEnabled--}
```
public final boolean getEnabled()
```


Ottiene un valore che indica se una forma sarà tracciata.


**Returns:**
boolean - Il valore predefinito è false.

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public final void setEnabled(boolean value)
```


Imposta un valore che indica se una forma sarà tracciata.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | boolean | Il valore predefinito è false. |
|

### getDashStyle() {#getDashStyle--}
```
public final int getDashStyle()
```


Ottiene il modello di punti e trattini per una linea.

<br />



**Returns:**
int
### setDashStyle(int value) {#setDashStyle-int-}
```
public final void setDashStyle(int value)
```


Imposta il modello di punti e trattini per una linea.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getLineStyle() {#getLineStyle--}
```
public final int getLineStyle()
```


Ottiene lo stile della linea.

Il valore predefinito è `[OfficeLineStyle.Single](../../com.groupdocs.watermark.contents/officelinestyle#Single)`.


**Returns:**
int - Lo stile della linea.

### setLineStyle(int value) {#setLineStyle-int-}
```
public final void setLineStyle(int value)
```


Imposta lo stile della linea.

Il valore predefinito è `[OfficeLineStyle.Single](../../com.groupdocs.watermark.contents/officelinestyle#Single)`.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | int | Lo stile della linea. |
|

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


<br />



**Returns:**
double
### getColorConsideringOpacity() {#getColorConsideringOpacity--}
```
public final Color getColorConsideringOpacity()
```


<br />



**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color)
