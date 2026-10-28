---
title: "PdfPermissions"
second_title: "GroupDocs.Watermark pour Java Référence API"
description: "Représente les autorisations des utilisateurs pour un document PDF."
type: docs
weight: 68
url: /fr/java/com.groupdocs.watermark.contents/pdfpermissions/
---
**Inheritance:**
java.lang.Object
```
public final class PdfPermissions
```

Représente les autorisations de l'utilisateur pour un document PDF.

## Champs

| Champ | Description |
| --- | --- |
|  | [PrintDocument](#PrintDocument) | Imprimer le contenu. |
|
|  | [ModifyContent](#ModifyContent) | Modifier le contenu. |
|
|  | [ExtractContent](#ExtractContent) | Copier ou extraire autrement le texte et les graphiques du document. |
|
|  | [ModifyTextAnnotations](#ModifyTextAnnotations) | Ajouter ou modifier des annotations de texte. |
|
|  | [FillForm](#FillForm) | Remplir les champs de formulaire interactifs existants. |
|
|  | [ExtractContentWithDisabilities](#ExtractContentWithDisabilities) | Extraire le texte et les graphiques. |
|
|  | [AssembleDocument](#AssembleDocument) | Assembler le contenu. |
|
|  | [PrintingQuality](#PrintingQuality) | Imprimer le contenu vers une représentation à partir de laquelle une copie numérique fidèle du document PDF pourrait être générée. |
|
### PrintDocument {#PrintDocument}
```
public static final int PrintDocument
```


Imprimer le contenu.

Gestionnaires de sécurité de la révision 2 : Imprimer le contenu.

Gestionnaires de sécurité de la révision 3 ou supérieure : Imprimer le contenu
(peut-être pas au niveau de qualité le plus élevé, selon que
`#PrintingQuality.PrintingQuality` est également défini).


### ModifyContent {#ModifyContent}
```
public static final int ModifyContent
```


Modifier le contenu.

Modifier le contenu du document par d'autres opérations
que celles contrôlées par `#ModifyTextAnnotations.ModifyTextAnnotations`, `#FillForm.FillForm`.


### ExtractContent {#ExtractContent}
```
public static final int ExtractContent
```


Copier ou extraire autrement le texte et les graphiques du document.

Gestionnaires de sécurité de la révision 2 : Copier ou extraire autrement le texte et les graphiques du contenu,
y compris l'extraction du texte et des graphiques (pour soutenir l'accessibilité aux utilisateurs avec
des handicaps ou à d'autres fins).

Gestionnaires de sécurité de la révision 3 ou supérieure : Copier ou extraire autrement le texte et les graphiques de
le contenu par des opérations autres que celles contrôlées par
`#ExtractContentWithDisabilities.ExtractContentWithDisabilities`.


### ModifyTextAnnotations {#ModifyTextAnnotations}
```
public static final int ModifyTextAnnotations
```


Ajouter ou modifier des annotations de texte.

Ajouter ou modifier des annotations de texte, remplir les champs de formulaire interactifs,
et, si `#ModifyContent.ModifyContent` est également défini,
créer ou modifier des champs de formulaire interactifs (y compris les champs de signature).


### FillForm {#FillForm}
```
public static final int FillForm
```


Remplir les champs de formulaire interactifs existants.

Gestionnaires de sécurité de la révision 3 ou supérieure : Remplir les champs de formulaire interactifs existants
(y compris les champs de signature), même si `#ModifyTextAnnotations.ModifyTextAnnotations` est désactivé.


### ExtractContentWithDisabilities {#ExtractContentWithDisabilities}
```
public static final int ExtractContentWithDisabilities
```


Extraire le texte et les graphiques.

Gestionnaires de sécurité de la révision 3 ou supérieure : Extraire le texte et les graphiques
(pour soutenir l'accessibilité des utilisateurs handicapés ou à d'autres fins).


### AssembleDocument {#AssembleDocument}
```
public static final int AssembleDocument
```


Assembler le contenu.

Gestionnaires de sécurité de la révision 3 ou supérieure : Assembler le contenu (insérer, faire pivoter ou supprimer des pages
et créer des signets ou des images miniatures), même si `#ModifyContent.ModifyContent` est désactivé.


### PrintingQuality {#PrintingQuality}
```
public static final int PrintingQuality
```


Imprimer le contenu vers une représentation à partir de laquelle une copie numérique fidèle du document PDF pourrait être générée.

Gestionnaires de sécurité de la révision 3 ou supérieure : Imprimer le contenu vers une représentation à partir de laquelle une copie fidèle
d'une copie numérique du document PDF pourrait être générée. Lorsque ce bit est désactivé (et `#PrintDocument.PrintDocument`
est activé), l'impression est limitée à une représentation de bas niveau de l'apparence, éventuellement de qualité dégradée.


