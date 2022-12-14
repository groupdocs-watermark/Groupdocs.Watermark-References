---
title: WordProcessingWatermarkPagesOptions
second_title: .NET API Başvurusu için GroupDocs.Watermark
description: Word belgesi sayfalarına filigran eklerken seçenekleri temsil eder.
type: docs
weight: 2370
url: /tr/net/groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkpagesoptions/
---
## WordProcessingWatermarkPagesOptions class

Word belgesi sayfalarına filigran eklerken seçenekleri temsil eder.

```csharp
public sealed class WordProcessingWatermarkPagesOptions : WordProcessingWatermarkBaseOptions
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [WordProcessingWatermarkPagesOptions](wordprocessingwatermarkpagesoptions)() | Yeni bir örneğini başlatır.[`WordProcessingWatermarkPagesOptions`](../wordprocessingwatermarkpagesoptions) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [AlternativeText](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/alternativetext) { get; set; } | Bir şekille ilişkilendirilecek açıklayıcı (alternatif) metni alır veya ayarlar. |
| [Effects](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/effects) { get; set; } | Şunun değerini alır veya ayarlar:[`WordProcessingImageEffects`](../wordprocessingimageeffects) or [`WordProcessingTextEffects`](../wordprocessingtexteffects) filigrana uygulanması gereken efektler için. |
| [IsLocked](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/islocked) { get; set; } | Word'de şeklin düzenlenmesinin yasak olup olmadığını gösteren bir değer alır veya ayarlar. |
| [LockType](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/locktype) { get; set; } | Filigran kilit türünü alır veya ayarlar. |
| [Name](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/name) { get; set; } | Bir şeklin adını alır veya ayarlar. |
| [PageNumbers](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkpagesoptions/pagenumbers) { get; set; } | Filigranı eklemek için sayfa numaralarını alır veya ayarlar. |
| [Password](../../groupdocs.watermark.options.wordprocessing/wordprocessingwatermarkbaseoptions/password) { get; set; } | Filigranı kilitlemek için kullanılan parolayı alır veya ayarlar. |

### Notlar

**Daha fazla bilgi edin:**

* [Kelime işlem belgelerine filigran ekleme](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+word+processing+documents)

### Örnekler

Bir Word belgesinin belirli bir sayfasına filigran ekleyin.

```csharp
WordProcessingLoadOptions loadOptions = new WordProcessingLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\test.doc", loadOptions))
{
    TextWatermark watermark = new TextWatermark("text", new Font("Arial", 42));

    WordProcessingWatermarkPagesOptions options = new WordProcessingWatermarkPagesOptions();
    options.PageNumbers = new[] { 1 };

    watermarker.Add(watermark, options);
    watermarker.Save();
}
```

### Ayrıca bakınız

* class [WordProcessingWatermarkBaseOptions](../wordprocessingwatermarkbaseoptions)
* ad alanı [GroupDocs.Watermark.Options.WordProcessing](../../groupdocs.watermark.options.wordprocessing)
* toplantı [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
