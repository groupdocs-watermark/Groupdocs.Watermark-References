---
title: "Margins"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Rappresenta le impostazioni dei margini per ogni bordo di un oggetto."
type: docs
weight: 15
url: /it/java/com.groupdocs.watermark.watermarks/margins/
---
**Inheritance:**
java.lang.Object
```
public class Margins
```

Rappresenta le impostazioni dei margini per ogni bordo di un oggetto.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [Margins()](#Margins--) | Inizializza una nuova istanza della classe `[Margins](../../com.groupdocs.watermark.watermarks/margins)`. |
|
|  | [Margins(int marginType, double left, double right, double top, double bottom)](#Margins-int-double-double-double-double-) | Inizializza una nuova istanza della classe `[Margins](../../com.groupdocs.watermark.watermarks/margins)` con il tipo, la posizione e le dimensioni specificati. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getMarginType()](#getMarginType--) | Ottiene `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`. |
|
|  | [setMarginType(int value)](#setMarginType-int-) | Imposta `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`. |
|
|  | [getLeft()](#getLeft--) | Ottiene il margine sinistro. |
|
|  | [setLeft(double value)](#setLeft-double-) | Imposta il margine sinistro. |
|
|  | [getRight()](#getRight--) | Ottiene il margine destro. |
|
|  | [setRight(double value)](#setRight-double-) | Imposta il margine destro. |
|
|  | [getTop()](#getTop--) | Ottiene il margine superiore. |
|
|  | [setTop(double value)](#setTop-double-) | Imposta il margine superiore. |
|
|  | [getBottom()](#getBottom--) | Ottiene il margine inferiore. |
|
|  | [setBottom(double value)](#setBottom-double-) | Imposta il margine inferiore. |
|
### Margins() {#Margins--}
```
public Margins()
```


Inizializza una nuova istanza della classe `[Margins](../../com.groupdocs.watermark.watermarks/margins)`.


### Margins(int marginType, double left, double right, double top, double bottom) {#Margins-int-double-double-double-double-}
```
public Margins(int marginType, double left, double right, double top, double bottom)
```


Inizializza una nuova istanza della classe `[Margins](../../com.groupdocs.watermark.watermarks/margins)` con il tipo, la posizione e le dimensioni specificati.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | marginType | int | Il `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`. Specifica come devono essere interpretati i valori dei margini. |
|
|  | sinistra | double | Il valore del margine sinistro. |
|
|  | destra | double | Il valore del margine destro. |
|
|  | superiore | double | Il valore del margine superiore. |
|
|  | inferiore | double | Il valore del margine inferiore. |
|

### getMarginType() {#getMarginType--}
```
public final int getMarginType()
```


Ottiene `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`. Impostare un nuovo valore per questa proprietà riporta automaticamente tutti i margini ai loro valori predefiniti (zero).

Il valore predefinito è `[MarginType.Absolute](../../com.groupdocs.watermark.watermarks/margintype#Absolute)`


**Returns:**
int - Il valore che specifica come devono essere interpretati i margini.

### setMarginType(int value) {#setMarginType-int-}
```
public final void setMarginType(int value)
```


Imposta `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`. Impostare un nuovo valore per questa proprietà riporta automaticamente tutti i margini ai loro valori predefiniti (zero).

Il valore predefinito è `[MarginType.Absolute](../../com.groupdocs.watermark.watermarks/margintype#Absolute)`


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | int | Il valore che specifica come devono essere interpretati i margini. |
|

### getLeft() {#getLeft--}
```
public final double getLeft()
```


Ottiene il margine sinistro.


**Returns:**
double - Offset orizzontale dal bordo sinistro del genitore.

### setLeft(double value) {#setLeft-double-}
```
public final void setLeft(double value)
```


Imposta il margine sinistro.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | double | Offset orizzontale dal bordo sinistro del genitore. |
|

### getRight() {#getRight--}
```
public final double getRight()
```


Ottiene il margine destro.


**Returns:**
double - Offset orizzontale dal bordo destro del genitore.

### setRight(double value) {#setRight-double-}
```
public final void setRight(double value)
```


Imposta il margine destro.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | double | Offset orizzontale dal bordo destro del genitore. |
|

### getTop() {#getTop--}
```
public final double getTop()
```


Ottiene il margine superiore.


**Returns:**
double - Offset orizzontale dal bordo superiore del genitore.

### setTop(double value) {#setTop-double-}
```
public final void setTop(double value)
```


Imposta il margine superiore.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | double | Offset orizzontale dal bordo superiore del genitore. |
|

### getBottom() {#getBottom--}
```
public final double getBottom()
```


Ottiene il margine inferiore.


**Returns:**
double - Offset orizzontale dal bordo inferiore del genitore.

### setBottom(double value) {#setBottom-double-}
```
public final void setBottom(double value)
```


Imposta il margine inferiore.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | double | Offset orizzontale dal bordo inferiore del genitore. |
|

