# LOPEZ
Large · Omics · Pathway · Enrichment · Z-score

LOPEZ is a fully self-contained, single-file (.html), client-side web application for interactive multi-omics pathway analysis. It requires no server, no installation, and no API keys. All computation runs in the browser using vanilla JavaScript. 

The application supports Over-Representation Analysis (ORA) via hypergeometric, Fisher's exact, and binomial tests; Gene Set Enrichment Analysis (GSEA) via a weighted Kolmogorov–Smirnov statistic with permutation-based p-values; network propagation via a Random Walk with Restart (RWR) algorithm; and comparative analysis of two independent gene lists across 13 interactive visualization modes. 

Pathway databases are loaded at runtime from open APIs (KEGG, Reactome, WikiPathways, Enrichr) with curated fallback sets bundled in the file. The application renders all figures as inline SVG, exportable as CSV, SVG, or PDF. This protocol describes the complete architecture, statistical methods, data flow, and extension guidelines for developers. 
