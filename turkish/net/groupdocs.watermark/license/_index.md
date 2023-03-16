---
title: License
second_title: .NET API Başvurusu için GroupDocs.Watermark
description: Bileşeni lisanslamak için yöntemler sağlar.
type: docs
weight: 1610
url: /tr/net/groupdocs.watermark/license/
---
## License class

Bileşeni lisanslamak için yöntemler sağlar.

```csharp
public sealed class License
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [License](license)() | Yeni bir örneğini başlatır.[`License`](../license) sınıf. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [SetLicense](../../groupdocs.watermark/license/setlicense#setlicense)(Stream) | Bileşeni lisanslar. |
| [SetLicense](../../groupdocs.watermark/license/setlicense#setlicense_1)(string) | Bileşeni lisanslar. |

### Notlar

* Lisanslama hakkında daha fazlası: [GroupDocs Lisanslama SSS](https://purchase.groupdocs.com/faqs/licensing)
* hakkında daha fazla bilgi**GroupDocs.Filigran** lisanslama: [Değerlendirme Sınırlamaları ve Lisanslama](https://docs.groupdocs.com/display/watermarknet/Evaluation+Limitations+and+Licensing)

### Örnekler

Bu örnek, lisansın yerel dosyadan nasıl kurulacağını gösterir.

```csharp
// Lisans sınıfını başlat.
License license = new License();

// .lic dosyasının yolunu ayarlayın.
license.SetLicense("C:\\GroupDocs.Watermark.lic");
```

### Ayrıca bakınız

* ad alanı [GroupDocs.Watermark](../../groupdocs.watermark)
* toplantı [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->