# Belgisch Brouwerijhandboek — Python Oefeningen

Deze repository bevat interactieve Python-notebooks die aansluiten bij het **Belgisch Brouwerijhandboek**.  
De notebooks volgen dezelfde structuur als het handboek en bouwen van **conceptueel systeemdenken** naar **kwantitatieve modellering**, **procesanalyse** en **technologische optimalisatie**.

Elke notebook implementeert een expliciet procesmodel waarin variabelen, aannames en interacties zichtbaar worden gemaakt.

---

## Deel I — Context en systeemdenken

### Hoofdstuk 1 — Belgische brouwerijsector en het brouwproces

Deze notebook vertaalt de concepten uit Hoofdstuk 1 naar een kwantitatief **input–proces–output-model** van het brouwproces.

### 1. Schematisch model van het brouwproces (input–proces–output)

<a href="https://colab.research.google.com/github/ronniewillaert/BHBT-Python-oefeningen/blob/main/notebooks/01_Deel_I_Context/H1_Belgische_brouwerijsector/BHBT_H1_Oefening1_Schematisch_IPO_model.ipynb" target="_blank" rel="noopener">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open in Colab"/>
</a>

In deze oefening wordt het brouwproces gemodelleerd als een keten van gekoppelde procesblokken.  
Variatie in één inputparameter wordt geanalyseerd op zijn impact op productparameters zoals **OG**, **FG** en **ABV**.  
De nadruk ligt op systeeminteractie, variabiliteit en procesgevoeligheid.

---

## Deel II — Grondstoffen

### Hoofdstuk 2 — Water

De onderstaande notebooks vormen samen één geïntegreerde **waterdesign-workflow**:  
van fundamentele zuur–base-chemie tot volledig geautomatiseerde stijlgebaseerde optimalisatie.

---

## Leerpad — Geïntegreerd waterdesign

Deze zes notebooks vormen één coherente ontwerpcyclus voor brouwwater.  
Ze bouwen conceptueel én computationeel op elkaar voort en weerspiegelen industriële realiteit:  
waterdesign is een gekoppeld chemisch systeem waarin ionensamenstelling, alkaliniteit en pH elkaar beïnvloeden.

### Aanbevolen volgorde

---

### 1. Mash pH model (Henderson–Hasselbalch)

<a href="https://colab.research.google.com/github/ronniewillaert/BHBT-Python-oefeningen/blob/main/notebooks/02_Deel_II_Grondstoffen/H2_Water/01_Mash_pH_model_HH.ipynb" target="_blank" rel="noopener">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open in Colab">
</a>

Begrijp hoe bufferwerking en zuurtoevoeging de maisch-pH beïnvloeden.

---

### 2. Waterprofiel & Residual Alkalinity (RA)

<a href="https://colab.research.google.com/github/ronniewillaert/BHBT-Python-oefeningen/blob/main/notebooks/02_Deel_II_Grondstoffen/H2_Water/02_Waterprofiel_RA.ipynb" target="_blank" rel="noopener">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open in Colab">
</a>

Analyseer een bestaand waterprofiel en evalueer de geschiktheid voor verschillende bierstijlen.

---

### 3. Waterblending & doelprofieloptimalisatie

<a href="https://colab.research.google.com/github/ronniewillaert/BHBT-Python-oefeningen/blob/main/notebooks/02_Deel_II_Grondstoffen/H2_Water/03_Water_blending_optimizer.ipynb" target="_blank" rel="noopener">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open in Colab">
</a>

Ontwerp mengstrategieën (bv. leidingwater + RO-water) om een doelprofiel te benaderen.

---

### 4. Zouttoevoegingen & stijlgebaseerde waterdesign

<a href="https://colab.research.google.com/github/ronniewillaert/BHBT-Python-oefeningen/blob/main/notebooks/02_Deel_II_Grondstoffen/H2_Water/04_Zouttoevoegingen_stijl_waterdesign.ipynb" target="_blank" rel="noopener">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open in Colab">
</a>

Corrigeer ionenverhoudingen gericht op smaakbalans (Cl⁻/SO₄²⁻), mondgevoel en vergistingsgedrag.

---

### 5. Zout + zuur → pH-doel in de maisch

<a href="https://colab.research.google.com/github/ronniewillaert/BHBT-Python-oefeningen/blob/main/notebooks/02_Deel_II_Grondstoffen/H2_Water/05_Zout_zuur_naar_mash_pH_doel.ipynb" target="_blank" rel="noopener">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open in Colab">
</a>

Integreer minerale correcties met zuurtoevoeging om het gewenste mash pH-bereik te bereiken.

---

### 6. Capstone — Volledig automatisch waterdesign (Tripel / IPA / Stout)

<a href="https://colab.research.google.com/github/ronniewillaert/BHBT-Python-oefeningen/blob/main/notebooks/02_Deel_II_Grondstoffen/H2_Water/06_Capstone_AutoWaterDesign_Tripel_IPA_Stout.ipynb" target="_blank" rel="noopener">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open in Colab">
</a>

Ontwerp een volledig waterprofiel — inclusief blending, zoutstrategie en pH-correctie — via geautomatiseerde optimalisatie.

---

## Didactische positionering

Deze repository bevat geen losse berekeningen.  
Elke notebook implementeert een expliciet model waarin aannames, interacties en gevoeligheden zichtbaar worden gemaakt.

**Theorie → Model → Simulatie → Procesinzicht.**
