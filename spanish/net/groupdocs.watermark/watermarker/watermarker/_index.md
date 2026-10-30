---
title: "Watermarker"
second_title: "GroupDocs.Watermark para la referencia de API de .NET"
description: "Inicializa una nueva instancia de la clase Watermarkergroupdocs.watermark/watermarker con la ruta de documento especificada."
type: docs
weight: 10
url: /es/net/groupdocs.watermark/watermarker/watermarker/
---
## Watermarker(string) {#constructor_4}

Inicializa una nueva instancia de la clase [`Watermarker`](../../watermarker) con la ruta de documento especificada.

```csharp
public Watermarker(string filePath)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| filePath | String | La ruta del archivo desde la cual cargar el documento. |

### Excepciones

| excepción | condición |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | El tipo de documento proporcionado no es compatible. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | La contraseña proporcionada es incorrecta. |

### Observaciones

Obtenga más información sobre la carga de documentos: [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### Ejemplos

Carga y guarda un contenido de cualquier formato compatible.

```csharp
// Carga un contenido desde un archivo.
using (Watermarker watermarker = new Watermarker("D:\\input.pdf"))
{
    // Utiliza los métodos de la clase Watermarker para añadir, buscar o eliminar marcas de agua.

    // Guarde el documento.
    watermarker.Save("D:\\output.pdf");
}
```

### Ver también

* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(string, LoadOptions) {#constructor_5}

Inicializa una nueva instancia de la clase [`Watermarker`](../../watermarker) con la ruta de documento especificada y las opciones de carga.

```csharp
public Watermarker(string filePath, LoadOptions options)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| filePath | String | La ruta del archivo desde la cual cargar el documento. |
| opciones | LoadOptions | Opciones adicionales para usar al cargar un documento. |

### Excepciones

| excepción | condición |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | El tipo de documento proporcionado no es compatible. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | La contraseña proporcionada es incorrecta. |

### Observaciones

Obtenga más información sobre la carga de documentos: [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### Ejemplos

Cargue un documento PDF cifrado usando una contraseña.

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
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(string, WatermarkerSettings) {#constructor_7}

Inicializa una nueva instancia de la clase [`Watermarker`](../../watermarker) con la ruta de documento especificada y la configuración.

```csharp
public Watermarker(string filePath, WatermarkerSettings settings)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| filePath | String | La ruta del archivo desde la cual cargar el documento. |
| configuración | WatermarkerSettings | Configuraciones adicionales para usar al trabajar con el documento cargado. |

### Excepciones

| excepción | condición |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | El tipo de documento proporcionado no es compatible. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | La contraseña proporcionada es incorrecta. |

### Observaciones

Obtenga más información sobre la carga de documentos: [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### Ejemplos

Establezca objetos buscables globalmente (para todos los documentos que se cargarán después de eso).

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
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(string, LoadOptions, WatermarkerSettings) {#constructor_6}

Inicializa una nueva instancia de la clase [`Watermarker`](../../watermarker) con la ruta de documento especificada, las opciones de carga y la configuración.

```csharp
public Watermarker(string filePath, LoadOptions options, WatermarkerSettings settings)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| filePath | String | La ruta del archivo desde la cual cargar el documento. |
| opciones | LoadOptions | Opciones adicionales para usar al cargar un documento. |
| configuración | WatermarkerSettings | Configuraciones adicionales para usar al trabajar con el documento cargado. |

### Excepciones

| excepción | condición |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | El tipo de documento proporcionado no es compatible. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | La contraseña proporcionada es incorrecta. |

### Observaciones

Obtenga más información sobre la carga de documentos: [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### Ejemplos

Encuentre fragmentos de texto particulares en el cuerpo/asunto del mensaje de correo electrónico.

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
    // Nota, la búsqueda se realiza solo si pasa una instancia de TextSearchCriteria al método Search
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
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream) {#constructor}

Inicializa una nueva instancia de la clase [`Watermarker`](../../watermarker) con el flujo especificado.

```csharp
public Watermarker(Stream document)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| documento | Stream | El flujo desde el cual cargar el documento. |

### Excepciones

| excepción | condición |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | El tipo de documento proporcionado no es compatible. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | La contraseña proporcionada es incorrecta. |

### Observaciones

Obtenga más información sobre la carga de documentos [Cargando documentos](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### Ejemplos

Cargue y guarde un documento en cualquier formato compatible.

```csharp
// Cargue contenido desde un flujo.
using (FileStream inputStream = File.Open("D:\\input.pdf", FileMode.Open))
using (FileStream outputStream = File.Open("D:\\output.pdf", FileMode.Create))
using (Watermarker watermarker = new Watermarker(inputStream))
{
    // Utiliza los métodos de la clase Watermarker para añadir, buscar o eliminar marcas de agua.

    // Guarda los cambios.
    watermarker.Save(outputStream);
}
```

### Ver también

* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, LoadOptions) {#constructor_1}

Inicializa una nueva instancia de la clase [`Watermarker`](../../watermarker) con el flujo especificado y opciones de carga.

```csharp
public Watermarker(Stream document, LoadOptions options)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| documento | Stream | El flujo desde el cual cargar el documento. |
| opciones | LoadOptions | Opciones adicionales para usar al cargar un documento. |

### Excepciones

| excepción | condición |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | El tipo de documento proporcionado no es compatible. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | La contraseña proporcionada es incorrecta. |

### Observaciones

Obtenga más información sobre la carga de documentos [Cargando documentos](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### Ejemplos

Cargue un documento PDF cifrado usando una contraseña

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
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, WatermarkerSettings) {#constructor_3}

Inicializa una nueva instancia de la clase [`Watermarker`](../../watermarker) con el flujo especificado y configuraciones.

```csharp
public Watermarker(Stream document, WatermarkerSettings settings)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| documento | Stream | El flujo desde el cual cargar el documento. |
| configuración | WatermarkerSettings | Configuraciones adicionales para usar al trabajar con el documento cargado. |

### Excepciones

| excepción | condición |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | El tipo de documento proporcionado no es compatible. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | La contraseña proporcionada es incorrecta. |

### Observaciones

Obtenga más información sobre la carga de documentos [Cargando documentos](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### Ejemplos

Establezca objetos buscables globalmente (para todos los documentos que se cargarán después de eso).

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
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, LoadOptions, WatermarkerSettings) {#constructor_2}

Inicializa una nueva instancia de la clase [`Watermarker`](../../watermarker) con el flujo especificado, opciones de carga y configuraciones.

```csharp
public Watermarker(Stream document, LoadOptions options, WatermarkerSettings settings)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| documento | Stream | El flujo desde el cual cargar el documento. |
| opciones | LoadOptions | Opciones adicionales para usar al cargar un documento. |
| configuración | WatermarkerSettings | Configuraciones adicionales para usar al trabajar con el documento cargado. |

### Excepciones

| excepción | condición |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | El tipo de documento proporcionado no es compatible. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | La contraseña proporcionada es incorrecta. |

### Observaciones

Obtenga más información sobre la carga de documentos [Cargando documentos](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### Ejemplos

Encuentre fragmentos de texto particulares en el cuerpo/asunto del mensaje de correo electrónico.

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
    // Nota, la búsqueda se realiza solo si pasa una instancia de TextSearchCriteria al método Search
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
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.watermark.dll -->
