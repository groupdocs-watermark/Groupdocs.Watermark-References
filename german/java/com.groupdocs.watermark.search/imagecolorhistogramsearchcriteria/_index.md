---
title: "ImageColorHistogramSearchCriteria"
second_title: "GroupDocs.Watermark für Java API-Referenz"
description: "Stellt Suchkriterien zum Finden von Bildern in einem Inhalt dar."
type: docs
weight: 30
url: /de/java/com.groupdocs.watermark.search/imagecolorhistogramsearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria), [com.groupdocs.watermark.search.PageSearchCriteria](../../com.groupdocs.watermark.search/pagesearchcriteria), [com.groupdocs.watermark.search.ImageSearchCriteria](../../com.groupdocs.watermark.search/imagesearchcriteria)
```
public class ImageColorHistogramSearchCriteria extends ImageSearchCriteria
```

Stellt Suchkriterien zum Finden von Bildern in einem Inhalt dar.

<br />

*** ** * ** ***

Dieses Suchkriterium verwendet Farbhistogramme von Bildern zur Berechnung der Bildähnlichkeit.

<br />


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [ImageColorHistogramSearchCriteria(String filePath)](#ImageColorHistogramSearchCriteria-java.lang.String-) | Initialisiert eine neue Instanz der `[ImageColorHistogramSearchCriteria](../../com.groupdocs.watermark.search/imagecolorhistogramsearchcriteria)`-Klasse mit einem angegebenen Dateipfad. |
|
|  | [ImageColorHistogramSearchCriteria(InputStream stream)](#ImageColorHistogramSearchCriteria-java.io.InputStream-) | Initialisiert eine neue Instanz der `[ImageColorHistogramSearchCriteria](../../com.groupdocs.watermark.search/imagecolorhistogramsearchcriteria)` Klasse mit einem angegebenen Stream. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getBinsCount()](#getBinsCount--) | Gibt die Anzahl der Behälter zurück, die zum Erstellen von Farbhistogrammen verwendet werden. |
|
|  | [setBinsCount(byte value)](#setBinsCount-byte-) | Legt die Anzahl der Behälter fest, die zum Erstellen von Farbhistogrammen verwendet werden. |
|
### ImageColorHistogramSearchCriteria(String filePath) {#ImageColorHistogramSearchCriteria-java.lang.String-}
```
public ImageColorHistogramSearchCriteria(String filePath)
```


Initialisiert eine neue Instanz der `[ImageColorHistogramSearchCriteria](../../com.groupdocs.watermark.search/imagecolorhistogramsearchcriteria)`-Klasse mit einem angegebenen Dateipfad.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | filePath | java.lang.String | Der Dateipfad, von dem das Bild geladen wird. |
|

### ImageColorHistogramSearchCriteria(InputStream stream) {#ImageColorHistogramSearchCriteria-java.io.InputStream-}
```
public ImageColorHistogramSearchCriteria(InputStream stream)
```


Initialisiert eine neue Instanz der `[ImageColorHistogramSearchCriteria](../../com.groupdocs.watermark.search/imagecolorhistogramsearchcriteria)` Klasse mit einem angegebenen Stream.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | stream | java.io.InputStream | Der Stream, von dem das Bild geladen wird. |
|

### getBinsCount() {#getBinsCount--}
```
public final byte getBinsCount()
```


Gibt die Anzahl der Behälter zurück, die zum Erstellen von Farbhistogrammen verwendet werden.


**Returns:**
byte - Der Standardwert ist 10.

### setBinsCount(byte value) {#setBinsCount-byte-}
```
public final void setBinsCount(byte value)
```


Legt die Anzahl der Behälter fest, die zum Erstellen von Farbhistogrammen verwendet werden.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Wert | byte | Der Standardwert ist 10. |
|

