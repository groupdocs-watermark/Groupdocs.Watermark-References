---
title: Watermarker
second_title: GroupDocs.Watermark für .NET-API-Referenz
description: Initialisiert eine neue Instanz vonWatermarkergroupdocs.watermark/watermarker Klasse mit dem angegebenen Dokumentpfad.
type: docs
weight: 10
url: /de/net/groupdocs.watermark/watermarker/watermarker/
---
## Watermarker(string) {#constructor_4}

Initialisiert eine neue Instanz von[`Watermarker`](../../watermarker) Klasse mit dem angegebenen Dokumentpfad.

```csharp
public Watermarker(string filePath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | String | Der Dateipfad, aus dem das Dokument geladen werden soll. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Angegebener Dokumenttyp wird nicht unterstützt. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Das angegebene Passwort ist falsch. |

### Bemerkungen

Weitere Informationen zum Laden von Dokumenten: [Dokumente laden](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### Beispiele

Laden und speichern Sie Inhalte in einem beliebigen unterstützten Format.

```csharp
// Inhalt aus einer Datei laden.
using (Watermarker watermarker = new Watermarker("D:\\input.pdf"))
{
    // Methoden der Watermarker-Klasse verwenden, um Wasserzeichen hinzuzufügen, zu suchen oder zu entfernen.

    // Speichern Sie das Dokument.
    watermarker.Save("D:\\output.pdf");
}
```

### Siehe auch

* class [Watermarker](../../watermarker)
* namensraum [GroupDocs.Watermark](../../watermarker)
* Montage [GroupDocs.Watermark](../../../)

---

## Watermarker(string, LoadOptions) {#constructor_5}

Initialisiert eine neue Instanz von[`Watermarker`](../../watermarker)Klasse mit dem angegebenen Dokumentpfad und den Ladeoptionen.

```csharp
public Watermarker(string filePath, LoadOptions options)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | String | Der Dateipfad, aus dem das Dokument geladen werden soll. |
| options | LoadOptions | Zusätzliche Optionen zum Laden eines Dokuments. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Angegebener Dokumenttyp wird nicht unterstützt. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Das angegebene Passwort ist falsch. |

### Bemerkungen

Weitere Informationen zum Laden von Dokumenten: [Dokumente laden](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### Beispiele

Verschlüsseltes PDF-Dokument mit Passwort laden.

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
* namensraum [GroupDocs.Watermark](../../watermarker)
* Montage [GroupDocs.Watermark](../../../)

---

## Watermarker(string, WatermarkerSettings) {#constructor_7}

Initialisiert eine neue Instanz von[`Watermarker`](../../watermarker) Klasse mit dem angegebenen Dokumentpfad und den Einstellungen.

```csharp
public Watermarker(string filePath, WatermarkerSettings settings)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | String | Der Dateipfad, aus dem das Dokument geladen werden soll. |
| settings | WatermarkerSettings | Zusätzliche Einstellungen für die Arbeit mit geladenen Dokumenten. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Angegebener Dokumenttyp wird nicht unterstützt. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Das angegebene Passwort ist falsch. |

### Bemerkungen

Weitere Informationen zum Laden von Dokumenten: [Dokumente laden](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### Beispiele

Durchsuchbare Objekte global setzen (für alle Dokumente, die danach geladen werden).

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

        // Der Code zum Arbeiten mit gefundenen Wasserzeichen gehört hierher.
    }
}
```

### Siehe auch

* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* namensraum [GroupDocs.Watermark](../../watermarker)
* Montage [GroupDocs.Watermark](../../../)

---

## Watermarker(string, LoadOptions, WatermarkerSettings) {#constructor_6}

Initialisiert eine neue Instanz von[`Watermarker`](../../watermarker) Klasse mit dem angegebenen Dokumentpfad, Ladeoptionen und Einstellungen.

```csharp
public Watermarker(string filePath, LoadOptions options, WatermarkerSettings settings)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | String | Der Dateipfad, aus dem das Dokument geladen werden soll. |
| options | LoadOptions | Zusätzliche Optionen zum Laden eines Dokuments. |
| settings | WatermarkerSettings | Zusätzliche Einstellungen für die Arbeit mit geladenen Dokumenten. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Angegebener Dokumenttyp wird nicht unterstützt. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Das angegebene Passwort ist falsch. |

### Bemerkungen

Weitere Informationen zum Laden von Dokumenten: [Dokumente laden](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### Beispiele

Bestimmte Textfragmente im Text/Betreff der E-Mail-Nachricht suchen.

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
    // Beachten Sie, dass die Suche nur durchgeführt wird, wenn Sie die TextSearchCriteria-Instanz an die Search-Methode übergeben
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
* namensraum [GroupDocs.Watermark](../../watermarker)
* Montage [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream) {#constructor}

Initialisiert eine neue Instanz von[`Watermarker`](../../watermarker) Klasse mit dem angegebenen Stream.

```csharp
public Watermarker(Stream document)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document | Stream | Der Stream, aus dem das Dokument geladen werden soll. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Angegebener Dokumenttyp wird nicht unterstützt. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Das angegebene Passwort ist falsch. |

### Bemerkungen

Weitere Informationen zum Laden von Dokumenten [Dokumente laden](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### Beispiele

Laden und speichern Sie ein Dokument in einem beliebigen unterstützten Format.

```csharp
// Inhalt aus einem Stream laden.
using (FileStream inputStream = File.Open("D:\\input.pdf", FileMode.Open))
using (FileStream outputStream = File.Open("D:\\output.pdf", FileMode.Create))
using (Watermarker watermarker = new Watermarker(inputStream))
{
    // Methoden der Watermarker-Klasse verwenden, um Wasserzeichen hinzuzufügen, zu suchen oder zu entfernen.

    // Änderungen speichern.
    watermarker.Save(outputStream);
}
```

### Siehe auch

* class [Watermarker](../../watermarker)
* namensraum [GroupDocs.Watermark](../../watermarker)
* Montage [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, LoadOptions) {#constructor_1}

Initialisiert eine neue Instanz von[`Watermarker`](../../watermarker) Klasse mit den angegebenen stream und Ladeoptionen.

```csharp
public Watermarker(Stream document, LoadOptions options)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document | Stream | Der Stream, aus dem das Dokument geladen werden soll. |
| options | LoadOptions | Zusätzliche Optionen zum Laden eines Dokuments. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Angegebener Dokumenttyp wird nicht unterstützt. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Das angegebene Passwort ist falsch. |

### Bemerkungen

Weitere Informationen zum Laden von Dokumenten [Dokumente laden](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### Beispiele

Verschlüsseltes PDF-Dokument mit Passwort laden

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
* namensraum [GroupDocs.Watermark](../../watermarker)
* Montage [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, WatermarkerSettings) {#constructor_3}

Initialisiert eine neue Instanz von[`Watermarker`](../../watermarker) Klasse mit dem angegebenen stream und settings.

```csharp
public Watermarker(Stream document, WatermarkerSettings settings)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document | Stream | Der Stream, aus dem das Dokument geladen werden soll. |
| settings | WatermarkerSettings | Zusätzliche Einstellungen für die Arbeit mit geladenen Dokumenten. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Angegebener Dokumenttyp wird nicht unterstützt. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Das angegebene Passwort ist falsch. |

### Bemerkungen

Weitere Informationen zum Laden von Dokumenten [Dokumente laden](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### Beispiele

Durchsuchbare Objekte global setzen (für alle Dokumente, die danach geladen werden).

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

        // Der Code zum Arbeiten mit gefundenen Wasserzeichen gehört hierher.
    }
}
```

### Siehe auch

* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* namensraum [GroupDocs.Watermark](../../watermarker)
* Montage [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, LoadOptions, WatermarkerSettings) {#constructor_2}

Initialisiert eine neue Instanz von[`Watermarker`](../../watermarker) Klasse mit dem angegebenen Stream, Ladeoptionen und Einstellungen.

```csharp
public Watermarker(Stream document, LoadOptions options, WatermarkerSettings settings)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document | Stream | Der Stream, aus dem das Dokument geladen werden soll. |
| options | LoadOptions | Zusätzliche Optionen zum Laden eines Dokuments. |
| settings | WatermarkerSettings | Zusätzliche Einstellungen für die Arbeit mit geladenen Dokumenten. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Angegebener Dokumenttyp wird nicht unterstützt. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Das angegebene Passwort ist falsch. |

### Bemerkungen

Weitere Informationen zum Laden von Dokumenten [Dokumente laden](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### Beispiele

Bestimmte Textfragmente im Text/Betreff der E-Mail-Nachricht suchen.

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
    // Beachten Sie, dass die Suche nur durchgeführt wird, wenn Sie die TextSearchCriteria-Instanz an die Search-Methode übergeben
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
* namensraum [GroupDocs.Watermark](../../watermarker)
* Montage [GroupDocs.Watermark](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
