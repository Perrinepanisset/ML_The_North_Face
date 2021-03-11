## MACHINE LEARNING - THE NORTH FACE E-COMMERCE

### GOALS
- Identify groups of products that have similar descriptions.
- Use the groups of similar products to build a simple recommender system algorithm.
- Use topic modeling algorithms to automatically assess the latent topics present in the item descriptions.

### USAGE

### 0.Preprocessing-The_North_Face_Ecommerce.ipynb
Understanding and cleaning dataset. Preprocessing text for the creation of a TF-IDF Matrix and the visualization in a Word Cloud.

- INPUT FILE : sample-data-ecommerce.csv

- OUTPUT FILES :
  - TF-IDF_Matrix.csv
  - northface_wordcloud.png
  
### 1.Part1-Group_Products-The_North_Face_Ecommerce.ipynb
Grouping products with similar descriptions.

- INPUT FILES : 
    - TF-IDF_Matrix.csv
    - sample-data-ecommerce.csv
    - Cleaned_descriptions.csv

- OUTPUT FILE :
    - Desc_clusters.csv

### 2.Part2-Recommender_system-The_North_Face_Ecommerce.ipynb
Developping a function that will recommand 5 other products to a client looking for a product in particular

- INPUT FILE : Desc_clusters.csv

### 3.Part3-Topic_Modeling-The_North_Face_Ecommerce.ipynb
Creating topics that will best fit product descriptions.

- INPUT FILE : Cleaned_descriptions.csv
