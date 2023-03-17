---
title: Watermarker
second_title: GroupDocs.Watermark untuk Referensi .NET API
description: Menginisialisasi instance baru dariWatermarkergroupdocs.watermark/watermarker kelas dengan jalur dokumen yang ditentukan.
type: docs
weight: 10
url: /id/net/groupdocs.watermark/watermarker/watermarker/
---
## Watermarker(string) {#constructor_4}

Menginisialisasi instance baru dari[`Watermarker`](../../watermarker) kelas dengan jalur dokumen yang ditentukan.

```csharp
public Watermarker(string filePath)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| filePath | String | Jalur file untuk memuat dokumen dari. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Jenis dokumen yang disediakan tidak didukung. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Sandi yang diberikan salah. |

### Perkataan

Pelajari lebih lanjut tentang memuat dokumen: [Memuat dokumen](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### Contoh

Memuat dan menyimpan konten dalam format apa pun yang didukung.

```csharp
// Memuat konten dari file.
using (Watermarker watermarker = new Watermarker("D:\\input.pdf"))
{
    // Gunakan metode kelas Watermarker untuk menambah, mencari, atau menghapus tanda air.

    // Simpan dokumen.
    watermarker.Save("D:\\output.pdf");
}
```

### Lihat juga

* class [Watermarker](../../watermarker)
* ruang nama [GroupDocs.Watermark](../../watermarker)
* perakitan [GroupDocs.Watermark](../../../)

---

## Watermarker(string, LoadOptions) {#constructor_5}

Menginisialisasi instance baru dari[`Watermarker`](../../watermarker)kelas dengan jalur dokumen yang ditentukan dan memuat opsi.

```csharp
public Watermarker(string filePath, LoadOptions options)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| filePath | String | Jalur file tempat memuat dokumen. |
| options | LoadOptions | Opsi tambahan untuk digunakan saat memuat dokumen. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Jenis dokumen yang disediakan tidak didukung. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Sandi yang diberikan salah. |

### Perkataan

Pelajari lebih lanjut tentang memuat dokumen: [Memuat dokumen](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

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

### Lihat juga

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [Watermarker](../../watermarker)
* ruang nama [GroupDocs.Watermark](../../watermarker)
* perakitan [GroupDocs.Watermark](../../../)

---

## Watermarker(string, WatermarkerSettings) {#constructor_7}

Menginisialisasi instance baru dari[`Watermarker`](../../watermarker) kelas dengan jalur dan pengaturan dokumen yang ditentukan.

```csharp
public Watermarker(string filePath, WatermarkerSettings settings)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| filePath | String | Jalur file tempat memuat dokumen. |
| settings | WatermarkerSettings | Pengaturan tambahan untuk digunakan saat bekerja dengan dokumen yang dimuat. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Jenis dokumen yang disediakan tidak didukung. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Sandi yang diberikan salah. |

### Perkataan

Pelajari lebih lanjut tentang memuat dokumen: [Memuat dokumen](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### Contoh

Tetapkan objek yang dapat dicari secara global (untuk semua dokumen yang akan dimuat setelah itu).

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

        // Kode untuk bekerja dengan tanda air yang ditemukan ada di sini.
    }
}
```

### Lihat juga

* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* ruang nama [GroupDocs.Watermark](../../watermarker)
* perakitan [GroupDocs.Watermark](../../../)

---

## Watermarker(string, LoadOptions, WatermarkerSettings) {#constructor_6}

Menginisialisasi instance baru dari[`Watermarker`](../../watermarker) kelas dengan jalur dokumen yang ditentukan , memuat opsi dan pengaturan.

```csharp
public Watermarker(string filePath, LoadOptions options, WatermarkerSettings settings)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| filePath | String | Jalur file tempat memuat dokumen. |
| options | LoadOptions | Opsi tambahan untuk digunakan saat memuat dokumen. |
| settings | WatermarkerSettings | Pengaturan tambahan untuk digunakan saat bekerja dengan dokumen yang dimuat. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Jenis dokumen yang disediakan tidak didukung. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Sandi yang diberikan salah. |

### Perkataan

Pelajari lebih lanjut tentang memuat dokumen: [Memuat dokumen](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### Contoh

Temukan fragmen teks tertentu di badan/subjek pesan email.

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
    // Catatan, pencarian dilakukan hanya jika Anda meneruskan instance TextSearchCriteria ke metode Pencarian
    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    // Hapus fragmen teks yang ditemukan
    watermarks.Clear();
    // Simpan perubahan
    watermarker.Save();
}
```

### Lihat juga

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* ruang nama [GroupDocs.Watermark](../../watermarker)
* perakitan [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream) {#constructor}

Menginisialisasi instance baru dari[`Watermarker`](../../watermarker) kelas dengan aliran yang ditentukan.

```csharp
public Watermarker(Stream document)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| document | Stream | Aliran untuk memuat dokumen dari. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Jenis dokumen yang disediakan tidak didukung. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Sandi yang diberikan salah. |

### Perkataan

Pelajari lebih lanjut tentang memuat dokumen [Memuat dokumen](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### Contoh

Memuat dan menyimpan dokumen dalam format apa pun yang didukung.

```csharp
// Memuat konten dari aliran.
using (FileStream inputStream = File.Open("D:\\input.pdf", FileMode.Open))
using (FileStream outputStream = File.Open("D:\\output.pdf", FileMode.Create))
using (Watermarker watermarker = new Watermarker(inputStream))
{
    // Gunakan metode kelas Watermarker untuk menambah, mencari, atau menghapus tanda air.

    // Simpan perubahan.
    watermarker.Save(outputStream);
}
```

### Lihat juga

* class [Watermarker](../../watermarker)
* ruang nama [GroupDocs.Watermark](../../watermarker)
* perakitan [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, LoadOptions) {#constructor_1}

Menginisialisasi instance baru dari[`Watermarker`](../../watermarker) kelas dengan stream yang ditentukan dan opsi muat.

```csharp
public Watermarker(Stream document, LoadOptions options)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| document | Stream | Aliran untuk memuat dokumen dari. |
| options | LoadOptions | Opsi tambahan untuk digunakan saat memuat dokumen. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Jenis dokumen yang disediakan tidak didukung. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Sandi yang diberikan salah. |

### Perkataan

Pelajari lebih lanjut tentang memuat dokumen [Memuat dokumen](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### Contoh

Memuat dokumen PDF terenkripsi menggunakan kata sandi

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
loadOptions.Password = "123";
using (FileStream fileStream = File.Open(@"C:\Documents\test.pdf", FileMode.Open))
using (Watermarker watermarker = new Watermarker(fileStream, loadOptions))
{
    // ...
}
```

### Lihat juga

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [Watermarker](../../watermarker)
* ruang nama [GroupDocs.Watermark](../../watermarker)
* perakitan [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, WatermarkerSettings) {#constructor_3}

Menginisialisasi instance baru dari[`Watermarker`](../../watermarker) kelas dengan stream dan pengaturan yang ditentukan.

```csharp
public Watermarker(Stream document, WatermarkerSettings settings)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| document | Stream | Aliran untuk memuat dokumen dari. |
| settings | WatermarkerSettings | Pengaturan tambahan untuk digunakan saat bekerja dengan dokumen yang dimuat. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Jenis dokumen yang disediakan tidak didukung. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Sandi yang diberikan salah. |

### Perkataan

Pelajari lebih lanjut tentang memuat dokumen [Memuat dokumen](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### Contoh

Tetapkan objek yang dapat dicari secara global (untuk semua dokumen yang akan dimuat setelah itu).

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

        // Kode untuk bekerja dengan tanda air yang ditemukan ada di sini.
    }
}
```

### Lihat juga

* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* ruang nama [GroupDocs.Watermark](../../watermarker)
* perakitan [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, LoadOptions, WatermarkerSettings) {#constructor_2}

Menginisialisasi instance baru dari[`Watermarker`](../../watermarker) kelas dengan aliran yang ditentukan, memuat opsi dan pengaturan.

```csharp
public Watermarker(Stream document, LoadOptions options, WatermarkerSettings settings)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| document | Stream | Aliran untuk memuat dokumen dari. |
| options | LoadOptions | Opsi tambahan untuk digunakan saat memuat dokumen. |
| settings | WatermarkerSettings | Pengaturan tambahan untuk digunakan saat bekerja dengan dokumen yang dimuat. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Jenis dokumen yang disediakan tidak didukung. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Sandi yang diberikan salah. |

### Perkataan

Pelajari lebih lanjut tentang memuat dokumen [Memuat dokumen](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### Contoh

Temukan fragmen teks tertentu di badan/subjek pesan email.

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
    // Catatan, pencarian dilakukan hanya jika Anda meneruskan instance TextSearchCriteria ke metode Pencarian
    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    // Hapus fragmen teks yang ditemukan
    watermarks.Clear();
    // Simpan perubahan
    watermarker.Save();
}
```

### Lihat juga

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* ruang nama [GroupDocs.Watermark](../../watermarker)
* perakitan [GroupDocs.Watermark](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
