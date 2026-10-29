---
title: "WordProcessingLockType"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Especifica el tipo de bloqueo de marca de agua en un documento de Word."
type: docs
weight: 68
url: /es/java/com.groupdocs.watermark.options/wordprocessinglocktype/
---
**Inheritance:**
java.lang.Object
```
public final class WordProcessingLockType
```

Especifica el tipo de bloqueo de marca de agua en un documento de Word.

## Campos

| Campo | Descripción |
| --- | --- |
|  | [AllowOnlyRevisions](#AllowOnlyRevisions) | El usuario solo puede agregar marcas de revisión al documento. |
|
|  | [AllowOnlyComments](#AllowOnlyComments) | El usuario solo puede modificar los comentarios en el documento. |
|
|  | [AllowOnlyFormFields](#AllowOnlyFormFields) | El usuario solo puede ingresar datos en los campos de formulario del documento. |
|
|  | [ReadOnly](#ReadOnly) | Todo el documento es de solo lectura. |
|
|  | [ReadOnlyWithEditableContent](#ReadOnlyWithEditableContent) | El documento es de solo lectura, pero todo el contenido, excepto la marca de agua, está marcado como editable. |
|
|  | [NoLock](#NoLock) | Deshabilitar cualquier bloqueo en la marca de agua y el documento. |
|
### AllowOnlyRevisions {#AllowOnlyRevisions}
```
public static final int AllowOnlyRevisions
```


El usuario solo puede agregar marcas de revisión al documento.


### AllowOnlyComments {#AllowOnlyComments}
```
public static final int AllowOnlyComments
```


El usuario solo puede modificar los comentarios en el documento.


### AllowOnlyFormFields {#AllowOnlyFormFields}
```
public static final int AllowOnlyFormFields
```


El usuario solo puede ingresar datos en los campos de formulario del documento.

<br />

*** ** * ** ***

El documento se divide en secciones de una página y se agrega una sección bloqueada con marca de agua entre cada dos secciones de contenido adyacentes.

<br />



### ReadOnly {#ReadOnly}
```
public static final int ReadOnly
```


Todo el documento es de solo lectura.


### ReadOnlyWithEditableContent {#ReadOnlyWithEditableContent}
```
public static final int ReadOnlyWithEditableContent
```


El documento es de solo lectura, pero todo el contenido, excepto la marca de agua, está marcado como editable.


### NoLock {#NoLock}
```
public static final int NoLock
```


Deshabilitar cualquier bloqueo en la marca de agua y el documento.


