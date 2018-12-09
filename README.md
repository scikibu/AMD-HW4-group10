# AMD-HW4-group10
![Screenshot](immobiliare.png)

Our team: Giulia Scikibu Maravalli, Katsiaryna Zavadskaya, Sara Cordaro.

The first part of the homework consists in scraping the website of [immobiliare.it](https://www.immobiliare.it/vendita-case/roma/?criterio=rilevanza&pag=1) to get some housing information, creating two dataframes with them, then cluster and compare the results. The second part is about building a hash function, in order to check whether there are duplicates inside [password.txt](https://drive.google.com/file/d/1wTmOU-yqk4qdQYg42AquhzgpNGrRA96d/view) file.

## Script descriptions:
1. **`AMD_HW4.ipynb`** :  
  The scritp with the code of our analysis.
  
2. **`desc_files`**:  
  This folder contains descriptions that we collected from announcements in Immobiliare.it (each desc_idx.txt is the           corresponds to the description inside an annpouncement). We used these files to build the second dataframe and the word cloud.

3.  **`matrices`**:  
This folder contains the first dataframe, as a dataframe in a .csv file and as a matrix in a .txt file. The same applies to the second dataframe (stored in *matrix_2.zip*, due to its large dimension). This folder contains also *vocabulary.txt*, where we put the dictionary we created to build the second dataframe.
