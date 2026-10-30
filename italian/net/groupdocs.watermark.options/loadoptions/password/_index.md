---
title: "Password"
second_title: "GroupDocs.Watermark per .NET Riferimento API"
description: "Ottiene o imposta la password per aprire un documento crittografato."
type: docs
weight: 50
url: /it/net/groupdocs.watermark.options/loadoptions/password/
---
## LoadOptions.Password property

Ottiene o imposta la password per aprire un documento crittografato.

```csharp
public string Password { get; set; }
```

### Property Value

La password per aprire un documento crittografato.

### Osservazioni

La password può essere null o una stringa vuota. Il valore predefinito è null. Se il contenuto non è crittografato, impostare questo a null o a una stringa vuota.

### Esempi

Carica un contenuto protetto da password.

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

### Vedi anche

* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Watermark.Options](../../../groupdocs.watermark.options)
* assembly [GroupDocs.Watermark](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.watermark.dll -->
