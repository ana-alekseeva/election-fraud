# Detecting Fraud in Russian Federal Duma Elections

Final project for Data Literacy course in Winter semester 2021/2022 at University of Tübingen.

# Summary
The main hypothesis of the project is that the results of the latest Federal Duma election held in 2021 in Russia were partially falsified by ballot box stuffing and
"drawing" the final results in the official reports at polling stations. To detect the aforementioned two kinds of fraud, I have examined the distribution of vote-shares, their relationship with turnout, and compared the results with the fair 2021 parliamentary election in Germany. Moreover, I have estimated the number of anomalous integer numbers in each region. As a result of this study, the main hypothesis was corroborated.

# Data
1. Polling station data for Russian Federal elections: Dmitry Kobak’s repository (https://github.com/dkobak/elections/blob/master/data/2021.csv.zip). 96,325 polling stations, 109,204,662 registered voters. Only traditional voting was included in the analysis. 
2. Polling station data for German Federal elections: the Federal Returning Officer’s website (https://www.bundeswahlleiter.de/en/bundestagswahlen/2021/ergebnisse/weitere-ergebnisse.html). 94668 polling stations, including voting by post, 61,181,072 eligible voters.The results from postal voting were excluded from the analysis as the dataset did
not allow matching the polling station and the voters used post, and consequently, calculate turnout for them correctly.

# Setup

No installation needed to run this project. Google Colab is more convinient in terms of installation of geopandas library.

Run the Jupyter notebooks in the following order:
1. Data_Preparation_Russia.ipynb
2. Data_Preparation_Germany.ipynb
3. Comparison_Rus_Germany.ipynb
4. Fraud_Detection_Russia.ipynb




[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
