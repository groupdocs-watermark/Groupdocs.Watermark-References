---
title: "MarginType"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Especifica cómo deben interpretarse los valores de margen."
type: docs
weight: 14
url: /es/java/com.groupdocs.watermark.watermarks/margintype/
---
**Inheritance:**
java.lang.Object
```
public final class MarginType
```

Especifica cómo deben interpretarse los valores de margen.

## Campos

| Campo | Descripción |
| --- | --- |
|  | [Absolute](#Absolute) | Valor del margen medido en unidades de contenido. |
|
|  | [RelativeToParentDimensions](#RelativeToParentDimensions) | El valor del margen debe interpretarse como una parte de la dimensión del padre correspondiente. |
|
|  | [RelativeToParentMinDimension](#RelativeToParentMinDimension) | El valor del margen debe interpretarse como una parte de la dimensión mínima del padre. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [toString(int value)](#toString-int-) | Devuelve una representación en cadena del valor `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`. |
|
|  | [parse(String value)](#parse-java.lang.String-) | Analiza una cadena a un valor de enumeración `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`. |
|
### Absolute {#Absolute}
```
public static final int Absolute
```


Valor del margen medido en unidades de contenido.


### RelativeToParentDimensions {#RelativeToParentDimensions}
```
public static final int RelativeToParentDimensions
```


El valor del margen debe interpretarse como una parte de la dimensión del padre correspondiente.


Los márgenes izquierdo y derecho son relativos al ancho del padre,
los márgenes superior e inferior son relativos a la altura del padre.
Si se elige este tipo, el valor del margen debe estar entre 0.0 y 1.0.


### RelativeToParentMinDimension {#RelativeToParentMinDimension}
```
public static final int RelativeToParentMinDimension
```


El valor del margen debe interpretarse como una parte de la dimensión mínima del padre.


Si se elige este tipo, el valor del margen debe estar entre 0.0 y 1.0.


### toString(int value) {#toString-int-}
```
public static final String toString(int value)
```


Devuelve una representación en cadena del valor `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | int | El valor a convertir. |
|

**Returns:**
java.lang.String - La representación en cadena del valor `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`.

### parse(String value) {#parse-java.lang.String-}
```
public static final int parse(String value)
```


Analiza una cadena a un valor de enumeración `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | java.lang.String | La cadena a analizar. |
|

**Returns:**
int - El valor de enumeración `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`.

