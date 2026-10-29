---
title: "Simpan"
second_title: "GroupDocs.Watermark untuk Referensi API .NET"
description: "Menyimpan data dokumen ke aliran dasar."
type: docs
weight: 100
url: /id/net/groupdocs.watermark/watermarker/save/
---
## Save() {#save}

Menyimpan data dokumen ke aliran dasar.

```csharp
public WatermarkResult Save()
```

### Catatan

Pelajari lebih lanjut tentang menyimpan dokumen [Saving documents](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### Contoh

Hapus fragmen teks tertentu dari isi/subjek pesan email dan simpan pesan email.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\test.msg"))
{
    SearchCriteria criteria = new TextSearchCriteria("test", false);
    // Catatan, pencarian hanya dilakukan jika Anda memberikan instance TextSearchCriteria ke metode Search
    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    // Hapus fragmen teks yang ditemukan
    watermarker.Remove(watermarks);
    // Simpan perubahan
    watermarker.Save();
}
```

### Lihat Juga

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Save(string) {#save_4}

Menyimpan dokumen ke lokasi file yang ditentukan.

```csharp
public WatermarkResult Save(string filePath)
```

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| filePath | String | Jalur file untuk menyimpan data dokumen. |

### Catatan

Pelajari lebih lanjut tentang menyimpan dokumen [Saving documents](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### Contoh

Tambahkan watermark dan simpan dokumen ke file lain.

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{                                                                                   
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);                                            
    watermarker.Save("ouput.pdf");                                   
}                                                                                   
```

### Lihat Juga

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Save(Stream) {#save_2}

Menyimpan dokumen ke aliran yang ditentukan.

```csharp
public WatermarkResult Save(Stream document)
```

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| dokumen | Stream | Aliran untuk menyimpan data dokumen. |

### Catatan

Pelajari lebih lanjut tentang menyimpan dokumen [Saving documents](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### Contoh

Tambahkan watermark dan simpan dokumen ke aliran memori.

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

### Lihat Juga

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Save(SaveOptions) {#save_1}

Menyimpan data dokumen ke aliran dasar menggunakan opsi penyimpanan.

```csharp
public WatermarkResult Save(SaveOptions options)
```

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| options | SaveOptions | Opsi tambahan untuk digunakan saat menyimpan dokumen. |

### Catatan

Pelajari lebih lanjut tentang menyimpan dokumen [Saving documents](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### Contoh

Tambahkan watermark dan simpan dokumen dengan [`SaveOptions`](../../../groupdocs.watermark.options/saveoptions) default.

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);
    watermarker.Save(new SaveOptions());
}
```

### Lihat Juga

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Save(string, SaveOptions) {#save_5}

Menyimpan dokumen ke lokasi file yang ditentukan menggunakan opsi penyimpanan.

```csharp
public WatermarkResult Save(string filePath, SaveOptions options)
```

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| filePath | String | Jalur file untuk menyimpan data dokumen. |
| options | SaveOptions | Opsi tambahan untuk digunakan saat menyimpan dokumen. |

### Catatan

Pelajari lebih lanjut tentang menyimpan dokumen [Saving documents](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### Contoh

Tambahkan watermark dan simpan dokumen ke file lain dengan [`SaveOptions`](../../../groupdocs.watermark.options/saveoptions) default.

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{                                                                                   
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);                                            
    watermarker.Save("ouput.pdf", new SaveOptions());
}                                                                                   
```

### Lihat Juga

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

---

## Save(Stream, SaveOptions) {#save_3}

Menyimpan dokumen ke aliran yang ditentukan menggunakan opsi penyimpanan.

```csharp
public WatermarkResult Save(Stream document, SaveOptions options)
```

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| dokumen | Stream | Aliran untuk menyimpan data dokumen. |
| options | SaveOptions | Opsi tambahan untuk digunakan saat menyimpan dokumen. |

### Catatan

Pelajari lebih lanjut tentang menyimpan dokumen [Saving documents](https://docs.groupdocs.com/display/watermarknet/Saving+documents).

### Contoh

Tambahkan watermark dan simpan dokumen ke aliran memori dengan [`SaveOptions`](../../../groupdocs.watermark.options/saveoptions) default.

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

### Lihat Juga

* class [WatermarkResult](../../../groupdocs.watermark.internal/watermarkresult)
* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* namespace [GroupDocs.Watermark](../../../groupdocs.watermark)
* assembly [GroupDocs.Watermark](../../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.watermark.dll -->
