---
title: "SizingType"
second_title: "GroupDocs.Watermark pour Java Référence API"
description: "Spécifie comment la taille du filigrane doit être calculée."
type: docs
weight: 16
url: /fr/java/com.groupdocs.watermark.watermarks/sizingtype/
---
**Inheritance:**
java.lang.Object
```
public final class SizingType
```

Spécifie comment la taille du filigrane doit être calculée.

## Champs

| Champ | Description |
| --- | --- |
|  | [Auto](#Auto) | Le filigrane doit être dimensionné automatiquement en fonction de son contenu. |
|
|  | [Absolute](#Absolute) | Le filigrane doit être dimensionné à une largeur exacte `[Watermark.getWidth()](../../com.groupdocs.watermark/watermark#getWidth--)` |
et `[Watermark.getHeight()](../../com.groupdocs.watermark/watermark#getHeight--)`.
|
|  | [ScaleToParentDimensions](#ScaleToParentDimensions) | Le filigrane doit être mis à l'échelle par rapport aux dimensions du parent en utilisant |
le `[Watermark.getScaleFactor()](../../com.groupdocs.watermark/watermark#getScaleFactor--)` spécifié.
|
|  | [ScaleToParentArea](#ScaleToParentArea) | Le filigrane doit être mis à l'échelle par rapport à la zone du parent en utilisant le `[Watermark.getScaleFactor()](../../com.groupdocs.watermark/watermark#getScaleFactor--)` spécifié. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [toString(int value)](#toString-int-) | Renvoie une représentation sous forme de chaîne de la valeur `[SizingType](../../com.groupdocs.watermark.watermarks/sizingtype)`. |
|
|  | [parse(String value)](#parse-java.lang.String-) | Analyse une chaîne pour obtenir une valeur d'énumération `[SizingType](../../com.groupdocs.watermark.watermarks/sizingtype)`. |
|
### Auto {#Auto}
```
public static final int Auto
```


Le filigrane doit être dimensionné automatiquement en fonction de son contenu.


### Absolute {#Absolute}
```
public static final int Absolute
```


Le filigrane doit être dimensionné à une largeur exacte `[Watermark.getWidth()](../../com.groupdocs.watermark/watermark#getWidth--)`
et `[Watermark.getHeight()](../../com.groupdocs.watermark/watermark#getHeight--)`.


### ScaleToParentDimensions {#ScaleToParentDimensions}
```
public static final int ScaleToParentDimensions
```


Le filigrane doit être mis à l'échelle par rapport aux dimensions du parent en utilisant
le `[Watermark.getScaleFactor()](../../com.groupdocs.watermark/watermark#getScaleFactor--)` spécifié.


### ScaleToParentArea {#ScaleToParentArea}
```
public static final int ScaleToParentArea
```


Le filigrane doit être mis à l'échelle par rapport à la zone du parent en utilisant le `[Watermark.getScaleFactor()](../../com.groupdocs.watermark/watermark#getScaleFactor--)` spécifié.


### toString(int value) {#toString-int-}
```
public static final String toString(int value)
```


Renvoie une représentation sous forme de chaîne de la valeur `[SizingType](../../com.groupdocs.watermark.watermarks/sizingtype)`.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | int | La valeur à convertir. |
|

**Returns:**
java.lang.String - La représentation sous forme de chaîne de la valeur `[SizingType](../../com.groupdocs.watermark.watermarks/sizingtype)`.

### parse(String value) {#parse-java.lang.String-}
```
public static final int parse(String value)
```


Analyse une chaîne pour obtenir une valeur d'énumération `[SizingType](../../com.groupdocs.watermark.watermarks/sizingtype)`.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | java.lang.String | La chaîne à analyser. |
|

**Returns:**
int - La valeur d'énumération `[SizingType](../../com.groupdocs.watermark.watermarks/sizingtype)`.

