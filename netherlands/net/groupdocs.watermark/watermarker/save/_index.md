---
title: "Opslaan"
second_title: "GroupDocs.Watermark voor .NET API-referentie"
description: "Slaat de documentgegevens op naar de onderliggende stream."
type: docs
weight: 100
url: /nl/net/groupdocs.watermark/watermarker/save/
---
## Save() {#save}

Slaat de documentgegevens op naar de onderliggende stream.

```csharp
public WatermarkResult Save()
```

### Opmerkingen

Meer informatie over het opslaan van documenten [Documenten opslaan](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### Voorbeelden

Verwijder specifieke tekstfragmenten uit de e‑mailberichtinhoud/onderwerp en sla het e‑mailbericht op.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\test.msg"))
{
    SearchCriteria criteria = new TextSearchCriteria("test", false);
    // Opmerking, zoeken wordt alleen uitgevoerd als u een TextSearchCriteria‑instantie doorgeeft aan de Search‑methode
    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    // Verwijder gevonden tekstfragmenten
    watermarker.Remove(watermarks);
    // Wijzigingen opslaan
    watermarker.Save();
}
```

### Zie ook

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Save(string) {#save_4}

Slaat het document op naar de opgegeven bestandslocatie.

```csharp
public WatermarkResult Save(string filePath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | String | Het bestandspad om de documentgegevens op te slaan. |

### Opmerkingen

Meer informatie over het opslaan van documenten [Documenten opslaan](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### Voorbeelden

Voeg het watermerk toe en sla het document op in een ander bestand.

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{                                                                                   
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);                                            
    watermarker.Save("ouput.pdf");                                   
}                                                                                   
```

### Zie ook

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Save(Stream) {#save_2}

Slaat het document op naar de opgegeven stream.

```csharp
public WatermarkResult Save(Stream document)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| document | Stream | De stream om de documentgegevens op te slaan. |

### Opmerkingen

Meer informatie over het opslaan van documenten [Documenten opslaan](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### Voorbeelden

Voeg watermerk toe en sla het document op in de geheugen‑stream.

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

### Zie ook

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Save(SaveOptions) {#save_1}

Slaat de documentgegevens op naar de onderliggende stream met behulp van opslaanopties.

```csharp
public WatermarkResult Save(SaveOptions options)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| opties | SaveOptions | Aanvullende opties om te gebruiken bij het opslaan van een document. |

### Opmerkingen

Meer informatie over het opslaan van documenten [Documenten opslaan](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### Voorbeelden

Voeg een watermerk toe en sla het document op met de standaard [`SaveOptions`](../../../groupdocs.watermark.options/saveoptions).

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);
    watermarker.Save(new SaveOptions());
}
```

### Zie ook

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Save(string, SaveOptions) {#save_5}

Slaat het document op naar de opgegeven bestandslocatie met behulp van opslagopties.

```csharp
public WatermarkResult Save(string filePath, SaveOptions options)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | String | Het bestandspad om de documentgegevens op te slaan. |
| opties | SaveOptions | Aanvullende opties om te gebruiken bij het opslaan van een document. |

### Opmerkingen

Meer informatie over het opslaan van documenten [Documenten opslaan](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### Voorbeelden

Voeg het watermerk toe en sla het document op in een ander bestand met de standaard [`SaveOptions`](../../../groupdocs.watermark.options/saveoptions).

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{                                                                                   
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);                                            
    watermarker.Save("ouput.pdf", new SaveOptions());
}                                                                                   
```

### Zie ook

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Save(Stream, SaveOptions) {#save_3}

Slaat het document op naar de opgegeven stream met behulp van opslaanopties.

```csharp
public WatermarkResult Save(Stream document, SaveOptions options)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| document | Stream | De stream om de documentgegevens op te slaan. |
| opties | SaveOptions | Aanvullende opties om te gebruiken bij het opslaan van een document. |

### Opmerkingen

Meer informatie over het opslaan van documenten [Documenten opslaan](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### Voorbeelden

Voeg een watermerk toe en sla het document op in de geheugenstroom met de standaard [`SaveOptions`](../../../groupdocs.watermark.options/saveoptions).

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

### Zie ook

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.watermark.dll -->
