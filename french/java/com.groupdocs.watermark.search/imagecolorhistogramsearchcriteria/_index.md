---
title: "ImageColorHistogramSearchCriteria"
second_title: "GroupDocs.Watermark pour Java Référence API"
description: "Représente les critères de recherche pour trouver des images dans un contenu."
type: docs
weight: 30
url: /fr/java/com.groupdocs.watermark.search/imagecolorhistogramsearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria), [com.groupdocs.watermark.search.PageSearchCriteria](../../com.groupdocs.watermark.search/pagesearchcriteria), [com.groupdocs.watermark.search.ImageSearchCriteria](../../com.groupdocs.watermark.search/imagesearchcriteria)
```
public class ImageColorHistogramSearchCriteria extends ImageSearchCriteria
```

Représente les critères de recherche pour trouver des images dans un contenu.

<br />

*** ** * ** ***

Ce critère de recherche utilise des histogrammes de couleur d'image pour calculer la similarité d'image.

<br />


## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [ImageColorHistogramSearchCriteria(String filePath)](#ImageColorHistogramSearchCriteria-java.lang.String-) | Initialise une nouvelle instance de la classe `[ImageColorHistogramSearchCriteria](../../com.groupdocs.watermark.search/imagecolorhistogramsearchcriteria)` avec un chemin de fichier spécifié. |
|
|  | [ImageColorHistogramSearchCriteria(InputStream stream)](#ImageColorHistogramSearchCriteria-java.io.InputStream-) | Initialise une nouvelle instance de la classe `[ImageColorHistogramSearchCriteria](../../com.groupdocs.watermark.search/imagecolorhistogramsearchcriteria)` avec un flux spécifié. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getBinsCount()](#getBinsCount--) | Obtient le nombre de compartiments qui seront utilisés pour construire les histogrammes de couleur. |
|
|  | [setBinsCount(byte value)](#setBinsCount-byte-) | Définit le nombre de compartiments qui seront utilisés pour construire les histogrammes de couleur. |
|
### ImageColorHistogramSearchCriteria(String filePath) {#ImageColorHistogramSearchCriteria-java.lang.String-}
```
public ImageColorHistogramSearchCriteria(String filePath)
```


Initialise une nouvelle instance de la classe `[ImageColorHistogramSearchCriteria](../../com.groupdocs.watermark.search/imagecolorhistogramsearchcriteria)` avec un chemin de fichier spécifié.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.lang.String | Le chemin du fichier à partir duquel charger l'image. |
|

### ImageColorHistogramSearchCriteria(InputStream stream) {#ImageColorHistogramSearchCriteria-java.io.InputStream-}
```
public ImageColorHistogramSearchCriteria(InputStream stream)
```


Initialise une nouvelle instance de la classe `[ImageColorHistogramSearchCriteria](../../com.groupdocs.watermark.search/imagecolorhistogramsearchcriteria)` avec un flux spécifié.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | stream | java.io.InputStream | Le flux à partir duquel charger l'image. |
|

### getBinsCount() {#getBinsCount--}
```
public final byte getBinsCount()
```


Obtient le nombre de compartiments qui seront utilisés pour construire les histogrammes de couleur.


**Returns:**
byte - La valeur par défaut est 10.

### setBinsCount(byte value) {#setBinsCount-byte-}
```
public final void setBinsCount(byte value)
```


Définit le nombre de compartiments qui seront utilisés pour construire les histogrammes de couleur.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | byte | La valeur par défaut est 10. |
|

