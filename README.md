# Speedmakers website

Statische Astro-site voor het ski- en snowboardonderhoud van Speedmakers in Slijpe.

## Lokaal in VS Code

```sh
npm ci
npm run dev
```

Home staat op `/`, de FAQ op `/faq/` en Contact behoudt het bestaande adres `/contactgegevens/`. De tarieven, adressen, telefoonnummers en openingsuren staan in `src/content/business.js`. De WhatsApp-knop staat in `src/components/WhatsAppLink.astro`.

## Afzonderlijk Vercel-project

Importeer `diego-kopilo-be/Speedmakers` als eigen project en kies de Astro-preset. Het commando `npm run build` schrijft de site naar `dist/`. Gebruik voor deze commerciële website een Vercel Pro-team. Koppel het domein pas nadat de preview is goedgekeurd.
