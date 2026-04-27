## Pathway database documentation
 
An ongoing reference list of biological pathway databases used in molecular biology and genetics research, including mSigDB databases and others. This resource is intended to provide information on the selection, comparison, and usage of pathway databases for various analyses.

## What's in this repo

```
pathwaydb-docs/
├── README.md            
├── comparison-table.md     ← comparison table across all current documented databases
├── databases/              ← extended notes per database
│   ├── reactome.md
│   ├── kegg.md
│   ├── wikipathways.md
│   └── ...
└── methods/                ← notes on computational/footprint-based approaches (not created)
    ├── gsea-based.md
    └── network-based.md
```
 
## Databases covered
 
| Database | Type | Status |
|---|---|---|
| Reactome | Manual curation, reaction-level | 🔲 In progress |
| KEGG | Mixed curation, pathway maps | 🔲 In progress |
| WikiPathways | Community-curated | 🔲 In progress |
| GO Biological Process | Ontology-based | 🔲 In progress |
| MSigDB | Curated gene set collections | 🔲 In progress |
| SIGNOR | Signaling, manual curation | 🔲 Not started |
| PharmGKB | Pharmacogenomics | 🔲 Not started |
| NCI-PID | Signaling (largely in Reactome now) | 🔲 Not started |
| PROGENy | Footprint-based (computational) | 🔲 Not started |
| DoRothEA | TF regulon-based (computational) | 🔲 Not started |

 
## Key references
 
- Reactome: Milacic et al. (2024) *Nucleic Acids Research* — [doi:10.1093/nar/gkad1025](https://doi.org/10.1093/nar/gkad1025)
- KEGG: Kanehisa et al. (2023) *Nucleic Acids Research* — [doi:10.1093/nar/gkac963](https://doi.org/10.1093/nar/gkac963)
- WikiPathways: Martens et al. (2021) *Nucleic Acids Research* — [doi:10.1093/nar/gkaa1024](https://doi.org/10.1093/nar/gkaa1024)
- MSigDB / GSEA: Liberzon et al. (2015) *Cell Systems* — [doi:10.1016/j.cels.2015.12.004](https://doi.org/10.1016/j.cels.2015.12.004)
- PROGENy: Schubert et al. (2018) *Nature Communications* — [doi:10.1038/s41467-017-02391-6](https://doi.org/10.1038/s41467-017-02391-6)
- DoRothEA: Garcia-Alonso et al. (2019) *Genome Research* — [doi:10.1101/gr.240663.118](https://doi.org/10.1101/gr.240663.118)
---
 
*Maintained by: <!-- lab name -->*  
*Started: <!-- date -->*
