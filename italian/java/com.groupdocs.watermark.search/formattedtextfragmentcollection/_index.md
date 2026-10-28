---
title: "FormattedTextFragmentCollection"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Rappresenta una collezione mutabile di frammenti di testo formattato."
type: docs
weight: 27
url: /it/java/com.groupdocs.watermark.search/formattedtextfragmentcollection/
---
**Inheritance:**
java.lang.Object, com.groupdocs.watermark.common.ReadOnlyListBase, com.groupdocs.watermark.common.RemoveOnlyListBase
```
public class FormattedTextFragmentCollection extends RemoveOnlyListBase<FormattedTextFragment>
```

Rappresenta una collezione mutabile di frammenti di testo formattato.

Questa collezione contiene gli elementi del tipo base `[FormattedTextFragment](../../com.groupdocs.watermark.search/formattedtextfragment)`.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [FormattedTextFragmentCollection(int collectionType)](#FormattedTextFragmentCollection-int-) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getCollectionType()](#getCollectionType--) | Restituisce il tipo di collezione di frammenti formattati. |
|
| [getDefaultFont()](#getDefaultFont--) |  |
| [getDefaultForegroundColor()](#getDefaultForegroundColor--) |  |
| [getDefaultBackgroundColor()](#getDefaultBackgroundColor--) |  |
| [getText()](#getText--) |  |
|  | [add(String text)](#add-java.lang.String-) | Aggiunge un frammento di testo formattato alla collezione. |
|
|  | [add(String text, Font font)](#add-java.lang.String-com.groupdocs.watermark.watermarks.Font-) | Aggiunge un frammento di testo formattato alla collezione. |
|
|  | [add(String text, Font font, Color foregroundColor)](#add-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-) | Aggiunge un frammento di testo formattato alla collezione. |
|
|  | [add(String text, Font font, Color foregroundColor, Color backgroundColor)](#add-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-) | Aggiunge un frammento di testo formattato alla collezione. |
|
|  | [insert(int index, String text)](#insert-int-java.lang.String-) | Inserisce un frammento di testo formattato nella collezione a un indice specificato. |
|
|  | [insert(int index, String text, Font font)](#insert-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-) | Inserisce un frammento di testo formattato nella collezione a un indice specificato. |
|
|  | [insert(int index, String text, Font font, Color foregroundColor)](#insert-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-) | Inserisce un frammento di testo formattato nella collezione a un indice specificato. |
|
|  | [insert(int index, String text, Font font, Color foregroundColor, Color backgroundColor)](#insert-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-) | Inserisce un frammento di testo formattato nella collezione a un indice specificato. |
|
| [createInDocument(int index, String text, Font font, Color foregroundColor, Color backgroundColor)](#createInDocument-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-) |  |
| [setText(String text)](#setText-java.lang.String-) |  |
### FormattedTextFragmentCollection(int collectionType) {#FormattedTextFragmentCollection-int-}
```
public FormattedTextFragmentCollection(int collectionType)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| collectionType | int |  |

### getCollectionType() {#getCollectionType--}
```
public final int getCollectionType()
```


Restituisce il tipo di collezione di frammenti formattati.


**Returns:**
int - Il tipo di collezione di frammenti formattati.

### getDefaultFont() {#getDefaultFont--}
```
public final Font getDefaultFont()
```




**Returns:**
[Font](../../com.groupdocs.watermark.watermarks/font)
### getDefaultForegroundColor() {#getDefaultForegroundColor--}
```
public final Color getDefaultForegroundColor()
```




**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color)
### getDefaultBackgroundColor() {#getDefaultBackgroundColor--}
```
public final Color getDefaultBackgroundColor()
```




**Returns:**
[Color](../../com.groupdocs.watermark.watermarks/color)
### getText() {#getText--}
```
public String getText()
```




**Returns:**
java.lang.String
### add(String text) {#add-java.lang.String-}
```
public final void add(String text)
```


Aggiunge un frammento di testo formattato alla collezione.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | testo | java.lang.String | Il testo del frammento. |
|

### add(String text, Font font) {#add-java.lang.String-com.groupdocs.watermark.watermarks.Font-}
```
public final void add(String text, Font font)
```


Aggiunge un frammento di testo formattato alla collezione.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | testo | java.lang.String | Il testo del frammento. |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | Il carattere del testo. |
|

### add(String text, Font font, Color foregroundColor) {#add-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-}
```
public final void add(String text, Font font, Color foregroundColor)
```


Aggiunge un frammento di testo formattato alla collezione.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | testo | java.lang.String | Il testo del frammento. |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | Il carattere del testo. |
|
|  | foregroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) | Il colore di primo piano del testo. |
|

### add(String text, Font font, Color foregroundColor, Color backgroundColor) {#add-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-}
```
public final void add(String text, Font font, Color foregroundColor, Color backgroundColor)
```


Aggiunge un frammento di testo formattato alla collezione.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | testo | java.lang.String | Il testo del frammento. |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | Il carattere del testo. |
|
|  | foregroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) | Il colore di primo piano del testo. |
|
|  | backgroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) | Il colore di sfondo del testo. |
|

### insert(int index, String text) {#insert-int-java.lang.String-}
```
public final void insert(int index, String text)
```


Inserisce un frammento di testo formattato nella collezione a un indice specificato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | indice | int | L'indice basato su zero al quale il frammento di testo formattato deve essere inserito. |
|
|  | testo | java.lang.String | Il testo del frammento. |
|

### insert(int index, String text, Font font) {#insert-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-}
```
public final void insert(int index, String text, Font font)
```


Inserisce un frammento di testo formattato nella collezione a un indice specificato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | indice | int | L'indice basato su zero al quale il frammento di testo formattato deve essere inserito. |
|
|  | testo | java.lang.String | Il testo del frammento. |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | Il carattere del testo. |
|

### insert(int index, String text, Font font, Color foregroundColor) {#insert-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-}
```
public final void insert(int index, String text, Font font, Color foregroundColor)
```


Inserisce un frammento di testo formattato nella collezione a un indice specificato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | indice | int | L'indice basato su zero al quale il frammento di testo formattato deve essere inserito. |
|
|  | testo | java.lang.String | Il testo del frammento. |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | Il carattere del testo. |
|
|  | foregroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) | Il colore di primo piano del testo. |
|

### insert(int index, String text, Font font, Color foregroundColor, Color backgroundColor) {#insert-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-}
```
public final void insert(int index, String text, Font font, Color foregroundColor, Color backgroundColor)
```


Inserisce un frammento di testo formattato nella collezione a un indice specificato.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | indice | int | L'indice basato su zero al quale il frammento di testo formattato deve essere inserito. |
|
|  | testo | java.lang.String | Il testo del frammento. |
|
|  | font | [Font](../../com.groupdocs.watermark.watermarks/font) | Il carattere del testo. |
|
|  | foregroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) | Il colore di primo piano del testo. |
|
|  | backgroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) | Il colore di sfondo del testo. |
|

### createInDocument(int index, String text, Font font, Color foregroundColor, Color backgroundColor) {#createInDocument-int-java.lang.String-com.groupdocs.watermark.watermarks.Font-com.groupdocs.watermark.watermarks.Color-com.groupdocs.watermark.watermarks.Color-}
```
public FormattedTextFragment createInDocument(int index, String text, Font font, Color foregroundColor, Color backgroundColor)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| indice | int |  |
| testo | java.lang.String |  |
| font | [Font](../../com.groupdocs.watermark.watermarks/font) |  |
| foregroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) |  |
| backgroundColor | [Color](../../com.groupdocs.watermark.watermarks/color) |  |

**Returns:**
[FormattedTextFragment](../../com.groupdocs.watermark.search/formattedtextfragment)
### setText(String text) {#setText-java.lang.String-}
```
public void setText(String text)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| testo | java.lang.String |  |

