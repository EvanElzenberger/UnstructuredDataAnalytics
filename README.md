# Unstructured Data Analytics
Course Description: Explores the concepts and management of big data projects, text analytics, natural language processing, social network analysis, and social media analytics. Focuses on using social data and combining disparate data sources for business decisions.

Learning Outcomes:
- Identify and list terminology and considerations for big data projects.
- Perform text analysis on textual data.
- Perform network analysis on appropriate data.
- Implement social media analytics using appropriate tools.
- Recognize the benefits of combining disparate data sources for business decisions.

Software:
- IBM SPSS Modeler
- Microsoft Excel
- Other open-source software
- NodeXL


IBM SPSS Modeler Exam Grade: 92%
- The provided exam focuses on performing text analytics using IBM SPSS Modeler on Airbnb reviews for listings in Denver. The goal is to extract insights from textual reviews and understand guests' experiences with Airbnb hosts. The exam covers various aspects of text mining, concept modeling, category modeling, text link analysis, and linguistic-based categorization. Exam used old dataset of reviews between August 2018 to December 2019.

Data: Provided by InsideAirBnB.com [Data Set Link](http://insideairbnb.com/get-the-data/)

Exam Highlights:
- The exam emphasizes the importance of understanding Airbnb guests' experiences through textual reviews rather than numerical ratings.
- IBM SPSS Modeler is utilized for text analytics, requiring adjustments in settings to optimize performance.
- The "Opinion(English)" resource template is chosen for accurate analysis, providing predetermined weighting on words and phrases to extract types, concepts, and categories.
- A concept model is built to identify the most frequent concepts in the reviews, with common concepts like excellent, place, location, comfortable, stay, and clean. ![Concept Model](https://user-images.githubusercontent.com/121822843/235010444-2179bbf4-1cc3-42a5-bd4d-fcc5c2411cfe.png)

- The most frequent concept within the "Contextual" type is determined using a distribution graph, revealing the associated terms and their implications.
- The dominating concept type, excluding "Unknown," is identified as <Positive>.
- Text link analysis is conducted, leading to the discovery of multiple patterns, with the second top pattern being <Unknown> & <Positive>.
- Concepts strongly linked with reviewers' positive terms are explored, indicating concepts such as excellent appearing in a significant percentage of documents.
- A new category, "Excellent Stay," is created using concepts from a meaningful cluster, but the categorization is questioned based on the relevance of included concepts.
- Linguistic-based categorization is employed to create meaningful categories, comparing methods like concept inclusion and semantic network.
- Frequency-based categories are generated, considering settings like the minimum records/doc. count and descriptors at concept or type level.
- Manual creation of categories using conditional rules is performed, followed by model generation to include these categories.
- Suggestions for further analysis include revisiting TAP Opinions and Text Link Analysis, incorporating custom categories, and exploring distribution graphs to understand category recognition frequencies.
