---
title: "LoadOptions"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Representa opciones de carga de documento al cargar un documento."
type: docs
weight: 24
url: /es/java/com.groupdocs.watermark.options/loadoptions/
---
**Inheritance:**
java.lang.Object
```
public class LoadOptions
```

Representa opciones de carga de documento al cargar un documento.

**Learn more:**

* [Loading documents](../https://docs.groupdocs.com/display/watermarkjava/Loading+documents)
* [Load from local disk](../https://docs.groupdocs.com/display/watermarkjava/Load+from+local+disk)
* [Load from stream](../https://docs.groupdocs.com/display/watermarkjava/Load+from+stream)
* [Load document of specific format](../https://docs.groupdocs.com/display/watermarkjava/Load+document+of+specific+format)
* [Load password-protected document](../https://docs.groupdocs.com/display/watermarkjava/Load+password-protected+document)

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [LoadOptions()](#LoadOptions--) | Inicializa una nueva instancia de la clase `[LoadOptions](../../com.groupdocs.watermark.options/loadoptions)`. |
|
|  | [LoadOptions(String password)](#LoadOptions-java.lang.String-) | Inicializa una nueva instancia de la clase `[LoadOptions](../../com.groupdocs.watermark.options/loadoptions)` con una contraseña especificada. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getPassword()](#getPassword--) | Obtiene la contraseña para abrir un documento cifrado. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Establece la contraseña para abrir un documento cifrado. |
|
|  | [getFormatFamily()](#getFormatFamily--) | Obtiene la familia de formato del documento, indicando su tipo (p. ej., Imagen, Pdf, Hoja de cálculo, etc.). |
|
|  | [setFormatFamily(int formatFamily)](#setFormatFamily-int-) | Establece la familia de formato del documento, indicando su tipo (p. ej., Imagen, Pdf, Hoja de cálculo, etc.). |
|
|  | [getFileType()](#getFileType--) | Obtiene el tipo del archivo, indicando su tipo (p. ej., docx, pdf, xlsx, etc.). |
|
|  | [setFileType(FileType fileType)](#setFileType-com.groupdocs.watermark.common.FileType-) | Establece el tipo del archivo, indicando su tipo (p. ej., docx, pdf, xlsx, etc.). |
|
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


Inicializa una nueva instancia de la clase `[LoadOptions](../../com.groupdocs.watermark.options/loadoptions)`.


### LoadOptions(String password) {#LoadOptions-java.lang.String-}
```
public LoadOptions(String password)
```


Inicializa una nueva instancia de la clase `[LoadOptions](../../com.groupdocs.watermark.options/loadoptions)` con una contraseña especificada.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | contraseña | java.lang.String | La contraseña para abrir contenido cifrado. |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Obtiene la contraseña para abrir un documento cifrado.


**Returns:**
java.lang.String - La contraseña para abrir un documento cifrado.

### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Establece la contraseña para abrir un documento cifrado.

La contraseña puede ser nula o una cadena vacía. El valor predeterminado es nulo.
Si el contenido no está cifrado, establezca esto como nulo o una cadena vacía.

El siguiente ejemplo muestra cómo cargar un documento protegido con una contraseña.
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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | java.lang.String | La contraseña para abrir un documento cifrado. |
|

### getFormatFamily() {#getFormatFamily--}
```
public int getFormatFamily()
```


Obtiene la familia de formato del documento, indicando su tipo (p. ej., Imagen, Pdf, Hoja de cálculo, etc.).


**Returns:**
int - formatFamily El tipo de archivo.

### setFormatFamily(int formatFamily) {#setFormatFamily-int-}
```
public void setFormatFamily(int formatFamily)
```


Establece la familia de formato del documento, indicando su tipo (p. ej., Imagen, Pdf, Hoja de cálculo, etc.).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | formatFamily | int | El tipo de archivo. |
|

### getFileType() {#getFileType--}
```
public FileType getFileType()
```


Obtiene el tipo del archivo, indicando su tipo (p. ej., docx, pdf, xlsx, etc.).


**Returns:**
[FileType](../../com.groupdocs.watermark.common/filetype) - fileType The file type.

### setFileType(FileType fileType) {#setFileType-com.groupdocs.watermark.common.FileType-}
```
public void setFileType(FileType fileType)
```


Establece el tipo del archivo, indicando su tipo (p. ej., docx, pdf, xlsx, etc.).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.watermark.common/filetype) | El tipo de archivo. |
|

