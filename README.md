# VirtualChem Labs

An interactive web-based chemistry platform with five virtual labs. Built as a single-file-per-lab project with no frameworks or build tools — just HTML, CSS, and JavaScript.

Live site: [virtualchemlabs.org](https://virtualchemlabs.org)

---

## Labs

### Titration Lab
Simulate acid-base, redox, complexometric, precipitation, and iodometric titrations. Includes a virtual burette, live pH curve plotting, and exam mode with grading.

### Organic Qualitative Analysis
Identify 100+ unknown organic compounds using functional group tests (Lucas, Tollens, Fehling, iodoform, 2,4-DNP, etc.), solubility profiling, and Lassaigne fusion. Supports 6-compound exam sets.

### Inorganic Qualitative Analysis
Systematically identify cations and anions using classical group separation (Groups I–V), confirmatory reagents, flame tests, and centrifuge mechanics. Supports 10-ion exam sets with unknown mixtures.

### Electrochemistry
Build galvanic and electrolytic cells with 22 half-reactions. Applies the Nernst equation (temperature-dependent), Faraday electrolysis calculations, and concentration cell simulations. Includes exam mode.

### Chemical Formula Finder
Search chemical compounds by element combination, name, or CAS number. Integrates with the PubChem API to retrieve compound properties, molecular weights, and structures.

---

## Structure

```
index.html          — landing page
labs/
  titration.html
  organic.html
  inorganic.html
  electrochem.html
  formula.html
  shared.css        — shared design tokens and nav styles
```

---

Built by **Murad Khalilzade**
