---
title: "GetConsumptionQuantity"
second_title: "GroupDocs.Watermark untuk Referensi API .NET"
description: "Mengambil jumlah MB yang diproses."
type: docs
weight: 40
url: /id/net/groupdocs.watermark/metered/getconsumptionquantity/
---
## Metered.GetConsumptionQuantity method

Mengambil jumlah MB yang diproses.

```csharp
public static decimal GetConsumptionQuantity()
```

### Nilai Kembalian

Jumlah MB yang diproses.

### Contoh

Contoh berikut menunjukkan cara mengambil jumlah MB yang diproses.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);

decimal mbProcessed = Metered.GetConsumptionQuantity();
```

### Lihat Juga

* class [Metered](../../metered)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.watermark.dll -->
