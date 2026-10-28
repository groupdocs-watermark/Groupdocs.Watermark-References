---
title: "WordProcessingPreviewOptions"
second_title: "GroupDocs.Watermark pour Java Référence API"
description: "Fournit des options pour définir les exigences et les délégués de flux pour la génération d'aperçu d'un document WordProcessing."
type: docs
weight: 69
url: /fr/java/com.groupdocs.watermark.options/wordprocessingpreviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)
```
public class WordProcessingPreviewOptions extends PreviewOptions
```

Fournit des options pour définir les exigences et les délégués de flux pour la génération d'aperçu d'un document WordProcessing.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [WordProcessingPreviewOptions(ICreatePageStream createPageStream)](#WordProcessingPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-) | Initialise une nouvelle instance de la classe `[WordProcessingPreviewOptions](../../com.groupdocs.watermark.options/wordprocessingpreviewoptions)` qui ferme le flux de sortie. |
|
|  | [WordProcessingPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)](#WordProcessingPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | Initialise une nouvelle instance de la classe `[WordProcessingPreviewOptions](../../com.groupdocs.watermark.options/wordprocessingpreviewoptions)` qui renvoie le flux de sortie au client pour une utilisation ultérieure. |
|
## Champs

| Champ | Description |
| --- | --- |
|  | [DefaultResolution](#DefaultResolution) | Résolution par défaut en points par pouce. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getResolution()](#getResolution--) | Obtient la résolution des images générées, en points par pouce. |
|
|  | [setResolution(float value)](#setResolution-float-) | Définit la résolution des images générées, en points par pouce. |
|
### WordProcessingPreviewOptions(ICreatePageStream createPageStream) {#WordProcessingPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-}
```
public WordProcessingPreviewOptions(ICreatePageStream createPageStream)
```


Initialise une nouvelle instance de la classe `[WordProcessingPreviewOptions](../../com.groupdocs.watermark.options/wordprocessingpreviewoptions)` qui ferme le flux de sortie.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Crée un flux pour un aperçu de page spécifique. |
|

### WordProcessingPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream) {#WordProcessingPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public WordProcessingPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)
```


Initialise une nouvelle instance de la classe `[WordProcessingPreviewOptions](../../com.groupdocs.watermark.options/wordprocessingpreviewoptions)` qui renvoie le flux de sortie au client pour une utilisation ultérieure.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Crée un flux pour un aperçu de page spécifique. |
|
|  | releasePageStream | [IReleasePageStream](../../com.groupdocs.watermark.options/ireleasepagestream) | Notifie que la génération de l'aperçu de page est terminée et obtient le flux de sortie. |
|

### DefaultResolution {#DefaultResolution}
```
public static final float DefaultResolution
```


Résolution par défaut en points par pouce.


### getResolution() {#getResolution--}
```
public final float getResolution()
```


Obtient la résolution des images générées, en points par pouce.


**Returns:**
float - La résolution des images générées, en points par pouce.

<br />

*** ** * ** ***

La valeur par défaut est 96.

<br />


### setResolution(float value) {#setResolution-float-}
```
public final void setResolution(float value)
```


Définit la résolution des images générées, en points par pouce.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | float | La résolution des images générées, en points par pouce. |

<br />

*** ** * ** ***

La valeur par défaut est 96.

<br />

|

