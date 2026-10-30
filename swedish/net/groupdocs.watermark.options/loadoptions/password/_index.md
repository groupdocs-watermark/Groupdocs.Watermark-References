---
title: "Password"
second_title: "GroupDocs.Watermark för .NET API-referens"
description: "Hämtar eller anger lösenordet för att öppna ett krypterat dokument."
type: docs
weight: 50
url: /sv/net/groupdocs.watermark.options/loadoptions/password/
---
## LoadOptions.Password property

Hämtar eller anger lösenordet för att öppna ett krypterat dokument.

```csharp
public string Password { get; set; }
```

### Property Value

Lösenordet för att öppna ett krypterat dokument.

### Anmärkningar

Lösenordet kan vara null eller en tom sträng. Standardvärdet är null. Om innehållet inte är krypterat, sätt detta till null eller en tom sträng.

### Exempel

Läs in innehåll som är skyddat med ett lösenord.

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

### Se även

* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Watermark.Options](../../../groupdocs.watermark.options)
* assembly [GroupDocs.Watermark](../../../)

<!-- FÅR INTE REDIGERAS: genererad av xmldocmd för GroupDocs.watermark.dll -->
