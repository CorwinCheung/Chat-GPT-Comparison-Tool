# ChatGPT Comparison Tool Using the OpenAI API, TF-IDF vectorization, and cosine similarity

This comparison tool works by taking an input of the question asked on the test and the student answer. <br>
It then queries the OpenAI API text completition GPT 3.5 model, 3 times with different temperatures with the question and the clause "X" number of words, <br>
so it generates a response similar to the length of the student's. Then it uses the TF-IDF(term frequency-inverse document frequency) vectors and cosine similarity to <br>
compute the similarity of the students answers to the three GPT 3.5 model's outputs. <br>
Email <a href = "mailto: corwintcheung@gmail.com">Corwin Cheung</a> with any questions or feedback! <br>
