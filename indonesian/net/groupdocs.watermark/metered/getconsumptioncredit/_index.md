---
title: "GetConsumptionCredit"
second_title: "GroupDocs.Watermark untuk Referensi API .NET"
description: "Mengambil jumlah kredit yang digunakan."
type: docs
weight: 30
url: /id/net/groupdocs.watermark/metered/getconsumptioncredit/
---
## Metered.GetConsumptionCredit method

Mengambil jumlah kredit yang digunakan.

```csharp
public static long GetConsumptionCredit()
```

### Nilai Kembalian

Jumlah kredit yang dikonsumsi.

### Contoh

Contoh berikut menunjukkan cara mengambil jumlah kredit yang dikonsumsi.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);

decimal creditsConsumed = Metered.GetConsumptionCredit();
```

### Lihat Juga

* class [Metered](../../metered)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.watermark.dll -->
