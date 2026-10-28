---
title: "SizingType"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Specifica come deve essere calcolata la dimensione della filigrana."
type: docs
weight: 16
url: /it/java/com.groupdocs.watermark.watermarks/sizingtype/
---
**Inheritance:**
java.lang.Object
```
public final class SizingType
```

Specifica come deve essere calcolata la dimensione della filigrana.

## Campi

| Campo | Descrizione |
| --- | --- |
|  | [Auto](#Auto) | Il watermark dovrebbe essere dimensionato automaticamente in base al suo contenuto. |
|
|  | [Absolute](#Absolute) | Il watermark dovrebbe essere dimensionato a una larghezza esatta `[Watermark.getWidth()](../../com.groupdocs.watermark/watermark#getWidth--)` |
e `[Watermark.getHeight()](../../com.groupdocs.watermark/watermark#getHeight--)`.
|
|  | [ScaleToParentDimensions](#ScaleToParentDimensions) | Il watermark dovrebbe essere scalato rispetto alle dimensioni del genitore usando |
specificato `[Watermark.getScaleFactor()](../../com.groupdocs.watermark/watermark#getScaleFactor--)`.
|
|  | [ScaleToParentArea](#ScaleToParentArea) | Il watermark dovrebbe essere scalato rispetto all'area del genitore usando il `[Watermark.getScaleFactor()](../../com.groupdocs.watermark/watermark#getScaleFactor--)` specificato. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [toString(int value)](#toString-int-) | Restituisce una rappresentazione stringa del valore `[SizingType](../../com.groupdocs.watermark.watermarks/sizingtype)`. |
|
|  | [parse(String value)](#parse-java.lang.String-) | Analizza una stringa in un valore di enumerazione `[SizingType](../../com.groupdocs.watermark.watermarks/sizingtype)`. |
|
### Auto {#Auto}
```
public static final int Auto
```


Il watermark dovrebbe essere dimensionato automaticamente in base al suo contenuto.


### Absolute {#Absolute}
```
public static final int Absolute
```


Il watermark dovrebbe essere dimensionato a una larghezza esatta `[Watermark.getWidth()](../../com.groupdocs.watermark/watermark#getWidth--)`
e `[Watermark.getHeight()](../../com.groupdocs.watermark/watermark#getHeight--)`.


### ScaleToParentDimensions {#ScaleToParentDimensions}
```
public static final int ScaleToParentDimensions
```


Il watermark dovrebbe essere scalato rispetto alle dimensioni del genitore usando
specificato `[Watermark.getScaleFactor()](../../com.groupdocs.watermark/watermark#getScaleFactor--)`.


### ScaleToParentArea {#ScaleToParentArea}
```
public static final int ScaleToParentArea
```


Il watermark dovrebbe essere scalato rispetto all'area del genitore usando il `[Watermark.getScaleFactor()](../../com.groupdocs.watermark/watermark#getScaleFactor--)` specificato.


### toString(int value) {#toString-int-}
```
public static final String toString(int value)
```


Restituisce una rappresentazione stringa del valore `[SizingType](../../com.groupdocs.watermark.watermarks/sizingtype)`.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | int | Il valore da convertire. |
|

**Returns:**
java.lang.String - La rappresentazione stringa del valore `[SizingType](../../com.groupdocs.watermark.watermarks/sizingtype)`.

### parse(String value) {#parse-java.lang.String-}
```
public static final int parse(String value)
```


Analizza una stringa in un valore di enumerazione `[SizingType](../../com.groupdocs.watermark.watermarks/sizingtype)`.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | java.lang.String | La stringa da analizzare. |
|

**Returns:**
int - Il valore di enumerazione `[SizingType](../../com.groupdocs.watermark.watermarks/sizingtype)`.

