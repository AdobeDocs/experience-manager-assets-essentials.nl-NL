---
title: Gebruikers implementeren en beheren
description: Het gebruiksgevallen van het beleid zoals plaatsing en gebruikersbeheer in  [!DNL Assets Essentials].
role: Administrator
source-git-commit: e54cdf9b8ecb5d9ddc5b90a3ca82549c61b35074
workflow-type: tm+mt
source-wordcount: '769'
ht-degree: 0%

---


# [!DNL Assets Essentials] implementeren en gebruikers toevoegen {#administer}

[!DNL Adobe Experience Manager Assets Essentials] is provisioned door Adobe voor zijn klanten. Als onderdeel van de provisioning wordt [!DNL Assets Essentials] toegevoegd aan de organisatie van een klant (Adobe Org). De klant heeft ook toegang tot [!DNL Experience Manager Cloud Manager] als een implementatiehulpmiddel en tot [!DNL Admin Console] als een hulpmiddel voor gebruikersbeheer.

Beheerders voeren de volgende taken uit:

* [ [!DNL Assets Essentials]](#deploy-essentials) Implementatie voor hun organisatie.
* [Beheer de gebruikerstoegang ](#add-users-to-essentials) van de organisatieleden tot  [!DNL Assets Essentials].
* Naar keuze, [bekijk de de dienststatus en logboeken](#view-logs).

## [!DNL Assets Essentials] implementeren {#deploy-essentials}

Na levering, wordt [!DNL Assets Essentials] recht toegevoegd aan uw Adobe Org, en de beheerder van een organisatie stelt het op. De beheerders van de organisatie doen eenmalig plaatsing gebruikend [!DNL Cloud Manager] gebruikersinterface. Na de eerste implementatie voert Adobe het onderhoud en de updates van de service uit. Voer de volgende stappen uit om te implementeren:

1. Zorg ervoor dat de beheerder een e-mail van Adobe ontvangt. Het e-mailbericht bevat een welkomstbericht en een koppeling om aan de slag te gaan.

1. Via de koppeling in de e-mail hebt u toegang tot en aanmelding bij [Admin Console](https://adminconsole.adobe.com). Als u beheerdertoegang tot meer dan één organisatierekening hebt, dan selecteer de aangewezen organisatie of schakelaar aan het gebruikend de schakelaar in de hoogste bar. De productkaart voor [!DNL Assets Essentials] is zichtbaar in [!DNL Admin Console].

   ![[!DNL Assets Essentials] inchecken  [!DNL Admin Console]](assets/essentials-in-admin-console.png)

1. Voeg uzelf als beheerder toe aan het `AEM Assets Essentials - Cloud Manager` product in [!DNL Cloud Manager]. In plaats van uzelf, kunt u een ander lid van uw organisatie toevoegen of u kunt meer dan één beheerder toevoegen.

1. Klik ![voeg pictogram](assets/do-not-localize/add-icon.svg) aan [!UICONTROL Select product profiles] toe, en selecteer dan [!UICONTROL Deployment Manager - Assets Essentials] als **[!UICONTROL product profile]**. De gebruiker die aan deze stap is toegevoegd, ontvangt een e-mail van Adobe met toegang tot [!DNL Cloud Manager] en kan de implementatie uitvoeren.

   ![Een beheerder toevoegen en een productprofiel selecteren in  [!DNL Admin Console]](assets/adminconsole-user1.png)

1. Als u [!DNL Cloud Manager] wilt openen, klikt u op de koppeling in de e-mail met toegang tot [!DNL Cloud Manager]. U kunt ook `https://experience.adobe.com/#/cloud-manager/` openen in uw browser.

1. Klik in de gebruikersinterface van Cloud Manager op **[!UICONTROL Add Program]** in de rechterbovenhoek.

1. Geef een naam van uw keuze en upload desgewenst een afbeelding (het staat voor het programma in [!DNL Cloud Manager]) en klik op **[!UICONTROL Create]**. [!DNL Cloud Manager] Het duurt een paar minuten om het programma in te stellen.

1. Als het programma gereed is, plaatst u de aanwijzer boven de tegel en klikt u op ![Omgevingspictogram toevoegen](assets/do-not-localize/add-environment-icon.png).

1. Als u [!DNL Assets Essentials]-service aan uw organisatie wilt toevoegen, klikt u op **[!UICONTROL Add Environment]**, selecteert u een naam en een implementatiegebied en klikt u op **[!UICONTROL Save]**. U kunt het implementatiegebied later niet wijzigen. Probeer het implementatiegebied van [!DNL Assets Essentials] af te stemmen op het implementatiegebied van de andere oplossing waarmee u [!DNL Assets Essentials] wilt gebruiken. De overeenkomst moet ervoor zorgen dat de netwerken zo snel mogelijk toegang krijgen tot digitale middelen en de laagst mogelijke latentie.

   ![Een omgeving toevoegen in  [!DNL Cloud Manager]](assets/cloudmanager-add-environment-for-essentials.png)

1. Wanneer de omgeving is gemaakt, kunt u toegang krijgen tot [!DNL Admin Console] en de gebruikers van uw organisatie toevoegen aan [!DNL Assets Essentials]-oplossing. Klik op ![optiepictogram](assets/do-not-localize/options-ellipses-icon.png) en selecteer de optie **[!UICONTROL Manage Access]**.

   ![Klaar omgeving in  [!DNL Cloud Manager]](assets/cloudmanager-manage-access-essentials.png)

## Gebruikersbeheer {#add-users-to-essentials}

Een beheerder beheert welke gebruikers toegang hebben tot [!DNL Assets Essentials]. Beheerders gebruiken [!DNL Adobe Admin Console] om gebruikerstoegang toe te voegen of te verwijderen. [!DNL Assets Essentials] heeft de volgende twee soorten beschikbare gebruikerstoegang.

* **[!DNL Assets Essentials]Toegang** tot de volledige gebruikersinterface. Deze gebruikers kunnen digitale elementen uploaden, organiseren, labelen en zoeken.
* **[!DNL Assets Essentials]Consumentengebruikers**: toegang hebben tot de ingesloten ervaring voor het selecteren van elementen in de  [!DNL Adobe Journey Optimizer] e-mailsjablooneditor. Zie [Gebruik [!DNL Assets Essentials] in [!DNL Journey Optimizer]](https://experienceleague.adobe.com/docs/journey-optimizer/using/create-messages/assets-essentials.html) voor meer informatie.

In [!DNL Admin Console], worden deze twee toegangstypes vertegenwoordigd door twee [!UICONTROL Product Profiles]. Voer de volgende stappen uit om leden van uw organisatie toe te voegen aan en te verwijderen uit een van de twee profielen:

1. Open [!DNL Admin Console] voor uw organisatie, klik **[!UICONTROL Products]** in de hoogste bar, klik **[!UICONTROL AEM Assets Essentials]**, en klik dan [!DNL Assets Essentials] milieu. [!DNL Assets Essentials] heeft twee productprofielen die toegang voor gewone en consumentengebruikers vertegenwoordigen.

   ![Twee profielen voor twee soorten gebruikers](assets/adminconsole-user-types.png)

1. Als u een gebruiker aan een groep wilt toevoegen, klikt u op de groep, selecteert u **[!UICONTROL Add User]**, geeft u de gebruikersgegevens op en klikt u op **[!UICONTROL Save]**. Wanneer u een gebruiker toevoegt, ontvangt de gebruiker een e-mailuitnodiging om aan de slag te gaan. U kunt de e-mailuitnodigingen uitschakelen in de instellingen voor het productprofiel in [!DNL Admin Console].

   ![Een gebruiker toevoegen aan  [!DNL Assets Essentials]](assets/adminconsole-add-user.png)

1. Als u een gebruiker uit een groep wilt verwijderen, klikt u op de groep, selecteert u een bestaande gebruiker en selecteert u **[!UICONTROL Remove User]**.

>[!TIP]
>
>In [!DNL Admin Console] kunt u de gebruikers in bulk beheren gebruikend Csv- dossiers. Zie [[!DNL Admin Console] documentatie](https://helpx.adobe.com/enterprise/using/accounts.html) voor meer informatie.

## Servicestatus en toegangslogboeken weergeven {#view-logs}

Na provisioning implementeren beheerders [!DNL Assets Essentials] slechts eenmaal. Na de eerste implementatie voert Adobe het onderhoud en de updates van de service uit. Beheerders kunnen de [!DNL Cloud Manager]-gebruikersinterface gebruiken om de servicestatus te controleren en de recente toegangslogbestanden te downloaden.

1. Wanneer gebruikers problemen melden, controleert u de servicestatus van [!DNL Assets Essentials] in de **[!UICONTROL Program Overview]**-interface. Tijdens de normale werking van de oplossing is de status `Running`. Als [!DNL Cloud Manager] een andere status toont, creeer een steunkaartje in [!DNL Admin Console] steunsectie.

   ![Runstatus van  [!DNL Assets Essentials] in  [!DNL Cloud Manager]](assets/cloudmanager-manage-access-essentials.png)

1. Om de recente toegangslogboeken te downloaden, klik ![optiepictogram](assets/do-not-localize/options-ellipses-icon.png), selecteer **[!UICONTROL Download Logs]**, en volg de instructies op het scherm. U kunt de HTTPS-toegangsverzoeken controleren met behulp van de logboeken.

   ![Logbestanden downloaden, optie](assets/cloudmanager-download-logs.png)

>[!MORELIKETHIS]
>
>* [[!DNL Admin Console] help](https://helpx.adobe.com/enterprise/using/admin-console.html)
>* [[!DNL Cloud Manager] help](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html)
>* [Adobe Journey Optimizer-documentatie](https://experienceleague.adobe.com/docs/journey-optimizer/using/ajo-home.html)
>* [Opmerkingen bij de release](release-notes.md)
* [Aan de slag met [!DNL Assets Essentials]](get-started.md)

