---
title: "WordProcessingWatermarkBaseOptions"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Classe base per le opzioni di aggiunta della filigrana a un documento Word."
type: docs
weight: 73
url: /it/java/com.groupdocs.watermark.options/wordprocessingwatermarkbaseoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.WatermarkOptions](../../com.groupdocs.watermark.options/watermarkoptions), [com.groupdocs.watermark.options.WordProcessingWatermarkOptions](../../com.groupdocs.watermark.options/wordprocessingwatermarkoptions)
```
public abstract class WordProcessingWatermarkBaseOptions extends WordProcessingWatermarkOptions
```

Classe base per le opzioni di aggiunta della filigrana a un documento Word.

## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [isLocked()](#isLocked--) | Ottiene un valore che indica se la modifica della forma in Word è vietata. |
|
|  | [setLocked(boolean value)](#setLocked-boolean-) | Imposta un valore che indica se la modifica della forma in Word è vietata. |
|
|  | [getLockType()](#getLockType--) | Ottiene il tipo di blocco della filigrana. |
|
|  | [setLockType(int value)](#setLockType-int-) | Imposta il tipo di blocco della filigrana. |
|
|  | [getPassword()](#getPassword--) | Ottiene una password utilizzata per bloccare la filigrana. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Imposta una password utilizzata per bloccare la filigrana. |
|
|  | [getName()](#getName--) | Ottiene il nome di una forma. |
|
|  | [setName(String value)](#setName-java.lang.String-) | Imposta il nome di una forma. |
|
|  | [getAlternativeText()](#getAlternativeText--) | Ottiene il testo descrittivo (alternativo) che sarà associato a una forma. |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Imposta il testo descrittivo (alternativo) che sarà associato a una forma. |
|
| [getEffects()](#getEffects--) |  |
| [setEffects(IWordProcessingWatermarkEffects value)](#setEffects-com.groupdocs.watermark.options.IWordProcessingWatermarkEffects-) |  |
### isLocked() {#isLocked--}
```
public final boolean isLocked()
```


Ottiene un valore che indica se la modifica della forma in Word è vietata.


**Returns:**
boolean - Se il valore è  true , la modifica della forma sarà vietata. Per impostazione predefinita, il valore è  false , la forma può essere modificata in Word.

### setLocked(boolean value) {#setLocked-boolean-}
```
public final void setLocked(boolean value)
```


Imposta un valore che indica se la modifica della forma in Word è vietata.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | boolean | Se il valore è  true , la modifica della forma sarà vietata. Per impostazione predefinita, il valore è  false , la forma può essere modificata in Word. |
|

### getLockType() {#getLockType--}
```
public final int getLockType()
```


Ottiene il tipo di blocco della filigrana.


**Returns:**
int - Il tipo di blocco del watermark `[WordProcessingLockType](../../com.groupdocs.watermark.options/wordprocessinglocktype)`.

### setLockType(int value) {#setLockType-int-}
```
public final void setLockType(int value)
```


Imposta il tipo di blocco della filigrana.

Il valore `[WordProcessingLockType.AllowOnlyFormFields](../../com.groupdocs.watermark.options/wordprocessinglocktype#AllowOnlyFormFields)` non può essere usato con
un oggetto di tipo `[WordProcessingHeaderFooter](../../com.groupdocs.watermark.contents/wordprocessingheaderfooter)`.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | int | Il tipo di blocco del watermark `[WordProcessingLockType](../../com.groupdocs.watermark.options/wordprocessinglocktype)`. |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Ottiene una password utilizzata per bloccare la filigrana.


**Returns:**
java.lang.String - Una password utilizzata per bloccare il watermark.

### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Imposta una password utilizzata per bloccare la filigrana.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | java.lang.String | Una password utilizzata per bloccare il watermark. |
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

### getEffects() {#getEffects--}
```
public final IWordProcessingWatermarkEffects getEffects()
```




**Returns:**
[IWordProcessingWatermarkEffects](../../com.groupdocs.watermark.options/iwordprocessingwatermarkeffects)
### setEffects(IWordProcessingWatermarkEffects value) {#setEffects-com.groupdocs.watermark.options.IWordProcessingWatermarkEffects-}
```
public final void setEffects(IWordProcessingWatermarkEffects value)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IWordProcessingWatermarkEffects](../../com.groupdocs.watermark.options/iwordprocessingwatermarkeffects) |  |

