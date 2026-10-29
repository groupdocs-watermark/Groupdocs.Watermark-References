---
title: "WordProcessingLockType"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Anger låstyp för vattenstämpel i ett Word-dokument."
type: docs
weight: 68
url: /sv/java/com.groupdocs.watermark.options/wordprocessinglocktype/
---
**Inheritance:**
java.lang.Object
```
public final class WordProcessingLockType
```

Anger låstyp för vattenstämpel i ett Word-dokument.

## Fält

| Fält | Beskrivning |
| --- | --- |
|  | [AllowOnlyRevisions](#AllowOnlyRevisions) | Användaren kan endast lägga till revisionsmarkeringar i dokumentet. |
|
|  | [AllowOnlyComments](#AllowOnlyComments) | Användaren kan endast ändra kommentarer i dokumentet. |
|
|  | [AllowOnlyFormFields](#AllowOnlyFormFields) | Användaren kan endast ange data i formulärfälten i dokumentet. |
|
|  | [ReadOnly](#ReadOnly) | Hela dokumentet är skrivskyddat. |
|
|  | [ReadOnlyWithEditableContent](#ReadOnlyWithEditableContent) | Dokumentet är skrivskyddat, men allt innehåll förutom vattenstämpeln är markerat som redigerbart. |
|
|  | [NoLock](#NoLock) | Inaktivera alla lås på vattenstämpeln och dokumentet. |
|
### AllowOnlyRevisions {#AllowOnlyRevisions}
```
public static final int AllowOnlyRevisions
```


Användaren kan endast lägga till revisionsmarkeringar i dokumentet.


### AllowOnlyComments {#AllowOnlyComments}
```
public static final int AllowOnlyComments
```


Användaren kan endast ändra kommentarer i dokumentet.


### AllowOnlyFormFields {#AllowOnlyFormFields}
```
public static final int AllowOnlyFormFields
```


Användaren kan endast ange data i formulärfälten i dokumentet.

<br />

*** ** * ** ***

Dokumentet delas upp i en-sidiga sektioner och en låst sektion med vattenstämpel läggs till mellan varje två intilliggande innehållssektioner.

<br />



### ReadOnly {#ReadOnly}
```
public static final int ReadOnly
```


Hela dokumentet är skrivskyddat.


### ReadOnlyWithEditableContent {#ReadOnlyWithEditableContent}
```
public static final int ReadOnlyWithEditableContent
```


Dokumentet är skrivskyddat, men allt innehåll förutom vattenstämpeln är markerat som redigerbart.


### NoLock {#NoLock}
```
public static final int NoLock
```


Inaktivera alla lås på vattenstämpeln och dokumentet.


