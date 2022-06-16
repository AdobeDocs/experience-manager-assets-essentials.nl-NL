---
title: Release-opmerkingen
description: Opmerkingen bij de release en bekende problemen met [!DNL Assets Essentials]
role: User,Leader,Admin,Architect,Developer
contentOwner: AK
exl-id: a0e29eb6-336a-4f78-b7bd-ec1338c86775
source-git-commit: 7c6293bb99d5be8084e6998da966bb89be9c714e
workflow-type: tm+mt
source-wordcount: '885'
ht-degree: 0%

---

# Opmerkingen bij de release van [!DNL Assets Essentials] {#release-notes}

De huidige release van [!DNL Assets Essentials] wordt vrijgegeven op 16 juni 2022.

Deze release biedt:

**Verbeteringen voor status van element**

* Met Assets Essentials kunt u nu [een vervaldatum voor een actief instellen](manage-organize.md#set-asset-status). Bovendien kunt u [filterelementen](search.md#refine-search-results) op basis van de `Expired` de status van de activa en een vervaldatumwaaier.

* U kunt nu de statusindicator van het element weergeven voor alle middelen die beschikbaar zijn in de prullenbak. Hierdoor kunt u een beslissing nemen om een element te herstellen op basis van de status.

**Verbeteringen in zoekfilters**

* Met Assets Essentials kunt u nu [filterelementen](search.md#refine-search-results) met de `No Status` status van het element.

<!--

* Assets Essentials now supports [using a wildcard operator (*) while using custom filters](search.md#custom-filters) to enable Assets Essentials to display assets in the results that partially match the search criteria.

-->

**Verbeteringen voor verzamelingen**

<!--

* Assets Essentials now enables you to [create Private collections](manage-collections.md#create-collection).

-->

* Assets Essentials biedt nu ondersteuning voor [een verzameling downloaden](manage-collections.md).

* U kunt nu het metagegevensveld Beschrijving voor een verzameling bewerken.

**Verbeterde documentatie**

* Een nieuwe versie van de [Assets Essentials - overzichtsdocumentatie](introduction.md) is nu beschikbaar.

**Verbeteringen gebaseerd op feedback van klanten**

* Verbeteringen en foutoplossingen op basis van feedback van klanten.


## Bekende problemen {#known-issues}

De lijst met bekende problemen van [!DNL Assets Essentials] Het aanbod wordt voortdurend herzien en bijgewerkt:

* Assets Essentials biedt geen ondersteuning voor het maken van privéverzamelingen.

Als u problemen of zelfs verbeteringsverzoeken tegenkomt, [feedback geven](#provide-feedback) naar het team.

## Eerdere versies {#past-release}

### 2022,4,0 {#april-2022}

De huidige release van [!DNL Assets Essentials] wordt vrijgegeven op 12 mei 2022. Deze release biedt:

* [!DNL Assets Essentials] now supports [verzamelingen maken](manage-collections.md). Een verzameling is een set elementen binnen Experience Manager Assets Essentials. Gebruik verzamelingen om elementen tussen gebruikers te delen. In tegenstelling tot mappen kan een verzameling elementen van verschillende locaties bevatten.

* Met Assets Essentials kunt u nu ook [Aangepaste filters toevoegen](search.md#custom-filters) naar de gebruikersinterface. Vervolgens kunt u deze aangepaste filters naast de standaardfilters toepassen om de zoekresultaten te verfijnen.

* Met Assets Essentials kunt u nu [status instellen](manage-organize.md#set-asset-status) op activa die beschikbaar zijn in de repository. Stel een elementstatus in om het downstreamgebruik van digitale elementen beter te beheren en te beheren.

* Verbeteringen en foutoplossingen op basis van feedback van klanten.

#### Incognitomodus in Chrome {#incognito-mode}

Met deze release optimaliseren we de prestaties van de levering van de gebruikersinterface en de specifieke functies in Assets Essentials - opmerkingen maken over elementen en beeldbewerking - afhankelijk van de lokale opslag in de browser en van cookies van derden. De incognitomodus in de Chrome-webbrowser blokkeert cookies van derden standaard. Gebruikers hebben een aantal opties om toegang te blijven krijgen tot alle mogelijkheden:

* Gebruik Chrome-profielen in plaats van Incognito-modus wanneer de gebruiker browsersessies moet scheiden

* Schakel de `Block third-party cookies` op het scherm Incognito-modus in Chrome

### 2022,2,0 {#march-2022}

[!DNL Assets Essentials] wordt gepubliceerd op 9 maart 2022, met de volgende updates:

* [!DNL Assets Essentials] nu kunt u [een koppeling tot stand brengen en middelen delen met externe belanghebbenden](share-links-for-assets.md), die geen toegang hebben tot [!DNL Assets Essentials] toepassing. U kunt een vervaldatum voor de verbinding bepalen en dan het delen met anderen gebruikend uw aangewezen communicatie methode zoals e-mail of overseinendiensten. Ontvangers van de koppeling kunnen een voorbeeld van de elementen bekijken en deze downloaden.

* De [!DNL Assets Essentials] now includes [een beheerdersproductprofiel](deploy-administer.md#add-users-to-essentials) Admin Console, naast de bestaande normale productprofielen en de profielen van consumentenproducten. Een beheerder kan nu andere gebruikers toewijzen aan het beheerdersproductprofiel.

* In Assets Essentials kunnen beheerders nu: [de toegangsniveaus beheren voor mappen die beschikbaar zijn in de opslagplaats](manage-permissions.md). Als beheerder, kunt u gebruikersgroepen tot stand brengen en toestemmingen aan die groepen toewijzen om toegangsniveaus te beheren. U kunt de bevoegdheden voor machtigingsbeheer ook delegeren aan gebruikersgroepen op mapniveau.

* Verbeteringen en foutoplossingen op basis van feedback van klanten.

Daarnaast [!DNL Adobe Asset Link] een extensie voor Creative Cloud (Photoshop, Illustrator en InDesign) uitgebracht. [nieuwe versie 3.2](https://exchange.adobe.com/creativecloud.details.106875.adobe-asset-link-cep.html)met prestatieverbeteringen in de opstarttijd van het deelvenster en de downloadsnelheid.


### release 2022.1.0 {#january-2022}

[!DNL Assets Essentials] wordt gepubliceerd op 3 februari 2022, met de volgende updates:

* Prestatieverbeteringen voor de [!UICONTROL Create Folder] bewerking. <!-- CQ-4338818 -->

### release 2021.11.0 {#november-2021}

[!DNL Assets Essentials] wordt gepubliceerd op 16 december 2021, met de volgende updates:

* Adobe implementeert Assets Essentials automatisch nadat het inrichtingsproces is voltooid. De beheerders hoeven geen extra stappen uit te voeren om Assets Essentials te implementeren met [!DNL Cloud Manager] gebruikersinterface. Deze automatische implementatie is beschikbaar voor omgevingen die na 6 januari 2022 zijn ingericht.
* Nieuwe versies van Creative Cloud-plug-ins die werken met Assets Essentials zijn beschikbaar op Adobe Exchange - [Adobe Asset Link voor Adobe XD v 2.1.0](https://exchange.adobe.com/creativecloud/plugindetails.html/app/cc/61d229b9) en [Adobe Asset Link voor Photoshop / InDesign / Illustrator v 3.1.65](https://exchange.adobe.com/creativecloud.details.106875.adobe-asset-link-cep.html).
* Verschillende foutoplossingen en productverbeteringen, inclusief bekende problemen (mappen worden nu correct weergegeven in de linkernavigatiestructuur na het uploaden)<!-- CQ-4337638 -->, uploaden via slepen en neerzetten zorgt ervoor dat de gebruiker de huidige map of een submap kan selecteren bij het neerzetten voor uploaden<!-- CQ-4327753 -->).

### release 2021.8.0 {#august2021}

[!DNL Assets Essentials] 2021.8.0 wordt gepubliceerd op 30 augustus 2021, met de volgende updates:

* Integratie met [!DNL Adobe Workfront] die [!DNL Workfront] gebruikers beheren hun digitale middelen in de context van het beheer van hun werk. Zie voor meer informatie [integratie met andere Adobe-oplossingen](/help/integration.md).

### release 2021.7.0 {#july2021}

[!DNL Assets Essentials] 2021.7.0 wordt gepubliceerd op 29 juli 2021, met de volgende updates:

* U kunt aangepaste metagegevensformulieren maken en beheren die worden gebruikt voor de weergave van eigenschappen van metagegevens voor gebruikers in het scherm met middelendetails [!UICONTROL Metadata Forms] optie onder [!DNL Settings]. Zie [metagegevensformulieren](metadata.md#metadata-forms).
* Verschillende opgeloste problemen en productverbeteringen, waaronder betere prestaties bij het uploaden van een geneste map met veel submappen.

### 2021.6.0-release {#june2021}

De eerste release van [!DNL Assets Essentials], beschikbaar gesteld op 21 juni 2021, biedt lichte mogelijkheden voor middelenbeheer. De volgende belangrijke functies en CRUD-bewerkingen (maken, lezen, bijwerken en verwijderen) worden ondersteund:

* Upload en voeg elementen toe, waaronder geneste mappen. Geef een voorvertoning weer van de elementen en versies.
* Volledige-tekstonderzoek, genummerde onderzoeksfilters, en bewaarde onderzoeken voor snelle activaontdekking.
* Basisbewerkingen voor middelenbeheer, zoals het bijwerken, verwijderen, downloaden en beheren van metagegevens.
* [!DNL Assets Essentials] is beschikbaar voor [!DNL Adobe Journey Optimizer] gebruikers om de elementen te beheren wanneer ze berichten maken. Zie voor meer informatie [integratie met andere Adobe-oplossingen](/help/integration.md).
