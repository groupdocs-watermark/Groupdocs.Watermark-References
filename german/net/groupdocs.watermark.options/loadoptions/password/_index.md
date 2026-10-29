---
title: "Passwort"
second_title: "GroupDocs.Watermark für .NET API-Referenz"
description: "Liest oder setzt das Passwort zum Öffnen eines verschlüsselten Dokuments."
type: docs
weight: 50
url: /de/net/groupdocs.watermark.options/loadoptions/password/
---
## LoadOptions.Password property

Liest oder setzt das Passwort zum Öffnen eines verschlüsselten Dokuments.

```csharp
public string Password { get; set; }
```

### Property Value

Das Passwort zum Öffnen eines verschlüsselten Dokuments.

### Hinweise

Das Passwort kann null oder ein leerer String sein. Der Standardwert ist null. Wenn der Inhalt nicht verschlüsselt ist, setzen Sie diesen auf null oder einen leeren String.

### Beispiele

Lädt einen mit einem Passwort geschützten Inhalt.

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

### Siehe auch

* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Watermark.Options](../../../groupdocs.watermark.options)
* assembly [GroupDocs.Watermark](../../../)

<!-- NICHT BEARBEITEN: erzeugt von xmldocmd für GroupDocs.watermark.dll -->
