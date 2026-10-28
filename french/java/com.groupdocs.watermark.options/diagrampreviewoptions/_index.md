---
title: "DiagramPreviewOptions"
second_title: "GroupDocs.Watermark pour Java Référence API"
description: "Fournit des options pour définir les exigences et les délégués de flux pour la génération d’aperçu d’un document Diagram."
type: docs
weight: 12
url: /fr/java/com.groupdocs.watermark.options/diagrampreviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)
```
public class DiagramPreviewOptions extends PreviewOptions
```

Fournit des options pour définir les exigences et les délégués de flux pour la génération d’aperçu d’un document Diagram.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [DiagramPreviewOptions(ICreatePageStream createPageStream)](#DiagramPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-) | Initialise une nouvelle instance de la classe `[DiagramPreviewOptions](../../com.groupdocs.watermark.options/diagrampreviewoptions)` entraînant la fermeture du flux de sortie. |
|
|  | [DiagramPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)](#DiagramPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | Initialise une nouvelle instance de la classe `[DiagramPreviewOptions](../../com.groupdocs.watermark.options/diagrampreviewoptions)` entraînant le retour du flux de sortie au client pour une utilisation ultérieure. |
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
|  | [getHighQualityRendering()](#getHighQualityRendering--) | Obtient l'indicateur de rendu haute qualité. |
|
|  | [setHighQualityRendering(boolean value)](#setHighQualityRendering-boolean-) | Définit l'indicateur de rendu haute qualité. |
|
### DiagramPreviewOptions(ICreatePageStream createPageStream) {#DiagramPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-}
```
public DiagramPreviewOptions(ICreatePageStream createPageStream)
```


Initialise une nouvelle instance de la classe `[DiagramPreviewOptions](../../com.groupdocs.watermark.options/diagrampreviewoptions)` entraînant la fermeture du flux de sortie.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Crée un flux pour un aperçu de page spécifique. |
|

### DiagramPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream) {#DiagramPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public DiagramPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)
```


Initialise une nouvelle instance de la classe `[DiagramPreviewOptions](../../com.groupdocs.watermark.options/diagrampreviewoptions)` entraînant le retour du flux de sortie au client pour une utilisation ultérieure.


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

La valeur par défaut est 300.

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

La valeur par défaut est 300.

<br />

|

### getHighQualityRendering() {#getHighQualityRendering--}
```
public final boolean getHighQualityRendering()
```


Obtient l'indicateur de rendu haute qualité.


**Returns:**
booléen - L'indicateur de rendu haute qualité.

<br />

*** ** * ** ***

Le rendu haute qualité utilise plus de ressources. La valeur par défaut est false.

<br />


### setHighQualityRendering(boolean value) {#setHighQualityRendering-boolean-}
```
public final void setHighQualityRendering(boolean value)
```


Définit l'indicateur de rendu haute qualité.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | boolean | L'indicateur de rendu haute qualité. |

<br />

*** ** * ** ***

Le rendu haute qualité utilise plus de ressources. La valeur par défaut est false.

<br />

|

