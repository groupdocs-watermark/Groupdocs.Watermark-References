---
title: Save
second_title: GroupDocs.Watermark für .NET-API-Referenz
description: Speichert die Dokumentdaten im zugrunde liegenden Stream.
type: docs
weight: 100
url: /de/net/groupdocs.watermark/watermarker/save/
---
## Save() {#save}

Speichert die Dokumentdaten im zugrunde liegenden Stream.

```csharp
public void Save()
```

### Bemerkungen

Weitere Informationen zum Speichern der Dokumente [Dokumente speichern](https://docs.groupdocs.com/display/watermarknet/Saving+documents) .

### Beispiele

Entfernen Sie bestimmte Textfragmente aus dem Text/Betreff der E-Mail-Nachricht und speichern Sie die E-Mail-Nachricht.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\test.msg"))
{
    SearchCriteria criteria = new TextSearchCriteria("test", false);
    // Beachten Sie, dass die Suche nur durchgeführt wird, wenn Sie die TextSearchCriteria-Instanz an die Search-Methode übergeben
    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    // Gefundene Textfragmente entfernen
    watermarker.Remove(watermarks);
    // Änderungen speichern
    watermarker.Save();
}
```

### Siehe auch

* class [Watermarker](../../watermarker)
* namensraum [GroupDocs.Watermark](../../watermarker)
* Montage [GroupDocs.Watermark](../../../)

---

## Save(string) {#save_4}

Speichert das Dokument am angegebenen Speicherort.

```csharp
public void Save(string filePath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | String | Der Dateipfad zum Speichern der Dokumentdaten. |

### Bemerkungen

Weitere Informationen zum Speichern der Dokumente [Dokumente speichern](https://docs.groupdocs.com/display/watermarknet/Saving+documents) .

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

* class [Watermarker](../../watermarker)
* namensraum [GroupDocs.Watermark](../../watermarker)
* Montage [GroupDocs.Watermark](../../../)

---

## Save(Stream) {#save_2}

Speichert das Dokument im angegebenen Stream.

```csharp
public void Save(Stream document)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document | Stream | Der Stream, in dem die Dokumentdaten gespeichert werden sollen. |

### Bemerkungen

Weitere Informationen zum Speichern der Dokumente [Dokumente speichern](https://docs.groupdocs.com/display/watermarknet/Saving+documents) .

### Beispiele

Wasserzeichen hinzufügen und das Dokument im Speicherstream speichern.

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

* class [Watermarker](../../watermarker)
* namensraum [GroupDocs.Watermark](../../watermarker)
* Montage [GroupDocs.Watermark](../../../)

---

## Save(SaveOptions) {#save_1}

Speichert die Dokumentdaten mit Speicheroptionen im zugrunde liegenden Stream.

```csharp
public void Save(SaveOptions options)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | SaveOptions | Zusätzliche Optionen zum Speichern eines Dokuments. |

### Bemerkungen

Weitere Informationen zum Speichern der Dokumente [Dokumente speichern](https://docs.groupdocs.com/display/watermarknet/Saving+documents) .

### Beispiele

Wasserzeichen hinzufügen und das Dokument standardmäßig speichern[`SaveOptions`](../../../groupdocs.watermark.options/saveoptions) .

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);
    watermarker.Save(new SaveOptions());
}
```

### Siehe auch

* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* namensraum [GroupDocs.Watermark](../../watermarker)
* Montage [GroupDocs.Watermark](../../../)

---

## Save(string, SaveOptions) {#save_5}

Speichert das Dokument unter Verwendung von Speicheroptionen am angegebenen Speicherort.

```csharp
public void Save(string filePath, SaveOptions options)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | String | Der Dateipfad zum Speichern der Dokumentdaten. |
| options | SaveOptions | Zusätzliche Optionen zum Speichern eines Dokuments. |

### Bemerkungen

Weitere Informationen zum Speichern der Dokumente [Dokumente speichern](https://docs.groupdocs.com/display/watermarknet/Saving+documents) .

### Beispiele

Fügen Sie das Wasserzeichen hinzu und speichern Sie das Dokument standardmäßig in einer anderen Datei[`SaveOptions`](../../../groupdocs.watermark.options/saveoptions) .

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{                                                                                   
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);                                            
    watermarker.Save("ouput.pdf", new SaveOptions());
}                                                                                   
```

### Siehe auch

* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* namensraum [GroupDocs.Watermark](../../watermarker)
* Montage [GroupDocs.Watermark](../../../)

---

## Save(Stream, SaveOptions) {#save_3}

Speichert das Dokument unter Verwendung von Speicheroptionen im angegebenen Stream.

```csharp
public void Save(Stream document, SaveOptions options)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document | Stream | Der Stream, in dem die Dokumentdaten gespeichert werden sollen. |
| options | SaveOptions | Zusätzliche Optionen zum Speichern eines Dokuments. |

### Bemerkungen

Weitere Informationen zum Speichern der Dokumente [Dokumente speichern](https://docs.groupdocs.com/display/watermarknet/Saving+documents) .

### Beispiele

Wasserzeichen hinzufügen und das Dokument standardmäßig im Speicherstrom speichern[`SaveOptions`](../../../groupdocs.watermark.options/saveoptions) .

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

* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* namensraum [GroupDocs.Watermark](../../watermarker)
* Montage [GroupDocs.Watermark](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
