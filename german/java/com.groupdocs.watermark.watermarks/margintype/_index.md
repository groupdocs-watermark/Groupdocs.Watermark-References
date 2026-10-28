---
title: "MarginType"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Gibt an, wie Randwerte interpretiert werden sollen."
type: docs
weight: 14
url: /de/java/com.groupdocs.watermark.watermarks/margintype/
---
**Inheritance:**
java.lang.Object
```
public final class MarginType
```

Gibt an, wie Randwerte interpretiert werden sollen.

## Felder

| Feld | Beschreibung |
| --- | --- |
|  | [Absolute](#Absolute) | Margin-Wert gemessen in Inhaltseinheiten. |
|
|  | [RelativeToParentDimensions](#RelativeToParentDimensions) | Der Margin-Wert sollte als ein Anteil der entsprechenden übergeordneten Dimension interpretiert werden. |
|
|  | [RelativeToParentMinDimension](#RelativeToParentMinDimension) | Der Margin-Wert sollte als ein Anteil der minimalen übergeordneten Dimension interpretiert werden. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [toString(int value)](#toString-int-) | Gibt eine String‑Darstellung des `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`‑Werts zurück. |
|
|  | [parse(String value)](#parse-java.lang.String-) | Parst einen String in einen `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)` Aufzählungswert. |
|
### Absolute {#Absolute}
```
public static final int Absolute
```


Margin-Wert gemessen in Inhaltseinheiten.


### RelativeToParentDimensions {#RelativeToParentDimensions}
```
public static final int RelativeToParentDimensions
```


Der Margin-Wert sollte als ein Anteil der entsprechenden übergeordneten Dimension interpretiert werden.


Linke und rechte Ränder beziehen sich auf die Breite des übergeordneten Elements,
obere und untere Ränder beziehen sich auf die Höhe des übergeordneten Elements.
Wenn dieser Typ gewählt wird, muss der Margin-Wert zwischen 0,0 und 1,0 liegen.


### RelativeToParentMinDimension {#RelativeToParentMinDimension}
```
public static final int RelativeToParentMinDimension
```


Der Margin-Wert sollte als ein Anteil der minimalen übergeordneten Dimension interpretiert werden.


Wenn dieser Typ gewählt wird, muss der Margin-Wert zwischen 0,0 und 1,0 liegen.


### toString(int value) {#toString-int-}
```
public static final String toString(int value)
```


Gibt eine String‑Darstellung des `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`‑Werts zurück.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | int | Der zu konvertierende Wert. |
|

**Returns:**
java.lang.String – Die String‑Darstellung des `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`‑Werts.

### parse(String value) {#parse-java.lang.String-}
```
public static final int parse(String value)
```


Parst einen String in einen `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)` Aufzählungswert.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | java.lang.String | Die zu parsende Zeichenkette. |
|

**Returns:**
int – Der `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)` Aufzählungswert.

