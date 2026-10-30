---
title: "Wachtwoord"
second_title: "GroupDocs.Watermark voor .NET API-referentie"
description: "Haalt of stelt het wachtwoord in voor het openen van een versleuteld document."
type: docs
weight: 50
url: /nl/net/groupdocs.watermark.options/loadoptions/password/
---
## LoadOptions.Password property

Haalt of stelt het wachtwoord in voor het openen van een versleuteld document.

```csharp
public string Password { get; set; }
```

### Property Value

Het wachtwoord voor het openen van een versleuteld document.

### Opmerkingen

Het wachtwoord mag null of een lege string zijn. De standaardwaarde is null. Als de inhoud niet versleuteld is, stel dit in op null of een lege string.

### Voorbeelden

Laad een inhoud die met een wachtwoord beschermd is.

```csharp
LoadOptions loadOptions = new LoadOptions
{
    Password = "pwd123"
};
using (Watermarker watermarker = new Watermarker(@"D:\doc.vsdx", loadOptions))
{
    // ...
}
```

### Zie ook

* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Watermark.Options](../../../groupdocs.watermark.options)
* assembly [GroupDocs.Watermark](../../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.watermark.dll -->
