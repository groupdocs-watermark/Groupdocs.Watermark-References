---
title: "SizingType"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Anger hur vattenmärkesstorlek ska beräknas."
type: docs
weight: 16
url: /sv/java/com.groupdocs.watermark.watermarks/sizingtype/
---
**Inheritance:**
java.lang.Object
```
public final class SizingType
```

Anger hur vattenmärkesstorlek ska beräknas.

## Fält

| Fält | Beskrivning |
| --- | --- |
|  | [Auto](#Auto) | Vattenstämpeln bör storleksanpassas automatiskt enligt dess innehåll. |
|
|  | [Absolute](#Absolute) | Vattenstämpeln bör storleksanpassas till en exakt `[Watermark.getWidth()](../../com.groupdocs.watermark/watermark#getWidth--)` |
och `[Watermark.getHeight()](../../com.groupdocs.watermark/watermark#getHeight--)`.
|
|  | [ScaleToParentDimensions](#ScaleToParentDimensions) | Vattenstämpeln bör skalas i förhållande till förälderns dimensioner med hjälp av |
angivet `[Watermark.getScaleFactor()](../../com.groupdocs.watermark/watermark#getScaleFactor--)`.
|
|  | [ScaleToParentArea](#ScaleToParentArea) | Vattenstämpeln bör skalas i förhållande till föräldraområdet med angivet `[Watermark.getScaleFactor()](../../com.groupdocs.watermark/watermark#getScaleFactor--)`. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [toString(int value)](#toString-int-) | Returnerar en strängrepresentation av värdet `[SizingType](../../com.groupdocs.watermark.watermarks/sizingtype)`. |
|
|  | [parse(String value)](#parse-java.lang.String-) | Tolkar en sträng till ett `[SizingType](../../com.groupdocs.watermark.watermarks/sizingtype)`‑enumvärde. |
|
### Auto {#Auto}
```
public static final int Auto
```


Vattenstämpeln bör storleksanpassas automatiskt enligt dess innehåll.


### Absolute {#Absolute}
```
public static final int Absolute
```


Vattenstämpeln bör storleksanpassas till en exakt `[Watermark.getWidth()](../../com.groupdocs.watermark/watermark#getWidth--)`
och `[Watermark.getHeight()](../../com.groupdocs.watermark/watermark#getHeight--)`.


### ScaleToParentDimensions {#ScaleToParentDimensions}
```
public static final int ScaleToParentDimensions
```


Vattenstämpeln bör skalas i förhållande till förälderns dimensioner med hjälp av
angivet `[Watermark.getScaleFactor()](../../com.groupdocs.watermark/watermark#getScaleFactor--)`.


### ScaleToParentArea {#ScaleToParentArea}
```
public static final int ScaleToParentArea
```


Vattenstämpeln bör skalas i förhållande till föräldraområdet med angivet `[Watermark.getScaleFactor()](../../com.groupdocs.watermark/watermark#getScaleFactor--)`.


### toString(int value) {#toString-int-}
```
public static final String toString(int value)
```


Returnerar en strängrepresentation av värdet `[SizingType](../../com.groupdocs.watermark.watermarks/sizingtype)`.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | int | Värdet att konvertera. |
|

**Returns:**
java.lang.String - Strängrepresentationen av värdet `[SizingType](../../com.groupdocs.watermark.watermarks/sizingtype)`.

### parse(String value) {#parse-java.lang.String-}
```
public static final int parse(String value)
```


Tolkar en sträng till ett `[SizingType](../../com.groupdocs.watermark.watermarks/sizingtype)`‑enumvärde.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | java.lang.String | Strängen att tolka. |
|

**Returns:**
int - `[SizingType](../../com.groupdocs.watermark.watermarks/sizingtype)`‑enumvärdet.

