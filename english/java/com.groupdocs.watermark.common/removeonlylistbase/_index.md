---
title: RemoveOnlyListBase
second_title: GroupDocs.Watermark for Java API Reference
description: Provides the abstract base class for a strongly typed remove-only list.
type: docs
weight: 17
url: /java/com.groupdocs.watermark.common/removeonlylistbase/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase
```
public abstract class RemoveOnlyListBase<T> extends ReadOnlyListBase<T>
```

Provides the abstract base class for a strongly typed remove-only list.

 T : The type of the element.
## Methods

| Method | Description |
| --- | --- |
| [isReadOnly()](#isReadOnly--) | Gets a value indicating whether the collection is read-only. |
| [clear()](#clear--) | Removes all items from the collection. |
| [remove(T item)](#remove-T-) | Removes the first occurrence of a specific object from the collection. |
| [removeAt(int index)](#removeAt-int-) | Removes the item at the specified index. |
| [removeFromDocument(T item)](#removeFromDocument-T-) |  |
### isReadOnly() {#isReadOnly--}
```
public boolean isReadOnly()
```


Gets a value indicating whether the collection is read-only.

**Returns:**
boolean - Returns true if the collection is read-only; otherwise, false.
### clear() {#clear--}
```
public final void clear()
```


Removes all items from the collection.

### remove(T item) {#remove-T-}
```
public final boolean remove(T item)
```


Removes the first occurrence of a specific object from the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | T | The item to remove from the collection. |

**Returns:**
boolean - True if  item  was successfully removed; otherwise false.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Removes the item at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index of the item to remove. |

### removeFromDocument(T item) {#removeFromDocument-T-}
```
public void removeFromDocument(T item)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | T |  |

