---
title: "WordProcessingLockType"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Gibt den Sperrtyp für Wasserzeichen in einem Word-Dokument an."
type: docs
weight: 68
url: /de/java/com.groupdocs.watermark.options/wordprocessinglocktype/
---
**Inheritance:**
java.lang.Object
```
public final class WordProcessingLockType
```

Gibt den Sperrtyp für Wasserzeichen in einem Word-Dokument an.

## Felder

| Feld | Beschreibung |
| --- | --- |
|  | [AllowOnlyRevisions](#AllowOnlyRevisions) | Der Benutzer kann dem Dokument nur Revisionsmarken hinzufügen. |
|
|  | [AllowOnlyComments](#AllowOnlyComments) | Der Benutzer kann im Dokument nur Kommentare ändern. |
|
|  | [AllowOnlyFormFields](#AllowOnlyFormFields) | Der Benutzer kann in den Formularfeldern des Dokuments nur Daten eingeben. |
|
|  | [ReadOnly](#ReadOnly) | Das gesamte Dokument ist schreibgeschützt. |
|
|  | [ReadOnlyWithEditableContent](#ReadOnlyWithEditableContent) | Das Dokument ist schreibgeschützt, aber aller Inhalt außer dem Wasserzeichen ist als editierbar markiert. |
|
|  | [NoLock](#NoLock) | Deaktiviert jegliche Sperre für das Wasserzeichen und das Dokument. |
|
### AllowOnlyRevisions {#AllowOnlyRevisions}
```
public static final int AllowOnlyRevisions
```


Der Benutzer kann dem Dokument nur Revisionsmarken hinzufügen.


### AllowOnlyComments {#AllowOnlyComments}
```
public static final int AllowOnlyComments
```


Der Benutzer kann im Dokument nur Kommentare ändern.


### AllowOnlyFormFields {#AllowOnlyFormFields}
```
public static final int AllowOnlyFormFields
```


Der Benutzer kann in den Formularfeldern des Dokuments nur Daten eingeben.

<br />

*** ** * ** ***

Das Dokument wird in einseitige Abschnitte aufgeteilt und ein gesperrter Abschnitt mit Wasserzeichen wird zwischen jeweils zwei benachbarten Inhaltsabschnitten eingefügt.

<br />



### ReadOnly {#ReadOnly}
```
public static final int ReadOnly
```


Das gesamte Dokument ist schreibgeschützt.


### ReadOnlyWithEditableContent {#ReadOnlyWithEditableContent}
```
public static final int ReadOnlyWithEditableContent
```


Das Dokument ist schreibgeschützt, aber aller Inhalt außer dem Wasserzeichen ist als editierbar markiert.


### NoLock {#NoLock}
```
public static final int NoLock
```


Deaktiviert jegliche Sperre für das Wasserzeichen und das Dokument.


