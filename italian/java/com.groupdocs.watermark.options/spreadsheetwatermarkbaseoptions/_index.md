---
title: "SpreadsheetWatermarkBaseOptions"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Classe base per le opzioni di aggiunta della filigrana a un documento Spreadsheet."
type: docs
weight: 56
url: /it/java/com.groupdocs.watermark.options/spreadsheetwatermarkbaseoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.SpreadsheetWatermarkOptions](../../com.groupdocs.watermark.options/spreadsheetwatermarkoptions)
```
public abstract class SpreadsheetWatermarkBaseOptions extends SpreadsheetWatermarkOptions
```

Classe base per le opzioni di aggiunta della filigrana a un documento Spreadsheet.

## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [isLocked()](#isLocked--) | Ottiene un valore che indica se la modifica della forma in Excel è vietata. |
|
|  | [setLocked(boolean value)](#setLocked-boolean-) | Imposta un valore che indica se la modifica della forma in Excel è vietata. |
|
|  | [getName()](#getName--) | Ottiene il nome di una forma. |
|
|  | [setName(String value)](#setName-java.lang.String-) | Imposta il nome di una forma. |
|
|  | [getAlternativeText()](#getAlternativeText--) | Ottiene il testo descrittivo (alternativo) che sarà associato a una forma. |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Imposta il testo descrittivo (alternativo) che sarà associato a una forma. |
|
### isLocked() {#isLocked--}
```
public final boolean isLocked()
```


Ottiene un valore che indica se la modifica della forma in Excel è vietata.


**Returns:**
boolean - Se il valore è true, la modifica della forma sarà vietata. Per impostazione predefinita, il valore è false, la forma può essere modificata in Excel.

### setLocked(boolean value) {#setLocked-boolean-}
```
public final void setLocked(boolean value)
```


Imposta un valore che indica se la modifica della forma in Excel è vietata.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | boolean | Se il valore è true, la modifica della forma sarà vietata. Per impostazione predefinita, il valore è false, la forma può essere modificata in Excel. |
|

### getName() {#getName--}
```
public final String getName()
```


Ottiene il nome di una forma.


**Returns:**
java.lang.String - Il nome della forma.

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Imposta il nome di una forma.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | java.lang.String | Il nome della forma. |
|

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


Ottiene il testo descrittivo (alternativo) che sarà associato a una forma.


**Returns:**
java.lang.String - Il testo descrittivo (alternativo) che verrà associato a una forma.

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


Imposta il testo descrittivo (alternativo) che sarà associato a una forma.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | java.lang.String | Il testo descrittivo (alternativo) che verrà associato a una forma. |
|

