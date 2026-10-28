---
title: "SpreadsheetAttachment"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Rappresenta un file allegato a un documento Excel."
type: docs
weight: 101
url: /it/java/com.groupdocs.watermark.contents/spreadsheetattachment/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.common.Attachment](../../com.groupdocs.watermark.common/attachment)

**All Implemented Interfaces:**
[com.groupdocs.watermark.search.ITwoDObject](../../com.groupdocs.watermark.search/itwodobject)
```
public class SpreadsheetAttachment extends Attachment implements ITwoDObject
```

Rappresenta un file allegato a un documento Excel.

## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getContent()](#getContent--) | Ottiene il contenuto del file allegato. |
|
|  | [setContent(byte[] value)](#setContent-byte---) | Imposta il contenuto del file allegato. |
|
|  | [getPreviewImageContent()](#getPreviewImageContent--) | Restituisce l'immagine di anteprima del file allegato come array di byte. |
|
|  | [setPreviewImageContent(byte[] value)](#setPreviewImageContent-byte---) | Imposta l'immagine di anteprima del file allegato come array di byte. |
|
|  | [isLink()](#isLink--) | Restituisce un valore che indica se il contenuto contiene solo un collegamento al file. |
|
|  | [getSourceFullName()](#getSourceFullName--) | Restituisce il nome completo del file allegato. |
|
|  | [getAlternativeText()](#getAlternativeText--) | Restituisce il testo descrittivo (alternativo) associato al file allegato. |
|
|  | [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Imposta il testo descrittivo (alternativo) associato al file allegato. |
|
|  | [getAsposeOleObject()](#getAsposeOleObject--) | <br /> |

|
|  | [getX()](#getX--) | Restituisce lo spostamento orizzontale del riquadro dell'allegato dal bordo sinistro del foglio di lavoro in punti. |
|
|  | [setX(double value)](#setX-double-) | Imposta lo spostamento orizzontale del riquadro dell'allegato dal bordo sinistro del foglio di lavoro in punti. |
|
|  | [getY()](#getY--) | Restituisce lo spostamento verticale del riquadro dell'allegato dal bordo superiore del foglio di lavoro in punti. |
|
|  | [setY(double value)](#setY-double-) | Imposta lo spostamento verticale del riquadro dell'allegato dal bordo superiore del foglio di lavoro in punti. |
|
|  | [getWidth()](#getWidth--) | Restituisce la larghezza del riquadro dell'allegato in punti. |
|
|  | [setWidth(double value)](#setWidth-double-) | Imposta la larghezza del riquadro dell'allegato in punti. |
|
|  | [getHeight()](#getHeight--) | Restituisce l'altezza del riquadro dell'allegato in punti. |
|
|  | [setHeight(double value)](#setHeight-double-) | Imposta l'altezza del riquadro dell'allegato in punti. |
|
|  | [checkImageType()](#checkImageType--) | <br /> |

|
### getContent() {#getContent--}
```
public byte[] getContent()
```


Ottiene il contenuto del file allegato.


**Returns:**
byte[] - Il contenuto del file allegato.

### setContent(byte[] value) {#setContent-byte---}
```
public void setContent(byte[] value)
```


Imposta il contenuto del file allegato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | byte[] | Il contenuto del file allegato. |
|

### getPreviewImageContent() {#getPreviewImageContent--}
```
public final byte[] getPreviewImageContent()
```


Restituisce l'immagine di anteprima del file allegato come array di byte.


**Returns:**
byte[] - L'immagine di anteprima del file allegato come array di byte.

### setPreviewImageContent(byte[] value) {#setPreviewImageContent-byte---}
```
public final void setPreviewImageContent(byte[] value)
```


Imposta l'immagine di anteprima del file allegato come array di byte.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | byte[] | L'immagine di anteprima del file allegato come array di byte. |
|

### isLink() {#isLink--}
```
public final boolean isLink()
```


Restituisce un valore che indica se il contenuto contiene solo un collegamento al file.


**Returns:**
boolean - Vero se il file allegato è referenziato da un collegamento (il contenuto non contiene il contenuto del file allegato); altrimenti, falso.

### getSourceFullName() {#getSourceFullName--}
```
public final String getSourceFullName()
```


Restituisce il nome completo del file allegato.


**Returns:**
java.lang.String - Il nome completo del file allegato.

<br />

*** ** * ** ***

L'estensione è usata per determinare l'applicazione appropriata per aprire il file.

<br />


### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


Restituisce il testo descrittivo (alternativo) associato al file allegato.


**Returns:**
java.lang.String - Il testo descrittivo (alternativo) associato al file allegato.

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


Imposta il testo descrittivo (alternativo) associato al file allegato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | java.lang.String | Il testo descrittivo (alternativo) associato al file allegato. |
|

### getAsposeOleObject() {#getAsposeOleObject--}
```
public final OleObject getAsposeOleObject()
```


<br />



**Returns:**
com.aspose.cells.OleObject
### getX() {#getX--}
```
public final double getX()
```


Restituisce lo spostamento orizzontale del riquadro dell'allegato dal bordo sinistro del foglio di lavoro in punti.


**Returns:**
double - La coordinata x del riquadro dell'allegato.

### setX(double value) {#setX-double-}
```
public final void setX(double value)
```


Imposta lo spostamento orizzontale del riquadro dell'allegato dal bordo sinistro del foglio di lavoro in punti.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | double | La coordinata x del riquadro dell'allegato. |
|

### getY() {#getY--}
```
public final double getY()
```


Restituisce lo spostamento verticale del riquadro dell'allegato dal bordo superiore del foglio di lavoro in punti.


**Returns:**
double - La coordinata y del riquadro dell'allegato.

### setY(double value) {#setY-double-}
```
public final void setY(double value)
```


Imposta lo spostamento verticale del riquadro dell'allegato dal bordo superiore del foglio di lavoro in punti.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | double | La coordinata y del frame di allegato. |
|

### getWidth() {#getWidth--}
```
public final double getWidth()
```


Restituisce la larghezza del riquadro dell'allegato in punti.


**Returns:**
double - La larghezza del frame di allegato in punti.

### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


Imposta la larghezza del riquadro dell'allegato in punti.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | double | La larghezza del frame di allegato in punti. |
|

### getHeight() {#getHeight--}
```
public final double getHeight()
```


Restituisce l'altezza del riquadro dell'allegato in punti.


**Returns:**
double - L'altezza del frame di allegato in punti.

### setHeight(double value) {#setHeight-double-}
```
public final void setHeight(double value)
```


Imposta l'altezza del riquadro dell'allegato in punti.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | double | L'altezza del frame di allegato in punti. |
|

### checkImageType() {#checkImageType--}
```
public final void checkImageType()
```


<br />



