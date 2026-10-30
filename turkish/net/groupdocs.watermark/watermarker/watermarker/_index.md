---
title: "Watermarker"
second_title: "GroupDocs.Watermark for .NET API Referansı"
description: "Belirtilen belge yolu ile [`Watermarker`](../../watermarker) sınıfının yeni bir örneğini başlatır."
type: docs
weight: 10
url: /tr/net/groupdocs.watermark/watermarker/watermarker/
---
## Watermarker(string) {#constructor_4}

Belgeyi yüklemek için dosya yolu.

```csharp
public Watermarker(string filePath)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| filePath | String | Sağlanan belge türü desteklenmiyor. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Sağlanan şifre yanlış. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Belgeleri yükleme hakkında daha fazla bilgi edinin: [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents). |

### Açıklamalar

Belgeyi kaydedin.

### Örnekler

Desteklenen herhangi bir formatta içeriği yükler ve kaydeder.

```csharp
// Bir dosyadan içeriği yükler.
using (Watermarker watermarker = new Watermarker("D:\\input.pdf"))
{
    // Filigran eklemek, aramak veya kaldırmak için Watermarker sınıfının yöntemlerini kullanın.

    // Belirtilen belge yolu ve yükleme seçenekleri ile [`Watermarker`](../../watermarker) sınıfının yeni bir örneğini başlatır.
    watermarker.Save("D:\\output.pdf");
}
```

### Ayrıca Bakınız

* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(string, LoadOptions) {#constructor_5}

Belgeyi yüklemek için dosya yolu.

```csharp
public Watermarker(string filePath, LoadOptions options)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| filePath | String | Bir belgeyi yüklerken kullanılacak ek seçenekler. |
| seçenekler | LoadOptions | Şifre kullanarak şifreli PDF belgesini yükleyin. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Sağlanan şifre yanlış. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Belgeleri yükleme hakkında daha fazla bilgi edinin: [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents). |

### Açıklamalar

Belgeyi kaydedin.

### Örnekler

Belirtilen belge yolu ve ayarlarla [`Watermarker`](../../watermarker) sınıfının yeni bir örneğini başlatır.

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
loadOptions.Password = "123";
using (Watermarker watermarker = new Watermarker(@"C:\Documents\test.pdf", loadOptions))
{
    // ...
}
```

### Ayrıca Bakınız

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(string, WatermarkerSettings) {#constructor_7}

ayarlar

```csharp
public Watermarker(string filePath, WatermarkerSettings settings)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| filePath | String | Bir belgeyi yüklerken kullanılacak ek seçenekler. |
| Aranabilir nesneleri küresel olarak ayarlayın (ondan sonra yüklenecek tüm belgeler için). | WatermarkerSettings | Yüklenmiş belgeyle çalışırken kullanılacak ek ayarlar. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Sağlanan şifre yanlış. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Belgeleri yükleme hakkında daha fazla bilgi edinin: [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents). |

### Açıklamalar

Belgeyi kaydedin.

### Örnekler

Bulunan filigranlarla çalışmak için kod burada yer alır.

```csharp
WatermarkerSettings settings = new WatermarkerSettings();
settings.SearchableObjects = new SearchableObjects
{
    WordProcessingSearchableObjects = WordProcessingSearchableObjects.Hyperlinks
                                    | WordProcessingSearchableObjects.Text,
    SpreadsheetSearchableObjects = SpreadsheetSearchableObjects.HeadersFooters,
    PresentationSearchableObjects = PresentationSearchableObjects.SlidesBackgrounds
                                  | PresentationSearchableObjects.Shapes,
    DiagramSearchableObjects = DiagramSearchableObjects.None,
    PdfSearchableObjects = PdfSearchableObjects.All
};

foreach (string file in Directory.GetFiles(@"D:\files"))
{
    using (Watermarker watermarker = new Watermarker(file, settings))
    {
        PossibleWatermarkCollection watermarks = watermarker.Search();

        // Belirtilen belge yolu, yükleme seçenekleri ve ayarlarla [`Watermarker`](../../watermarker) sınıfının yeni bir örneğini başlatır.
    }
}
```

### Ayrıca Bakınız

* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(string, LoadOptions, WatermarkerSettings) {#constructor_6}

E-posta mesajının gövdesinde/konusunda belirli metin parçacıklarını bulun.

```csharp
public Watermarker(string filePath, LoadOptions options, WatermarkerSettings settings)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| filePath | String | Bir belgeyi yüklerken kullanılacak ek seçenekler. |
| seçenekler | LoadOptions | Şifre kullanarak şifreli PDF belgesini yükleyin. |
| Aranabilir nesneleri küresel olarak ayarlayın (ondan sonra yüklenecek tüm belgeler için). | WatermarkerSettings | Yüklenmiş belgeyle çalışırken kullanılacak ek ayarlar. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Sağlanan şifre yanlış. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Belgeleri yükleme hakkında daha fazla bilgi edinin: [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents). |

### Açıklamalar

Belgeyi kaydedin.

### Örnekler

E-posta mesajının gövdesinde/konusunda belirli metin parçacıklarını bulun.

```csharp
WatermarkerSettings settings = new WatermarkerSettings();
settings.SearchableObjects = new SearchableObjects
{
    EmailSearchableObjects = EmailSearchableObjects.Subject
                           | EmailSearchableObjects.HtmlBody
                           | EmailSearchableObjects.PlainTextBody
};
EmailLoadOptions loadOptions = new EmailLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\test.msg", loadOptions, settings))
{
    SearchCriteria criteria = new TextSearchCriteria("test", false);
    // Not, arama yalnızca TextSearchCriteria örneğini Search metoduna geçirirseniz gerçekleştirilir.
    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    // Bulunan metin parçacıklarını kaldır
    watermarks.Clear();
    // Değişiklikleri kaydet
    watermarker.Save();
}
```

### Ayrıca Bakınız

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream) {#constructor}

Belirtilen akış ile [`Watermarker`](../../watermarker) sınıfının yeni bir örneğini başlatır.

```csharp
public Watermarker(Stream document)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| belge | Stream | Belgeyi yüklemek için kullanılan akış. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Sağlanan şifre yanlış. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Belgeleri yükleme hakkında daha fazla bilgi edinin: [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents). |

### Açıklamalar

Belgeleri yükleme hakkında daha fazla bilgi edinin [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### Örnekler

Desteklenen herhangi bir formatta belgeyi yükleyin ve kaydedin.

```csharp
// Bir akıştan içerik yükleyin.
using (FileStream inputStream = File.Open("D:\\input.pdf", FileMode.Open))
using (FileStream outputStream = File.Open("D:\\output.pdf", FileMode.Create))
using (Watermarker watermarker = new Watermarker(inputStream))
{
    // Filigran eklemek, aramak veya kaldırmak için Watermarker sınıfının yöntemlerini kullanın.

    // Değişiklikleri kaydet.
    watermarker.Save(outputStream);
}
```

### Ayrıca Bakınız

* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, LoadOptions) {#constructor_1}

Belirtilen akış ve yükleme seçenekleri ile [`Watermarker`](../../watermarker) sınıfının yeni bir örneğini başlatır.

```csharp
public Watermarker(Stream document, LoadOptions options)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| belge | Stream | Belgeyi yüklemek için kullanılan akış. |
| seçenekler | LoadOptions | Şifre kullanarak şifreli PDF belgesini yükleyin. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Sağlanan şifre yanlış. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Belgeleri yükleme hakkında daha fazla bilgi edinin: [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents). |

### Açıklamalar

Belgeleri yükleme hakkında daha fazla bilgi edinin [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### Örnekler

Şifreyle korunan PDF belgesini şifre kullanarak yükle

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
loadOptions.Password = "123";
using (FileStream fileStream = File.Open(@"C:\Documents\test.pdf", FileMode.Open))
using (Watermarker watermarker = new Watermarker(fileStream, loadOptions))
{
    // ...
}
```

### Ayrıca Bakınız

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, WatermarkerSettings) {#constructor_3}

Belirtilen akış ve ayarlarla [`Watermarker`](../../watermarker) sınıfının yeni bir örneğini başlatır.

```csharp
public Watermarker(Stream document, WatermarkerSettings settings)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| belge | Stream | Belgeyi yüklemek için kullanılan akış. |
| Aranabilir nesneleri küresel olarak ayarlayın (ondan sonra yüklenecek tüm belgeler için). | WatermarkerSettings | Yüklenmiş belgeyle çalışırken kullanılacak ek ayarlar. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Sağlanan şifre yanlış. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Belgeleri yükleme hakkında daha fazla bilgi edinin: [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents). |

### Açıklamalar

Belgeleri yükleme hakkında daha fazla bilgi edinin [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### Örnekler

Bulunan filigranlarla çalışmak için kod burada yer alır.

```csharp
WatermarkerSettings settings = new WatermarkerSettings();
settings.SearchableObjects = new SearchableObjects
{
    WordProcessingSearchableObjects = WordProcessingSearchableObjects.Hyperlinks
                                    | WordProcessingSearchableObjects.Text,
    SpreadsheetSearchableObjects = SpreadsheetSearchableObjects.HeadersFooters,
    PresentationSearchableObjects = PresentationSearchableObjects.SlidesBackgrounds
                                  | PresentationSearchableObjects.Shapes,
    DiagramSearchableObjects = DiagramSearchableObjects.None,
    PdfSearchableObjects = PdfSearchableObjects.All
};

foreach (string file in Directory.GetFiles(@"D:\files"))
{
    using (FileStream fileStream = File.Open(file, FileMode.Open))
    using (Watermarker watermarker = new Watermarker(fileStream, settings))
    {
        PossibleWatermarkCollection watermarks = watermarker.Search();

        // Belirtilen belge yolu, yükleme seçenekleri ve ayarlarla [`Watermarker`](../../watermarker) sınıfının yeni bir örneğini başlatır.
    }
}
```

### Ayrıca Bakınız

* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, LoadOptions, WatermarkerSettings) {#constructor_2}

Belirtilen akış, yükleme seçenekleri ve ayarlarla [`Watermarker`](../../watermarker) sınıfının yeni bir örneğini başlatır.

```csharp
public Watermarker(Stream document, LoadOptions options, WatermarkerSettings settings)
```

| Parametre | Type | Açıklama |
| --- | --- | --- |
| belge | Stream | Belgeyi yüklemek için kullanılan akış. |
| seçenekler | LoadOptions | Şifre kullanarak şifreli PDF belgesini yükleyin. |
| Aranabilir nesneleri küresel olarak ayarlayın (ondan sonra yüklenecek tüm belgeler için). | WatermarkerSettings | Yüklenmiş belgeyle çalışırken kullanılacak ek ayarlar. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Sağlanan şifre yanlış. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Belgeleri yükleme hakkında daha fazla bilgi edinin: [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents). |

### Açıklamalar

Belgeleri yükleme hakkında daha fazla bilgi edinin [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### Örnekler

E-posta mesajının gövdesinde/konusunda belirli metin parçacıklarını bulun.

```csharp
WatermarkerSettings settings = new WatermarkerSettings();
settings.SearchableObjects = new SearchableObjects
{
    EmailSearchableObjects = EmailSearchableObjects.Subject
                           | EmailSearchableObjects.HtmlBody
                           | EmailSearchableObjects.PlainTextBody
};
EmailLoadOptions loadOptions = new EmailLoadOptions();
using (FileStream fileStream = File.Open(@"D:\test.msg", FileMode.Open))
using (Watermarker watermarker = new Watermarker(fileStream, loadOptions, settings))
{
    SearchCriteria criteria = new TextSearchCriteria("test", false);
    // Not, arama yalnızca TextSearchCriteria örneğini Search metoduna geçirirseniz gerçekleştirilir.
    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    // Bulunan metin parçacıklarını kaldır
    watermarks.Clear();
    // Değişiklikleri kaydet
    watermarker.Save();
}
```

### Ayrıca Bakınız

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.watermark.dll -->
