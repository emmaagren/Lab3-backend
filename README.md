# Laboration 3 - REST API med MongoDB

## Beskrivning

En REST-baserad webbtjänst för att hantera arbetslivserfarenheter. Webbtjänsten är skapad med Node.js och Express och använder MongoDB som databas tillsammans med Mongoose.

API:et har stöd för CRUD-operationer och returnerar data i JSON-format.

## Tekniker

- Node.js
- Express
- MongoDB Atlas
- Mongoose
- CORS
- dotenv

## Funktionalitet

Webbtjänsten kan:
- Hämta alla arbetslivserfarenheter (GET).
- Lägga till nya arbetslivserfarenheter (POST).
- Uppdatera befintliga arbetslivserfarenheter (PUT).
- Radera arbetslivserfarenheter (DELETE).

Inmatad data valideras och tydliga felmeddelanden returneras vid fel.

## API-endpoints

**Lokal API-adress:**
`http://localhost:3000/api/workexperience`

**Publicerad API-adress:**
`https://lab3-workexperience-api.onrender.com/api/workexperience`

## Installation

Klona projektet och installera beroenden:

```bash
npm install
```

Skapa en `.env`-fil med anslutningsadressen till MongoDB:

```env
MONGODB_URI=din_anslutningsadress
```

Starta servern:

```bash
node server.js
```

## Databas

MongoDB används för att lagra arbetslivserfarenheter med följande fält:

- companyname
- jobtitle
- location
- startdate
- enddate
- description

Varje dokument får automatiskt ett unikt `_id`.

## Kurs

Backend-baserad webbutveckling - Laboration 3, uppgift 1.

## Skapad av

Emma Ågren
student
MIUN