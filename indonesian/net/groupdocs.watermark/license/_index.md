---
title: "License"
second_title: "GroupDocs.Watermark untuk Referensi API .NET"
description: "Menyediakan metode untuk melisensikan komponen."
type: docs
weight: 1680
url: /id/net/groupdocs.watermark/license/
---
## License class

Menyediakan metode untuk melisensikan komponen.

```csharp
public sealed class License
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [License](license)() | Menginisialisasi instance baru dari kelas [`License`](../license). |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [SetLicense](../../groupdocs.watermark/license/setlicense#setlicense)(Stream) | Melakukan lisensi pada komponen. |
| [SetLicense](../../groupdocs.watermark/license/setlicense#setlicense_1)(string) | Melakukan lisensi pada komponen. |

### Catatan

* More about licensing: [GroupDocs Licensing FAQ](https://purchase.groupdocs.com/faqs/licensing)
* More about **GroupDocs.Watermark** licensing: [Evaluation Limitations and Licensing](https://docs.groupdocs.com/display/watermarknet/Evaluation+Limitations+and+Licensing)

### Contoh

Contoh ini menunjukkan cara menyiapkan lisensi dari file lokal.

```csharp
// Inisialisasi kelas License.
License license = new License();

// Tetapkan jalur ke file .lic.
license.SetLicense("C:\\GroupDocs.Watermark.lic");
```

### Lihat Juga

* namespace [GroupDocs.Watermark](../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.watermark.dll -->
