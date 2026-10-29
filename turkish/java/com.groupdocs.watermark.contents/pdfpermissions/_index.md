---
title: "PdfPermissions"
second_title: "GroupDocs.Watermark for Java API Referansı"
description: "Bir PDF belgesi için kullanıcı izinlerini temsil eder."
type: docs
weight: 68
url: /tr/java/com.groupdocs.watermark.contents/pdfpermissions/
---
**Inheritance:**
java.lang.Object
```
public final class PdfPermissions
```

Bir PDF belgesi için kullanıcının izinlerini temsil eder.

## Alanlar

| Alan | Açıklama |
| --- | --- |
|  | [PrintDocument](#PrintDocument) | İçeriği yazdır. |
|
|  | [ModifyContent](#ModifyContent) | İçeriği değiştir. |
|
|  | [ExtractContent](#ExtractContent) | Belgeden metin ve grafikleri kopyala ya da başka şekilde çıkar. |
|
|  | [ModifyTextAnnotations](#ModifyTextAnnotations) | Metin açıklamalarını ekle ya da değiştir. |
|
|  | [FillForm](#FillForm) | Mevcut etkileşimli form alanlarını doldur. |
|
|  | [ExtractContentWithDisabilities](#ExtractContentWithDisabilities) | Metin ve grafikleri çıkar. |
|
|  | [AssembleDocument](#AssembleDocument) | İçeriği birleştir. |
|
|  | [PrintingQuality](#PrintingQuality) | PDF belgesinin doğru bir dijital kopyası oluşturulabilecek bir temsile içeriği yazdır. |
|
### PrintDocument {#PrintDocument}
```
public static final int PrintDocument
```


İçeriği yazdır.

Revizyon 2 güvenlik işleyicileri: İçeriği yazdır.

Revizyon 3 veya daha yüksek güvenlik işleyicileri: İçeriği yazdır
(muhtemelen en yüksek kalite seviyesinde olmayabilir, şu şeye bağlı olarak `#PrintingQuality.PrintingQuality` de ayarlanmışsa).
Belgenin içeriğini diğer işlemlerle değiştir


### ModifyContent {#ModifyContent}
```
public static final int ModifyContent
```


İçeriği değiştir.

`#ModifyTextAnnotations.ModifyTextAnnotations`, `#FillForm.FillForm` tarafından kontrol edilenlerden farklı olarak.
Revizyon 2 güvenlik işleyicileri: İçerikten metin ve grafikleri kopyala ya da başka şekilde çıkar,


### ExtractContent {#ExtractContent}
```
public static final int ExtractContent
```


Belgeden metin ve grafikleri kopyala ya da başka şekilde çıkar.

metin ve grafik çıkarımını da içerecek şekilde (engelli kullanıcıların erişilebilirliğini desteklemek için
veya diğer amaçlar için).
engellilikler veya diğer amaçlar için).

Revizyon 3 veya üzerindeki güvenlik işleyicileri: Metin ve grafikleri kopyalayın veya başka şekilde şuradan çıkarın
içeriği, kontrol edilen işlemler dışındaki işlemlerle
`#ExtractContentWithDisabilities.ExtractContentWithDisabilities`.


### ModifyTextAnnotations {#ModifyTextAnnotations}
```
public static final int ModifyTextAnnotations
```


Metin açıklamalarını ekle ya da değiştir.

Metin açıklamalarını ekleyin veya değiştirin, etkileşimli form alanlarını doldurun,
ve, eğer `#ModifyContent.ModifyContent` de ayarlanmışsa,
etkileşimli form alanlarını (imza alanları dahil) oluşturun veya değiştirin.


### FillForm {#FillForm}
```
public static final int FillForm
```


Mevcut etkileşimli form alanlarını doldur.

Revizyon 3 veya üzerindeki güvenlik işleyicileri: Mevcut etkileşimli form alanlarını doldurun
(imza alanları dahil), `#ModifyTextAnnotations.ModifyTextAnnotations` temiz olsa bile.


### ExtractContentWithDisabilities {#ExtractContentWithDisabilities}
```
public static final int ExtractContentWithDisabilities
```


Metin ve grafikleri çıkar.

Revizyon 3 veya üzerindeki güvenlik işleyicileri: Metin ve grafikleri çıkarın
(engelliler için erişilebilirliği desteklemek veya diğer amaçlar için).


### AssembleDocument {#AssembleDocument}
```
public static final int AssembleDocument
```


İçeriği birleştir.

Revizyon 3 veya üzerindeki güvenlik işleyicileri: İçeriği birleştirin (sayfaları ekleyin, döndürün veya silin
ve yer imleri veya küçük resim oluşturun), `#ModifyContent.ModifyContent` temiz olsa bile.


### PrintingQuality {#PrintingQuality}
```
public static final int PrintingQuality
```


PDF belgesinin doğru bir dijital kopyası oluşturulabilecek bir temsile içeriği yazdır.

Revizyon 3 veya üzerindeki güvenlik işleyicileri: İçeriği, doğru bir
PDF belgesinin dijital kopyasının oluşturulabileceği bir temsile yazdırın. Bu bit temiz olduğunda (ve `#PrintDocument.PrintDocument`
ayarlanmışsa), baskı, görünümün düşük seviyeli bir temsiliyle sınırlıdır, muhtemelen kalite kaybıyla.


