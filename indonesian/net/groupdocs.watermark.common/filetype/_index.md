---
title: FileType
second_title: GroupDocs.Watermark untuk Referensi .NET API
description: Mewakili jenis file.
type: docs
weight: 40
url: /id/net/groupdocs.watermark.common/filetype/
---
## FileType class

Mewakili jenis file.

```csharp
public sealed class FileType : IEquatable<FileType>
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [Extension](../../groupdocs.watermark.common/filetype/extension) { get; } | Mendapat akhiran nama file (termasuk titik ".") misalnya, ".doc". |
| [FileFormatName](../../groupdocs.watermark.common/filetype/fileformatname) { get; } | Mendapat nama jenis file misalnya, "Dokumen Microsoft Word". |
| [FormatFamily](../../groupdocs.watermark.common/filetype/formatfamily) { get; } | Mendapatkan format family. |

## Metode

| Nama | Keterangan |
| --- | --- |
| static [FromExtension](../../groupdocs.watermark.common/filetype/fromextension)(string) | Memetakan ekstensi file ke jenis file. |
| [Equals](../../groupdocs.watermark.common/filetype/equals#equals)(FileType) | Menentukan apakah arus[`FileType`](../filetype) adalah sama dengan yang ditentukan[`FileType`](../filetype) objek. |
| override [Equals](../../groupdocs.watermark.common/filetype/equals#equals_1)(object) | Menentukan apakah arus[`FileType`](../filetype) sama dengan objek yang ditentukan. |
| override [GetHashCode](../../groupdocs.watermark.common/filetype/gethashcode)() | Mengembalikan kode hash untuk saat ini[`FileType`](../filetype) objek. |
| override [ToString](../../groupdocs.watermark.common/filetype/tostring)() | Mengembalikan string yang mewakili objek saat ini. |
| static [GetSupportedFileTypes](../../groupdocs.watermark.common/filetype/getsupportedfiletypes)() | Mengambil jenis file yang didukung. |
| [operator ==](../../groupdocs.watermark.common/filetype/op_equality) | Menentukan apakah dua[`FileType`](../filetype) objeknya sama. |
| [operator !=](../../groupdocs.watermark.common/filetype/op_inequality) | Menentukan apakah dua[`FileType`](../filetype) objek tidak sama. |

## Bidang

| Nama | Keterangan |
| --- | --- |
| static readonly [BMP](../../groupdocs.watermark.common/filetype/bmp) | File yang berekstensi .BMP mewakili file Gambar Bitmap yang digunakan untuk menyimpan gambar digital bitmap. Gambar ini tidak tergantung pada adaptor grafis dan juga disebut format file device independent bitmap (DIB). Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/image/bmp/) . |
| static readonly [DOC](../../groupdocs.watermark.common/filetype/doc) | File dengan ekstensi .doc mewakili dokumen yang dihasilkan oleh Microsoft Word atau dokumen pengolah kata lainnya dalam format file biner. Pelajari lebih lanjut tentang format file ini [Di Sini](https://wiki.fileformat.com/word-processing/doc/) . |
| static readonly [DOCM](../../groupdocs.watermark.common/filetype/docm) | File DOCM adalah dokumen yang dibuat Microsoft Word 2007 atau lebih tinggi dengan kemampuan untuk menjalankan makro. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/word-processing/docm/) . |
| static readonly [DOCX](../../groupdocs.watermark.common/filetype/docx) | DOCX adalah format terkenal untuk dokumen Microsoft Word. Diperkenalkan dari tahun 2007 dengan rilis dari Microsoft Office 2007, struktur format Dokumen baru ini diubah dari binary biasa menjadi kombinasi file XML dan biner. Pelajari lebih lanjut tentang format file ini [Di Sini](https://wiki.fileformat.com/word-processing/docx/) . |
| static readonly [DOT](../../groupdocs.watermark.common/filetype/dot) | File dengan ekstensi .DOT adalah file template yang dibuat oleh Microsoft Word untuk memiliki pengaturan pra-format untuk membuat file DOC atau DOCX lebih lanjut. Pelajari lebih lanjut tentang format file ini [Di Sini](https://wiki.fileformat.com/word-processing/dot/) . |
| static readonly [DOTM](../../groupdocs.watermark.common/filetype/dotm) | File dengan ekstensi DOTM mewakili file template yang dibuat dengan Microsoft Word 2007 atau lebih tinggi. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/word-processing/dotm/) . |
| static readonly [DOTX](../../groupdocs.watermark.common/filetype/dotx) | File dengan ekstensi DOTX adalah file template yang dibuat oleh Microsoft Word untuk memiliki pengaturan pra-format untuk pembuatan file DOCX lebih lanjut. Pelajari lebih lanjut tentang format file ini [Di Sini](https://wiki.fileformat.com/word-processing/dotx/) . |
| static readonly [EML](../../groupdocs.watermark.common/filetype/eml) | Format file EML mewakili pesan email yang disimpan menggunakan Outlook dan aplikasi lain yang relevan. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/email/eml/) . |
| static readonly [EMLX](../../groupdocs.watermark.common/filetype/emlx) | Format file EMLX diimplementasikan dan dikembangkan oleh Apple. Aplikasi Apple Mail menggunakan format file EMLX untuk mengekspor email. Pelajari lebih lanjut tentang format file ini [Di Sini](https://wiki.fileformat.com/email/emlx/) . |
| static readonly [FlatOpc](../../groupdocs.watermark.common/filetype/flatopc) | Office Open XML WordprocessingML disimpan dalam file XML datar, bukan paket ZIP (.xml). Pelajari lebih lanjut tentang format file ini[Di Sini](https://en.wikipedia.org/wiki/Office_Open_XML) . |
| static readonly [FlatOpcMacroEnabled](../../groupdocs.watermark.common/filetype/flatopcmacroenabled) | Office Open XML WordprocessingML Macro-Enabled Document yang disimpan dalam file XML datar, bukan paket ZIP (.xml). Pelajari selengkapnya tentang format file ini[Di Sini](https://en.wikipedia.org/wiki/Office_Open_XML) . |
| static readonly [FlatOpcTemplate](../../groupdocs.watermark.common/filetype/flatopctemplate) | Templat Office Open XML WordprocessingML (bebas makro) disimpan dalam file XML datar, bukan paket ZIP (.xml). Pelajari lebih lanjut tentang format file ini[Di Sini](https://en.wikipedia.org/wiki/Office_Open_XML) . |
| static readonly [FlatOpcTemplateMacroEnabled](../../groupdocs.watermark.common/filetype/flatopctemplatemacroenabled) | Office Open XML WordprocessingML Macro-Enabled Template disimpan dalam file XML datar, bukan paket ZIP (.xml). Pelajari lebih lanjut tentang format file ini[Di Sini](https://en.wikipedia.org/wiki/Office_Open_XML) . |
| static readonly [GIF](../../groupdocs.watermark.common/filetype/gif) | GIF atau Graphical Interchange Format adalah jenis gambar yang sangat terkompresi. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/image/gif/) . |
| static readonly [JPEG](../../groupdocs.watermark.common/filetype/jpeg) | JPEG adalah jenis format gambar yang disimpan menggunakan metode kompresi lossy. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/image/jpeg/) . |
| static readonly [JPF](../../groupdocs.watermark.common/filetype/jpf) | JPEG 2000 (JPF) adalah sistem pengkodean gambar dan standar kompresi gambar yang canggih. Didesain, menggunakan teknologi wavelet JPEG 2000 dapat mengkodekan konten lossless dalam kualitas apa pun sekaligus. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/image/jp2/) . |
| static readonly [JPG](../../groupdocs.watermark.common/filetype/jpg) | JPEG adalah jenis format gambar yang disimpan menggunakan metode kompresi lossy. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/image/jpeg/) . |
| static readonly [JPM](../../groupdocs.watermark.common/filetype/jpm) | JPEG 2000 (JPM) adalah sistem pengkodean gambar dan standar kompresi gambar yang canggih. Didesain, menggunakan teknologi wavelet JPEG 2000 dapat mengkodekan konten lossless dalam kualitas apa pun sekaligus. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/image/jp2/) . |
| static readonly [JPX](../../groupdocs.watermark.common/filetype/jpx) | JPEG 2000 (JPX) adalah sistem pengkodean gambar dan standar kompresi gambar yang canggih. Didesain, menggunakan teknologi wavelet JPEG 2000 dapat mengkodekan konten lossless dalam kualitas apa pun sekaligus. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/image/jp2/) . |
| static readonly [MSG](../../groupdocs.watermark.common/filetype/msg) | MSG adalah format file yang digunakan oleh Microsoft Outlook dan Exchange untuk menyimpan pesan email, kontak, janji temu, atau tugas lainnya. Pelajari lebih lanjut tentang format file ini [Di Sini](https://wiki.fileformat.com/email/msg/) . |
| static readonly [ODT](../../groupdocs.watermark.common/filetype/odt) | File ODT adalah jenis dokumen yang dibuat dengan aplikasi pengolah kata yang didasarkan pada format File Teks OpenDocument . Ini dibuat dengan aplikasi pengolah kata seperti OpenOffice Writer gratis dan dapat menampung konten seperti teks, gambar, objek, dan gaya. Pelajari lebih lanjut tentang format file ini [Di Sini](https://wiki.fileformat.com/word-processing/odt/) . |
| static readonly [OFT](../../groupdocs.watermark.common/filetype/oft) | File dengan ekstensi .OFT mewakili file template pesan yang dibuat menggunakan Microsoft Outlook. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/email/oft/) . |
| static readonly [OOXML](../../groupdocs.watermark.common/filetype/ooxml) | Office membuka file xml (.ooxml). |
| static readonly [PDF](../../groupdocs.watermark.common/filetype/pdf) | Portable Document Format (PDF) adalah jenis dokumen yang dibuat oleh Adobe pada tahun 1990-an. Tujuan dari format file ini adalah untuk memperkenalkan standar untuk representasi dokumen dan bahan referensi lainnya dalam format yang independen dari perangkat lunak aplikasi, perangkat keras, serta Sistem Operasi. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/view/pdf/) . |
| static readonly [PNG](../../groupdocs.watermark.common/filetype/png) | PNG, Portable Network Graphics, mengacu pada jenis format file gambar raster yang menggunakan kompresi lossless. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/image/png/) . |
| static readonly [POTM](../../groupdocs.watermark.common/filetype/potm) | File dengan ekstensi POTM adalah file template Microsoft PowerPoint dengan dukungan untuk Macro. File POTM dibuat dengan PowerPoint 2007 atau lebih tinggi dan berisi pengaturan default yang dapat digunakan untuk membuat file presentasi lebih lanjut. Pelajari lebih lanjut tentang format file ini [Di Sini](https://wiki.fileformat.com/presentation/potm/) . |
| static readonly [POTX](../../groupdocs.watermark.common/filetype/potx) | File dengan ekstensi .POTX mewakili presentasi template Microsoft PowerPoint yang dibuat dengan Microsoft PowerPoint 2007 ke atas. Pelajari lebih lanjut tentang format file ini [Di Sini](https://wiki.fileformat.com/presentation/potx/) . |
| static readonly [PPS](../../groupdocs.watermark.common/filetype/pps) | PPS, Peragaan Slide PowerPoint, file dibuat menggunakan Microsoft PowerPoint untuk tujuan Peragaan Slide. Pembacaan dan pembuatan file PPS didukung oleh Microsoft PowerPoint 97-2003. Pelajari lebih lanjut tentang format file ini [Di Sini](https://wiki.fileformat.com/presentation/pps/) . |
| static readonly [PPSM](../../groupdocs.watermark.common/filetype/ppsm) | File dengan ekstensi PPSM mewakili format file Peragaan Slide dengan Makro aktif yang dibuat dengan Microsoft PowerPoint 2007 atau lebih tinggi. Pelajari lebih lanjut tentang format file ini [Di Sini](https://wiki.fileformat.com/presentation/ppsm/) . |
| static readonly [PPSX](../../groupdocs.watermark.common/filetype/ppsx) | PPSX, Power Point Slide Show, file dibuat menggunakan Microsoft PowerPoint 2007 ke atas untuk tujuan Slide Show. Pelajari lebih lanjut tentang format file ini [Di Sini](https://wiki.fileformat.com/presentation/ppsx/) . |
| static readonly [PPT](../../groupdocs.watermark.common/filetype/ppt) | File dengan ekstensi PPT mewakili file PowerPoint yang terdiri dari kumpulan slide untuk ditampilkan sebagai SlideShow. Ini menentukan Format File Biner yang digunakan oleh Microsoft PowerPoint 97-2003. Pelajari selengkapnya tentang format file ini[Di Sini](https://wiki.fileformat.com/presentation/ppt/) . |
| static readonly [PPTM](../../groupdocs.watermark.common/filetype/pptm) | File dengan ekstensi PPTM adalah file Presentasi dengan dukungan Makro yang dibuat dengan Microsoft PowerPoint 2007 atau versi yang lebih tinggi. Pelajari lebih lanjut tentang format file ini [Di Sini](https://wiki.fileformat.com/presentation/pptm/) . |
| static readonly [PPTX](../../groupdocs.watermark.common/filetype/pptx) | File dengan ekstensi PPTX adalah file presentasi yang dibuat dengan aplikasi Microsoft PowerPoint yang populer. Berbeda dengan versi sebelumnya dari format file presentasi PPT yang merupakan biner, format PPTX didasarkan pada format file presentasi terbuka XML Microsoft PowerPoint. Pelajari lebih lanjut tentang format file ini [Di Sini](https://wiki.fileformat.com/presentation/pptx/) . |
| static readonly [RTF](../../groupdocs.watermark.common/filetype/rtf) | Diperkenalkan dan didokumentasikan oleh Microsoft, Rich Text Format (RTF) mewakili metode pengkodean teks dan grafik berformat untuk digunakan dalam aplikasi. Format ini memfasilitasi pertukaran dokumen lintas platform dengan Produk Microsoft lainnya, sehingga melayani tujuan interoperabilitas. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/word-processing/rtf/) . |
| static readonly [TIF](../../groupdocs.watermark.common/filetype/tif) | TIFF atau TIF, Tagged Image File Format, mewakili gambar raster yang dimaksudkan untuk digunakan pada berbagai perangkat yang mematuhi standar format file ini. Pelajari lebih lanjut tentang format file ini [Di Sini](https://wiki.fileformat.com/image/tiff/) . |
| static readonly [TIFF](../../groupdocs.watermark.common/filetype/tiff) | TIFF atau TIF, Tagged Image File Format, mewakili gambar raster yang dimaksudkan untuk digunakan pada berbagai perangkat yang mematuhi standar format file ini. Pelajari lebih lanjut tentang format file ini [Di Sini](https://wiki.fileformat.com/image/tiff/) . |
| static readonly [Unknown](../../groupdocs.watermark.common/filetype/unknown) | Mewakili jenis file yang tidak diketahui. |
| static readonly [VDW](../../groupdocs.watermark.common/filetype/vdw) | VDW adalah format file Layanan Grafik Visio yang menentukan aliran dan penyimpanan yang diperlukan untuk merender gambar Web. Pelajari lebih lanjut tentang format file ini [Di Sini](https://wiki.fileformat.com/web/vdw/) . |
| static readonly [VDX](../../groupdocs.watermark.common/filetype/vdx) | Semua gambar atau bagan yang dibuat di Microsoft Visio, tetapi disimpan dalam format XML memiliki ekstensi .VDX. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/image/vdx/) . |
| static readonly [VSD](../../groupdocs.watermark.common/filetype/vsd) | File VSD adalah gambar yang dibuat dengan aplikasi Microsoft Visio untuk mewakili berbagai objek grafis dan interkoneksi di antara ini. Pelajari lebih lanjut tentang format file ini [Di Sini](https://wiki.fileformat.com/image/vsd/) . |
| static readonly [VSDM](../../groupdocs.watermark.common/filetype/vsdm) | File dengan ekstensi VSDM adalah file gambar yang dibuat dengan aplikasi Microsoft Visio yang mendukung makro. Pelajari lebih lanjut tentang format file ini [Di Sini](https://wiki.fileformat.com/image/vsdm/) . |
| static readonly [VSDX](../../groupdocs.watermark.common/filetype/vsdx) | File dengan ekstensi .VSDX mewakili format file Microsoft Visio yang diperkenalkan dari Microsoft Office 2013 dan seterusnya. Pelajari lebih lanjut tentang format file ini [Di Sini](https://wiki.fileformat.com/image/vsdx/) . |
| static readonly [VSS](../../groupdocs.watermark.common/filetype/vss) | VSS adalah file stensil yang dibuat dengan Microsoft Visio 2007 dan sebelumnya. File stensil menyediakan objek drawing yang dapat disertakan dalam gambar .VSD Visio. Pelajari lebih lanjut tentang format file ini [Di Sini](https://wiki.fileformat.com/image/vss/) . |
| static readonly [VSSM](../../groupdocs.watermark.common/filetype/vssm) | File dengan ekstensi .VSSM adalah file Microsoft Visio Stencil yang mendukung menyediakan dukungan untuk makro. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/image/vssm/) . |
| static readonly [VSSX](../../groupdocs.watermark.common/filetype/vssx) | File dengan ekstensi .VSSX adalah stensil gambar yang dibuat dengan Microsoft Visio 2013 ke atas. Pelajari lebih lanjut tentang format file ini [Di Sini](https://wiki.fileformat.com/image/vssx/) . |
| static readonly [VST](../../groupdocs.watermark.common/filetype/vst) | File dengan ekstensi VST adalah file gambar vektor yang dibuat dengan Microsoft Visio dan bertindak sebagai template untuk membuat file lebih lanjut. Pelajari lebih lanjut tentang format file ini [Di Sini](https://wiki.fileformat.com/image/vst/) . |
| static readonly [VSTM](../../groupdocs.watermark.common/filetype/vstm) | File dengan ekstensi VSTM adalah file template yang dibuat dengan Microsoft Visio yang mendukung makro. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/image/vstm/) . |
| static readonly [VSTX](../../groupdocs.watermark.common/filetype/vstx) | File dengan ekstensi VSTX menggambar file template yang dibuat dengan Microsoft Visio 2013 ke atas. Pelajari lebih lanjut tentang format file ini [Di Sini](https://wiki.fileformat.com/image/vstx/) . |
| static readonly [VSX](../../groupdocs.watermark.common/filetype/vsx) | File dengan ekstensi .VSX mengacu pada stensil yang terdiri dari gambar dan bentuk yang digunakan untuk membuat diagram di Microsoft Visio. Pelajari lebih lanjut tentang format file ini [Di Sini](https://wiki.fileformat.com/image/vsx/) . |
| static readonly [VTX](../../groupdocs.watermark.common/filetype/vtx) | File dengan ekstensi VTX adalah template gambar Microsoft Visio yang disimpan ke disk dalam format file XML. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/image/vtx/) . |
| static readonly [WEBP](../../groupdocs.watermark.common/filetype/webp) | WebP, diperkenalkan oleh Google, adalah format file gambar web raster modern yang didasarkan pada kompresi lossless dan lossy. Ini memberikan kualitas gambar yang sama sekaligus mengurangi ukuran gambar. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/image/webp/) . |
| static readonly [XLS](../../groupdocs.watermark.common/filetype/xls) | File dengan ekstensi XLS mewakili Format File Biner Excel. File tersebut dapat dibuat oleh Microsoft Excel serta program spreadsheet serupa lainnya seperti OpenOffice Calc atau Apple Numbers. Pelajari lebih lanjut tentang format file ini[Di Sini](https://wiki.fileformat.com/specification/spreadsheet/xls/) . |
| static readonly [XLSB](../../groupdocs.watermark.common/filetype/xlsb) | Format file XLSB menentukan Format File Biner Excel, yang merupakan kumpulan rekaman dan struktur yang menentukan konten buku kerja Excel. Pelajari lebih lanjut tentang format file ini [Di Sini](https://wiki.fileformat.com/specification/spreadsheet/xlsb/) . |
| static readonly [XLSM](../../groupdocs.watermark.common/filetype/xlsm) | File dengan ekstensi XLSM adalah jenis file Spreadsheet yang mendukung Macro. Pelajari lebih lanjut tentang format file ini [Di Sini](https://wiki.fileformat.com/specification/spreadsheet/xlsm/) . |
| static readonly [XLSX](../../groupdocs.watermark.common/filetype/xlsx) | XLSX adalah format terkenal untuk dokumen Microsoft Excel yang diperkenalkan oleh Microsoft dengan rilis dari Microsoft Office 2007. Pelajari lebih lanjut tentang format file ini [Di Sini](https://wiki.fileformat.com/specification/spreadsheet/xlsx/) . |
| static readonly [XLT](../../groupdocs.watermark.common/filetype/xlt) | File dengan ekstensi .XLT adalah file template yang dibuat dengan Microsoft Excel yang merupakan aplikasi spreadsheet yang hadir sebagai bagian dari suite Microsoft Office. Pelajari lebih lanjut tentang format file ini [Di Sini](https://wiki.fileformat.com/specification/spreadsheet/xlt/) . |
| static readonly [XLTM](../../groupdocs.watermark.common/filetype/xltm) | Ekstensi file XLTM mewakili file yang dihasilkan oleh Microsoft Excel sebagai file template Macro-enabled . Pelajari lebih lanjut tentang format file ini [Di Sini](https://wiki.fileformat.com/specification/spreadsheet/xltm/) . |
| static readonly [XLTX](../../groupdocs.watermark.common/filetype/xltx) | File dengan ekstensi XLTX mewakili file Template Microsoft Excel yang didasarkan pada spesifikasi format file Office OpenXML . Pelajari lebih lanjut tentang format file ini [Di Sini](https://wiki.fileformat.com/specification/spreadsheet/xltx/) . |

### Perkataan

Kelas ini menyediakan metode untuk mendapatkan daftar semua jenis file yang didukung oleh**GroupDocs.Watermark**.**Belajarlah lagi**

* [Format Dokumen yang Didukung](https://docs.groupdocs.com/display/watermarknet/Supported+Document+Formats)
* [Dapatkan format file yang didukung](https://docs.groupdocs.com/display/watermarknet/Get+supported+file+formats)
* [Dapatkan info dokumen](https://docs.groupdocs.com/display/watermarknet/Get+document+info)

### Lihat juga

* ruang nama [GroupDocs.Watermark.Common](../../groupdocs.watermark.common)
* perakitan [GroupDocs.Watermark](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
