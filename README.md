# Unstructured Data Analytics

## Course Description:
Explores the concepts and management of big data projects, text analytics, natural language processing, social network analysis, and social media analytics. Focuses on using social data and combining disparate data sources for business decisions.

## Skills Learned:
- Identify and list terminology and considerations for big data projects.
- Perform sentiment analysis on textual data.
- Perform network analysis on categorized data.
- Implement social media analytics using appropriate tools.
- Recognize the benefits of combining disparate data sources for business decisions.

## Software:
- IBM SPSS Modeler
- Microsoft Excel with NodeXL developed by Social Media Research Foundation
- Open-source software [VADER](https://github.com/cjhutto/vaderSentiment)

## IBM SPSS Modeler Exam Grade: 92%
The provided exam focuses on performing text analytics using IBM SPSS Modeler on Airbnb reviews for listings in Denver. The goal is to extract insights from textual reviews and understand guests' experiences with Airbnb hosts. The exam covers various aspects of text mining, concept modeling, category modeling, text link analysis, and linguistic-based categorization. Exam used old dataset of reviews between August 2018 to December 2019.

### Data Source: InsideAirBnB.com [Data Set Link](http://insideairbnb.com/get-the-data/)

### Exam Highlights:
- The exam emphasizes the importance of understanding Airbnb guests' experiences through textual reviews rather than numerical ratings.
- IBM SPSS Modeler is utilized for text analytics, requiring adjustments in settings to optimize performance.
- The "Opinion(English)" resource template is chosen for accurate analysis, providing predetermined weighting on words and phrases to extract types, concepts, and categories.
- A concept model is built to identify the most frequent concepts in the reviews, with common concepts like excellent, place, location, comfortable, stay, and clean. 

![Concept Model](https://user-images.githubusercontent.com/121822843/235010444-2179bbf4-1cc3-42a5-bd4d-fcc5c2411cfe.png)

- The most frequent concept within the "Contextual" type is determined using a distribution graph, revealing the associated terms and their implications.

![Concept Model Dist 1](https://user-images.githubusercontent.com/121822843/235010960-a637b26a-ebb7-4c9e-9149-b38e56e30e21.png) 

- Text link analysis is conducted, leading to the discovery of multiple patterns. Concepts strongly linked with reviewers' positive terms are explored, indicating concepts such as excellent appearing in a significant percentage of documents.
- A new category, "Excellent Stay," is created using concepts from a meaningful cluster, but the categorization is questioned based on the relevance of included concepts.

![Pattern Recognition](https://user-images.githubusercontent.com/121822843/235011735-fc71cade-56ce-4aaf-839d-34eb57369aae.png)

- Three types of categorization are completed with manual rule edits such as, the term "bed" can be associated with either a positive OR negative qualifier. Since the category is "Excellent stay", it indicates a combination of an entity (related to stay) and a qualifier (related to excellent. Therefore, a rule with an "and" operator would be more appropriate. For example bed & excellent 
  - Linguistic-based categorization is employed to create meaningful categories, comparing methods like concept inclusion and semantic network.
  - Frequency-based categories are generated, considering settings like the minimum records/doc. count and descriptors at concept or

## NodeXL Exam Grade: 90%
This exam focuses on conducting a Social Network Analysis (SNA) of the Facebook fan pages of two NFL teams, Denver Broncos and Carolina Panthers. The goal is to analyze the fan networks and their interactions. The analysis aims to identify the differences between the two teams' fan networks, determine the most active and important fans, and provide suggestions for improving sports teams' social media campaigns based on the SNA findings.

### Data Source: Colorado [Broncos Facebook Fan-page](https://www.facebook.com/Broncos) & Carolina [Panthers Facebook Fan-page](https://www.facebook.com/CarolinaPanthers)

### Exam Highlights: 
- The analysis begins with data preparation and summary, including merging duplicate edges and calculating various metrics such as unique edges, unique vertices, graph density, and edge weight range. Data was not normalized, rusulting in difficulty comparing absolute values.
- Network graphs and statistics are generated using the Harel-Koren Fast Multiscale method, highlighting the differences in the fan networks (fan groups) of the two teams. Broncos shown first have 58 groups and Panthers shown second have 16 groups. Broncos data had almost twice the number of posts, which likely reached a wider range of people and thus the actors have a wider range of sub relations. Panthers have less groups, but more connected

![Harel-Koren Fast Multiscale Broncos](https://user-images.githubusercontent.com/121822843/235029559-0b973398-1e99-4c27-9d5a-a298e0c83d21.png)
![Harel-Koren Fast Multiscale Panthers](https://user-images.githubusercontent.com/121822843/235029563-48042ec0-be7d-4515-91b3-86325f1b9c82.png)

- Network metrics like Betweenness Centrality, Closeness Centrality, and Eigenvector Centrality are calculated and visualized through histograms.
- Dynamic filters are applied to explore networks with different edge weight thresholds.
- Sub-networks are created by filtering the networks based on edge weight, and their metrics are summarized.
- Visualizations of the sub-networks are generated, showcasing important fans based on centrality metrics.
- Broncos Top Fans (Last names removed for privacy)
  - Renee H.
  - Tammy W.
  - Jayden S.
  - James J.
  - Benjamin B.
  - Joe A.

![Sub-network Broncos](https://user-images.githubusercontent.com/121822843/235030897-dbaa0a56-4d51-4a8b-b712-3c3ecf988d21.png)

- Panthers Top Fans (Last names removed for privacy)
  - Lisa L.
  - Christopher T.
  - Andrew L.
  - Donna S.
  - Anna S.
  - Carolina Panthers (Facebook-page Administrator)
  - Rachit D.
  - Bobby G.

![Sub-network Panthers](https://user-images.githubusercontent.com/121822843/235030900-6f57e0f4-a1c8-4761-bf3c-ec7f90d3e226.png)

- Strategies for enhancing the social media campaigns are discussed, including engaging important fans and identifying potential spammers.
- Insights and recommendations are provided for sports teams' social media campaigns based on the overall analysis.
