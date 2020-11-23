# Similar Products
### Recommending similar apparel products in e-commerce using product description and images.

The aim is to build a recommender system for the e-commerce industry in particular apparel industry.

We have used both image based similarity and text based similarity to generate a powerful recommender system.

### Approach
We have two approaches here:

1. Content based recommendation: As its name suggests, we do content based recommendation, means its based on tittle text, Description text and images.

2. Collobarative filtering based recommendation: These recommendations are done based on the behaviour of the user.

Since Amazon doesn't provide users data, so we are not going to do collobarative filtering. Instead we use content based.

### Plan of Attack
The steps followed during the project were:
1. Data Aquisition
2. Data Cleaning
3. Text Processing using NLP
4. Text based product recommendation using Bag of Words, Term frequency-Inverse document frequency (TF-IDF), Word2Vec, Avg W2V, TF-IDF weighted W2V techniques.
5. Image based product recommendation using CNN deep learning techniques.
