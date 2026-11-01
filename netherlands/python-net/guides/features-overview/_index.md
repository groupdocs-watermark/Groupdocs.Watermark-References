---
title: "Overzicht van functies"
linkTitle: "Features overview"
second_title: "GroupDocs.Watermark voor Python via .NET API-referenties"
description: "GroupDocs.Watermark voor Python via .NET voegt tekst- en afbeeldingwatermerken toe, zoekt ze en verwijdert ze via een enkele, formaat-onafhankelijke API — met formaat-specifieke plaatsing, bewerking van de inhoudboom, vergrendeling en rasterisatie."
type: docs
url: /nl/python-net/guides/features-overview/
is_root: false
weight: 30
---


GroupDocs.Watermark voor Python via .NET voegt watermerken toe, zoekt ze en verwijdert ze over een breed scala aan [supported document formats](https://docs.groupdocs.com/watermark/python-net/supported-document-formats/). Elke bewerking volgt dezelfde workflow: open een document met [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/), roep `add()`, `search()` of `remove()` aan, en `save()` vervolgens het resultaat terug naar het oorspronkelijke formaat. De onderstaande mogelijkheden kunnen vrijelijk worden gecombineerd in één enkele pass.

## Text and image watermarks

Voeg gestileerde tekst- of afbeeldingwatermerken toe met volledige controle over lettertype, kleur, doorzichtigheid, rotatie, uitlijning en grootte. Afbeeldingswatermerken kunnen worden geladen uit een bestand of een stream. Zie [Add text watermarks](/watermark/python-net/guides/add-text/) en [Add image watermarks](/watermark/python-net/guides/add-image/).

## Customization and tiling

Positioneer een watermerk met absolute coördinaten of ouder-relatieve uitlijning en marges, schaal het relatief aan de pagina, roteer het en tegel het over de hele pagina in een herhalend patroon. Zie [Customize watermarks](/watermark/python-net/guides/customize/), [Adding repeated watermarks](/watermark/python-net/guides/adding-repeated-watermarks/), en [Adding text watermarks](https://docs.groupdocs.com/watermark/python-net/adding-text-watermarks/).

## Format-specific placement

Plaats watermerken met de opties die passen bij elk formaat — PDF‑artefacten, annotaties en alleen‑bij‑afdrukken annotaties; presentatieslides, masters, lay-outs en notities; spreadsheet‑werkbladen, achtergronden en kop‑/voetteksten; Visio‑pagina's; en vergrendelde Word‑secties en -pagina's. Zie [Add watermarks to PDF documents](https://docs.groupdocs.com/watermark/python-net/add-watermarks-to-pdf-documents/) en de andere formaatonderwerpen in de [Developer Guide](https://docs.groupdocs.com/watermark/python-net/adding-watermarks/).

## Searching, modifying, and removing

Zoek watermerken die al in een document aanwezig zijn — inclusief die toegevoegd door tools van derden — op exacte tekst, reguliere expressie, afbeeldingsgelijkenis of tekstopmaak, en combineer criteria met `and_`/`or_`/`not_`. Eenmaal gevonden, vervang hun tekst of afbeelding, of verwijder ze. Zie [Searching watermarks](/watermark/python-net/guides/searching-watermarks/), [Modifying found watermark properties](https://docs.groupdocs.com/watermark/python-net/modifying-found-watermark-properties/), en [Removing found watermarks](https://docs.groupdocs.com/watermark/python-net/removing-found-watermarks/).

## Working with existing content

`Watermarker.get_content()` biedt een op formaat specifiek inhoudsboom zodat je bestaande vormen, PDF XObjects/artifacts/annotations, bijlagen, achtergronden en kop- en voetteksten kunt inspecteren en bewerken — en je kunt de afbeeldingen die in een document zijn ingesloten watermerken met `get_images()`. Zie [Watermerk toevoegen aan afbeeldingen in een document](https://docs.groupdocs.com/watermark/python-net/adding-watermark-to-images-inside-a-document/).

## Tamper resistance

Maak watermerken moeilijk te verwijderen door ze te vergrendelen, Word‑documenten te beschermen, alleen‑afdruk PDF‑annotaties toe te voegen, of PDF‑pagina's te rasteren zodat het watermerk niet kan worden verwijderd. Zie [Watermerk vergrendelen in een tekstverwerkingsdocument](https://docs.groupdocs.com/watermark/python-net/locking-watermark-in-word-processing-document/) en [Document of pagina rasteren](https://docs.groupdocs.com/watermark/python-net/rasterize-document-or-page/).

## Document inspection

Lees het bestandstype, paginatelling en de grootte van een document zonder het te wijzigen, en lijst elk bestandsformaat op dat de bibliotheek ondersteunt. Zie [Documentinformatie ophalen](/watermark/python-net/guides/get-document-info/) en [Ondersteunde bestandsformaten ophalen](/watermark/python-net/guides/get-supported-file-formats/).

## On-premise

GroupDocs.Watermark voor Python via .NET draait volledig op uw eigen infrastructuur — uw documenten verlaten uw omgeving nooit. Het pakket is een zelfstandige wheel die alles bundelt wat het nodig heeft, zodat er geen Microsoft Office, OpenOffice of aparte runtime geïnstalleerd hoeft te worden. Zie [Systeemvereisten](https://docs.groupdocs.com/watermark/python-net/system-requirements/) voor de ondersteunde platforms en native afhankelijkheden.
