---
title: Middelen zoeken en ontdekken in [!DNL Assets Essentials]
description: Middelen zoeken en ontdekken in [!DNL Assets Essentials].
role: User
exl-id: be9597a3-056c-436c-a09e-15a03567c85a
source-git-commit: 92cfe963d37df919b8bc29c49da7c8e9bd62638e
workflow-type: tm+mt
source-wordcount: '1458'
ht-degree: 0%

---

# Middelen zoeken in [!DNL Assets Essentials] {#search-assets}

>[!CONTEXTUALHELP]
>id="assets_search"
>title="Zoeken in middelen"
>abstract="Zoek naar activa door een sleutelwoord in de bar van het Onderzoek te specificeren of door activa te filtreren die op hun status, dossiertype, MIME type, grootte, verwezenlijking, wijziging, en vervaldata worden gebaseerd. Naast de standaardfilters kunt u ook aangepaste filters toepassen. U kunt de gefilterde resultaten opslaan als een opgeslagen zoekopdracht of als een slimme verzameling."
>additional-url="https://experienceleague.adobe.com/docs/experience-manager-assets-essentials/help/manage-collections.html?lang=en#manage-smart-collection" text="Slimme verzamelingen maken"

[!DNL Assets Essentials] biedt effectief zoeken, dat werkt standaard. De zoekopdracht is uitgebreid omdat er in volledige tekst wordt gezocht. Met de krachtige zoekfunctionaliteit kunt u snel de juiste middelen vinden en de snelheid van de inhoud verbeteren. [!DNL Assets Essentials] biedt zoekopdrachten in volledige tekst en zoekopdrachten via metagegevens, zoals slimme tags, titel, gemaakte datum en copyright.

Als u elementen wilt zoeken,

* Klik in het zoekvak boven aan de pagina. Standaard wordt gezocht in de map waarin u momenteel bladert. Voer een van de volgende handelingen uit:

  ![zoekvak](assets/search-box.png)

   * Zoeken met een trefwoord en desgewenst map wijzigen. Druk op Return.

   * Begin met het werken met een onlangs weergegeven element door er direct naar te zoeken. Klik in het zoekvak en selecteer een element dat onlangs is weergegeven in de suggesties.

## De zoekresultaten filteren {#refine-search-results}

U kunt de zoekresultaten filteren op basis van de volgende parameters.

![Zoekfilters](assets/filters1.png)

*Afbeelding: gezochte elementen filteren op basis van verschillende parameters.*

* De Status van het element: Filter de onderzoeksresultaten gebruikend een `Approved`, `Rejected`, of `No Status` status van het element.

* Bestandstype: filtreer de zoekresultaten op de ondersteunde bestandstypen, namelijk `Images`, `Documents`, en `Videos`.
* MIME-type: filter voor een of meer ondersteunde bestandsindelingen. <!-- TBD:  [supported file formats](/help/using/supported-file-formats.md). -->
* Afbeeldingsgrootte: geef een van de minimale en maximale afmetingen op voor het filteren van afbeeldingen. De grootte wordt opgegeven in pixelafmetingen en is niet de bestandsgrootte van de afbeeldingen.
* Aanmaakdatum: de aanmaakdatum van het element zoals vermeld in de metagegevens. De standaard datumnotatie die wordt gebruikt is `yyyy-mm-dd`.
* Gewijzigde datum: de datum waarop de elementen als laatste zijn gewijzigd. De standaard datumnotatie die wordt gebruikt is `yyyy-mm-dd`.

* Vervaldatum: filter de zoekresultaten op basis van een `Expired` status van het element. Daarnaast kunt u een datumbereik voor de vervaldatum voor elementen opgeven om de zoekresultaten verder te filteren.

* Aangepaste filters: [Aangepaste filters toevoegen](#custom-filters) naar Assets Essentials gebruikersinterface. Pas de aangepaste filters toe naast de standaardfilters om de zoekresultaten te verfijnen.

U kunt de gezochte middelen in stijgende of dalende orde van sorteren `Name`, `Relevance`, `Size`, `Modified`, en `Created`. De gezochte elementen worden gesorteerd op `Relevance`, standaard.

## Aangepaste filters beheren {#custom-filters}

**Vereiste machtigingen:**  `Can Edit`, `Owner`of Beheerder.

Met Assets Essentials kunt u ook aangepaste filters toevoegen aan de gebruikersinterface. Vervolgens kunt u deze aangepaste filters toepassen naast de [standaardfilters](#refine-search-results) om de zoekresultaten te verfijnen.

Assets Essentials bieden de volgende aangepaste filters:

<table>
    <tbody>
     <tr>
      <th><strong>Aangepaste filternaam</strong></th>
      <th><strong>Beschrijving</strong></th>
     </tr>
     <tr>
      <td>Titel</td>
      <td>Filter elementen met de titel van het element. De titel die u opgeeft in de hoofdlettergevoelige zoekcriteria moet overeenkomen met de exacte titel van het element om in de resultaten te worden weergegeven.</td>
     </tr>
     <tr>
      <td>Naam</td>
      <td>Filter elementen met de naam van het elementbestand. De naam die u opgeeft in de hoofdlettergevoelige zoekcriteria moet overeenkomen met de exacte bestandsnaam van het element om in de resultaten te worden weergegeven.</td>
     </tr>
     <tr>
      <td>Elementgrootte</td>
      <td>Filter elementen door een formaatbereik in bytes te definiëren in de zoekcriteria voor een element dat in de resultaten moet worden weergegeven.</td>
     </tr>
     <tr>
      <td>Vooraf gedefinieerde labels</td>
      <td>Filter elementen met de slimme tag voor elementen. De naam van de slimme tag die u opgeeft in de hoofdlettergevoelige zoekcriteria, moet overeenkomen met de exacte naam van de slimme tag van het element om in de resultaten te worden weergegeven. U kunt niet meerdere slimme tags opgeven in zoekcriteria.</td>
     </tr>    
    </tbody>
   </table>

<!--
   You can use a wildcard operator (*) to enable Assets Essentials to display assets in the results that partially match the search criteria. For example, if you define <b>ma*</b> as the search criteria, Assets Essentials displays assets with title, such as, market, marketing, man, manchester, and so on in the results.

   You can use a wildcard operator (*) to enable Assets Essentials to display assets in the results that partially match the search criteria.

   You can use a wildcard operator (*) to enable Assets Essentials to display assets in the results that partially match the search criteria. You can specify multiple smart tags separated by a comma in the search criteria.

   -->

### Aangepaste filters toevoegen {#add-custom-filters}

Aangepaste filters toevoegen:

1. Klik op **[!UICONTROL Filters]**.

1. In de **[!UICONTROL Custom Filters]** sectie, klikken **[!UICONTROL Edit]** of **[!UICONTROL Add Filters]**.

   ![Aangepaste filters toevoegen](assets/add-custom-filters.png)

1. Op de **[!UICONTROL Custom filters management]** selecteert u de filters die u aan de bestaande lijst met filters wilt toevoegen. Selecteren **[!UICONTROL Custom Filters]** om alle filters te selecteren.

1. Klikken **[!UICONTROL Confirm]** om de filters aan de gebruikersinterface toe te voegen.

### Aangepaste filters verwijderen {#remove-custom-filters}

Aangepaste filters verwijderen:

1. Klik op **[!UICONTROL Filters]**.

1. In de **[!UICONTROL Custom Filters]** sectie, klikken **[!UICONTROL Edit]**.

1. Op de **[!UICONTROL Custom filters management]** schakelt u de filters uit die u uit de bestaande lijst met filters wilt verwijderen.

1. Klikken **[!UICONTROL Confirm]** om de filters uit de gebruikersinterface te verwijderen.

## Middelen zoeken met [!DNL Adobe Firefly] {#search-firefly}

U kunt zoeken naar elementen die niet beschikbaar zijn in een van de mappen met elementen door de opdracht [!DNL Adobe Firefly] zoekfunctie voor elementen binnen [!DNL Experience Manager Assets]. Op deze manier kunt u op efficiënte wijze elementen in real-time genereren die niet in de mappen met elementen zijn opgeslagen.

### Voordat u begint

U moet een actieve [!DNL Adobe Express] abonnement.

### Elementen genereren

Nieuwe elementen genereren met [!DNL Adobe Firefly]:

1. Ga naar de [!DNL AEM Assets] werkruimte.
1. Typ de naam van het element in de zoekbalk boven aan de pagina.<br>
U kunt bijvoorbeeld een element zoeken met het trefwoord `Bugatti Type 57`. Bij het zoeken naar het element worden geen resultaten gevonden, omdat het element in geen van de elementmappen aanwezig is.
1. Typ de elementnaam in de zoekbalk midden op de pagina en klik op **[!UICONTROL Generate]**.
   ![Integratie van Fireflys](firefly-integration.jpg)
   *Afbeelding: Geen resultaten gevonden voor Bugatti Type 57 in de elementenmap.*<br>
De nieuwe elementen worden gegenereerd.
   ![Integratie van Fireflys](assets/bugatti-type-57.jpg)
   *Afbeelding: Referentie-elementen doorzocht met [!DNL Adobe Firefly] zoekfunctie voor middelen.* <br>
U kunt deze elementen uploaden naar de map van uw voorkeur, zodat u ze gemakkelijk kunt openen.

### Elementen uploaden

Het gegenereerde element uploaden naar de gegevensopslagplaats:

1. Klik op **[!UICONTROL Upload]**.
1. Selecteer de elementmap waarnaar u het element wilt uploaden en klik op **[!UICONTROL Select Folder]**.
   ![Element uploaden](assets/upload-asset-firefly.jpg)
   *Afbeelding: selecteer de map die u wilt uploaden.*

## Opgeslagen zoekopdrachten {#saved-search}

Zoekfuncties zijn heel eenvoudig in [!DNL Assets Essentials]. Vanuit het zoekvak kunt u niet alleen een trefwoord typen en op Enter drukken om de resultaten weer te geven, maar u kunt ook snel met één klik nogmaals zoeken naar de laatst doorzochte trefwoorden.

U kunt de zoekresultaten ook filteren op basis van specifieke criteria voor metagegevens en het type element. Voor veelgebruikte filters om de zoekervaring te verbeteren, [!DNL Assets Essentials] Hiermee kunt u de zoekparameters opslaan. Vervolgens kunt u de opgeslagen zoekopdracht selecteren en het filter toepassen met één klik.

Als u een opgeslagen zoekopdracht wilt maken, zoekt u naar een element, past u een of meer filters toe en klikt u op **[!UICONTROL Save as]** > **[!UICONTROL Saved Search]** in de [!UICONTROL Filters] deelvenster. U kunt ook op **[!UICONTROL Save as]** en selecteert u **[!UICONTROL Smart Collection]** om de resultaten op te slaan als een slimme verzameling. Zie [Een slimme verzameling maken](manage-collections.md#create-a-smart-collection) voor meer informatie .

![Slimme verzameling maken](assets/create-smart-collection.png)

<!-- TBD: Search behavior. Full-text search. Ranking and rank boosts. Hidden assets.
Report poor UX that users can only save a filtered search and not a simple search.
.
Are other supported files fully indexed and support full-text search? Eg. audio/videos files can at best have metadata indexed.
Anything about ranking of assets displayed in search results?

What about temporarily hiding an asset (suspending search on it) from the search results? If an asset is undergoing review collaboration, should it be used by others? Should it be hidden in search?

When userA is searching and userB add an asset that matches search results, will the asset display in search as soon as userA refreshes the page? Assuming indexing is near real-time. May not be so for bulk uploads.
-->

## Werken met zoekresultaten {#work-with-search-results}

U kunt de elementen selecteren die in de zoekresultaten worden weergegeven en de volgende handelingen uitvoeren:

* **Vergelijkbare afbeelding zoeken**: Zoek vergelijkbare afbeeldingselementen in de interface Middelen op basis van de metagegevens en slimme tags.

* **Details**: Elementeigenschappen weergeven en bewerken.

* **Downloaden**: Download een middel.

* **Toevoegen aan verzameling**: Voeg het geselecteerde element toe aan een verzameling.

* **Vastmaken aan snelle toegang**: [Een element vastzetten](my-workspace.md) voor snellere toegang wanneer u het later nodig hebt. Alle vastgezette items worden weergegeven in het dialoogvenster **Snelle toegang** van Mijn werkruimte.

* **Openen in Adobe Express**: Bewerk een afbeelding in de geïntegreerde Adobe Express vanuit het Experience Manager Assets-scherm.

* **Bewerken**: Bewerk de afbeelding met Adobe Express.

* **Koppeling delen**: [Koppelingen delen](share-links-for-assets.md) voor een middel met andere gebruikers zodat zij tot het kunnen toegang hebben en downloaden.

* **Verwijderen**: Een element verwijderen.

* **Kopiëren**: Kopieer een element naar een andere maplocatie.

* **Verplaatsen**: Verplaats een element naar een andere maplocatie.

* **Naam wijzigen**: Wijzig de naam van een element.

* **Kopiëren naar bibliotheken**: Voeg een element toe aan de bibliotheek.

* **Taken toewijzen**: Taken toewijzen aan gebruikers voor een element.

* **Controle**: [De bewerkingen controleren](manage-notifications.md) uitgevoerd op een element.

## Eerste homepage van zoekopdracht configureren {#configuring-search-first-homepage}

Met Assets Essentials kunt u de standaardbestemmingspagina voor uw organisatie selecteren. Wanneer u de startpagina Zoekopdracht eerst gebruikt, hebt u ook de mogelijkheid om de branding van de pagina aan te passen door de achtergrond- en logoafbeeldingen zo te configureren dat deze overeenkomen met uw merk.

Voer de onderstaande stappen uit om de eerste homepage van de zoekopdracht te configureren:

1. Ga naar **[!UICONTROL Settings]** > **[!UICONTROL General Settings]**.
1. Selecteer **[!UICONTROL Search first]**. Het opent verder onderzoek eerst verwante configuratie. U kunt instellen [uitlijning](#setting-alignment-search-bar) of [achtergrond- en logoafbeelding instellen](#setting-background-image-and-logo) van uw homepage.

### Uitlijning van zoekbalk instellen {#setting-alignment-search-bar}

[!DNL Assets Essentials] kunt u de uitlijning van de zoekbalk wijzigen. U kunt de zoekbalk in het midden of boven aan het scherm weergeven. Selecteer de gewenste uitlijning en klik op **[!UICONTROL Save]**.

![Eerste homepage-uitlijning zoeken](assets/search-first-alignment.png)

### Achtergrond- en logoafbeelding van homepage instellen {#setting-background-image-and-logo}

U kunt het merklogo en de achtergrondafbeelding toevoegen aan uw eerste zoekpagina. Voer de volgende stappen uit:

1. Navigeren naar **[!UICONTROL Background and Logo image]** deel onder **[!UICONTROL Homepage]**.
1. Klikken **[!UICONTROL Replace]** om afbeeldingen te zoeken in de bestaande gegevensopslagruimte.
1. Klik op **[!UICONTROL Save]**. [Voorvertoning](#preview-configured-homepage) de wijzigingen om de wijzigingen te herzien.

### Voorvertoning geconfigureerde homepage {#preview-configured-homepage}

U kunt een voorvertoning weergeven om de lay-out en opmaak van de eerste homepage van de zoekopdracht te controleren. Gebruiken **[!UICONTROL Preview]** kunt u de layout herstellen of de layout naar wens wijzigen. Voer de onderstaande stappen uit om een voorvertoning van de geconfigureerde homepage weer te geven:

1. Klikken **[!UICONTROL General Settings]** en selecteert u **[!UICONTROL Search first]**.
1. Navigeren naar **[!UICONTROL Customize search first homepage]** en klik op **[!UICONTROL Preview]**. Doorschakelen **[!UICONTROL Dark theme]** om de homepage in het donkere of lichte thema voor te vertonen.
1. Klikken **[!UICONTROL Close]** om het voorvertoningsscherm te sluiten.

   ![Eerste homepatievoorvertoning zoeken](assets/search-first-preview.gif)

## Volgende stappen {#next-steps}

* [Een video bekijken om elementen in Assets Essentials te zoeken](https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/basics/using.html)

* Feedback geven op het product met de [!UICONTROL Feedback] optie beschikbaar in de gebruikersinterface van Assets Essentials

* Documentfeedback geven met [!UICONTROL Edit this page] ![de pagina bewerken](assets/do-not-localize/edit-page.png) of [!UICONTROL Log an issue] ![een GitHub-probleem maken](assets/do-not-localize/github-issue.png) beschikbaar op de rechterzijbalk

* Contact [Klantenservice](https://experienceleague.adobe.com/?support-solution=General#support)
