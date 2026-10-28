---
title: "WordProcessingShapeSettings"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Rappresenta le impostazioni che possono essere applicate a una filigrana forma per un documento Word."
type: docs
weight: 71
url: /it/java/com.groupdocs.watermark.options/wordprocessingshapesettings/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.contents.OfficeShapeSettings](../../com.groupdocs.watermark.contents/officeshapesettings)
```
public final class WordProcessingShapeSettings extends OfficeShapeSettings
```

Rappresenta le impostazioni che possono essere applicate a una filigrana forma per un documento Word.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [WordProcessingShapeSettings()](#WordProcessingShapeSettings--) | Inizializza una nuova istanza della classe `[WordProcessingShapeSettings](../../com.groupdocs.watermark.options/wordprocessingshapesettings)`. |
|
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
|  | [getPageNumbers()](#getPageNumbers--) | Ottiene i numeri di pagina a cui aggiungere il watermark. |
|
|  | [setPageNumbers(int[] value)](#setPageNumbers-int---) | Imposta i numeri di pagina a cui aggiungere il watermark. |
|
### WordProcessingShapeSettings() {#WordProcessingShapeSettings--}
```
public WordProcessingShapeSettings()
```


Inizializza una nuova istanza della classe `[WordProcessingShapeSettings](../../com.groupdocs.watermark.options/wordprocessingshapesettings)`.


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
int - Il tipo di blocco del watermark di `[WordProcessingLockType](../../com.groupdocs.watermark.options/wordprocessinglocktype)`.

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
|  | value | int | Il tipo di blocco del watermark di `[WordProcessingLockType](../../com.groupdocs.watermark.options/wordprocessinglocktype)`. |
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

### getPageNumbers() {#getPageNumbers--}
```
public final int[] getPageNumbers()
```


Ottiene i numeri di pagina a cui aggiungere il watermark.


**Returns:**
int[] - I numeri di pagina a cui aggiungere il watermark.

<br />

*** ** * ** ***

Tutti i numeri devono essere maggiori o uguali a 1. Questa proprietà è utilizzata solo quando si aggiunge il watermark a un documento. Se questo valore è  null , il watermark viene aggiunto a tutte le pagine.

<br />


### setPageNumbers(int[] value) {#setPageNumbers-int---}
```
public final void setPageNumbers(int[] value)
```


Imposta i numeri di pagina a cui aggiungere il watermark.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | int[] | I numeri di pagina a cui aggiungere il watermark. |

<br />

*** ** * ** ***

Tutti i numeri devono essere maggiori o uguali a 1. Questa proprietà è utilizzata solo quando si aggiunge il watermark a un documento. Se questo valore è  null , il watermark viene aggiunto a tutte le pagine.

<br />

|

