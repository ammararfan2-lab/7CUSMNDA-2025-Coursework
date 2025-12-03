# 7CUSMNDA Coursework 
**Network Data Analysis**  

---

## 📘 Overview

This repository contains the complete coursework submission for the module **7CUSMNDA: Network Data Analysis** at King's College London. It covers both Part 1 (Wikidata Editor Networks) and Part 2 (Spatial Networks in Leeds), demonstrating advanced techniques in graph analysis, spatial analytics, provenance modeling, and graph embeddings.

---

## 📂 Repository Structure

```bash
7cusmnda-coursework/
│
├── part1_wikidata_networks/
│   ├── small_editor_network.ipynb
│   ├── medium_editor_network.ipynb
│   ├── large_editor_network.ipynb
│   └── epidemic_simulations.ipynb
│
├── part2_leeds_spatial/
│   ├── task_a_road_network.ipynb
│   ├── task_b_accident_analysis.ipynb
│   ├── task_c_voronoi_marathon.ipynb
│   └── task_d_provenance_embeddings.ipynb
│
└── README.md
```

## Coursework Breakdown

### Part 1 – Wikidata Editor Networks

#### Task A: Network Construction  
- Constructs editor interaction networks using **NetworkX** from Wikidata talk page logs.  
- Creates edges between users who comment on the same thread and page.  
- Generates separate networks for small, medium, and large datasets.

#### Task B: Network Metrics  
- Computes:
  - Degree distributions  
  - Clustering coefficients  
  - Centrality measures  
  - Small-world characteristics  
- Compares results to random graph baselines.

#### Task C: Epidemic Simulation  
- Simulates the spread of controversial behavior using the **SIR model**.  
- Identifies key individuals for intervention based on centrality and infection dynamics.  
- Uses **NDlib** for temporal visualization of infection curves.

#### Task D: Network Comparison  
- Compares structural differences between small, medium, and large networks.  
- Evaluates each graph’s position on the spectrum from regular → small-world → random.  
- Discusses how network topology affects propagation dynamics.

---

### Part 2 – Spatial Networks in Leeds

#### Task A: Road Network Construction  
- Extracts a **1 km²** road network in central Leeds using **OSMnx**.  
- Computes key statistics including:
  - Spatial density  
  - Edge density  
  - Circuitry  
  - Planarity  
  - Node and intersection counts

#### Task B: Accident Analysis  
- Analyzes **Leeds traffic accident data (2010–2019)** using spatial techniques:  
  - **Global AutoK** for hotspot detection  
  - **Moran’s I** for spatial autocorrelation  
  - Proximity metrics relative to the road network  
- Visualizes clusters and evaluates network-risk relationships.

#### Task C: Voronoi-Based Marathon Planning  
- Strategically selects 4 seed nodes across the Leeds road graph.  
- Constructs edge-based **Voronoi diagrams** to partition the city.  
- Generates valid **~42 km marathon loops** within Voronoi subgraphs using shortest path search.  
- Evaluates loop feasibility and cell fairness.

#### Task D: Provenance Modeling & Embeddings  
- Models event provenance using the **W3C PROV** standard with **PROV Python**.  
- Computes **PageRank** to measure activity importance.  
- Trains and evaluates **TransE**, **RotatE**, and **CompGCN** models using **PyKEEN**.  
- Discusses how embeddings can support future link prediction and semantic reasoning tasks.

---

## Technologies Used

- Python 3.10+  
- `NetworkX`, `OSMnx`, `GeoPandas`, `Spaghetti`, `esda`, `shapely`  
- `NDlib`, `matplotlib`, `folium`, `prov`, `pykeen`, `pandas`

---

## Report & Submission

A full coursework report (PDF) has been submitted in accordance with university guidelines.  
The Jupyter notebooks in this repository provide all analysis, results, and visualizations referenced in the report.

---

## Author

**Ammar Arfan**  
MSc Data Science  
King’s College London  
Module: *7CUSMNDA – Network Data Analysis*  
Supervisor: Dr. Albert Merono  
Email: [K24101560@kcl.ac.uk](mailto:K24101560@kcl.ac.uk)

---

## License

This repository is part of MSc-level coursework submitted to **King’s College London**. It is shared strictly for educational and professional portfolio purposes. Reproduction or reuse for academic credit is strictly prohibited.

