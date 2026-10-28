---
title: "PdfPreviewOptions"
second_title: "GroupDocs.Watermark pour Java Référence API"
description: "Fournit des options pour définir les exigences et les délégués de flux pour la génération d'aperçu d'un document PDF."
type: docs
weight: 31
url: /fr/java/com.groupdocs.watermark.options/pdfpreviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)
```
public class PdfPreviewOptions extends PreviewOptions
```

Fournit des options pour définir les exigences et les délégués de flux pour la génération d'aperçu d'un document PDF.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [PdfPreviewOptions(ICreatePageStream createPageStream)](#PdfPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-) | Initialise une nouvelle instance de la classe `[PdfPreviewOptions](../../com.groupdocs.watermark.options/pdfpreviewoptions)` provoquant la fermeture du flux de sortie. |
|
|  | [PdfPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)](#PdfPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | Initialise une nouvelle instance de la classe `[PdfPreviewOptions](../../com.groupdocs.watermark.options/pdfpreviewoptions)` faisant retourner le flux de sortie au client pour une utilisation ultérieure. |
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
|  | [setResolution(int value)](#setResolution-int-) | Définit la résolution des images générées, en points par pouce. |
|
### PdfPreviewOptions(ICreatePageStream createPageStream) {#PdfPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-}
```
public PdfPreviewOptions(ICreatePageStream createPageStream)
```


Initialise une nouvelle instance de la classe `[PdfPreviewOptions](../../com.groupdocs.watermark.options/pdfpreviewoptions)` provoquant la fermeture du flux de sortie.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Crée un flux pour un aperçu de page spécifique. |
|

### PdfPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream) {#PdfPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public PdfPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)
```


Initialise une nouvelle instance de la classe `[PdfPreviewOptions](../../com.groupdocs.watermark.options/pdfpreviewoptions)` faisant retourner le flux de sortie au client pour une utilisation ultérieure.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Crée un flux pour un aperçu de page spécifique. |
|
|  | releasePageStream | [IReleasePageStream](../../com.groupdocs.watermark.options/ireleasepagestream) | Notifie que la génération de l'aperçu de page est terminée et obtient le flux de sortie. |
|

### DefaultResolution {#DefaultResolution}
```
public static final int DefaultResolution
```


Résolution par défaut en points par pouce.


### getResolution() {#getResolution--}
```
public final int getResolution()
```


Obtient la résolution des images générées, en points par pouce.


**Returns:**
int - La résolution des images générées, en points par pouce.

<br />

*** ** * ** ***

La valeur par défaut est 150.

<br />


### setResolution(int value) {#setResolution-int-}
```
public final void setResolution(int value)
```


Définit la résolution des images générées, en points par pouce.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | int | La résolution des images générées, en points par pouce. |

<br />

*** ** * ** ***

La valeur par défaut est 150.

<br />

|

