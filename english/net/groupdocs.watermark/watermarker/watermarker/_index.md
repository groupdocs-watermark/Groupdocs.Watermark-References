---
title: Watermarker
second_title: GroupDocs.Watermark for .NET API Reference
description: Initializes a new instance of the Watermarkergroupdocs.watermark/watermarker class with the specified document path.
type: docs
weight: 10
url: /net/groupdocs.watermark/watermarker/watermarker/
---
## Watermarker(string) {#constructor_4}

Initializes a new instance of the [`Watermarker`](../../watermarker) class with the specified document path.

```csharp
public Watermarker(string filePath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | The file path to load the document from. |

### Exceptions

| exception | condition |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Supplied document type is not supported. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Supplied password is incorrect. |

### Remarks

Learn more about loading documents: [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### Examples

Load and save a content of any supported format.

```csharp
// Load a content from a file.
using (Watermarker watermarker = new Watermarker("D:\\input.pdf"))
{
    // Use methods of Watermarker class to add, search or remove watermarks.

    // Save the document.
    watermarker.Save("D:\\output.pdf");
}
```

### See Also

* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../watermarker)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(string, LoadOptions) {#constructor_5}

Initializes a new instance of the [`Watermarker`](../../watermarker) class with the specified document path and load options.

```csharp
public Watermarker(string filePath, LoadOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | The file path to load document from. |
| options | LoadOptions | Additional options to use when loading a document. |

### Exceptions

| exception | condition |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Supplied document type is not supported. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Supplied password is incorrect. |

### Remarks

Learn more about loading documents: [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### Examples

Load encrypted PDF document using password.

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
loadOptions.Password = "123";
using (Watermarker watermarker = new Watermarker(@"C:\Documents\test.pdf", loadOptions))
{
    // ...
}
```

### See Also

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../watermarker)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(string, WatermarkerSettings) {#constructor_7}

Initializes a new instance of the [`Watermarker`](../../watermarker) class with the specified document path and settings.

```csharp
public Watermarker(string filePath, WatermarkerSettings settings)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | The file path to load document from. |
| settings | WatermarkerSettings | Additional settings to use when working with loaded document. |

### Exceptions

| exception | condition |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Supplied document type is not supported. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Supplied password is incorrect. |

### Remarks

Learn more about loading documents: [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### Examples

Set searchable objects globally (for all documents that will be loaded after that).

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

        // The code for working with found watermarks goes here.
    }
}
```

### See Also

* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../watermarker)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(string, LoadOptions, WatermarkerSettings) {#constructor_6}

Initializes a new instance of the [`Watermarker`](../../watermarker) class with the specified document path, load options and settings.

```csharp
public Watermarker(string filePath, LoadOptions options, WatermarkerSettings settings)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | The file path to load document from. |
| options | LoadOptions | Additional options to use when loading a document. |
| settings | WatermarkerSettings | Additional settings to use when working with loaded document. |

### Exceptions

| exception | condition |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Supplied document type is not supported. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Supplied password is incorrect. |

### Remarks

Learn more about loading documents: [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### Examples

Find particular text fragments in email message body/subject.

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
    // Note, search is performed only if you pass TextSearchCriteria instance to Search method
    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    // Remove found text fragments
    watermarks.Clear();
    // Save changes
    watermarker.Save();
}
```

### See Also

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../watermarker)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream) {#constructor}

Initializes a new instance of the [`Watermarker`](../../watermarker) class with the specified stream.

```csharp
public Watermarker(Stream document)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | Stream | The stream to load document from. |

### Exceptions

| exception | condition |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Supplied document type is not supported. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Supplied password is incorrect. |

### Remarks

Learn more about loading documents [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### Examples

Load and save a document of any supported format.

```csharp
// Load a content from a stream.
using (FileStream inputStream = File.Open("D:\\input.pdf", FileMode.Open))
using (FileStream outputStream = File.Open("D:\\output.pdf", FileMode.Create))
using (Watermarker watermarker = new Watermarker(inputStream))
{
    // Use methods of Watermarker class to add, search or remove watermarks.

    // Save changes.
    watermarker.Save(outputStream);
}
```

### See Also

* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../watermarker)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, LoadOptions) {#constructor_1}

Initializes a new instance of the [`Watermarker`](../../watermarker) class with the specified stream and load options.

```csharp
public Watermarker(Stream document, LoadOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | Stream | The stream to load document from. |
| options | LoadOptions | Additional options to use when loading a document. |

### Exceptions

| exception | condition |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Supplied document type is not supported. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Supplied password is incorrect. |

### Remarks

Learn more about loading documents [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### Examples

Load encrypted PDF document using password

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
loadOptions.Password = "123";
using (FileStream fileStream = File.Open(@"C:\Documents\test.pdf", FileMode.Open))
using (Watermarker watermarker = new Watermarker(fileStream, loadOptions))
{
    // ...
}
```

### See Also

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../watermarker)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, WatermarkerSettings) {#constructor_3}

Initializes a new instance of the [`Watermarker`](../../watermarker) class with the specified stream and settings.

```csharp
public Watermarker(Stream document, WatermarkerSettings settings)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | Stream | The stream to load document from. |
| settings | WatermarkerSettings | Additional settings to use when working with loaded document. |

### Exceptions

| exception | condition |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Supplied document type is not supported. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Supplied password is incorrect. |

### Remarks

Learn more about loading documents [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### Examples

Set searchable objects globally (for all documents that will be loaded after that).

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

        // The code for working with found watermarks goes here.
    }
}
```

### See Also

* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../watermarker)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, LoadOptions, WatermarkerSettings) {#constructor_2}

Initializes a new instance of the [`Watermarker`](../../watermarker) class with the specified stream, load options and settings.

```csharp
public Watermarker(Stream document, LoadOptions options, WatermarkerSettings settings)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document | Stream | The stream to load document from. |
| options | LoadOptions | Additional options to use when loading a document. |
| settings | WatermarkerSettings | Additional settings to use when working with loaded document. |

### Exceptions

| exception | condition |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Supplied document type is not supported. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Supplied password is incorrect. |

### Remarks

Learn more about loading documents [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### Examples

Find particular text fragments in email message body/subject.

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
    // Note, search is performed only if you pass TextSearchCriteria instance to Search method
    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    // Remove found text fragments
    watermarks.Clear();
    // Save changes
    watermarker.Save();
}
```

### See Also

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../watermarker)
* assembly [GroupDocs.Watermark](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.watermark.dll -->
