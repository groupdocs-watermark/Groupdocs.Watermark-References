---
title: ReadOnlyListBase
second_title: GroupDocs.Watermark for Java API Reference
description: Provides the abstract base class for a strongly typed read-only list.
type: docs
weight: 16
url: /java/com.groupdocs.watermark.common/readonlylistbase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.watermark.internal.IReadOnlyList
```
public abstract class ReadOnlyListBase<T> implements IReadOnlyList<T>
```

Provides the abstract base class for a strongly typed read-only list.

 T : The type of the element.
## Methods

| Method | Description |
| --- | --- |
| [getCount()](#getCount--) | Gets the number of elements contained in the collection. |
| [getInnerList()](#getInnerList--) |  |
| [get_Item(int index)](#get-Item-int-) | Gets the element at the specified index in the collection. |
| [contains(T item)](#contains-T-) | Determines whether the collection contains a specific item. |
| [indexOf(T item)](#indexOf-T-) | Determines the index of a specific item in the collection. |
| [iterator()](#iterator--) | Returns an enumerator that iterates through a collection. |
| [addInternally(T item)](#addInternally-T-) |  |
### getCount() {#getCount--}
```
public int getCount()
```


Gets the number of elements contained in the collection.

**Returns:**
int - The number of elements contained in the collection.
### getInnerList() {#getInnerList--}
```
public final System.Collections.Generic.List<T> getInnerList()
```




**Returns:**
com.aspose.ms.System.Collections.Generic.List<T>
### get_Item(int index) {#get-Item-int-}
```
public T get_Item(int index)
```


Gets the element at the specified index in the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index of the element to get. Value: The element at the specified index. |

**Returns:**
T
### contains(T item) {#contains-T-}
```
public boolean contains(T item)
```


Determines whether the collection contains a specific item.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | T | The item to locate in the collection. |

**Returns:**
boolean - True if the item is found in the collection; otherwise, false.
### indexOf(T item) {#indexOf-T-}
```
public int indexOf(T item)
```


Determines the index of a specific item in the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | T | The item to locate in the collection. |

**Returns:**
int - The index of  item  if found in the collection; otherwise, -1.
### iterator() {#iterator--}
```
public Iterator<T> iterator()
```


Returns an enumerator that iterates through a collection.

**Returns:**
java.util.Iterator<T> - An  IEnumerator\{T\}  object that can be used to iterate through the collection.
### addInternally(T item) {#addInternally-T-}
```
public void addInternally(T item)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | T |  |

