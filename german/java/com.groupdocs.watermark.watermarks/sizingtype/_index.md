---
title: "SizingType"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Gibt an, wie die Größe des Wasserzeichens berechnet werden soll."
type: docs
weight: 16
url: /de/java/com.groupdocs.watermark.watermarks/sizingtype/
---
**Inheritance:**
java.lang.Object
```
public final class SizingType
```

Gibt an, wie die Größe des Wasserzeichens berechnet werden soll.

## Felder

| Feld | Beschreibung |
| --- | --- |
|  | [Auto](#Auto) | Wasserzeichen sollte automatisch anhand seines Inhalts skaliert werden. |
|
|  | [Absolute](#Absolute) | Wasserzeichen sollte auf eine exakte `[Watermark.getWidth()](../../com.groupdocs.watermark/watermark#getWidth--)` |
und `[Watermark.getHeight()](../../com.groupdocs.watermark/watermark#getHeight--)`.
|
|  | [ScaleToParentDimensions](#ScaleToParentDimensions) | Wasserzeichen sollte relativ zu den Abmessungen des übergeordneten Elements skaliert werden, indem |
angegebenen `[Watermark.getScaleFactor()](../../com.groupdocs.watermark/watermark#getScaleFactor--)`.
|
|  | [ScaleToParentArea](#ScaleToParentArea) | Wasserzeichen sollte relativ zur Fläche des übergeordneten Elements skaliert werden, indem der angegebene `[Watermark.getScaleFactor()](../../com.groupdocs.watermark/watermark#getScaleFactor--)` verwendet wird. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [toString(int value)](#toString-int-) | Gibt eine Zeichenkettenrepräsentation des `[SizingType](../../com.groupdocs.watermark.watermarks/sizingtype)`-Werts zurück. |
|
|  | [parse(String value)](#parse-java.lang.String-) | Parst eine Zeichenkette in einen `[SizingType](../../com.groupdocs.watermark.watermarks/sizingtype)`-Aufzählungswert. |
|
### Auto {#Auto}
```
public static final int Auto
```


Wasserzeichen sollte automatisch anhand seines Inhalts skaliert werden.


### Absolute {#Absolute}
```
public static final int Absolute
```


Wasserzeichen sollte auf eine exakte `[Watermark.getWidth()](../../com.groupdocs.watermark/watermark#getWidth--)`
und `[Watermark.getHeight()](../../com.groupdocs.watermark/watermark#getHeight--)`.


### ScaleToParentDimensions {#ScaleToParentDimensions}
```
public static final int ScaleToParentDimensions
```


Wasserzeichen sollte relativ zu den Abmessungen des übergeordneten Elements skaliert werden, indem
angegebenen `[Watermark.getScaleFactor()](../../com.groupdocs.watermark/watermark#getScaleFactor--)`.


### ScaleToParentArea {#ScaleToParentArea}
```
public static final int ScaleToParentArea
```


Wasserzeichen sollte relativ zur Fläche des übergeordneten Elements skaliert werden, indem der angegebene `[Watermark.getScaleFactor()](../../com.groupdocs.watermark/watermark#getScaleFactor--)` verwendet wird.


### toString(int value) {#toString-int-}
```
public static final String toString(int value)
```


Gibt eine Zeichenkettenrepräsentation des `[SizingType](../../com.groupdocs.watermark.watermarks/sizingtype)`-Werts zurück.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | int | Der zu konvertierende Wert. |
|

**Returns:**
java.lang.String - Die Zeichenkettenrepräsentation des `[SizingType](../../com.groupdocs.watermark.watermarks/sizingtype)`-Werts.

### parse(String value) {#parse-java.lang.String-}
```
public static final int parse(String value)
```


Parst eine Zeichenkette in einen `[SizingType](../../com.groupdocs.watermark.watermarks/sizingtype)`-Aufzählungswert.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | java.lang.String | Die zu parsende Zeichenkette. |
|

**Returns:**
int - Der `[SizingType](../../com.groupdocs.watermark.watermarks/sizingtype)`-Aufzählungswert.

