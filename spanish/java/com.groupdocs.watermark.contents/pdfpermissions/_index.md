---
title: "PdfPermissions"
second_title: "Referencia de API de GroupDocs.Watermark para Java"
description: "Representa los permisos de los usuarios para un documento pdf."
type: docs
weight: 68
url: /es/java/com.groupdocs.watermark.contents/pdfpermissions/
---
**Inheritance:**
java.lang.Object
```
public final class PdfPermissions
```

Representa los permisos del usuario para un documento pdf.

## Campos

| Campo | Descripción |
| --- | --- |
|  | [PrintDocument](#PrintDocument) | Imprime el contenido. |
|
|  | [ModifyContent](#ModifyContent) | Modifica el contenido. |
|
|  | [ExtractContent](#ExtractContent) | Copiar o extraer de otro modo texto y gráficos del documento. |
|
|  | [ModifyTextAnnotations](#ModifyTextAnnotations) | Agregar o modificar anotaciones de texto. |
|
|  | [FillForm](#FillForm) | Rellenar los campos de formulario interactivo existentes. |
|
|  | [ExtractContentWithDisabilities](#ExtractContentWithDisabilities) | Extraer texto y gráficos. |
|
|  | [AssembleDocument](#AssembleDocument) | Ensambla el contenido. |
|
|  | [PrintingQuality](#PrintingQuality) | Imprime el contenido a una representación desde la cual se pueda generar una copia digital fiel del documento PDF. |
|
### PrintDocument {#PrintDocument}
```
public static final int PrintDocument
```


Imprime el contenido.

Controladores de seguridad de la revisión 2: Imprime el contenido.

Controladores de seguridad de la revisión 3 o superior: Imprime el contenido
(posiblemente no al nivel de mayor calidad, dependiendo de si
`#PrintingQuality.PrintingQuality` también está configurado).


### ModifyContent {#ModifyContent}
```
public static final int ModifyContent
```


Modifica el contenido.

Modifica el contenido del documento mediante operaciones distintas
que las controladas por `#ModifyTextAnnotations.ModifyTextAnnotations`, `#FillForm.FillForm`.


### ExtractContent {#ExtractContent}
```
public static final int ExtractContent
```


Copiar o extraer de otro modo texto y gráficos del documento.

Controladores de seguridad de la revisión 2: Copiar o extraer de otro modo texto y gráficos del contenido,
incluyendo la extracción de texto y gráficos (en apoyo a la accesibilidad para usuarios con
discapacidades o para otros propósitos).

Controladores de seguridad de la revisión 3 o superior: Copiar o extraer de otro modo texto y gráficos de
el contenido mediante operaciones distintas a las controladas por
`#ExtractContentWithDisabilities.ExtractContentWithDisabilities`.


### ModifyTextAnnotations {#ModifyTextAnnotations}
```
public static final int ModifyTextAnnotations
```


Agregar o modificar anotaciones de texto.

Agregar o modificar anotaciones de texto, rellenar campos de formulario interactivo,
y, si `#ModifyContent.ModifyContent` también está activado,
crear o modificar campos de formulario interactivos (incluidos los campos de firma).


### FillForm {#FillForm}
```
public static final int FillForm
```


Rellenar los campos de formulario interactivo existentes.

Controladores de seguridad de la revisión 3 o superior: Rellenar campos de formulario interactivos existentes
(incluidos los campos de firma), incluso si `#ModifyTextAnnotations.ModifyTextAnnotations` está desactivado.


### ExtractContentWithDisabilities {#ExtractContentWithDisabilities}
```
public static final int ExtractContentWithDisabilities
```


Extraer texto y gráficos.

Controladores de seguridad de la revisión 3 o superior: Extraer texto y gráficos
(para apoyar la accesibilidad de usuarios con discapacidades o para otros propósitos).


### AssembleDocument {#AssembleDocument}
```
public static final int AssembleDocument
```


Ensambla el contenido.

Controladores de seguridad de la revisión 3 o superior: Ensamblar el contenido (insertar, rotar o eliminar páginas
y crear marcadores o imágenes en miniatura), incluso si `#ModifyContent.ModifyContent` está desactivado.


### PrintingQuality {#PrintingQuality}
```
public static final int PrintingQuality
```


Imprime el contenido a una representación desde la cual se pueda generar una copia digital fiel del documento PDF.

Controladores de seguridad de la revisión 3 o superior: Imprimir el contenido a una representación desde la cual una copia fiel
de una copia digital del documento PDF pueda generarse. Cuando este bit está desactivado (y `#PrintDocument.PrintDocument`
está activado), la impresión se limita a una representación de bajo nivel de la apariencia, posiblemente de calidad degradada.


