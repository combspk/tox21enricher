<h1>Tox21 Enricher</h1>
Tox21 Enricher is a web application that is still currently under development. It performs PubChem enrichment analysis on a set or sets of chemicals included in the the Tox21 chemical dataset, and it is being devloped in collaboration with NIEHS as part of their suite of Tox21-related tools.

<h2>Process</h2>
Chemicals are specified directly via their corresponding CASRN or indirectly with a SMILE/InChI string upon which a substructure search is executed. Once chemicals containing the given chemical string(s) are identified, CASRNs are used and enrichment proceeds as if the system was given CASRN input originally. Enrichment is then performed on the CASRNs.

After performing enrichment, the results are displayed (heatmap images per set, .gct, .xls, .txt files, cluster and chart full heatmaps) along with an option to view the cluster and chart full heatmaps visualized as networks. In the networks displayed, two nodes with a connecting edge indicate two annotations that have a statistically significant connection.

<h2>Development Tools</h2>
Tools used in the development of the Tox21 Enricher:

<br/>Plumber
<br/>PostgreSQL
<br/>Python
<br/>RDKit
<br/>R
<br/>Shiny
