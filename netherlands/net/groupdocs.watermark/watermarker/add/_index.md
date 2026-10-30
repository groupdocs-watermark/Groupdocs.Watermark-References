---
title: "Add"
second_title: "GroupDocs.Watermark voor .NET API-referentie"
description: "Voegt een watermerk toe aan het geladen document."
type: docs
weight: 30
url: /nl/net/groupdocs.watermark/watermarker/add/
---
## Add(Watermark) {#add}

Voegt een watermerk toe aan het geladen document.

```csharp
public AddWatermarkResult Add(Watermark watermark)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| watermerk | Watermark | Het watermerk om toe te voegen aan het document. |

### Opmerkingen

Meer informatie over het toevoegen van watermerken: [Watermerken toevoegen](https://docs.groupdocs.com/display/watermarknet/Adding+watermarks).

### Voorbeelden

Voeg afbeelding- en tekstwatermerk toe aan een document van elk ondersteund type.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\input.pdf"))
{
    TextWatermark textWatermark = new TextWatermark("DRAFT", new Font("Arial", 19));
    textWatermark.HorizontalAlignment = HorizontalAlignment.Center;
    textWatermark.VerticalAlignment = VerticalAlignment.Top;
    textWatermark.ConsiderParentMargins = true;
    textWatermark.ForegroundColor = Color.Red;
    textWatermark.IsBackground = true;
    textWatermark.Opacity = 0.5;
    watermarker.Add(textWatermark);

    using (ImageWatermark imageWatermark = new ImageWatermark(@"D:\draft.png"))
    {
        imageWatermark.HorizontalAlignment = HorizontalAlignment.Center;
        imageWatermark.VerticalAlignment = VerticalAlignment.Bottom;
        imageWatermark.ConsiderParentMargins = true;
        imageWatermark.IsBackground = true;
        imageWatermark.Opacity = 0.5;
        watermarker.Add(imageWatermark);
    }

    watermarker.Save(@"D:\output.pdf");
}
```

### Zie ook

* class [AddWatermarkResult](../../../groupdocs.watermark.watermarks.results/addwatermarkresult)
* class [Watermark](../../watermark)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Add(Watermark, WatermarkOptions) {#add_1}

Voegt een watermerk toe aan het geladen document met behulp van watermerkopties.

```csharp
public AddWatermarkResult Add(Watermark watermark, WatermarkOptions options)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| watermerk | Watermark | Het watermerk om toe te voegen aan het document. |
| opties | WatermarkOptions | Aanvullende opties om te gebruiken bij het toevoegen van het watermerk. |

### Opmerkingen

Meer informatie over het toevoegen van watermerken [Watermerken toevoegen](https://docs.groupdocs.com/display/watermarknet/Adding+watermarks).

### Voorbeelden

Voeg een afbeeldingwatermerk toe aan een specifieke pagina van een pdf-document.

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
using (Watermarker watermarker = new Watermarker(@"C:\doc.pdf", loadOptions))
using (ImageWatermark watermark = new ImageWatermark(@"C:\watermark.png"))
{
    PdfXObjectWatermarkOptions options = new PdfXObjectWatermarkOptions();
    options.PageIndex = 0;

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### Zie ook

* class [AddWatermarkResult](../../../groupdocs.watermark.watermarks.results/addwatermarkresult)
* class [Watermark](../../watermark)
* class [WatermarkOptions](../../../groupdocs.watermark.options/watermarkoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.watermark.dll -->
