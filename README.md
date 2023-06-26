# Big-Data-Project
Document classification on the arXiv PDF dataset, using different models. 
## Part 1: Preprocessing and PDF Feature Extraction
### Preprocessing
remove_category: Removes the category of the pdf from the pdf. <br>
tokenize_text: Tokenizes the sentences. Keep words that appear more than twice in the whole pdf.  <br>
cleanText: Performs lemmatization of the input. <br>
### PDF Feature Extraction
350 pdfs were samples from each category.
From each one, 500 features were extracted using *TfidfVectorizer* function from *sklearn*.
## Part 2
