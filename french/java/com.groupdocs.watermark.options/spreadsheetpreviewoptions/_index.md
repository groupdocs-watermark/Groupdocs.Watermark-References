---
title: "SpreadsheetPreviewOptions"
second_title: "GroupDocs.Watermark pour Java Référence API"
description: "Fournit des options pour définir les exigences et les délégués de flux pour la génération d'aperçu d'un document Spreadsheet."
type: docs
weight: 52
url: /fr/java/com.groupdocs.watermark.options/spreadsheetpreviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.watermark.options.PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)
```
public class SpreadsheetPreviewOptions extends PreviewOptions
```

Fournit des options pour définir les exigences et les délégués de flux pour la génération d'aperçu d'un document Spreadsheet.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [SpreadsheetPreviewOptions(ICreatePageStream createPageStream)](#SpreadsheetPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-) | Initialise une nouvelle instance de la classe `[SpreadsheetPreviewOptions](../../com.groupdocs.watermark.options/spreadsheetpreviewoptions)` entraînant la fermeture du flux de sortie. |
|
|  | [SpreadsheetPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)](#SpreadsheetPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | Initialise une nouvelle instance de la classe `[SpreadsheetPreviewOptions](../../com.groupdocs.watermark.options/spreadsheetpreviewoptions)` entraînant le renvoi du flux de sortie au client pour une utilisation ultérieure. |
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
|  | [getOnlyDataArea()](#getOnlyDataArea--) | Obtient le drapeau pour le rendu de la zone de données uniquement, sans en-têtes, pieds de page ni marges. |
|
|  | [setOnlyDataArea(boolean value)](#setOnlyDataArea-boolean-) | Définit le drapeau pour le rendu de la zone de données uniquement, sans en-têtes, pieds de page ni marges. |
|
### SpreadsheetPreviewOptions(ICreatePageStream createPageStream) {#SpreadsheetPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-}
```
public SpreadsheetPreviewOptions(ICreatePageStream createPageStream)
```


Initialise une nouvelle instance de la classe `[SpreadsheetPreviewOptions](../../com.groupdocs.watermark.options/spreadsheetpreviewoptions)` entraînant la fermeture du flux de sortie.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Crée un flux pour un aperçu de page spécifique. |
|

### SpreadsheetPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream) {#SpreadsheetPreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public SpreadsheetPreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)
```


Initialise une nouvelle instance de la classe `[SpreadsheetPreviewOptions](../../com.groupdocs.watermark.options/spreadsheetpreviewoptions)` entraînant le renvoi du flux de sortie au client pour une utilisation ultérieure.


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

La valeur par défaut est 96.

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

La valeur par défaut est 96.

<br />

|

### getOnlyDataArea() {#getOnlyDataArea--}
```
public final boolean getOnlyDataArea()
```


Obtient le drapeau pour le rendu de la zone de données uniquement, sans en-têtes, pieds de page ni marges.


**Returns:**
boolean - Le drapeau pour le rendu de la zone de données uniquement, sans en-têtes, pieds de page ni marges.

<br />

*** ** * ** ***

Ce drapeau entraîne le rendu de toute la feuille de calcul sur une seule page. La valeur par défaut est false.

<br />


### setOnlyDataArea(boolean value) {#setOnlyDataArea-boolean-}
```
public final void setOnlyDataArea(boolean value)
```


Définit le drapeau pour le rendu de la zone de données uniquement, sans en-têtes, pieds de page ni marges.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | boolean | Le drapeau pour le rendu de la zone de données uniquement, sans en-têtes, pieds de page ni marges. |

<br />

*** ** * ** ***

Ce drapeau entraîne le rendu de toute la feuille de calcul sur une seule page. La valeur par défaut est false.

<br />

|

