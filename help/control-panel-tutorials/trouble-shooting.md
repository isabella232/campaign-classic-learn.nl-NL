---
title: Problemen met het Configuratiescherm oplossen
description: Leer hoe u het Configuratiescherm problemen kunt oplossen.
feature: 'Configuratiescherm '
kt: 2938
doc-type: article
activity: use
team: PM
role: Admin
level: Experienced
original-url: https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/administrating/control-panel-acc/trouble-shooting.html
exl-id: 016e8b77-20df-4ca5-b5e7-fe2f3e7ba7a3
source-git-commit: 2f8ae3d47e4debf71311f341d3c02ff3a7f5297a
workflow-type: tm+mt
source-wordcount: '322'
ht-degree: 38%

---

# Problemen oplossen [!UICONTROL Control Panel]

## Aanmelding en startpagina

### Symptoom: Kan niet aanmelden bij Experience Cloud

**Wat te doen:**
de gebruiker moet van hun IMS Org ID (xxx) de plaats bepalen. De beheerder moet de gebruiker aan het Profiel van het Product &quot;Campagne-xxx-Admins&quot;voor elke instantie toevoegen die zij zouden willen leiden. Als de gebruiker een beheerder van alle instanties is, moeten zij toevoegen als gebruikers.

### Symptoom: Koppelingen in de Experience Cloud Home voor toegang tot [!UICONTROL Control Panel] worden niet weergegeven voor een gebruiker

**Oorzaak:**
Gebruikers zien de koppelingen pas nadat ze als gebruikers aan de  _campagne-xxx-beheerders/Admin_ voor productprofielen zijn toegevoegd.

**Wat te doen:**
De beheerder moet de gebruiker aan de Campagne-xxx- _Adminsfor van het Profiel van het Product_  toevoegen die zij zouden willen leiden. Als de gebruiker een beheerder van alle instanties is, moeten zij toevoegen als gebruikers.

### Symptoom: Een instantie wordt niet vermeld in het [!UICONTROL Control Panel]

**Oorzaak:**
Meest waarschijnlijke gebruiker moet worden toegevoegd als  ** userProduct Profile  _Campaign-xxx-Administrators/_ Adminfor de instantie die mist

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
* Als u rechtstreeks verbinding wilt maken met de SFTP-server, hebt u ook SFTP-clientsoftware nodig

### Nuttige documentatie {#helpful-docs}

* [Aanmelden bij uw SFTP-server](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=en)
