---
title: Assets Essentials integreren met Creative Cloud-toepassingen
description: Integreer Assets Essentials met de toepassingen van het Creative Cloud zodat u de verbinding van Activa van de Adobe in-app paneel kunt gebruiken om met  [!DNL Assets Essentials]  bewaarplaats van binnen de gesteunde  [!DNL Adobe Creative Cloud]  Desktoptoepassingen te verbinden.
exl-id: 611fd958-3fd3-4c46-bee9-8b866b7dc208
source-git-commit: 65200f73a954e4ebf4fbd6dc3a819acc6e0beda4
workflow-type: tm+mt
source-wordcount: '810'
ht-degree: 0%

---

# Assets Essentials integreren met Creative Cloud-toepassingen {#integrate-assets-essentials-creative-cloud-applications}

![&#x200B; Voorkeur om donker en licht thema &#x200B;](assets/cce-creative-cloud.png) te schakelen

## Het verhaal tot nu toe

Na [&#x200B; vormend de Hoofdzaak van Experience Manager Assets &#x200B;](adminster-aem-assets-essentials.md) in dit leerprogramma, kunt u op de ervaring voortbouwen om de toepassingen van het Creative Cloud met Assets Essentials te integreren.

## Doelstelling

* **Publiek**: De beheerders van het Creative Cloud

* **Doelstelling**: Integreer Assets Essentials met de toepassingen van het Creative Cloud zodat uw creatieve gebruikers de verbinding van Activa van de Adobe in-app paneel kunnen gebruiken om met [!DNL Assets Essentials] bewaarplaats van binnen de gesteunde [!DNL Adobe Creative Cloud] Desktoptoepassingen te verbinden.

## Overzicht

[&#x200B; Adobe de Verbinding van Activa in-app paneel &#x200B;](https://www.adobe.com/creativecloud/business/enterprise/adobe-asset-link.html) laat creatieve beroeps met [!DNL Assets Essentials] bewaarplaats van binnen gesteunde [!DNL Adobe Creative Cloud] Desktop apps verbinden. Het deelvenster is beschikbaar voor [!DNL Adobe Photoshop] , [!DNL Adobe Illustrator] , [!DNL Adobe InDesign] en [!DNL Adobe XD] . Het stroomlijnt de toegang tot elementen, wat op zijn beurt de snelheid van de inhoud verhoogt.

Gebruikers van een Creative Cloud kunnen het paneel Asset Link in-app alleen gebruiken voor het Adoben van Creatives Cloud wanneer u de toepassingen integreert met de Experience Manager Assets Essentials-opslagplaats.

Voer de volgende taken uit om Assets Essentials met de toepassingen van het Creative Cloud te integreren:

* [Map maken die wordt vertrouwd tussen Admin Console van Creative Cloud en Experience Cloud](#directory-trusting-cc-assets-essentials-consoles)

* [Gebruikers van Creatives Cloud toevoegen aan productprofielen van Assets Essentials](#add-cc-users-assets-essentials-product-profiles)

* [Koppeling met Adobe-elementen installeren](#install-asset-link)

* [Koppeling met Adobe-elementen gebruiken](#use-asset-link)

## Map maken die wordt vertrouwd tussen Admin Consoles van Creatives Cloud en Experiencen Cloud {#directory-trusting-cc-assets-essentials-consoles}

Als uw Creative Cloud in afzonderlijk Adobe Admin Console van met Assets Essentials (de oplossing van het Experience Cloud) wordt opgesteld, moet u vertrouwensverhouding tussen de twee consoles toevoegen.

Om Creative Cloud en Assets Essentials toepassingen te integreren, moeten de gebruikers die in Admin Console voor Creative Cloud beschikbaar zijn in Admin Console voor Experience Cloud ter beschikking worden gesteld. Als het Creative Cloud en de Assets Essentials in afzonderlijke Admin Consoles worden opgesteld, wordt het vertrouwensverband tussen hen vereist om dit toe te laten.

Voor de Admin Console van het Experience Cloud, klik **[!UICONTROL Settings]** en gebruik het **[!UICONTROL Directories]** lusje om een folder tot stand te brengen om [&#x200B; folder te vestigen die &#x200B;](https://helpx.adobe.com/nl/enterprise/using/set-up-identity.html#directory-trusting) tussen de twee Admin Consoles vertrouwt.

## Gebruikers van Creatives Cloud toevoegen aan productprofielen van Assets Essentials {#add-cc-users-assets-essentials-product-profiles}

Na het vestigen van folder het vertrouwen tussen de Admin Console voor Creative Cloud en Admin Console voor Experience Cloud, wijs de gebruikers van het Creative Cloud aan het **[!DNL Assets Essentials]Gebruikers** productprofiel onder de [!DNL Assets Essentials] productkaart in de Admin Console van het Experience Cloud toe. Hiermee krijgen gebruikers van het Creative Cloud toegang tot Assets Essentials via het deelvenster voor de insteekmodule voor de Adobe Asset Link. Bovendien krijgen gebruikers toegang tot de webgebruikersinterface van alle Assets Essentials voor het uploaden, organiseren, labelen en zoeken van digitale middelen via een webbrowser.

Andere profielen van het product van Assets Essentials - **[!DNL Assets Essentials]Beheerders** en **[!DNL Assets Essentials]Consumentengebruikers** - worden gebruikt voor verschillende gebruikersrechten (toepassingsbeheerders en gebruikers die tot Assets Essentials via de integratie van het Experience Cloud toegang hebben).

Voor meer informatie over hoe te om gebruikers aan de profielen van het Assets Essentials product toe te wijzen, zie [&#x200B; gebruikers aan de profielen van het Assets Essentials product toewijzen &#x200B;](adminster-aem-assets-essentials.md#add-users-to-product-profiles).

## Koppeling met Adobe-elementen installeren {#install-asset-link}

[!DNL Adobe Asset Link] -plug-in kan op twee manieren worden geïnstalleerd en beschikbaar worden gemaakt voor creatieve gebruikers:

* Creatieve gebruikers kunnen de insteekmodule installeren vanuit hun [!DNL Creative Cloud Desktop] -toepassing
* De beheerder van het Creative Cloud kan de insteekmodule van de Verbinding van Activa aan een Creative Cloud in Admin Console toevoegen

De keuze hangt af van het IT-beleid van de organisatie.

**Installatie die [!DNL Creative Cloud Desktop] toepassing** gebruikt wordt beschreven [&#x200B; hier &#x200B;](https://helpx.adobe.com/nl/creative-cloud/kb/installingextensionsandaddons.html). Er zijn twee beschikbare stoppen en ontvangen op [&#x200B; Adobe Exchange &#x200B;](https://exchange.adobe.com/) markt, afhankelijk van de toepassing van het Creative Cloud:

* Voor [!DNL Adobe Photoshop], [!DNL Adobe Illustrator], en [!DNL Adobe InDesign]: [&#x200B; de Verbinding van Activa van de Adobe CEP &#x200B;](https://exchange.adobe.com/creativecloud.details.106875.adobe-asset-link-cep.html)
* Voor [!DNL Adobe XD]: [&#x200B; de Verbinding van Activa van de Adobe &#x200B;](https://exchange.adobe.com/creativecloud/plugindetails.html/app/cc/61d229b9)

**Installatie met een pakket van het Creative Cloud** wordt gedaan door de beheerder van het Creative Cloud in Admin Console, door de insteekmodule van de Verbinding van Activa te omvatten wanneer het bouwen van een plaatsingspakket, dat later aan gebruikersmachines kan worden opgesteld. In geleid kiest het scherm van Insteekmodules, onderzoek naar **de Verbinding van Activa van de Adobe** in de **Aanbevolen bedrijfsplugins** sectie. Voor meer informatie, zie [&#x200B; verpakken apps via de Admin Console &#x200B;](https://helpx.adobe.com/nl/enterprise/using/package-apps-admin-console.html).

## Koppeling met Adobe-elementen gebruiken {#use-asset-link}

Creatieve gebruikers kunnen nu Adobe Asset Link gebruiken met Photoshop, Illustrator, InDesign of XD. Als u het deelvenster in InDesign of Illustrator wilt openen, gaat u naar Windows > Extensies > Adobe Asset Link. Ga in Photoshop naar Venster > Extensies (verouderd) > Adobe Asset Link.

Voor informatie over hoe te om de Verbinding van Activa van de Adobe voor Adobe XD te plaatsen, klik [&#x200B; hier &#x200B;](https://helpx.adobe.com/nl/enterprise/using/adobe-asset-link-for-xd.html).

>[!NOTE]
>
>Als u werkt met Apple Silicon/M1-hardware, moet Adobe Photoshop worden gestart met de Rosetta-compatibiliteitsmodus om ervoor te zorgen dat creatieve gebruikers toegang hebben tot het deelvenster voor Adobe Asset Link, omdat dit wordt gebouwd met de CEP-extensietechnologie. Voor meer informatie, zie [&#x200B; Photoshop voor Apple Silicon &#x200B;](https://helpx.adobe.com/nl/photoshop/kb/photoshop-for-apple-silicon.html).


De Verbinding van Activa van de Adobe van het gebruik om met en te werken activa te wijzigen die in de bewaarplaats van Assets Essentials worden opgeslagen. U kunt verschillende taken uitvoeren, zoals:

* Middelen zoeken en doorbladeren

* Elementen uploaden

* Elementen sorteren en filteren

* Middelen plaatsen, downloaden en slepen

* Middelen uitchecken en inchecken

* Versiegeschiedenis en bestandsgegevens weergeven

Voor instructies op hoe te om deze taken uit te voeren, zie [&#x200B; activa beheren gebruikend de Verbinding van Activa van de Adobe &#x200B;](https://helpx.adobe.com/in/enterprise/using/manage-assets-using-adobe-asset-link.html).

## Volgende functies

Nu u de toepassingen van het Creative Cloud met Assets Essentials hebt geïntegreerd, [&#x200B; integreert Adobe Workfront met de Hoofdzaak van Experience Manager Assets &#x200B;](integrate-assets-essentials-workfront.md).
