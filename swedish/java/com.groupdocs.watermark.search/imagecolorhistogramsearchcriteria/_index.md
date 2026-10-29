---
title: "ImageColorHistogramSearchCriteria"
second_title: "GroupDocs.Watermark för Java API-referens"
description: "Representerar sökkriterier för att hitta bilder i ett innehåll."
type: docs
weight: 30
url: /sv/java/com.groupdocs.watermark.search/imagecolorhistogramsearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria), [com.groupdocs.watermark.search.PageSearchCriteria](../../com.groupdocs.watermark.search/pagesearchcriteria), [com.groupdocs.watermark.search.ImageSearchCriteria](../../com.groupdocs.watermark.search/imagesearchcriteria)
```
public class ImageColorHistogramSearchCriteria extends ImageSearchCriteria
```

Representerar sökkriterier för att hitta bilder i ett innehåll.

<br />

*** ** * ** ***

Detta sökkriterium använder färg-histogram för bilder för att beräkna bildlikhet.

<br />


## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [ImageColorHistogramSearchCriteria(String filePath)](#ImageColorHistogramSearchCriteria-java.lang.String-) | Initierar en ny instans av klassen `[ImageColorHistogramSearchCriteria](../../com.groupdocs.watermark.search/imagecolorhistogramsearchcriteria)` med en angiven filsökväg. |
|
|  | [ImageColorHistogramSearchCriteria(InputStream stream)](#ImageColorHistogramSearchCriteria-java.io.InputStream-) | Initierar en ny instans av klassen `[ImageColorHistogramSearchCriteria](../../com.groupdocs.watermark.search/imagecolorhistogramsearchcriteria)` med en angiven ström. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getBinsCount()](#getBinsCount--) | Hämtar antalet fack som kommer att användas för att bygga färg-histogram. |
|
|  | [setBinsCount(byte value)](#setBinsCount-byte-) | Ställer in antalet fack som kommer att användas för att bygga färg-histogram. |
|
### ImageColorHistogramSearchCriteria(String filePath) {#ImageColorHistogramSearchCriteria-java.lang.String-}
```
public ImageColorHistogramSearchCriteria(String filePath)
```


Initierar en ny instans av klassen `[ImageColorHistogramSearchCriteria](../../com.groupdocs.watermark.search/imagecolorhistogramsearchcriteria)` med en angiven filsökväg.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | filePath | java.lang.String | Filsökvägen för att läsa in bilden från. |
|

### ImageColorHistogramSearchCriteria(InputStream stream) {#ImageColorHistogramSearchCriteria-java.io.InputStream-}
```
public ImageColorHistogramSearchCriteria(InputStream stream)
```


Initierar en ny instans av klassen `[ImageColorHistogramSearchCriteria](../../com.groupdocs.watermark.search/imagecolorhistogramsearchcriteria)` med en angiven ström.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | stream | java.io.InputStream | Strömmen för att läsa in bilden från. |
|

### getBinsCount() {#getBinsCount--}
```
public final byte getBinsCount()
```


Hämtar antalet fack som kommer att användas för att bygga färg-histogram.


**Returns:**
byte - Standardvärdet är 10.

### setBinsCount(byte value) {#setBinsCount-byte-}
```
public final void setBinsCount(byte value)
```


Ställer in antalet fack som kommer att användas för att bygga färg-histogram.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | byte | Standardvärdet är 10. |
|

