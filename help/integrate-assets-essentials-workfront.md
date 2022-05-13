---
title: Assets Essentials integreren met Adobe Workfront
description: Integreer Assets Essentials met de Adobe Workfront-toepassing, zodat u toegang krijgt tot de Assets Essentials-opslagplaats in de Workfront-toepassing.
source-git-commit: 7d49060ba2e02bd9c5caf9753ef56b5feed5b3df
workflow-type: tm+mt
source-wordcount: '609'
ht-degree: 0%

---


# Assets Essentials integreren met Adobe Workfront {#integrate-assets-essentials-workfront}

![Voorkeur voor schakelen tussen donker en licht thema](assets/cce-workfront.png)

## Het verhaal tot nu toe

Na [configureren van Experience Manager Assets Essentials](adminster-aem-assets-essentials.md) en [integratie van de Creative Cloud-toepassingen met Assets Essentials](integrate-assets-essentials-creative-cloud.md)kunt u verder bouwen om de Adobe Workfront-toepassing te integreren met Assets Essentials.

## Doelstelling

* **Publiek**: Adobe Workfront-beheerders

* **Doelstelling**: Integreer Assets Essentials met de Adobe Workfront-toepassing, zodat u toegang krijgt tot de Assets Essentials-opslagplaats in de Workfront-toepassing.

## Overzicht

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

Voor meer informatie over het toewijzen van gebruikers aan Assets Essentials-productprofielen raadpleegt u [Gebruikers toewijzen aan Assets Essentials-productprofielen](adminster-aem-assets-essentials.md#add-users-to-product-profiles).

## Experience Manager Assets Essentials Integration configureren {#configure-assets-essentials-integration}

Nadat u gebruikers met de Admin Console hebt toegevoegd aan de Workfront- en Assets Essentials-productprofielen, kunt u [De integratie met Experience Manager Assets Essentials configureren](https://one.workfront.com/s/document-item?bundleId=the-new-workfront-experience&amp;topicId=Content%2FDocuments%2FAdobe_Workfront_for_Experience_Manager_Assets_Essentials%2F_workfront-for-aem-asset-essentials.htm).

Nadat u de integratie hebt ingesteld, kunt u:

* [Elementen en mappen koppelen vanuit Experience Manager Assets Essentials](https://one.workfront.com/s/document-item?bundleId=the-new-workfront-experience&amp;topicId=Content%2FDocuments%2FAdobe_Workfront_for_Experience_Manager_Assets_Essentials%2Flink-to-aem.htm&amp;_LANG=enus)

* [Een document verzenden naar Experience Manager Assets Essentials](https://one.workfront.com/s/document-item?bundleId=the-new-workfront-experience&amp;topicId=Content%2FDocuments%2FAdobe_Workfront_for_Experience_Manager_Assets_Essentials%2Fsend-to-aem.htm&amp;_LANG=enus)

* [Bewijs van een gekoppeld element voor Experience Manager Assets Essentials](https://one.workfront.com/s/document-item?bundleId=the-new-workfront-experience&amp;topicId=Content%2FDocuments%2FAdobe_Workfront_for_Experience_Manager_Assets_Essentials%2Fproof-linked-asset-aem.htm)

* [Een gekoppeld element weergeven of downloaden vanuit Experience Manager Assets Essentials](https://one.workfront.com/s/document-item?bundleId=the-new-workfront-experience&amp;topicId=Content%2FDocuments%2FAdobe_Workfront_for_Experience_Manager_Assets_Essentials%2Fview-download-asset.htm)
