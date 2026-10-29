---
title: "FileType"
second_title: "GroupDocs.Watermark untuk Referensi API .NET"
description: "Mewakili tipe file."
type: docs
weight: 40
url: /id/net/groupdocs.watermark.common/filetype/
---
## FileType class

Mewakili tipe file.

```csharp
public sealed class FileType : IEquatable<FileType>
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Extension](../../groupdocs.watermark.common/filetype/extension) { get; } | Mendapatkan akhiran nama file (termasuk titik \".\") misalnya, \".doc\". |
| [FileFormatName](../../groupdocs.watermark.common/filetype/fileformatname) { get; } | Mendapatkan nama tipe file, misalnya \"Microsoft Word Document\". |
| [FormatFamily](../../groupdocs.watermark.common/filetype/formatfamily) { get; } | Mendapatkan keluarga format. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| static [FromExtension](../../groupdocs.watermark.common/filetype/fromextension)(string) | Memetakan ekstensi file ke tipe file. |
| [Equals](../../groupdocs.watermark.common/filetype/equals#equals)(FileType) | Menentukan apakah [`FileType`](../filetype) saat ini sama dengan objek [`FileType`](../filetype) yang ditentukan. |
| override [Equals](../../groupdocs.watermark.common/filetype/equals#equals_1)(object) | Menentukan apakah [`FileType`](../filetype) saat ini sama dengan objek yang ditentukan. |
| override [GetHashCode](../../groupdocs.watermark.common/filetype/gethashcode)() | Mengembalikan kode hash untuk objek [`FileType`](../filetype) saat ini. |
| override [ToString](../../groupdocs.watermark.common/filetype/tostring)() | Mengembalikan string yang mewakili objek saat ini. |
| static [GetSupportedFileTypes](../../groupdocs.watermark.common/filetype/getsupportedfiletypes)() | Mengambil tipe file yang didukung. |
| [operator ==](../../groupdocs.watermark.common/filetype/op_equality) | Menentukan apakah dua objek [`FileType`](../filetype) sama. |
| [operator !=](../../groupdocs.watermark.common/filetype/op_inequality) | Menentukan apakah dua objek [`FileType`](../filetype) tidak sama. |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| static readonly [BMP](../../groupdocs.watermark.common/filetype/bmp) | File dengan ekstensi .BMP mewakili file Gambar Bitmap yang digunakan untuk menyimpan gambar digital bitmap. Gambar ini independen dari adaptor grafis dan juga disebut format file bitmap independen perangkat (DIB). Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/image/bmp/). |
| static readonly [DOC](../../groupdocs.watermark.common/filetype/doc) | File dengan ekstensi .doc mewakili dokumen yang dihasilkan oleh Microsoft Word atau program pengolah kata lainnya dalam format file biner. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/word-processing/doc/). |
| static readonly [DOCM](../../groupdocs.watermark.common/filetype/docm) | File DOCM adalah dokumen yang dihasilkan oleh Microsoft Word 2007 atau lebih tinggi dengan kemampuan menjalankan makro. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/word-processing/docm/). |
| static readonly [DOCX](../../groupdocs.watermark.common/filetype/docx) | DOCX adalah format yang terkenal untuk dokumen Microsoft Word. Diperkenalkan sejak 2007 dengan rilis Microsoft Office 2007, struktur format Dokumen baru ini diubah dari biner sederhana menjadi kombinasi file XML dan biner. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/word-processing/docx/). |
| static readonly [DOT](../../groupdocs.watermark.common/filetype/dot) | File dengan ekstensi .DOT adalah file templat yang dibuat oleh Microsoft Word dengan pengaturan pra-format untuk menghasilkan file DOC atau DOCX selanjutnya. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/word-processing/dot/). |
| static readonly [DOTM](../../groupdocs.watermark.common/filetype/dotm) | File dengan ekstensi DOTM mewakili file templat yang dibuat dengan Microsoft Word 2007 atau lebih tinggi. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/word-processing/dotm/). |
| static readonly [DOTX](../../groupdocs.watermark.common/filetype/dotx) | File dengan ekstensi .DOTX adalah file templat yang dibuat oleh Microsoft Word dengan pengaturan pra-format untuk menghasilkan file DOCX selanjutnya. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/word-processing/dotx/). |
| static readonly [EML](../../groupdocs.watermark.common/filetype/eml) | Format file EML mewakili pesan email yang disimpan menggunakan Outlook dan aplikasi relevan lainnya. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/email/eml/). |
| static readonly [EMLX](../../groupdocs.watermark.common/filetype/emlx) | Format file EMLX diimplementasikan dan dikembangkan oleh Apple. Aplikasi Apple Mail menggunakan format file EMLX untuk mengekspor email. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/email/emlx/). |
| static readonly [FlatOpc](../../groupdocs.watermark.common/filetype/flatopc) | Office Open XML WordprocessingML disimpan dalam file XML datar alih-alih paket ZIP (.xml). Pelajari lebih lanjut tentang format file ini [di sini](https://en.wikipedia.org/wiki/Office_Open_XML). |
| static readonly [FlatOpcMacroEnabled](../../groupdocs.watermark.common/filetype/flatopcmacroenabled) | Office Open XML WordprocessingML Dokumen Macro-Enabled disimpan dalam file XML datar alih-alih paket ZIP (.xml). Pelajari lebih lanjut tentang format file ini [di sini](https://en.wikipedia.org/wiki/Office_Open_XML). |
| static readonly [FlatOpcTemplate](../../groupdocs.watermark.common/filetype/flatopctemplate) | Office Open XML WordprocessingML Templat (tanpa makro) disimpan dalam file XML datar alih-alih paket ZIP (.xml). Pelajari lebih lanjut tentang format file ini [di sini](https://en.wikipedia.org/wiki/Office_Open_XML). |
| static readonly [FlatOpcTemplateMacroEnabled](../../groupdocs.watermark.common/filetype/flatopctemplatemacroenabled) | Office Open XML WordprocessingML Templat Macro-Enabled disimpan dalam file XML datar alih-alih paket ZIP (.xml). Pelajari lebih lanjut tentang format file ini [di sini](https://en.wikipedia.org/wiki/Office_Open_XML). |
| static readonly [GIF](../../groupdocs.watermark.common/filetype/gif) | GIF atau Graphical Interchange Format adalah jenis gambar yang sangat terkompresi. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/image/gif/). |
| static readonly [JPEG](../../groupdocs.watermark.common/filetype/jpeg) | JPEG adalah jenis format gambar yang disimpan menggunakan metode kompresi lossy. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/image/jpeg/). |
| static readonly [JPF](../../groupdocs.watermark.common/filetype/jpf) | JPEG 2000 (JPF) adalah sistem pengkodean gambar dan standar kompresi gambar mutakhir. Dirancang dengan teknologi wavelet, JPEG 2000 dapat mengkode konten lossless dalam kualitas apa pun secara sekaligus. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/image/jp2/). |
| static readonly [JPG](../../groupdocs.watermark.common/filetype/jpg) | JPEG adalah jenis format gambar yang disimpan menggunakan metode kompresi lossy. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/image/jpeg/). |
| static readonly [JPM](../../groupdocs.watermark.common/filetype/jpm) | JPEG 2000 (JPM) adalah sistem pengkodean gambar dan standar kompresi gambar mutakhir. Dirancang, menggunakan teknologi wavelet, JPEG 2000 dapat mengkodekan konten lossless dalam kualitas apa pun sekaligus. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/image/jp2/). |
| static readonly [JPX](../../groupdocs.watermark.common/filetype/jpx) | JPEG 2000 (JPX) adalah sistem pengkodean gambar dan standar kompresi gambar mutakhir. Dirancang, menggunakan teknologi wavelet, JPEG 2000 dapat mengkodekan konten lossless dalam kualitas apa pun sekaligus. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/image/jp2/). |
| static readonly [MSG](../../groupdocs.watermark.common/filetype/msg) | MSG adalah format file yang digunakan oleh Microsoft Outlook dan Exchange untuk menyimpan pesan email, kontak, janji, atau tugas lainnya. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/email/msg/). |
| static readonly [ODT](../../groupdocs.watermark.common/filetype/odt) | File ODT adalah jenis dokumen yang dibuat dengan aplikasi pengolah kata yang berbasis pada format File Teks OpenDocument. Dokumen ini dibuat dengan aplikasi pengolah kata seperti OpenOffice Writer gratis dan dapat berisi konten seperti teks, gambar, objek, dan gaya. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/word-processing/odt/). |
| static readonly [OFT](../../groupdocs.watermark.common/filetype/oft) | File dengan ekstensi .OFT merupakan file templat pesan yang dibuat menggunakan Microsoft Outlook. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/email/oft/). |
| static readonly [OOXML](../../groupdocs.watermark.common/filetype/ooxml) | File Office Open XML (.ooxml). |
| static readonly [PDF](../../groupdocs.watermark.common/filetype/pdf) | Portable Document Format (PDF) adalah jenis dokumen yang dibuat oleh Adobe pada tahun 1990-an. Tujuan format file ini adalah memperkenalkan standar untuk representasi dokumen dan materi referensi lainnya dalam format yang independen dari perangkat lunak aplikasi, perangkat keras, serta Sistem Operasi. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/view/pdf/). |
| static readonly [PNG](../../groupdocs.watermark.common/filetype/png) | PNG, Portable Network Graphics, merujuk pada jenis format file gambar raster yang menggunakan kompresi lossless. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/image/png/). |
| static readonly [POTM](../../groupdocs.watermark.common/filetype/potm) | File dengan ekstensi POTM adalah file templat Microsoft PowerPoint yang mendukung Makro. File POTM dibuat dengan PowerPoint 2007 atau yang lebih baru dan berisi pengaturan default yang dapat digunakan untuk membuat file presentasi lebih lanjut. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/presentation/potm/). |
| static readonly [POTX](../../groupdocs.watermark.common/filetype/potx) | File dengan ekstensi .POTX merupakan presentasi templat Microsoft PowerPoint yang dibuat dengan Microsoft PowerPoint 2007 ke atas. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/presentation/potx/). |
| static readonly [PPS](../../groupdocs.watermark.common/filetype/pps) | PPS, PowerPoint Slide Show, adalah file yang dibuat menggunakan Microsoft PowerPoint untuk tujuan Slide Show. Pembacaan dan pembuatan file PPS didukung oleh Microsoft PowerPoint 97-2003. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/presentation/pps/). |
| static readonly [PPSM](../../groupdocs.watermark.common/filetype/ppsm) | File dengan ekstensi PPSM merupakan format file Slide Show yang mendukung Makro yang dibuat dengan Microsoft PowerPoint 2007 atau lebih tinggi. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/presentation/ppsm/). |
| static readonly [PPSX](../../groupdocs.watermark.common/filetype/ppsx) | PPSX, Power Point Slide Show, adalah file yang dibuat menggunakan Microsoft PowerPoint 2007 ke atas untuk tujuan Slide Show. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/presentation/ppsx/). |
| static readonly [PPT](../../groupdocs.watermark.common/filetype/ppt) | File dengan ekstensi PPT merupakan file PowerPoint yang terdiri dari kumpulan slide untuk ditampilkan sebagai SlideShow. Ini menentukan Format File Biner yang digunakan oleh Microsoft PowerPoint 97-2003. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/presentation/ppt/). |
| static readonly [PPTM](../../groupdocs.watermark.common/filetype/pptm) | File dengan ekstensi PPTM adalah file Presentasi yang mendukung Makro yang dibuat dengan Microsoft PowerPoint 2007 atau versi lebih tinggi. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/presentation/pptm/). |
| static readonly [PPTX](../../groupdocs.watermark.common/filetype/pptx) | File dengan ekstensi PPTX adalah file presentasi yang dibuat dengan aplikasi Microsoft PowerPoint yang populer. Tidak seperti versi sebelumnya dari format file presentasi PPT yang berbentuk biner, format PPTX berbasis pada format file presentasi Microsoft PowerPoint Open XML. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/presentation/pptx/). |
| static readonly [RTF](../../groupdocs.watermark.common/filetype/rtf) | Diperkenalkan dan didokumentasikan oleh Microsoft, Rich Text Format (RTF) merupakan metode pengkodean teks terformat dan grafik untuk digunakan dalam aplikasi. Format ini memfasilitasi pertukaran dokumen lintas platform dengan produk Microsoft lainnya, sehingga melayani tujuan interoperabilitas. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/word-processing/rtf/). |
| static readonly [TIF](../../groupdocs.watermark.common/filetype/tif) | TIFF atau TIF, Tagged Image File Format, merupakan gambar raster yang dimaksudkan untuk penggunaan pada berbagai perangkat yang mematuhi standar format file ini. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/image/tiff/). |
| static readonly [TIFF](../../groupdocs.watermark.common/filetype/tiff) | TIFF atau TIF, Tagged Image File Format, merupakan gambar raster yang dimaksudkan untuk penggunaan pada berbagai perangkat yang mematuhi standar format file ini. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/image/tiff/). |
| static readonly [Unknown](../../groupdocs.watermark.common/filetype/unknown) | Mewakili tipe file yang tidak diketahui. |
| static readonly [VDW](../../groupdocs.watermark.common/filetype/vdw) | VDW adalah format file Visio Graphics Service yang menentukan aliran dan penyimpanan yang diperlukan untuk merender gambar Web. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/web/vdw/). |
| static readonly [VDX](../../groupdocs.watermark.common/filetype/vdx) | Setiap gambar atau diagram yang dibuat di Microsoft Visio, tetapi disimpan dalam format XML memiliki ekstensi .VDX. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/image/vdx/). |
| static readonly [VSD](../../groupdocs.watermark.common/filetype/vsd) | File VSD adalah gambar yang dibuat dengan aplikasi Microsoft Visio untuk mewakili berbagai objek grafis dan interkoneksi di antara mereka. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/image/vsd/). |
| static readonly [VSDM](../../groupdocs.watermark.common/filetype/vsdm) | File dengan ekstensi VSDM adalah file gambar yang dibuat dengan aplikasi Microsoft Visio yang mendukung makro. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/image/vsdm/). |
| static readonly [VSDX](../../groupdocs.watermark.common/filetype/vsdx) | File dengan ekstensi .VSDX mewakili format file Microsoft Visio yang diperkenalkan sejak Microsoft Office 2013. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/image/vsdx/). |
| static readonly [VSS](../../groupdocs.watermark.common/filetype/vss) | VSS adalah file stencil yang dibuat dengan Microsoft Visio 2007 dan sebelumnya. File stencil menyediakan objek gambar yang dapat dimasukkan ke dalam gambar Visio .VSD. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/image/vss/). |
| static readonly [VSSM](../../groupdocs.watermark.common/filetype/vssm) | File dengan ekstensi .VSSM adalah file Stencil Microsoft Visio yang mendukung makro. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/image/vssm/). |
| static readonly [VSSX](../../groupdocs.watermark.common/filetype/vssx) | File dengan ekstensi .VSSX adalah stencil gambar yang dibuat dengan Microsoft Visio 2013 ke atas. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/image/vssx/). |
| static readonly [VST](../../groupdocs.watermark.common/filetype/vst) | File dengan ekstensi VST adalah file gambar vektor yang dibuat dengan Microsoft Visio dan berfungsi sebagai templat untuk membuat file lebih lanjut. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/image/vst/). |
| static readonly [VSTM](../../groupdocs.watermark.common/filetype/vstm) | File dengan ekstensi VSTM adalah file templat yang dibuat dengan Microsoft Visio yang mendukung makro. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/image/vstm/). |
| static readonly [VSTX](../../groupdocs.watermark.common/filetype/vstx) | File dengan ekstensi VSTX adalah file templat gambar yang dibuat dengan Microsoft Visio 2013 ke atas. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/image/vstx/). |
| static readonly [VSX](../../groupdocs.watermark.common/filetype/vsx) | File dengan ekstensi .VSX mengacu pada stencil yang terdiri dari gambar dan bentuk yang digunakan untuk membuat diagram di Microsoft Visio. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/image/vsx/). |
| static readonly [VTX](../../groupdocs.watermark.common/filetype/vtx) | Sebuah file dengan ekstensi VTX adalah templat gambar Microsoft Visio yang disimpan ke disk dalam format file XML. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/image/vtx/). |
| static readonly [WEBP](../../groupdocs.watermark.common/filetype/webp) | WebP, yang diperkenalkan oleh Google, adalah format file gambar web raster modern yang berbasis pada kompresi lossless dan lossy. Ini menyediakan kualitas gambar yang sama sambil secara signifikan mengurangi ukuran gambar. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/image/webp/). |
| static readonly [XLS](../../groupdocs.watermark.common/filetype/xls) | File dengan ekstensi XLS mewakili Excel Binary File Format. File semacam ini dapat dibuat oleh Microsoft Excel serta program spreadsheet serupa lainnya seperti OpenOffice Calc atau Apple Numbers. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/specification/spreadsheet/xls/). |
| static readonly [XLSB](../../groupdocs.watermark.common/filetype/xlsb) | Format file XLSB menentukan Excel Binary File Format, yang merupakan kumpulan catatan dan struktur yang menentukan konten buku kerja Excel. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/specification/spreadsheet/xlsb/). |
| static readonly [XLSM](../../groupdocs.watermark.common/filetype/xlsm) | File dengan ekstensi XLSM adalah jenis file Spreadsheet yang mendukung Makro. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/specification/spreadsheet/xlsm/). |
| static readonly [XLSX](../../groupdocs.watermark.common/filetype/xlsx) | XLSX adalah format terkenal untuk dokumen Microsoft Excel yang diperkenalkan oleh Microsoft pada rilis Microsoft Office 2007. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/specification/spreadsheet/xlsx/). |
| static readonly [XLT](../../groupdocs.watermark.common/filetype/xlt) | File dengan ekstensi .XLT adalah file templat yang dibuat dengan Microsoft Excel, yang merupakan aplikasi spreadsheet yang termasuk dalam paket Microsoft Office. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/specification/spreadsheet/xlt/). |
| static readonly [XLTM](../../groupdocs.watermark.common/filetype/xltm) | Ekstensi file XLTM mewakili file yang dihasilkan oleh Microsoft Excel sebagai file templat yang mendukung makro. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/specification/spreadsheet/xltm/). |
| static readonly [XLTX](../../groupdocs.watermark.common/filetype/xltx) | File dengan ekstensi XLTX mewakili file Templat Microsoft Excel yang berbasis pada spesifikasi format file Office OpenXML. Pelajari lebih lanjut tentang format file ini [di sini](https://wiki.fileformat.com/specification/spreadsheet/xltx/). |

### Catatan

Kelas ini menyediakan metode untuk memperoleh daftar semua jenis file yang didukung oleh **GroupDocs.Watermark**.**Pelajari lebih lanjut**

* [Supported Document Formats](https://docs.groupdocs.com/display/watermarknet/Supported+Document+Formats)
* [Get supported file formats](https://docs.groupdocs.com/display/watermarknet/Get+supported+file+formats)
* [Get document info](https://docs.groupdocs.com/display/watermarknet/Get+document+info)

### Lihat Juga

* namespace [GroupDocs.Watermark.Common](../../groupdocs.watermark.common)
* assembly [GroupDocs.Watermark](../../)

<!-- JANGAN EDIT: dihasilkan oleh xmldocmd untuk GroupDocs.watermark.dll -->
