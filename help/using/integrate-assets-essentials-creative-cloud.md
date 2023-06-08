---
title: Assets Essentials integreren met Creative Cloud-toepassingen
description: Integreer Assets Essentials met Creative Cloud-toepassingen, zodat u in het app-deelvenster met de koppeling Adobe-element verbinding verbinding kunt maken met [!DNL Assets Essentials] opslagplaats vanuit de ondersteunde [!DNL Adobe Creative Cloud] bureaubladtoepassingen.
exl-id: 611fd958-3fd3-4c46-bee9-8b866b7dc208
source-git-commit: 65200f73a954e4ebf4fbd6dc3a819acc6e0beda4
workflow-type: tm+mt
source-wordcount: '852'
ht-degree: 0%

---

# Assets Essentials integreren met Creative Cloud-toepassingen {#integrate-assets-essentials-creative-cloud-applications}

![Voorkeur voor schakelen tussen donker en licht thema](assets/cce-creative-cloud.png)

## Het verhaal tot nu toe

Na [configureren van Experience Manager Assets Essentials](adminster-aem-assets-essentials.md) in deze zelfstudie kunt u voortbouwen op de ervaring om de Creative Cloud-toepassingen te integreren met Assets Essentials.

## Doelstelling

* **Publiek**: Creative Cloud-beheerders

* **Doelstelling**: Integreer Assets Essentials met Creative Cloud-toepassingen, zodat uw creatieve gebruikers in-app-deelvensters met de Adobe Asset Link kunnen gebruiken om verbinding te maken met [!DNL Assets Essentials] opslagplaats vanuit de ondersteunde [!DNL Adobe Creative Cloud] bureaubladtoepassingen.

## Overzicht

[In-app-deelvenster voor Adobe-middelenkoppeling](https://www.adobe.com/creativecloud/business/enterprise/adobe-asset-link.html) biedt professionals uit de creatieve sector de mogelijkheid verbinding te maken met [!DNL Assets Essentials] opslagplaats vanuit de ondersteunde [!DNL Adobe Creative Cloud] bureaubladtoepassingen. Het deelvenster is beschikbaar voor [!DNL Adobe Photoshop], [!DNL Adobe Illustrator], [!DNL Adobe InDesign], en [!DNL Adobe XD]. Het stroomlijnt de toegang tot elementen, wat op zijn beurt de snelheid van de inhoud verhoogt.

Gebruikers van de Creative Cloud-toepassing kunnen het paneel voor het koppelen van Adobe-middelen alleen gebruiken wanneer u de Creative Cloud-toepassingen integreert met de Experience Manager Assets Essentials-opslagplaats.

Voer de volgende taken uit om Assets Essentials te integreren met Creative Cloud-toepassingen:

* [Map maken die wordt vertrouwd tussen Admin Console Creative Cloud en Experience Cloud](#directory-trusting-cc-assets-essentials-consoles)

* [Creative Cloud-gebruikers toevoegen aan Assets Essentials-productprofielen](#add-cc-users-assets-essentials-product-profiles)

* [Adobe-elementkoppeling installeren](#install-asset-link)

* [Adobe-itemkoppeling gebruiken](#use-asset-link)

## Map maken die wordt vertrouwd tussen Admin Consoles Creative Cloud en Experience Cloud {#directory-trusting-cc-assets-essentials-consoles}

Als uw Creative Cloud in een afzonderlijke Adobe Admin Console van met Assets Essentials (de oplossing van Experience Cloud) wordt opgesteld, moet u vertrouwensverhouding tussen de twee consoles toevoegen.

Om Creative Cloud en de toepassingen van Assets Essentials te integreren, moeten de gebruikers die in Admin Console voor Creative Cloud beschikbaar zijn in Admin Console voor Experience Cloud worden ter beschikking gesteld. Als Creative Cloud en Assets Essentials in afzonderlijke Admin Consoles worden opgesteld, wordt het vertrouwensverband tussen hen vereist om dit toe te laten.

Klik in de Admin Console Experience Cloud op **[!UICONTROL Settings]** en gebruiken de **[!UICONTROL Directories]** tabblad om een map te maken die [directory vertrouwen](https://helpx.adobe.com/enterprise/using/set-up-identity.html#directory-trusting) tussen de twee Admin Consoles.

## Creative Cloud-gebruikers toevoegen aan Assets Essentials-productprofielen {#add-cc-users-assets-essentials-product-profiles}

Na het vestigen van folder het vertrouwen tussen de Admin Console voor Creative Cloud en Admin Console voor Experience Cloud, wijs de gebruikers van Creative Cloud aan toe **[!DNL Assets Essentials]Gebruikers** productprofiel onder [!DNL Assets Essentials] productkaart in de Experience Cloud Admin Console. Hiermee krijgen Creative Cloud-gebruikers toegang tot Assets Essentials via hun insteekmodule voor Adobe Asset Link; bovendien krijgen ze toegang tot de volledige Assets Essentials-webgebruikersinterface voor het uploaden, organiseren, labelen en zoeken van digitale middelen via een webbrowser.

Andere Assets Essentials-productprofielen - **[!DNL Assets Essentials]Beheerders** en **[!DNL Assets Essentials]Consumentengebruikers** - worden gebruikt voor verschillende gebruikersrechten (toepassingsbeheerders en gebruikers die Assets Essentials openen via Experience Cloud-integratie).

Voor meer informatie over het toewijzen van gebruikers aan Assets Essentials-productprofielen raadpleegt u [Gebruikers toewijzen aan Assets Essentials-productprofielen](adminster-aem-assets-essentials.md#add-users-to-product-profiles).

## Adobe-elementkoppeling installeren {#install-asset-link}

[!DNL Adobe Asset Link] insteekmodule kan op twee manieren worden geïnstalleerd en beschikbaar gemaakt voor creatieve gebruikers :

* Creatieve gebruikers kunnen de plug-in installeren vanuit hun [!DNL Creative Cloud Desktop] toepassing
* Creative Cloud-beheerder kan de insteekmodule Asset Link toevoegen aan een Creative Cloud-pakket in Admin Console

De keuze hangt af van het IT-beleid van de organisatie.

**Installatie met [!DNL Creative Cloud Desktop] toepassing** wordt beschreven [hier](https://helpx.adobe.com/creative-cloud/kb/installingextensionsandaddons.html). Er zijn twee plug-ins beschikbaar die u kunt hosten op [Adobe Exchange](https://exchange.adobe.com/) Marketplace, afhankelijk van de Creative Cloud-toepassing:

* Voor [!DNL Adobe Photoshop], [!DNL Adobe Illustrator], en [!DNL Adobe InDesign]: [Adobe Asset Link CEP](https://exchange.adobe.com/creativecloud.details.106875.adobe-asset-link-cep.html)
* Voor [!DNL Adobe XD]: [Adobe-itemkoppeling](https://exchange.adobe.com/creativecloud/plugindetails.html/app/cc/61d229b9)

**Installatie met een Creative Cloud-pakket** wordt gedaan door Creative Cloud beheerder in Admin Console, door de insteekmodule van de Verbinding van Activa te omvatten wanneer het bouwen van een plaatsingspakket, dat later aan gebruikersmachines kan worden opgesteld. Zoek in het beheerde scherm Plug-ins kiezen naar **Adobe-itemkoppeling** in de **Aanbevolen plug-ins voor bedrijven** sectie. Zie voor meer informatie [toepassingen verpakken via de Admin Console](https://helpx.adobe.com/enterprise/using/package-apps-admin-console.html).

## Adobe-itemkoppeling gebruiken {#use-asset-link}

Creatieve gebruikers kunnen nu Adobe Asset Link gebruiken met Photoshop, Illustrator, InDesign of XD. Als u het deelvenster in InDesign of Illustrator wilt openen, gaat u naar Windows > Extensies > Adobe-itemkoppeling. Ga in Photoshop naar Venster > Extensies (verouderd) > Adobe Asset Link.

Voor informatie over het instellen van Adobe Asset Link voor Adobe XD klikt u op [hier](https://helpx.adobe.com/enterprise/using/adobe-asset-link-for-xd.html).

>[!NOTE]
>
>Als u werkt met Apple Silicon/M1-hardware, moet Adobe Photoshop worden gestart met de Rosetta-compatibiliteitsmodus om ervoor te zorgen dat creatieve gebruikers toegang hebben tot het deelvenster Adobe Asset Link, omdat dit wordt gemaakt met de CEP-extensietechnologie. Zie voor meer informatie [Photoshop voor Apple Silicon](https://helpx.adobe.com/photoshop/kb/photoshop-for-apple-silicon.html).


Gebruik Adobe Asset Link om te werken met en elementen te wijzigen die zijn opgeslagen in de Assets Essentials-opslagplaats. U kunt verschillende taken uitvoeren, zoals:

* Middelen zoeken en doorbladeren

* Elementen uploaden

* Elementen sorteren en filteren

* Middelen plaatsen, downloaden en slepen

* Middelen uitchecken en inchecken

* Versiegeschiedenis en bestandsgegevens weergeven

Voor instructies over hoe te om deze taken uit te voeren, zie [Elementen beheren met Adobe Asset Link](https://helpx.adobe.com/in/enterprise/using/manage-assets-using-adobe-asset-link.html).

## Volgende functies

Nu u de Creative Cloud-toepassingen hebt geïntegreerd met Assets Essentials, [Adobe Workfront integreren met Experience Manager Assets Essentials](integrate-assets-essentials-workfront.md).
