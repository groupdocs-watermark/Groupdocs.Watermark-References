---
title: "Spara"
second_title: "GroupDocs.Watermark för .NET API-referens"
description: "Sparar dokumentdata till den underliggande strömmen."
type: docs
weight: 100
url: /sv/net/groupdocs.watermark/watermarker/save/
---
## Save() {#save}

Sparar dokumentdata till den underliggande strömmen.

```csharp
public WatermarkResult Save()
```

### Anmärkningar

Läs mer om att spara dokumenten [Spara dokument](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### Exempel

Ta bort specifika textfragment från e‑postmeddelandets brödtext/ämne och spara e‑postmeddelandet.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\test.msg"))
{
    SearchCriteria criteria = new TextSearchCriteria("test", false);
    // Observera, sökningen utförs endast om du skickar en TextSearchCriteria‑instans till Search‑metoden.
    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    // Ta bort hittade textfragment
    watermarker.Remove(watermarks);
    // Spara ändringar
    watermarker.Save();
}
```

### Se även

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Save(string) {#save_4}

Sparar dokumentet till den angivna filplatsen.

```csharp
public WatermarkResult Save(string filePath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | Sträng | Filvägen att spara dokumentdata till. |

### Anmärkningar

Läs mer om att spara dokumenten [Spara dokument](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### Exempel

Lägg till vattenmärket och spara dokumentet till en annan fil.

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{                                                                                   
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);                                            
    watermarker.Save("ouput.pdf");                                   
}                                                                                   
```

### Se även

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Save(Stream) {#save_2}

Sparar dokumentet till den angivna strömmen.

```csharp
public WatermarkResult Save(Stream document)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dokument | Stream | Strömmen att spara dokumentdata till. |

### Anmärkningar

Läs mer om att spara dokumenten [Spara dokument](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### Exempel

Lägg till vattenmärke och spara dokumentet till minnesströmmen.

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

### Se även

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Save(SaveOptions) {#save_1}

Sparar dokumentdata till den underliggande strömmen med hjälp av sparalternativ.

```csharp
public WatermarkResult Save(SaveOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| alternativ | SaveOptions | Ytterligare alternativ att använda när du sparar ett dokument. |

### Anmärkningar

Läs mer om att spara dokumenten [Spara dokument](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### Exempel

Lägg till vattenmärke och spara dokumentet med standard [`SaveOptions`](../../../groupdocs.watermark.options/saveoptions).

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);
    watermarker.Save(new SaveOptions());
}
```

### Se även

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Save(string, SaveOptions) {#save_5}

Sparar dokumentet till den angivna filplatsen med hjälp av sparalternativ.

```csharp
public WatermarkResult Save(string filePath, SaveOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | Sträng | Filvägen att spara dokumentdata till. |
| alternativ | SaveOptions | Ytterligare alternativ att använda när du sparar ett dokument. |

### Anmärkningar

Läs mer om att spara dokumenten [Spara dokument](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### Exempel

Lägg till vattenmärket och spara dokumentet till en annan fil med standard [`SaveOptions`](../../../groupdocs.watermark.options/saveoptions).

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{                                                                                   
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);                                            
    watermarker.Save("ouput.pdf", new SaveOptions());
}                                                                                   
```

### Se även

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Save(Stream, SaveOptions) {#save_3}

Sparar dokumentet till den angivna strömmen med hjälp av sparalternativ.

```csharp
public WatermarkResult Save(Stream document, SaveOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dokument | Stream | Strömmen att spara dokumentdata till. |
| alternativ | SaveOptions | Ytterligare alternativ att använda när du sparar ett dokument. |

### Anmärkningar

Läs mer om att spara dokumenten [Spara dokument](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### Exempel

Lägg till vattenmärke och spara dokumentet till minnesströmmen med standard [`SaveOptions`](../../../groupdocs.watermark.options/saveoptions).

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

### Se även

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- FÅR INTE REDIGERAS: genererad av xmldocmd för GroupDocs.watermark.dll -->
