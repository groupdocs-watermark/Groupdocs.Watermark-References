---
title: "Watermarker"
second_title: "GroupDocs.Watermark voor .NET API-referentie"
description: "Initialiseert een nieuw exemplaar van de Watermarkergroupdocs.watermark/watermarker-klasse met het opgegeven documentpad."
type: docs
weight: 10
url: /nl/net/groupdocs.watermark/watermarker/watermarker/
---
## Watermarker(string) {#constructor_4}

Initialiseert een nieuw exemplaar van de [`Watermarker`](../../watermarker)-klasse met het opgegeven documentpad.

```csharp
public Watermarker(string filePath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | String | Het bestandspad om het document van te laden. |

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Het opgegeven documenttype wordt niet ondersteund. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Het opgegeven wachtwoord is onjuist. |

### Opmerkingen

Meer informatie over het laden van documenten: [Documenten laden](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### Voorbeelden

Laad en sla inhoud op in elk ondersteund formaat.

```csharp
// Laad inhoud vanuit een bestand.
using (Watermarker watermarker = new Watermarker("D:\\input.pdf"))
{
    // Gebruik methoden van de Watermarker-klasse om watermerken toe te voegen, te zoeken of te verwijderen.

    // Sla het document op.
    watermarker.Save("D:\\output.pdf");
}
```

### Zie ook

* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(string, LoadOptions) {#constructor_5}

Initialiseert een nieuw exemplaar van de [`Watermarker`](../../watermarker)-klasse met het opgegeven documentpad en laadopties.

```csharp
public Watermarker(string filePath, LoadOptions options)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | String | Het bestandspad om het document van te laden. |
| opties | LoadOptions | Aanvullende opties om te gebruiken bij het laden van een document. |

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Het opgegeven documenttype wordt niet ondersteund. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Het opgegeven wachtwoord is onjuist. |

### Opmerkingen

Meer informatie over het laden van documenten: [Documenten laden](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### Voorbeelden

Laad een versleuteld PDF-document met wachtwoord.

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
loadOptions.Password = "123";
using (Watermarker watermarker = new Watermarker(@"C:\Documents\test.pdf", loadOptions))
{
    // ...
}
```

### Zie ook

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(string, WatermarkerSettings) {#constructor_7}

Initialiseert een nieuw exemplaar van de [`Watermarker`](../../watermarker)-klasse met het opgegeven documentpad en instellingen.

```csharp
public Watermarker(string filePath, WatermarkerSettings settings)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | String | Het bestandspad om het document van te laden. |
| instellingen | WatermarkerSettings | Aanvullende instellingen om te gebruiken bij het werken met een geladen document. |

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Het opgegeven documenttype wordt niet ondersteund. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Het opgegeven wachtwoord is onjuist. |

### Opmerkingen

Meer informatie over het laden van documenten: [Documenten laden](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### Voorbeelden

Stel doorzoekbare objecten globaal in (voor alle documenten die daarna worden geladen).

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

        // De code voor het werken met gevonden watermerken komt hier.
    }
}
```

### Zie ook

* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(string, LoadOptions, WatermarkerSettings) {#constructor_6}

Initialiseert een nieuw exemplaar van de [`Watermarker`](../../watermarker)-klasse met het opgegeven documentpad, laadopties en instellingen.

```csharp
public Watermarker(string filePath, LoadOptions options, WatermarkerSettings settings)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | String | Het bestandspad om het document van te laden. |
| opties | LoadOptions | Aanvullende opties om te gebruiken bij het laden van een document. |
| instellingen | WatermarkerSettings | Aanvullende instellingen om te gebruiken bij het werken met een geladen document. |

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Het opgegeven documenttype wordt niet ondersteund. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Het opgegeven wachtwoord is onjuist. |

### Opmerkingen

Meer informatie over het laden van documenten: [Documenten laden](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### Voorbeelden

Zoek specifieke tekstfragmenten in de hoofdtekst/onderwerp van een e-mailbericht.

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
    // Opmerking, zoeken wordt alleen uitgevoerd als u een TextSearchCriteria‑instantie doorgeeft aan de Search‑methode
    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    // Verwijder gevonden tekstfragmenten
    watermarks.Clear();
    // Wijzigingen opslaan
    watermarker.Save();
}
```

### Zie ook

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream) {#constructor}

Initialiseert een nieuw exemplaar van de [`Watermarker`](../../watermarker)‑klasse met de opgegeven stream.

```csharp
public Watermarker(Stream document)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| document | Stream | De stream om het document uit te laden. |

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Het opgegeven documenttype wordt niet ondersteund. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Het opgegeven wachtwoord is onjuist. |

### Opmerkingen

Meer informatie over het laden van documenten [Documenten laden](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### Voorbeelden

Laad en sla een document op in elk ondersteund formaat.

```csharp
// Laad inhoud van een stream.
using (FileStream inputStream = File.Open("D:\\input.pdf", FileMode.Open))
using (FileStream outputStream = File.Open("D:\\output.pdf", FileMode.Create))
using (Watermarker watermarker = new Watermarker(inputStream))
{
    // Gebruik methoden van de Watermarker-klasse om watermerken toe te voegen, te zoeken of te verwijderen.

    // Sla wijzigingen op.
    watermarker.Save(outputStream);
}
```

### Zie ook

* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, LoadOptions) {#constructor_1}

Initialiseert een nieuw exemplaar van de [`Watermarker`](../../watermarker)‑klasse met de opgegeven stream en laadopties.

```csharp
public Watermarker(Stream document, LoadOptions options)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| document | Stream | De stream om het document uit te laden. |
| opties | LoadOptions | Aanvullende opties om te gebruiken bij het laden van een document. |

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Het opgegeven documenttype wordt niet ondersteund. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Het opgegeven wachtwoord is onjuist. |

### Opmerkingen

Meer informatie over het laden van documenten [Documenten laden](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### Voorbeelden

Laad versleuteld PDF‑document met wachtwoord

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
loadOptions.Password = "123";
using (FileStream fileStream = File.Open(@"C:\Documents\test.pdf", FileMode.Open))
using (Watermarker watermarker = new Watermarker(fileStream, loadOptions))
{
    // ...
}
```

### Zie ook

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, WatermarkerSettings) {#constructor_3}

Initialiseert een nieuw exemplaar van de [`Watermarker`](../../watermarker)‑klasse met de opgegeven stream en instellingen.

```csharp
public Watermarker(Stream document, WatermarkerSettings settings)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| document | Stream | De stream om het document uit te laden. |
| instellingen | WatermarkerSettings | Aanvullende instellingen om te gebruiken bij het werken met een geladen document. |

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Het opgegeven documenttype wordt niet ondersteund. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Het opgegeven wachtwoord is onjuist. |

### Opmerkingen

Meer informatie over het laden van documenten [Documenten laden](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### Voorbeelden

Stel doorzoekbare objecten globaal in (voor alle documenten die daarna worden geladen).

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

        // De code voor het werken met gevonden watermerken komt hier.
    }
}
```

### Zie ook

* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, LoadOptions, WatermarkerSettings) {#constructor_2}

Initialiseert een nieuw exemplaar van de [`Watermarker`](../../watermarker)‑klasse met de opgegeven stream, laadopties en instellingen.

```csharp
public Watermarker(Stream document, LoadOptions options, WatermarkerSettings settings)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| document | Stream | De stream om het document uit te laden. |
| opties | LoadOptions | Aanvullende opties om te gebruiken bij het laden van een document. |
| instellingen | WatermarkerSettings | Aanvullende instellingen om te gebruiken bij het werken met een geladen document. |

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Het opgegeven documenttype wordt niet ondersteund. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Het opgegeven wachtwoord is onjuist. |

### Opmerkingen

Meer informatie over het laden van documenten [Documenten laden](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### Voorbeelden

Zoek specifieke tekstfragmenten in de hoofdtekst/onderwerp van een e-mailbericht.

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
    // Opmerking, zoeken wordt alleen uitgevoerd als u een TextSearchCriteria‑instantie doorgeeft aan de Search‑methode
    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    // Verwijder gevonden tekstfragmenten
    watermarks.Clear();
    // Wijzigingen opslaan
    watermarker.Save();
}
```

### Zie ook

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.watermark.dll -->
