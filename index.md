# Play Store Review Analysis Tool Documentation

## Requiremets  
>- **Python 3 with pip**
>- **Python libraries of (Jupyter, IPython, Numpy and Pandas)**
>- **Tableau Public Profile with *Tableau Desktop* installed**  

## Introduction  
To get an introduction of the Tools and how they are meant to be used, please first refere to [User Documentation](https://github.com/cd-shubhamkumar/Play-Store-Review-Analysis-Tool/raw/master/User%20Documentation.pdf). This tool is a User Review Analysis tool. The main aim of the of these tools are to get an overall user sentiment with **major user pain points**. The toolset consists of two main tools:  
> ***1. User Sentiment Analysis Dashboard (A Tableau Dashboard)***  
> ***2. Back Validation Tool (A Colab Notebook)***  

These tools are meant to work together. More info can be found in  [User Documentation](https://github.com/cd-shubhamkumar/Play-Store-Review-Analysis-Tool/raw/master/User%20Documentation.pdf) about these tools. The main aim of this documentation is to show how these tools can be built and manipulated.  

## How to Re-Build these Tools  
To rebuild this tool please follow the following steps:  
>**Step 1:** Download the Play Store User Review Data (Please ask for Colab Notebbok to download data via Slack or Email. The Colab Notebook is not included in this repo).  

>**Step 2:** Download this [Repository](https://github.com/cd-shubhamkumar/Play-Store-Review-Analysis-Tool/archive/master.zip) and unzip the file.  

>**Step 3:** Replace [frizza_reviews.csv](https://raw.githubusercontent.com/cd-shubhamkumar/Play-Store-Review-Analysis-Tool/master/frizza_reviews.csv) and [apps.csv](https://raw.githubusercontent.com/cd-shubhamkumar/Play-Store-Review-Analysis-Tool/master/apps.csv) file in the folder by newly downloaded data from Colab Notebook in Step 1 (These files would be automatically be generated with correct name from Colab Notebook, so just replace the files in the folder with new updated data).  

>**Step 4:** Run **[[Tableau_01]Frizza_Final.ipynb](https://github.com/cd-shubhamkumar/Play-Store-Review-Analysis-Tool/blob/master/%5BTableau_01%5DFrizza_Final.ipynb)** and **[[Tableau02]Token_classifier.ipynb](https://github.com/cd-shubhamkumar/Play-Store-Review-Analysis-Tool/blob/master/%5BTableau02%5DToken_classifier.ipynb)** in same order. These files would automatically generate and save the data inside ***for_tableau*** folder.  

>**Step 5:** Open the ***User Sentiment Analysis Dashboard*** and chnage the data with data generated in Step 4 (The folder ***for_tableau*** contains five csv files. Each for one rating. So, replace the data accordingly in ***User Sentiment Analysis Dashboard***).  

>**Step 6:** Run **[[To GitHub]Back_Validation_Tool_Data_Shaping.ipynb](https://github.com/cd-shubhamkumar/Play-Store-Review-Analysis-Tool/blob/master/%5BTo%20GitHub%5DBack_Validation_Tool_Data_Shaping.ipynb)** notebook. It will save the data for ***Back Validation Tool*** inside ***back_validation_tool_github*** folder. This data is required to be hosted on a GitHub repo or Cloud Storage Service. And the link to acces the data has to changed inside ***Back Validation Tool***.  

After Completing these six steps both the tools would be ready to use.
 
 
                    

                    

***NOTE:*** Link for ***User Sentiment Analysis Dashboard*** and ***Back Validation Tool*** would be shared via email or Slack.
