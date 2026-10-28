---
title: "ReadOnlyListBase"
second_title: "GroupDocs.Watermark لـ Java مرجع API"
description: "يوفر الفئة الأساسية المجردة لقائمة للقراءة فقط ذات نوعية قوية."
type: docs
weight: 16
url: /ar/java/com.groupdocs.watermark.common/readonlylistbase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.watermark.internal.IReadOnlyList
```
public abstract class ReadOnlyListBase<T> implements IReadOnlyList<T>
```

يوفر الفئة الأساسية المجردة لقائمة للقراءة فقط ذات نوعية قوية.


T
: نوع العنصر.

## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getCount()](#getCount--) | يحصل على عدد العناصر الموجودة في المجموعة. |
|
|  | [getInnerList()](#getInnerList--) | <br /> |

|
|  | [get_Item(int index)](#get-Item-int-) | يحصل على العنصر في الفهرس المحدد داخل المجموعة. |
|
|  | [contains(T item)](#contains-T-) | يحدد ما إذا كانت المجموعة تحتوي على عنصر محدد. |
|
|  | [indexOf(T item)](#indexOf-T-) | يحدد فهرس عنصر محدد في المجموعة. |
|
|  | [iterator()](#iterator--) | يعيد عدادًا يتنقل عبر المجموعة. |
|
|  | [addInternally(T item)](#addInternally-T-) | <br /> |

|
### getCount() {#getCount--}
```
public int getCount()
```


يحصل على عدد العناصر الموجودة في المجموعة.


**Returns:**
int - عدد العناصر الموجودة في المجموعة.

### getInnerList() {#getInnerList--}
```
public final System.Collections.Generic.List<T> getInnerList()
```


<br />



**Returns:**
com.aspose.ms.System.Collections.Generic.List<T>
### get_Item(int index) {#get-Item-int-}
```
public T get_Item(int index)
```


يحصل على العنصر في الفهرس المحدد داخل المجموعة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | index | int | الفهرس الصفري للعنصر المراد الحصول عليه. القيمة: العنصر في الفهرس المحدد. |
|

**Returns:**
T
### contains(T item) {#contains-T-}
```
public boolean contains(T item)
```


يحدد ما إذا كانت المجموعة تحتوي على عنصر محدد.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | item | T | العنصر المراد تحديد موقعه في المجموعة. |
|

**Returns:**
boolean - صحيح إذا تم العثور على العنصر في المجموعة؛ وإلا، خطأ.

### indexOf(T item) {#indexOf-T-}
```
public int indexOf(T item)
```


يحدد فهرس عنصر محدد في المجموعة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | item | T | العنصر المراد تحديد موقعه في المجموعة. |
|

**Returns:**
int - فهرس العنصر إذا تم العثور عليه في المجموعة؛ وإلا، -1.

### iterator() {#iterator--}
```
public Iterator<T> iterator()
```


يعيد عدادًا يتنقل عبر المجموعة.


**Returns:**
java.util.Iterator<T> - كائن IEnumerator{T} يمكن استخدامه للتنقل عبر المجموعة.

### addInternally(T item) {#addInternally-T-}
```
public void addInternally(T item)
```


<br />



**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| item | T |  |

