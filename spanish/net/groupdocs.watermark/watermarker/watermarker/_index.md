---
title: Watermarker
second_title: Referencia de API de GroupDocs.Watermark para .NET
description: Inicializa una nueva instancia delWatermarkergroupdocs.watermark/watermarker clase con la ruta del documento especificado.
type: docs
weight: 10
url: /es/net/groupdocs.watermark/watermarker/watermarker/
---
## Watermarker(string) {#constructor_4}

Inicializa una nueva instancia del[`Watermarker`](../../watermarker) clase con la ruta del documento especificado.

```csharp
public Watermarker(string filePath)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| filePath | String | La ruta del archivo desde el que cargar el documento. |

### Excepciones

| excepción | condición |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | El tipo de documento proporcionado no es compatible. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | La contraseña proporcionada es incorrecta. |

### Observaciones

Más información sobre la carga de documentos: [Cargando documentos](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### Ejemplos

Cargue y guarde un contenido de cualquier formato compatible.

```csharp
// Carga un contenido de un archivo.
using (Watermarker watermarker = new Watermarker("D:\\input.pdf"))
{
    // Usar métodos de la clase Watermarker para agregar, buscar o eliminar marcas de agua.

    // Guarda el documento.
    watermarker.Save("D:\\output.pdf");
}
```

### Ver también

* class [Watermarker](../../watermarker)
* espacio de nombres [GroupDocs.Watermark](../../watermarker)
* asamblea [GroupDocs.Watermark](../../../)

---

## Watermarker(string, LoadOptions) {#constructor_5}

Inicializa una nueva instancia del[`Watermarker`](../../watermarker)clase con la ruta del documento especificada y opciones de carga.

```csharp
public Watermarker(string filePath, LoadOptions options)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| filePath | String | La ruta del archivo desde el que cargar el documento. |
| options | LoadOptions | Opciones adicionales para usar al cargar un documento. |

### Excepciones

| excepción | condición |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | El tipo de documento proporcionado no es compatible. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | La contraseña proporcionada es incorrecta. |

### Observaciones

Más información sobre la carga de documentos: [Cargando documentos](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### Ejemplos

Cargar documento PDF encriptado usando contraseña.

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
loadOptions.Password = "123";
using (Watermarker watermarker = new Watermarker(@"C:\Documents\test.pdf", loadOptions))
{
    // ...
}
```

### Ver también

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [Watermarker](../../watermarker)
* espacio de nombres [GroupDocs.Watermark](../../watermarker)
* asamblea [GroupDocs.Watermark](../../../)

---

## Watermarker(string, WatermarkerSettings) {#constructor_7}

Inicializa una nueva instancia del[`Watermarker`](../../watermarker) clase con la configuración y la ruta del documento especificados.

```csharp
public Watermarker(string filePath, WatermarkerSettings settings)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| filePath | String | La ruta del archivo desde el que cargar el documento. |
| settings | WatermarkerSettings | Configuraciones adicionales para usar cuando se trabaja con un documento cargado. |

### Excepciones

| excepción | condición |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | El tipo de documento proporcionado no es compatible. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | La contraseña proporcionada es incorrecta. |

### Observaciones

Más información sobre la carga de documentos: [Cargando documentos](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### Ejemplos

Establecer objetos de búsqueda globalmente (para todos los documentos que se cargarán después de eso).

```csharp
WatermarkerSettings settings = new WatermarkerSettings();
settings.SearchableObjects = new SearchableObjects
{
    WordProcessingSearchableObjects = WordProcessingSearchableObjects.Hyperlinks
                                    | WordProcessingSearchableObjects.Text,
    SpreadsheetSearchableObjects = SpreadsheetSearchableObjects.HeadersFooters,
    PresentationSearchableObjects = PresentationSearchableObjects.SlidesBackgrounds
                                  | PresentationSearchableObjects.Shapes,
    DiagramSearchableObjects = DiagramSearchableObjects.None,
    PdfSearchableObjects = PdfSearchableObjects.All
};

foreach (string file in Directory.GetFiles(@"D:\files"))
{
    using (Watermarker watermarker = new Watermarker(file, settings))
    {
        PossibleWatermarkCollection watermarks = watermarker.Search();

        // El código para trabajar con marcas de agua encontradas va aquí.
    }
}
```

### Ver también

* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* espacio de nombres [GroupDocs.Watermark](../../watermarker)
* asamblea [GroupDocs.Watermark](../../../)

---

## Watermarker(string, LoadOptions, WatermarkerSettings) {#constructor_6}

Inicializa una nueva instancia del[`Watermarker`](../../watermarker) clase con la ruta del documento especificada , las opciones de carga y la configuración.

```csharp
public Watermarker(string filePath, LoadOptions options, WatermarkerSettings settings)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| filePath | String | La ruta del archivo desde el que cargar el documento. |
| options | LoadOptions | Opciones adicionales para usar al cargar un documento. |
| settings | WatermarkerSettings | Configuraciones adicionales para usar cuando se trabaja con un documento cargado. |

### Excepciones

| excepción | condición |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | El tipo de documento proporcionado no es compatible. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | La contraseña proporcionada es incorrecta. |

### Observaciones

Más información sobre la carga de documentos: [Cargando documentos](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### Ejemplos

Encuentra fragmentos de texto particulares en el cuerpo/asunto del mensaje de correo electrónico.

```csharp
WatermarkerSettings settings = new WatermarkerSettings();
settings.SearchableObjects = new SearchableObjects
{
    EmailSearchableObjects = EmailSearchableObjects.Subject
                           | EmailSearchableObjects.HtmlBody
                           | EmailSearchableObjects.PlainTextBody
};
EmailLoadOptions loadOptions = new EmailLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\test.msg", loadOptions, settings))
{
    SearchCriteria criteria = new TextSearchCriteria("test", false);
    // Tenga en cuenta que la búsqueda se realiza solo si pasa la instancia de TextSearchCriteria al método de búsqueda
    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    // Eliminar fragmentos de texto encontrados
    watermarks.Clear();
    // Guardar cambios
    watermarker.Save();
}
```

### Ver también

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* espacio de nombres [GroupDocs.Watermark](../../watermarker)
* asamblea [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream) {#constructor}

Inicializa una nueva instancia del[`Watermarker`](../../watermarker) clase con el flujo especificado.

```csharp
public Watermarker(Stream document)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| document | Stream | La secuencia desde la que cargar el documento. |

### Excepciones

| excepción | condición |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | El tipo de documento proporcionado no es compatible. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | La contraseña proporcionada es incorrecta. |

### Observaciones

Obtenga más información sobre cómo cargar documentos [Cargando documentos](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### Ejemplos

Cargue y guarde un documento de cualquier formato compatible.

```csharp
// Carga un contenido de una secuencia.
using (FileStream inputStream = File.Open("D:\\input.pdf", FileMode.Open))
using (FileStream outputStream = File.Open("D:\\output.pdf", FileMode.Create))
using (Watermarker watermarker = new Watermarker(inputStream))
{
    // Usar métodos de la clase Watermarker para agregar, buscar o eliminar marcas de agua.

    // Guardar cambios.
    watermarker.Save(outputStream);
}
```

### Ver también

* class [Watermarker](../../watermarker)
* espacio de nombres [GroupDocs.Watermark](../../watermarker)
* asamblea [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, LoadOptions) {#constructor_1}

Inicializa una nueva instancia del[`Watermarker`](../../watermarker) clase con el stream especificado y las opciones de carga.

```csharp
public Watermarker(Stream document, LoadOptions options)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| document | Stream | La secuencia desde la que cargar el documento. |
| options | LoadOptions | Opciones adicionales para usar al cargar un documento. |

### Excepciones

| excepción | condición |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | El tipo de documento proporcionado no es compatible. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | La contraseña proporcionada es incorrecta. |

### Observaciones

Obtenga más información sobre cómo cargar documentos [Cargando documentos](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### Ejemplos

Cargar documento PDF encriptado usando contraseña

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
loadOptions.Password = "123";
using (FileStream fileStream = File.Open(@"C:\Documents\test.pdf", FileMode.Open))
using (Watermarker watermarker = new Watermarker(fileStream, loadOptions))
{
    // ...
}
```

### Ver también

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [Watermarker](../../watermarker)
* espacio de nombres [GroupDocs.Watermark](../../watermarker)
* asamblea [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, WatermarkerSettings) {#constructor_3}

Inicializa una nueva instancia del[`Watermarker`](../../watermarker) clase con el stream y settings. especificados

```csharp
public Watermarker(Stream document, WatermarkerSettings settings)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| document | Stream | La secuencia desde la que cargar el documento. |
| settings | WatermarkerSettings | Configuraciones adicionales para usar cuando se trabaja con un documento cargado. |

### Excepciones

| excepción | condición |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | El tipo de documento proporcionado no es compatible. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | La contraseña proporcionada es incorrecta. |

### Observaciones

Obtenga más información sobre cómo cargar documentos [Cargando documentos](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### Ejemplos

Establecer objetos de búsqueda globalmente (para todos los documentos que se cargarán después de eso).

```csharp
WatermarkerSettings settings = new WatermarkerSettings();
settings.SearchableObjects = new SearchableObjects
{
    WordProcessingSearchableObjects = WordProcessingSearchableObjects.Hyperlinks
                                    | WordProcessingSearchableObjects.Text,
    SpreadsheetSearchableObjects = SpreadsheetSearchableObjects.HeadersFooters,
    PresentationSearchableObjects = PresentationSearchableObjects.SlidesBackgrounds
                                  | PresentationSearchableObjects.Shapes,
    DiagramSearchableObjects = DiagramSearchableObjects.None,
    PdfSearchableObjects = PdfSearchableObjects.All
};

foreach (string file in Directory.GetFiles(@"D:\files"))
{
    using (FileStream fileStream = File.Open(file, FileMode.Open))
    using (Watermarker watermarker = new Watermarker(fileStream, settings))
    {
        PossibleWatermarkCollection watermarks = watermarker.Search();

        // El código para trabajar con marcas de agua encontradas va aquí.
    }
}
```

### Ver también

* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* espacio de nombres [GroupDocs.Watermark](../../watermarker)
* asamblea [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, LoadOptions, WatermarkerSettings) {#constructor_2}

Inicializa una nueva instancia del[`Watermarker`](../../watermarker) clase con el flujo especificado, cargar opciones y configuraciones.

```csharp
public Watermarker(Stream document, LoadOptions options, WatermarkerSettings settings)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| document | Stream | La secuencia desde la que cargar el documento. |
| options | LoadOptions | Opciones adicionales para usar al cargar un documento. |
| settings | WatermarkerSettings | Configuraciones adicionales para usar cuando se trabaja con un documento cargado. |

### Excepciones

| excepción | condición |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | El tipo de documento proporcionado no es compatible. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | La contraseña proporcionada es incorrecta. |

### Observaciones

Obtenga más información sobre cómo cargar documentos [Cargando documentos](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### Ejemplos

Encuentra fragmentos de texto particulares en el cuerpo/asunto del mensaje de correo electrónico.

```csharp
WatermarkerSettings settings = new WatermarkerSettings();
settings.SearchableObjects = new SearchableObjects
{
    EmailSearchableObjects = EmailSearchableObjects.Subject
                           | EmailSearchableObjects.HtmlBody
                           | EmailSearchableObjects.PlainTextBody
};
EmailLoadOptions loadOptions = new EmailLoadOptions();
using (FileStream fileStream = File.Open(@"D:\test.msg", FileMode.Open))
using (Watermarker watermarker = new Watermarker(fileStream, loadOptions, settings))
{
    SearchCriteria criteria = new TextSearchCriteria("test", false);
    // Tenga en cuenta que la búsqueda se realiza solo si pasa la instancia de TextSearchCriteria al método de búsqueda
    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    // Eliminar fragmentos de texto encontrados
    watermarks.Clear();
    // Guardar cambios
    watermarker.Save();
}
```

### Ver también

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* espacio de nombres [GroupDocs.Watermark](../../watermarker)
* asamblea [GroupDocs.Watermark](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
