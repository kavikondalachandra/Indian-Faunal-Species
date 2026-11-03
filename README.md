# National Biodiversity Portal of India
### Comprehensive Faunal, Mammalian, Amphibian & Insect Species Database & Interactive GIS Atlas

> **Concept & Design by K.S.Chandra 2026**  
> **Contact:** [kavikondalaschandra@gmail.com](mailto:kavikondalaschandra@gmail.com)

---

## 🌟 Overview

This repository hosts the **National Biodiversity Portal of India**, a web-ready, interactive biodiversity database and GIS atlas covering all 28 States and 8 Union Territories across all 735 administrative districts.

### Core Database Metrics
* **Total States & UTs:** 36 (All 28 States + 8 Union Territories)
* **Administrative Districts Covered:** 735 Districts
* **Master Species Cataloged:** 518 Species
* **High-Quality Photographic Records:** 518 / 518 Species (100% verified photography)
* **Specialized Deep-Dives:**
  * **Class Mammalia:** 46 Species (Carnivores, River Dolphins, Alpine Ungulates, Bats, Whales)
  * **Class Amphibia:** 27 Species (Western Ghats, Northeast & Andaman Endemics)
  * **Class Insecta:** 25 Species (Lepidoptera, Odonata, Hymenoptera, Hemiptera)
* **State Top Faunal Records:** 1,430 Verified Taxa
* **Ecosystem Realms:** Land (Terrestrial), Water (Freshwater), Sea (Marine), Air (Aerial)
* **Scientific Citations & Sources:** 17 Statutory & Institutional Repositories (ZSI, WII, MoEFCC, GBIF, IUCN Red List, ENVIS, BNHS, CITES)

---

## 🚀 Instant Web Deployment

This project is configured as a zero-dependency, static web application ready for one-click deployment across all major static hosting platforms.

### Option 1: GitHub Pages
1. Push this repository to GitHub.
2. In the repository settings, go to **Settings > Pages**.
3. Under **Build and deployment > Branch**, select `main` (or `master`) and folder `/ (root)`.
4. Click **Save**. The website is live in seconds.

### Option 2: Vercel (Zero Configuration)
Run the following in the repository root:
```bash
npx vercel
```
Or connect your GitHub repository directly to [Vercel](https://vercel.com). The pre-configured `vercel.json` provides instant zero-config routing.

### Option 3: Netlify
Run the following:
```bash
npx netlify deploy --prod
```
Or drag-and-drop the project folder directly into the Netlify Dashboard. The pre-configured `netlify.toml` handles routing.

### Option 4: Local Preview
Using Python:
```bash
python -m http.server 8080
```
Open `http://localhost:8080` in your web browser.

Using Node.js:
```bash
npm start
```

---

## 📁 Repository Structure

```
.
├── index.html                                      # Self-contained Web Application & Interactive GIS Atlas
├── India_Faunal_Species_Comprehensive_Database.xlsx# Master Excel Database (11 Sheets, Photo URLs, Citations)
├── complete_dashboard_data.json                    # Full structured JSON dataset (for REST/API integrations)
├── vercel.json                                     # Vercel deployment configuration
├── netlify.toml                                    # Netlify deployment configuration
├── package.json                                    # Project metadata and static server scripts
└── README.md                                       # Documentation & Deployment Guide
```

---

## 📜 Citations, References & Scientific Sources
1. **Zoological Survey of India (ZSI)** – Animal Discoveries & Faunal Diversity in India.
2. **Wildlife Institute of India (WII)** – National Wildlife Database & ENVIS Centre on Wildlife & Protected Areas.
3. **Global Biodiversity Information Facility (GBIF)** – Occurrence datasets for Indian Animalia & Insecta.
4. **IUCN Red List of Threatened Species (v2024-2)** – Global threat categorisation and population trends.
5. **Ministry of Environment, Forest and Climate Change (MoEFCC)** – Wildlife (Protection) Act, 1972 & Amendment Act, 2022.
6. **Convention on International Trade in Endangered Species of Wild Fauna and Flora (CITES)** – Appendices I, II, III (2024).
7. **Bombay Natural History Society (BNHS)** – Monographs on Indian Avifauna and Mammalia.
8. **India Biodiversity Portal (IBP)** – Open-access citizen science and participatory mapping data.

---

## 👤 Author & Licensing
* **Concept & Design:** K.S.Chandra (2026)
* **Contact:** [kavikondalaschandra@gmail.com](mailto:kavikondalaschandra@gmail.com)
* **Data License:** CC-BY 4.0 International
