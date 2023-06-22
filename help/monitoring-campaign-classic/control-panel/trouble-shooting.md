---
title: Problemen met het configuratiescherm oplossen
description: Met het Configuratiescherm kunt u uw SFTP-opslag op instantie controleren en beheren en IP-adressen van lijsten van gewenste personen beheren.
feature: Control Panel
jira: KT-2938
doc-type: article
activity: use
team: PM
source-git-commit: f4e86b933660ced199c30d318445363b74c51c4b
workflow-type: tm+mt
source-wordcount: '330'
ht-degree: 80%

---


# Problemen oplossen [!UICONTROL Control Panel]

## Aanmelding en startpagina

### Probleem: kan niet aanmelden bij Experience Cloud

**Wat moet u doen:**
De gebruiker moet de IMS-organisatie-id (xxx) zoeken. De beheerder moet de gebruiker toevoegen aan het productprofiel ‘Campaign-xxx-Admins’ voor elke versie die deze wil beheren. Als de gebruiker een beheerder van alle versies is, moet deze ook zichzelf toevoegen als gebruiker.

### Symptoom: Koppelingen in de Experience Cloud Home voor toegang tot [!UICONTROL Control Panel] worden niet weergegeven voor een gebruiker

**Oorzaak:**
Gebruikers zien de koppelingen pas wanneer ze als gebruikers zijn toegevoegd aan het productprofiel _Campaign-xxx-Administrators/Admin_.

**Wat moet u doen:**
De beheerder moet de gebruiker toevoegen aan het productprofiel _Campaign-xxx-Admins_ voor elke versie die deze wil beheren. Als de gebruiker een beheerder van alle instanties is, moeten zij toevoegen als &quot;gebruikers.

### Symptoom: Een instantie wordt niet vermeld in het [!UICONTROL Control Panel]

**Oorzaak:**
Meest waarschijnlijke gebruiker moet worden toegevoegd als een &quot;gebruiker&quot;-productprofiel _Campagne-xxx-beheerders/Admin_ voor de instantie die ontbreekt

**Wat moet u doen:**
De beheerder moet de gebruiker toevoegen aan het productprofiel _Campaign-xxx-Admins_ voor elke versie die deze wil beheren. Als de gebruiker een beheerder van alle versies is, moet deze ook zichzelf toevoegen als &#39;gebruiker&#39;.

### Nuttige video’s

>[!VIDEO](https://video.tv.adobe.com/v/27183?quality=12&learn=on)

*IMS-organisatie-id controleren (00:26 min)*

>[!VIDEO](https://video.tv.adobe.com/v/27147?quality=12&learn=on)

*Een beheerder toevoegen aan het productprofiel voor beheerders om [!UICONTROL Control panel] te kunnen gebruiken (01:03 min)*

### Nuttige documentatie

* [Het Configuratiescherm verkennen](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=nl)
* [Machtigingen beheren voor het [!UICONTROL Control Panel]](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=nl)

## Verbinding met SFTP-server tot stand brengen (client of API)

Voor verbinding met SFTP-servers is het volgende vereist:

* [!UICONTROL Allow listing] het IP-adres waarvan u verbinding maakt met de SFTP-server
* Persoonlijk/openbaar sleutelpaar dat bij Adobe Campaign moet zijn geregistreerd
* Als u rechtstreeks verbinding maakt met de SFTP-server, hebt u SFTP-clientsoftware nodig

### Nuttige documentatie {#helpful-docs}

* [Aanmelden bij uw SFTP-server](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=nl)

