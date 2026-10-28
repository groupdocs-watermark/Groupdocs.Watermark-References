---
title: "EmailSearchableObjects"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Specifica i flag che rappresentano gli oggetti del messaggio email da includere in una ricerca di filigrana."
type: docs
weight: 22
url: /it/java/com.groupdocs.watermark.search/emailsearchableobjects/
---
**Inheritance:**
java.lang.Object
```
public final class EmailSearchableObjects
```

Specifica i flag che rappresentano gli oggetti del messaggio email da includere in una ricerca di filigrana.

## Campi

| Campo | Descrizione |
| --- | --- |
|  | [None](#None) | Specifica nessun oggetto di ricerca. |
|
|  | [Subject](#Subject) | Cerca nell'oggetto del messaggio. |
|
|  | [PlainTextBody](#PlainTextBody) | Cerca nel corpo del messaggio in testo semplice. |
|
|  | [HtmlBody](#HtmlBody) | Cerca nel corpo HTML del messaggio. |
|
|  | [AttachedImages](#AttachedImages) | Cerca nelle immagini allegate. |
|
|  | [EmbeddedImages](#EmbeddedImages) | Cerca nelle immagini incorporate. |
|
|  | [All](#All) | Cerca in tutti gli oggetti email. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getValues()](#getValues--) | Ottiene un array di tutti i valori dell'enumerazione `[EmailSearchableObjects](../../com.groupdocs.watermark.search/emailsearchableobjects)`. |
|
### None {#None}
```
public static final int None
```


Specifica nessun oggetto di ricerca.


### Subject {#Subject}
```
public static final int Subject
```


Cerca nell'oggetto del messaggio.


### PlainTextBody {#PlainTextBody}
```
public static final int PlainTextBody
```


Cerca nel corpo del messaggio in testo semplice.


### HtmlBody {#HtmlBody}
```
public static final int HtmlBody
```


Cerca nel corpo HTML del messaggio.


### AttachedImages {#AttachedImages}
```
public static final int AttachedImages
```


Cerca nelle immagini allegate.


### EmbeddedImages {#EmbeddedImages}
```
public static final int EmbeddedImages
```


Cerca nelle immagini incorporate.


### All {#All}
```
public static final int All
```


Cerca in tutti gli oggetti email.


### getValues() {#getValues--}
```
public static final int[] getValues()
```


Ottiene un array di tutti i valori dell'enumerazione `[EmailSearchableObjects](../../com.groupdocs.watermark.search/emailsearchableobjects)`.


**Returns:**
int[] - L'array di tutti i valori dell'enumerazione `[EmailSearchableObjects](../../com.groupdocs.watermark.search/emailsearchableobjects)`.

