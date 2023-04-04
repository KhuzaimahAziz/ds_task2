# ds_task2

In this task I had to make an algorithm that can answer User question based on the data in the dataframe.

## Algorithms Used:

TfidfVectorizer, Cosine-Similarity, GPT-3

## Methodology

Firstly I used vectorizer to convert the data in dataframe and question into vectors. After that cosine similarity is calculated based on the user question and the data after that one row is generated from the algorithm that will have the highest similarity score.

Then I passed this row as a prompt to the GPT api that can generate the answer to the user question.

## Furtherenhancment

Further modification can be done by taking keywords from the most similar row, cleaning it and then passing it to chat gpt to enhance results.
