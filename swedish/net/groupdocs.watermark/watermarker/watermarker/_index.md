---
title: Watermarker
second_title: GroupDocs.Watermark for .NET API-referens
description: Initierar en ny instans avWatermarkergroupdocs.watermark/watermarker klass med den angivna dokumentsökvägen.
type: docs
weight: 10
url: /sv/net/groupdocs.watermark/watermarker/watermarker/
---
## Watermarker(string) {#constructor_4}

Initierar en ny instans av[`Watermarker`](../../watermarker) klass med den angivna dokumentsökvägen.

```csharp
public Watermarker(string filePath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | String | Filsökvägen att ladda dokumentet från. |

### Undantag

| undantag | skick |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Medföljande dokumenttyp stöds inte. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Det angivna lösenordet är felaktigt. |

### Anmärkningar

Läs mer om att ladda dokument: [Laddar dokument](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### Exempel

Ladda och spara ett innehåll i valfritt format som stöds.

```csharp
// Ladda ett innehåll från en fil.
using (Watermarker watermarker = new Watermarker("D:\\input.pdf"))
{
    // Använd metoder i klassen Watermarker för att lägga till, söka eller ta bort vattenstämplar.

    // Spara dokumentet.
    watermarker.Save("D:\\output.pdf");
}
```

### Se även

* class [Watermarker](../../watermarker)
* namnutrymme [GroupDocs.Watermark](../../watermarker)
* hopsättning [GroupDocs.Watermark](../../../)

---

## Watermarker(string, LoadOptions) {#constructor_5}

Initierar en ny instans av[`Watermarker`](../../watermarker)klass med specificerad dokumentsökväg och laddningsalternativ.

```csharp
public Watermarker(string filePath, LoadOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | String | Filsökvägen att ladda dokument från. |
| options | LoadOptions | Ytterligare alternativ att använda när du laddar ett dokument. |

### Undantag

| undantag | skick |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Medföljande dokumenttyp stöds inte. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Det angivna lösenordet är felaktigt. |

### Anmärkningar

Läs mer om att ladda dokument: [Laddar dokument](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### Exempel

Ladda krypterade PDF-dokument med lösenord.

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
* namnutrymme [GroupDocs.Watermark](../../watermarker)
* hopsättning [GroupDocs.Watermark](../../../)

---

## Watermarker(string, WatermarkerSettings) {#constructor_7}

Initierar en ny instans av[`Watermarker`](../../watermarker) klass med specificerad dokumentsökväg och inställningar.

```csharp
public Watermarker(string filePath, WatermarkerSettings settings)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | String | Filsökvägen att ladda dokument från. |
| settings | WatermarkerSettings | Ytterligare inställningar att använda när du arbetar med laddade dokument. |

### Undantag

| undantag | skick |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Medföljande dokumenttyp stöds inte. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Det angivna lösenordet är felaktigt. |

### Anmärkningar

Läs mer om att ladda dokument: [Laddar dokument](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### Exempel

Ställ in sökbara objekt globalt (för alla dokument som kommer att laddas efter det).

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

        // Koden för att arbeta med hittade vattenstämplar går här.
    }
}
```

### Se även

* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* namnutrymme [GroupDocs.Watermark](../../watermarker)
* hopsättning [GroupDocs.Watermark](../../../)

---

## Watermarker(string, LoadOptions, WatermarkerSettings) {#constructor_6}

Initierar en ny instans av[`Watermarker`](../../watermarker) klass med specificerad dokumentsökväg, laddningsalternativ och inställningar.

```csharp
public Watermarker(string filePath, LoadOptions options, WatermarkerSettings settings)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | String | Filsökvägen att ladda dokument från. |
| options | LoadOptions | Ytterligare alternativ att använda när du laddar ett dokument. |
| settings | WatermarkerSettings | Ytterligare inställningar att använda när du arbetar med laddade dokument. |

### Undantag

| undantag | skick |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Medföljande dokumenttyp stöds inte. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Det angivna lösenordet är felaktigt. |

### Anmärkningar

Läs mer om att ladda dokument: [Laddar dokument](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### Exempel

Hitta särskilda textfragment i e-postmeddelandets brödtext/ämne.

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
    // Obs, sökning utförs endast om du skickar TextSearchCriteria-instansen till sökmetoden
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
* namnutrymme [GroupDocs.Watermark](../../watermarker)
* hopsättning [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream) {#constructor}

Initierar en ny instans av[`Watermarker`](../../watermarker) klass med den angivna strömmen.

```csharp
public Watermarker(Stream document)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | Stream | Streamen att ladda dokument från. |

### Undantag

| undantag | skick |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Medföljande dokumenttyp stöds inte. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Det angivna lösenordet är felaktigt. |

### Anmärkningar

Läs mer om att ladda dokument [Laddar dokument](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### Exempel

Ladda och spara ett dokument i valfritt format som stöds.

```csharp
// Ladda ett innehåll från en stream.
using (FileStream inputStream = File.Open("D:\\input.pdf", FileMode.Open))
using (FileStream outputStream = File.Open("D:\\output.pdf", FileMode.Create))
using (Watermarker watermarker = new Watermarker(inputStream))
{
    // Använd metoder i klassen Watermarker för att lägga till, söka eller ta bort vattenstämplar.

    // Spara ändringar.
    watermarker.Save(outputStream);
}
```

### Se även

* class [Watermarker](../../watermarker)
* namnutrymme [GroupDocs.Watermark](../../watermarker)
* hopsättning [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, LoadOptions) {#constructor_1}

Initierar en ny instans av[`Watermarker`](../../watermarker) klass med de angivna stream och laddningsalternativ.

```csharp
public Watermarker(Stream document, LoadOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | Stream | Streamen att ladda dokument från. |
| options | LoadOptions | Ytterligare alternativ att använda när du laddar ett dokument. |

### Undantag

| undantag | skick |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Medföljande dokumenttyp stöds inte. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Det angivna lösenordet är felaktigt. |

### Anmärkningar

Läs mer om att ladda dokument [Laddar dokument](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### Exempel

Ladda krypterade PDF-dokument med lösenord

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
* namnutrymme [GroupDocs.Watermark](../../watermarker)
* hopsättning [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, WatermarkerSettings) {#constructor_3}

Initierar en ny instans av[`Watermarker`](../../watermarker) klass med den angivna stream och inställningar.

```csharp
public Watermarker(Stream document, WatermarkerSettings settings)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | Stream | Streamen att ladda dokument från. |
| settings | WatermarkerSettings | Ytterligare inställningar att använda när du arbetar med laddade dokument. |

### Undantag

| undantag | skick |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Medföljande dokumenttyp stöds inte. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Det angivna lösenordet är felaktigt. |

### Anmärkningar

Läs mer om att ladda dokument [Laddar dokument](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### Exempel

Ställ in sökbara objekt globalt (för alla dokument som kommer att laddas efter det).

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

        // Koden för att arbeta med hittade vattenstämplar går här.
    }
}
```

### Se även

* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* namnutrymme [GroupDocs.Watermark](../../watermarker)
* hopsättning [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, LoadOptions, WatermarkerSettings) {#constructor_2}

Initierar en ny instans av[`Watermarker`](../../watermarker) klass med den angivna strömmen, laddningsalternativ och inställningar.

```csharp
public Watermarker(Stream document, LoadOptions options, WatermarkerSettings settings)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | Stream | Streamen att ladda dokument från. |
| options | LoadOptions | Ytterligare alternativ att använda när du laddar ett dokument. |
| settings | WatermarkerSettings | Ytterligare inställningar att använda när du arbetar med laddade dokument. |

### Undantag

| undantag | skick |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Medföljande dokumenttyp stöds inte. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Det angivna lösenordet är felaktigt. |

### Anmärkningar

Läs mer om att ladda dokument [Laddar dokument](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### Exempel

Hitta särskilda textfragment i e-postmeddelandets brödtext/ämne.

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
    // Obs, sökning utförs endast om du skickar TextSearchCriteria-instansen till sökmetoden
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
* namnutrymme [GroupDocs.Watermark](../../watermarker)
* hopsättning [GroupDocs.Watermark](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
