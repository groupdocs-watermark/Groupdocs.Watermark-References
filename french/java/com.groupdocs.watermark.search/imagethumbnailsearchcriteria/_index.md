---
title: "ImageThumbnailSearchCriteria"
second_title: "GroupDocs.Watermark pour Java Référence API"
description: "Représente les critères de recherche pour trouver des images dans un contenu."
type: docs
weight: 33
url: /fr/java/com.groupdocs.watermark.search/imagethumbnailsearchcriteria/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.search.SearchCriteria](../../com.groupdocs.watermark.search/searchcriteria), [com.groupdocs.watermark.search.PageSearchCriteria](../../com.groupdocs.watermark.search/pagesearchcriteria), [com.groupdocs.watermark.search.ImageSearchCriteria](../../com.groupdocs.watermark.search/imagesearchcriteria)
```
public class ImageThumbnailSearchCriteria extends ImageSearchCriteria
```

Représente les critères de recherche pour trouver des images dans un contenu.

<br />

*** ** * ** ***

Ce critère de recherche utilise une miniature d'image binarisée pour calculer la similarité d'images.

<br />


## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [ImageThumbnailSearchCriteria(String filePath)](#ImageThumbnailSearchCriteria-java.lang.String-) | Initialise une nouvelle instance de la classe `[ImageThumbnailSearchCriteria](../../com.groupdocs.watermark.search/imagethumbnailsearchcriteria)` avec un chemin de fichier spécifié. |
|
|  | [ImageThumbnailSearchCriteria(InputStream stream)](#ImageThumbnailSearchCriteria-java.io.InputStream-) | Initialise une nouvelle instance de la classe `[ImageThumbnailSearchCriteria](../../com.groupdocs.watermark.search/imagethumbnailsearchcriteria)` avec un flux spécifié. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getThumbnailSize()](#getThumbnailSize--) | Obtient la taille de la miniature. |
|
|  | [setThumbnailSize(byte value)](#setThumbnailSize-byte-) | Définit la taille de la miniature. |
|
### ImageThumbnailSearchCriteria(String filePath) {#ImageThumbnailSearchCriteria-java.lang.String-}
```
public ImageThumbnailSearchCriteria(String filePath)
```


Initialise une nouvelle instance de la classe `[ImageThumbnailSearchCriteria](../../com.groupdocs.watermark.search/imagethumbnailsearchcriteria)` avec un chemin de fichier spécifié.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.lang.String | Le chemin du fichier à partir duquel charger l'image. |
|

### ImageThumbnailSearchCriteria(InputStream stream) {#ImageThumbnailSearchCriteria-java.io.InputStream-}
```
public ImageThumbnailSearchCriteria(InputStream stream)
```


Initialise une nouvelle instance de la classe `[ImageThumbnailSearchCriteria](../../com.groupdocs.watermark.search/imagethumbnailsearchcriteria)` avec un flux spécifié.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | stream | java.io.InputStream | Le flux à partir duquel charger l'image. |
|

### getThumbnailSize() {#getThumbnailSize--}
```
public final byte getThumbnailSize()
```


Obtient la taille de la miniature.


**Returns:**
byte - Par défaut, une miniature 32X32 sera utilisée.

### setThumbnailSize(byte value) {#setThumbnailSize-byte-}
```
public final void setThumbnailSize(byte value)
```


Définit la taille de la miniature.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | byte | Par défaut, une miniature 32X32 sera utilisée. |
|

