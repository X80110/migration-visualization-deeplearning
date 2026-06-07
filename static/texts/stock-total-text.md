#### Measure
Migrant stock data represent the estimated total number of international migrants born in their country of origin who reside in a destination country at a specific point in time.

#### Data & Methodology
Values are based on migration estimates generated using a deep learning model proposed by [Gaskin and Abel (2025)](https://www.nature.com/articles/s41586-026-10611-7). The framework combines and reconciles multiple data sources, including [UN DESA migrant stocks](https://www.un.org/development/desa/pd/content/international-migrant-stock), bias-adjusted flow estimates derived from [Facebook data](https://www.pnas.org/doi/10.1073/pnas.2409418122), harmonised statistics from European countries via [QuantMig](https://www.quantmig.eu/), and official data from select nations. To improve estimation accuracy—particularly in data-poor countries with no prior migration data or official statistics—the neural network leverages a wide range of geographic, economic, cultural, and political covariates as predictive variables.

To compare these annual results with longer-term five-year migration flow estimates based on demographic accounting models, visit the original [Global Migration Flows Explorer](https://global-migration.iiasa.ac.at/).

Zenodo [Download](https://zenodo.org/records/15778301)  —  HuggingFace [Download](https://huggingface.co/datasets/ThGaskin/Migration_flows)

#### Reference
Gaskin, T., & Abel, G. J. (2026). [Deep learning four decades of human migration](https://www.nature.com/articles/s41586-026-10611-7). *Nature*. Advance online publication. [doi.org/10.1038/s41586-026-10611-7](https://doi.org/10.1038/s41586-026-10611-7)
