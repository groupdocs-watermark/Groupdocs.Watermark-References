---
title: "Översikt över funktioner"
linkTitle: "Features overview"
second_title: "GroupDocs.Watermark för Python via .NET API-referenser"
description: "GroupDocs.Watermark för Python via .NET lägger till, söker och tar bort text‑ och bildvattenmärken via ett enda, formatoberoende API — med format‑specifik placering, redigering av innehållsträd, låsning och rasterisering."
type: docs
url: /sv/python-net/guides/features-overview/
is_root: false
weight: 30
---


GroupDocs.Watermark för Python via .NET lägger till, söker och tar bort vattenmärken över ett brett spektrum av [stödda dokumentformat](https://docs.groupdocs.com/watermark/python-net/supported-document-formats/). Varje operation följer samma arbetsflöde: öppna ett dokument med [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/), anropa `add()`, `search()` eller `remove()`, och sedan `save()` resultatet tillbaka till dess ursprungliga format. Följande funktioner kan kombineras fritt i ett enda pass.

## Text and image watermarks

Lägg till formaterad text‑ eller bildvattenmärke med full kontroll över teckensnitt, färg, opacitet, rotation, justering och storlek. Bildvattenmärken kan laddas från en fil eller en ström. Se [Lägg till textvattenmärken](/watermark/python-net/guides/add-text/) och [Lägg till bildvattenmärken](/watermark/python-net/guides/add-image/).

## Customization and tiling

Placera ett vattenmärke med absoluta koordinater eller föräldra‑relativ justering och marginaler, skala det i förhållande till sidan, rotera det och mosa det över hela sidan i ett upprepande mönster. Se [Anpassa vattenmärken](/watermark/python-net/guides/customize/), [Lägga till upprepade vattenmärken](/watermark/python-net/guides/adding-repeated-watermarks/), och [Lägga till textvattenmärken](https://docs.groupdocs.com/watermark/python-net/adding-text-watermarks/).

## Format-specific placement

Placera vattenstämplar med de alternativ som passar varje format — PDF‑artefakter, annotationer och endast‑utskrifts‑annotationer; presentationsbilder, master‑bilder, layouter och anteckningar; kalkylblad, bakgrunder och sidhuvud/sidfot; Visio‑sidor; och låsta Word‑sektioner och -sidor. Se [Add watermarks to PDF documents](https://docs.groupdocs.com/watermark/python-net/add-watermarks-to-pdf-documents/) och de andra formatämnena i [Developer Guide](https://docs.groupdocs.com/watermark/python-net/adding-watermarks/).

## Searching, modifying, and removing

Hitta vattenstämplar som redan finns i ett dokument — inklusive sådana som lagts till av tredjepartsverktyg — genom exakt text, reguljärt uttryck, bildlikhet eller textformatering, och kombinera kriterier med `and_`/`or_`/`not_`. När de hittats, ersätt deras text eller bild, eller ta bort dem. Se [Searching watermarks](/watermark/python-net/guides/searching-watermarks/), [Modifying found watermark properties](https://docs.groupdocs.com/watermark/python-net/modifying-found-watermark-properties/), och [Removing found watermarks](https://docs.groupdocs.com/watermark/python-net/removing-found-watermarks/).

## Working with existing content

`Watermarker.get_content()` exponerar ett format‑specifikt innehållsträd så att du kan inspektera och redigera befintliga former, PDF‑XObjects/artefakter/annotationer, bilagor, bakgrunder och sidhuvud/sidfot — och du kan vattenstämpa bilder som är inbäddade i ett dokument med `get_images()`. Se [Adding watermark to images inside a document](https://docs.groupdocs.com/watermark/python-net/adding-watermark-to-images-inside-a-document/).

## Tamper resistance

Gör vattenstämplar svåra att ta bort genom att låsa dem, skydda Word‑dokument, lägga till endast‑utskrifts‑PDF‑annotationer eller rasterisera PDF‑sidor så att vattenstämpeln inte kan redigeras bort. Se [Locking watermark in word processing document](https://docs.groupdocs.com/watermark/python-net/locking-watermark-in-word-processing-document/) och [Rasterize document or page](https://docs.groupdocs.com/watermark/python-net/rasterize-document-or-page/).

## Document inspection

Läs ett dokuments filtyp, sidantal och storlek utan att ändra det, och lista alla filformat som biblioteket stöder. Se [Get document info](/watermark/python-net/guides/get-document-info/) och [Get supported file formats](/watermark/python-net/guides/get-supported-file-formats/).

## On-premise

GroupDocs.Watermark för Python via .NET körs helt på din egen infrastruktur — dina dokument lämnar aldrig din miljö. Paketet är ett självständigt wheel som samlar allt som behövs, så ingen Microsoft Office, OpenOffice eller separat runtime behöver installeras. Se [System Requirements](https://docs.groupdocs.com/watermark/python-net/system-requirements/) för de stödda plattformarna och inhemska beroenden.
