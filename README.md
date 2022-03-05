# Interactome
Comparison of iPSC -> neuron differentiation using multiple plattforms

Definition of enhancers: 
- non-coding RNA
- Enhancer DHS mark based on Encodev2
- not overlapping +/- 500bp of TSS

Selection of enhancer-promoter pairs based on Cicero 
- co-accessibility > 0.3, if distance of pairs are > 250kbp apart coaccessibility > 0.1 
- select pairs which are cell type specific (enhancer & promoter show FC > 0.25) 


Additional proof for enhancer-promoter pairing
- select genomic sequence and compare percentage of enhancer promoter sequence overlap compared to others 
- check GO/GSEA of protein coding genes from FC>0.25 vs. non-cell type specific protein-coding genes 
