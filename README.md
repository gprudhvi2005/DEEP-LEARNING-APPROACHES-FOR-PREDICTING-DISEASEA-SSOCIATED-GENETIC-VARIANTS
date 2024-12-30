# Predicting the Pathogenicity of Genetic Variants  

Predicting the pathogenicity of genetic variants is a critical task in healthcare, enabling early identification of diseases and facilitating personalized treatment plans. This research explores the use of deep learning models to classify genetic variants as "Pathogenic" or "Benign."  

## Overview  
This project implements and evaluates two deep learning architectures:  

1. **Convolutional Neural Networks (CNNs)**:  
   - Leverages spatial relationships between genetic features.  
   - Utilizes embedding, convolutional, pooling, and fully connected layers to detect patterns indicative of pathogenicity.  

2. **Fully Connected Neural Networks (FCNNs)**:  
   - Processes structured data linearly without spatial analysis.  
   - Uses dense layers to associate features with classification outcomes efficiently.  

## Dataset  
The dataset used is a **variant summary dataset**, primarily sourced from **ClinVar (NCBI)**, which compiles information on the clinical significance of genetic variants.  

- Dataset Source: [ClinVar Variant Summary](https://ftp.ncbi.nlm.nih.gov/pub/clinvar/tab_delimited/)  
