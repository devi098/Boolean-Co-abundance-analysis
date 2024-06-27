## Project Title: Thresholded Boolean Co-Abundance (ESABO) analysis for continuous-valued datasets
## Project Category/Topic:  Data Science

## Abstract:
Communities proliferate in the world of microorganisms and constitute essential components of the environments they inhabit. It is of the utmost importance to comprehend these societies and the complex relationships that link them. Using the well-known Entropy shifts of Abundance Vectors under Boolean Operations(ESABO) approach, our effort goes deep into the investigation of these interactions. To reveal the nature of interactions between microorganisms, this approach uses entropy fluctuations in data on microbial abundance. Our main aim behind the project lies in the generalisation of the ESABO method to account for continuous valued datasets using thresholding of the dataset. We are able to determine the best thresholding settings for various subsets of a microbiome dataset(959 species) owing to this adaption and also examine the effect of thresholding on various data compositionality. Furthermore, we extend the ESABO approach to a novel dataset of abundance of 354 plant species, in order to discover its viability in extracting interactions from ecological data. In order to shed insight on the complex web of interactions between these microbial and ecological communities, we also analyse the network topologies created by the ESABO technique. We get a better understanding of microbial and ecological dynamics through our thorough investigation, opening the door for useful applications and insights in these areas. Our study shows that adapting the abundance threshold opens a way for a better understanding of microbial and ecological dynamics, opening the door for useful applications and insights in these areas.

## Motivation:
Our project will involve the ESABO approach and modified ESABO approach in a systematic manner. Both the approaches input binary abundance vectors for co-abundance analysis. Below are the motivations of the current study:
1) Extending the ESABO approach to continuous valued abundance datasets. The current ESABO approach assumes a threshold of 1(i.e, absence-0, presence-1). We are interested in investigating whether this is the optimal threshold for the data. This investigation further motivates us to binarize the data using an optimal threshold value to attain maximum information from the data. As a result, we are able to capture the threshold which can lead to larger number of links in the data.
2) The ESABO approach with the analytical formula has been stated to be more computationally efficient compared to the original ESABO in. We are interested in investigating this to a specific case scenario and comparing between the methods to find the best one for application in our project.
3) Thirdly, we apply the ESABO approach to a different scenario of application in ecological framework by applying it to an abundance data of the plants. In this context, we aim to uncover the valuable the insights that can inform ecological research and conservation efforts.
4) We are also interested in analysing the complex networks attained as a result of the ESABO approaches. The analysis of these inferred networks help in its evaluation through network complexity measures and also comprehends whether the optimal threshold value can actually result in inference of denser networks in the data.

## Methodology:
The research has been broadly divided into two subsections where we will looking extensively into two different datasets of interest: 
1) microbiome dataset, and,
2) plant species abundance dataset.

The study initiates with a comparison of the original and modified ESABO approach in order to adopt the best approach as the primary method for our investigation. It proceeds with the thresholding of different subsets of the microbiome data and analysis of the research questions on the same.The application of ESABO approach is extended to the plant abundance dataset in the later part of the study.

## Instructions: 
There are three files/folders on the repository for the project.
1) **Dissertation_CODEFINAL.ipynb** - The python file which contains the entire code for the project.
2) **Data** - Folder containing datasets used in the project, namely **taxonomic_profiles.xlsx(Microbial species abundance dataset)** and **plant_species.xlsx(Plant species abundance dataset)**
3) **Dissertation_documentation** - Folder containing all necessary files for the project:
   1) Project Proposal
   2) Project Demonstration
   3) Chandran_2430977 - Final Report

## Additional Instructions: 
1) The code must be run on a python 3 environment,
2) GPU access would speed up the computations and is highly recommended.
