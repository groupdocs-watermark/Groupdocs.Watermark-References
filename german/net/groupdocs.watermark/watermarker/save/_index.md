---
title: "Speichern"
second_title: "GroupDocs.Watermark für .NET API-Referenz"
description: "Speichert die Dokumentdaten in den zugrunde liegenden Stream."
type: docs
weight: 100
url: /de/net/groupdocs.watermark/watermarker/save/
---
## Save() {#save}

Speichert die Dokumentdaten in den zugrunde liegenden Stream.

```csharp
public WatermarkResult Save()
```

### Hinweise

Erfahren Sie mehr über das Speichern von Dokumenten [Speichern von Dokumenten](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### Beispiele

Entfernen Sie bestimmte Textfragmente aus dem E-Mail-Nachrichtentext/-Betreff und speichern Sie die E-Mail-Nachricht.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\test.msg"))
{
    SearchCriteria criteria = new TextSearchCriteria("test", false);
    // Hinweis, die Suche wird nur durchgeführt, wenn Sie eine TextSearchCriteria-Instanz an die Search-Methode übergeben.
    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    // Gefundene Textfragmente entfernen
    watermarker.Remove(watermarks);
    // Änderungen speichern
    watermarker.Save();
}
```

### Siehe auch

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Save(string) {#save_4}

Speichert das Dokument am angegebenen Dateipfad.

```csharp
public WatermarkResult Save(string filePath)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| filePath | String | Der Dateipfad, in dem die Dokumentdaten gespeichert werden sollen. |

### Hinweise

Erfahren Sie mehr über das Speichern von Dokumenten [Speichern von Dokumenten](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### Beispiele

Fügen Sie das Wasserzeichen hinzu und speichern Sie das Dokument in einer anderen Datei.

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{                                                                                   
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);                                            
    watermarker.Save("ouput.pdf");                                   
}                                                                                   
```

### Siehe auch

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Save(Stream) {#save_2}

Speichert das Dokument in den angegebenen Stream.

```csharp
public WatermarkResult Save(Stream document)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Dokument | Stream | Der Stream, in dem die Dokumentdaten gespeichert werden. |

### Hinweise

Erfahren Sie mehr über das Speichern von Dokumenten [Speichern von Dokumenten](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### Beispiele

Fügen Sie das Wasserzeichen hinzu und speichern Sie das Dokument im Speicher-Stream.

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

### Siehe auch

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Save(SaveOptions) {#save_1}

Speichert die Dokumentdaten in den zugrunde liegenden Stream unter Verwendung von Speicheroptionen.

```csharp
public WatermarkResult Save(SaveOptions options)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Optionen | SaveOptions | Zusätzliche Optionen, die beim Speichern eines Dokuments verwendet werden können. |

### Hinweise

Erfahren Sie mehr über das Speichern von Dokumenten [Speichern von Dokumenten](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### Beispiele

Wasserzeichen hinzufügen und das Dokument mit den Standard-[`SaveOptions`](../../../groupdocs.watermark.options/saveoptions) speichern.

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);
    watermarker.Save(new SaveOptions());
}
```

### Siehe auch

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Save(string, SaveOptions) {#save_5}

Speichert das Dokument am angegebenen Dateipfad unter Verwendung von Speicheroptionen.

```csharp
public WatermarkResult Save(string filePath, SaveOptions options)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| filePath | String | Der Dateipfad, in dem die Dokumentdaten gespeichert werden sollen. |
| Optionen | SaveOptions | Zusätzliche Optionen, die beim Speichern eines Dokuments verwendet werden können. |

### Hinweise

Erfahren Sie mehr über das Speichern von Dokumenten [Speichern von Dokumenten](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### Beispiele

Füge das Wasserzeichen hinzu und speichere das Dokument in einer anderen Datei mit den Standard-[`SaveOptions`](../../../groupdocs.watermark.options/saveoptions).

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{                                                                                   
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);                                            
    watermarker.Save("ouput.pdf", new SaveOptions());
}                                                                                   
```

### Siehe auch

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Save(Stream, SaveOptions) {#save_3}

Speichert das Dokument in den angegebenen Stream unter Verwendung von Speicheroptionen.

```csharp
public WatermarkResult Save(Stream document, SaveOptions options)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Dokument | Stream | Der Stream, in dem die Dokumentdaten gespeichert werden. |
| Optionen | SaveOptions | Zusätzliche Optionen, die beim Speichern eines Dokuments verwendet werden können. |

### Hinweise

Erfahren Sie mehr über das Speichern von Dokumenten [Speichern von Dokumenten](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### Beispiele

Wasserzeichen hinzufügen und das Dokument mit den Standard-[`SaveOptions`](../../../groupdocs.watermark.options/saveoptions) in den Speicherstream speichern.

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

### Siehe auch

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.watermark.dll -->
