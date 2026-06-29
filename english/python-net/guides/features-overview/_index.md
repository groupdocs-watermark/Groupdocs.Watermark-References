---
title: Features Overview
linkTitle: "Features overview"
second_title: GroupDocs.Watermark for Python via .NET API References
description: "GroupDocs.Watermark for Python via .NET adds, searches, and removes text and image watermarks through a single, format-independent API — with format-specific placement, content-tree editing, locking, and rasterization."
type: docs
url: /python-net/guides/features-overview/
is_root: false
weight: 30
---


GroupDocs.Watermark for Python via .NET adds, searches, and removes watermarks across a wide range of [supported document formats](). Every operation follows the same workflow: open a document with [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/), call `add()`, `search()`, or `remove()`, then `save()` the result back to its original format. The capabilities below can be combined freely in a single pass.

## Text and image watermarks

Add styled text or image watermarks with full control over font, color, opacity, rotation, alignment, and sizing. Image watermarks can be loaded from a file or a stream. See [Add text watermarks]() and [Add image watermarks]().

## Customization and tiling

Position a watermark with absolute coordinates or parent-relative alignment and margins, scale it relative to the page, rotate it, and tile it across the whole page in a repeating pattern. See [Customize watermarks](), [Adding repeated watermarks](), and [Adding text watermarks]().

## Format-specific placement

Place watermarks using the options that fit each format — PDF artifacts, annotations, and print-only annotations; presentation slides, masters, layouts, and notes; spreadsheet worksheets, backgrounds, and header/footers; Visio pages; and locked Word sections and pages. See [Add watermarks to PDF documents]() and the other format topics in the [Developer Guide]().

## Searching, modifying, and removing

Find watermarks already present in a document — including ones added by third-party tools — by exact text, regular expression, image similarity, or text formatting, and combine criteria with `and_`/`or_`/`not_`. Once found, replace their text or image, or remove them. See [Searching watermarks](), [Modifying found watermark properties](), and [Removing found watermarks]().

## Working with existing content

`Watermarker.get_content()` exposes a format-specific content tree so you can inspect and edit existing shapes, PDF XObjects/artifacts/annotations, attachments, backgrounds, and headers/footers — and you can watermark the images embedded inside a document with `get_images()`. See [Adding watermark to images inside a document]().

## Tamper resistance

Make watermarks hard to remove by locking them, protecting Word documents, adding print-only PDF annotations, or rasterizing PDF pages so the watermark cannot be edited out. See [Locking watermark in word processing document]() and [Rasterize document or page]().

## Document inspection

Read a document's file type, page count, and size without modifying it, and list every file format the library supports. See [Get document info]() and [Get supported file formats]().

## On-premise

GroupDocs.Watermark for Python via .NET runs entirely on your own infrastructure — your documents never leave your environment. The package is a self-contained wheel that bundles everything it needs, so no Microsoft Office, OpenOffice, or separate runtime has to be installed. See [System Requirements]() for the supported platforms and native dependencies.
