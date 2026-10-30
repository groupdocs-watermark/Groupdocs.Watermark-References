---
title: "Guardar"
second_title: "GroupDocs.Watermark para la referencia de API de .NET"
description: "Guarda los datos del documento en el flujo subyacente."
type: docs
weight: 100
url: /es/net/groupdocs.watermark/watermarker/save/
---
## Save() {#save}

Guarda los datos del documento en el flujo subyacente.

```csharp
public WatermarkResult Save()
```

### Observaciones

Obtenga más información sobre el guardado de documentos [Guardado de documentos](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### Ejemplos

Elimine fragmentos de texto particulares del cuerpo/asunto del mensaje de correo electrónico y guarde el mensaje de correo.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\test.msg"))
{
    SearchCriteria criteria = new TextSearchCriteria("test", false);
    // Nota, la búsqueda se realiza solo si pasa una instancia de TextSearchCriteria al método Search
    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    // Eliminar fragmentos de texto encontrados
    watermarker.Remove(watermarks);
    // Guardar cambios
    watermarker.Save();
}
```

### Ver también

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Save(string) {#save_4}

Guarda el documento en la ubicación de archivo especificada.

```csharp
public WatermarkResult Save(string filePath)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| filePath | String | La ruta del archivo donde guardar los datos del documento. |

### Observaciones

Obtenga más información sobre el guardado de documentos [Guardado de documentos](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

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

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Save(Stream) {#save_2}

Guarda el documento en el flujo especificado.

```csharp
public WatermarkResult Save(Stream document)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| documento | Stream | El flujo donde guardar los datos del documento. |

### Observaciones

Obtenga más información sobre el guardado de documentos [Guardado de documentos](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### Ejemplos

Agregue la marca de agua y guarde el documento en el flujo de memoria.

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

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Save(SaveOptions) {#save_1}

Guarda los datos del documento en el flujo subyacente usando opciones de guardado.

```csharp
public WatermarkResult Save(SaveOptions options)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| opciones | SaveOptions | Opciones adicionales para usar al guardar un documento. |

### Observaciones

Obtenga más información sobre el guardado de documentos [Guardado de documentos](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### Ejemplos

Agregar marca de agua y guardar el documento con las [`SaveOptions`](../../../groupdocs.watermark.options/saveoptions) predeterminadas.

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);
    watermarker.Save(new SaveOptions());
}
```

### Ver también

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Save(string, SaveOptions) {#save_5}

Guarda el documento en la ubicación de archivo especificada usando opciones de guardado.

```csharp
public WatermarkResult Save(string filePath, SaveOptions options)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| filePath | String | La ruta del archivo donde guardar los datos del documento. |
| opciones | SaveOptions | Opciones adicionales para usar al guardar un documento. |

### Observaciones

Obtenga más información sobre el guardado de documentos [Guardado de documentos](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### Ejemplos

Agregar la marca de agua y guardar el documento en otro archivo con las [`SaveOptions`](../../../groupdocs.watermark.options/saveoptions) predeterminadas.

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{                                                                                   
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);                                            
    watermarker.Save("ouput.pdf", new SaveOptions());
}                                                                                   
```

### Ver también

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Save(Stream, SaveOptions) {#save_3}

Guarda el documento en el flujo especificado usando opciones de guardado.

```csharp
public WatermarkResult Save(Stream document, SaveOptions options)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| documento | Stream | El flujo donde guardar los datos del documento. |
| opciones | SaveOptions | Opciones adicionales para usar al guardar un documento. |

### Observaciones

Obtenga más información sobre el guardado de documentos [Guardado de documentos](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### Ejemplos

Agregar marca de agua y guardar el documento en el flujo de memoria con las [`SaveOptions`](../../../groupdocs.watermark.options/saveoptions) predeterminadas.

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

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.watermark.dll -->
