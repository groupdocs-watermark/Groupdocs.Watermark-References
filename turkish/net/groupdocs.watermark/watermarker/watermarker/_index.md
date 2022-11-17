---
title: Watermarker
second_title: .NET API Başvurusu için GroupDocs.Watermark
description: Yeni bir örneğini başlatır.Watermarkergroupdocs.watermark/watermarker belirtilen belge yoluna sahip sınıf.
type: docs
weight: 10
url: /tr/net/groupdocs.watermark/watermarker/watermarker/
---
## Watermarker(string) {#constructor_4}

Yeni bir örneğini başlatır.[`Watermarker`](../../watermarker) belirtilen belge yoluna sahip sınıf.

```csharp
public Watermarker(string filePath)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| filePath | String | Belgenin yükleneceği dosya yolu. |

### istisnalar

| istisna | şart |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Sağlanan belge türü desteklenmiyor. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Sağlanan şifre yanlış. |

### Notlar

Belgeleri yükleme hakkında daha fazla bilgi edinin: [Belgeleri yükleme](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### Örnekler

Desteklenen herhangi bir biçimdeki içeriği yükleyin ve kaydedin.

```csharp
// Bir dosyadan içerik yükleyin.
using (Watermarker watermarker = new Watermarker("D:\\input.pdf"))
{
    // Filigran eklemek, aramak veya kaldırmak için Watermarker sınıfının yöntemlerini kullanın.

    // Belgeyi kaydedin.
    watermarker.Save("D:\\output.pdf");
}
```

### Ayrıca bakınız

* class [Watermarker](../../watermarker)
* ad alanı [GroupDocs.Watermark](../../watermarker)
* toplantı [GroupDocs.Watermark](../../../)

---

## Watermarker(string, LoadOptions) {#constructor_5}

Yeni bir örneğini başlatır.[`Watermarker`](../../watermarker)belirtilen belge yolu ve yükleme seçenekleriyle sınıf.

```csharp
public Watermarker(string filePath, LoadOptions options)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| filePath | String | Belgenin yükleneceği dosya yolu. |
| options | LoadOptions | Belge yüklerken kullanılacak ek seçenekler. |

### istisnalar

| istisna | şart |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Sağlanan belge türü desteklenmiyor. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Sağlanan şifre yanlış. |

### Notlar

Belgeleri yükleme hakkında daha fazla bilgi edinin: [Belgeleri yükleme](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### Örnekler

password. kullanarak şifrelenmiş PDF belgesini yükleyin

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
loadOptions.Password = "123";
using (Watermarker watermarker = new Watermarker(@"C:\Documents\test.pdf", loadOptions))
{
    // ...
}
```

### Ayrıca bakınız

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [Watermarker](../../watermarker)
* ad alanı [GroupDocs.Watermark](../../watermarker)
* toplantı [GroupDocs.Watermark](../../../)

---

## Watermarker(string, WatermarkerSettings) {#constructor_7}

Yeni bir örneğini başlatır.[`Watermarker`](../../watermarker) belirtilen belge yolu ve ayarları ile sınıf.

```csharp
public Watermarker(string filePath, WatermarkerSettings settings)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| filePath | String | Belgenin yükleneceği dosya yolu. |
| settings | WatermarkerSettings | Yüklenen belgeyle çalışırken kullanılacak ek ayarlar. |

### istisnalar

| istisna | şart |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Sağlanan belge türü desteklenmiyor. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Sağlanan şifre yanlış. |

### Notlar

Belgeleri yükleme hakkında daha fazla bilgi edinin: [Belgeleri yükleme](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### Örnekler

Aranabilir nesneleri genel olarak ayarlayın (bundan sonra yüklenecek tüm belgeler için).

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

        // Bulunan filigranlarla çalışma kodu buraya gelir.
    }
}
```

### Ayrıca bakınız

* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* ad alanı [GroupDocs.Watermark](../../watermarker)
* toplantı [GroupDocs.Watermark](../../../)

---

## Watermarker(string, LoadOptions, WatermarkerSettings) {#constructor_6}

Yeni bir örneğini başlatır.[`Watermarker`](../../watermarker) belirtilen belge yolu, yükleme seçenekleri ve ayarları ile sınıf.

```csharp
public Watermarker(string filePath, LoadOptions options, WatermarkerSettings settings)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| filePath | String | Belgenin yükleneceği dosya yolu. |
| options | LoadOptions | Belge yüklerken kullanılacak ek seçenekler. |
| settings | WatermarkerSettings | Yüklenen belgeyle çalışırken kullanılacak ek ayarlar. |

### istisnalar

| istisna | şart |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Sağlanan belge türü desteklenmiyor. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Sağlanan şifre yanlış. |

### Notlar

Belgeleri yükleme hakkında daha fazla bilgi edinin: [Belgeleri yükleme](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### Örnekler

E-posta mesajı gövdesinde/konusunda belirli metin parçalarını bulun.

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
    // Dikkat, arama yalnızca TextSearchCriteria örneğini Search yöntemine iletirseniz gerçekleştirilir
    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    // Bulunan metin parçalarını kaldır
    watermarks.Clear();
    // Değişiklikleri Kaydet
    watermarker.Save();
}
```

### Ayrıca bakınız

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* ad alanı [GroupDocs.Watermark](../../watermarker)
* toplantı [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream) {#constructor}

Yeni bir örneğini başlatır.[`Watermarker`](../../watermarker) belirtilen akışa sahip sınıf.

```csharp
public Watermarker(Stream document)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| document | Stream | Belgenin yükleneceği akış. |

### istisnalar

| istisna | şart |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Sağlanan belge türü desteklenmiyor. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Sağlanan şifre yanlış. |

### Notlar

Belgeleri yükleme hakkında daha fazla bilgi edinin [Belgeleri yükleme](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### Örnekler

Belgeyi desteklenen herhangi bir biçimde yükleyin ve kaydedin.

```csharp
// Bir akıştan içerik yükleyin.
using (FileStream inputStream = File.Open("D:\\input.pdf", FileMode.Open))
using (FileStream outputStream = File.Open("D:\\output.pdf", FileMode.Create))
using (Watermarker watermarker = new Watermarker(inputStream))
{
    // Filigran eklemek, aramak veya kaldırmak için Watermarker sınıfının yöntemlerini kullanın.

    // Değişiklikleri Kaydet.
    watermarker.Save(outputStream);
}
```

### Ayrıca bakınız

* class [Watermarker](../../watermarker)
* ad alanı [GroupDocs.Watermark](../../watermarker)
* toplantı [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, LoadOptions) {#constructor_1}

Yeni bir örneğini başlatır.[`Watermarker`](../../watermarker) belirtilen stream ve yükleme seçeneklerine sahip sınıf.

```csharp
public Watermarker(Stream document, LoadOptions options)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| document | Stream | Belgenin yükleneceği akış. |
| options | LoadOptions | Belge yüklerken kullanılacak ek seçenekler. |

### istisnalar

| istisna | şart |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Sağlanan belge türü desteklenmiyor. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Sağlanan şifre yanlış. |

### Notlar

Belgeleri yükleme hakkında daha fazla bilgi edinin [Belgeleri yükleme](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### Örnekler

password kullanarak şifrelenmiş PDF belgesini yükleyin

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
loadOptions.Password = "123";
using (FileStream fileStream = File.Open(@"C:\Documents\test.pdf", FileMode.Open))
using (Watermarker watermarker = new Watermarker(fileStream, loadOptions))
{
    // ...
}
```

### Ayrıca bakınız

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [Watermarker](../../watermarker)
* ad alanı [GroupDocs.Watermark](../../watermarker)
* toplantı [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, WatermarkerSettings) {#constructor_3}

Yeni bir örneğini başlatır.[`Watermarker`](../../watermarker) belirtilen stream ve settings. ile sınıf

```csharp
public Watermarker(Stream document, WatermarkerSettings settings)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| document | Stream | Belgenin yükleneceği akış. |
| settings | WatermarkerSettings | Yüklenen belgeyle çalışırken kullanılacak ek ayarlar. |

### istisnalar

| istisna | şart |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Sağlanan belge türü desteklenmiyor. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Sağlanan şifre yanlış. |

### Notlar

Belgeleri yükleme hakkında daha fazla bilgi edinin [Belgeleri yükleme](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### Örnekler

Aranabilir nesneleri genel olarak ayarlayın (bundan sonra yüklenecek tüm belgeler için).

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

        // Bulunan filigranlarla çalışma kodu buraya gelir.
    }
}
```

### Ayrıca bakınız

* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* ad alanı [GroupDocs.Watermark](../../watermarker)
* toplantı [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, LoadOptions, WatermarkerSettings) {#constructor_2}

Yeni bir örneğini başlatır.[`Watermarker`](../../watermarker) belirtilen akışa sahip sınıf, yükleme seçenekleri ve ayarları.

```csharp
public Watermarker(Stream document, LoadOptions options, WatermarkerSettings settings)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| document | Stream | Belgenin yükleneceği akış. |
| options | LoadOptions | Belge yüklerken kullanılacak ek seçenekler. |
| settings | WatermarkerSettings | Yüklenen belgeyle çalışırken kullanılacak ek ayarlar. |

### istisnalar

| istisna | şart |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Sağlanan belge türü desteklenmiyor. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Sağlanan şifre yanlış. |

### Notlar

Belgeleri yükleme hakkında daha fazla bilgi edinin [Belgeleri yükleme](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### Örnekler

E-posta mesajı gövdesinde/konusunda belirli metin parçalarını bulun.

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
    // Dikkat, arama yalnızca TextSearchCriteria örneğini Search yöntemine iletirseniz gerçekleştirilir
    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    // Bulunan metin parçalarını kaldır
    watermarks.Clear();
    // Değişiklikleri Kaydet
    watermarker.Save();
}
```

### Ayrıca bakınız

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* ad alanı [GroupDocs.Watermark](../../watermarker)
* toplantı [GroupDocs.Watermark](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
