# 🏙️ Smart City Ontology

A group project that presents a formal OWL 2 ontology conceptualising the interconnected subsystems of a Smart City across four primary domains: Smart Transportation, Smart Energy Grid, Smart Water Management, and Smart Healthcare. The ontology was implemented in Protégé 5.5.0 and validated through SPARQL queries against 32 competency questions.

The ontology consists of:

- **68 classes** organised into a hierarchy of depth 3
- **38 object properties** encoding inter-subsystem relationships
- **85 named individuals** representing real-world instances
- **186 formal axioms** expressed in both First-Order Logic (FOL) and Description Logic (DL)

---

## 🗂️ Repository Structure

```
.
├── SmartCityOntology.owl       # Complete OWL 2 ontology file in RDF/XML format
├── Smart_City_Project_Review.pdf   # Full project report including axioms, SPARQL queries, and results
└── README.md
```

---

## 📋 Project Overview

The ontology formalises four primary Smart City domains, all underpinned by a shared IoT infrastructure backbone:

- **Smart Transportation** — traffic management, connected vehicles, public transit, micro-mobility, and parking systems
- **Smart Energy Grid** — advanced metering infrastructure, distributed energy resources, demand response, and virtual power plants
- **Smart Water Management** — water treatment, distribution networks, leak detection, wastewater treatment, and stormwater management
- **Smart Healthcare** — electronic health records, telemedicine, wearable sensors, remote patient monitoring, and ambulance dispatch

Cross-domain integration is modelled through shared infrastructure classes including IoT Platform, Edge Computing Node, Cloud Platform, 5G Network, Cybersecurity System, Digital Twin, and Urban Sensor Network.

---

## 🛠️ Requirements

To open and work with the ontology you will need:

| Tool | Version | Purpose |
|------|---------|---------|
| [Protégé](https://protege.stanford.edu/) | 5.5.0 | Ontology editor |
| HermiT Reasoner | 1.4.3 | OWL reasoning and consistency checking |
| OWLViz Plugin | — | Class hierarchy visualisation |

Protégé is free and available for Windows, macOS, and Linux. HermiT and OWLViz are bundled with Protégé by default.

---

## 🚀 How to Open the Ontology

### Option 1 — Open in Protégé (Recommended)

1. Download and install [Protégé 5.5.0](https://protege.stanford.edu/products.php).
2. Clone or download this repository.
3. Open Protégé and go to **File → Open**.
4. Select `SmartCityOntology.owl`.
5. To run the reasoner, go to **Reasoner → HermiT** and click **Start Reasoner**.
6. To visualise the class hierarchy, open the **OWLViz** tab.

### Option 2 — Inspect the OWL File Directly

The ontology uses OWL 2 with RDF/XML serialisation and can be opened in any text editor or RDF-aware tool. The file is human-readable and all classes, properties, and axioms are labelled.

---

## 🔄 Ontology Summary

| Metric | Count |
|--------|-------|
| Classes | 68 |
| Object Properties | 38 |
| Named Individuals | 85 |
| Formal Axioms | 186 |
| Competency Questions Validated | 32 / 32 |

---

## 🔁 Validation

The HermiT 1.4.3 reasoner confirmed logical consistency — no unsatisfiable classes were detected. All 32 competency questions defined at the outset were successfully answered via SPARQL queries executed in Protégé's built-in query interface. Full query listings and results are included in the project report.

---

## 👥 Contributors

Tashmika Pillay · Vyasa Aiyer · Josh Goodwin · Jeryn Naidoo
