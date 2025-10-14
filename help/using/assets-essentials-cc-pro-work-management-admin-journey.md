---
title: Assets Essentials instellen voor Creative Cloud Pro met oplossingen voor werkbeheer
description: Dit leerprogramma introduceert een beheerderreis om de toepassing van Assets Essentials toe te laten om met de toepassingen van de Desktop van het Creative Cloud en de toepassing van Adobe Workfront te integreren. Tot de bureaubladtoepassingen voor Creatives Cloud behoren Adobe Photoshop, Adobe Illustrator, Adobe InDesign en Adobe XD.
exl-id: a5e9e0c3-35ec-41de-9656-f4f0f88946c7
source-git-commit: b1ae487b4b4e9a88e0d9c39889d3893d92a766c9
workflow-type: tm+mt
source-wordcount: '867'
ht-degree: 0%

---

# Assets Essentials voor Creative Cloud Pro met oplossingen voor werkbeheer {#creative-cloud-enterprise-user-journeys}

![&#x200B; Voorkeur om donker en licht thema &#x200B;](assets/cce-next-banner-landing-page.png) te schakelen

## Inleiding {#introduction}

Creative Cloud Pro voor ondernemingen met oplossingen voor werkbeheer integreert creatieve, content- en werkbeheertools om uw mogelijkheden om creatieve inhoud te produceren te vergroten en snel zakelijke doelen te bereiken. De oplossing omvat de volgende componenten:

* Creative Cloud Pro

* Adobe Workfront

* Experience Manager Assets Essentials

Dit leerprogramma introduceert een beheerderreis om de toepassing van Assets Essentials toe te laten om met de toepassingen van de Desktop van het Creative Cloud en de toepassing van Adobe Workfront te integreren. Tot de bureaubladtoepassingen voor Creatives Cloud behoren Adobe Photoshop, Adobe Illustrator, Adobe InDesign en Adobe XD.

## Implementatietypen {#deployment-types}

Aangezien de oplossing uit toepassingen en de diensten van zowel Creative Cloud als Adobe Experience Cloud bestaat, zouden zij in één of twee Admin Consoles van de Adobe voor uw bedrijf kunnen worden opgesteld.

In het geval van plaatsing in twee Admin Consoles, wordt een extra configuratiestap vereist:

* De diensten en de toepassingen van het Creative Cloud (Creative Cloud voor onderneming Pro en facultatieve modules) worden beheerd in [&#x200B; Adobe Admin Console voor uw plaatsing van het Creative Cloud &#x200B;](https://chl-author-preview.corp.adobe.com/content/help/en/enterprise/admin-guide.html).

* Adobe Workfront en Adobe Experience Manager Assets Essentials worden beheerd in [&#x200B; Adobe Admin Console voor de oplossingen van het Experience Cloud &#x200B;](https://experienceleague.adobe.com/docs/core-services/interface/administration/admin-getting-started.html?lang=nl-NL).

Om Creative Cloud en Assets Essentials toepassingen te integreren, moeten de gebruikers die in Admin Console voor Creative Cloud beschikbaar zijn in Admin Console voor Experience Cloud ter beschikking worden gesteld. Om de gebruikers beschikbaar te maken in de Admin Console van het Experience Cloud, creeer een folder om [&#x200B; folder te vestigen die &#x200B;](https://helpx.adobe.com/nl/enterprise/using/set-up-identity.html#directory-trusting) tussen de twee admin consoles vertrouwt.

![&#x200B; Gebruikers van het Creative Cloud &#x200B;](assets/creative-cloud-users.svg)

Zoals afgebeeld in het diagram, worden de gebruikers van het Creative Cloud automatisch ter beschikking gesteld in de Admin Console van het Experience Cloud die op een vertrouwensverhouding tussen de twee consoles wordt gebaseerd. Vervolgens kunt u de gebruikers toevoegen aan productprofielen voor Assets Essentials. Dientengevolge, kunnen de gebruikers van het Creative Cloud tot de toepassing van de Verbinding van Activa van de Adobe toegang hebben die met de bewaarplaats van Assets Essentials kan communiceren. Voor meer informatie, zie [&#x200B; Assets Essentials met de toepassingen van het Creative Cloud &#x200B;](integrate-with-creative-cloud.md) integreren.

## Experience Manager Documentatiereizen {#documentation-journeys}

Een reis van de Documentatie verbindt vele verschillende en misschien complexe onderwerpen en eigenschappen door een verhaal te verstrekken dat de lezer helpt, die aan Assets Essentials nieuw kan zijn, een bedrijfsprobleem van begin tot eind begrijpen en oplossen, terwijl het veronderstellen van minimale voorafgaand onderwerp of Assets Essentials kennis.

Documentatiereizen zijn gebaseerd op de beginselen van best practices, op basis van het meest recente onderzoek van de Adobe, bewezen ervaring met de implementatie door consultants van de Adobe en feedback van klantprojecten.

## Vereisten

* [&#x200B; Toegang tot Adobe Admin Console voor de oplossingen van het Experience Cloud &#x200B;](https://experienceleague.adobe.com/docs/core-services/interface/administration/admin-getting-started.html?lang=nl-NL)

* [&#x200B; Toegang tot Adobe Admin Console voor Creative Cloud voor ondernemingsplaatsing &#x200B;](https://helpx.adobe.com/nl/enterprise/admin-guide.html)

## Experience Manager Assets Essentials beheren {#administer-assets-essentials}

![&#x200B; Voorkeur om donker en licht thema &#x200B;](assets/cce-assets.png) te schakelen

Adobe Experience Manager Assets Essentials is een nieuwe, lichtgewicht editie van Adobe Experience Manager Assets. Assets Essentials bieden een vereenvoudigde en consistente gebruikersinterface voor Unified Asset Management en samenwerking. Dankzij de gebruiksvriendelijkheid kunnen meer creatieve en marketingteams digitale middelen opslaan, ontdekken en distribueren.

Adobe Experience Manager Assets Essentials wordt door Adobe geleverd voor zijn klanten. Als onderdeel van de provisioning worden Assets Essentials toegevoegd aan de organisatie van een klant in de Adobe Admin Console.

Beheerders gebruiken de Admin Console voor het beheer van gebruikersrechten voor het product Assets Essentials:

* Gebruikersgroepen toevoegen

* Gebruikers toevoegen aan gebruikersgroepen

* Gebruikers toevoegen aan productprofielen voor Assets Essentials

Na het beheren van de gebruikersrechten in Admin Console, kunnen de beheerders de toepassing van Assets Essentials gebruiken om:

* Een mappenstructuur maken die de behoeften van de organisatie het best ondersteunt

* Rechten voor de mappenstructuur beheren

* Metagegevensformulieren instellen

[![&#x200B; zie de Gids &#x200B;](assets/see-the-guide-sm.png)](deploy-administer.md)

Nu u de toepassing van Assets Essentials hebt gevormd en geleid, [&#x200B; integreren de toepassingen van het Creative Cloud met de toepassing van de Hoofdzaak van Experience Manager Assets &#x200B;](integrate-with-creative-cloud.md).

## Creative Cloud-toepassingen integreren met Experience Manager Assets Essentials {#administer-creative-cloud-applications}

![&#x200B; Voorkeur om donker en licht thema &#x200B;](assets/cce-creative-cloud.png) te schakelen

[&#x200B; Adobe de Verbinding van Activa in-app paneel &#x200B;](https://www.adobe.com/creativecloud/business/enterprise/adobe-asset-link.html) laat creatieve beroeps met [!DNL Assets Essentials] bewaarplaats van binnen gesteunde [!DNL Adobe Creative Cloud] Desktop apps verbinden. Het deelvenster is beschikbaar voor [!DNL Adobe Photoshop] , [!DNL Adobe Illustrator] , [!DNL Adobe InDesign] en [!DNL Adobe XD] . Het stroomlijnt de toegang tot activa die op zijn beurt inhoudssnelheid verhogen.

Deze zelfstudie begeleidt u bij het integreren van [!DNL Adobe Photoshop] -, [!DNL Adobe Illustrator] -, [!DNL Adobe InDesign] - en [!DNL Adobe XD] -toepassingen met Experience Manager Assets Essentials.

Doelstellingen:

* Map maken die wordt vertrouwd tussen Admin Consoles van Creatives Cloud en Experiencen Cloud

* Gebruikers van Creatives Cloud toevoegen aan productprofielen van Assets Essentials

* Koppeling met Adobe-elementen installeren

* Koppeling met Adobe-elementen gebruiken

[![&#x200B; zie de Gids &#x200B;](assets/see-the-guide-sm.png)](integrate-with-creative-cloud.md)

Nu u de toepassingen van het Creative Cloud met Assets Essentials hebt geïntegreerd, [&#x200B; integreert Adobe Workfront met de Hoofdzaak van Experience Manager Assets &#x200B;](integrate-with-workfront.md).

## Adobe Workfront integreren met Experience Manager Assets Essentials {#administer-adobe-workfront}

![&#x200B; Voorkeur om donker en licht thema &#x200B;](assets/cce-workfront.png) te schakelen

[[!DNL Adobe Workfront] &#x200B;](https://www.workfront.com/) is een werkbeheertoepassing die u helpt de volledige levenscyclus van het werk op één plaats beheren. Dankzij de native integratie tussen [!DNL Adobe Workfront] en [!DNL Assets Essentials] kunnen organisaties de snelheid van inhoud en de tijd die nodig is om op de markt te komen verbeteren door het werk en het middelenbeheer intrinsiek met elkaar te verbinden. In het kader van het beheer van hun werk hebben gebruikers toegang tot de vereiste documenten en afbeeldingen in dezelfde oplossing.

Deze zelfstudie begeleidt u bij het beheren van Adobe Workfront en het vervolgens integreren met Experience Manager Assets Essentials.

Doelstellingen:

* Gebruikers toevoegen aan Workfront-productprofielen

* Gebruikers toevoegen aan productprofielen voor Assets Essentials

* Integratie met Experience Manager Assets Essentials configureren

[![&#x200B; zie de Gids &#x200B;](assets/see-the-guide-sm.png)](integrate-with-workfront.md)
