---
title: Assets Essentials for Creative Cloud Pro instellen met oplossingen voor werkbeheer
description: 'Deze zelfstudie introduceert een beheerderstraject waarmee Assets Essentials-toepassingen kunnen worden geïntegreerd met Creative Cloud-bureaubladtoepassingen en Adobe Workfront-toepassingen. Tot de Creative Cloud-bureaubladtoepassingen behoren Adobe Photoshop, Adobe Illustrator, Adobe InDesign en Adobe XD. '
source-git-commit: f4e56fc6bb76eeb2770b18be88b7da1a1829069c
workflow-type: tm+mt
source-wordcount: '900'
ht-degree: 0%

---


# Assets Essentials for Creative Cloud Pro met oplossingen voor werkbeheer {#creative-cloud-enterprise-user-journeys}

![Voorkeur voor schakelen tussen donker en licht thema](assets/cce-next-banner-landing-page.png)

## Inleiding {#introduction}

Creative Cloud Pro voor ondernemingen met oplossingen voor werkbeheer integreert creatieve, content- en werkbeheertools om uw capaciteit om creatieve content te produceren te vergroten en snel zakelijke doelen te bereiken. De oplossing omvat de volgende componenten:

* Creative Cloud Pro

* Adobe Workfront

* Experience Manager Assets Essentials

Deze zelfstudie introduceert een beheerderstraject waarmee Assets Essentials-toepassingen kunnen worden geïntegreerd met Creative Cloud-bureaubladtoepassingen en Adobe Workfront-toepassingen. Tot de Creative Cloud-bureaubladtoepassingen behoren Adobe Photoshop, Adobe Illustrator, Adobe InDesign en Adobe XD.

## Implementatietypen {#deployment-types}

Aangezien de oplossing uit toepassingen en de diensten van zowel Creative Cloud als Adobe Experience Cloud bestaat, zouden zij in één of twee Admin Consoles van Adobe voor uw bedrijf kunnen worden opgesteld.

In het geval van plaatsing in twee Admin Consoles, wordt een extra configuratiestap vereist:

* Creative Cloud-services en -toepassingen (Creative Cloud voor Enterprise Pro en optionele modules) worden beheerd in [Adobe Admin Console voor uw implementatie van Creative Cloud](https://chl-author-preview.corp.adobe.com/content/help/en/enterprise/admin-guide.html).

* Adobe Workfront en Adobe Experience Manager Assets Essentials worden beheerd in [Adobe Admin Console for Experience Cloud oplossingen](https://experienceleague.adobe.com/docs/core-services/interface/administration/admin-getting-started.html).

Om Creative Cloud en de toepassingen van Assets Essentials te integreren, moeten de gebruikers die in Admin Console voor Creative Cloud beschikbaar zijn in Admin Console voor Experience Cloud worden ter beschikking gesteld. Als u de gebruikers beschikbaar wilt maken in de Experience Cloud Admin Console, maakt u een directory om [directory vertrouwen](https://helpx.adobe.com/enterprise/using/set-up-identity.html#directory-trusting) tussen de twee beheerconsoles.

![Creative Cloud-gebruikers](assets/creative-cloud-users.svg)

Zoals afgebeeld in het diagram, worden de gebruikers van de Creative Cloud automatisch ter beschikking gesteld in de Admin Console van de Experience Cloud die op een vertrouwensverhouding tussen de twee consoles wordt gebaseerd. Vervolgens kunt u de gebruikers toevoegen aan Assets Essentials-productprofielen. Dientengevolge, kunnen de gebruikers van de Creative Cloud tot de toepassing van de Verbinding van de Activa van de Adobe toegang hebben die met de bewaarplaats van Assets Essentials kan communiceren. Zie voor meer informatie [Assets Essentials integreren met Creative Cloud-toepassingen](integrate-assets-essentials-creative-cloud.md).

## Experience Manager Documentatiereizen {#documentation-journeys}

Een reis van de Documentatie verbindt vele verschillende en misschien complexe onderwerpen en eigenschappen door een verhaal te verstrekken dat de lezer helpt, die nieuw aan Assets Essentials kan zijn, een bedrijfsprobleem van begin tot eind begrijpen en oplossen, terwijl het veronderstellen van minimale voorafgaand onderwerp of kennis van Assets Essentials.

Documentatiereizen zijn gebaseerd op de beginselen van best practices, op basis van het meest recente onderzoek van Adobe, bewezen ervaring met de implementatie van Adobe-consultants en feedback van klantprojecten.

## Vereisten

* [Toegang tot Adobe Admin Console voor Experience Cloud-oplossingen](https://experienceleague.adobe.com/docs/core-services/interface/administration/admin-getting-started.html)

* [Toegang tot Adobe Admin Console voor Creative Cloud voor bedrijfsimplementatie](https://helpx.adobe.com/enterprise/admin-guide.html)

## Experience Manager Assets Essentials beheren {#administer-assets-essentials}

![Voorkeur voor schakelen tussen donker en licht thema](assets/cce-assets.png)

Adobe Experience Manager Assets Essentials is een nieuwe, lichtgewicht editie van Adobe Experience Manager Assets. Assets Essentials biedt een uniforme functionaliteit voor middelenbeheer en samenwerking met een vereenvoudigde en consistente gebruikersinterface. Dankzij de gebruiksvriendelijkheid kunnen meer creatieve en marketingteams digitale middelen opslaan, ontdekken en distribueren.

Adobe Experience Manager Assets Essentials wordt geleverd door Adobe voor zijn klanten. Als deel van de levering, wordt Assets Essentials toegevoegd aan de organisatie van een klant in Adobe Admin Console.

Beheerders gebruiken de Admin Console voor het beheer van gebruikersrechten voor Assets Essentials-producten:

* Gebruikersgroepen toevoegen

* Gebruikers toevoegen aan gebruikersgroepen

* Gebruikers toevoegen aan Assets Essentials-productprofielen

Na het beheren van de gebruikersrechten in Admin Console, kunnen de beheerders de toepassing van Assets Essentials gebruiken om:

* Een mappenstructuur maken die de behoeften van de organisatie het best ondersteunt

* Rechten voor de mappenstructuur beheren

* Metagegevensformulieren instellen

[![Zie de Guide](https://helpx.adobe.com/content/dam/help/en/marketing-cloud/how-to/digital-foundation/_jcr_content/main-pars/image_1250343773/see-the-guide-sm.png)](adminster-aem-assets-essentials.md)

## Creative Cloud-toepassingen integreren met Experience Manager Assets Essentials {#administer-creative-cloud-applications}

![Voorkeur voor schakelen tussen donker en licht thema](assets/cce-creative-cloud.png)

[In-app-deelvenster voor Adobe-middelenkoppeling](https://www.adobe.com/creativecloud/business/enterprise/adobe-asset-link.html) biedt professionals uit de creatieve sector de mogelijkheid verbinding te maken met [!DNL Assets Essentials] opslagplaats vanuit de ondersteunde [!DNL Adobe Creative Cloud] bureaubladtoepassingen. Het deelvenster is beschikbaar voor [!DNL Adobe Photoshop], [!DNL Adobe Illustrator], [!DNL Adobe InDesign], en [!DNL Adobe XD]. Het stroomlijnt de toegang tot activa die op zijn beurt inhoudssnelheid verhogen.

Deze zelfstudie begeleidt u bij het integreren [!DNL Adobe Photoshop], [!DNL Adobe Illustrator], [!DNL Adobe InDesign], en [!DNL Adobe XD] toepassingen met Experience Manager Assets Essentials.

Doelstellingen:

* Map maken die wordt vertrouwd tussen Admin Consoles Creative Cloud en Experience Cloud

* Creative Cloud-gebruikers toevoegen aan Assets Essentials-productprofielen

* Adobe-elementkoppeling installeren

* Adobe-itemkoppeling gebruiken

[![Zie de Guide](https://helpx.adobe.com/content/dam/help/en/marketing-cloud/how-to/digital-foundation/_jcr_content/main-pars/image_1250343773/see-the-guide-sm.png)](integrate-assets-essentials-creative-cloud.md)

## Adobe Workfront integreren met Experience Manager Assets Essentials {#administer-adobe-workfront}

![Voorkeur voor schakelen tussen donker en licht thema](assets/cce-workfront.png)

[[!DNL Adobe Workfront]](https://www.workfront.com/) is een werkbeheertoepassing waarmee u de volledige levenscyclus van het werk op één locatie kunt beheren. De native integratie tussen [!DNL Adobe Workfront] en [!DNL Assets Essentials] organisaties kunnen de snelheid van de inhoud en de tijd aan markt verbeteren door werk en activabeheer intrinsiek met elkaar te verbinden. In het kader van het beheer van hun werk hebben gebruikers toegang tot de vereiste documenten en afbeeldingen in dezelfde oplossing.

Deze zelfstudie begeleidt u bij het beheren van Adobe Workfront en het vervolgens integreren met Experience Manager Assets Essentials.

Doelstellingen:

* Gebruikers toevoegen aan Workfront-productprofielen

* Gebruikers toevoegen aan Assets Essentials-productprofielen

* Integratie met Experience Manager Assets Essentials configureren

[![Zie de Guide](https://helpx.adobe.com/content/dam/help/en/marketing-cloud/how-to/digital-foundation/_jcr_content/main-pars/image_1250343773/see-the-guide-sm.png)](integrate-assets-essentials-workfront.md)


