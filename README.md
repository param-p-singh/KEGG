### Download genes and pathways from KEGG

* Download all genes in all pathways from KEGG: [getGenesInAllPathways.pl](getGenesInAllPathways.pl)

* Organism list can be seen at: http://www.genome.jp/kegg/rest/keggapi.html

* Check this for KEGG API: http://www.genome.jp/kegg/rest/keggapi.html

* Example files for Mouse, Zebrafish and Human are in [mouse_mmu](/mouse_mmu), [zebrafish_dre](zebrafish_dre) and [human_hsa](human_hsa)

* Output files:   
  **KEGG_Pathway-genes_Processed_\<organism\>.txt: All genes and pathways**   
  \<organism\>_all-genes.txt: List of all genes for an organism   
  \<organism\>_all-pathways: List of all pathways for an organism in KEGG   
  \<organism\>_kegg-info.txt: Information of the KEGG version stats etc for records   
  \<organism\>_pathway-to-gene-mapping.txt: Pathway and gene mappping              

* 20170316: Updated to adjust the gene name parsing a bit since in the new version file format has changed.  
  Also created new directories for the version Mar_2016 and Mar_2017
  
* 20170405: There was a bug is gene name so updated again, now the gene names are proper.