---
title: Ondersteunde bestandsindelingen
description: Ondersteunde bestandsindelingen voor de verschillende gebruiksgevallen van [!DNL Assets Essentials]
role: User,Leader,Administrator,Architect,Developer
contentOwner: AG
source-git-commit: 5bae37e18ac587aaacaa004e5ec02775888d7f9a
workflow-type: tm+mt
source-wordcount: '196'
ht-degree: 9%

---


# Ondersteuning voor bestandsindelingen in [!DNL Assets Essentials] {#file-format-support}

[!DNL Assets Essentials] ondersteunt een groot aantal bestandsindelingen en elke functie biedt verschillende ondersteuning voor verschillende bestandstypen.

* ![afbeeldingsbestandstype ](assets/do-not-localize/image-icon.png) iconImages: GIF, JPG, PNG en TIFF
* ![documentbestandstype ](assets/do-not-localize/document-icon.png) iconDocuments: DOCX, PDF, PPTX en XLSX
* ![videobestandstype ](assets/do-not-localize/video-icon.png) iconVideos: MP4

De verschillende bestandstypen bieden verschillende ondersteuningsgraden voor de gebruiksgevallen en -functies, zoals hieronder wordt beschreven. Gebruik de legenda om het steunniveau te begrijpen.

| Ondersteuningsniveau | Beschrijving |
|---------------|-------------------------|
| ✓ | Ondersteund |
| * | voorwaardelijk ondersteund |
| - | Niet van toepassing |

* Andere taken op het gebied van vermogensbeheer:

## Elementen toevoegen, uploaden en weergeven {#support-to-upload-view}

<!-- TBD: For AEM, AI files require the PDF option to be selected when saving the AI file.
-->

| Type element | Bladeren | Kopiëren | Uploaden | Maken | Verwijderen | Details | Zoomen op afbeelding | Onlangs bekeken |
|---------------|----------|------|----------|----------|----------|----------|------------|-----------------|
| Rasterafbeeldingen | ✓ |  | ✓ | - | ✓ | ✓ | ✓ | ✓ |
| Mappen | ✓ |  | ✓ | ✓ | ✓ | ✓ | - | - |
| Video&#39;s | ✓ |  | ✓ | - | ✓ | * | - | ✓ |
| CC-bibliotheken | ✓ |  | ✓ | ✓ | ✓ | ✓ | - | - |
| PDF | ✓ |  | ✓ | - | ✓ | ✓ | - | ✓ |
| PSD | ✓ |  | ✓ | - | ✓ | * | - | ✓ |
| AI | ✓ |  | ✓ | - | ✓ | * | - | ✓ |
| INDD | ✓ |  | ✓ | - | ✓ | * | - | ✓ |

## Elementen zoeken, gebruiken en bewerken {#support-to-search-use-edit}

| Type element | Downloaden | Slepen en neerzetten | Afbeeldingseditor | Zoeken | Slimme tags | Naam wijzigen | Versies |
|---------------|----------|---------------|--------------|----------|------------|----------|----------|
| Rasterafbeeldingen | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ |
| Mappen | ✓ | ✓ | - | ✓ | - | ✓ | - |
| Video&#39;s | ✓ | ✓ | - | ✓ | ✓ | ✓ | - |
| CC-bibliotheken | - | - | - | - | - | ✓ | - |
| PDF | ✓ | ✓ | - | ✓ | ✓ | ✓ | - |
| PSD | ✓ | ✓ | - | ✓ | ✓ | ✓ | - |
| AI | ✓ | ✓ | - | ✓ | ✓ | ✓ | - |
| INDD | ✓ | ✓ | - | ✓ | ✓ | ✓ | - |

## Elementen controleren en samenwerken {#support-to-review-collaborate}

| Type element | Annoteren | Opmerking | Taken en revisie maken |
|---------------|----------|----------|-------------------------|
| Rasterafbeeldingen | ✓ | ✓ | ✓ |
| Mappen | - | - | - |
| Video&#39;s | - | ✓ | ✓ |
| CC-bibliotheken | - | - | - |
| PDF | - | ✓ | ✓ |
| PSD | - | ✓ | ✓ |
| AI | - | ✓ | ✓ |
| INDD | - | ✓ | ✓ |

## Overige taken voor vermogensbeheer {#support-to-manage-assets}

| Type element | Metagegevens | Uitvoeringen | Prullenbak | Kopiëren | Verplaatsen | [!DNL Adobe Asset Link] inchecken |
|---------------|----------|------------|----------|----------|----------|----------------------------------|
| Rasterafbeeldingen | * | ✓ | ✓ | ✓ | ✓ | ✓ |
| Mappen | * | - | ✓ | ✓ | ✓ | - |
| Video&#39;s | * | - | ✓ | ✓ | ✓ | - |
| CC-bibliotheken | * | - | - | - | - | - |
| PDF | * | - | ✓ | ✓ | ✓ | - |
| PSD | * | - | ✓ | ✓ | ✓ | - |
| AI | * | - | ✓ | ✓ | ✓ | - |
| INDD | * | - | ✓ | ✓ | ✓ | - |

<!-- TBD: Saving template table separately.
| Asset type    | Features |
|---------------|----------|
| Raster images |          |
| Folders       |          |
| Videos        |          |
| CC Libraries  |          |
| PDF files     |          |
| PSD           |          |
| AI            |          |
| INDD          |          |

>[!MORELIKETHIS]
>
>* []()
-->
