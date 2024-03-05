---
title: Save
second_title: GroupDocs.Watermark for .NET API Reference
description: Saves the document data to the underlying stream.
type: docs
weight: 100
url: /net/groupdocs.watermark/watermarker/save/
---
## Save() {#save}

Saves the document data to the underlying stream.

```csharp
public WatermarkResult Save()
```

### Remarks

Learn more about saving the documents [Saving documents](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### Examples

Remove particular text fragments from the email message body/subject and save the email message.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\test.msg"))
{
    SearchCriteria criteria = new TextSearchCriteria("test", false);
    // Note, search is performed only if you pass TextSearchCriteria instance to Search method
    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    // Remove found text fragments
    watermarker.Remove(watermarks);
    // Save changes
    watermarker.Save();
}
```

### See Also

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../watermarker)
* assembly [GroupDocs.Watermark](../../../)

---

## Save(string) {#save_4}

Saves the document to the specified file location.

```csharp
public WatermarkResult Save(string filePath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | The file path to save the document data to. |

### Remarks

Learn more about saving the documents [Saving documents](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### Examples

Add the watermark and save the document to another file.

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{                                                                                   
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);                                            
    watermarker.Save("ouput.pdf");                                   
}                                                                                   
```

### See Also

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../watermarker)
* assembly [GroupDocs.Watermark](../../../)

---

## Save(Stream) {#save_2}

Saves the document to the specified stream.

```csharp
public WatermarkResult Save(Stream document)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | Stream | The stream to save the document data to. |

### Remarks

Learn more about saving the documents [Saving documents](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### Examples

Add watermark and save the document to the memory stream.

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

### See Also

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../watermarker)
* assembly [GroupDocs.Watermark](../../../)

---

## Save(SaveOptions) {#save_1}

Saves the document data to the underlying stream using save options.

```csharp
public WatermarkResult Save(SaveOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| options | SaveOptions | Additional options to use when saving a document. |

### Remarks

Learn more about saving the documents [Saving documents](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### Examples

Add watermark and save the document with default [`SaveOptions`](../../../groupdocs.watermark.options/saveoptions).

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);
    watermarker.Save(new SaveOptions());
}
```

### See Also

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../watermarker)
* assembly [GroupDocs.Watermark](../../../)

---

## Save(string, SaveOptions) {#save_5}

Saves the document to the specified file location using save options.

```csharp
public WatermarkResult Save(string filePath, SaveOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | The file path to save the document data to. |
| options | SaveOptions | Additional options to use when saving a document. |

### Remarks

Learn more about saving the documents [Saving documents](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### Examples

Add the watermark and save the document to another file with default [`SaveOptions`](../../../groupdocs.watermark.options/saveoptions).

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{                                                                                   
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);                                            
    watermarker.Save("ouput.pdf", new SaveOptions());
}                                                                                   
```

### See Also

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../watermarker)
* assembly [GroupDocs.Watermark](../../../)

---

## Save(Stream, SaveOptions) {#save_3}

Saves the document to the specified stream using save options.

```csharp
public WatermarkResult Save(Stream document, SaveOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | Stream | The stream to save the document data to. |
| options | SaveOptions | Additional options to use when saving a document. |

### Remarks

Learn more about saving the documents [Saving documents](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### Examples

Add watermark and save the document to the memory stream with default [`SaveOptions`](../../../groupdocs.watermark.options/saveoptions).

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

### See Also

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../watermarker)
* assembly [GroupDocs.Watermark](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.watermark.dll -->
