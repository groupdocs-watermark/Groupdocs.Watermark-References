---
title: WordProcessingContent
second_title: .NET API Başvurusu için GroupDocs.Watermark
description: Filigranın yerleştirilmesi gereken Word belgesini doc docx vb. temsil eden sınıf.
type: docs
weight: 1280
url: /tr/net/groupdocs.watermark.contents.wordprocessing/wordprocessingcontent/
---
## WordProcessingContent class

Filigranın yerleştirilmesi gereken Word belgesini (doc, docx vb.) temsil eden sınıf.

```csharp
public class WordProcessingContent : Content
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [PageCount](../../groupdocs.watermark.contents.wordprocessing/wordprocessingcontent/pagecount) { get; } | Belgedeki sayfa sayısını alır. |
| [Sections](../../groupdocs.watermark.contents.wordprocessing/wordprocessingcontent/sections) { get; } | Bunun tüm bölümlerinin koleksiyonunu alır[`WordProcessingContent`](../wordprocessingcontent) . |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [Decrypt](../../groupdocs.watermark.contents.wordprocessing/wordprocessingcontent/decrypt)() | Belgenin şifresini çözer. |
| [Dispose](../../groupdocs.watermark.contents/content/dispose)() | Geçerli örneği ortadan kaldırır. |
| [Encrypt](../../groupdocs.watermark.contents.wordprocessing/wordprocessingcontent/encrypt)(string) | Belgeyi şifreler. |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)() | İçerikteki tüm resimleri bulur. Arama, belirtilen nesnelerde gerçekleştirilir.[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) . |
| [FindImages](../../groupdocs.watermark.contents/contentpart/findimages)(ImageSearchCriteria) | Belirtilen arama kriterlerine göre görüntüleri bulur. Arama, belirtilen nesnelerde gerçekleştirilir.[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) . |
| [Protect](../../groupdocs.watermark.contents.wordprocessing/wordprocessingcontent/protect)(WordProcessingProtectionType, string) | Belgeyi değişikliklerden korur ve bir koruma parolası ayarlar. |
| [Search](../../groupdocs.watermark.contents/contentpart/search)() | İçerikteki tüm olası filigranları bulur. Arama, belirtilen nesnelerde gerçekleştirilir.[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) . |
| [Search](../../groupdocs.watermark.contents/contentpart/search)(SearchCriteria) | Belirtilen arama kriterlerine göre olası filigranları bulur. Arama, belirtilen nesnelerde gerçekleştirilir.[`SearchableObjects`](../../groupdocs.watermark/watermarker/searchableobjects) . |
| [Unprotect](../../groupdocs.watermark.contents.wordprocessing/wordprocessingcontent/unprotect)() | Paroladan bağımsız olarak belgedeki korumayı kaldırır. |

### Notlar

**Daha fazla bilgi edin:**

* [Kelime işlem belgelerine filigran ekleme](https://docs.groupdocs.com/display/watermarknet/Add+watermarks+to+word+processing+documents)
* [Kelime işlem belgesindeki mevcut nesneler](https://docs.groupdocs.com/display/watermarknet/Existing+objects+in+word+processing+document)
* [Kelime işlem belgesinde filigranı kilitleme](https://docs.groupdocs.com/display/watermarknet/Locking+watermark+in+word+processing+document)
* [Kelime işlem belgelerini koruma](https://docs.groupdocs.com/display/watermarknet/Protecting+word+processing+documents)
* [Kelime işlem belgesindeki filigranlar](https://docs.groupdocs.com/display/watermarknet/Watermarks+in+word+processing+document)

### Örnekler

Desteklenen herhangi bir türde Word belgesi yükleyin ve kaydedin.

```csharp
WordProcessingLoadOptions loadOptions = new WordProcessingLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\input.doc", loadOptions))
{
    // Belirli bir bölüme veya tüm bölümlere filigran eklemek için Add yöntemini kullanın.

    // Değişiklikleri Kaydet.
    watermarker.Save(@"D:\output.doc");
}
```

### Ayrıca bakınız

* class [Content](../../groupdocs.watermark.contents/content)
* ad alanı [GroupDocs.Watermark.Contents.WordProcessing](../../groupdocs.watermark.contents.wordprocessing)
* toplantı [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->