---
title: "Gambaran Fitur"
linkTitle: "Features overview"
second_title: "Referensi API GroupDocs.Watermark untuk Python via .NET"
description: "GroupDocs.Watermark untuk Python via .NET menambahkan, mencari, dan menghapus watermark teks serta gambar melalui satu API yang independen format — dengan penempatan spesifik format, penyuntingan pohon konten, penguncian, dan rasterisasi."
type: docs
url: /id/python-net/guides/features-overview/
is_root: false
weight: 30
---


GroupDocs.Watermark untuk Python via .NET menambahkan, mencari, dan menghapus watermark di berbagai [format dokumen yang didukung](https://docs.groupdocs.com/watermark/python-net/supported-document-formats/). Setiap operasi mengikuti alur kerja yang sama: buka dokumen dengan [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/), panggil `add()`, `search()`, atau `remove()`, kemudian `save()` hasilnya kembali ke format aslinya. Kemampuan di bawah ini dapat digabungkan secara bebas dalam satu proses.

## Text and image watermarks

Tambahkan watermark teks atau gambar yang bergaya dengan kontrol penuh atas font, warna, opasitas, rotasi, perataan, dan ukuran. Watermark gambar dapat dimuat dari file atau aliran. Lihat [Add text watermarks](/watermark/python-net/guides/add-text/) dan [Add image watermarks](/watermark/python-net/guides/add-image/).

## Customization and tiling

Posisikan watermark dengan koordinat absolut atau perataan dan margin relatif terhadap induk, skala relatif terhadap halaman, putar, dan ubin di seluruh halaman dalam pola berulang. Lihat [Customize watermarks](/watermark/python-net/guides/customize/), [Adding repeated watermarks](/watermark/python-net/guides/adding-repeated-watermarks/), dan [Adding text watermarks](https://docs.groupheads.com/watermark/python-net/adding-text-watermarks/).

## Format-specific placement

Tempatkan watermark menggunakan opsi yang sesuai untuk setiap format — artefak PDF, anotasi, dan anotasi hanya cetak; slide presentasi, master, tata letak, dan catatan; lembar kerja spreadsheet, latar belakang, dan header/footer; halaman Visio; serta bagian dan halaman Word yang terkunci. Lihat [Add watermarks to PDF documents](https://docs.groupdocs.com/watermark/python-net/add-watermarks-to-pdf-documents/) dan topik format lainnya dalam [Developer Guide](https://docs.groupdocs.com/watermark/python-net/adding-watermarks/).

## Searching, modifying, and removing

Temukan watermark yang sudah ada dalam dokumen — termasuk yang ditambahkan oleh alat pihak ketiga — berdasarkan teks tepat, ekspresi reguler, kemiripan gambar, atau pemformatan teks, dan gabungkan kriteria dengan `and_`/`or_`/`not_`. Setelah ditemukan, ganti teks atau gambar mereka, atau hapus. Lihat [Searching watermarks](/watermark/python-net/guides/searching-watermarks/), [Modifying found watermark properties](https://docs.groupdocs.com/watermark/python-net/modifying-found-watermark-properties/), dan [Removing found watermarks](https://docs.groupdocs.com/watermark/python-net/removing-found-watermarks/).

## Working with existing content

`Watermarker.get_content()` menampilkan pohon konten spesifik format sehingga Anda dapat memeriksa dan mengedit bentuk yang ada, PDF XObjects/artifacts/annotations, lampiran, latar belakang, dan header/footer — dan Anda dapat menambahkan watermark pada gambar yang disematkan dalam dokumen dengan `get_images()`. Lihat [Menambahkan watermark ke gambar di dalam dokumen](https://docs.groupdocs.com/watermark/python-net/adding-watermark-to-images-inside-a-document/).

## Tamper resistance

Buat watermark sulit dihapus dengan mengunci mereka, melindungi dokumen Word, menambahkan anotasi PDF hanya cetak, atau meraster halaman PDF sehingga watermark tidak dapat dihapus. Lihat [Mengunci watermark dalam dokumen pengolah kata](https://docs.groupdocs.com/watermark/python-net/locking-watermark-in-word-processing-document/) dan [Meraster dokumen atau halaman](https://docs.groupdocs.com/watermark/python-net/rasterize-document-or-page/).

## Document inspection

Baca tipe file dokumen, jumlah halaman, dan ukuran tanpa mengubahnya, serta daftar semua format file yang didukung perpustakaan. Lihat [Dapatkan info dokumen](/watermark/python-net/guides/get-document-info/) dan [Dapatkan format file yang didukung](/watermark/python-net/guides/get-supported-file-formats/).

## On-premise

GroupDocs.Watermark untuk Python via .NET berjalan sepenuhnya di infrastruktur Anda sendiri — dokumen Anda tidak pernah keluar dari lingkungan Anda. Paket ini adalah wheel mandiri yang menggabungkan semua yang dibutuhkan, sehingga tidak perlu menginstal Microsoft Office, OpenOffice, atau runtime terpisah. Lihat [Persyaratan Sistem](https://docs.groupdocs.com/watermark/python-net/system-requirements/) untuk platform yang didukung dan dependensi native.
