---
title: "MarginType"
second_title: "GroupDocs.Watermark pour Java Référence API"
description: "Spécifie comment les valeurs de marge doivent être interprétées."
type: docs
weight: 14
url: /fr/java/com.groupdocs.watermark.watermarks/margintype/
---
**Inheritance:**
java.lang.Object
```
public final class MarginType
```

Spécifie comment les valeurs de marge doivent être interprétées.

## Champs

| Champ | Description |
| --- | --- |
|  | [Absolute](#Absolute) | Valeur de marge mesurée en unités de contenu. |
|
|  | [RelativeToParentDimensions](#RelativeToParentDimensions) | La valeur de marge doit être interprétée comme une portion de la dimension parent appropriée. |
|
|  | [RelativeToParentMinDimension](#RelativeToParentMinDimension) | La valeur de marge doit être interprétée comme une portion de la dimension minimale du parent. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [toString(int value)](#toString-int-) | Renvoie une représentation sous forme de chaîne de la valeur `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`. |
|
|  | [parse(String value)](#parse-java.lang.String-) | Analyse une chaîne pour obtenir une valeur d'énumération `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`. |
|
### Absolute {#Absolute}
```
public static final int Absolute
```


Valeur de marge mesurée en unités de contenu.


### RelativeToParentDimensions {#RelativeToParentDimensions}
```
public static final int RelativeToParentDimensions
```


La valeur de marge doit être interprétée comme une portion de la dimension parent appropriée.


Les marges gauche et droite sont relatives à la largeur du parent,
les marges supérieure et inférieure sont relatives à la hauteur du parent.
Si ce type est choisi, la valeur de marge doit être comprise entre 0.0 et 1.0.


### RelativeToParentMinDimension {#RelativeToParentMinDimension}
```
public static final int RelativeToParentMinDimension
```


La valeur de marge doit être interprétée comme une portion de la dimension minimale du parent.


Si ce type est choisi, la valeur de marge doit être comprise entre 0.0 et 1.0.


### toString(int value) {#toString-int-}
```
public static final String toString(int value)
```


Renvoie une représentation sous forme de chaîne de la valeur `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | int | La valeur à convertir. |
|

**Returns:**
java.lang.String - La représentation sous forme de chaîne de la valeur `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`.

### parse(String value) {#parse-java.lang.String-}
```
public static final int parse(String value)
```


Analyse une chaîne pour obtenir une valeur d'énumération `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | java.lang.String | La chaîne à analyser. |
|

**Returns:**
int - La valeur d'énumération `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`.

