---
title: "PreviewOptions"
second_title: "GroupDocs.Watermark pour Java Référence API"
description: "Fournit des options pour définir les exigences et les délégués de flux pour la génération d'aperçu."
type: docs
weight: 47
url: /fr/java/com.groupdocs.watermark.options/previewoptions/
---
**Inheritance:**
java.lang.Object
```
public class PreviewOptions
```

Fournit des options pour définir les exigences et les délégués de flux pour la génération d'aperçu.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [PreviewOptions(ICreatePageStream createPageStream)](#PreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-) | Initialise une nouvelle instance de la classe `[PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)` provoquant la fermeture du flux de sortie. |
|
|  | [PreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)](#PreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | Initialise une nouvelle instance de la classe `[PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)` faisant retourner le flux de sortie au client pour une utilisation ultérieure. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getWidth()](#getWidth--) | Obtient la largeur de l'aperçu de page. |
|
|  | [setWidth(int value)](#setWidth-int-) | Définit la largeur de l'aperçu de page. |
|
|  | [getHeight()](#getHeight--) | Obtient la hauteur de l'aperçu de page. |
|
|  | [setHeight(int value)](#setHeight-int-) | Définit la hauteur de l'aperçu de page. |
|
|  | [getPageNumbers()](#getPageNumbers--) | Obtient un tableau de numéros de page pour générer des aperçus. |
|
|  | [setPageNumbers(int[] value)](#setPageNumbers-int---) | Définit un tableau de numéros de page pour générer des aperçus. |
|
|  | [getPreviewFormat()](#getPreviewFormat--) | Obtient le format de l'image d'aperçu. |
|
|  | [setPreviewFormat(int value)](#setPreviewFormat-int-) | Définit le format de l'image d'aperçu. |
|
|  | [getCreatePageStream()](#getCreatePageStream--) | Obtient une instance de la classe de création de flux de page. |
|
|  | [setCreatePageStream(ICreatePageStream value)](#setCreatePageStream-com.groupdocs.watermark.options.ICreatePageStream-) | Définit une instance de la classe de création de flux de page. |
|
|  | [getReleasePageStream()](#getReleasePageStream--) | Obtient une instance de la classe de finalisation de l'aperçu de page. |
|
|  | [setReleasePageStream(IReleasePageStream value)](#setReleasePageStream-com.groupdocs.watermark.options.IReleasePageStream-) | Définit une instance de la classe de finalisation de l'aperçu de page. |
|
### PreviewOptions(ICreatePageStream createPageStream) {#PreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-}
```
public PreviewOptions(ICreatePageStream createPageStream)
```


Initialise une nouvelle instance de la classe `[PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)` provoquant la fermeture du flux de sortie.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Crée un flux pour un aperçu de page spécifique. |
|

### PreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream) {#PreviewOptions-com.groupdocs.watermark.options.ICreatePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public PreviewOptions(ICreatePageStream createPageStream, IReleasePageStream releasePageStream)
```


Initialise une nouvelle instance de la classe `[PreviewOptions](../../com.groupdocs.watermark.options/previewoptions)` faisant retourner le flux de sortie au client pour une utilisation ultérieure.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | createPageStream | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | Crée un flux pour un aperçu de page spécifique. |
|
|  | releasePageStream | [IReleasePageStream](../../com.groupdocs.watermark.options/ireleasepagestream) | Notifie que la génération de l'aperçu de page est terminée et obtient le flux de sortie. |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Obtient la largeur de l'aperçu de page.


**Returns:**
int - La largeur de l'aperçu de page.

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Définit la largeur de l'aperçu de page.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | int | La largeur de l'aperçu de page. |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Obtient la hauteur de l'aperçu de page.


**Returns:**
int - La hauteur de l'aperçu de page.

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Définit la hauteur de l'aperçu de page.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | int | La hauteur de l'aperçu de page. |
|

### getPageNumbers() {#getPageNumbers--}
```
public final int[] getPageNumbers()
```


Obtient un tableau de numéros de page pour générer des aperçus.


**Returns:**
int[] - Le tableau de numéros de page pour générer des aperçus.

### setPageNumbers(int[] value) {#setPageNumbers-int---}
```
public final void setPageNumbers(int[] value)
```


Définit un tableau de numéros de page pour générer des aperçus.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | int[] | Le tableau de numéros de page pour générer des aperçus. |
|

### getPreviewFormat() {#getPreviewFormat--}
```
public final int getPreviewFormat()
```


Obtient le format de l'image d'aperçu.


**Returns:**
int - Le format de l'image d'aperçu.

### setPreviewFormat(int value) {#setPreviewFormat-int-}
```
public final void setPreviewFormat(int value)
```


Définit le format de l'image d'aperçu.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | int | Le format de l'image d'aperçu. |
|

### getCreatePageStream() {#getCreatePageStream--}
```
public final ICreatePageStream getCreatePageStream()
```


Obtient une instance de la classe de création de flux de page.


**Returns:**
[ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) - The instance of the page stream creation class.

### setCreatePageStream(ICreatePageStream value) {#setCreatePageStream-com.groupdocs.watermark.options.ICreatePageStream-}
```
public final void setCreatePageStream(ICreatePageStream value)
```


Définit une instance de la classe de création de flux de page.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | [ICreatePageStream](../../com.groupdocs.watermark.options/icreatepagestream) | L'instance de la classe de création du flux de page. |
|

### getReleasePageStream() {#getReleasePageStream--}
```
public final IReleasePageStream getReleasePageStream()
```


Obtient une instance de la classe de finalisation de l'aperçu de page.


**Returns:**
[IReleasePageStream](../../com.groupdocs.watermark.options/ireleasepagestream) - The instance of the page preview completion delegate.

### setReleasePageStream(IReleasePageStream value) {#setReleasePageStream-com.groupdocs.watermark.options.IReleasePageStream-}
```
public final void setReleasePageStream(IReleasePageStream value)
```


Définit une instance de la classe de finalisation de l'aperçu de page.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | [IReleasePageStream](../../com.groupdocs.watermark.options/ireleasepagestream) | L'instance du délégué d'achèvement de l'aperçu de page. |
|

