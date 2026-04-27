# pathwaydb-docs
Documentation on the several pathway databases used in molecular biology and genetics research, including those in mSigDB, as well as additional databases beyond it.

## Pathway database documentation
 
A living reference for evaluating biological pathway databases and enrichment methods. The goal is to document each resource consistently enough to make informed decisions about which database(s) to use for a given analysis.
 
## What's in this repo
 
```
pathway-db-docs/
├── README.md               ← you are here
├── comparison-table.md     ← master comparison table across all databases
├── databases/              ← extended notes per database (add as needed)
│   ├── reactome.md
│   ├── kegg.md
│   ├── wikipathways.md
│   └── ...
└── methods/                ← notes on computational/footprint-based approaches
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
 
## How to contribute
 
1. Pick a database marked **Not started** or **In progress**
2. Fill in the relevant rows in `comparison-table.md`
3. Optionally add a `databases/<name>.md` file for extended notes
4. Cite your sources — prefer the database's own NAR or primary paper, plus the version/release you checked
5. Add your name and date to the row you filled in via the **Notes** column
When in doubt, leave a cell blank or mark it `?` rather than guessing. Unknown is more useful than wrong.
 
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
