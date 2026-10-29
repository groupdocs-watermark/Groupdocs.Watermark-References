---
title: "RemoveOnlyListBase"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Tillhandahåller den abstrakta basklassen för en starkt typad endast‑borttagningslista."
type: docs
weight: 17
url: /sv/java/com.groupdocs.watermark.common/removeonlylistbase/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase
```
public abstract class RemoveOnlyListBase<T> extends ReadOnlyListBase<T>
```

Tillhandahåller den abstrakta basklassen för en starkt typad endast‑borttagningslista.


T
: Typen av elementet.

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [isReadOnly()](#isReadOnly--) | Hämtar ett värde som indikerar om samlingen är skrivskyddad. |
|
|  | [clear()](#clear--) | Tar bort alla objekt från samlingen. |
|
|  | [remove(T item)](#remove-T-) | Tar bort den första förekomsten av ett specifikt objekt från samlingen. |
|
|  | [removeAt(int index)](#removeAt-int-) | Tar bort objektet på det angivna indexet. |
|
|  | [removeFromDocument(T item)](#removeFromDocument-T-) | <br /> |

|
### isReadOnly() {#isReadOnly--}
```
public boolean isReadOnly()
```


Hämtar ett värde som indikerar om samlingen är skrivskyddad.


**Returns:**
boolean - Returnerar true om samlingen är skrivskyddad; annars false.

### clear() {#clear--}
```
public final void clear()
```


Tar bort alla objekt från samlingen.


### remove(T item) {#remove-T-}
```
public final boolean remove(T item)
```


Tar bort den första förekomsten av ett specifikt objekt från samlingen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | objekt | T | Objektet som ska tas bort från samlingen. |
|

**Returns:**
boolean - True om  item  togs bort framgångsrikt; annars false.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Tar bort objektet på det angivna indexet.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | index | int | Det nollbaserade indexet för objektet som ska tas bort. |
|

### removeFromDocument(T item) {#removeFromDocument-T-}
```
public void removeFromDocument(T item)
```


<br />



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| objekt | T |  |

