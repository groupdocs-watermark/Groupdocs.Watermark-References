---
title: SpreadsheetPreviewOptions
second_title: Referencia de API de GroupDocs.Watermark para .NET
description: Inicializa una nueva instancia delSpreadsheetPreviewOptionsgroupdocs.watermark.options.spreadsheet/spreadsheetpreviewoptions clase que hace que se cierre el flujo de salida.
type: docs
weight: 10
url: /es/net/groupdocs.watermark.options.spreadsheet/spreadsheetpreviewoptions/spreadsheetpreviewoptions/
---
## SpreadsheetPreviewOptions(CreatePageStream) {#constructor}

Inicializa una nueva instancia del[`SpreadsheetPreviewOptions`](../../spreadsheetpreviewoptions) clase que hace que se cierre el flujo de salida.

```csharp
public SpreadsheetPreviewOptions(CreatePageStream createPageStream)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| createPageStream | CreatePageStream | Crea una secuencia para una vista previa de página específica. |

### Ver también

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* class [SpreadsheetPreviewOptions](../../spreadsheetpreviewoptions)
* espacio de nombres [GroupDocs.Watermark.Options.Spreadsheet](../../spreadsheetpreviewoptions)
* asamblea [GroupDocs.Watermark](../../../)

---

## SpreadsheetPreviewOptions(CreatePageStream, ReleasePageStream) {#constructor_1}

Inicializa una nueva instancia de[`SpreadsheetPreviewOptions`](../../spreadsheetpreviewoptions) clase que hace que el flujo de salida se devuelva al cliente para su uso posterior.

```csharp
public SpreadsheetPreviewOptions(CreatePageStream createPageStream, 
    ReleasePageStream releasePageStream)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| createPageStream | CreatePageStream | Crea una secuencia para una vista previa de página específica. |
| releasePageStream | ReleasePageStream | Notifica que la generación de la vista previa de la página ha finalizado y obtiene el flujo de salida. |

### Ver también

* delegate [CreatePageStream](../../../groupdocs.watermark.options/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.watermark.options/releasepagestream)
* class [SpreadsheetPreviewOptions](../../spreadsheetpreviewoptions)
* espacio de nombres [GroupDocs.Watermark.Options.Spreadsheet](../../spreadsheetpreviewoptions)
* asamblea [GroupDocs.Watermark](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->