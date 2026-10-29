---
title: "Margins"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Representerar marginalinställningar för varje kant av ett objekt."
type: docs
weight: 15
url: /sv/java/com.groupdocs.watermark.watermarks/margins/
---
**Inheritance:**
java.lang.Object
```
public class Margins
```

Representerar marginalinställningar för varje kant av ett objekt.

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [Margins()](#Margins--) | Initierar en ny instans av klassen `[Margins](../../com.groupdocs.watermark.watermarks/margins)`. |
|
|  | [Margins(int marginType, double left, double right, double top, double bottom)](#Margins-int-double-double-double-double-) | Initierar en ny instans av klassen `[Margins](../../com.groupdocs.watermark.watermarks/margins)` med den angivna typen, platsen och storleken. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getMarginType()](#getMarginType--) | Hämtar `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`. |
|
|  | [setMarginType(int value)](#setMarginType-int-) | Ställer in `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`. |
|
|  | [getLeft()](#getLeft--) | Hämtar den vänstra marginalen. |
|
|  | [setLeft(double value)](#setLeft-double-) | Ställer in den vänstra marginalen. |
|
|  | [getRight()](#getRight--) | Hämtar den högra marginalen. |
|
|  | [setRight(double value)](#setRight-double-) | Ställer in den högra marginalen. |
|
|  | [getTop()](#getTop--) | Hämtar den övre marginalen. |
|
|  | [setTop(double value)](#setTop-double-) | Ställer in den övre marginalen. |
|
|  | [getBottom()](#getBottom--) | Hämtar den nedre marginalen. |
|
|  | [setBottom(double value)](#setBottom-double-) | Ställer in den nedre marginalen. |
|
### Margins() {#Margins--}
```
public Margins()
```


Initierar en ny instans av klassen `[Margins](../../com.groupdocs.watermark.watermarks/margins)`.


### Margins(int marginType, double left, double right, double top, double bottom) {#Margins-int-double-double-double-double-}
```
public Margins(int marginType, double left, double right, double top, double bottom)
```


Initierar en ny instans av klassen `[Margins](../../com.groupdocs.watermark.watermarks/margins)` med den angivna typen, platsen och storleken.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | marginType | int | Den `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`. Anger hur marginalvärden ska tolkas. |
|
|  | vänster | double | Värdet för den vänstra marginalen. |
|
|  | höger | double | Värdet för den högra marginalen. |
|
|  | övre | double | Värdet för den övre marginalen. |
|
|  | nedre | double | Värdet för den nedre marginalen. |
|

### getMarginType() {#getMarginType--}
```
public final int getMarginType()
```


Hämtar `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`. Att sätta ett nytt värde på denna egenskap återställer automatiskt alla marginaler till sina standardvärden (noll).

Standardvärdet är `[MarginType.Absolute](../../com.groupdocs.watermark.watermarks/margintype#Absolute)`


**Returns:**
int - Värdet som anger hur marginaler ska tolkas.

### setMarginType(int value) {#setMarginType-int-}
```
public final void setMarginType(int value)
```


Ställer in `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`. Att sätta ett nytt värde på denna egenskap återställer automatiskt alla marginaler till sina standardvärden (noll).

Standardvärdet är `[MarginType.Absolute](../../com.groupdocs.watermark.watermarks/margintype#Absolute)`


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | int | Värdet som anger hur marginaler ska tolkas. |
|

### getLeft() {#getLeft--}
```
public final double getLeft()
```


Hämtar den vänstra marginalen.


**Returns:**
double - Horisontell förskjutning från förälderns vänstra kant.

### setLeft(double value) {#setLeft-double-}
```
public final void setLeft(double value)
```


Ställer in den vänstra marginalen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | double | Horisontell förskjutning från förälderns vänstra kant. |
|

### getRight() {#getRight--}
```
public final double getRight()
```


Hämtar den högra marginalen.


**Returns:**
double - Horisontell förskjutning från förälderns högra kant.

### setRight(double value) {#setRight-double-}
```
public final void setRight(double value)
```


Ställer in den högra marginalen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | double | Horisontell förskjutning från förälderns högra kant. |
|

### getTop() {#getTop--}
```
public final double getTop()
```


Hämtar den övre marginalen.


**Returns:**
double - Horisontell förskjutning från förälderns övre kant.

### setTop(double value) {#setTop-double-}
```
public final void setTop(double value)
```


Ställer in den övre marginalen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | double | Horisontell förskjutning från förälderns övre kant. |
|

### getBottom() {#getBottom--}
```
public final double getBottom()
```


Hämtar den nedre marginalen.


**Returns:**
double - Horisontell förskjutning från förälderns nedre kant.

### setBottom(double value) {#setBottom-double-}
```
public final void setBottom(double value)
```


Ställer in den nedre marginalen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | double | Horisontell förskjutning från förälderns nedre kant. |
|

