Steps: [Convert the steps into workflow diagram (include tools for each step) and update README.md]
Below is a list of steps we intend to take to meet our set objectives

1. Sequence selection 
In this study protein sequences of the beta-N-acetylglucosaminyltransferase TarS were obtained from the NCBI. The protein sequence downloaded were only those that were expressed in Staphylococcus aureus. 250 FASTA format of the sequneces were randomly selected from NCBI and downloaded

2. Epitope Prediction 
To determine the immunogenicity of the proteins before any intial analysis
i)MHC class I
The (Immune Epitope Database and Analysis Resource ) IEDB will be used for the intial determination of intial epitopes. MHC I will fisrt be determined using the NetMHCpan model an Artificial neural network trained on on a set of quantitative peptide-MHC class I binding metrics, the link is as follows [http://tools.iedb.org/mhci/]. The input will be the downloaded protein FASTA sequences, the predictions will be made based on the HLA allele selected. The output file is selected and the files are submitted for prediction.
_For epitopes expected to bind exceptionally well to a given HLA allele, the value shown in the “score” column will be closer to 1. The score is inversely related to the percentile rank, which will have a lower value for epitopes expected to bind more effectively to MHC class I_
** For the HLA class I binding affinty is directly affilited to immunogencity.

ii) MHC class II
