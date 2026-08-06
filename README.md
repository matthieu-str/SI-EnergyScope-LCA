# SI-EnergyScope-Prospective-Regionalized-LCA

Supplementary interactive dashboard for the paper:

> Souttre M., Chuat A., Schnidrig J., Fischer L., Maj J., Majeau-Bettez G., Maréchal F., Margni M. (2026). Regionalized and prospective life-cycle assessment in energy system models: evaluating the effects on energy planning and environmental performance. Submitted to *Renewable and Sustainable Energy Reviews*.

## 🌐 Dashboard

> **[https://matthieu-str.github.io/SI-EnergyScope-Prospective-Regionalized-LCA/](https://matthieu-str.github.io/SI-EnergyScope-Prospective-Regionalized-LCA/)**

The dashboard allows interactive exploration of the paper's results across four views:

- **Comparative view** — Energy system configurations and life-cycle environmental impacts across all prospective-regionalization levels, with sector and technology contribution breakdowns.
- **Per-level view** — Energy and carbon flow Sankey diagrams for each individual modeling level and SSP scenario.
- **Sensitivity analysis** — Energy system configurations as a function of industrial carbon capture availability (7–36 Mt CO₂/yr).
- **About** — Description of the modeling levels, environmental impact categories, and tools used.

## Modeling levels

Results are produced for six levels of prospective and regionalization assumptions, combining IAM background projections (IMAGE model, SSP5-H and SSP2-L scenarios) with up to three layers of LCA regionalization (spatialization, foreground regionalization, background regionalization via `regioinvent`).

## Tools

[`mescal`](https://mescal.readthedocs.io) · [`premise`](https://github.com/polca/premise) · [`regioinvent`](https://github.com/CIRAIG/regioinvent) · [`regiopremise`](https://github.com/matthieu-str/regiopremise) · [EnergyScope-Québec](https://github.com/CIRAIG/EnergyScope-Quebec) · [ecoinvent 3.10.1](https://support.ecoinvent.org/ecoinvent-version-3.10.1) · [IMPACT World+ v2.1](https://zenodo.org/records/14041258)

## Data and code availability

The code and data used to produce the results are available in the `lca` project of the EnergyScope-Quebec repository:
> [https://github.com/CIRAIG/EnergyScope-Quebec/tree/main/projects/lca/02_Regionalization](https://github.com/CIRAIG/EnergyScope-Quebec/tree/main/projects/lca/02_Regionalization)