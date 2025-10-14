---
title: AEM Assets verbinden met Creative Cloud
description: Leer hoe u AEM Assets configureert en verbindt met Creative Cloud. Maak verbinding met een Creative Cloud dat is toegewezen aan een andere IMS-organisatie om de meest recente integratie van Creatives Cloud in AEM Assets, waaronder Express en Creative Cloud Libraries, eenvoudig te kunnen gebruiken.
exl-id: 3d8d7429-ddf6-44cd-a6e7-ba2afcbaf52b
source-git-commit: 36f13972e7dc7b1546cdba0713a60f95f2bbc415
workflow-type: tm+mt
source-wordcount: '275'
ht-degree: 0%

---

# AEM Assets verbinden met Creative Cloud  {#cross-org-entitlements}

Experience Manager Assets heeft de mogelijkheid om verbinding te maken met een machtiging voor een Creative Cloud die is ingericht voor een andere IMS-organisatie om eenvoudig de nieuwste integraties van Creatives Cloud in AEM Assets, waaronder Express en Creative Cloud Libraries, te kunnen gebruiken.

Als uw producten van het Creative Cloud en AEM Assets aan afzonderlijke organisaties IMS worden geleverd, kunt u met een verschillende organisatie van het Creative Cloud verbinden om geïntegreerde werkschema&#39;s tussen de twee oplossingen uit te voeren.

## Vereisten {#prerequisites}

* Beheerdersrechten voor Experience Manager Assets

* Actieve bevoegdheid tot Creative Cloud voor de zelfde gebruiker - identiteitskaart die over Creative Cloud en Experience Manager wordt gebruikt. Rechten op persoonlijke en gefedereerde id&#39;s met hetzelfde e-mailadres worden beschouwd als verschillende gebruikers-id&#39;s.

## Verbinding maken met een nieuwe Creative Cloud {#connect-to-creative-cloud-org}

Voer de volgende stappen uit om verbinding te maken met een nieuwe Creative Cloud-organisatie:

1. Ga naar **[!UICONTROL Settings]** > **[!UICONTROL Creative Cloud]**.

1. Selecteer de nieuwe organisatie van het Creative Cloud met behulp van de vervolgkeuzelijst **[!UICONTROL Select new Creative Cloud org ID]** . In de lijst worden alle organisaties weergegeven waartoe u toegang hebt. Selecteer de organisatie met actieve rechten voor Creatives Cloud.

1. Klik op **[!UICONTROL Switch orgs]** om over te schakelen naar de nieuwe organisatie.

   ![&#x200B; dwars-Org Entitlements &#x200B;](assets/cross-org-entitlements.png)

## Beperkingen {#limitations}

* U kunt AEM Assets per keer verbinden met één organisatie van het Creative Cloud. Verbinding met meerdere organisaties van het Creative Cloud tegelijk wordt niet ondersteund.

* De organisatie van het Creative Cloud waarmee u verbinding maakt binnen AEM Assets is van toepassing op alle gebruikers binnen uw organisatie.
