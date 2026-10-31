---
title: "Aperçu des fonctionnalités"
linkTitle: "Features overview"
second_title: "Références d'API GroupDocs.Watermark pour Python via .NET"
description: "GroupDocs.Watermark pour Python via .NET ajoute, recherche et supprime les filigranes texte et image via une API unique, indépendante du format — avec un positionnement spécifique au format, l'édition de l'arborescence du contenu, le verrouillage et la rasterisation."
type: docs
url: /fr/python-net/guides/features-overview/
is_root: false
weight: 30
---


GroupDocs.Watermark pour Python via .NET ajoute, recherche et supprime les filigranes sur un large éventail de [formats de documents pris en charge](https://docs.groupdocs.com/watermark/python-net/supported-document-formats/). Chaque opération suit le même flux de travail : ouvrez un document avec [`Watermarker`](/watermark/python-net/groupdocs.watermark/watermarker/), appelez `add()`, `search()` ou `remove()`, puis `save()` le résultat dans son format d'origine. Les capacités ci‑dessous peuvent être combinées librement en un seul passage.

## Text and image watermarks

Ajoutez des filigranes texte ou image stylisés avec un contrôle complet sur la police, la couleur, l'opacité, la rotation, l'alignement et la taille. Les filigranes image peuvent être chargés depuis un fichier ou un flux. Voir [Ajouter des filigranes texte](/watermark/python-net/guides/add-text/) et [Ajouter des filigranes image](/watermark/python-net/guides/add-image/).

## Customization and tiling

Positionnez un filigrane avec des coordonnées absolues ou un alignement et des marges relatifs au parent, redimensionnez‑le proportionnellement à la page, faites‑le pivoter, et répétez‑le sur toute la page selon un motif répétitif. Voir [Personnaliser les filigranes](/watermark/python-net/guides/customize/), [Ajouter des filigranes répétés](/watermark/python-net/guides/adding-repeated-watermarks/), et [Ajouter des filigranes texte](https://docs.groupdocs.com/watermark/python-net/adding-text-watermarks/).

## Format-specific placement

Placez les filigranes en utilisant les options adaptées à chaque format — artefacts PDF, annotations et annotations d'impression uniquement ; diapositives de présentation, maîtres, mises en page et notes ; feuilles de calcul, arrière‑plans et en‑têtes/pieds de page ; pages Visio ; et sections et pages Word verrouillées. Voir [Ajouter des filigranes aux documents PDF](https://docs.groupdocs.com/watermark/python-net/add-watermarks-to-pdf-documents/) et les autres sujets de format dans le [Guide du développeur](https://docs.groupdocs.com/watermark/python-net/adding-watermarks/).

## Searching, modifying, and removing

Recherchez les filigranes déjà présents dans un document — y compris ceux ajoutés par des outils tiers — par texte exact, expression régulière, similarité d'image ou formatage du texte, et combinez les critères avec `and_`/`or_`/`not_`. Une fois trouvés, remplacez leur texte ou image, ou supprimez‑les. Voir [Recherche de filigranes](/watermark/python-net/guides/searching-watermarks/), [Modification des propriétés des filigranes trouvés](https://docs.groupdocs.com/watermark/python-net/modifying-found-watermark-properties/), et [Suppression des filigranes trouvés](https://docs.groupdocs.com/watermark/python-net/removing-found-watermarks/).

## Working with existing content

`Watermarker.get_content()` expose un arbre de contenu spécifique au format afin que vous puissiez inspecter et modifier les formes existantes, les XObjects/artéfacts/annotations PDF, les pièces jointes, les arrière‑plans et les en‑têtes/pieds de page — et vous pouvez appliquer un filigrane aux images intégrées dans un document avec `get_images()`. Voir [Adding watermark to images inside a document](https://docs.groupdocs.com/watermark/python-net/adding-watermark-to-images-inside-a-document/).

## Tamper resistance

Rendez les filigranes difficiles à supprimer en les verrouillant, en protégeant les documents Word, en ajoutant des annotations PDF uniquement imprimables, ou en rasterisant les pages PDF afin que le filigrane ne puisse pas être retiré. Voir [Locking watermark in word processing document](https://docs.groupdocs.com/watermark/python-net/locking-watermark-in-word-processing-document/) et [Rasterize document or page](https://docs.groupdocs.com/watermark/python-net/rasterize-document-or-page/).

## Document inspection

Lisez le type de fichier, le nombre de pages et la taille d’un document sans le modifier, et répertoriez chaque format de fichier pris en charge par la bibliothèque. Voir [Get document info](/watermark/python-net/guides/get-document-info/) et [Get supported file formats](/watermark/python-net/guides/get-supported-file-formats/).

## On-premise

GroupDocs.Watermark for Python via .NET fonctionne entièrement sur votre propre infrastructure — vos documents ne quittent jamais votre environnement. Le paquet est une roue autonome qui regroupe tout ce dont il a besoin, ainsi aucun Microsoft Office, OpenOffice ou runtime séparé n’a besoin d’être installé. Voir [System Requirements](https://docs.groupdocs.com/watermark/python-net/system-requirements/) pour les plateformes prises en charge et les dépendances natives.
