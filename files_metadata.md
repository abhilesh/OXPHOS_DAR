- ## Results  
	- ### Subsampling analysis for mtDNA DARs  
		- [`DAR_subsampling_analysis_mtDNA.csv`](https://github.com/abhilesh/OXPHOS_DAR/blob/main/results/DAR_subsampling_analysis_mtDNA.csv)  
		    
		  Column descriptions -  
		  `Num_species` = Number of species in the replicate *(50 - 1050)*  
		  `Replicate_number` =  Replicate id *(0 - 99)*  
		  `Num_total_DAR` = Total number of DARs in the analysis *(289)*  
		  `Num_cDAR` = Number of c-DARs in the current replicate  
		  `Num_uDAR` = Number of u-DARs in the current replicate  
	- ### Effect of DAR mutation on proteins  
		- [`DAR_exchangeability_values.csv`](https://github.com/abhilesh/OXPHOS_DAR/blob/main/results/DAR_Exchangeability_values.csv)  
		    
		  Column descriptions -  
		  `ann_id` = Annotation id as per MITOMAP or HGMD  
		  `ann_locus` = Gene where the DAR is located  
		  `ann_genome`= Genome where the DAR is located  
		  `ann_aa_change` = Amino acid change for DAR  
		  `ann_DAR_class` = Classification of DAR *[cDAR/uDAR]*  
		  `ann_Ex_val` = Exchangeability value for the amino acid change  
	- ### Variability in the structural neighborhood of DARs  
		- [`DAR_neighborhood_shannon_entropy.csv`](https://github.com/abhilesh/OXPHOS_DAR/blob/main/results/DAR_neighborhood_shannon_entropy.csv)  
		    
		  Column descriptions -  
		  `ann_id` = Annotation id as per MITOMAP or HGMD  
		  `ann_genome` = Genome where the DAR is located  
		  `ann_DAR_class` = Classification of DAR *[cDAR/uDAR]*  
		  `ann_shannon_entropy`= Average Shannon's Entropy of residues within 5 Å of the DAR  
	- ### Covariation with the structural neighborhood  
		- **Observed Minus Expected Scores (OMES)**:  
		  [`DAR_neighborhood_OMES_values.csv`](https://github.com/abhilesh/OXPHOS_DAR/blob/main/results/DAR_neighborhood_OMES_values.csv)  
		    
		  **Joint Entropies**:  
		  [`DAR_neighborhood_joint_entropies.csv`](https://github.com/abhilesh/OXPHOS_DAR/blob/main/results/DAR_neighborhood_joint_entropies.csv)  
		    
		  **Mutual Information (MI)**  
		  [`DAR_neighborhood_MI_values.csv`](https://github.com/abhilesh/OXPHOS_DAR/blob/main/results/DAR_neighborhood_MI_values.csv)  
		    
		  **Mutual Information (MI_p)**  
		  [`DAR_neighborhood_MI_p_values.csv`](https://github.com/abhilesh/OXPHOS_DAR/blob/main/results/DAR_neighborhood_MI_p_values.csv)  
		    
		  Column descriptions -   
		  `ann_id`= Annotation id as per MITOMAP or HGMD  
		  `ann_DAR_class` = Classification of DAR *[cDAR/uDAR]*  
		  `ann_genome`= Genome where the DAR is located  
		  `ann_gene` = Gene where the DAR is located  
		  `ann_resnum` = Residue number for DAR  
		  `ann_restype` = Amino acid type for DAR  
		  `neighbor_gene` = Gene where the structural neighbor (< 5 Å away) is located  
		  `neighbor_resnum` = Residue number for the structural neighbor  
		  `neighbor_restype` = Amino acid type for the structural neighbor  
		  `OMES_value` = OMES value between DAR and structural neighbor  
		  `joint_entropy` = Joint entropy value between DAR and structural neighbor  
		  `MI_value` = MI value between DAR and structural neighbor  
		  `MI_p_value` = MI_p value between DAR and structural neighbor  
	- ### Number of independent origins for each annotation  
		- `independent_origins_{genome}.csv`  
		    
		  Column descriptions -  
		  `ann_id`= Annotation id as per MITOMAP or HGMD  
		  `ann_gene` = Gene where the DAR is located  
		  `ann_complex` = OXPHOS complex where the DAR is located  
		  `ann_aa_coord` = Amino acid coordinate for the DAR  
		  `ann_wt_aa`= Wild-type (non-disease causing) amino acid for DAR  
		  `ann_mut_aa` = Mutant (disease causing) amino acid for DAR  
		  `num_cDAR_species` = Number of species in the alignment with wt_aa  
		  `indep_origins` = Number of independent origins for the DAR  
		  `num_align_species` = Number of species in the alignment for ann_gene  
		  `ann_interface` = Genomic interface where the DAR is located