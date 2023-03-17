---
title: Watermarker
second_title: GroupDocs.Watermark voor .NET API-referentie
description: Initialiseert een nieuw exemplaar van hetWatermarkergroupdocs.watermark/watermarker klasse met het opgegeven documentpad.
type: docs
weight: 10
url: /nl/net/groupdocs.watermark/watermarker/watermarker/
---
## Watermarker(string) {#constructor_4}

Initialiseert een nieuw exemplaar van het[`Watermarker`](../../watermarker) klasse met het opgegeven documentpad.

```csharp
public Watermarker(string filePath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | String | Het bestandspad waaruit het document moet worden geladen. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Geleverd documenttype wordt niet ondersteund. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Het opgegeven wachtwoord is onjuist. |

### Opmerkingen

Meer informatie over het laden van documenten: [Documenten laden](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### Voorbeelden

Laad en bewaar inhoud van elk ondersteund formaat.

```csharp
// Laad een inhoud uit een bestand.
using (Watermarker watermarker = new Watermarker("D:\\input.pdf"))
{
    // Gebruik methoden van de klasse Watermarker om watermerken toe te voegen, te zoeken of te verwijderen.

    // Sla het document op.
    watermarker.Save("D:\\output.pdf");
}
```

### Zie ook

* class [Watermarker](../../watermarker)
* naamruimte [GroupDocs.Watermark](../../watermarker)
* montage [GroupDocs.Watermark](../../../)

---

## Watermarker(string, LoadOptions) {#constructor_5}

Initialiseert een nieuw exemplaar van het[`Watermarker`](../../watermarker)klasse met het opgegeven documentpad en laadopties.

```csharp
public Watermarker(string filePath, LoadOptions options)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | String | Het bestandspad waaruit het document moet worden geladen. |
| options | LoadOptions | Extra opties om te gebruiken bij het laden van een document. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Geleverd documenttype wordt niet ondersteund. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Het opgegeven wachtwoord is onjuist. |

### Opmerkingen

Meer informatie over het laden van documenten: [Documenten laden](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### Voorbeelden

Laad versleuteld PDF-document met wachtwoord.

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
* naamruimte [GroupDocs.Watermark](../../watermarker)
* montage [GroupDocs.Watermark](../../../)

---

## Watermarker(string, WatermarkerSettings) {#constructor_7}

Initialiseert een nieuw exemplaar van het[`Watermarker`](../../watermarker) klasse met het opgegeven documentpad en instellingen.

```csharp
public Watermarker(string filePath, WatermarkerSettings settings)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | String | Het bestandspad waaruit het document moet worden geladen. |
| settings | WatermarkerSettings | Aanvullende instellingen die u kunt gebruiken bij het werken met een geladen document. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Geleverd documenttype wordt niet ondersteund. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Het opgegeven wachtwoord is onjuist. |

### Opmerkingen

Meer informatie over het laden van documenten: [Documenten laden](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### Voorbeelden

Doorzoekbare objecten globaal instellen (voor alle documenten die daarna worden geladen).

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
* naamruimte [GroupDocs.Watermark](../../watermarker)
* montage [GroupDocs.Watermark](../../../)

---

## Watermarker(string, LoadOptions, WatermarkerSettings) {#constructor_6}

Initialiseert een nieuw exemplaar van het[`Watermarker`](../../watermarker) klasse met het opgegeven documentpad, laadopties en instellingen.

```csharp
public Watermarker(string filePath, LoadOptions options, WatermarkerSettings settings)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | String | Het bestandspad waaruit het document moet worden geladen. |
| options | LoadOptions | Extra opties om te gebruiken bij het laden van een document. |
| settings | WatermarkerSettings | Aanvullende instellingen die u kunt gebruiken bij het werken met een geladen document. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Geleverd documenttype wordt niet ondersteund. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Het opgegeven wachtwoord is onjuist. |

### Opmerkingen

Meer informatie over het laden van documenten: [Documenten laden](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### Voorbeelden

Vind bepaalde tekstfragmenten in de hoofdtekst/het onderwerp van het e-mailbericht.

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
    // Let op, zoeken wordt alleen uitgevoerd als u de instantie TextSearchCriteria doorgeeft aan de zoekmethode
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
* naamruimte [GroupDocs.Watermark](../../watermarker)
* montage [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream) {#constructor}

Initialiseert een nieuw exemplaar van het[`Watermarker`](../../watermarker) klasse met de opgegeven stream.

```csharp
public Watermarker(Stream document)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| document | Stream | De stream waaruit het document moet worden geladen. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Geleverd documenttype wordt niet ondersteund. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Het opgegeven wachtwoord is onjuist. |

### Opmerkingen

Meer informatie over het laden van documenten [Documenten laden](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### Voorbeelden

Laad en bewaar een document van elk ondersteund formaat.

```csharp
// Laad een inhoud van een stream.
using (FileStream inputStream = File.Open("D:\\input.pdf", FileMode.Open))
using (FileStream outputStream = File.Open("D:\\output.pdf", FileMode.Create))
using (Watermarker watermarker = new Watermarker(inputStream))
{
    // Gebruik methoden van de klasse Watermarker om watermerken toe te voegen, te zoeken of te verwijderen.

    // Wijzigingen opslaan.
    watermarker.Save(outputStream);
}
```

### Zie ook

* class [Watermarker](../../watermarker)
* naamruimte [GroupDocs.Watermark](../../watermarker)
* montage [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, LoadOptions) {#constructor_1}

Initialiseert een nieuw exemplaar van het[`Watermarker`](../../watermarker) klasse met de opgegeven stream en laadopties.

```csharp
public Watermarker(Stream document, LoadOptions options)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| document | Stream | De stream waaruit het document moet worden geladen. |
| options | LoadOptions | Extra opties om te gebruiken bij het laden van een document. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Geleverd documenttype wordt niet ondersteund. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Het opgegeven wachtwoord is onjuist. |

### Opmerkingen

Meer informatie over het laden van documenten [Documenten laden](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### Voorbeelden

Laad versleuteld PDF-document met wachtwoord

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
* naamruimte [GroupDocs.Watermark](../../watermarker)
* montage [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, WatermarkerSettings) {#constructor_3}

Initialiseert een nieuw exemplaar van het[`Watermarker`](../../watermarker) klasse met de opgegeven stream en instellingen.

```csharp
public Watermarker(Stream document, WatermarkerSettings settings)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| document | Stream | De stream waaruit het document moet worden geladen. |
| settings | WatermarkerSettings | Aanvullende instellingen die u kunt gebruiken bij het werken met een geladen document. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Geleverd documenttype wordt niet ondersteund. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Het opgegeven wachtwoord is onjuist. |

### Opmerkingen

Meer informatie over het laden van documenten [Documenten laden](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### Voorbeelden

Doorzoekbare objecten globaal instellen (voor alle documenten die daarna worden geladen).

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
* naamruimte [GroupDocs.Watermark](../../watermarker)
* montage [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, LoadOptions, WatermarkerSettings) {#constructor_2}

Initialiseert een nieuw exemplaar van het[`Watermarker`](../../watermarker) klasse met de opgegeven stream, laadopties en instellingen.

```csharp
public Watermarker(Stream document, LoadOptions options, WatermarkerSettings settings)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| document | Stream | De stream waaruit het document moet worden geladen. |
| options | LoadOptions | Extra opties om te gebruiken bij het laden van een document. |
| settings | WatermarkerSettings | Aanvullende instellingen die u kunt gebruiken bij het werken met een geladen document. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Geleverd documenttype wordt niet ondersteund. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Het opgegeven wachtwoord is onjuist. |

### Opmerkingen

Meer informatie over het laden van documenten [Documenten laden](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### Voorbeelden

Vind bepaalde tekstfragmenten in de hoofdtekst/het onderwerp van het e-mailbericht.

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
    // Let op, zoeken wordt alleen uitgevoerd als u de instantie TextSearchCriteria doorgeeft aan de zoekmethode
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
* naamruimte [GroupDocs.Watermark](../../watermarker)
* montage [GroupDocs.Watermark](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
