---
title: "Add"
second_title: "GroupDocs.Watermark för .NET API-referens"
description: "Lägger till ett vattenmärke i det inlästa dokumentet."
type: docs
weight: 30
url: /sv/net/groupdocs.watermark/watermarker/add/
---
## Add(Watermark) {#add}

Lägger till ett vattenmärke i det inlästa dokumentet.

```csharp
public AddWatermarkResult Add(Watermark watermark)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vattenstämpel | Watermark | Vattenstämpeln att lägga till i dokumentet. |

### Anmärkningar

Läs mer om att lägga till vattenstämplar: [Lägga till vattenstämplar](https://docs.groupdocs.com/display/watermarknet/Adding+watermarks).

### Exempel

Lägg till bild- och textvattenstämpel i ett dokument av någon stödd typ.

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

### Se även

* class [AddWatermarkResult](../../../groupdocs.watermark.watermarks.results/addwatermarkresult)
* class [Watermark](../../watermark)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Add(Watermark, WatermarkOptions) {#add_1}

Lägger till ett vattenmärke i det inlästa dokumentet med hjälp av vattenmärkesalternativ.

```csharp
public AddWatermarkResult Add(Watermark watermark, WatermarkOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vattenstämpel | Watermark | Vattenstämpeln att lägga till i dokumentet. |
| alternativ | WatermarkOptions | Ytterligare alternativ att använda när du lägger till vattenstämpeln. |

### Anmärkningar

Läs mer om att lägga till vattenstämplar [Lägga till vattenstämplar](https://docs.groupdocs.com/display/watermarknet/Adding+watermarks).

### Exempel

Lägg till en bildvattenstämpel på en specifik sida i ett pdf-dokument.

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

### Se även

* class [AddWatermarkResult](../../../groupdocs.watermark.watermarks.results/addwatermarkresult)
* class [Watermark](../../watermark)
* class [WatermarkOptions](../../../groupdocs.watermark.options/watermarkoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- FÅR INTE REDIGERAS: genererad av xmldocmd för GroupDocs.watermark.dll -->
