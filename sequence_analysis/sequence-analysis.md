# Sequence Analysis

Get started with sequence analysis, alignment and phylogenetics.

---

## Sequence Visualization and Search

* **BLAST (NCBI)** – Suite for sequence similarity searches. Choose the algorithm based on query and database:  
  * `blastn` — nucleotide → nucleotide  
  * `blastp` — protein → protein  
  * `tblastn` — protein → translated nucleotide database  
  * `blastx` — translated nucleotide → protein database  
  * Web and standalone executables available.  
  * [BLAST interface & docs](https://blast.ncbi.nlm.nih.gov/Blast.cgi)

* **GeneRunner** – Sequence viewer/editor. Can translate DNA → protein (ensure correct reading frame). *Windows-only; installers often hosted on software repositories.*  
  * [Download / info (Softpedia)](https://www.softpedia.com/get/Science-CAD/Gene-Runner.shtml)

* **Jalview** – Alignment viewer and editor highlighting amino-acid conservation and annotation/colour schemes. Best used *after* generating alignments with a dedicated aligner.  
  * [Website & docs](https://www.jalview.org/)

---

## Sequence Alignment

* **MAFFT** – Multiple-sequence aligner with several algorithms (choose method based on dataset size and accuracy needs). Works for nucleotide and protein sequences.  
  * [Website & download](https://mafft.cbrc.jp/alignment/software/)

* **trimAl** – Automated trimming of poorly aligned or gappy regions; recommended after alignment before downstream analysis.  
  * [Docs / download](https://trimal.cgenomics.org/)  
  * [Alternative docs](https://trimal.readthedocs.io/)

---

## Phylogenetics & Visualization

* **iTOL (Interactive Tree Of Life)** – Web-based tree visualization/annotation tool; great for polished phylogenetic figures.  
  * [Website & docs](https://itol.embl.de/)

* **MEGA X** – Desktop software for constructing phylogenies (various inference methods), model testing, and basic sequence analyses. GUI + command-line options.  
  * [Website & downloads](https://www.megasoftware.net/)

---

## Quick Tips

* **Trim before tree-building** – remove low-quality or ambiguously aligned regions (trimAl) to avoid phylogenetic artefacts.  
* **Pick the right BLAST algorithm** – ensure input and target DB match (BLASTn/blastp/tblastn/blastx).  
* **Align before visualizing** – Jalview expects aligned sequences; use MAFFT (or another aligner) first.
