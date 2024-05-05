<p> A simple Movie recommender system which recommends 5 movies similiar to the movie we provide </p>
<p> We use the 5000 movies data from tmdb </p>
<p> First we do the data preprocessing using the libraries numpy and pandas, data cleaning includes

  - Filtering the important columns and merging two data files given
  - Merging columns to create a single tags colums which holds most important words
  - Correcting the formatting of columns
  - Removing missing and duplicate data

</p>
<p> After data preprocessing we do vectorization (changing the tags to vectors) </p>
<p> Using cosine similarity to create a similarity matrix between all the movies and using this similarity matrix to calculate the 5 most similiar movies to a given movie </p>
