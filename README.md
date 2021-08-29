# Generator-based-approach-to-analyze-mutations-in-genomic-datasets

Software requirements:

(1) Python3 (any version preferably >3.6), jupyter.
(2) Packages: numpy, pandas, scikit-learn, seaborn, glob, collections, pickle, matplotlib.
(3) The fasta files can be downloaded from GISAID. The GISAID acknowledgment files for each set of experiments done in the paper are provided on the github page and the supplementary material.


Code and data for Generator based approach to analyze mutations in genomic datasets

(1) The functions used to generate the state machine are provided in important_functions.ipynb, and the pickle file for any fasta file can be generated using create_pickle.ipynb.

(2) For Figure 2a,b,c,d,e,f, please use the Fig2_synthetic_data.ipynb.

(3) For Figure 2g,h, please use PCA_strains.ipynb. GISAID acknowledgement files for the samples used in Fig 2g are provided in the folder G_L_GR and for Fig 2h are provided in the folder UK_SA_Braz.

(4) For Figure 3, please use Intra_Strain_Evolution.ipynb. GISAID acknowledgement files for the samples used are provided in the folder continuous_evol.

(5) For Figure 4b,c,d,e and 6, please use Mutation_detection_time.ipynb, our 'State Machine' method, 'Needleman-Wunsch' method and 'Smith-Waterman' method are included in it. The specific data for Figure 6 are provided in folders 'Time_N_*'.

(6) For Figure 5, please use mutation_detection_region.ipynb. Metadata information for the samples used is provided in the folder samples_used_figure_5.

 
