---
title: "SizingType"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: "Specificeert hoe de grootte van het watermerk moet worden berekend."
type: docs
weight: 16
url: /nl/java/com.groupdocs.watermark.watermarks/sizingtype/
---
**Inheritance:**
java.lang.Object
```
public final class SizingType
```

Specificeert hoe de grootte van het watermerk moet worden berekend.

## Velden

| Veld | Beschrijving |
| --- | --- |
|  | [Auto](#Auto) | Watermerk moet automatisch worden aangepast aan de inhoud. |
|
|  | [Absolute](#Absolute) | Watermerk moet worden ingesteld op een exacte `[Watermark.getWidth()](../../com.groupdocs.watermark/watermark#getWidth--)` |
en `[Watermark.getHeight()](../../com.groupdocs.watermark/watermark#getHeight--)`.
|
|  | [ScaleToParentDimensions](#ScaleToParentDimensions) | Watermerk moet worden geschaald ten opzichte van de afmetingen van de bovenliggende container met behulp van |
gespecificeerde `[Watermark.getScaleFactor()](../../com.groupdocs.watermark/watermark#getScaleFactor--)`.
|
|  | [ScaleToParentArea](#ScaleToParentArea) | Watermerk moet worden geschaald ten opzichte van het gebied van de bovenliggende container met behulp van de gespecificeerde `[Watermark.getScaleFactor()](../../com.groupdocs.watermark/watermark#getScaleFactor--)`. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [toString(int value)](#toString-int-) | Retourneert een tekenreeksrepresentatie van de `[SizingType](../../com.groupdocs.watermark.watermarks/sizingtype)`-waarde. |
|
|  | [parse(String value)](#parse-java.lang.String-) | Parseert een tekenreeks naar een `[SizingType](../../com.groupdocs.watermark.watermarks/sizingtype)`-enumeratiewaarde. |
|
### Auto {#Auto}
```
public static final int Auto
```


Watermerk moet automatisch worden aangepast aan de inhoud.


### Absolute {#Absolute}
```
public static final int Absolute
```


Watermerk moet worden ingesteld op een exacte `[Watermark.getWidth()](../../com.groupdocs.watermark/watermark#getWidth--)`
en `[Watermark.getHeight()](../../com.groupdocs.watermark/watermark#getHeight--)`.


### ScaleToParentDimensions {#ScaleToParentDimensions}
```
public static final int ScaleToParentDimensions
```


Watermerk moet worden geschaald ten opzichte van de afmetingen van de bovenliggende container met behulp van
gespecificeerde `[Watermark.getScaleFactor()](../../com.groupdocs.watermark/watermark#getScaleFactor--)`.


### ScaleToParentArea {#ScaleToParentArea}
```
public static final int ScaleToParentArea
```


Watermerk moet worden geschaald ten opzichte van het gebied van de bovenliggende container met behulp van de gespecificeerde `[Watermark.getScaleFactor()](../../com.groupdocs.watermark/watermark#getScaleFactor--)`.


### toString(int value) {#toString-int-}
```
public static final String toString(int value)
```


Retourneert een tekenreeksrepresentatie van de `[SizingType](../../com.groupdocs.watermark.watermarks/sizingtype)`-waarde.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | int | De waarde om te converteren. |
|

**Returns:**
java.lang.String - De tekenreeksrepresentatie van de `[SizingType](../../com.groupdocs.watermark.watermarks/sizingtype)`-waarde.

### parse(String value) {#parse-java.lang.String-}
```
public static final int parse(String value)
```


Parseert een tekenreeks naar een `[SizingType](../../com.groupdocs.watermark.watermarks/sizingtype)`-enumeratiewaarde.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | java.lang.String | De te parseren string. |
|

**Returns:**
int - De `[SizingType](../../com.groupdocs.watermark.watermarks/sizingtype)`-enumeratiewaarde.

