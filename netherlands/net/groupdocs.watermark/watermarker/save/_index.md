---
title: Save
second_title: GroupDocs.Watermark voor .NET API-referentie
description: Slaat de documentgegevens op in de onderliggende stream.
type: docs
weight: 100
url: /nl/net/groupdocs.watermark/watermarker/save/
---
## Save() {#save}

Slaat de documentgegevens op in de onderliggende stream.

```csharp
public void Save()
```

### Opmerkingen

Meer informatie over het opslaan van de documenten [Documenten opslaan](https://docs.groupdocs.com/display/watermarknet/Saving+documents) .

### Voorbeelden

Verwijder bepaalde tekstfragmenten uit de hoofdtekst/het onderwerp van het e-mailbericht en sla het e-mailbericht op.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\test.msg"))
{
    SearchCriteria criteria = new TextSearchCriteria("test", false);
    // Let op, zoeken wordt alleen uitgevoerd als u de instantie TextSearchCriteria doorgeeft aan de zoekmethode
    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    // Verwijder gevonden tekstfragmenten
    watermarker.Remove(watermarks);
    // Wijzigingen opslaan
    watermarker.Save();
}
```

### Zie ook

* class [Watermarker](../../watermarker)
* naamruimte [GroupDocs.Watermark](../../watermarker)
* montage [GroupDocs.Watermark](../../../)

---

## Save(string) {#save_4}

Slaat het document op de opgegeven bestandslocatie op.

```csharp
public void Save(string filePath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | String | Het bestandspad om de documentgegevens in op te slaan. |

### Opmerkingen

Meer informatie over het opslaan van de documenten [Documenten opslaan](https://docs.groupdocs.com/display/watermarknet/Saving+documents) .

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

* class [Watermarker](../../watermarker)
* naamruimte [GroupDocs.Watermark](../../watermarker)
* montage [GroupDocs.Watermark](../../../)

---

## Save(Stream) {#save_2}

Slaat het document op in de opgegeven stream.

```csharp
public void Save(Stream document)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| document | Stream | De stream waarin de documentgegevens moeten worden opgeslagen. |

### Opmerkingen

Meer informatie over het opslaan van de documenten [Documenten opslaan](https://docs.groupdocs.com/display/watermarknet/Saving+documents) .

### Voorbeelden

Voeg een watermerk toe en sla het document op in de geheugenstream.

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

* class [Watermarker](../../watermarker)
* naamruimte [GroupDocs.Watermark](../../watermarker)
* montage [GroupDocs.Watermark](../../../)

---

## Save(SaveOptions) {#save_1}

Slaat de documentgegevens op in de onderliggende stroom met behulp van opslagopties.

```csharp
public void Save(SaveOptions options)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | SaveOptions | Extra opties om te gebruiken bij het opslaan van een document. |

### Opmerkingen

Meer informatie over het opslaan van de documenten [Documenten opslaan](https://docs.groupdocs.com/display/watermarknet/Saving+documents) .

### Voorbeelden

Voeg een watermerk toe en sla het document standaard op[`SaveOptions`](../../../groupdocs.watermark.options/saveoptions) .

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);
    watermarker.Save(new SaveOptions());
}
```

### Zie ook

* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* naamruimte [GroupDocs.Watermark](../../watermarker)
* montage [GroupDocs.Watermark](../../../)

---

## Save(string, SaveOptions) {#save_5}

Slaat het document op de gespecificeerde bestandslocatie op met behulp van opslagopties.

```csharp
public void Save(string filePath, SaveOptions options)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | String | Het bestandspad om de documentgegevens in op te slaan. |
| options | SaveOptions | Extra opties om te gebruiken bij het opslaan van een document. |

### Opmerkingen

Meer informatie over het opslaan van de documenten [Documenten opslaan](https://docs.groupdocs.com/display/watermarknet/Saving+documents) .

### Voorbeelden

Voeg het watermerk toe en sla het document standaard op in een ander bestand[`SaveOptions`](../../../groupdocs.watermark.options/saveoptions) .

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{                                                                                   
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);                                            
    watermarker.Save("ouput.pdf", new SaveOptions());
}                                                                                   
```

### Zie ook

* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* naamruimte [GroupDocs.Watermark](../../watermarker)
* montage [GroupDocs.Watermark](../../../)

---

## Save(Stream, SaveOptions) {#save_3}

Slaat het document op in de opgegeven stream met behulp van opslagopties.

```csharp
public void Save(Stream document, SaveOptions options)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| document | Stream | De stream waarin de documentgegevens moeten worden opgeslagen. |
| options | SaveOptions | Extra opties om te gebruiken bij het opslaan van een document. |

### Opmerkingen

Meer informatie over het opslaan van de documenten [Documenten opslaan](https://docs.groupdocs.com/display/watermarknet/Saving+documents) .

### Voorbeelden

Voeg een watermerk toe en sla het document standaard op in de geheugenstroom[`SaveOptions`](../../../groupdocs.watermark.options/saveoptions) .

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

* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* naamruimte [GroupDocs.Watermark](../../watermarker)
* montage [GroupDocs.Watermark](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
