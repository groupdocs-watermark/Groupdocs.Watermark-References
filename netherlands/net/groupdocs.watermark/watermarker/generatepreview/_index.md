---
title: "GeneratePreview"
second_title: "GroupDocs.Watermark voor .NET API-referentie"
description: "Genereert voorbeeldafbeeldingen voor het document."
type: docs
weight: 50
url: /nl/net/groupdocs.watermark/watermarker/generatepreview/
---
## Watermarker.GeneratePreview method

Genereert voorbeeldafbeeldingen voor het document.

```csharp
public void GeneratePreview(PreviewOptions previewOptions)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| previewOptions | PreviewOptions | Aanvullende opties om te gebruiken bij het genereren van voorbeeldafbeeldingen. |

### Voorbeelden

Genereer voorbeeldafbeelding voor de eerste pagina van een Word-document.

```csharp
CreatePageStream createPageStreamDelegate = delegate(int number)
                                            {
                                                string previewImageFileName = string.Format("page{0}.png", number);
                                                return File.OpenWrite(previewImageFileName);
                                            };
ReleasePageStream releasePageStreamDelegate = delegate(int number, Stream stream)
                                              {
                                                  stream.Close();
                                              };
PreviewOptions previewOptions = new PreviewOptions(createPageStreamDelegate, releasePageStreamDelegate)
                                {
                                    PreviewFormat = PreviewOptions.PreviewFormats.PNG,
                                    PageNumbers = new []{1}
                                };

using (Watermarker watermarker = new Watermarker(@"C:\Documents\test.docx"))
{
    watermarker.GeneratePreview(previewOptions);
}
```

### Zie ook

* class [PreviewOptions](../../../groupdocs.watermark.options/previewoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.watermark.dll -->
