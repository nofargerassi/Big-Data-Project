## Big-Data-Project
Document classification on the arXiv PDF dataset, using different models. 
### Part 1: Preprocessing and PDF Feature Extraction
#### Preprocessing
remove_category: Removes the category of the pdf from the pdf. <br>
tokenize_text: Tokenizes the sentences. Keep words that appear more than twice in the whole pdf.  <br>
cleanText: Performs lemmatization of the input. <br>
#### PDF Feature Extraction
350 pdfs were samples from each category. <br>
From each one, 500 features were extracted using *TfidfVectorizer* function from *sklearn*.<br>
### Part 2: Model Creation and Evaluation
Splitting the features data into train (70%) and test (30%) <br>
Fitting three models: Logistic Regression, Multilayer Perceptron and Naive Bayes <br>
Presenting and discussing the results.

### How we ran this code:
We downloaded the 2003 file from the cluster onto our own laptop computer.
Everything was done locally on our own computer. Results can be reproduced by having the 2003 folder locally and then changing the directory accordingly.


