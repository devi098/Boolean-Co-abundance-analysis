## Project Title: Thresholded Boolean Co-Abundance (ESABO) analysis for continuous-valued datasets
## Project Category/Topic:  Data Science

## Motivation:
Our project will involve the ESABO approach and modified ESABO approach in a systematic manner. Both the approaches input binary abundance vectors for co-abundance analysis. Below are the
motivations of the current study:
• Extending the ESABO approach to continuous valued abundance datasets. The current ESABO approach assumes a threshold of 1(i.e, absence-0, presence-1). We are interested in investigating
whether this is the optimal threshold for the data. This investigation further motivates us to binarize the data using an optimal threshold value to attain maximum information from the data. As a result,
we are able to capture the threshold which can lead to larger number of links in the data.
• The ESABO approach with the analytical formula has been stated to be more computationally efficient compared to the original ESABO in. We are interested in investigating this to a
specific case scenario and comparing between the methods to find the best one for application in our project.
• Thirdly, we apply the ESABO approach to a different scenario of application in ecological framework by applying it to an abundance data of the plants. In this context, we aim to uncover the
valuable the insights that can inform ecological research and conservation efforts.
• We are also interested in analysing the complex networks attained as a result of the ESABO approaches. The analysis of these inferred networks help in its evaluation through network
complexity measures and also comprehends whether the optimal threshold value can actually result in inference of denser networks in the data.

## Methodology:
The research has been broadly divided into two subsections where we will looking extensively into two different datasets of interest: 
(i) microbiome dataset and, 
(ii) plant species abundance dataset. 
The study initiates with a comparison of the original and modified ESABO approach in order to adopt the best approach as the primary method for our investigation. It proceeds with the thresholding of different
subsets of the microbiome data and analysis of the research questions on the same.The application of ESABO approach is extended to the plant abundance dataset in the later part of the study.

## Instructions: 
There are three files on the repository for the project.
1) The python file under the name- 'Dissertation_finalcode.ipynb’
2) The first dataset for use under the name- ‘taxonomic_profiles.xlsx’
3) The second dataset for the project under the name – ‘plant_species.xlsx’
The code must be run on a python 3 environment and a GPU access would speed up the computations to some extent.
