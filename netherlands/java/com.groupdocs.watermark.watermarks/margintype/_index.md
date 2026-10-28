---
title: "MarginType"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: "Specificeert hoe marge‑waarden geïnterpreteerd moeten worden."
type: docs
weight: 14
url: /nl/java/com.groupdocs.watermark.watermarks/margintype/
---
**Inheritance:**
java.lang.Object
```
public final class MarginType
```

Specificeert hoe marge‑waarden geïnterpreteerd moeten worden.

## Velden

| Veld | Beschrijving |
| --- | --- |
|  | [Absolute](#Absolute) | Margewaarde gemeten in inhoudseenheden. |
|
|  | [RelativeToParentDimensions](#RelativeToParentDimensions) | Margewaarde moet worden geïnterpreteerd als een deel van de juiste bovenliggende dimensie. |
|
|  | [RelativeToParentMinDimension](#RelativeToParentMinDimension) | Margewaarde moet worden geïnterpreteerd als een deel van de minimale dimensie van de bovenliggende. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [toString(int value)](#toString-int-) | Retourneert een tekenreeksrepresentatie van de `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)` waarde. |
|
|  | [parse(String value)](#parse-java.lang.String-) | Parseert een string naar een `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)` enumeratiewaarde. |
|
### Absolute {#Absolute}
```
public static final int Absolute
```


Margewaarde gemeten in inhoudseenheden.


### RelativeToParentDimensions {#RelativeToParentDimensions}
```
public static final int RelativeToParentDimensions
```


Margewaarde moet worden geïnterpreteerd als een deel van de juiste bovenliggende dimensie.


Linker- en rechtermarges zijn relatief ten opzichte van de breedte van de bovenliggende,
boven- en ondermarges zijn relatief ten opzichte van de hoogte van de bovenliggende.
Als dit type wordt gekozen, moet de margewaarde tussen 0,0 en 1,0 liggen.


### RelativeToParentMinDimension {#RelativeToParentMinDimension}
```
public static final int RelativeToParentMinDimension
```


Margewaarde moet worden geïnterpreteerd als een deel van de minimale dimensie van de bovenliggende.


Als dit type wordt gekozen, moet de margewaarde tussen 0,0 en 1,0 liggen.


### toString(int value) {#toString-int-}
```
public static final String toString(int value)
```


Retourneert een tekenreeksrepresentatie van de `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)` waarde.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | int | De waarde om te converteren. |
|

**Returns:**
java.lang.String - De tekenreeksrepresentatie van de `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)` waarde.

### parse(String value) {#parse-java.lang.String-}
```
public static final int parse(String value)
```


Parseert een string naar een `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)` enumeratiewaarde.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | java.lang.String | De te parseren string. |
|

**Returns:**
int - De `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)` enumeratiewaarde.

