---
title: "GeneratePreview"
second_title: "GroupDocs.Watermark per .NET Riferimento API"
description: "Genera immagini di anteprima per il documento."
type: docs
weight: 50
url: /it/net/groupdocs.watermark/watermarker/generatepreview/
---
## Watermarker.GeneratePreview method

Genera immagini di anteprima per il documento.

```csharp
public void GeneratePreview(PreviewOptions previewOptions)
```

| Parametro | Type | Descrizione |
| --- | --- | --- |
| previewOptions | PreviewOptions | Opzioni aggiuntive da utilizzare durante la generazione delle immagini di anteprima. |

### Esempi

Genera l'immagine di anteprima per la prima pagina del documento Word.

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

### Vedi anche

* class [PreviewOptions](../../../groupdocs.watermark.options/previewoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.watermark.dll -->
