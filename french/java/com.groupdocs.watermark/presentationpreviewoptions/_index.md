---
title: "PresentationPreviewOptions"
second_title: "GroupDocs.Watermark pour Java Référence API"
description: "Fournit des options pour définir les exigences et les délégués de flux pour la génération d’aperçu d’un document Presentation."
type: docs
weight: 12
url: /fr/java/com.groupdocs.watermark/presentationpreviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)
```
public class PresentationPreviewOptions extends PreviewOptions
```

Fournit des options pour définir les exigences et les délégués de flux pour la génération d’aperçu d’un document Presentation.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [PresentationPreviewOptions(ICreatePageStream createPageStream)](#PresentationPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-) | Initialise une nouvelle instance de la classe `[PresentationPreviewOptions](../../com.groupdocs.watermark/presentationpreviewoptions)` provoquant la fermeture du flux de sortie. |
|
|  | [PresentationPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)](#PresentationPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | Initialise une nouvelle instance de la classe `[PresentationPreviewOptions](../../com.groupdocs.watermark/presentationpreviewoptions)` provoquant le renvoi du flux de sortie au client pour une utilisation ultérieure. |
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
|  | [setResolution(long value)](#setResolution-long-) | Définit la résolution des images générées, en points par pouce. |
|
### PresentationPreviewOptions(ICreatePageStream createPageStream) {#PresentationPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-}
```
public PresentationPreviewOptions(ICreatePageStream createPageStream)
```


Initialise une nouvelle instance de la classe `[PresentationPreviewOptions](../../com.groupdocs.watermark/presentationpreviewoptions)` provoquant la fermeture du flux de sortie.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Crée un flux pour un aperçu de page spécifique. |
|

### PresentationPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream) {#PresentationPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public PresentationPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)
```


Initialise une nouvelle instance de la classe `[PresentationPreviewOptions](../../com.groupdocs.watermark/presentationpreviewoptions)` provoquant le renvoi du flux de sortie au client pour une utilisation ultérieure.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Crée un flux pour un aperçu de page spécifique. |
|
|  | releasePageStream | [IReleasePageStream](../../com.groupdocs.watermark.options/ireleasepagestream) | Notifie que la génération de l'aperçu de page est terminée et obtient le flux de sortie. |
|

### DefaultResolution {#DefaultResolution}
```
public static final long DefaultResolution
```


Résolution par défaut en points par pouce.


### getResolution() {#getResolution--}
```
public final long getResolution()
```


Obtient la résolution des images générées, en points par pouce.


**Returns:**
long - La résolution des images générées, en points par pouce.

### setResolution(long value) {#setResolution-long-}
```
public final void setResolution(long value)
```


Définit la résolution des images générées, en points par pouce.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | long | La résolution des images générées, en points par pouce. |
|

