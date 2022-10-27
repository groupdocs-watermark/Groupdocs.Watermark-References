---
title: Save
second_title: Referencia de API de GroupDocs.Watermark para .NET
description: Guarda los datos del documento en el flujo subyacente.
type: docs
weight: 100
url: /es/net/groupdocs.watermark/watermarker/save/
---
## Save() {#save}

Guarda los datos del documento en el flujo subyacente.

```csharp
public void Save()
```

### Observaciones

Obtenga más información sobre cómo guardar los documentos [Guardar documentos](https://docs.groupdocs.com/display/watermarknet/Saving+documents) .

### Ejemplos

Eliminar fragmentos de texto particulares del cuerpo/asunto del mensaje de correo electrónico y guardar el mensaje de correo electrónico.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\test.msg"))
{
    SearchCriteria criteria = new TextSearchCriteria("test", false);
    // Tenga en cuenta que la búsqueda se realiza solo si pasa la instancia de TextSearchCriteria al método de búsqueda
    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    // Eliminar fragmentos de texto encontrados
    watermarker.Remove(watermarks);
    // Guardar cambios
    watermarker.Save();
}
```

### Ver también

* class [Watermarker](../../watermarker)
* espacio de nombres [GroupDocs.Watermark](../../watermarker)
* asamblea [GroupDocs.Watermark](../../../)

---

## Save(string) {#save_4}

Guarda el documento en la ubicación de archivo especificada.

```csharp
public void Save(string filePath)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| filePath | String | La ruta del archivo para guardar los datos del documento. |

### Observaciones

Obtenga más información sobre cómo guardar los documentos [Guardar documentos](https://docs.groupdocs.com/display/watermarknet/Saving+documents) .

### Ejemplos

Agregue la marca de agua y guarde el documento en otro archivo.

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{                                                                                   
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);                                            
    watermarker.Save("ouput.pdf");                                   
}                                                                                   
```

### Ver también

* class [Watermarker](../../watermarker)
* espacio de nombres [GroupDocs.Watermark](../../watermarker)
* asamblea [GroupDocs.Watermark](../../../)

---

## Save(Stream) {#save_2}

Guarda el documento en el flujo especificado.

```csharp
public void Save(Stream document)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| document | Stream | La secuencia en la que guardar los datos del documento. |

### Observaciones

Obtenga más información sobre cómo guardar los documentos [Guardar documentos](https://docs.groupdocs.com/display/watermarknet/Saving+documents) .

### Ejemplos

Agregue una marca de agua y guarde el documento en el flujo de memoria.

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);
    using (MemoryStream stream = new MemoryStream())
    {
        watermarker.Save(stream);
        // ...
    }
}
```

### Ver también

* class [Watermarker](../../watermarker)
* espacio de nombres [GroupDocs.Watermark](../../watermarker)
* asamblea [GroupDocs.Watermark](../../../)

---

## Save(SaveOptions) {#save_1}

Guarda los datos del documento en la secuencia subyacente usando las opciones de guardado.

```csharp
public void Save(SaveOptions options)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| options | SaveOptions | Opciones adicionales para usar al guardar un documento. |

### Observaciones

Obtenga más información sobre cómo guardar los documentos [Guardar documentos](https://docs.groupdocs.com/display/watermarknet/Saving+documents) .

### Ejemplos

Agregar marca de agua y guardar el documento con el valor predeterminado[`SaveOptions`](../../../groupdocs.watermark.options/saveoptions) .

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);
    watermarker.Save(new SaveOptions());
}
```

### Ver también

* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* espacio de nombres [GroupDocs.Watermark](../../watermarker)
* asamblea [GroupDocs.Watermark](../../../)

---

## Save(string, SaveOptions) {#save_5}

Guarda el documento en la ubicación de archivo especificada utilizando las opciones de guardado.

```csharp
public void Save(string filePath, SaveOptions options)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| filePath | String | La ruta del archivo para guardar los datos del documento. |
| options | SaveOptions | Opciones adicionales para usar al guardar un documento. |

### Observaciones

Obtenga más información sobre cómo guardar los documentos [Guardar documentos](https://docs.groupdocs.com/display/watermarknet/Saving+documents) .

### Ejemplos

Agregue la marca de agua y guarde el documento en otro archivo con el valor predeterminado[`SaveOptions`](../../../groupdocs.watermark.options/saveoptions) .

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{                                                                                   
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);                                            
    watermarker.Save("ouput.pdf", new SaveOptions());
}                                                                                   
```

### Ver también

* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* espacio de nombres [GroupDocs.Watermark](../../watermarker)
* asamblea [GroupDocs.Watermark](../../../)

---

## Save(Stream, SaveOptions) {#save_3}

Guarda el documento en la secuencia especificada utilizando las opciones de guardado.

```csharp
public void Save(Stream document, SaveOptions options)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| document | Stream | La secuencia en la que guardar los datos del documento. |
| options | SaveOptions | Opciones adicionales para usar al guardar un documento. |

### Observaciones

Obtenga más información sobre cómo guardar los documentos [Guardar documentos](https://docs.groupdocs.com/display/watermarknet/Saving+documents) .

### Ejemplos

Agregar marca de agua y guardar el documento en el flujo de memoria con el valor predeterminado[`SaveOptions`](../../../groupdocs.watermark.options/saveoptions) .

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);
    using (MemoryStream stream = new MemoryStream())
    {
        watermarker.Save(stream, new SaveOptions());
        // ...
    }
}
```

### Ver también

* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* espacio de nombres [GroupDocs.Watermark](../../watermarker)
* asamblea [GroupDocs.Watermark](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
