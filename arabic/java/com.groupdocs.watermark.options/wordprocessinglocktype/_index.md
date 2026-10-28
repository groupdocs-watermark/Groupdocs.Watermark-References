---
title: "WordProcessingLockType"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يحدد نوع قفل العلامة المائية في مستند Word."
type: docs
weight: 68
url: /ar/java/com.groupdocs.watermark.options/wordprocessinglocktype/
---
**Inheritance:**
java.lang.Object
```
public final class WordProcessingLockType
```

يحدد نوع قفل العلامة المائية في مستند Word.

## الحقول

| حقل | الوصف |
| --- | --- |
|  | [AllowOnlyRevisions](#AllowOnlyRevisions) | يمكن للمستخدم فقط إضافة علامات المراجعة إلى المستند. |
|
|  | [AllowOnlyComments](#AllowOnlyComments) | يمكن للمستخدم فقط تعديل التعليقات في المستند. |
|
|  | [AllowOnlyFormFields](#AllowOnlyFormFields) | يمكن للمستخدم فقط إدخال البيانات في حقول النموذج داخل المستند. |
|
|  | [ReadOnly](#ReadOnly) | المستند بأكمله للقراءة فقط. |
|
|  | [ReadOnlyWithEditableContent](#ReadOnlyWithEditableContent) | المستند للقراءة فقط، لكن جميع المحتويات باستثناء العلامة المائية مُعلمة كقابلة للتحرير. |
|
|  | [NoLock](#NoLock) | تعطيل أي قفل على العلامة المائية والمستند. |
|
### AllowOnlyRevisions {#AllowOnlyRevisions}
```
public static final int AllowOnlyRevisions
```


يمكن للمستخدم فقط إضافة علامات المراجعة إلى المستند.


### AllowOnlyComments {#AllowOnlyComments}
```
public static final int AllowOnlyComments
```


يمكن للمستخدم فقط تعديل التعليقات في المستند.


### AllowOnlyFormFields {#AllowOnlyFormFields}
```
public static final int AllowOnlyFormFields
```


يمكن للمستخدم فقط إدخال البيانات في حقول النموذج داخل المستند.

<br />

*** ** * ** ***

يتم تقسيم المستند إلى أقسام صفحة واحدة وتُضاف قسم مقفل مع علامة مائية بين كل قسمين متجاورين من المحتوى.

<br />



### ReadOnly {#ReadOnly}
```
public static final int ReadOnly
```


المستند بأكمله للقراءة فقط.


### ReadOnlyWithEditableContent {#ReadOnlyWithEditableContent}
```
public static final int ReadOnlyWithEditableContent
```


المستند للقراءة فقط، لكن جميع المحتويات باستثناء العلامة المائية مُعلمة كقابلة للتحرير.


### NoLock {#NoLock}
```
public static final int NoLock
```


تعطيل أي قفل على العلامة المائية والمستند.


