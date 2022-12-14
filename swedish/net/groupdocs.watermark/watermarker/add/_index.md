---
title: Add
second_title: GroupDocs.Watermark for .NET API-referens
description: Lägger till en vattenstämpel till det laddade dokumentet.
type: docs
weight: 30
url: /sv/net/groupdocs.watermark/watermarker/add/
---
## Add(Watermark) {#add}

Lägger till en vattenstämpel till det laddade dokumentet.

```csharp
public void Add(Watermark watermark)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| watermark | Watermark | Vattenstämpeln som ska läggas till i dokumentet. |

### Anmärkningar

Läs mer om att lägga till vattenstämplar: [Lägger till vattenstämplar](https://docs.groupdocs.com/display/watermarknet/Adding+watermarks) .

### Exempel

Lägg till bild och textvattenstämpel i ett dokument av vilken typ som helst.

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

* class [Watermark](../../watermark)
* class [Watermarker](../../watermarker)
* namnutrymme [GroupDocs.Watermark](../../watermarker)
* hopsättning [GroupDocs.Watermark](../../../)

---

## Add(Watermark, WatermarkOptions) {#add_1}

Lägger till en vattenstämpel till det laddade dokumentet med vattenstämpelalternativ.

```csharp
public void Add(Watermark watermark, WatermarkOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| watermark | Watermark | Vattenstämpeln som ska läggas till i dokumentet. |
| options | WatermarkOptions | Ytterligare alternativ att använda när du lägger till vattenstämpeln. |

### Anmärkningar

Läs mer om att lägga till vattenstämplar [Lägger till vattenstämplar](https://docs.groupdocs.com/display/watermarknet/Adding+watermarks) .

### Exempel

Lägg till en bildvattenstämpel på en viss sida i ett pdf-dokument.

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

* class [Watermark](../../watermark)
* class [WatermarkOptions](../../../groupdocs.watermark.options/watermarkoptions)
* class [Watermarker](../../watermarker)
* namnutrymme [GroupDocs.Watermark](../../watermarker)
* hopsättning [GroupDocs.Watermark](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
