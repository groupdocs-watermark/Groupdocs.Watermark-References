---
title: "LoadOptions"
second_title: "GroupDocs.Watermark pour Java Référence API"
description: "Représente les options de chargement de document lors du chargement d'un document."
type: docs
weight: 24
url: /fr/java/com.groupdocs.watermark.options/loadoptions/
---
**Inheritance:**
java.lang.Object
```
public class LoadOptions
```

Représente les options de chargement de document lors du chargement d'un document.

**Learn more:**

* [Loading documents](../https://docs.groupdocs.com/display/watermarkjava/Loading+documents)
* [Load from local disk](../https://docs.groupdocs.com/display/watermarkjava/Load+from+local+disk)
* [Load from stream](../https://docs.groupdocs.com/display/watermarkjava/Load+from+stream)
* [Load document of specific format](../https://docs.groupdocs.com/display/watermarkjava/Load+document+of+specific+format)
* [Load password-protected document](../https://docs.groupdocs.com/display/watermarkjava/Load+password-protected+document)

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [LoadOptions()](#LoadOptions--) | Initialise une nouvelle instance de la classe `[LoadOptions](../../com.groupdocs.watermark.options/loadoptions)`. |
|
|  | [LoadOptions(String password)](#LoadOptions-java.lang.String-) | Initialise une nouvelle instance de la classe `[LoadOptions](../../com.groupdocs.watermark.options/loadoptions)` avec un mot de passe spécifié. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getPassword()](#getPassword--) | Obtient le mot de passe pour ouvrir un document chiffré. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Définit le mot de passe pour ouvrir un document chiffré. |
|
|  | [getFormatFamily()](#getFormatFamily--) | Obtient la famille de format du document, indiquant son type (par ex., Image, Pdf, Spreadsheet, etc.). |
|
|  | [setFormatFamily(int formatFamily)](#setFormatFamily-int-) | Définit la famille de format du document, indiquant son type (par ex., Image, Pdf, Spreadsheet, etc.). |
|
|  | [getFileType()](#getFileType--) | Obtient le type du fichier, indiquant son type (par ex., docx, pdf, xlsx, etc.). |
|
|  | [setFileType(FileType fileType)](#setFileType-com.groupdocs.watermark.common.FileType-) | Définit le type du fichier, indiquant son type (par ex., docx, pdf, xlsx, etc.). |
|
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


Initialise une nouvelle instance de la classe `[LoadOptions](../../com.groupdocs.watermark.options/loadoptions)`.


### LoadOptions(String password) {#LoadOptions-java.lang.String-}
```
public LoadOptions(String password)
```


Initialise une nouvelle instance de la classe `[LoadOptions](../../com.groupdocs.watermark.options/loadoptions)` avec un mot de passe spécifié.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | mot de passe | java.lang.String | Le mot de passe pour ouvrir un contenu chiffré. |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Obtient le mot de passe pour ouvrir un document chiffré.


**Returns:**
java.lang.String - Le mot de passe pour ouvrir un document chiffré.

### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Définit le mot de passe pour ouvrir un document chiffré.

Le mot de passe peut être nul ou une chaîne vide. La valeur par défaut est null.
Si le contenu n'est pas chiffré, définissez ceci sur null ou une chaîne vide.

L'exemple suivant montre comment charger un document protégé par un mot de passe.
>
> ````
> ```
>
>    LoadOptions loadOptions = new LoadOptions();
>    loadOptions.setPassword("pwd123");
>  
>    Watermarker watermarker = new Watermarker("D:\\doc.vsdx", loadOptions);
>    // ...
>    watermarker.close();
>  
> ```
> ````



**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | java.lang.String | Le mot de passe pour ouvrir un document chiffré. |
|

### getFormatFamily() {#getFormatFamily--}
```
public int getFormatFamily()
```


Obtient la famille de format du document, indiquant son type (par ex., Image, Pdf, Spreadsheet, etc.).


**Returns:**
int - formatFamily Le type de fichier.

### setFormatFamily(int formatFamily) {#setFormatFamily-int-}
```
public void setFormatFamily(int formatFamily)
```


Définit la famille de format du document, indiquant son type (par ex., Image, Pdf, Spreadsheet, etc.).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | formatFamily | int | Le type de fichier. |
|

### getFileType() {#getFileType--}
```
public FileType getFileType()
```


Obtient le type du fichier, indiquant son type (par ex., docx, pdf, xlsx, etc.).


**Returns:**
[FileType](../../com.groupdocs.watermark.common/filetype) - fileType The file type.

### setFileType(FileType fileType) {#setFileType-com.groupdocs.watermark.common.FileType-}
```
public void setFileType(FileType fileType)
```


Définit le type du fichier, indiquant son type (par ex., docx, pdf, xlsx, etc.).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.watermark.common/filetype) | Le type de fichier. |
|

