# Belgisch Brouwerijhandboek & Technologie — Python Notebooks

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ronniewillaert/BHBT-Python-oefeningen/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

Interactieve Python-notebooks bij het handboek **Belgische Brouwerijhandboek & Technologie (BHBT)**.
Elke notebook vertaalt theorie naar kwantitatieve modellen die je zelf kan verkennen — van systeemdenken over waterchemie tot procesoptimalisatie.

```
Theorie  →  Model  →  Simulatie  →  Procesinzicht
```

---

## Snel starten

1. Klik op een **Open in Colab**-link bij de notebook die je wil openen.
2. Meld je aan met je Google-account (gratis).
3. Voer alle cellen uit via **Runtime → Run all** (`Ctrl + F9`).
4. Experimenteer met de **interactieve sliders** en analyseer het effect op de procesuitkomsten.

> **Tip:** je hoeft niets lokaal te installeren — alles draait in de browser via Google Colab.

---

## Overzicht van de notebooks

### Deel I — Context en systeemdenken

#### Hoofdstuk 1 — De Belgische brouwerijsector en het brouwproces

| # | Notebook | Beschrijving |
|---|----------|--------------|
| 1 | [Schematisch IPO-model](notebooks/01_Deel_I_Context/H1_Belgische_brouwerijsector/BHBT_H1_Oefening1_Schematisch_IPO_model.ipynb) | Het brouwproces als gekoppeld input–proces–output-systeem. Interactieve sliders om het effect van variatie in moutmassa, extractopbrengst, kookintensiteit en vergistingsgraad op OG, FG en ABV te verkennen. Inclusief gevoeligheidsanalyse en Monte Carlo-simulatie. |

---

### Deel II — Grondstoffen

#### Hoofdstuk 2 — Water

Zes notebooks die samen een geïntegreerde waterdesign-workflow vormen — van fundamentele zuur–base-chemie tot volledig geautomatiseerde stijlgebaseerde optimalisatie.

| # | Notebook | Beschrijving |
|---|----------|--------------|
| 1 | [Mash pH-model (Henderson–Hasselbalch)](notebooks/02_Deel_II_Grondstoffen/H2_Water/01_Mash_pH_model_HH.ipynb) | Zuur–base-evenwichten en pH-voorspelling in de maisch. |
| 2 | [Waterprofiel & Residual Alkalinity](notebooks/02_Deel_II_Grondstoffen/H2_Water/02_Waterprofiel_RA.ipynb) | Ionenbalans, alkaliniteit en het RA-concept van Kolbach. |
| 3 | [Waterblending & doelprofieloptimalisatie](notebooks/02_Deel_II_Grondstoffen/H2_Water/03_Water_blending_optimizer.ipynb) | Optimale mengverhouding van waterbronnen berekenen. |
| 4 | [Zouttoevoegingen & stijlgebaseerde waterdesign](notebooks/02_Deel_II_Grondstoffen/H2_Water/04_Zouttoevoegingen_stijl_waterdesign.ipynb) | Zouten doseren om een doelwaterprofiel te bereiken. |
| 5 | [Zout + zuur → pH-doel in de maisch](notebooks/02_Deel_II_Grondstoffen/H2_Water/05_Zout_zuur_naar_mash_pH_doel.ipynb) | Gecombineerde zout- en zuurtoevoegingen voor pH-sturing. |
| 6 | [Capstone: AutoWaterDesign (Tripel / IPA / Stout)](notebooks/02_Deel_II_Grondstoffen/H2_Water/06_Capstone_AutoWaterDesign_Tripel_IPA_Stout.ipynb) | Volledig geautomatiseerd waterdesign voor drie Belgische/internationale stijlen. |

> **Kernidee:** waterdesign is geen losse berekening, maar een gekoppeld chemisch systeem waarin ionensamenstelling, alkaliniteit en pH elkaar beïnvloeden.

#### Hoofdstuk 3 — Mout
> *Notebooks in voorbereiding*

#### Hoofdstuk 4 — Hop
> *Notebooks in voorbereiding*

#### Hoofdstuk 5 — Gist
> *Notebooks in voorbereiding*

---

### Deel III — Wortproductie

#### Hoofdstuk 6 — Maischen & filtratie
> *Notebooks in voorbereiding*

#### Hoofdstuk 7 — Koken & koelen
> *Notebooks in voorbereiding*

---

### Deel IV — Procescontrole, schaal en engineering

#### Hoofdstuk 8 — Procescontrole & schaal
> *Notebooks in voorbereiding*

---

## Didactische filosofie

Deze notebooks zijn geen kant-en-klare rekenmachines, maar **leeromgevingen** waarin je:

- **variabiliteit expliciet maakt** — via parameter sweeps en Monte Carlo-simulaties;
- **aannames zichtbaar maakt** — elk model documenteert wat het vereenvoudigt;
- **gevoeligheidsanalyses uitvoert** — om te begrijpen welke parameters het meest kritisch zijn;
- **technologische beslissingen onderbouwt** — met kwantitatieve argumenten in plaats van vuistregels.

De rode draad is het **systeemdenken** uit Hoofdstuk 1: brouwen als een gekoppeld biotechnologisch systeem waarin inputvariaties doorwerken naar productuitkomsten.

---

## Mapstructuur

```
BHBT-Python-oefeningen/
├── notebooks/
│   ├── 01_Deel_I_Context/
│   │   └── H1_Belgische_brouwerijsector/
│   ├── 02_Deel_II_Grondstoffen/
│   │   ├── H2_Water/          ← 6 notebooks
│   │   ├── H3_Mout/
│   │   ├── H4_Hop/
│   │   └── H5_Gist/
│   ├── 03_Deel_III_Wortproductie/
│   │   ├── H6_Maischen_Filtratie/
│   │   └── H7_Koken_Koelen/
│   └── 04_Deel_IV_Procescontrole/
│       └── H8_Procescontrole_Schaal/
├── data/
├── docs/
├── LICENSE
└── README.md
```

---

## Vereisten

| Wat | Details |
|-----|---------|
| **Omgeving** | [Google Colab](https://colab.research.google.com/) (gratis, geen installatie) |
| **Account** | Google-account |
| **Uitvoering** | Cellen sequentieel uitvoeren (Run all) |
| **Lokaal draaien** | Optioneel: `pip install numpy matplotlib ipywidgets` + Jupyter |

---

## Bijdragen

Suggesties, verbeteringen en nieuwe oefeningen zijn welkom.
Open een [issue](https://github.com/ronniewillaert/BHBT-Python-oefeningen/issues) of maak een pull request.

---

## Licentie

Dit project valt onder de [MIT-licentie](LICENSE).




# Belgisch Brouwerijhandboek — Python Notebooks

Deze repository bevat interactieve Python-notebooks die aansluiten bij het **Belgisch Brouwerijhandboek**.

De notebooks volgen dezelfde structuur als het handboek en bouwen van:

**Conceptueel systeemdenken → Kwantitatieve modellering → Procesanalyse → Technologische optimalisatie**

Elke notebook implementeert een expliciet procesmodel waarin variabelen, aannames en interacties zichtbaar worden gemaakt.

---

# 🚀 Quick Start

1. Open een notebook via de **Google Colab-link**.
2. Log in met je Google-account.
3. Kies *Runtime → Run all*.
4. Experimenteer met parameters en analyseer de impact op procesuitkomsten.

Aanbevolen startpunt:
- **Deel I — Hoofdstuk 1: IPO-model van het brouwproces**

---

# Deel I — Context en systeemdenken

## Hoofdstuk 1 — Schematisch IPO-model van het brouwproces

Het brouwproces wordt gemodelleerd als een gekoppeld input–proces–output-systeem.  
Variatie in één inputparameter wordt geanalyseerd op zijn impact op **OG**, **FG** en **ABV**.

- **[Open in Google Colab — IPO-model](https://colab.research.google.com/github/ronniewillaert/BHBT-Python-oefeningen/blob/main/notebooks/01_Deel_I_Context/H1_Belgische_brouwerijsector/BHBT_H1_Oefening1_Schematisch_IPO_model.ipynb)**

---

# Deel II — Grondstoffen

## Hoofdstuk 2 — Water

De onderstaande notebooks vormen samen één geïntegreerde waterdesign-workflow:  
van fundamentele zuur–base-chemie tot volledig geautomatiseerde stijlgebaseerde optimalisatie.

1. **[Mash pH model (Henderson–Hasselbalch)](https://colab.research.google.com/github/ronniewillaert/BHBT-Python-oefeningen/blob/main/notebooks/02_Deel_II_Grondstoffen/H2_Water/01_Mash_pH_model_HH.ipynb)**  
2. **[Waterprofiel & Residual Alkalinity (RA)](https://colab.research.google.com/github/ronniewillaert/BHBT-Python-oefeningen/blob/main/notebooks/02_Deel_II_Grondstoffen/H2_Water/02_Waterprofiel_RA.ipynb)**  
3. **[Waterblending & doelprofieloptimalisatie](https://colab.research.google.com/github/ronniewillaert/BHBT-Python-oefeningen/blob/main/notebooks/02_Deel_II_Grondstoffen/H2_Water/03_Water_blending_optimizer.ipynb)**  
4. **[Zouttoevoegingen & stijlgebaseerde waterdesign](https://colab.research.google.com/github/ronniewillaert/BHBT-Python-oefeningen/blob/main/notebooks/02_Deel_II_Grondstoffen/H2_Water/04_Zouttoevoegingen_stijl_waterdesign.ipynb)**  
5. **[Zout + zuur → pH-doel in de maisch](https://colab.research.google.com/github/ronniewillaert/BHBT-Python-oefeningen/blob/main/notebooks/02_Deel_II_Grondstoffen/H2_Water/05_Zout_zuur_naar_mash_pH_doel.ipynb)**  
6. **[Capstone — Volledig automatisch waterdesign (Tripel / IPA / Stout)](https://colab.research.google.com/github/ronniewillaert/BHBT-Python-oefeningen/blob/main/notebooks/02_Deel_II_Grondstoffen/H2_Water/06_Capstone_AutoWaterDesign_Tripel_IPA_Stout.ipynb)**  

Deze workflow weerspiegelt industriële realiteit:  
waterdesign is geen losse berekening, maar een gekoppeld chemisch systeem waarin ionensamenstelling, alkaliniteit en pH elkaar beïnvloeden.

---

# Didactische filosofie

Deze repository bevat geen losse scripts.  
Elke notebook:

- maakt variabiliteit expliciet  
- maakt aannames zichtbaar  
- analyseert gevoeligheid  
- ondersteunt technologische beslissingen  

**Theorie → Model → Simulatie → Procesinzicht**

---

# Gebruik

De notebooks draaien in **Google Colab** en vereisen geen lokale installatie.

Voor optimale werking:
- Gebruik een Google-account  
- Open via de Colab-link  
- Run alle cellen in volgorde  

---

# Licentie

Zie LICENSE-bestand.
