# Data Scientist

#### Technical Skills: Python, SQL, R, MongoDB, Machine Learning, (Knowledge Graph, Matplotlib, KNN, KDD Dataset, Tree Model, K-Neighbors Classifier Model, NLP, Knowledge Graph) | Microsoft Azure| Databricks | PHP 

# Education							       		
M.S., Data Science	| George Washington University (_Expected_ _May 2025_)	 			        		
B.tech., Information Technology | Maharaja Agrasen Institute of Technology (_May 2022_)

# Projects
## Intrusion detection system (_November 2021_) 
### Project overview: 
- IDS stands for Intrusion Detection System. It helps in monitoring network traffic and detects unwanted intrusions to secure our system from any kind of attacks or malwares. I basically used KNN datasets and NIDS as an algorithm to find the best possible way to get our results. I have used different models like Decision Tree Model, Gaussian Naïve Baye Model, K-Neighbors Classifier Model, Logistic Regression model. To build an algorithm for processing the data and network and monitor it for the detection of intrusion. In our project I found that the *KNN algorithm is fastest* and that's why we adopted it.

### Tools: 
**A. KDD’99 CUP DATASET**
- It is based on the data collected during DARPA's IDS evaluation programme in 1998.
- DARPA 98 consists of around 4 gigabytes of compressed raw tcp dump data from 7 weeks of network activity, which may be processed into approximately 5 million connection records, each with approximately 100 bytes. It provides a training dataset of roughly 4,900,000 single connection vectors, each of which has 41 characteristics and is labelled as either normal or attack, with only one attack type. Denial of service (dos), user to root (u2r), remote to local (r2l), and probing assaults are the four types of attacks that may be found in a military network.

**B. DECISION TREE**
  
**C. ATTRIBUTE SELECTION MEASURES**

1. Entropy
    
2. INFORMATION GAIN
    
3. GINI INDEX
    
4. GAIN RATIO
    
5. CHI-SQUARE
    
### Comparison between accuracy
1. Naïve bayes model Figure and Decision tree model
![](/Images/Picture4.png)
2. Logistic regression model and K-Neighbor model
![](/Images/Picture5.png)

### Evaluation and results
![](/Images/Screenshot%202023-10-04%20at%206.56.43%E2%80%AFPM.png)



## Searching for relevant text (_April 2022_)
# Project overview:
- This project is dedicated to addressing this challenge by proposing a model that streamlines the process of discovering accurate and pertinent answers to questions. The model harnesses the power of Natural Language Processing (NLP) algorithms and leverages knowledge graphs to accomplish this objective efficiently.
- **Data Acquisition**:
To demonstrate the versatility of our proposed method, we focused on textbooks from subjects like geography and history, sourced primarily from Kaggle. These educational texts, totaling around 500 pages for each subject, were selected for practical illustration. Initially available in unstructured text format, we moved on to data preprocessing to render it usable. Our next step involves storing quintets for each phrase, now conveniently organized within a dataframe.
- **Knowledge Graph Creation**:
A knowledge graph is a data display method that integrates information into an ontology, enabling the system to derive new insights. We use it due to its flexibility, which allows us to map our JSON file dynamically onto the graph. The graph visualization is generated using the Python NetworkX module, utilizing each quintet's subject, object, and predicate to construct a graph edge.
- **Algorithm Implementation Setup**:
We implemented the algorithms using the following hardware setup, although other hardware can also be used. The Python programming was performed on a 64-bit Windows 10 operating system, with essential libraries including NumPy and Pandas. Matplotlib, SciPy, Scikit-Learn, PyTorch, Seaborn,Plotly, TensorFlow, Keras, and Seaborn were used in the implementation.
- **The Dataset**:
Our experiment utilizes the SQUAD dataset, specifically designed for factoid question-answering. This dataset comprises a diverse collection of articles covering various subjects and topics, enabling comprehensive analysis and testing across multiple challenges.

- **Result**
When evaluated across 422 articles from the SQUAD dataset, our passage retrieval accuracy reached 69.69%. This accuracy notably improved to 77.49% after the removal of stop words and the application of Porter Stemmer. Furthermore, in 94.23% of passage retrievals, the relevant paragraph appeared within the top three results.

To enhance the precision of our approach, the following steps can be considered:

1. Utilizing user input for more accurate responses.
2. Extracting contextual data in the form of entities to address complex queries.
3. Employing advanced search algorithms for timely and accurate responses.
4. Leveraging collected data to train a neural network, enhancing system accuracy.
5. Upon achieving specific developmental milestones, deploying the system in educational settings to assist students with inquiries and specific information retrieval.


## Balance of payment statistics Analysis (_September 2023_) ongoing.
### Project overview
- This research project aims to conduct a comprehensive global analysis of key economic indicators, such as Capital Accounts, Net Lending/Borrowing, and Balance on Goods, Services, and Income. Utlizing a dataset that encompasses all the countries and spans from 2015 to 2020, the study will explore trends, correlations, and impacts of these indicators on economic development. Four SMART questions have been formulated to guide the research, focusing on changes over time, correlations between different accounts, and global economic stability. The findings of this research could offer valuable insights for policymakers, economists, and researchers interested in global economic trends and their implications.
- **Questions** :
1. Trade balance:
- What is the trade balance (exports minus imports) for a specific country over a particular time period?
- Is there a significant correla1on between Net Lending/Borrowing and Capital Accounts across countries for the years 2015-2020?

2. Current Account Analysis:
- What is the current account balance and what components contribute to it (e.g., trade balance, income, transfers)?
- Is a country running a current account surplus or deficit? Also what are the implica1ons of this?
  
3. Economic Indicators :
- Are there relationships between balance of payments indicators (e.g., trade balance, FDI) and other economic indicators like GDP growth, inflation, or employment rates?
  
4. Comparative Analysis:
- How does the balance of payments of one country compare to that of other countries in the same region or with similar economic characteristics?
- Is there a measurable decrease in Current Account debit in Goods and Services globally from 2015 to 2020?


# Work Experience
## Software Engineer Trainee @ Protiviti (_June 2022 - July 2023_)
- Designed a robust machine learning model on Azure Databricks to analyze opportunities. Employed Python and the H2O library to create an accurate model that forecasts the probability of client engagement with specific opportunities. Achieved 95% accuracy rate by systematically selecting the best-performing machine learning algorithm.
-	Utilized scikit-learn to enhance the model and applied matplotlib for insightful visualizations, aiding in precise opportunity assessment and strategic decision-making. Additionally, I played a pivotal role in the initial stages of the project by performing data ingestion, efficiently extracting data from Salesforce using PySpark. Subsequently, I executed a comprehensive data integration process to harmonize diverse datasets, ensuring that the data was well-prepared and structured for subsequent modeling and analysis.
-	Engineered a tailored calendar system within Salesforce using Apex, streamlining meeting accessibility through Outlook. Categorized meetings into priority and general segments, elevating scheduling efficiency. 
-	I assisted the team by getting data from Azure Blob Storage, cleaning it, and using PySpark on Databricks. Afterward, I rewrote the CSV file back to Azure Blob Storage and aided in uploading this data to pipelines.



