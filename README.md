# IDynoMiCS Exploration and Demo 
This repository explores **IDynoMiCS** indvidual-based modeling software for modeling microbial colonies/biofilms. The protocol file used was **bacillis.xml** provided by the IDynoMiCS github page as a test simulation. It includes a Python script to parse XML outputs and summarize agent counts by timestep and a Jupyter notebook to convert per-timestep SVG snapshots into an animated GIF for quick inspection. The goal is to evaluate iDynoMiCS output handling as a stepping stone toward whole-cell / Vivarium workflow for modeling biofilm formation in _E.coli_.

---

## Repository Content

- `Idynomics_SVG.ipynb` — interactive notebook for parsing XML, plotting counts, and previewing SVGs as images/animations.
- `parsing_idynomics.py` — script version of the parsing/visualization workflow.
- `second_agents_animation.gif` — example animation rendered from iDynoMiCS SVG frames (download and view in chrome)
- `cell_counts.png` — example time-series of agent counts.

**Platform Notes:** iDynoMiCS is a Java-based platform that uses XML for inputs and outputs (conditions, species, positions, etc.), which makes parsing necessary to view any results/output. 

---

