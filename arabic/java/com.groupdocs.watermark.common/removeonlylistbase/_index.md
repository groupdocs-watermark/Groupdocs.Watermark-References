---
title: "RemoveOnlyListBase"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يوفر الفئة الأساسية المجردة لقائمة للإزالة فقط ذات نوعية قوية."
type: docs
weight: 17
url: /ar/java/com.groupdocs.watermark.common/removeonlylistbase/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase
```
public abstract class RemoveOnlyListBase<T> extends ReadOnlyListBase<T>
```

يوفر الفئة الأساسية المجردة لقائمة للإزالة فقط ذات نوعية قوية.


T
: نوع العنصر.

## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [isReadOnly()](#isReadOnly--) | يحصل على قيمة تشير إلى ما إذا كانت المجموعة للقراءة فقط. |
|
|  | [clear()](#clear--) | يزيل جميع العناصر من المجموعة. |
|
|  | [remove(T item)](#remove-T-) | يزيل الظهور الأول لكائن محدد من المجموعة. |
|
|  | [removeAt(int index)](#removeAt-int-) | يزيل العنصر في الفهرس المحدد. |
|
|  | [removeFromDocument(T item)](#removeFromDocument-T-) | <br /> |

|
### isReadOnly() {#isReadOnly--}
```
public boolean isReadOnly()
```


يحصل على قيمة تشير إلى ما إذا كانت المجموعة للقراءة فقط.


**Returns:**
boolean - إرجاع true إذا كانت المجموعة للقراءة فقط؛ وإلا false.

### clear() {#clear--}
```
public final void clear()
```


يزيل جميع العناصر من المجموعة.


### remove(T item) {#remove-T-}
```
public final boolean remove(T item)
```


يزيل الظهور الأول لكائن محدد من المجموعة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | item | T | العنصر المراد إزالته من المجموعة. |
|

**Returns:**
boolean - True إذا تم إزالة العنصر بنجاح؛ وإلا false.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


يزيل العنصر في الفهرس المحدد.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | index | int | الفهرس الصفري للعنصر المراد إزالته. |
|

### removeFromDocument(T item) {#removeFromDocument-T-}
```
public void removeFromDocument(T item)
```


<br />



**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| item | T |  |

