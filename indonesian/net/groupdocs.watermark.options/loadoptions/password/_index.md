---
title: "Kata Sandi"
second_title: "GroupDocs.Watermark untuk Referensi API .NET"
description: "Mendapatkan atau mengatur kata sandi untuk membuka dokumen terenkripsi."
type: docs
weight: 50
url: /id/net/groupdocs.watermark.options/loadoptions/password/
---
## LoadOptions.Password property

Mendapatkan atau mengatur kata sandi untuk membuka dokumen terenkripsi.

```csharp
public string Password { get; set; }
```

### Property Value

Kata sandi untuk membuka dokumen terenkripsi.

### Catatan

Kata sandi boleh null atau string kosong. Nilai default adalah null. Jika konten tidak terenkripsi, atur ini menjadi null atau string kosong.

### Contoh

Muat konten yang dilindungi dengan kata sandi.

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

### Lihat Juga

* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Watermark.Options](../../../groupdocs.watermark.options)
* assembly [GroupDocs.Watermark](../../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.watermark.dll -->
