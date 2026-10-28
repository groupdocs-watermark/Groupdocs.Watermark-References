---
title: "WordProcessingLockType"
second_title: "GroupDocs.Watermark pour Java Référence API"
description: "Spécifie le type de verrouillage du filigrane dans un document Word."
type: docs
weight: 68
url: /fr/java/com.groupdocs.watermark.options/wordprocessinglocktype/
---
**Inheritance:**
java.lang.Object
```
public final class WordProcessingLockType
```

Spécifie le type de verrouillage du filigrane dans un document Word.

## Champs

| Champ | Description |
| --- | --- |
|  | [AllowOnlyRevisions](#AllowOnlyRevisions) | L'utilisateur ne peut ajouter que des marques de révision au document. |
|
|  | [AllowOnlyComments](#AllowOnlyComments) | L'utilisateur ne peut modifier que les commentaires dans le document. |
|
|  | [AllowOnlyFormFields](#AllowOnlyFormFields) | L'utilisateur ne peut saisir que des données dans les champs de formulaire du document. |
|
|  | [ReadOnly](#ReadOnly) | L'ensemble du document est en lecture seule. |
|
|  | [ReadOnlyWithEditableContent](#ReadOnlyWithEditableContent) | Le document est en lecture seule, mais tout le contenu sauf le filigrane est marqué comme modifiable. |
|
|  | [NoLock](#NoLock) | Désactiver tout verrouillage sur le filigrane et le document. |
|
### AllowOnlyRevisions {#AllowOnlyRevisions}
```
public static final int AllowOnlyRevisions
```


L'utilisateur ne peut ajouter que des marques de révision au document.


### AllowOnlyComments {#AllowOnlyComments}
```
public static final int AllowOnlyComments
```


L'utilisateur ne peut modifier que les commentaires dans le document.


### AllowOnlyFormFields {#AllowOnlyFormFields}
```
public static final int AllowOnlyFormFields
```


L'utilisateur ne peut saisir que des données dans les champs de formulaire du document.

<br />

*** ** * ** ***

Le document est divisé en sections d'une page et une section verrouillée avec filigrane est ajoutée entre chaque paire de sections de contenu adjacentes.

<br />



### ReadOnly {#ReadOnly}
```
public static final int ReadOnly
```


L'ensemble du document est en lecture seule.


### ReadOnlyWithEditableContent {#ReadOnlyWithEditableContent}
```
public static final int ReadOnlyWithEditableContent
```


Le document est en lecture seule, mais tout le contenu sauf le filigrane est marqué comme modifiable.


### NoLock {#NoLock}
```
public static final int NoLock
```


Désactiver tout verrouillage sur le filigrane et le document.


