---
title: "ImageColorHistogramSearchCriteria"
second_title: "GroupDocs.Watermark for Java API-referentie"
description: "Stelt zoekcriteria voor het vinden van afbeeldingen in een inhoud voor."
type: docs
weight: 30
url: /nl/java/com.groupdocs.watermark.search/imagecolorhistogramsearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria), [com.groupdocs.watermark.search.PageSearchCriteria](../../com.groupdocs.watermark.search/pagesearchcriteria), [com.groupdocs.watermark.search.ImageSearchCriteria](../../com.groupdocs.watermark.search/imagesearchcriteria)
```
public class ImageColorHistogramSearchCriteria extends ImageSearchCriteria
```

Stelt zoekcriteria voor het vinden van afbeeldingen in een inhoud voor.

<br />

*** ** * ** ***

Deze zoekcriteria gebruikt kleurhistogrammen van afbeeldingen voor het berekenen van afbeeldingsgelijkenis.

<br />


## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [ImageColorHistogramSearchCriteria(String filePath)](#ImageColorHistogramSearchCriteria-java.lang.String-) | Initialiseert een nieuw exemplaar van de `[ImageColorHistogramSearchCriteria](../../com.groupdocs.watermark.search/imagecolorhistogramsearchcriteria)` klasse met een opgegeven bestandspad. |
|
|  | [ImageColorHistogramSearchCriteria(InputStream stream)](#ImageColorHistogramSearchCriteria-java.io.InputStream-) | Initialiseert een nieuw exemplaar van de `[ImageColorHistogramSearchCriteria](../../com.groupdocs.watermark.search/imagecolorhistogramsearchcriteria)` klasse met een opgegeven stream. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getBinsCount()](#getBinsCount--) | Haalt het aantal bakken op dat zal worden gebruikt voor het bouwen van kleurhistogrammen. |
|
|  | [setBinsCount(byte value)](#setBinsCount-byte-) | Stelt het aantal bakken in dat zal worden gebruikt voor het bouwen van kleurhistogrammen. |
|
### ImageColorHistogramSearchCriteria(String filePath) {#ImageColorHistogramSearchCriteria-java.lang.String-}
```
public ImageColorHistogramSearchCriteria(String filePath)
```


Initialiseert een nieuw exemplaar van de `[ImageColorHistogramSearchCriteria](../../com.groupdocs.watermark.search/imagecolorhistogramsearchcriteria)` klasse met een opgegeven bestandspad.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | filePath | java.lang.String | Het bestandspad om de afbeelding van te laden. |
|

### ImageColorHistogramSearchCriteria(InputStream stream) {#ImageColorHistogramSearchCriteria-java.io.InputStream-}
```
public ImageColorHistogramSearchCriteria(InputStream stream)
```


Initialiseert een nieuw exemplaar van de `[ImageColorHistogramSearchCriteria](../../com.groupdocs.watermark.search/imagecolorhistogramsearchcriteria)` klasse met een opgegeven stream.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | stream | java.io.InputStream | De stream om de afbeelding van te laden. |
|

### getBinsCount() {#getBinsCount--}
```
public final byte getBinsCount()
```


Haalt het aantal bakken op dat zal worden gebruikt voor het bouwen van kleurhistogrammen.


**Returns:**
byte - De standaardwaarde is 10.

### setBinsCount(byte value) {#setBinsCount-byte-}
```
public final void setBinsCount(byte value)
```


Stelt het aantal bakken in dat zal worden gebruikt voor het bouwen van kleurhistogrammen.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | byte | De standaardwaarde is 10. |
|

