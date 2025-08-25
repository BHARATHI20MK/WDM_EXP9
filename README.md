### EX9 Preprocessing on Twitter Data using Rapidminer
### DATE: 24-08-2025
### AIM: To implement preprocessing technique on Twitter Data using Rapidminer
### Description: 
<div align = "justify">
RapidMiner provides data mining and machine learning procedures including: data loading and transformation (ETL), data preprocessing and visualization, 
predictive analytics and statistical modeling, evaluation, and deployment. RapidMiner is written in the Java programming language. 
RapidMiner provides a GUI to design and execute analytical workflows. Those workflows are called “Processes” in RapidMiner and they consist of multiple “Operators”. 
Each operator performs a single task within the process, and the output of each operator forms the input of the next one. Alternatively, the engine can be called from 
other programs or used as an API. Individual functions can be called from the command line. 
RapidMiner provides learning schemes, models and algorithms and can be extended using R and Python scripts.

### Procedure:
1) ***Import Twitter data:*** Import the Twitter data into RapidMiner. You can do this by selecting the appropriate
data source operator, such as "Read Excel" or "Read CSV," and specifying the location of your Twitter data
file.
2) ***Preprocess data:*** Preprocess the imported data to clean and prepare it for text processing. Use the following
operators for preprocessing:
    <p>a. Tokenize: Split the text into individual words or tokens.
    <p>b. Transform Cases: Convert the text to lowercase or uppercase to ensure consistency.
    <p>c. Remove Stopwords: Remove common words that do not provide much meaningful information.
    <p>d. Remove Special Characters: Eliminate special characters, such as punctuation marks or symbols.
    <p>e. Remove Numbers: Exclude numeric values from the text.
3) ***Stemming:*** Apply stemming to reduce words to their root forms. You can use operators like "Stem (Porter)"
for this purpose.


### Output:
<img width="1367" height="722" alt="Screenshot 2025-08-25 141042" src="https://github.com/user-attachments/assets/dd3af160-532b-41e8-9b33-a043d6ab66cf" />
<img width="1423" height="678" alt="Screenshot 2025-08-25 141102" src="https://github.com/user-attachments/assets/d28de24d-98ab-4d98-af8c-c7b8fcddc4d2" />
<img width="1726" height="822" alt="Screenshot 2025-08-25 141118" src="https://github.com/user-attachments/assets/69f04e4d-80f3-40f2-890f-1362ff4e4801" />

### Result:
Thus the experiment to implement preprocessing technique on Twitter Data using Rapidminer is done successfully.
