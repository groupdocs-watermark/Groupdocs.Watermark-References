---
title: "Watermarker"
second_title: "GroupDocs.Watermark för .NET API-referens"
description: "Initierar en ny instans av Watermarkergroupdocs.watermark/watermarker-klassen med den angivna dokumentsökvägen."
type: docs
weight: 10
url: /sv/net/groupdocs.watermark/watermarker/watermarker/
---
## Watermarker(string) {#constructor_4}

Initierar en ny instans av [`Watermarker`](../../watermarker)-klassen med den angivna dokumentsökvägen.

```csharp
public Watermarker(string filePath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | Sträng | Filsökvägen att ladda dokumentet från. |

### Undantag

| undantag | villkor |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Den angivna dokumenttypen stöds inte. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Det angivna lösenordet är felaktigt. |

### Anmärkningar

Läs mer om att ladda dokument: [Ladda dokument](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### Exempel

Läs in och spara innehåll i vilket som helst stödd format.

```csharp
// Läs in ett innehåll från en fil.
using (Watermarker watermarker = new Watermarker("D:\\input.pdf"))
{
    // Använd metoder i Watermarker-klassen för att lägga till, söka eller ta bort vattenmärken.

    // Spara dokumentet.
    watermarker.Save("D:\\output.pdf");
}
```

### Se även

* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(string, LoadOptions) {#constructor_5}

Initierar en ny instans av klassen [`Watermarker`](../../watermarker) med den angivna dokumentvägen och inläsningsalternativen.

```csharp
public Watermarker(string filePath, LoadOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | Sträng | Filvägen för att läsa in dokumentet från. |
| alternativ | LoadOptions | Ytterligare alternativ att använda när ett dokument läses in. |

### Undantag

| undantag | villkor |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Den angivna dokumenttypen stöds inte. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Det angivna lösenordet är felaktigt. |

### Anmärkningar

Läs mer om att ladda dokument: [Ladda dokument](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### Exempel

Läs in ett krypterat PDF-dokument med lösenord.

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
loadOptions.Password = "123";
using (Watermarker watermarker = new Watermarker(@"C:\Documents\test.pdf", loadOptions))
{
    // ...
}
```

### Se även

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(string, WatermarkerSettings) {#constructor_7}

Initierar en ny instans av klassen [`Watermarker`](../../watermarker) med den angivna dokumentvägen och inställningarna.

```csharp
public Watermarker(string filePath, WatermarkerSettings settings)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | Sträng | Filvägen för att läsa in dokumentet från. |
| inställningar | WatermarkerSettings | Ytterligare inställningar att använda när du arbetar med ett inläst dokument. |

### Undantag

| undantag | villkor |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Den angivna dokumenttypen stöds inte. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Det angivna lösenordet är felaktigt. |

### Anmärkningar

Läs mer om att ladda dokument: [Ladda dokument](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### Exempel

Ställ in sökbara objekt globalt (för alla dokument som laddas efter detta).

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

        // Koden för att arbeta med hittade vattenmärken placeras här.
    }
}
```

### Se även

* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(string, LoadOptions, WatermarkerSettings) {#constructor_6}

Initierar en ny instans av klassen [`Watermarker`](../../watermarker) med den angivna dokumentvägen, inläsningsalternativen och inställningarna.

```csharp
public Watermarker(string filePath, LoadOptions options, WatermarkerSettings settings)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | Sträng | Filvägen för att läsa in dokumentet från. |
| alternativ | LoadOptions | Ytterligare alternativ att använda när ett dokument läses in. |
| inställningar | WatermarkerSettings | Ytterligare inställningar att använda när du arbetar med ett inläst dokument. |

### Undantag

| undantag | villkor |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Den angivna dokumenttypen stöds inte. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Det angivna lösenordet är felaktigt. |

### Anmärkningar

Läs mer om att ladda dokument: [Ladda dokument](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### Exempel

Hitta specifika textfragment i e‑postmeddelandets brödtext/ämne.

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
    // Observera, sökningen utförs endast om du skickar en TextSearchCriteria‑instans till Search‑metoden.
    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    // Ta bort hittade textfragment
    watermarks.Clear();
    // Spara ändringar
    watermarker.Save();
}
```

### Se även

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream) {#constructor}

Initierar en ny instans av klassen [`Watermarker`](../../watermarker) med den angivna strömmen.

```csharp
public Watermarker(Stream document)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dokument | Stream | Strömmen att läsa in dokumentet från. |

### Undantag

| undantag | villkor |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Den angivna dokumenttypen stöds inte. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Det angivna lösenordet är felaktigt. |

### Anmärkningar

Läs mer om att läsa in dokument [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### Exempel

Läs in och spara ett dokument i vilket som helst stödformat.

```csharp
// Läs in innehåll från en ström.
using (FileStream inputStream = File.Open("D:\\input.pdf", FileMode.Open))
using (FileStream outputStream = File.Open("D:\\output.pdf", FileMode.Create))
using (Watermarker watermarker = new Watermarker(inputStream))
{
    // Använd metoder i Watermarker-klassen för att lägga till, söka eller ta bort vattenmärken.

    // Spara ändringar.
    watermarker.Save(outputStream);
}
```

### Se även

* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, LoadOptions) {#constructor_1}

Initierar en ny instans av klassen [`Watermarker`](../../watermarker) med den angivna strömmen och inläsningsalternativen.

```csharp
public Watermarker(Stream document, LoadOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dokument | Stream | Strömmen att läsa in dokumentet från. |
| alternativ | LoadOptions | Ytterligare alternativ att använda när ett dokument läses in. |

### Undantag

| undantag | villkor |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Den angivna dokumenttypen stöds inte. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Det angivna lösenordet är felaktigt. |

### Anmärkningar

Läs mer om att läsa in dokument [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### Exempel

Läs in ett krypterat PDF-dokument med lösenord

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
loadOptions.Password = "123";
using (FileStream fileStream = File.Open(@"C:\Documents\test.pdf", FileMode.Open))
using (Watermarker watermarker = new Watermarker(fileStream, loadOptions))
{
    // ...
}
```

### Se även

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, WatermarkerSettings) {#constructor_3}

Initierar en ny instans av klassen [`Watermarker`](../../watermarker) med den angivna strömmen och inställningarna.

```csharp
public Watermarker(Stream document, WatermarkerSettings settings)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dokument | Stream | Strömmen att läsa in dokumentet från. |
| inställningar | WatermarkerSettings | Ytterligare inställningar att använda när du arbetar med ett inläst dokument. |

### Undantag

| undantag | villkor |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Den angivna dokumenttypen stöds inte. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Det angivna lösenordet är felaktigt. |

### Anmärkningar

Läs mer om att läsa in dokument [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### Exempel

Ställ in sökbara objekt globalt (för alla dokument som laddas efter detta).

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

        // Koden för att arbeta med hittade vattenmärken placeras här.
    }
}
```

### Se även

* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, LoadOptions, WatermarkerSettings) {#constructor_2}

Initierar en ny instans av klassen [`Watermarker`](../../watermarker) med den angivna strömmen, inläsningsalternativen och inställningarna.

```csharp
public Watermarker(Stream document, LoadOptions options, WatermarkerSettings settings)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dokument | Stream | Strömmen att läsa in dokumentet från. |
| alternativ | LoadOptions | Ytterligare alternativ att använda när ett dokument läses in. |
| inställningar | WatermarkerSettings | Ytterligare inställningar att använda när du arbetar med ett inläst dokument. |

### Undantag

| undantag | villkor |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Den angivna dokumenttypen stöds inte. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Det angivna lösenordet är felaktigt. |

### Anmärkningar

Läs mer om att läsa in dokument [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### Exempel

Hitta specifika textfragment i e‑postmeddelandets brödtext/ämne.

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
    // Observera, sökningen utförs endast om du skickar en TextSearchCriteria‑instans till Search‑metoden.
    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    // Ta bort hittade textfragment
    watermarks.Clear();
    // Spara ändringar
    watermarker.Save();
}
```

### Se även

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- FÅR INTE REDIGERAS: genererad av xmldocmd för GroupDocs.watermark.dll -->
