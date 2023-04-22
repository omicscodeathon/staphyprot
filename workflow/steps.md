Steps: [Convert the steps into workflow diagram (include tools for each step) and update README.md]

## Below is a list of steps we intend to take to meet our set objectives

1. Retrieval of sequences
Each of the 200 amino acid sequences of length 266 amino acids for Staphylococcal SEB were retrieved from the National Center for Biotechnology Information (NCBI) (NCBI, 2019) database with their respective accession numbers and saved in FASTA format.


2. Antigenicity testing
The antigenicity of the retrieved protein’s amino acid sequences was checked using Vaxijen v2.0 at a threshold value of 0.6 (VaxiJen, n.d.).
3. Allergenicity test
Each of the retrieved 200 sequences was checked for allergenic properties using AllerTop tool v2.0 server (Bioinformatics Tool for Allergenicity Prediction., n.d.). 
4.  HLA I & II Allele selection.
Ten HLA I alleles and ten HLA II alleles that occur more frequently in the general population were considered for T cell epitope prediction as accessed on 5th of July 2020 (HLA Allele Frequencies and Reference Sets with Maximal Population Coverage, n.d.)
5. Prediction of  Cytotoxic T lymphocytes (CTLs), helper T lymphocyte (HTL) and B-cell epitopes.
NetCTLpan 1.1 server(NetCTLpan 1.1 - DTU Health Tech - Bioinformatic Services, n.d.) was used with the default MHC I threshold value of 1 and  each putative SEB sequence epitopes were predicted. Only peptides with threshold values of 1 were taken into consideration for epitope mapping once the server distributed the potential epitopes together with their corresponding threshold scores. 
NetMHCIIpan V 4.0 (NetMHCIIpan 4.0 - DTU Health Tech - Bioinformatic Services, n.d.) was utilized for the identification of epitopes associated with MHC II. Epitopes that had strong affinities to the MHC II were considered for further analysis. The threshold for strong binding epitopes was set at 1 and weak binding epitopes threshold was set at 5.  The lower percentile rank scores showed a higher binding affinity for the MHC II receptor. These epitopes were selected for further analysis. 
Linear B-cell epitopes prediction for all the SEB sequences being investigated was performed using the BCPRED (BCEPRED Submission Page, n.d.) where the epitopes whose scores were between 2.0 - 2.5   with a length  >10 AA from the results were selected for further analysis.
6. Construction of Vaccine Primary structure
The final list of selected HTL’s, CTL’s and B-cells epitopes were coupled with adjuvants and linkers to construct the final multi-epitope vaccines. In this study two vaccines were constructed with different lengths. In both constructs CTL, HTL and B-cells epitopes were joined together using the AAY, GPGPG and KK linkers respectively. β-defensin and PADRE were used as adjuvants in the first vaccine construct with the EAAAK linker on the N-terminal of the vaccine and hexahistidine at the C-terminal . The first vaccine construct contained 5 CTL epitopes , 1 B-cell epitope and 2 HTL epitopes which were coupled with the linkers and two adjuvants.
The epitopes in this vaccine had a predicted antigenicity of  >1.0 from the VaxiJen Server. The end result was a vaccine with 167 aa.
The second vaccine construct contained β-defensin as the only adjuvant, 8 CTL epitopes, 2 B-cell epitopes and 5 HTL epitopes. The epitopes used in this construct had a predicted antigenicity of >0.4 from the VaxiJen Server, this resulted in a vaccine containing 258 aa. 
7. Assessment of Vaccine Primary Structure
For the assessment of the allergenicity of the vaccines the AllerTop V2.0 (Bioinformatics Tool for Allergenicity Prediction., n.d.) server was used, the antigenicity of the vaccine constructs was also assessed using the VaxiJen V 2.0 server(VaxiJen, n.d.). The toxicity of the vaccine constructs was predicted using the ToxinPred server  (Designing of Peptides for Deisred Toxicity a Module of ToxinPred, n.d.). The physicochemical properties of the constructs were evaluated using the ExPASy ProtParam server (ExPASy - ProtParam Tool, 2019). The properties tested from this server include : molecular weight, Theoretical PI (Protrusion Index), amino acid composition, Extinction coefficients, Estimated half-life, Instability index, Aliphatic index and Grand Average of Hydropathicity (GRAVY).(NPS@ : SOPMA Secondary Structure Prediction, n.d.)
8. Secondary and Tertiary Vaccine Construction and refinement 
The secondary structure of the multi-epitope vaccine construct was assessed using the Self Optimized Prediction technique with Alignment (SOPMA) server(NPS@ : SOPMA Secondary Structure Prediction, n.d.) server. This server  simplifies analysis of the protein and predicts the secondary structure of the protein(Olatunde et al., 2022). The tertiary structure of the protein was assessed using the Iterative Threading Assembly Refinement (I-TASSER)(I-TASSER Server for Protein Structure and Function Prediction, 2019) . This server is commonly used for protein structure prediction and it uses a vast number of cutting edge algorithms to make predictions of the structure and function of the protein(Olatunde et al., 2022).
