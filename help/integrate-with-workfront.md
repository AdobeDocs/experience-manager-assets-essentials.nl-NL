---
title: Assets Essentials integreren met Adobe Workfront
description: Integreer Assets Essentials met de Adobe Workfront-toepassing, zodat u toegang krijgt tot de Assets Essentials-opslagplaats in de Workfront-toepassing.
source-git-commit: 8920080944981fc1a990136af46c9258c5e8627c
workflow-type: tm+mt
source-wordcount: '562'
ht-degree: 0%

---

# Assets Essentials integreren met Adobe Workfront {#integrate-assets-essentials-workfront}

[[!DNL Adobe Workfront]](https://www.workfront.com/) is een werkbeheertoepassing waarmee u de volledige levenscyclus van het werk op één locatie kunt beheren. De native integratie tussen [!DNL Adobe Workfront] en [!DNL Assets Essentials] organisaties kunnen de snelheid van de inhoud en de tijd aan markt verbeteren door werk en activabeheer intrinsiek met elkaar te verbinden. In het kader van het beheer van hun werk hebben gebruikers toegang tot de vereiste documenten en afbeeldingen in dezelfde oplossing.

Voer de volgende taken uit om Workfront te integreren met Experience Manager Assets Essentials:

* [Gebruikers toevoegen aan Workfront-productprofielen](#add-users-to-product-profiles)

* [Gebruikers toevoegen aan Assets Essentials-productprofielen](#add-workfront-users-assets-essentials-product-profiles)

* [Experience Manager Assets Essentials Integration configureren](#configure-assets-essentials-integration)

## Gebruikers toevoegen aan Workfront-productprofielen {#add-users-to-product-profiles}

Gebruikers toevoegen aan Workfront-productprofielen:

1. Toegang [Admin Console](https://adminconsole.adobe.com) voor uw organisatie klikt u op **[!UICONTROL Products]** in de bovenste balk klikt u op **[!UICONTROL Workfront]** en klik op het eerste exemplaar in de lijst. Klik niet op de tweede en derde instantie in de lijst.

   ![Beheerprofiel Admin Console](assets/workfront-instances.png)

   Admin Console geeft het enige beschikbare productprofiel weer.

1. Als u een gebruiker aan een productprofiel wilt toevoegen, klikt u op het profiel en klikt u op **[!UICONTROL Add User]**, geef de gebruikersgegevens op en klik op **[!UICONTROL Save]**.

   ![Beheerdersprofiel voor gebruikers toevoegen](assets/add-users-workfront.png)

   Wanneer u een gebruiker toevoegt, ontvangt de gebruiker een e-mailuitnodiging om aan de slag te gaan. U kunt de e-mailuitnodigingen in de instellingen voor het productprofiel uitschakelen in [!DNL Admin Console].

1. Als u een gebruiker uit een groep wilt verwijderen, klikt u op de groep, selecteert u een bestaande gebruiker en selecteert u **[!UICONTROL Remove User]**.

Ga voor meer informatie over het maken van gebruikers en systeembeheerders in Workfront met Adobe Admin Console naar [Gebruikers beheren in de Adobe Admin Console](https://one.workfront.com/s/document-item?bundleId=the-new-workfront-experience&amp;topicId=Content%2FAdministration_and_Setup%2FAdd_users%2FCreate_and_manage_users%2Fadmin-console.htm&amp;_LANG=enus).

## Gebruikers toevoegen aan Assets Essentials-productprofielen {#add-workfront-users-assets-essentials-product-profiles}

Wijs de Workfront-gebruikers toe aan een van de volgende Assets Essentials-productprofielen:

* **[!DNL Assets Essentials]Gebruikers** toegang hebben tot de volledige Assets Essentials-gebruikersinterface. Deze gebruikers kunnen digitale middelen uploaden, organiseren, labelen en zoeken in een Assets Essentials-toepassing. Bovendien hebben de gebruikers toegang tot de ingesloten selectie van elementen in [!DNL Adobe Workfront] toepassing.
* **[!DNL Assets Essentials]Consumentengebruikers**: toegang hebben tot de ervaring die is opgedaan met het selecteren van ingesloten elementen in [!DNL Adobe Workfront] toepassing.

Daarnaast is er ook **[!DNL Assets Essentials]Beheerders** productprofiel dat administratieve toegang tot de toepassing biedt.

Voor meer informatie over het toewijzen van gebruikers aan Assets Essentials-productprofielen raadpleegt u [Gebruikers toewijzen aan Assets Essentials-productprofielen](deploy-administer.md#add-users-to-product-profiles).

## Experience Manager Assets Essentials Integration configureren {#configure-assets-essentials-integration}

Nadat u gebruikers met de Admin Console hebt toegevoegd aan de Workfront- en Assets Essentials-productprofielen, kunt u [De integratie van Experience Manager Assets Essentials met Adobe Workfront configureren](https://one.workfront.com/s/document-item?bundleId=the-new-workfront-experience&amp;topicId=Content%2FDocuments%2FAdobe_Workfront_for_Experience_Manager_Assets_Essentials%2F_workfront-for-aem-asset-essentials.htm).

Nadat u de integratie hebt ingesteld, kunt u:

* [Elementen en mappen koppelen vanuit Experience Manager Assets Essentials](https://one.workfront.com/s/document-item?bundleId=the-new-workfront-experience&amp;topicId=Content%2FDocuments%2FAdobe_Workfront_for_Experience_Manager_Assets_Essentials%2Flink-to-aem.htm&amp;_LANG=enus)

* [Een document verzenden naar Experience Manager Assets Essentials](https://one.workfront.com/s/document-item?bundleId=the-new-workfront-experience&amp;topicId=Content%2FDocuments%2FAdobe_Workfront_for_Experience_Manager_Assets_Essentials%2Fsend-to-aem.htm&amp;_LANG=enus)

* [Bewijs van een gekoppeld element voor Experience Manager Assets Essentials](https://one.workfront.com/s/document-item?bundleId=the-new-workfront-experience&amp;topicId=Content%2FDocuments%2FAdobe_Workfront_for_Experience_Manager_Assets_Essentials%2Fproof-linked-asset-aem.htm)

* [Een gekoppeld element weergeven of downloaden vanuit Experience Manager Assets Essentials](https://one.workfront.com/s/document-item?bundleId=the-new-workfront-experience&amp;topicId=Content%2FDocuments%2FAdobe_Workfront_for_Experience_Manager_Assets_Essentials%2Fview-download-asset.htm)
