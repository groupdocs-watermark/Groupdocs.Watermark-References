---
title: "WordProcessingLockType"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: "Specificeert het type vergrendeling van watermerk in een Word-document."
type: docs
weight: 68
url: /nl/java/com.groupdocs.watermark.options/wordprocessinglocktype/
---
**Inheritance:**
java.lang.Object
```
public final class WordProcessingLockType
```

Specificeert het type vergrendeling van watermerk in een Word-document.

## Velden

| Veld | Beschrijving |
| --- | --- |
|  | [AllowOnlyRevisions](#AllowOnlyRevisions) | Gebruiker kan alleen revisiemarkeringen aan het document toevoegen. |
|
|  | [AllowOnlyComments](#AllowOnlyComments) | Gebruiker kan alleen opmerkingen in het document wijzigen. |
|
|  | [AllowOnlyFormFields](#AllowOnlyFormFields) | Gebruiker kan alleen gegevens invoeren in de formuliervelden in het document. |
|
|  | [ReadOnly](#ReadOnly) | Het volledige document is alleen-lezen. |
|
|  | [ReadOnlyWithEditableContent](#ReadOnlyWithEditableContent) | Het document is alleen-lezen, maar alle inhoud behalve de watermerk is gemarkeerd als bewerkbaar. |
|
|  | [NoLock](#NoLock) | Schakel elke vergrendeling van watermerk en document uit. |
|
### AllowOnlyRevisions {#AllowOnlyRevisions}
```
public static final int AllowOnlyRevisions
```


Gebruiker kan alleen revisiemarkeringen aan het document toevoegen.


### AllowOnlyComments {#AllowOnlyComments}
```
public static final int AllowOnlyComments
```


Gebruiker kan alleen opmerkingen in het document wijzigen.


### AllowOnlyFormFields {#AllowOnlyFormFields}
```
public static final int AllowOnlyFormFields
```


Gebruiker kan alleen gegevens invoeren in de formuliervelden in het document.

<br />

*** ** * ** ***

Het document wordt opgesplitst in één-pagina secties en een vergrendelde sectie met watermerk wordt toegevoegd tussen elke twee aangrenzende inhoudssecties.

<br />



### ReadOnly {#ReadOnly}
```
public static final int ReadOnly
```


Het volledige document is alleen-lezen.


### ReadOnlyWithEditableContent {#ReadOnlyWithEditableContent}
```
public static final int ReadOnlyWithEditableContent
```


Het document is alleen-lezen, maar alle inhoud behalve de watermerk is gemarkeerd als bewerkbaar.


### NoLock {#NoLock}
```
public static final int NoLock
```


Schakel elke vergrendeling van watermerk en document uit.


