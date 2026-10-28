---
title: "Margins"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: "Stelt marge‑instellingen voor elke rand van een object voor."
type: docs
weight: 15
url: /nl/java/com.groupdocs.watermark.watermarks/margins/
---
**Inheritance:**
java.lang.Object
```
public class Margins
```

Stelt marge‑instellingen voor elke rand van een object voor.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [Margins()](#Margins--) | Initialiseert een nieuw exemplaar van de `[Margins](../../com.groupdocs.watermark.watermarks/margins)` klasse. |
|
|  | [Margins(int marginType, double left, double right, double top, double bottom)](#Margins-int-double-double-double-double-) | Initialiseert een nieuw exemplaar van de `[Margins](../../com.groupdocs.watermark.watermarks/margins)` klasse met het opgegeven type, locatie en grootte. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getMarginType()](#getMarginType--) | Haalt `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)` op. |
|
|  | [setMarginType(int value)](#setMarginType-int-) | Stelt `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)` in. |
|
|  | [getLeft()](#getLeft--) | Haalt de linkermarge op. |
|
|  | [setLeft(double value)](#setLeft-double-) | Stelt de linkermarge in. |
|
|  | [getRight()](#getRight--) | Haalt de rechtermarge op. |
|
|  | [setRight(double value)](#setRight-double-) | Stelt de rechtermarge in. |
|
|  | [getTop()](#getTop--) | Haalt de bovenmarge op. |
|
|  | [setTop(double value)](#setTop-double-) | Stelt de bovenmarge in. |
|
|  | [getBottom()](#getBottom--) | Haalt de ondermarge op. |
|
|  | [setBottom(double value)](#setBottom-double-) | Stelt de ondermarge in. |
|
### Margins() {#Margins--}
```
public Margins()
```


Initialiseert een nieuw exemplaar van de `[Margins](../../com.groupdocs.watermark.watermarks/margins)` klasse.


### Margins(int marginType, double left, double right, double top, double bottom) {#Margins-int-double-double-double-double-}
```
public Margins(int marginType, double left, double right, double top, double bottom)
```


Initialiseert een nieuw exemplaar van de `[Margins](../../com.groupdocs.watermark.watermarks/margins)` klasse met het opgegeven type, locatie en grootte.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | marginType | int | De `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`. Geeft aan hoe marges moeten worden geïnterpreteerd. |
|
|  | links | double | De waarde van de linkermarge. |
|
|  | rechts | double | De waarde van de rechtermarge. |
|
|  | boven | double | De waarde van de bovenmarge. |
|
|  | onder | double | De waarde van de ondermarge. |
|

### getMarginType() {#getMarginType--}
```
public final int getMarginType()
```


Haalt `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)` op. Het instellen van een nieuwe waarde voor deze eigenschap zet automatisch alle marges terug naar hun standaardwaarden (nul).

De standaardwaarde is `[MarginType.Absolute](../../com.groupdocs.watermark.watermarks/margintype#Absolute)`


**Returns:**
int - De waarde die aangeeft hoe marges moeten worden geïnterpreteerd.

### setMarginType(int value) {#setMarginType-int-}
```
public final void setMarginType(int value)
```


Stelt `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)` in. Het instellen van een nieuwe waarde voor deze eigenschap zet automatisch alle marges terug naar hun standaardwaarden (nul).

De standaardwaarde is `[MarginType.Absolute](../../com.groupdocs.watermark.watermarks/margintype#Absolute)`


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | int | De waarde die aangeeft hoe marges moeten worden geïnterpreteerd. |
|

### getLeft() {#getLeft--}
```
public final double getLeft()
```


Haalt de linkermarge op.


**Returns:**
double - Horizontale offset vanaf de linkerrand van de bovenliggende container.

### setLeft(double value) {#setLeft-double-}
```
public final void setLeft(double value)
```


Stelt de linkermarge in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | double | Horizontale offset vanaf de linkerrand van de bovenliggende container. |
|

### getRight() {#getRight--}
```
public final double getRight()
```


Haalt de rechtermarge op.


**Returns:**
double - Horizontale offset vanaf de rechterrand van de bovenliggende container.

### setRight(double value) {#setRight-double-}
```
public final void setRight(double value)
```


Stelt de rechtermarge in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | double | Horizontale offset vanaf de rechterrand van de bovenliggende container. |
|

### getTop() {#getTop--}
```
public final double getTop()
```


Haalt de bovenmarge op.


**Returns:**
double - Horizontale offset vanaf de bovenrand van de bovenliggende container.

### setTop(double value) {#setTop-double-}
```
public final void setTop(double value)
```


Stelt de bovenmarge in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | double | Horizontale offset vanaf de bovenrand van de bovenliggende container. |
|

### getBottom() {#getBottom--}
```
public final double getBottom()
```


Haalt de ondermarge op.


**Returns:**
double - Horizontale offset vanaf de onderrand van de bovenliggende container.

### setBottom(double value) {#setBottom-double-}
```
public final void setBottom(double value)
```


Stelt de ondermarge in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | double | Horizontale offset vanaf de onderrand van de bovenliggende container. |
|

