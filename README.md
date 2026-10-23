# Kruidenwijzer — Vercel/GitHub project

## Publiceren met GitHub + Vercel

1. Open GitHub en maak een nieuwe repository aan met de naam `kruidenwijzer`.
2. Kies bij voorkeur **Public** als je de app openbaar wilt delen, of **Private** als je de broncode privé wilt houden.
3. Upload de bestanden uit deze map naar de hoofdmap (root) van de repository:
   - `index.html`
   - `styles.css`
   - `app.js`
   - `manifest.json`
   - `sw.js`
   - `vercel.json`
4. Open Vercel → **Add New** → **Project**.
5. Importeer de GitHub-repository `kruidenwijzer`.
6. Framework Preset: **Other**. Build Command leeg laten; Output Directory leeg laten (statische HTML-site).
7. Klik **Deploy**.
8. Open de URL die Vercel toont. Gebruik deze HTTPS-URL op de Samsung. Voeg eventueel toe aan startscherm via Chrome-menu → **Toevoegen aan startscherm**.

## Inhoud
- Zoekfunctie
- Categorieën
- Detailpagina's met ingrediënten, stappen en veiligheidsinformatie
- Favorieten (opgeslagen op het apparaat)
- Basis offline-cache voor reeds geladen bestanden

## Status en medische veiligheid
Dit is een functioneel prototype met 12 voorbeelditems, geen complete database van 250 remedies. De inhoud is educatief en moet voor publicatie deskundig worden gecontroleerd. De app stelt geen diagnose en vervangt geen arts of apotheker.
