---
title: "Add"
second_title: "GroupDocs.Watermark pour .NET Référence de l'API"
description: "Ajoute un filigrane au document chargé."
type: docs
weight: 30
url: /fr/net/groupdocs.watermark/watermarker/add/
---
## Add(Watermark) {#add}

Ajoute un filigrane au document chargé.

```csharp
public AddWatermarkResult Add(Watermark watermark)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| watermark | Watermark | Le filigrane à ajouter au document. |

### Remarques

En savoir plus sur l'ajout de filigranes : [Ajout de filigranes](https://docs.groupdocs.com/display/watermarknet/Adding+watermarks).

### Exemples

Ajoutez un filigrane d'image et de texte à un document de tout type pris en charge.

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

### Voir aussi

* class [AddWatermarkResult](../../../groupdocs.watermark.watermarks.results/addwatermarkresult)
* class [Watermark](../../watermark)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Add(Watermark, WatermarkOptions) {#add_1}

Ajoute un filigrane au document chargé en utilisant les options de filigrane.

```csharp
public AddWatermarkResult Add(Watermark watermark, WatermarkOptions options)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| watermark | Watermark | Le filigrane à ajouter au document. |
| options | WatermarkOptions | Options supplémentaires à utiliser lors de l'ajout du filigrane. |

### Remarques

En savoir plus sur l'ajout de filigranes [Adding watermarks](https://docs.groupdocs.com/display/watermarknet/Adding+watermarks).

### Exemples

Ajoutez un filigrane image à une page particulière d'un document pdf.

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

### Voir aussi

* class [AddWatermarkResult](../../../groupdocs.watermark.watermarks.results/addwatermarkresult)
* class [Watermark](../../watermark)
* class [WatermarkOptions](../../../groupdocs.watermark.options/watermarkoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.watermark.dll -->
