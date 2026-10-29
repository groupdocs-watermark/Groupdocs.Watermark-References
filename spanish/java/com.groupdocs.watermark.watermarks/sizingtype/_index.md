---
title: "SizingType"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Especifica cómo debe calcularse el tamaño de la marca de agua."
type: docs
weight: 16
url: /es/java/com.groupdocs.watermark.watermarks/sizingtype/
---
**Inheritance:**
java.lang.Object
```
public final class SizingType
```

Especifica cómo debe calcularse el tamaño de la marca de agua.

## Campos

| Campo | Descripción |
| --- | --- |
|  | [Auto](#Auto) | La marca de agua debe dimensionarse automáticamente según su contenido. |
|
|  | [Absolute](#Absolute) | La marca de agua debe dimensionarse a un valor exacto `[Watermark.getWidth()](../../com.groupdocs.watermark/watermark#getWidth--)` |
y `[Watermark.getHeight()](../../com.groupdocs.watermark/watermark#getHeight--)`.
|
|  | [ScaleToParentDimensions](#ScaleToParentDimensions) | La marca de agua debe escalarse en relación con las dimensiones del padre usando |
especificado `[Watermark.getScaleFactor()](../../com.groupdocs.watermark/watermark#getScaleFactor--)`.
|
|  | [ScaleToParentArea](#ScaleToParentArea) | La marca de agua debe escalarse en relación con el área del padre usando el `[Watermark.getScaleFactor()](../../com.groupdocs.watermark/watermark#getScaleFactor--)` especificado. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [toString(int value)](#toString-int-) | Devuelve una representación en cadena del valor `[SizingType](../../com.groupdocs.watermark.watermarks/sizingtype)`. |
|
|  | [parse(String value)](#parse-java.lang.String-) | Analiza una cadena a un valor de enumeración `[SizingType](../../com.groupdocs.watermark.watermarks/sizingtype)`. |
|
### Auto {#Auto}
```
public static final int Auto
```


La marca de agua debe dimensionarse automáticamente según su contenido.


### Absolute {#Absolute}
```
public static final int Absolute
```


La marca de agua debe dimensionarse a un valor exacto `[Watermark.getWidth()](../../com.groupdocs.watermark/watermark#getWidth--)`
y `[Watermark.getHeight()](../../com.groupdocs.watermark/watermark#getHeight--)`.


### ScaleToParentDimensions {#ScaleToParentDimensions}
```
public static final int ScaleToParentDimensions
```


La marca de agua debe escalarse en relación con las dimensiones del padre usando
especificado `[Watermark.getScaleFactor()](../../com.groupdocs.watermark/watermark#getScaleFactor--)`.


### ScaleToParentArea {#ScaleToParentArea}
```
public static final int ScaleToParentArea
```


La marca de agua debe escalarse en relación con el área del padre usando el `[Watermark.getScaleFactor()](../../com.groupdocs.watermark/watermark#getScaleFactor--)` especificado.


### toString(int value) {#toString-int-}
```
public static final String toString(int value)
```


Devuelve una representación en cadena del valor `[SizingType](../../com.groupdocs.watermark.watermarks/sizingtype)`.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | int | El valor a convertir. |
|

**Returns:**
java.lang.String - La representación en cadena del valor `[SizingType](../../com.groupdocs.watermark.watermarks/sizingtype)`.

### parse(String value) {#parse-java.lang.String-}
```
public static final int parse(String value)
```


Analiza una cadena a un valor de enumeración `[SizingType](../../com.groupdocs.watermark.watermarks/sizingtype)`.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | java.lang.String | La cadena a analizar. |
|

**Returns:**
int - El valor de enumeración `[SizingType](../../com.groupdocs.watermark.watermarks/sizingtype)`.

