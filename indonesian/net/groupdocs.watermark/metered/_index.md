---
title: "Metered"
second_title: "GroupDocs.Watermark untuk Referensi API .NET"
description: "Menyediakan metode untuk melisensikan komponen dengan lisensi Metered."
type: docs
weight: 1690
url: /id/net/groupdocs.watermark/metered/
---
## Metered class

Menyediakan metode untuk melisensikan komponen dengan lisensi Metered.

```csharp
public class Metered
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [Metered](metered)() | Menginisialisasi instance baru dari kelas [`Metered`](../metered) class. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [SetMeteredKey](../../groupdocs.watermark/metered/setmeteredkey)(string, string) | Mengaktifkan produk dengan kunci Metered. |
| static [GetConsumptionCredit](../../groupdocs.watermark/metered/getconsumptioncredit)() | Mengambil jumlah kredit yang digunakan. |
| static [GetConsumptionQuantity](../../groupdocs.watermark/metered/getconsumptionquantity)() | Mengambil jumlah MB yang diproses. |

### Catatan

**Learn more**

* More about Metered licensing: [Metered Licensing FAQ](https://purchase.groupdocs.com/faqs/licensing/metered)
* More about **GroupDocs.Watermark** licensing: [Evaluation Limitations and Licensing](https://docs.groupdocs.com/display/watermarknet/Evaluation+Limitations+and+Licensing)

### Contoh

Contoh berikut menunjukkan cara mengaktifkan produk dengan kunci Metered.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);
```

### Lihat Juga

* namespace [GroupDocs.Watermark](../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.watermark.dll -->
