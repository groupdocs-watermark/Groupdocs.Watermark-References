---
title: "GeneratePreview"
second_title: "GroupDocs.Watermark für .NET API-Referenz"
description: "Erstellt Vorschaubilder für das Dokument."
type: docs
weight: 50
url: /de/net/groupdocs.watermark/watermarker/generatepreview/
---
## Watermarker.GeneratePreview method

Erstellt Vorschaubilder für das Dokument.

```csharp
public void GeneratePreview(PreviewOptions previewOptions)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| previewOptions | PreviewOptions | Zusätzliche Optionen, die beim Erzeugen von Vorschaubildern verwendet werden können. |

### Beispiele

Vorschaubild für die erste Seite des Word-Dokuments erzeugen.

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

### Siehe auch

* class [PreviewOptions](../../../groupdocs.watermark.options/previewoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.watermark.dll -->
