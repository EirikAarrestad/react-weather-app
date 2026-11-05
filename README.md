# WeatherApp – værvarsel for neste døgn

En enkel nettapp i React der du skriver inn en by eller et land og får dagens temperatur og en time-for-time-oversikt over neste 24 timer, hentet fra [WeatherAPI](https://www.weatherapi.com/).

## Funksjoner

- Søk etter by eller land
- Viser nåværende følt temperatur i °C
- Tabell med temperatur og værikon for hver time gjennom døgnet
- Navigasjon mellom Celsius og Fahrenheit

## Teknologi

- **React 18** (Create React App) med funksjonskomponenter og `useState`
- **styled-components** og CSS-moduler for utseendet
- **Fetch API** mot WeatherAPI sitt `forecast`-endepunkt
- **react-router-dom** for navigasjon

## Filer

```
├── src/
│   ├── index.js                     # inngangspunkt
│   └── pages/
│       ├── components/              # DailyForecast, Navbar, tabeller
│       └── styles/                  # styled-components og CSS
├── public/                          # index.html og statiske filer
└── .env.example                     # mal for API-nøkkelen
```

## Kjøring

1. Lag en gratis API-nøkkel på [weatherapi.com](https://www.weatherapi.com/).
2. Kopier `.env.example` til `.env` og lim inn nøkkelen.
3. Installer og start:

```bash
npm install
npm start
```

Appen åpnes på http://localhost:3000.

## Forfatter

Eirik Aarrestad – bachelor i statistikk og data science, UiB
