---
title: "Margins"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt Rand-Einstellungen für jede Kante eines Objekts dar."
type: docs
weight: 15
url: /de/java/com.groupdocs.watermark.watermarks/margins/
---
**Inheritance:**
java.lang.Object
```
public class Margins
```

Stellt Rand-Einstellungen für jede Kante eines Objekts dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [Margins()](#Margins--) | Initialisiert eine neue Instanz der `[Margins](../../com.groupdocs.watermark.watermarks/margins)`‑Klasse. |
|
|  | [Margins(int marginType, double left, double right, double top, double bottom)](#Margins-int-double-double-double-double-) | Initialisiert eine neue Instanz der `[Margins](../../com.groupdocs.watermark.watermarks/margins)`‑Klasse mit dem angegebenen Typ, der Position und der Größe. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getMarginType()](#getMarginType--) | Ruft `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)` ab. |
|
|  | [setMarginType(int value)](#setMarginType-int-) | Setzt `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`. |
|
|  | [getLeft()](#getLeft--) | Liest den linken Rand. |
|
|  | [setLeft(double value)](#setLeft-double-) | Setzt den linken Rand. |
|
|  | [getRight()](#getRight--) | Liest den rechten Rand. |
|
|  | [setRight(double value)](#setRight-double-) | Setzt den rechten Rand. |
|
|  | [getTop()](#getTop--) | Liest den oberen Rand. |
|
|  | [setTop(double value)](#setTop-double-) | Setzt den oberen Rand. |
|
|  | [getBottom()](#getBottom--) | Liest den unteren Rand. |
|
|  | [setBottom(double value)](#setBottom-double-) | Setzt den unteren Rand. |
|
### Margins() {#Margins--}
```
public Margins()
```


Initialisiert eine neue Instanz der `[Margins](../../com.groupdocs.watermark.watermarks/margins)`‑Klasse.


### Margins(int marginType, double left, double right, double top, double bottom) {#Margins-int-double-double-double-double-}
```
public Margins(int marginType, double left, double right, double top, double bottom)
```


Initialisiert eine neue Instanz der `[Margins](../../com.groupdocs.watermark.watermarks/margins)`‑Klasse mit dem angegebenen Typ, der Position und der Größe.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | marginType | int | Der `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`. Gibt an, wie Randwerte interpretiert werden sollen. |
|
|  | links | double | Der Wert des linken Randes. |
|
|  | rechts | double | Der Wert des rechten Randes. |
|
|  | oben | double | Der Wert des oberen Randes. |
|
|  | unten | double | Der Wert des unteren Randes. |
|

### getMarginType() {#getMarginType--}
```
public final int getMarginType()
```


Liest `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`. Das Setzen eines neuen Werts für diese Eigenschaft setzt alle Ränder automatisch auf ihre Standardwerte (null) zurück.

Der Standardwert ist `[MarginType.Absolute](../../com.groupdocs.watermark.watermarks/margintype#Absolute)`


**Returns:**
int - Der Wert, der angibt, wie Ränder interpretiert werden sollen.

### setMarginType(int value) {#setMarginType-int-}
```
public final void setMarginType(int value)
```


Setzt `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`. Das Setzen eines neuen Werts für diese Eigenschaft setzt alle Ränder automatisch auf ihre Standardwerte (null) zurück.

Der Standardwert ist `[MarginType.Absolute](../../com.groupdocs.watermark.watermarks/margintype#Absolute)`


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | int | Der Wert, der angibt, wie Ränder interpretiert werden sollen. |
|

### getLeft() {#getLeft--}
```
public final double getLeft()
```


Liest den linken Rand.


**Returns:**
double - Horizontaler Versatz vom linken Rand des übergeordneten Elements.

### setLeft(double value) {#setLeft-double-}
```
public final void setLeft(double value)
```


Setzt den linken Rand.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | double | Horizontaler Versatz vom linken Rand des übergeordneten Elements. |
|

### getRight() {#getRight--}
```
public final double getRight()
```


Liest den rechten Rand.


**Returns:**
double - Horizontaler Versatz vom rechten Rand des übergeordneten Elements.

### setRight(double value) {#setRight-double-}
```
public final void setRight(double value)
```


Setzt den rechten Rand.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | double | Horizontaler Versatz vom rechten Rand des übergeordneten Elements. |
|

### getTop() {#getTop--}
```
public final double getTop()
```


Liest den oberen Rand.


**Returns:**
double - Horizontaler Versatz vom oberen Rand des übergeordneten Elements.

### setTop(double value) {#setTop-double-}
```
public final void setTop(double value)
```


Setzt den oberen Rand.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | double | Horizontaler Versatz vom oberen Rand des übergeordneten Elements. |
|

### getBottom() {#getBottom--}
```
public final double getBottom()
```


Liest den unteren Rand.


**Returns:**
double - Horizontaler Versatz vom unteren Rand des übergeordneten Elements.

### setBottom(double value) {#setBottom-double-}
```
public final void setBottom(double value)
```


Setzt den unteren Rand.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | double | Horizontaler Versatz vom unteren Rand des übergeordneten Elements. |
|

