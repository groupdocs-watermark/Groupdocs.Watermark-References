---
title: "Kaydet"
second_title: "GroupDocs.Watermark for .NET API Referansı"
description: "Belge verilerini temel akışa kaydeder."
type: docs
weight: 100
url: /tr/net/groupdocs.watermark/watermarker/save/
---
## Save() {#save}

Belge verilerini temel akışa kaydeder.

```csharp
public WatermarkResult Save()
```

### Açıklamalar

Belgeleri kaydetme hakkında daha fazla bilgi edinin [Saving documents](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### Örnekler

E-posta mesajının gövde/konu kısmındaki belirli metin parçacıklarını kaldırın ve e-posta mesajını kaydedin.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\test.msg"))
{
    SearchCriteria criteria = new TextSearchCriteria("test", false);
    // Not, arama yalnızca TextSearchCriteria örneğini Search metoduna geçirirseniz gerçekleştirilir.
    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    // Bulunan metin parçacıklarını kaldır
    watermarker.Remove(watermarks);
    // Değişiklikleri kaydet
    watermarker.Save();
}
```

### Ayrıca Bakınız

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Save(string) {#save_4}

Belgeyi belirtilen dosya konumuna kaydeder.

```csharp
public WatermarkResult Save(string filePath)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| filePath | String | Belge verilerinin kaydedileceği dosya yolu. |

### Açıklamalar

Belgeleri kaydetme hakkında daha fazla bilgi edinin [Saving documents](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

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

### Ayrıca Bakınız

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Save(Stream) {#save_2}

Belgeyi belirtilen akışa kaydeder.

```csharp
public WatermarkResult Save(Stream document)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| belge | Stream | Belge verilerinin kaydedileceği akış. |

### Açıklamalar

Belgeleri kaydetme hakkında daha fazla bilgi edinin [Saving documents](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### Örnekler

Filigranı ekleyin ve belgeyi bellek akışına kaydedin.

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

### Ayrıca Bakınız

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Save(SaveOptions) {#save_1}

Belge verilerini kaydetme seçeneklerini kullanarak temel akışa kaydeder.

```csharp
public WatermarkResult Save(SaveOptions options)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| seçenekler | SaveOptions | Bir belgeyi kaydederken kullanılacak ek seçenekler. |

### Açıklamalar

Belgeleri kaydetme hakkında daha fazla bilgi edinin [Saving documents](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### Örnekler

Varsayılan [`SaveOptions`](../../../groupdocs.watermark.options/saveoptions) ile filigran ekleyin ve belgeyi kaydedin.

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);
    watermarker.Save(new SaveOptions());
}
```

### Ayrıca Bakınız

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Save(string, SaveOptions) {#save_5}

Belirtilen dosya konumuna, kaydetme seçeneklerini kullanarak belgeyi kaydeder.

```csharp
public WatermarkResult Save(string filePath, SaveOptions options)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| filePath | String | Belge verilerinin kaydedileceği dosya yolu. |
| seçenekler | SaveOptions | Bir belgeyi kaydederken kullanılacak ek seçenekler. |

### Açıklamalar

Belgeleri kaydetme hakkında daha fazla bilgi edinin [Saving documents](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### Örnekler

Filigranı ekleyin ve belgeyi varsayılan [`SaveOptions`](../../../groupdocs.watermark.options/saveoptions) ile başka bir dosyaya kaydedin.

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{                                                                                   
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);                                            
    watermarker.Save("ouput.pdf", new SaveOptions());
}                                                                                   
```

### Ayrıca Bakınız

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Save(Stream, SaveOptions) {#save_3}

Belgeyi belirtilen akışa kaydetme seçeneklerini kullanarak kaydeder.

```csharp
public WatermarkResult Save(Stream document, SaveOptions options)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| belge | Stream | Belge verilerinin kaydedileceği akış. |
| seçenekler | SaveOptions | Bir belgeyi kaydederken kullanılacak ek seçenekler. |

### Açıklamalar

Belgeleri kaydetme hakkında daha fazla bilgi edinin [Saving documents](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### Örnekler

Filigran ekleyin ve belgeyi varsayılan [`SaveOptions`](../../../groupdocs.watermark.options/saveoptions) ile bellek akışına kaydedin.

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

### Ayrıca Bakınız

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.watermark.dll -->
