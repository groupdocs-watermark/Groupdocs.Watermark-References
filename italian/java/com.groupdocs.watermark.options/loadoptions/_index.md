---
title: "LoadOptions"
second_title: "Riferimento API di GroupDocs.Watermark per Java"
description: "Rappresenta le opzioni di caricamento del documento quando si carica un documento."
type: docs
weight: 24
url: /it/java/com.groupdocs.watermark.options/loadoptions/
---
**Inheritance:**
java.lang.Object
```
public class LoadOptions
```

Rappresenta le opzioni di caricamento del documento quando si carica un documento.

**Learn more:**

* [Loading documents](../https://docs.groupdocs.com/display/watermarkjava/Loading+documents)
* [Load from local disk](../https://docs.groupdocs.com/display/watermarkjava/Load+from+local+disk)
* [Load from stream](../https://docs.groupdocs.com/display/watermarkjava/Load+from+stream)
* [Load document of specific format](../https://docs.groupdocs.com/display/watermarkjava/Load+document+of+specific+format)
* [Load password-protected document](../https://docs.groupdocs.com/display/watermarkjava/Load+password-protected+document)

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [LoadOptions()](#LoadOptions--) | Inizializza una nuova istanza della classe `[LoadOptions](../../com.groupdocs.watermark.options/loadoptions)`. |
|
|  | [LoadOptions(String password)](#LoadOptions-java.lang.String-) | Inizializza una nuova istanza della classe `[LoadOptions](../../com.groupdocs.watermark.options/loadoptions)` con una password specificata. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getPassword()](#getPassword--) | Ottiene la password per aprire un documento crittografato. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Imposta la password per aprire un documento crittografato. |
|
|  | [getFormatFamily()](#getFormatFamily--) | Ottieni la famiglia di formato del documento, indicando il suo tipo (ad es., Image, Pdf, Spreadsheet, ecc.). |
|
|  | [setFormatFamily(int formatFamily)](#setFormatFamily-int-) | Imposta la famiglia di formato del documento, indicando il suo tipo (ad es., Image, Pdf, Spreadsheet, ecc.). |
|
|  | [getFileType()](#getFileType--) | Ottieni il tipo del file, indicando il suo tipo (ad es., docx, pdf, xlsx, ecc.). |
|
|  | [setFileType(FileType fileType)](#setFileType-com.groupdocs.watermark.common.FileType-) | Imposta il tipo del file, indicando il suo tipo (ad es., docx, pdf, xlsx, ecc.). |
|
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


Inizializza una nuova istanza della classe `[LoadOptions](../../com.groupdocs.watermark.options/loadoptions)`.


### LoadOptions(String password) {#LoadOptions-java.lang.String-}
```
public LoadOptions(String password)
```


Inizializza una nuova istanza della classe `[LoadOptions](../../com.groupdocs.watermark.options/loadoptions)` con una password specificata.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | password | java.lang.String | La password per aprire un contenuto crittografato. |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Ottiene la password per aprire un documento crittografato.


**Returns:**
java.lang.String - La password per aprire un documento crittografato.

### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Imposta la password per aprire un documento crittografato.

La password può essere null o una stringa vuota. Il valore predefinito è null.
Se il contenuto non è crittografato, impostalo su null o su una stringa vuota.

Il seguente esempio dimostra come caricare un documento protetto da password.
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | java.lang.String | La password per aprire un documento crittografato. |
|

### getFormatFamily() {#getFormatFamily--}
```
public int getFormatFamily()
```


Ottieni la famiglia di formato del documento, indicando il suo tipo (ad es., Image, Pdf, Spreadsheet, ecc.).


**Returns:**
int - formatFamily Il tipo di file.

### setFormatFamily(int formatFamily) {#setFormatFamily-int-}
```
public void setFormatFamily(int formatFamily)
```


Imposta la famiglia di formato del documento, indicando il suo tipo (ad es., Image, Pdf, Spreadsheet, ecc.).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | formatFamily | int | Il tipo di file. |
|

### getFileType() {#getFileType--}
```
public FileType getFileType()
```


Ottieni il tipo del file, indicando il suo tipo (ad es., docx, pdf, xlsx, ecc.).


**Returns:**
[FileType](../../com.groupdocs.watermark.common/filetype) - fileType The file type.

### setFileType(FileType fileType) {#setFileType-com.groupdocs.watermark.common.FileType-}
```
public void setFileType(FileType fileType)
```


Imposta il tipo del file, indicando il suo tipo (ad es., docx, pdf, xlsx, ecc.).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.watermark.common/filetype) | Il tipo di file. |
|

