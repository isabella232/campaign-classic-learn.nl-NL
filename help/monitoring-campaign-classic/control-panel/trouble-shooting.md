---
title: Problemen met het Configuratiescherm oplossen
description: Met het Configuratiescherm kunt u uw SFTP-opslag op instantie controleren en beheren en IP-adressen van lijsten van gewenste personen beheren.
feature: 'Configuratiescherm '
kt: 2938
doc-type: article
activity: use
team: PM
source-git-commit: 8910430585bdaa0db076db9c34b34798f649d39c
workflow-type: tm+mt
source-wordcount: '0'
ht-degree: 0%

---


# Problemen oplossen [!UICONTROL Control Panel]

## Aanmelding en startpagina

### Symptoom: Kan niet aanmelden bij Experience Cloud

**Wat te doen:**
de gebruiker moet van hun IMS Org ID (xxx) de plaats bepalen. De beheerder moet de gebruiker aan het Profiel van het Product &quot;Campagne-xxx-Admins&quot;voor elke instantie toevoegen die zij zouden willen leiden. Als de gebruiker een beheerder van alle instanties is, moeten zij toevoegen als gebruikers.

### Symptoom: Koppelingen in de Experience Cloud Home voor toegang tot [!UICONTROL Control Panel] worden niet weergegeven voor een gebruiker

**Oorzaak:**
Gebruikers zien de koppelingen pas wanneer ze als gebruikers zijn toegevoegd aan het productprofiel _Campaign-xxx-Administrators/Admin_.

**Wat te doen:**
De beheerder moet de gebruiker aan de Campagne-xxx- _Adminsfor van het Profiel van het Product_  toevoegen die zij zouden willen leiden. Als de gebruiker een beheerder van alle instanties is, moeten zij toevoegen als &quot;gebruikers.

### Symptoom: Een instantie wordt niet vermeld in het [!UICONTROL Control Panel]

**Oorzaak:**
Meest waarschijnlijke gebruiker moet als &quot;gebruiker&quot; _Campagne-xxx-Beheerders/_ Adminfor van het Profiel van het Product worden toegevoegd die ontbreekt

**Wat te doen:**
De beheerder moet de gebruiker aan de Campagne-xxx- _Adminsfor van het Profiel van het Product_  toevoegen die zij zouden willen leiden. Als de gebruiker een beheerder van alle instanties is, moeten zij toevoegen als &quot;gebruikers&quot;.

### Nuttige video’s

>[!VIDEO](https://video.tv.adobe.com/v/27183?quality=12)

*IMS-organisatie-id controleren (00:26 min)*

>[!VIDEO](https://video.tv.adobe.com/v/27147?quality=12)

*Een beheerder toevoegen aan het productprofiel voor beheerders om [!UICONTROL Control panel] te kunnen gebruiken (01:03 min)*

### Nuttige documentatie

* [Het Configuratiescherm verkennen](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=nl)
* [Machtigingen beheren voor het [!UICONTROL Control Panel]](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=en)

## Verbinding met SFTP-server tot stand brengen (client of API)

Voor verbinding met SFTP-servers is het volgende vereist:

* [!UICONTROL Allow listing] het IP-adres waarvan u verbinding maakt met de SFTP-server
* Persoonlijke/openbare sleutelparen die bij Adobe Campaign moeten worden geregistreerd
* Als u rechtstreeks verbinding maakt met de SFTP-server, hebt u SFTP-clientsoftware nodig

### Nuttige documentatie {#helpful-docs}

* [Aanmelden bij uw SFTP-server](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=en)

