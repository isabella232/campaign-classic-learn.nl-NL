---
title: Aan de slag met pushmeldingen voor Android - Inleiding
description: Deze zelfstudie begeleidt u door de stappen die nodig zijn voor het verzenden van pushberichten van Adobe Campaign en het ontvangen van deze meldingen in uw Android-app.
feature: push
topics: mobile channels
kt: 6438
doc-type: article
activity: setup
team: TM
translation-type: tm+mt
source-git-commit: 016f47e131df9c3a25b9131da372efaedf6cd5ad
workflow-type: tm+mt
source-wordcount: '365'
ht-degree: 2%

---


# Aan de slag met pushmeldingen voor Android - Inleiding

Adobe Campaign allows you to send personalized and segmented [!DNL push] notifications to [!DNL iOS] and [!DNL Android] mobile devices. Deze zelfstudie begeleidt u door de stappen die nodig zijn voor het verzenden van [!DNL push] berichten van Adobe Campaign naar een [!DNL Android] app.

## Vereisten

Voordat u kunt beginnen, hebt u het volgende nodig:

1) **Android Mobile-toepassing**

   Deze zelfstudie behandelt niet de gedetailleerde stappen die nodig zijn om de mobiele toepassing in te stellen. U moet beschikken over een **[!DNL Android]mobiele toepassing met de [!DNL Campaign SDK] geïntegreerde**.

   U vindt een gedetailleerde beschrijving van de vereiste stappen in de productdocumentatie:

   [De Campaign-SDK integreren in de mobiele applicatie](https://experienceleague.adobe.com/docs/campaign-classic/using/sending-messages/sending-push-notifications/integrating-campaign-sdk-into-the-mobile-application.html)

   U kunt ook de Experience Platform Mobile SDK gebruiken. Bekijk de videozelfstudie voor meer informatie:

   [Het pushkanaal configureren met de Experience Platform Mobile SDK](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/sending-messages/push-channel/configure-push-using-aep-mobile-sdk.html)

2) **[!DNL Mobile App channel]pakket geïnstalleerd**

   Het [!DNL Mobile App channel] pakket moet op uw [!DNL Campaign] instantie worden geïnstalleerd. In de volgende video wordt uitgelegd hoe u kunt controleren of het programma op uw exemplaar [!DNL Mobile App channel] is geïnstalleerd en, indien dit niet het geval is, hoe u het programma kunt installeren.

>[!VIDEO](https://video.tv.adobe.com/v/326544?quality=12)

## Overzicht van zelfstudie

We willen graag een persoonlijke promotiekennisgeving sturen [!DNL push] naar de abonnees van de [!DNL Neotrip] [!DNL Android] mobiele app. De [!DNL Neotrip] app is geconfigureerd met de [!DNL Campaign SDK] en we hebben ervoor gezorgd dat de app [!DNL Mobile App channel] op ons [!DNL Campaign] exemplaar wordt geactiveerd.

De volgende configuratiestappen worden vereist:

### Stap 1: Het schema voor app-abonnementen uitbreiden om [!DNL push] meldingen aan te passen

Aangezien wij de [!DNL push] kennisgeving willen personaliseren, zullen wij eerst het schema [van het toepassingsabonnement](/help/tutorial-getting-started-with-push-notifications-for-android/extending-the-app-subscription-schema.md) uitbreiden om de verpersoonlijkingswaarden op te slaan die wij van app ontvangen wanneer de gebruiker aan de dienst abonneert.

### Stap 2: De Android-service configureren en de mobiele toepassing maken in Campagne

Vervolgens moeten we de Android-service [configureren en de mobiele toepassing maken in Campagne](/help/tutorial-getting-started-with-push-notifications-for-android/configuring-an-android-service-in-campaign.md). In deze stap definiëren we de [!DNL Neotrip] app als het doel voor de pushmelding.

### Stap 3: De pushmelding configureren en verzenden

Dan zijn wij bereid om het dupbericht [te](/help/tutorial-getting-started-with-push-notifications-for-android/configuring-and-sending-push-notifications.md)vormen en te verzenden.

## Zelfstudie starten

Stap 1: [Het schema voor app-abonnementen uitbreiden](/help/tutorial-getting-started-with-push-notifications-for-android/extending-the-app-subscription-schema.md)
