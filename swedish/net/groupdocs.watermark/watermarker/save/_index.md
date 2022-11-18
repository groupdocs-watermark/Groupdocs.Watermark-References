---
title: Save
second_title: GroupDocs.Watermark for .NET API-referens
description: Sparar dokumentdata till den underliggande strömmen.
type: docs
weight: 100
url: /sv/net/groupdocs.watermark/watermarker/save/
---
## Save() {#save}

Sparar dokumentdata till den underliggande strömmen.

```csharp
public void Save()
```

### Anmärkningar

Läs mer om hur du sparar dokumenten [Spara dokument](https://docs.groupdocs.com/display/watermarknet/Saving+documents) .

### Exempel

Ta bort särskilda textfragment från e-postmeddelandets brödtext/ämne och spara e-postmeddelandet.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\test.msg"))
{
    SearchCriteria criteria = new TextSearchCriteria("test", false);
    // Obs, sökning utförs endast om du skickar TextSearchCriteria-instansen till sökmetoden
    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    // Ta bort hittade textfragment
    watermarker.Remove(watermarks);
    // Spara ändringar
    watermarker.Save();
}
```

### Se även

* class [Watermarker](../../watermarker)
* namnutrymme [GroupDocs.Watermark](../../watermarker)
* hopsättning [GroupDocs.Watermark](../../../)

---

## Save(string) {#save_4}

Sparar dokumentet till den angivna filplatsen.

```csharp
public void Save(string filePath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | String | Filsökvägen att spara dokumentdata till. |

### Anmärkningar

Läs mer om hur du sparar dokumenten [Spara dokument](https://docs.groupdocs.com/display/watermarknet/Saving+documents) .

### Exempel

Lägg till vattenstämpeln och spara dokumentet i en annan fil.

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{                                                                                   
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);                                            
    watermarker.Save("ouput.pdf");                                   
}                                                                                   
```

### Se även

* class [Watermarker](../../watermarker)
* namnutrymme [GroupDocs.Watermark](../../watermarker)
* hopsättning [GroupDocs.Watermark](../../../)

---

## Save(Stream) {#save_2}

Sparar dokumentet i den angivna strömmen.

```csharp
public void Save(Stream document)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | Stream | Streamen att spara dokumentdata till. |

### Anmärkningar

Läs mer om hur du sparar dokumenten [Spara dokument](https://docs.groupdocs.com/display/watermarknet/Saving+documents) .

### Exempel

Lägg till vattenstämpel och spara dokumentet i minnesströmmen.

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

* class [Watermarker](../../watermarker)
* namnutrymme [GroupDocs.Watermark](../../watermarker)
* hopsättning [GroupDocs.Watermark](../../../)

---

## Save(SaveOptions) {#save_1}

Sparar dokumentdata till den underliggande strömmen med hjälp av sparalternativ.

```csharp
public void Save(SaveOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | SaveOptions | Ytterligare alternativ att använda när du sparar ett dokument. |

### Anmärkningar

Läs mer om hur du sparar dokumenten [Spara dokument](https://docs.groupdocs.com/display/watermarknet/Saving+documents) .

### Exempel

Lägg till vattenstämpel och spara dokumentet med standard[`SaveOptions`](../../../groupdocs.watermark.options/saveoptions) .

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);
    watermarker.Save(new SaveOptions());
}
```

### Se även

* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* namnutrymme [GroupDocs.Watermark](../../watermarker)
* hopsättning [GroupDocs.Watermark](../../../)

---

## Save(string, SaveOptions) {#save_5}

Sparar dokumentet till den angivna filplatsen med hjälp av sparaalternativ.

```csharp
public void Save(string filePath, SaveOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | String | Filsökvägen att spara dokumentdata till. |
| options | SaveOptions | Ytterligare alternativ att använda när du sparar ett dokument. |

### Anmärkningar

Läs mer om hur du sparar dokumenten [Spara dokument](https://docs.groupdocs.com/display/watermarknet/Saving+documents) .

### Exempel

Lägg till vattenstämpeln och spara dokumentet i en annan fil med standard[`SaveOptions`](../../../groupdocs.watermark.options/saveoptions) .

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{                                                                                   
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);                                            
    watermarker.Save("ouput.pdf", new SaveOptions());
}                                                                                   
```

### Se även

* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* namnutrymme [GroupDocs.Watermark](../../watermarker)
* hopsättning [GroupDocs.Watermark](../../../)

---

## Save(Stream, SaveOptions) {#save_3}

Sparar dokumentet till den angivna strömmen med hjälp av sparaalternativ.

```csharp
public void Save(Stream document, SaveOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | Stream | Streamen att spara dokumentdata till. |
| options | SaveOptions | Ytterligare alternativ att använda när du sparar ett dokument. |

### Anmärkningar

Läs mer om hur du sparar dokumenten [Spara dokument](https://docs.groupdocs.com/display/watermarknet/Saving+documents) .

### Exempel

Lägg till vattenstämpel och spara dokumentet i minnesströmmen med standard[`SaveOptions`](../../../groupdocs.watermark.options/saveoptions) .

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

* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* namnutrymme [GroupDocs.Watermark](../../watermarker)
* hopsättning [GroupDocs.Watermark](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
