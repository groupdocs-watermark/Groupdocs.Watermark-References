---
title: Save
second_title: GroupDocs.Watermark untuk Referensi .NET API
description: Menyimpan data dokumen ke aliran yang mendasarinya.
type: docs
weight: 100
url: /id/net/groupdocs.watermark/watermarker/save/
---
## Save() {#save}

Menyimpan data dokumen ke aliran yang mendasarinya.

```csharp
public void Save()
```

### Perkataan

Pelajari lebih lanjut tentang menyimpan dokumen [Menyimpan dokumen](https://docs.groupdocs.com/display/watermarknet/Saving+documents) .

### Contoh

Hapus fragmen teks tertentu dari isi/subjek pesan email dan simpan pesan email.

```csharp
using (Watermarker watermarker = new Watermarker(@"D:\test.msg"))
{
    SearchCriteria criteria = new TextSearchCriteria("test", false);
    // Catatan, pencarian dilakukan hanya jika Anda meneruskan instance TextSearchCriteria ke metode Pencarian
    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    // Hapus fragmen teks yang ditemukan
    watermarker.Remove(watermarks);
    // Simpan perubahan
    watermarker.Save();
}
```

### Lihat juga

* class [Watermarker](../../watermarker)
* ruang nama [GroupDocs.Watermark](../../watermarker)
* perakitan [GroupDocs.Watermark](../../../)

---

## Save(string) {#save_4}

Menyimpan dokumen ke lokasi file yang ditentukan.

```csharp
public void Save(string filePath)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| filePath | String | Jalur file untuk menyimpan data dokumen. |

### Perkataan

Pelajari lebih lanjut tentang menyimpan dokumen [Menyimpan dokumen](https://docs.groupdocs.com/display/watermarknet/Saving+documents) .

### Contoh

Tambahkan tanda air dan simpan dokumen ke file lain.

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{                                                                                   
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);                                            
    watermarker.Save("ouput.pdf");                                   
}                                                                                   
```

### Lihat juga

* class [Watermarker](../../watermarker)
* ruang nama [GroupDocs.Watermark](../../watermarker)
* perakitan [GroupDocs.Watermark](../../../)

---

## Save(Stream) {#save_2}

Menyimpan dokumen ke aliran yang ditentukan.

```csharp
public void Save(Stream document)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| document | Stream | Aliran untuk menyimpan data dokumen. |

### Perkataan

Pelajari lebih lanjut tentang menyimpan dokumen [Menyimpan dokumen](https://docs.groupdocs.com/display/watermarknet/Saving+documents) .

### Contoh

Tambahkan tanda air dan simpan dokumen ke aliran memori.

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

### Lihat juga

* class [Watermarker](../../watermarker)
* ruang nama [GroupDocs.Watermark](../../watermarker)
* perakitan [GroupDocs.Watermark](../../../)

---

## Save(SaveOptions) {#save_1}

Menyimpan data dokumen ke aliran dasar menggunakan opsi penyimpanan.

```csharp
public void Save(SaveOptions options)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| options | SaveOptions | Opsi tambahan untuk digunakan saat menyimpan dokumen. |

### Perkataan

Pelajari lebih lanjut tentang menyimpan dokumen [Menyimpan dokumen](https://docs.groupdocs.com/display/watermarknet/Saving+documents) .

### Contoh

Tambahkan watermark dan simpan dokumen dengan default[`SaveOptions`](../../../groupdocs.watermark.options/saveoptions) .

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);
    watermarker.Save(new SaveOptions());
}
```

### Lihat juga

* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* ruang nama [GroupDocs.Watermark](../../watermarker)
* perakitan [GroupDocs.Watermark](../../../)

---

## Save(string, SaveOptions) {#save_5}

Menyimpan dokumen ke lokasi file yang ditentukan menggunakan opsi penyimpanan.

```csharp
public void Save(string filePath, SaveOptions options)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| filePath | String | Jalur file untuk menyimpan data dokumen. |
| options | SaveOptions | Opsi tambahan untuk digunakan saat menyimpan dokumen. |

### Perkataan

Pelajari lebih lanjut tentang menyimpan dokumen [Menyimpan dokumen](https://docs.groupdocs.com/display/watermarknet/Saving+documents) .

### Contoh

Tambahkan watermark dan simpan dokumen ke file lain dengan default[`SaveOptions`](../../../groupdocs.watermark.options/saveoptions) .

```csharp
using (Watermarker watermarker = new Watermarker("input.pdf"))
{                                                                                   
    TextWatermark watermark = new TextWatermark("top secret", new Font("Arial", 36));
    watermarker.Add(watermark);                                            
    watermarker.Save("ouput.pdf", new SaveOptions());
}                                                                                   
```

### Lihat juga

* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* ruang nama [GroupDocs.Watermark](../../watermarker)
* perakitan [GroupDocs.Watermark](../../../)

---

## Save(Stream, SaveOptions) {#save_3}

Menyimpan dokumen ke aliran yang ditentukan menggunakan opsi simpan.

```csharp
public void Save(Stream document, SaveOptions options)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| document | Stream | Aliran untuk menyimpan data dokumen. |
| options | SaveOptions | Opsi tambahan untuk digunakan saat menyimpan dokumen. |

### Perkataan

Pelajari lebih lanjut tentang menyimpan dokumen [Menyimpan dokumen](https://docs.groupdocs.com/display/watermarknet/Saving+documents) .

### Contoh

Tambahkan tanda air dan simpan dokumen ke aliran memori dengan default[`SaveOptions`](../../../groupdocs.watermark.options/saveoptions) .

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

### Lihat juga

* class [SaveOptions](../../../groupdocs.watermark.options/saveoptions)
* class [Watermarker](../../watermarker)
* ruang nama [GroupDocs.Watermark](../../watermarker)
* perakitan [GroupDocs.Watermark](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
