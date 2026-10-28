---
title: "WordProcessingLockType"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Specifica il tipo di blocco della filigrana in un documento Word."
type: docs
weight: 68
url: /it/java/com.groupdocs.watermark.options/wordprocessinglocktype/
---
**Inheritance:**
java.lang.Object
```
public final class WordProcessingLockType
```

Specifica il tipo di blocco della filigrana in un documento Word.

## Campi

| Campo | Descrizione |
| --- | --- |
|  | [AllowOnlyRevisions](#AllowOnlyRevisions) | L'utente può aggiungere solo segni di revisione al documento. |
|
|  | [AllowOnlyComments](#AllowOnlyComments) | L'utente può modificare solo i commenti nel documento. |
|
|  | [AllowOnlyFormFields](#AllowOnlyFormFields) | L'utente può inserire dati solo nei campi modulo del documento. |
|
|  | [ReadOnly](#ReadOnly) | L'intero documento è di sola lettura. |
|
|  | [ReadOnlyWithEditableContent](#ReadOnlyWithEditableContent) | Il documento è di sola lettura, ma tutto il contenuto, eccetto la filigrana, è contrassegnato come modificabile. |
|
|  | [NoLock](#NoLock) | Disabilita qualsiasi blocco sulla filigrana e sul documento. |
|
### AllowOnlyRevisions {#AllowOnlyRevisions}
```
public static final int AllowOnlyRevisions
```


L'utente può aggiungere solo segni di revisione al documento.


### AllowOnlyComments {#AllowOnlyComments}
```
public static final int AllowOnlyComments
```


L'utente può modificare solo i commenti nel documento.


### AllowOnlyFormFields {#AllowOnlyFormFields}
```
public static final int AllowOnlyFormFields
```


L'utente può inserire dati solo nei campi modulo del documento.

<br />

*** ** * ** ***

Il documento è suddiviso in sezioni di una pagina e una sezione bloccata con filigrana è aggiunta tra ogni due sezioni di contenuto adiacenti.

<br />



### ReadOnly {#ReadOnly}
```
public static final int ReadOnly
```


L'intero documento è di sola lettura.


### ReadOnlyWithEditableContent {#ReadOnlyWithEditableContent}
```
public static final int ReadOnlyWithEditableContent
```


Il documento è di sola lettura, ma tutto il contenuto, eccetto la filigrana, è contrassegnato come modificabile.


### NoLock {#NoLock}
```
public static final int NoLock
```


Disabilita qualsiasi blocco sulla filigrana e sul documento.


