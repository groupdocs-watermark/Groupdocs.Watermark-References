---
title: "Watermarker"
second_title: "GroupDocs.Watermark untuk Referensi API .NET"
description: "Menginisialisasi instance baru dari kelas Watermarkergroupdocs.watermark/watermarker dengan jalur dokumen yang ditentukan."
type: docs
weight: 10
url: /id/net/groupdocs.watermark/watermarker/watermarker/
---
## Watermarker(string) {#constructor_4}

Menginisialisasi instance baru dari kelas [`Watermarker`](../../watermarker) dengan jalur dokumen yang ditentukan.

```csharp
public Watermarker(string filePath)
```

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| filePath | String | Jalur file untuk memuat dokumen. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Tipe dokumen yang diberikan tidak didukung. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Kata sandi yang diberikan tidak benar. |

### Catatan

Pelajari lebih lanjut tentang memuat dokumen: [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### Contoh

Muat dan simpan konten dalam format apa pun yang didukung.

```csharp
// Muat konten dari sebuah file.
using (Watermarker watermarker = new Watermarker("D:\\input.pdf"))
{
    // Gunakan metode kelas Watermarker untuk menambahkan, mencari, atau menghapus watermark.

    // Simpan dokumen.
    watermarker.Save("D:\\output.pdf");
}
```

### Lihat Juga

* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(string, LoadOptions) {#constructor_5}

Menginisialisasi instance baru dari kelas [`Watermarker`](../../watermarker) dengan jalur dokumen yang ditentukan dan opsi pemuatan.

```csharp
public Watermarker(string filePath, LoadOptions options)
```

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| filePath | String | Jalur file untuk memuat dokumen. |
| options | LoadOptions | Opsi tambahan untuk digunakan saat memuat dokumen. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Tipe dokumen yang diberikan tidak didukung. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Kata sandi yang diberikan tidak benar. |

### Catatan

Pelajari lebih lanjut tentang memuat dokumen: [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### Contoh

Muat dokumen PDF terenkripsi menggunakan kata sandi.

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
loadOptions.Password = "123";
using (Watermarker watermarker = new Watermarker(@"C:\Documents\test.pdf", loadOptions))
{
    // ...
}
```

### Lihat Juga

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(string, WatermarkerSettings) {#constructor_7}

Menginisialisasi instance baru dari kelas [`Watermarker`](../../watermarker) dengan jalur dokumen yang ditentukan dan pengaturan.

```csharp
public Watermarker(string filePath, WatermarkerSettings settings)
```

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| filePath | String | Jalur file untuk memuat dokumen. |
| pengaturan | WatermarkerSettings | Pengaturan tambahan untuk digunakan saat bekerja dengan dokumen yang dimuat. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Tipe dokumen yang diberikan tidak didukung. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Kata sandi yang diberikan tidak benar. |

### Catatan

Pelajari lebih lanjut tentang memuat dokumen: [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### Contoh

Atur objek yang dapat dicari secara global (untuk semua dokumen yang akan dimuat setelahnya).

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

        // Kode untuk bekerja dengan watermark yang ditemukan ditempatkan di sini.
    }
}
```

### Lihat Juga

* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(string, LoadOptions, WatermarkerSettings) {#constructor_6}

Menginisialisasi instance baru dari kelas [`Watermarker`](../../watermarker) dengan jalur dokumen yang ditentukan, opsi pemuatan, dan pengaturan.

```csharp
public Watermarker(string filePath, LoadOptions options, WatermarkerSettings settings)
```

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| filePath | String | Jalur file untuk memuat dokumen. |
| options | LoadOptions | Opsi tambahan untuk digunakan saat memuat dokumen. |
| pengaturan | WatermarkerSettings | Pengaturan tambahan untuk digunakan saat bekerja dengan dokumen yang dimuat. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Tipe dokumen yang diberikan tidak didukung. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Kata sandi yang diberikan tidak benar. |

### Catatan

Pelajari lebih lanjut tentang memuat dokumen: [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### Contoh

Temukan fragmen teks tertentu dalam isi/subjek pesan email.

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
    // Catatan, pencarian hanya dilakukan jika Anda memberikan instance TextSearchCriteria ke metode Search
    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    // Hapus fragmen teks yang ditemukan
    watermarks.Clear();
    // Simpan perubahan
    watermarker.Save();
}
```

### Lihat Juga

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream) {#constructor}

Menginisialisasi instance baru dari kelas [`Watermarker`](../../watermarker) dengan aliran yang ditentukan.

```csharp
public Watermarker(Stream document)
```

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| dokumen | Stream | Aliran untuk memuat dokumen dari. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Tipe dokumen yang diberikan tidak didukung. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Kata sandi yang diberikan tidak benar. |

### Catatan

Pelajari lebih lanjut tentang memuat dokumen [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### Contoh

Muat dan simpan dokumen dalam format apa pun yang didukung.

```csharp
// Muat konten dari aliran.
using (FileStream inputStream = File.Open("D:\\input.pdf", FileMode.Open))
using (FileStream outputStream = File.Open("D:\\output.pdf", FileMode.Create))
using (Watermarker watermarker = new Watermarker(inputStream))
{
    // Gunakan metode kelas Watermarker untuk menambahkan, mencari, atau menghapus watermark.

    // Simpan perubahan.
    watermarker.Save(outputStream);
}
```

### Lihat Juga

* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, LoadOptions) {#constructor_1}

Menginisialisasi instance baru dari kelas [`Watermarker`](../../watermarker) dengan aliran yang ditentukan dan opsi pemuatan.

```csharp
public Watermarker(Stream document, LoadOptions options)
```

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| dokumen | Stream | Aliran untuk memuat dokumen dari. |
| options | LoadOptions | Opsi tambahan untuk digunakan saat memuat dokumen. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Tipe dokumen yang diberikan tidak didukung. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Kata sandi yang diberikan tidak benar. |

### Catatan

Pelajari lebih lanjut tentang memuat dokumen [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### Contoh

Muat dokumen PDF terenkripsi menggunakan kata sandi

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
loadOptions.Password = "123";
using (FileStream fileStream = File.Open(@"C:\Documents\test.pdf", FileMode.Open))
using (Watermarker watermarker = new Watermarker(fileStream, loadOptions))
{
    // ...
}
```

### Lihat Juga

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, WatermarkerSettings) {#constructor_3}

Menginisialisasi instance baru dari kelas [`Watermarker`](../../watermarker) dengan aliran yang ditentukan dan pengaturan.

```csharp
public Watermarker(Stream document, WatermarkerSettings settings)
```

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| dokumen | Stream | Aliran untuk memuat dokumen dari. |
| pengaturan | WatermarkerSettings | Pengaturan tambahan untuk digunakan saat bekerja dengan dokumen yang dimuat. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Tipe dokumen yang diberikan tidak didukung. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Kata sandi yang diberikan tidak benar. |

### Catatan

Pelajari lebih lanjut tentang memuat dokumen [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### Contoh

Atur objek yang dapat dicari secara global (untuk semua dokumen yang akan dimuat setelahnya).

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

        // Kode untuk bekerja dengan watermark yang ditemukan ditempatkan di sini.
    }
}
```

### Lihat Juga

* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, LoadOptions, WatermarkerSettings) {#constructor_2}

Menginisialisasi instance baru dari kelas [`Watermarker`](../../watermarker) dengan aliran yang ditentukan, opsi pemuatan, dan pengaturan.

```csharp
public Watermarker(Stream document, LoadOptions options, WatermarkerSettings settings)
```

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| dokumen | Stream | Aliran untuk memuat dokumen dari. |
| options | LoadOptions | Opsi tambahan untuk digunakan saat memuat dokumen. |
| pengaturan | WatermarkerSettings | Pengaturan tambahan untuk digunakan saat bekerja dengan dokumen yang dimuat. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Tipe dokumen yang diberikan tidak didukung. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Kata sandi yang diberikan tidak benar. |

### Catatan

Pelajari lebih lanjut tentang memuat dokumen [Loading documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents).

### Contoh

Temukan fragmen teks tertentu dalam isi/subjek pesan email.

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
    // Catatan, pencarian hanya dilakukan jika Anda memberikan instance TextSearchCriteria ke metode Search
    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    // Hapus fragmen teks yang ditemukan
    watermarks.Clear();
    // Simpan perubahan
    watermarker.Save();
}
```

### Lihat Juga

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.watermark.dll -->
