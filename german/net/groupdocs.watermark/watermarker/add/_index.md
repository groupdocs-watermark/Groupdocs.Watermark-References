---
title: "Add"
second_title: "GroupDocs.Watermark für .NET API-Referenz"
description: "Fügt dem geladenen Dokument ein Wasserzeichen hinzu."
type: docs
weight: 30
url: /de/net/groupdocs.watermark/watermarker/add/
---
## Add(Watermark) {#add}

Fügt dem geladenen Dokument ein Wasserzeichen hinzu.

```csharp
public AddWatermarkResult Add(Watermark watermark)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wasserzeichen | Watermark | Das Wasserzeichen, das dem Dokument hinzugefügt werden soll. |

### Hinweise

Erfahren Sie mehr über das Hinzufügen von Wasserzeichen: [Wasserzeichen hinzufügen](https://docs.groupdocs.com/display/watermarknet/Adding+watermarks).

### Beispiele

Fügen Sie einem Dokument eines beliebigen unterstützten Typs ein Bild- und Textwasserzeichen hinzu.

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

### Siehe auch

* class [AddWatermarkResult](../../../groupdocs.watermark.watermarks.results/addwatermarkresult)
* class [Watermark](../../watermark)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Add(Watermark, WatermarkOptions) {#add_1}

Fügt dem geladenen Dokument ein Wasserzeichen mithilfe von Wasserzeichen-Optionen hinzu.

```csharp
public AddWatermarkResult Add(Watermark watermark, WatermarkOptions options)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Wasserzeichen | Watermark | Das Wasserzeichen, das dem Dokument hinzugefügt werden soll. |
| Optionen | WatermarkOptions | Zusätzliche Optionen, die beim Hinzufügen des Wasserzeichens verwendet werden. |

### Hinweise

Erfahren Sie mehr über das Hinzufügen von Wasserzeichen [Adding watermarks](https://docs.groupdocs.com/display/watermarknet/Adding+watermarks).

### Beispiele

Fügen Sie ein Bildwasserzeichen zu einer bestimmten Seite eines PDF-Dokuments hinzu.

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

### Siehe auch

* class [AddWatermarkResult](../../../groupdocs.watermark.watermarks.results/addwatermarkresult)
* class [Watermark](../../watermark)
* class [WatermarkOptions](../../../groupdocs.watermark.options/watermarkoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.watermark.dll -->
