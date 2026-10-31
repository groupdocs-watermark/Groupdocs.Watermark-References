---
title: "Übersicht der Funktionen"
linkTitle: "Features overview"
second_title: "GroupDocs.Watermark für Python über .NET API-Referenzen"
description: "GroupDocs.Watermark für Python via .NET fügt Text‑ und Bildwasserzeichen hinzu, sucht sie und entfernt sie über eine einheitliche, formatunabhängige API — mit formatabhängiger Platzierung, Bearbeitung des Inhaltsbaums, Sperrung und Rasterisierung."
type: docs
url: /de/python-net/guides/features-overview/
is_root: false
weight: 30
---


GroupDocs.Watermark für Python über .NET fügt Wasserzeichen hinzu, sucht nach ihnen und entfernt sie über eine breite Palette von [unterstützten Dokumentformaten](https://docs.groupdocs.com/watermark/python-net/supported-document-formats/). Jeder Vorgang folgt demselben Arbeitsablauf: Öffnen Sie ein Dokument mit [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/), rufen Sie `add()`, `search()` oder `remove()` auf und `save()` dann das Ergebnis zurück in das ursprüngliche Format. Die unten aufgeführten Funktionen können frei in einem Durchlauf kombiniert werden.

## Text and image watermarks

Fügen Sie formatierte Text- oder Bildwasserzeichen mit voller Kontrolle über Schriftart, Farbe, Transparenz, Drehung, Ausrichtung und Größe hinzu. Bildwasserzeichen können aus einer Datei oder einem Stream geladen werden. Siehe [Add text watermarks](/watermark/python-net/guides/add-text/) und [Add image watermarks](/watermark/python-net/guides/add-image/).

## Customization and tiling

Positionieren Sie ein Wasserzeichen mit absoluten Koordinaten oder elternbezogener Ausrichtung und Rändern, skalieren Sie es relativ zur Seite, drehen Sie es und kacheln Sie es über die gesamte Seite in einem wiederholenden Muster. Siehe [Customize watermarks](/watermark/python-net/guides/customize/), [Adding repeated watermarks](/watermark/python-net/guides/adding-repeated-watermarks/) und [Adding text watermarks](https://docs.groupdocs.com/watermark/python-net/adding-text-watermarks/).

## Format-specific placement

Platzieren Sie Wasserzeichen mit den Optionen, die zu jedem Format passen — PDF-Artefakte, Anmerkungen und nur‑Druck‑Anmerkungen; Präsentationsfolien, Master, Layouts und Notizen; Tabellenkalkulations‑Arbeitsblätter, Hintergründe und Kopf‑/Fußzeilen; Visio‑Seiten; sowie gesperrte Word‑Abschnitte und -Seiten. Siehe [Add watermarks to PDF documents](https://docs.groupdocs.com/watermark/python-net/add-watermarks-to-pdf-documents/) und die anderen Format‑Themen im [Developer Guide](https://docs.groupdocs.com/watermark/python-net/adding-watermarks/).

## Searching, modifying, and removing

Finden Sie bereits im Dokument vorhandene Wasserzeichen — einschließlich solcher, die von Drittanbieter‑Tools hinzugefügt wurden — anhand von exakt­em Text, regulären Ausdrücken, Bildähnlichkeit oder Textformatierung und kombinieren Sie Kriterien mit `and_`/`or_`/`not_`. Sobald sie gefunden sind, ersetzen Sie deren Text oder Bild oder entfernen Sie sie. Siehe [Searching watermarks](/watermark/python-net/guides/searching-watermarks/), [Modifying found watermark properties](https://docs.groupdocs.com/watermark/python-net/modifying-found-watermark-properties/) und [Removing found watermarks](https://docs.groupdocs.com/watermark/python-net/removing-found-watermarks/).

## Working with existing content

`Watermarker.get_content()` stellt einen format‑spezifischen Inhaltsbaum bereit, sodass Sie vorhandene Formen, PDF‑XObjects/Artefakte/Anmerkungen, Anhänge, Hintergründe und Kopf‑/Fußzeilen untersuchen und bearbeiten können — und Sie können die in einem Dokument eingebetteten Bilder mit `get_images()` mit einem Wasserzeichen versehen. Siehe [Adding watermark to images inside a document](https://docs.groupdocs.com/watermark/python-net/adding-watermark-to-images-inside-a-document/).

## Tamper resistance

Machen Sie Wasserzeichen schwer zu entfernen, indem Sie sie sperren, Word‑Dokumente schützen, nur‑Druck‑PDF‑Anmerkungen hinzufügen oder PDF‑Seiten rasterisieren, sodass das Wasserzeichen nicht bearbeitet werden kann. Siehe [Locking watermark in word processing document](https://docs.groupdocs.com/watermark/python-net/locking-watermark-in-word-processing-document/) und [Rasterize document or page](https://docs.groupdocs.com/watermark/python-net/rasterize-document-or-page/).

## Document inspection

Lesen Sie den Dateityp, die Seitenanzahl und die Größe eines Dokuments, ohne es zu ändern, und listen Sie jedes Dateiformat auf, das die Bibliothek unterstützt. Siehe [Get document info](/watermark/python-net/guides/get-document-info/) und [Get supported file formats](/watermark/python-net/guides/get-supported-file-formats/).

## On-premise

GroupDocs.Watermark für Python über .NET läuft vollständig in Ihrer eigenen Infrastruktur – Ihre Dokumente verlassen niemals Ihre Umgebung. Das Paket ist ein eigenständiges Wheel, das alles Notwendige bündelt, sodass kein Microsoft Office, OpenOffice oder separates Laufzeit‑Framework installiert werden muss. Siehe [System Requirements](https://docs.groupdocs.com/watermark/python-net/system-requirements/) für die unterstützten Plattformen und nativen Abhängigkeiten.
