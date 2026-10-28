---
title: "MarginType"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Specifica come i valori dei margini devono essere interpretati."
type: docs
weight: 14
url: /it/java/com.groupdocs.watermark.watermarks/margintype/
---
**Inheritance:**
java.lang.Object
```
public final class MarginType
```

Specifica come i valori dei margini devono essere interpretati.

## Campi

| Campo | Descrizione |
| --- | --- |
|  | [Absolute](#Absolute) | Valore del margine misurato in unità di contenuto. |
|
|  | [RelativeToParentDimensions](#RelativeToParentDimensions) | Il valore del margine deve essere interpretato come una parte della dimensione appropriata del genitore. |
|
|  | [RelativeToParentMinDimension](#RelativeToParentMinDimension) | Il valore del margine deve essere interpretato come una parte della dimensione minima del genitore. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [toString(int value)](#toString-int-) | Restituisce una rappresentazione stringa del valore `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`. |
|
|  | [parse(String value)](#parse-java.lang.String-) | Analizza una stringa in un valore di enumerazione `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`. |
|
### Absolute {#Absolute}
```
public static final int Absolute
```


Valore del margine misurato in unità di contenuto.


### RelativeToParentDimensions {#RelativeToParentDimensions}
```
public static final int RelativeToParentDimensions
```


Il valore del margine deve essere interpretato come una parte della dimensione appropriata del genitore.


I margini sinistro e destro sono relativi alla larghezza del genitore,
i margini superiore e inferiore sono relativi all'altezza del genitore.
Se questo tipo è scelto, il valore del margine deve essere compreso tra 0.0 e 1.0.


### RelativeToParentMinDimension {#RelativeToParentMinDimension}
```
public static final int RelativeToParentMinDimension
```


Il valore del margine deve essere interpretato come una parte della dimensione minima del genitore.


Se questo tipo è scelto, il valore del margine deve essere compreso tra 0.0 e 1.0.


### toString(int value) {#toString-int-}
```
public static final String toString(int value)
```


Restituisce una rappresentazione stringa del valore `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | int | Il valore da convertire. |
|

**Returns:**
java.lang.String - La rappresentazione stringa del valore `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`.

### parse(String value) {#parse-java.lang.String-}
```
public static final int parse(String value)
```


Analizza una stringa in un valore di enumerazione `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | java.lang.String | La stringa da analizzare. |
|

**Returns:**
int - Il valore di enumerazione `[MarginType](../../com.groupdocs.watermark.watermarks/margintype)`.

