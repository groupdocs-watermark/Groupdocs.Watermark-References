---
title: "Margins"
second_title: "GroupDocs.Watermark pour Java Référence API"
description: "Représente les paramètres de marge pour chaque bord d'un objet."
type: docs
weight: 15
url: /fr/java/com.groupdocs.watermark.watermarks/margins/
---
**Inheritance:**
java.lang.Object
```
public class Margins
```

Représente les paramètres de marge pour chaque bord d'un objet.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [Margins()](#Margins--) | Initialise une nouvelle instance de la classe `[Margins](../../com.groupdocs.watermark.watermarks/margins)`. |
|
|  | [Margins(int marginType, double left, double right, double top, double bottom)](#Margins-int-double-double-double-double-) | Initialise une nouvelle instance de la classe `[Margins](../../com.groupdocs.watermark.watermarks/margins)` avec le type, l'emplacement et la taille spécifiés. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getMarginType()](#getMarginType--) | Obtient `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`. |
|
|  | [setMarginType(int value)](#setMarginType-int-) | Définit `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`. |
|
|  | [getLeft()](#getLeft--) | Obtient la marge gauche. |
|
|  | [setLeft(double value)](#setLeft-double-) | Définit la marge gauche. |
|
|  | [getRight()](#getRight--) | Obtient la marge droite. |
|
|  | [setRight(double value)](#setRight-double-) | Définit la marge droite. |
|
|  | [getTop()](#getTop--) | Obtient la marge supérieure. |
|
|  | [setTop(double value)](#setTop-double-) | Définit la marge supérieure. |
|
|  | [getBottom()](#getBottom--) | Obtient la marge inférieure. |
|
|  | [setBottom(double value)](#setBottom-double-) | Définit la marge inférieure. |
|
### Margins() {#Margins--}
```
public Margins()
```


Initialise une nouvelle instance de la classe `[Margins](../../com.groupdocs.watermark.watermarks/margins)`.


### Margins(int marginType, double left, double right, double top, double bottom) {#Margins-int-double-double-double-double-}
```
public Margins(int marginType, double left, double right, double top, double bottom)
```


Initialise une nouvelle instance de la classe `[Margins](../../com.groupdocs.watermark.watermarks/margins)` avec le type, l'emplacement et la taille spécifiés.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | marginType | int | Le `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`. Spécifie comment les valeurs de marge doivent être interprétées. |
|
|  | gauche | double | La valeur de la marge gauche. |
|
|  | droite | double | La valeur de la marge droite. |
|
|  | haut | double | La valeur de la marge supérieure. |
|
|  | bas | double | La valeur de la marge inférieure. |
|

### getMarginType() {#getMarginType--}
```
public final int getMarginType()
```


Obtient `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`. Définir une nouvelle valeur à cette propriété réinitialise automatiquement toutes les marges à leurs valeurs par défaut (zéro).

La valeur par défaut est `[MarginType.Absolute](../../com.groupdocs.watermark.watermarks/margintype#Absolute)`


**Returns:**
int - La valeur spécifiant comment les marges doivent être interprétées.

### setMarginType(int value) {#setMarginType-int-}
```
public final void setMarginType(int value)
```


Définit `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`. Définir une nouvelle valeur à cette propriété réinitialise automatiquement toutes les marges à leurs valeurs par défaut (zéro).

La valeur par défaut est `[MarginType.Absolute](../../com.groupdocs.watermark.watermarks/margintype#Absolute)`


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | int | La valeur spécifiant comment les marges doivent être interprétées. |
|

### getLeft() {#getLeft--}
```
public final double getLeft()
```


Obtient la marge gauche.


**Returns:**
double - Décalage horizontal depuis la bordure gauche du parent.

### setLeft(double value) {#setLeft-double-}
```
public final void setLeft(double value)
```


Définit la marge gauche.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | double | Décalage horizontal depuis la bordure gauche du parent. |
|

### getRight() {#getRight--}
```
public final double getRight()
```


Obtient la marge droite.


**Returns:**
double - Décalage horizontal depuis la bordure droite du parent.

### setRight(double value) {#setRight-double-}
```
public final void setRight(double value)
```


Définit la marge droite.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | double | Décalage horizontal depuis la bordure droite du parent. |
|

### getTop() {#getTop--}
```
public final double getTop()
```


Obtient la marge supérieure.


**Returns:**
double - Décalage horizontal depuis la bordure supérieure du parent.

### setTop(double value) {#setTop-double-}
```
public final void setTop(double value)
```


Définit la marge supérieure.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | double | Décalage horizontal depuis la bordure supérieure du parent. |
|

### getBottom() {#getBottom--}
```
public final double getBottom()
```


Obtient la marge inférieure.


**Returns:**
double - Décalage horizontal depuis la bordure inférieure du parent.

### setBottom(double value) {#setBottom-double-}
```
public final void setBottom(double value)
```


Définit la marge inférieure.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | double | Décalage horizontal depuis la bordure inférieure du parent. |
|

