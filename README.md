# Afstudeerstage Dura Vermeer Railinfra – RESA-app

Voor mijn afstudeerstage van de opleiding Ad Software Development aan Hogeschool Rotterdam heb ik bij **Dura Vermeer Railinfra** gewerkt aan de **RESA-app** (Resource Aanvragen).

## Beschrijving

Binnen Railinfra werden aanvragen voor personeel en andere resources bijgehouden via onder andere Excel, e-mail en WhatsApp. Daardoor was het soms lastig om overzicht te houden en te zien wat de status van een aanvraag was.

Mijn opdracht was om een eerste werkende versie te bouwen van een webapplicatie waarin werkvoorbereiders aanvragen kunnen indienen en planners ze op één plek kunnen bekijken en behandelen.

## Tech stack

- **Frontend:** React, TypeScript, Vite
- **Backend:** Python, FastAPI, Pydantic, SQLAlchemy
- **Database:** PostgreSQL, Docker, Alembic
- **Tests:** pytest
- **Overig:** REST API, Git/GitHub, Trello

## Mijn bijdrage

Ik heb grotendeels zelfstandig aan dit project gewerkt, van de eerste analyse tot de lokale MVP.

- Het bestaande aanvraagproces onderzocht en gesprekken gevoerd met betrokken medewerkers.
- Requirements uitgewerkt en prioriteiten bepaald met onder andere MoSCoW.
- Een aanvraagflow gemaakt waarin gebruikers projectgegevens, werkplekken en resourceplanning kunnen invullen en een aanvraag kunnen indienen.
- Een omgeving voor planners gebouwd met een dashboard, aanvragenoverzicht, zoek- en filtermogelijkheden en een detailpagina.
- De frontend, backend en database aan elkaar gekoppeld via een REST API.
- Rollen en rechten voor aanvragers en planners verwerkt, inclusief statuswijzigingen en statusgeschiedenis.
- De belangrijkste backendfunctionaliteiten getest met pytest en verbeteringen doorgevoerd op basis van feedback.

De aanvraag doorloopt de volgende statusflow:

`concept → ingediend → in behandeling → goedgekeurd / afgewezen`

## Wat ik heb geleerd

- Eerst goed begrijpen hoe het proces werkt en wat de gebruikers nodig hebben voordat je gaat bouwen.
- Een grotere full-stack applicatie opzetten en de verschillende onderdelen laten samenwerken.
- Business rules, zoals de statusflow en rechten van gebruikers, ook in de backend controleren.
- Zelfstandig plannen, keuzes onderbouwen en de scope van een project bewaken.
- Werken met feedback en testen om fouten in de applicatie op te lossen.

## Resultaat

Het eindresultaat was een **lokale MVP** waarmee de belangrijkste stappen van het RESA-proces konden worden gedemonstreerd. Het was nog geen productieapplicatie. Onderdelen zoals concepten volledig opslaan en hervatten, uitgebreid filteren en productiebeveiliging waren nog niet helemaal uitgewerkt.

De originele projectcode staat in een aparte privé-repository. Deze repo is bedoeld om kort te laten zien wat ik tijdens mijn afstudeerstage heb gedaan, zonder interne broncode te delen.

## Screenshots

<img width="1280" height="720" alt="download" src="https://github.com/user-attachments/assets/7b3cdd44-8990-4b94-9b96-5ffbd9c35acc" />


### 1. Nieuwe aanvraag

### 2. Projectgegevens en werkplekken

### 3. Resourceplanning

### 4. Controleren en indienen

