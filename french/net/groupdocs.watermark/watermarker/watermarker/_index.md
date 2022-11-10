---
title: Watermarker
second_title: Référence de l'API GroupDocs.Watermark pour .NET
description: Initialise une nouvelle instance duWatermarkergroupdocs.watermark/watermarker classe avec le chemin de document spécifié.
type: docs
weight: 10
url: /fr/net/groupdocs.watermark/watermarker/watermarker/
---
## Watermarker(string) {#constructor_4}

Initialise une nouvelle instance du[`Watermarker`](../../watermarker) classe avec le chemin de document spécifié.

```csharp
public Watermarker(string filePath)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| filePath | String | Le chemin du fichier à partir duquel charger le document. |

### Exceptions

| exception | condition |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Le type de document fourni n'est pas pris en charge. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Le mot de passe fourni est incorrect. |

### Remarques

En savoir plus sur le chargement de documents : [Chargement de documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### Exemples

Charger et enregistrer un contenu de n'importe quel format pris en charge.

```csharp
// Charge un contenu depuis un fichier.
using (Watermarker watermarker = new Watermarker("D:\\input.pdf"))
{
    // Utilisez les méthodes de la classe Watermarker pour ajouter, rechercher ou supprimer des filigranes.

    // Enregistre le document.
    watermarker.Save("D:\\output.pdf");
}
```

### Voir également

* class [Watermarker](../../watermarker)
* espace de noms [GroupDocs.Watermark](../../watermarker)
* Assemblée [GroupDocs.Watermark](../../../)

---

## Watermarker(string, LoadOptions) {#constructor_5}

Initialise une nouvelle instance du[`Watermarker`](../../watermarker)class avec le chemin d'accès au document spécifié et les options de chargement.

```csharp
public Watermarker(string filePath, LoadOptions options)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| filePath | String | Le chemin du fichier à partir duquel charger le document. |
| options | LoadOptions | Options supplémentaires à utiliser lors du chargement d'un document. |

### Exceptions

| exception | condition |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Le type de document fourni n'est pas pris en charge. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Le mot de passe fourni est incorrect. |

### Remarques

En savoir plus sur le chargement de documents : [Chargement de documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### Exemples

Charger un document PDF crypté à l'aide d'un mot de passe.

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
loadOptions.Password = "123";
using (Watermarker watermarker = new Watermarker(@"C:\Documents\test.pdf", loadOptions))
{
    // ...
}
```

### Voir également

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [Watermarker](../../watermarker)
* espace de noms [GroupDocs.Watermark](../../watermarker)
* Assemblée [GroupDocs.Watermark](../../../)

---

## Watermarker(string, WatermarkerSettings) {#constructor_7}

Initialise une nouvelle instance du[`Watermarker`](../../watermarker) classe avec le chemin d'accès au document et les paramètres spécifiés .

```csharp
public Watermarker(string filePath, WatermarkerSettings settings)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| filePath | String | Le chemin du fichier à partir duquel charger le document. |
| settings | WatermarkerSettings | Paramètres supplémentaires à utiliser lorsque vous travaillez avec un document chargé. |

### Exceptions

| exception | condition |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Le type de document fourni n'est pas pris en charge. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Le mot de passe fourni est incorrect. |

### Remarques

En savoir plus sur le chargement de documents : [Chargement de documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### Exemples

Définir les objets interrogeables globalement (pour tous les documents qui seront chargés par la suite).

```csharp
WatermarkerSettings settings = new WatermarkerSettings();
settings.SearchableObjects = new SearchableObjects
{
    WordProcessingSearchableObjects = WordProcessingSearchableObjects.Hyperlinks
                                    | WordProcessingSearchableObjects.Text,
    SpreadsheetSearchableObjects = SpreadsheetSearchableObjects.HeadersFooters,
    PresentationSearchableObjects = PresentationSearchableObjects.SlidesBackgrounds
                                  | PresentationSearchableObjects.Shapes,
    DiagramSearchableObjects = DiagramSearchableObjects.None,
    PdfSearchableObjects = PdfSearchableObjects.All
};

foreach (string file in Directory.GetFiles(@"D:\files"))
{
    using (Watermarker watermarker = new Watermarker(file, settings))
    {
        PossibleWatermarkCollection watermarks = watermarker.Search();

        // Le code pour travailler avec les filigranes trouvés va ici.
    }
}
```

### Voir également

* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* espace de noms [GroupDocs.Watermark](../../watermarker)
* Assemblée [GroupDocs.Watermark](../../../)

---

## Watermarker(string, LoadOptions, WatermarkerSettings) {#constructor_6}

Initialise une nouvelle instance du[`Watermarker`](../../watermarker) classe avec le chemin d'accès au document spécifié , les options de chargement et les paramètres.

```csharp
public Watermarker(string filePath, LoadOptions options, WatermarkerSettings settings)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| filePath | String | Le chemin du fichier à partir duquel charger le document. |
| options | LoadOptions | Options supplémentaires à utiliser lors du chargement d'un document. |
| settings | WatermarkerSettings | Paramètres supplémentaires à utiliser lorsque vous travaillez avec un document chargé. |

### Exceptions

| exception | condition |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Le type de document fourni n'est pas pris en charge. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Le mot de passe fourni est incorrect. |

### Remarques

En savoir plus sur le chargement de documents : [Chargement de documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### Exemples

Rechercher des fragments de texte particuliers dans le corps/l'objet du message électronique.

```csharp
WatermarkerSettings settings = new WatermarkerSettings();
settings.SearchableObjects = new SearchableObjects
{
    EmailSearchableObjects = EmailSearchableObjects.Subject
                           | EmailSearchableObjects.HtmlBody
                           | EmailSearchableObjects.PlainTextBody
};
EmailLoadOptions loadOptions = new EmailLoadOptions();
using (Watermarker watermarker = new Watermarker(@"D:\test.msg", loadOptions, settings))
{
    SearchCriteria criteria = new TextSearchCriteria("test", false);
    // Remarque, la recherche n'est effectuée que si vous passez l'instance TextSearchCriteria à la méthode Search
    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    // Supprime les fragments de texte trouvés
    watermarks.Clear();
    // Sauvegarder les modifications
    watermarker.Save();
}
```

### Voir également

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* espace de noms [GroupDocs.Watermark](../../watermarker)
* Assemblée [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream) {#constructor}

Initialise une nouvelle instance du[`Watermarker`](../../watermarker) classe avec le flux spécifié.

```csharp
public Watermarker(Stream document)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| document | Stream | Le flux à partir duquel charger le document. |

### Exceptions

| exception | condition |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Le type de document fourni n'est pas pris en charge. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Le mot de passe fourni est incorrect. |

### Remarques

En savoir plus sur le chargement de documents [Chargement de documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### Exemples

Chargez et enregistrez un document de n'importe quel format pris en charge.

```csharp
// Charge un contenu à partir d'un flux.
using (FileStream inputStream = File.Open("D:\\input.pdf", FileMode.Open))
using (FileStream outputStream = File.Open("D:\\output.pdf", FileMode.Create))
using (Watermarker watermarker = new Watermarker(inputStream))
{
    // Utilisez les méthodes de la classe Watermarker pour ajouter, rechercher ou supprimer des filigranes.

    // Sauvegarder les modifications.
    watermarker.Save(outputStream);
}
```

### Voir également

* class [Watermarker](../../watermarker)
* espace de noms [GroupDocs.Watermark](../../watermarker)
* Assemblée [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, LoadOptions) {#constructor_1}

Initialise une nouvelle instance du[`Watermarker`](../../watermarker) classe avec les options stream et load spécifiées.

```csharp
public Watermarker(Stream document, LoadOptions options)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| document | Stream | Le flux à partir duquel charger le document. |
| options | LoadOptions | Options supplémentaires à utiliser lors du chargement d'un document. |

### Exceptions

| exception | condition |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Le type de document fourni n'est pas pris en charge. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Le mot de passe fourni est incorrect. |

### Remarques

En savoir plus sur le chargement de documents [Chargement de documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### Exemples

Charger un document PDF crypté à l'aide du mot de passe

```csharp
PdfLoadOptions loadOptions = new PdfLoadOptions();
loadOptions.Password = "123";
using (FileStream fileStream = File.Open(@"C:\Documents\test.pdf", FileMode.Open))
using (Watermarker watermarker = new Watermarker(fileStream, loadOptions))
{
    // ...
}
```

### Voir également

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [Watermarker](../../watermarker)
* espace de noms [GroupDocs.Watermark](../../watermarker)
* Assemblée [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, WatermarkerSettings) {#constructor_3}

Initialise une nouvelle instance du[`Watermarker`](../../watermarker) classe avec le stream et les paramètres spécifiés.

```csharp
public Watermarker(Stream document, WatermarkerSettings settings)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| document | Stream | Le flux à partir duquel charger le document. |
| settings | WatermarkerSettings | Paramètres supplémentaires à utiliser lorsque vous travaillez avec un document chargé. |

### Exceptions

| exception | condition |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Le type de document fourni n'est pas pris en charge. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Le mot de passe fourni est incorrect. |

### Remarques

En savoir plus sur le chargement de documents [Chargement de documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### Exemples

Définir les objets interrogeables globalement (pour tous les documents qui seront chargés par la suite).

```csharp
WatermarkerSettings settings = new WatermarkerSettings();
settings.SearchableObjects = new SearchableObjects
{
    WordProcessingSearchableObjects = WordProcessingSearchableObjects.Hyperlinks
                                    | WordProcessingSearchableObjects.Text,
    SpreadsheetSearchableObjects = SpreadsheetSearchableObjects.HeadersFooters,
    PresentationSearchableObjects = PresentationSearchableObjects.SlidesBackgrounds
                                  | PresentationSearchableObjects.Shapes,
    DiagramSearchableObjects = DiagramSearchableObjects.None,
    PdfSearchableObjects = PdfSearchableObjects.All
};

foreach (string file in Directory.GetFiles(@"D:\files"))
{
    using (FileStream fileStream = File.Open(file, FileMode.Open))
    using (Watermarker watermarker = new Watermarker(fileStream, settings))
    {
        PossibleWatermarkCollection watermarks = watermarker.Search();

        // Le code pour travailler avec les filigranes trouvés va ici.
    }
}
```

### Voir également

* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* espace de noms [GroupDocs.Watermark](../../watermarker)
* Assemblée [GroupDocs.Watermark](../../../)

---

## Watermarker(Stream, LoadOptions, WatermarkerSettings) {#constructor_2}

Initialise une nouvelle instance du[`Watermarker`](../../watermarker) classe avec le flux spécifié, charger les options et les paramètres.

```csharp
public Watermarker(Stream document, LoadOptions options, WatermarkerSettings settings)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| document | Stream | Le flux à partir duquel charger le document. |
| options | LoadOptions | Options supplémentaires à utiliser lors du chargement d'un document. |
| settings | WatermarkerSettings | Paramètres supplémentaires à utiliser lorsque vous travaillez avec un document chargé. |

### Exceptions

| exception | condition |
| --- | --- |
| [UnsupportedFileTypeException](../../../groupdocs.watermark.exceptions/unsupportedfiletypeexception) | Le type de document fourni n'est pas pris en charge. |
| [InvalidPasswordException](../../../groupdocs.watermark.exceptions/invalidpasswordexception) | Le mot de passe fourni est incorrect. |

### Remarques

En savoir plus sur le chargement de documents [Chargement de documents](https://docs.groupdocs.com/display/watermarknet/Loading+documents) .

### Exemples

Rechercher des fragments de texte particuliers dans le corps/l'objet du message électronique.

```csharp
WatermarkerSettings settings = new WatermarkerSettings();
settings.SearchableObjects = new SearchableObjects
{
    EmailSearchableObjects = EmailSearchableObjects.Subject
                           | EmailSearchableObjects.HtmlBody
                           | EmailSearchableObjects.PlainTextBody
};
EmailLoadOptions loadOptions = new EmailLoadOptions();
using (FileStream fileStream = File.Open(@"D:\test.msg", FileMode.Open))
using (Watermarker watermarker = new Watermarker(fileStream, loadOptions, settings))
{
    SearchCriteria criteria = new TextSearchCriteria("test", false);
    // Remarque, la recherche n'est effectuée que si vous passez l'instance TextSearchCriteria à la méthode Search
    PossibleWatermarkCollection watermarks = watermarker.Search(criteria);
    // Supprime les fragments de texte trouvés
    watermarks.Clear();
    // Sauvegarder les modifications
    watermarker.Save();
}
```

### Voir également

* class [LoadOptions](../../../groupdocs.watermark.options/loadoptions)
* class [WatermarkerSettings](../../watermarkersettings)
* class [Watermarker](../../watermarker)
* espace de noms [GroupDocs.Watermark](../../watermarker)
* Assemblée [GroupDocs.Watermark](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Watermark.dll -->
