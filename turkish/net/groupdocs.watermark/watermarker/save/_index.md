---
title: Save
second_title: .NET API Başvurusu için GroupDocs.Watermark
description: Belge verilerini alttaki akışa kaydeder.
type: docs
weight: 100
url: /tr/net/groupdocs.watermark/watermarker/save/
---
## Save() {#save}

Belge verilerini alttaki akışa kaydeder.

```csharp
public void Save()
```

### Notlar

Belgeleri kaydetme hakkında daha fazla bilgi edinin [Belgeleri kaydetme](https://docs.groupdocs.com/display/watermarknet/Saving+documents) .

### Örnekler

E-posta mesajı gövdesinden/konusundan belirli metin parçalarını kaldırın ve e-posta mesajını kaydedin.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\test.msg"))
{
    SearchCriteria criteria = new TextSearchCriteria("test", false);
    // Dikkat, arama yalnızca TextSearchCriteria örneğini Search yöntemine iletirseniz gerçekleştirilir
    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    // Bulunan metin parçalarını kaldır
    watermarker.Remove(watermarks);
    // Değişiklikleri Kaydet
    watermarker.Save();
}
```

### Ayrıca bakınız

* class [Watermarker](../../watermarker)
* ad alanı [GroupDocs.Watermark](../../watermarker)
* toplantı [GroupDocs.Watermark](../../../)

---

## Save(string) {#save_4}

Belgeyi belirtilen dosya konumuna kaydeder.

```csharp
public void Save(string filePath)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| filePath | String | Belge verilerinin kaydedileceği dosya yolu. |

### Notlar

Belgeleri kaydetme hakkında daha fazla bilgi edinin [Belgeleri kaydetme](https://docs.groupdocs.com/display/watermarknet/Saving+documents) .

### Örnekler

Filigranı ekleyin ve belgeyi başka bir dosyaya kaydedin.

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{                                                                                   
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);                                            
    watermarker.Save("ouput.pdf");                                   
}                                                                                   
```

### Ayrıca bakınız

* class [Watermarker](../../watermarker)
* ad alanı [GroupDocs.Watermark](../../watermarker)
* toplantı [GroupDocs.Watermark](../../../)

---

## Save(Stream) {#save_2}

Belgeyi belirtilen akışa kaydeder.

```csharp
public void Save(Stream document)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| document | Stream | Belge verilerinin kaydedileceği akış. |

### Notlar

Belgeleri kaydetme hakkında daha fazla bilgi edinin [Belgeleri kaydetme](https://docs.groupdocs.com/display/watermarknet/Saving+documents) .

### Örnekler

Filigran ekleyin ve belgeyi bellek akışına kaydedin.

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);
    using (MemoryStream stream = new MemoryStream())
    {
        watermarker.Save(stream);
        // ...
    }
}
```

### Ayrıca bakınız

* class [Watermarker](../../watermarker)
* ad alanı [GroupDocs.Watermark](../../watermarker)
* toplantı [GroupDocs.Watermark](../../../)

---

## Save(SaveOptions) {#save_1}

Belge verilerini, kaydetme seçeneklerini kullanarak alttaki akışa kaydeder.

```csharp
public void Save(SaveOptions options)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| options | SaveOptions | Bir belgeyi kaydederken kullanılacak ek seçenekler. |

### Notlar

Belgeleri kaydetme hakkında daha fazla bilgi edinin [Belgeleri kaydetme](https://docs.groupdocs.com/display/watermarknet/Saving+documents) .

### Örnekler

Filigran ekleyin ve belgeyi varsayılan olarak kaydedin[`SaveOptions`](../../../groupdocs.watermark.options/saveoptions) .

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);
    watermarker.Save(new SaveOptions());
}
```

### Ayrıca bakınız

* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* ad alanı [GroupDocs.Watermark](../../watermarker)
* toplantı [GroupDocs.Watermark](../../../)

---

## Save(string, SaveOptions) {#save_5}

Kaydetme seçeneklerini kullanarak belgeyi belirtilen dosya konumuna kaydeder.

```csharp
public void Save(string filePath, SaveOptions options)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| filePath | String | Belge verilerinin kaydedileceği dosya yolu. |
| options | SaveOptions | Bir belgeyi kaydederken kullanılacak ek seçenekler. |

### Notlar

Belgeleri kaydetme hakkında daha fazla bilgi edinin [Belgeleri kaydetme](https://docs.groupdocs.com/display/watermarknet/Saving+documents) .

### Örnekler

Filigranı ekleyin ve belgeyi varsayılan olarak başka bir dosyaya kaydedin[`SaveOptions`](../../../groupdocs.watermark.options/saveoptions) .

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{                                                                                   
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);                                            
    watermarker.Save("ouput.pdf", new SaveOptions());
}                                                                                   
```

### Ayrıca bakınız

* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* ad alanı [GroupDocs.Watermark](../../watermarker)
* toplantı [GroupDocs.Watermark](../../../)

---

## Save(Stream, SaveOptions) {#save_3}

Kaydetme seçeneklerini kullanarak belgeyi belirtilen akışa kaydeder.

```csharp
public void Save(Stream document, SaveOptions options)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| document | Stream | Belge verilerinin kaydedileceği akış. |
| options | SaveOptions | Bir belgeyi kaydederken kullanılacak ek seçenekler. |

### Notlar

Belgeleri kaydetme hakkında daha fazla bilgi edinin [Belgeleri kaydetme](https://docs.groupdocs.com/display/watermarknet/Saving+documents) .

### Örnekler

Filigran ekleyin ve belgeyi varsayılan olarak bellek akışına kaydedin[`SaveOptions`](../../../groupdocs.watermark.options/saveoptions) .

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);
    using (MemoryStream stream = new MemoryStream())
    {
        watermarker.Save(stream, new SaveOptions());
        // ...
    }
}
```

### Ayrıca bakınız

* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* ad alanı [GroupDocs.Watermark](../../watermarker)
* toplantı [GroupDocs.Watermark](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
