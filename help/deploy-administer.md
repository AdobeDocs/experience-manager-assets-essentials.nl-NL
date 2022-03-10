---
title: Gebruikers beheren en beheren
description: Gebruiksgevallen voor beheerders zoals implementatie en gebruikersbeheer in [!DNL Assets Essentials].
role: Admin
exl-id: ef91126f-3aee-442b-b242-a6bf4034f3dc
source-git-commit: fb4ca5b3ab85f77cc1013c2d4743530f5d48e96d
workflow-type: tm+mt
source-wordcount: '1089'
ht-degree: 0%

---

# Beheren [!DNL Assets Essentials] en gebruikers toevoegen {#administer}

[!DNL Adobe Experience Manager Assets Essentials] is provisioned door Adobe voor zijn klanten. In het kader van de levering [!DNL Assets Essentials] wordt toegevoegd aan de organisatie van een klant in [!DNL Adobe Admin Console]. Beheerders gebruiken [!DNL Admin Console] om gebruikersrechten te beheren aan [!DNL Assets Essentials] oplossing, en wijs toepassingsbeheerders aan opstellingstoestemmingen en meta-gegevensformulieren in [!DNL Assets Essentials].

## Automatische implementatie van Assets Essentials {#automatic-deployment-assets-essentials}

Nadat de Assets Essentials-oplossing is ingericht, ontvangt de beheerder een e-mail van Adobe. Het e-mailbericht bevat een welkomstbericht en een koppeling om aan de slag te gaan. Daarnaast start Adobe het proces om Assets Essentials automatisch te implementeren. Het implementatieproces duurt een uur.

Via de koppeling in de e-mail kunt u toegang krijgen tot en aanmelden bij [Admin Console](https://adminconsole.adobe.com). Als u beheerdertoegang tot meer dan één organisatierekening hebt, dan selecteer de aangewezen organisatie of schakelaar aan het gebruikend de schakelaar in de hoogste bar. Zodra het automatische plaatsingsproces volledig is, de productkaart voor [!DNL AEM Assets Essentials] is zichtbaar in de [!DNL Admin Console].

![Assets Essentials-implementatie](assets/assets-essentials-deployment.png)

Beheerders moeten de volgende taken uitvoeren na een geslaagde implementatie van de Assets Essentials-oplossing:

* [Gebruikersgroepen instellen, mapstructuur instellen en machtigingen toewijzen](manage-permissions.md) voor de oplossing. Volg [best practices](permission-management-best-practices.md) om een eenvoudige en efficiënte opstelling van toestemmingen te verzekeren.
* [De gebruikerstoegang beheren](#add-users-to-essentials) van de organisatieleden [!DNL Assets Essentials].
* Optioneel [servicestatus en logbestanden weergeven](#view-logs).

>[!NOTE]
>
>Als Assets Essentials is ingericht vóór 6 januari 2022, voert u de opdracht [implementatiestappen in Cloud Manager](#deploy-essentials) voordat de gebruikerstoegang van de leden van de organisatie wordt beheerd.


## Gebruikersbeheer {#add-users-to-essentials}

Een beheerder beheert welke gebruikers toegang hebben tot [!DNL Assets Essentials]. Beheerders gebruiken [!DNL Adobe Admin Console] om gebruikerstoegang toe te voegen of te verwijderen. [!DNL Assets Essentials] heeft de volgende twee soorten beschikbare gebruikerstoegang.

* **[!DNL Assets Essentials]Beheerders** administratieve toegang tot de toepassing hebben. Naast alle mogelijkheden voor eindgebruikers kunnen toepassingsbeheerders in deze groep machtigingen beheren voor elke map en groep/gebruiker in de gehele opslagplaats van de toepassing.
* **[!DNL Assets Essentials]Gebruikers** toegang hebben tot de volledige gebruikersinterface. Deze gebruikers kunnen digitale elementen uploaden, organiseren, labelen en zoeken.
* **[!DNL Assets Essentials]Consumentengebruikers**: toegang hebben tot de ervaring die is opgedaan met het selecteren van ingesloten elementen in [!DNL Adobe Journey Optimizer] e-mailsjablooneditor. Zie voor meer informatie [Gebruiken [!DNL Assets Essentials] in [!DNL Journey Optimizer]](https://experienceleague.adobe.com/docs/journey-optimizer/using/create-messages/assets-essentials.html).

In [!DNL Admin Console], deze drie toegangstypen door drie [!UICONTROL Product Profiles]. Voer de volgende stappen uit om leden van uw organisatie toe te voegen aan en te verwijderen uit een van de twee profielen:

1. Toegang [!DNL Admin Console] voor uw organisatie klikt u op **[!UICONTROL Products]** in de bovenste balk klikt u op **[!UICONTROL AEM Assets Essentials]** en klik vervolgens op [!DNL Assets Essentials] milieu. [!DNL Assets Essentials] heeft drie productprofielen die toegang voor beheerder, regelmatige, en consument gebruikers vertegenwoordigen.

   ![Drie profielen voor drie soorten gebruikers](assets/admin-console-admin-profile.png)
   <!-- Need to update screenshot to include 3 profiles -->

   *Afbeelding: Er zijn drie profielen beschikbaar om de drie soorten gebruikers toe te voegen.*

1. Als u een gebruiker aan een groep wilt toevoegen, klikt u op de groep en selecteert u **[!UICONTROL Add User]**, geef de gebruikersgegevens op en klik op **[!UICONTROL Save]**. Wanneer u een gebruiker toevoegt, ontvangt de gebruiker een e-mailuitnodiging om aan de slag te gaan. U kunt de e-mailuitnodigingen in de instellingen voor het productprofiel uitschakelen in [!DNL Admin Console].

   ![Een gebruiker toevoegen aan [!DNL Assets Essentials]](assets/adminconsole-add-user.png)

   *Afbeelding: Een gebruiker toevoegen aan [!DNL Assets Essentials] van [!DNL Admin Console].*

1. Als u een gebruiker uit een groep wilt verwijderen, klikt u op de groep, selecteert u een bestaande gebruiker en selecteert u **[!UICONTROL Remove User]**.

>[!TIP]
>
>In [!DNL Admin Console], kunt u de gebruikers in bulk beheren gebruikend Csv- dossiers. Zie voor meer informatie [[!DNL Admin Console] documentatie](https://helpx.adobe.com/enterprise/using/accounts.html).

## Servicestatus en toegangslogboeken weergeven {#view-logs}

Na provisioning implementeren beheerders [!DNL Assets Essentials] slechts eenmaal. Na de eerste implementatie voert Adobe het onderhoud en de updates van de service uit. Beheerders kunnen de [!DNL Cloud Manager] gebruikersinterface om de de dienststatus te controleren en de recente toegangslogboeken te downloaden.

1. Wanneer gebruikers problemen melden, controleer de servicestatus van [!DNL Assets Essentials] in de **[!UICONTROL Program Overview]** interface. Tijdens de normale werking van de oplossing is de status `Running`. Indien [!DNL Cloud Manager] geeft een andere status weer, maakt een ondersteuningsticket in het dialoogvenster [!DNL Admin Console] ondersteunende sectie.

   ![De status van [!DNL Assets Essentials] in [!DNL Cloud Manager]](assets/cloudmanager-manage-access-essentials.png)

   *Afbeelding: De normale status van [!DNL Assets Essentials] in [!DNL Cloud Manager] is `Running`.*

1. Klik op ![optiepictogram](assets/do-not-localize/options-ellipses-icon.png), selecteert u **[!UICONTROL Download Logs]** en volgt u de aanwijzingen op het scherm. U kunt de HTTPS-toegangsverzoeken controleren met behulp van de logboeken.

   ![ Optie om de toegangslogboeken te downloaden](assets/cloudmanager-download-logs.png)

   *Afbeelding: Optie om de toegangslogboeken te downloaden.*

## Implementeren [!DNL Assets Essentials] {#deploy-essentials}

>[!NOTE]
>
>Voer deze stappen alleen uit als Assets Essentials is ingericht vóór 6 januari 2022.

Na levering, [!DNL Assets Essentials] rechten worden toegevoegd aan uw organisatie in [!DNL Admin Console]. Alvorens de oplossing aan de gebruiker beschikbaar is, moet een organisatiebeheerder het opstellen. De beheerder voert eenmalig implementatie uit met [!DNL Cloud Manager] gebruikersinterface. Na de eerste implementatie voert Adobe het onderhoud en de updates van de service uit. Nadat de oplossing wordt geleverd, ontvangt de beheerder een e-mail van Adobe. Het e-mailbericht bevat een welkomstbericht en een koppeling om aan de slag te gaan. Voer de volgende stappen uit om te implementeren:

1. Via de koppeling in de e-mail kunt u toegang krijgen tot en aanmelden bij [Admin Console](https://adminconsole.adobe.com). Als u beheerdertoegang tot meer dan één organisatierekening hebt, dan selecteer de aangewezen organisatie of schakelaar aan het gebruikend de schakelaar in de hoogste bar. De productkaart voor [!DNL Assets Essentials] is zichtbaar in de [!DNL Admin Console].

   ![[!DNL Assets Essentials] inchecken [!DNL Admin Console]](assets/essentials-in-admin-console.png)

   *Afbeelding: [!DNL Assets Essentials] inchecken [!DNL Admin Console].*

   >[!NOTE]
   >
   >Als u de **[!UICONTROL AEM Assets Essentials]** kaart in de productsectie in plaats van **[!UICONTROL AEM Assets Essentials - Cloud Manager]** -kaart, is de implementatie van Assets Essentials al voltooid. U kunt de resterende stappen overslaan.

1. Als beheerder toevoegen aan de `AEM Assets Essentials - Cloud Manager` productprofiel in de [!DNL Admin Console]. In plaats van uzelf, kunt u een ander lid van uw organisatie toevoegen of u kunt meer dan één beheerder toevoegen.

1. Klikken ![pictogram toevoegen](assets/do-not-localize/add-icon.svg) tot [!UICONTROL Select product profiles]en selecteer vervolgens [!UICONTROL Deployment Manager - Assets Essentials] als de **[!UICONTROL product profile]**. De gebruiker die aan deze stap is toegevoegd, ontvangt een e-mail van Adobe met toegang tot [!DNL Cloud Manager] en kan de implementatie uitvoeren.

   ![Een beheerder toevoegen en een productprofiel selecteren in [!DNL Admin Console]](assets/adminconsole-user1.png)

   *Afbeelding: Een beheerder toevoegen en een productprofiel selecteren in [!DNL Admin Console].*

1. Toegang tot [!DNL Cloud Manager]klikt u op de koppeling in de e-mail met toegang tot [!DNL Cloud Manager]. Alternatief, toegang [https://experience.adobe.com/#/cloud-manager/](https://experience.adobe.com/#/cloud-manager/) in uw browser.

1. Klik in de gebruikersinterface van Cloud Manager op **[!UICONTROL Add Program]** in de rechterbovenhoek.

1. Geef uw keuze een naam en upload eventueel een afbeelding (het vertegenwoordigt het programma in [!DNL Cloud Manager]) en klik vervolgens op **[!UICONTROL Create]**. [!DNL Cloud Manager] Het duurt een paar minuten om het programma in te stellen.

1. Als het programma gereed is, plaatst u de aanwijzer op de tegel en klikt u op ![pictogram voor omgeving toevoegen](assets/do-not-localize/add-environment-icon.png).

1. Toevoegen [!DNL Assets Essentials] service aan uw organisatie, klikt u op **[!UICONTROL Add Environment]** selecteert u een naam en een implementatiegebied en klikt u op **[!UICONTROL Save]**. U kunt het implementatiegebied later niet wijzigen. Probeer het implementatiegebied van [!DNL Assets Essentials] met het plaatsingsgebied van de andere oplossing waarmee u van plan bent te gebruiken [!DNL Assets Essentials]. De overeenkomst moet ervoor zorgen dat de netwerken zo snel mogelijk toegang krijgen tot digitale middelen en de laagst mogelijke latentie.

   ![Een omgeving toevoegen in [!DNL Cloud Manager]](assets/cloudmanager-add-environment-for-essentials.png)

   *Afbeelding: Een omgeving toevoegen in [!DNL Cloud Manager] om te beginnen met [!DNL Assets Essentials].*

1. Wanneer de omgeving na enkele minuten is gemaakt, hebt u toegang tot de [!DNL Admin Console] en voeg de gebruikers van uw organisatie toe aan [!DNL Assets Essentials] oplossing. Klikken ![optiepictogram](assets/do-not-localize/options-ellipses-icon.png) en selecteert u de **[!UICONTROL Manage Access]** optie.

   ![Klaar omgeving in [!DNL Cloud Manager]](assets/cloudmanager-manage-access-essentials.png)

   *Afbeelding: Een omgeving in [!DNL Cloud Manager] dat klaar is om te gebruiken.*

>[!MORELIKETHIS]
>
>* [[!DNL Admin Console] help](https://helpx.adobe.com/enterprise/using/admin-console.html)
>* [[!DNL Cloud Manager] help](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html)
>* [Adobe Journey Optimizer-documentatie](https://experienceleague.adobe.com/docs/journey-optimizer/using/ajo-home.html)
>* [Opmerkingen bij de release](release-notes.md)
>* [Aan de slag met [!DNL Assets Essentials]](get-started.md)

