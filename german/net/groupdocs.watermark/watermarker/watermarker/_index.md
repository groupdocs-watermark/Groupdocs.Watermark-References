---
title: "Watermarker"
second_title: "GroupDocs.Watermark für .NET API-Referenz"
description: "Initialisiert eine neue Instanz der Watermarkergroupdocs.watermark/watermarker-Klasse mit dem angegebenen Dokumentpfad."
type: docs
weight: 10
url: /de/net/groupdocs.watermark/watermarker/watermarker/
---
## Watermarker(string) {#constructor_4}

Initialisiert eine neue Instanz der [`Watermarker`](../../watermarker)-Klasse mit dem angegebenen Dokumentpfad.

```csharp
public Watermarker(string filePath)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| filePath | String | Der Dateipfad, von dem das Dokument geladen wird. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Der angegebene Dokumenttyp wird nicht unterstützt. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Das angegebene Passwort ist falsch. |

### Hinweise

Erfahren Sie mehr über das Laden von Dokumenten: [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### Beispiele

Lädt und speichert Inhalte in einem beliebigen unterstützten Format.

```csharp
// Lädt Inhalte aus einer Datei.
using (Watermarker watermarker = new Watermarker("D:\\input.pdf"))
{
    // Verwenden Sie Methoden der Watermarker class, um Wasserzeichen hinzuzufügen, zu suchen oder zu entfernen.

    // Speichern Sie das Dokument.
    watermarker.Save("D:\\output.pdf");
}
```

### Siehe auch

* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(string, LoadOptions) {#constructor_5}

Initialisiert eine neue Instanz der [`Watermarker`](../../watermarker)-Klasse mit dem angegebenen Dokumentpfad und Ladeoptionen.

```csharp
public Watermarker(string filePath, LoadOptions options)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| filePath | String | Der Dateipfad, von dem das Dokument geladen wird. |
| Optionen | LoadOptions | Zusätzliche Optionen, die beim Laden eines Dokuments verwendet werden. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Der angegebene Dokumenttyp wird nicht unterstützt. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Das angegebene Passwort ist falsch. |

### Hinweise

Erfahren Sie mehr über das Laden von Dokumenten: [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### Beispiele

Laden Sie ein verschlüsseltes PDF-Dokument mit Passwort.

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
loadOptions.Password = "123";
using (Watermarker watermarker = new Watermarker(@"C:\Documents\test.pdf", loadOptions))
{
    // ...
}
```

### Siehe auch

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(string, WatermarkerSettings) {#constructor_7}

Initialisiert eine neue Instanz der [`Watermarker`](../../watermarker)-Klasse mit dem angegebenen Dokumentpfad und Einstellungen.

```csharp
public Watermarker(string filePath, WatermarkerSettings settings)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| filePath | String | Der Dateipfad, von dem das Dokument geladen wird. |
| Einstellungen | WatermarkerSettings | Zusätzliche Einstellungen, die bei der Arbeit mit dem geladenen Dokument verwendet werden. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Der angegebene Dokumenttyp wird nicht unterstützt. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Das angegebene Passwort ist falsch. |

### Hinweise

Erfahren Sie mehr über das Laden von Dokumenten: [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### Beispiele

Suchbare Objekte global festlegen (für alle Dokumente, die danach geladen werden).

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

        // Der Code für die Arbeit mit gefundenen Wasserzeichen kommt hier hin.
    }
}
```

### Siehe auch

* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(string, LoadOptions, WatermarkerSettings) {#constructor_6}

Initialisiert eine neue Instanz der [`Watermarker`](../../watermarker)-Klasse mit dem angegebenen Dokumentpfad, Ladeoptionen und Einstellungen.

```csharp
public Watermarker(string filePath, LoadOptions options, WatermarkerSettings settings)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| filePath | String | Der Dateipfad, von dem das Dokument geladen wird. |
| Optionen | LoadOptions | Zusätzliche Optionen, die beim Laden eines Dokuments verwendet werden. |
| Einstellungen | WatermarkerSettings | Zusätzliche Einstellungen, die bei der Arbeit mit dem geladenen Dokument verwendet werden. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Der angegebene Dokumenttyp wird nicht unterstützt. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Das angegebene Passwort ist falsch. |

### Hinweise

Erfahren Sie mehr über das Laden von Dokumenten: [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### Beispiele

Finden Sie bestimmte Textfragmente im E-Mail-Nachrichtentext/-Betreff.

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
    // Hinweis, die Suche wird nur durchgeführt, wenn Sie eine TextSearchCriteria-Instanz an die Search-Methode übergeben.
    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    // Gefundene Textfragmente entfernen
    watermarks.Clear();
    // Änderungen speichern
    watermarker.Save();
}
```

### Siehe auch

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream) {#constructor}

Initialisiert eine neue Instanz der [`Watermarker`](../../watermarker)-Klasse mit dem angegebenen Stream.

```csharp
public Watermarker(Stream document)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Dokument | Stream | Der Stream, aus dem das Dokument geladen wird. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Der angegebene Dokumenttyp wird nicht unterstützt. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Das angegebene Passwort ist falsch. |

### Hinweise

Erfahren Sie mehr über das Laden von Dokumenten [Laden von Dokumenten](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### Beispiele

Laden und speichern Sie ein Dokument in einem beliebigen unterstützten Format.

```csharp
// Laden Sie Inhalte aus einem Stream.
using (FileStream inputStream = File.Open("D:\\input.pdf", FileMode.Open))
using (FileStream outputStream = File.Open("D:\\output.pdf", FileMode.Create))
using (Watermarker watermarker = new Watermarker(inputStream))
{
    // Verwenden Sie Methoden der Watermarker class, um Wasserzeichen hinzuzufügen, zu suchen oder zu entfernen.

    // Änderungen speichern.
    watermarker.Save(outputStream);
}
```

### Siehe auch

* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, LoadOptions) {#constructor_1}

Initialisiert eine neue Instanz der [`Watermarker`](../../watermarker)-Klasse mit dem angegebenen Stream und den Ladeoptionen.

```csharp
public Watermarker(Stream document, LoadOptions options)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Dokument | Stream | Der Stream, aus dem das Dokument geladen wird. |
| Optionen | LoadOptions | Zusätzliche Optionen, die beim Laden eines Dokuments verwendet werden. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Der angegebene Dokumenttyp wird nicht unterstützt. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Das angegebene Passwort ist falsch. |

### Hinweise

Erfahren Sie mehr über das Laden von Dokumenten [Laden von Dokumenten](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### Beispiele

Laden Sie ein verschlüsseltes PDF-Dokument mit Passwort

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
loadOptions.Password = "123";
using (FileStream fileStream = File.Open(@"C:\Documents\test.pdf", FileMode.Open))
using (Watermarker watermarker = new Watermarker(fileStream, loadOptions))
{
    // ...
}
```

### Siehe auch

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, WatermarkerSettings) {#constructor_3}

Initialisiert eine neue Instanz der [`Watermarker`](../../watermarker)-Klasse mit dem angegebenen Stream und den Einstellungen.

```csharp
public Watermarker(Stream document, WatermarkerSettings settings)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Dokument | Stream | Der Stream, aus dem das Dokument geladen wird. |
| Einstellungen | WatermarkerSettings | Zusätzliche Einstellungen, die bei der Arbeit mit dem geladenen Dokument verwendet werden. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Der angegebene Dokumenttyp wird nicht unterstützt. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Das angegebene Passwort ist falsch. |

### Hinweise

Erfahren Sie mehr über das Laden von Dokumenten [Laden von Dokumenten](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### Beispiele

Suchbare Objekte global festlegen (für alle Dokumente, die danach geladen werden).

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

        // Der Code für die Arbeit mit gefundenen Wasserzeichen kommt hier hin.
    }
}
```

### Siehe auch

* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, LoadOptions, WatermarkerSettings) {#constructor_2}

Initialisiert eine neue Instanz der [`Watermarker`](../../watermarker)-Klasse mit dem angegebenen Stream, den Ladeoptionen und den Einstellungen.

```csharp
public Watermarker(Stream document, LoadOptions options, WatermarkerSettings settings)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Dokument | Stream | Der Stream, aus dem das Dokument geladen wird. |
| Optionen | LoadOptions | Zusätzliche Optionen, die beim Laden eines Dokuments verwendet werden. |
| Einstellungen | WatermarkerSettings | Zusätzliche Einstellungen, die bei der Arbeit mit dem geladenen Dokument verwendet werden. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Der angegebene Dokumenttyp wird nicht unterstützt. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Das angegebene Passwort ist falsch. |

### Hinweise

Erfahren Sie mehr über das Laden von Dokumenten [Laden von Dokumenten](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### Beispiele

Finden Sie bestimmte Textfragmente im E-Mail-Nachrichtentext/-Betreff.

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
    // Hinweis, die Suche wird nur durchgeführt, wenn Sie eine TextSearchCriteria-Instanz an die Search-Methode übergeben.
    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    // Gefundene Textfragmente entfernen
    watermarks.Clear();
    // Änderungen speichern
    watermarker.Save();
}
```

### Siehe auch

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.watermark.dll -->
