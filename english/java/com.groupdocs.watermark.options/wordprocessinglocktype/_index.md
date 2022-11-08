---
title: WordProcessingLockType
second_title: GroupDocs.Watermark for Java API Reference
description: Specifies watermark lock type in Word document.
type: docs
weight: 68
url: /java/com.groupdocs.watermark.options/wordprocessinglocktype/
---
**Inheritance:**
java.lang.Object
```
public final class WordProcessingLockType
```

Specifies watermark lock type in Word document.
## Fields

| Field | Description |
| --- | --- |
| [AllowOnlyRevisions](#AllowOnlyRevisions) | User can only add revision marks to the document. |
| [AllowOnlyComments](#AllowOnlyComments) | User can only modify comments in the document. |
| [AllowOnlyFormFields](#AllowOnlyFormFields) | User can only enter data in the form fields in the document. |
| [ReadOnly](#ReadOnly) | The entire document is read-only. |
| [ReadOnlyWithEditableContent](#ReadOnlyWithEditableContent) | The document is read-only, but all the content except of the watermark is marked as editable. |
| [NoLock](#NoLock) | Disable any lock on watermark and document. |
### AllowOnlyRevisions {#AllowOnlyRevisions}
```
public static final int AllowOnlyRevisions
```


User can only add revision marks to the document.

### AllowOnlyComments {#AllowOnlyComments}
```
public static final int AllowOnlyComments
```


User can only modify comments in the document.

### AllowOnlyFormFields {#AllowOnlyFormFields}
```
public static final int AllowOnlyFormFields
```


User can only enter data in the form fields in the document.

--------------------

The document is splitted into one-page sections and locked section with watermark is added between each two adjacent content sections.

### ReadOnly {#ReadOnly}
```
public static final int ReadOnly
```


The entire document is read-only.

### ReadOnlyWithEditableContent {#ReadOnlyWithEditableContent}
```
public static final int ReadOnlyWithEditableContent
```


The document is read-only, but all the content except of the watermark is marked as editable.

### NoLock {#NoLock}
```
public static final int NoLock
```


Disable any lock on watermark and document.

