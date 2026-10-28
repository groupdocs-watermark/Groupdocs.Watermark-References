---
title: "OfficeImageEffects"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Rappresenta gli effetti che possono essere applicati a una filigrana immagine per un contenuto Office."
type: docs
weight: 45
url: /it/java/com.groupdocs.watermark.contents/officeimageeffects/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.watermark.internal.IDocumentSpecificSettings](../../com.groupdocs.watermark.internal/idocumentspecificsettings)
```
public abstract class OfficeImageEffects implements IDocumentSpecificSettings
```

Rappresenta gli effetti che possono essere applicati a una filigrana immagine per un contenuto Office.

## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getBorderLineFormat()](#getBorderLineFormat--) | Ottiene le impostazioni del formato linea per il bordo dell'immagine. |
|
|  | [setBorderLineFormat(OfficeLineFormat value)](#setBorderLineFormat-com.groupdocs.watermark.contents.OfficeLineFormat-) | Imposta le impostazioni del formato linea per il bordo dell'immagine. |
|
|  | [getGrayScale()](#getGrayScale--) | Ottiene un valore che indica se un'immagine verrà visualizzata in modalità scala di grigi. |
|
|  | [setGrayScale(boolean value)](#setGrayScale-boolean-) | Imposta un valore che indica se un'immagine verrà visualizzata in modalità scala di grigi. |
|
|  | [getChromaKey()](#getChromaKey--) | Ottiene il valore colore dell'immagine che verrà trattato come trasparente. |
|
|  | [setChromaKey(Color value)](#setChromaKey-com.groupdocs.watermark.watermarks.Color-) | Imposta il valore colore dell'immagine che verrà trattato come trasparente. |
|
|  | [getBrightness()](#getBrightness--) | Ottiene la luminosità dell'immagine. |
|
|  | [setBrightness(double value)](#setBrightness-double-) | Imposta la luminosità dell'immagine. |
|
|  | [getContrast()](#getContrast--) | Ottiene il contrasto per l'immagine specificata. |
|
|  | [setContrast(double value)](#setContrast-double-) | Imposta il contrasto per l'immagine specificata. |
|
### getBorderLineFormat() {#getBorderLineFormat--}
```
public final OfficeLineFormat getBorderLineFormat()
```


Ottiene le impostazioni del formato linea per il bordo dell'immagine.


**Returns:**
[OfficeLineFormat](../../com.groupdocs.watermark.contents/officelineformat) - Instance of  OfficeLineFormat  class, representing shape line format.

### setBorderLineFormat(OfficeLineFormat value) {#setBorderLineFormat-com.groupdocs.watermark.contents.OfficeLineFormat-}
```
public final void setBorderLineFormat(OfficeLineFormat value)
```


Imposta le impostazioni del formato linea per il bordo dell'immagine.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | [OfficeLineFormat](../../com.groupdocs.watermark.contents/officelineformat) | Istanza della classe OfficeLineFormat, che rappresenta il formato linea della forma. |
|

### getGrayScale() {#getGrayScale--}
```
public final boolean getGrayScale()
```


Ottiene un valore che indica se un'immagine verrà visualizzata in modalità scala di grigi.


**Returns:**
boolean - Il valore predefinito è false.

### setGrayScale(boolean value) {#setGrayScale-boolean-}
```
public final void setGrayScale(boolean value)
```


Imposta un valore che indica se un'immagine verrà visualizzata in modalità scala di grigi.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | boolean | Il valore predefinito è false. |
|

### getChromaKey() {#getChromaKey--}
```
public final Color getChromaKey()
```


Ottiene il valore colore dell'immagine che verrà trattato come trasparente.


**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color) - The default value is fully transparent color.

### setChromaKey(Color value) {#setChromaKey-com.groupdocs.watermark.watermarks.Color-}
```
public final void setChromaKey(Color value)
```


Imposta il valore colore dell'immagine che verrà trattato come trasparente.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | [Color](../../com.groupdocs.watermark.watermarks/color) | Il valore predefinito è colore completamente trasparente. |
|

### getBrightness() {#getBrightness--}
```
public final double getBrightness()
```


Ottiene la luminosità dell'immagine. Il valore per questa proprietà deve
essere un numero da 0.0 (più scuro) a 1.0 (più luminoso).


**Returns:**
double - Il valore predefinito è 0.5.

### setBrightness(double value) {#setBrightness-double-}
```
public final void setBrightness(double value)
```


Imposta la luminosità dell'immagine. Il valore per questa proprietà deve
essere un numero da 0.0 (più scuro) a 1.0 (più luminoso).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | double | Il valore predefinito è 0.5. |
|

### getContrast() {#getContrast--}
```
public final double getContrast()
```


Ottiene il contrasto per l'immagine specificata. Il valore per questa proprietà
deve essere un numero da 0.0 (il contrasto più basso) a 1.0 (il contrasto più alto).


**Returns:**
double - Il valore predefinito è 0.5.

### setContrast(double value) {#setContrast-double-}
```
public final void setContrast(double value)
```


Imposta il contrasto per l'immagine specificata. Il valore per questa proprietà
deve essere un numero da 0.0 (il contrasto più basso) a 1.0 (il contrasto più alto).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | double | Il valore predefinito è 0.5. |
|

