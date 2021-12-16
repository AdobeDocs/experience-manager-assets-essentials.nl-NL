---
title: Release-opmerkingen
description: Opmerkingen bij de release en bekende problemen met [!DNL Assets Essentials]
role: User,Leader,Admin,Architect,Developer
contentOwner: AG
exl-id: a0e29eb6-336a-4f78-b7bd-ec1338c86775
source-git-commit: 0c849c92562f9102819aaea627f5945030b27a1e
workflow-type: tm+mt
source-wordcount: '380'
ht-degree: 0%

---

# Opmerkingen bij de release van [!DNL Assets Essentials] {#release-notes}

De huidige release van [!DNL Assets Essentials] wordt vrijgegeven op 16 december 2021. Met deze release:

* Adobe implementeert Assets Essentials automatisch nadat het inrichtingsproces is voltooid. De beheerders hoeven geen extra stappen uit te voeren om Assets Essentials te implementeren met [!DNL Cloud Manager] gebruikersinterface. Deze automatische implementatie is beschikbaar voor omgevingen die na 6 januari 2022 zijn ingericht.
* Nieuwe versies van Creative Cloud-plug-ins die werken met Assets Essentials zijn beschikbaar op Adobe Exchange - [Adobe Asset Link voor Adobe XD v 2.1.0](https://exchange.adobe.com/creativecloud/plugindetails.html/app/cc/61d229b9) en [Adobe Asset Link voor Photoshop / InDesign / Illustrator v 3.1.65](https://exchange.adobe.com/creativecloud.details.106875.adobe-asset-link-cep.html).
* Verschillende foutoplossingen en productverbeteringen, inclusief bekende problemen (mappen worden nu correct weergegeven in de linkernavigatiestructuur na het uploaden)<!-- CQ-4337638 -->, uploaden via slepen en neerzetten zorgt ervoor dat de gebruiker de huidige map of een submap kan selecteren bij het neerzetten voor uploaden<!-- CQ-4327753 -->).

Als u meer wilt weten over de oplossing, raadpleegt u de [inleiding tot [!DNL Assets Essentials]](introduction.md). Als u de functies wilt gaan gebruiken, raadpleegt u [Aan de slag](/help/get-started.md).

## Bekende problemen {#known-issues}

De lijst met bekende problemen van [!DNL Assets Essentials] Het aanbod wordt voortdurend herzien en bijgewerkt:

* Afzonderlijke elementen kunnen niet naar de bovenste map (Middelen) worden geüpload, alleen naar een submap in het systeem. <!-- CQ-4337638 -->

Als u problemen of zelfs verbeteringsverzoeken tegenkomt, [feedback geven](#provide-feedback) naar het team.

## Eerdere versies {#past-release}

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
