# Topic-modeling-on-COVID-19-data

## 1. Motivation
Since the outbreak of the novel coronavirus (COVID-19), it has become a significant and urgent threat to global health. Within months of the outbreak, thousands of research papers relating to its effects, risks and treatments have been published. The pace at which research is carried out is increasing at fast rate. But it brings with it a new problem for someone wanting to look for answers. This generates an opportunity for us, data scientists, to showcase our expertise by developing data mining tools that can help the medical community find answers to highly important scientific questions.

## 2. Description
The repository consist of notebooks for data loading and processing, training LDA models using sklearn and gensim, visualizing topics generated and also carry out further analysis.

## 3. Features

- Load JSON data into pandas dataframe
- Process and clean text data and merge it into 1 column
- Train gensim based LDA to find optimal topics
- Create a dictionary of documents related to risks of COVID-19 
- Evaluate which topics did our trained LDA model detected it in. 
- Once those topics were identified, documents occurring under those topics were our primary focus of research
- We even went a step ahead and used cosine similarity metric to find k nearest neighbors. 
- Finally, we visualized our findings using pyLDAvis library and also building our own visualization with the help of t-SNE and bookeh.

## 4. Owner

Piyush Anasta Rumao

## 5. Contributors

Piyush Anasta Rumao

## 6. Version

0.1

## 7. Technology
- Python 3.6+

