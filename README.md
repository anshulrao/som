# Self-Organizing Maps
[Please refer to the report [here](https://github.com/anshulrao/som/blob/master/files/Report.pdf) for a more thorough dive into the project.]


1. [DEMO](https://github.com/anshulrao/som/blob/master/notebooks/DEMO.ipynb): A simple implementation of the algorithm in Python. I randomly generated 1k 
colors and produced a 3x3 SOM map for it. It is a minimalistic implementation of the algorithm from scratch in Python that helps build the 
understanding of how it actually works.
2. [Topic Modeling using SOM](https://github.com/anshulrao/som/blob/master/notebooks/Topic%20Modeling%20using%20SOM.ipynb): I tried to cluster the textual data
scraped from Stocktwits using SOM. The library used was MiniSom and I first cleaned the data, then used TF-IDF to convert them into numerical vectors and finally
used these vectors to train SOM model for 40k iterations.
3. [Python Libraries](https://github.com/anshulrao/som/blob/master/notebooks/minisom%20and%20sklearn-som.ipynb): For the same input that I generated and used in DEMO, I used
SOM libraries like MiniSom and sklearn-som to generate maps/lattics for them. 
