---
title: "WordProcessingWatermarkPagesOptions"
second_title: "GroupDocs.Watermark för .NET API-referens"
description: "Representerar alternativ när vattenstämpel läggs till på Word-dokumentets sidor."
type: docs
weight: 2410
url: /sv/net/groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkpagesoptions/
---
## WordProcessingWatermarkPagesOptions class

Representerar alternativ när vattenstämpel läggs till på Word-dokumentets sidor.

```csharp
public sealed class WordProcessingWatermarkPagesOptions : WordProcessingWatermarkBaseOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [WordProcessingWatermarkPagesOptions](wordprocessingwatermarkpagesoptions)() | Initierar en ny instans av klassen [`WordProcessingWatermarkPagesOptions`](../wordprocessingwatermarkpagesoptions). |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AlternativeText](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/alternativetext) { get; set; } | Hämtar eller anger den beskrivande (alternativa) texten som kommer att associeras med en form. |
| [Effects](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/effects) { get; set; } | Hämtar eller anger ett värde av [`WordProcessingImageEffects`](../wordprocessingimageeffects) eller [`WordProcessingTextEffects`](../wordprocessingtexteffects) för effekter som ska tillämpas på vattenstämpeln. |
| [IsLocked](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/islocked) { get; set; } | Hämtar eller anger ett värde som indikerar om redigering av formen i Word är förbjuden. |
| [LockType](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/locktype) { get; set; } | Hämtar eller anger vattenstämpelns låstyp. |
| [Name](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/name) { get; set; } | Hämtar eller anger namnet på en form. |
| [PageNumbers](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkpagesoptions/pagenumbers) { get; set; } | Hämtar eller anger sidnumren för att lägga till vattenstämpeln. |
| [Password](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/password) { get; set; } | Hämtar eller anger ett lösenord som används för att låsa vattenstämpeln. |

### Anmärkningar

**Learn more:**

* [Add watermarks to word processing documents](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+word+processing+documents)

### Exempel

Lägg till vattenstämpel på en specifik sida i ett Word-dokument.

```csharp
WordProcessingLoadOptions loadOptions = new WordProcessingLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\test.doc", loadOptions))
{
    TextWatermark watermark = new TextWatermark("text", new Font("Arial", 42));

    WordProcessingWatermarkPagesOptions options = new WordProcessingWatermarkPagesOptions();
    options.PageNumbers = new[] { 1 };

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### Se även

* class [WordProcessingWatermarkBaseOptions](../wordprocessingwatermarkbaseoptions)
* namespace [GroupDocs.Watermark.Options.WordProcessing](../../groupdocs.watermark.options.wordprocessing)
* assembly [GroupDocs.Watermark](../../)

<!-- FÅR INTE REDIGERAS: genererad av xmldocmd för GroupDocs.watermark.dll -->
