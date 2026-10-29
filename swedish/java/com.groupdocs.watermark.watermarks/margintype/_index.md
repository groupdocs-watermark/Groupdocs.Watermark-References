---
title: "MarginType"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Anger hur marginalvärden ska tolkas."
type: docs
weight: 14
url: /sv/java/com.groupdocs.watermark.watermarks/margintype/
---
**Inheritance:**
java.lang.Object
```
public final class MarginType
```

Anger hur marginalvärden ska tolkas.

## Fält

| Fält | Beskrivning |
| --- | --- |
|  | [Absolute](#Absolute) | Marginalvärde mätt i innehållsenheter. |
|
|  | [RelativeToParentDimensions](#RelativeToParentDimensions) | Marginalvärdet bör tolkas som en del av lämplig föräldradimension. |
|
|  | [RelativeToParentMinDimension](#RelativeToParentMinDimension) | Marginalvärdet bör tolkas som en del av förälderns minsta dimension. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [toString(int value)](#toString-int-) | Returnerar en strängrepresentation av `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`-värdet. |
|
|  | [parse(String value)](#parse-java.lang.String-) | Analyserar en sträng till ett `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)` enumerationsvärde. |
|
### Absolute {#Absolute}
```
public static final int Absolute
```


Marginalvärde mätt i innehållsenheter.


### RelativeToParentDimensions {#RelativeToParentDimensions}
```
public static final int RelativeToParentDimensions
```


Marginalvärdet bör tolkas som en del av lämplig föräldradimension.


Vänster- och högermarginaler är relativa till förälderns bredd,
övre och nedre marginaler är relativa till förälderns höjd.
Om denna typ väljs måste marginalvärdet ligga mellan 0,0 och 1,0.


### RelativeToParentMinDimension {#RelativeToParentMinDimension}
```
public static final int RelativeToParentMinDimension
```


Marginalvärdet bör tolkas som en del av förälderns minsta dimension.


Om denna typ väljs måste marginalvärdet ligga mellan 0,0 och 1,0.


### toString(int value) {#toString-int-}
```
public static final String toString(int value)
```


Returnerar en strängrepresentation av `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`-värdet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | int | Värdet att konvertera. |
|

**Returns:**
`java.lang.String` - Strängrepresentationen av `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`-värdet.

### parse(String value) {#parse-java.lang.String-}
```
public static final int parse(String value)
```


Analyserar en sträng till ett `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)` enumerationsvärde.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | java.lang.String | Strängen att tolka. |
|

**Returns:**
`int` - `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`-enumerationsvärdet.

